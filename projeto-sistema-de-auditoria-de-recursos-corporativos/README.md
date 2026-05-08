# 🏢 Auditoria de Orçamentos Corporativos (Python)
 
[![Python Version](https://img.shields.io/badge/python-3.x-blue.svg)](https://www.python.org/)
[![Status](https://img.shields.io/badge/status-concluído-brightgreen.svg)]()
 
## 📖 Sobre o Projeto
Este projeto foi desenvolvido como parte da disciplina de Programação de Computadores do curso de Engenharia de Software. O objetivo do script é processar e calcular o orçamento de uma estrutura organizacional complexa (dicionários aninhados) de uma multinacional, aplicando regras de negócio dinâmicas e auditoria de execução.

A solução foi arquitetada utilizando conceitos avançados de Python para garantir flexibilidade, performance e rastreabilidade.
 
## 🚀 Funcionalidades
- **Cálculo Hierárquico:** Varredura completa da estrutura corporativa, independentemente do nível de profundidade.
- **Filtros Dinâmicos:** Capacidade de ignorar setores específicos e todos os seus subsetores na hora do cálculo financeiro.
- **Conversão de Câmbio:** Suporte a parâmetros opcionais para conversão de moedas em tempo de execução.
- **Sistema de Auditoria:** Monitoramento automatizado de tempo de execução e registro (logging) dos parâmetros utilizados na transação financeira.
 
## 🛠️ Tecnologias e Conceitos Aplicados
Este projeto foi construído utilizando Python puro (Standard Library), com foco nos seguintes paradigmas e recursos:
* **Funções Recursivas (Recursion):** Utilizadas para a navegação na árvore de dados (dicionários aninhados).
* **Decorators:** Implementação do `@auditor` para injetar comportamentos de log e cronometragem sem modificar a lógica de negócios.
* **Empacotamento de Argumentos (`*args` e `**kwargs`):** Utilizados tanto no decorator quanto na função principal para permitir a passagem dinâmica de departamentos a serem ignorados e taxas de câmbio.
 
## ⚙️ Como Executar
 
### Pré-requisitos
* Python 3.8 ou superior instalado.
 
### Passo a Passo
1. Clone este repositório:
   ```bash
   git clone [[https://github.com/SeuUsuario/seu-repositorio.git](https://github.com/SeuUsuario/seu-repositorio.git)](https://github.com/lucastfonseca-ai/portfolio-lucas-teodosio-da-fonseca/tree/main)
   ```
2. Acesse a pasta do projeto:
   ```bash
   cd [seu-repositorio](https://github.com/lucastfonseca-ai/portfolio-lucas-teodosio-da-fonseca/tree/main/projeto-sistema-de-auditoria-de-recursos-corporativos)
   ```
3. Execute o script principal:
   ```bash
   Sistema_de_Auditoria_de_Recursos_Corporativos.ipynb
   ```
 
## 🧠 Lógica e Estrutura do Código
Breve explicação de como o código foi organizado:
* `A recursão foi construída pensando na estrutura hierárquica da empresa, onde cada departamento poderia conter outros sub-departamentos em níveis desconhecidos. Para resolver isso, a função interna somar() percorre o dicionário verificando se o valor encontrado é outro dicionário ou um número. Quando encontra um dicionário, a própria função é chamada novamente, permitindo navegar automaticamente por toda a árvore organizacional até chegar aos valores finais dos orçamentos. Também foi adicionada a lógica de *args, permitindo ignorar departamentos específicos durante a soma, deixando o cálculo mais flexível para auditorias financeiras.
O decorator @auditor foi acoplado ao projeto para separar a lógica de auditoria da lógica principal do cálculo. Assim, a função calcular_orcamento() ficou responsável apenas pela soma dos valores, enquanto o decorator intercepta a execução para exibir informações importantes, como nome da empresa, departamentos ignorados, parâmetros financeiros recebidos em **kwargs e o tempo total de execução usando a biblioteca time. O uso de *args e **kwargs dentro do wrapper garantiu que o decorator funcionasse corretamente com qualquer conjunto de parâmetros enviados para a função principal.`.
* **Dados:** Os dados simulados da empresa foram estruturados em um dicionário aninhado, representando a organização interna da empresa Google. O primeiro nível contém a empresa principal, enquanto os níveis seguintes representam departamentos e sub-departamentos, como “Tecnologia”, “Cloud”, “YouTube” e “RH”.`.
 
## 👤 Autor
 
* **Lucas Teodósio da Fonseca** * LinkedIn: www.linkedin.com/in/lucas-teodósio-da-fonseca-2483bb3a3
* E-mail: lucas.tfonseca@outlook.com
 
---
*Projeto acadêmico com foco na aplicação prática de conceitos avançados da linguagem Python.*

---
[Voltar ao início](https://github.com/lucastfonseca-ai/portifolio-lucas-teodosio-da-fonseca/tree/main)
