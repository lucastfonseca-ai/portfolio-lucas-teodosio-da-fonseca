# 🚦 Sistema Inteligente de Otimização de Semáforos

## 📝 Descrição do Projeto
Este projeto propõe um sistema inteligente para **otimização de semáforos em tempo real**, com o objetivo de reduzir congestionamentos urbanos e melhorar a fluidez do tráfego em cidades inteligentes.
A solução utiliza dados provenientes de sensores (como câmeras, laços indutivos ou APIs de tráfego) para analisar o fluxo de veículos em diferentes vias. Com base nessas informações, o sistema toma decisões dinâmicas sobre o tempo de abertura e fechamento dos semáforos, priorizando vias mais congestionadas e evitando gargalos.
O projeto foi desenvolvido como parte da disciplina de **Engenharia de Soluções Lógicas**, com foco na construção de algoritmos baseados em **fluxogramas e pseudocódigo estruturado**, simulando a lógica de sistemas reais de controle urbano.

📄 *Os arquivos em PDF anexados apresentam o fluxograma e o pseudocódigo detalhado da solução.*

---

## ⚙️ Funcionamento do Sistema

O sistema segue três etapas principais:

1. **Entrada de Dados**
   - Quantidade de veículos por via
   - Tempo de espera atual
   - Estado atual do semáforo

2. **Processamento**
   - Cálculo do nível de congestionamento
   - Comparação entre vias concorrentes
   - Aplicação de regras condicionais para priorização

3. **Decisão**
   - Ajuste do tempo do sinal verde
   - Alternância entre vias
   - Tratamento de situações críticas (ex: congestionamento extremo)

---

## 🧠 Estrutura Lógica

### 🔷 Fluxograma
O fluxograma representa visualmente:
- Início e fim do processo
- Coleta de dados de tráfego
- Processamento das informações
- Múltiplas decisões condicionais (≥ 3)
- Ajuste dinâmico dos semáforos

### 🔷 Pseudocódigo (Portugol)
O pseudocódigo implementa:
- Estruturas de repetição (`enquanto`)
- Estruturas condicionais (`se`, `senão`)
- Variáveis para controle de fluxo e tempo
- Tratamento de erros para entradas inválidas

---

## 🧪 Testes e Validação

O sistema foi validado com três cenários distintos:

### ✅ Cenário A — Entrada Ideal
- Fluxo moderado e equilibrado entre vias
- O sistema distribui tempos de forma proporcional
- Resultado: tráfego fluido

### ⚠️ Cenário B — Limite/Borda
- Uma via com fluxo extremamente alto e outra com fluxo baixo
- O sistema prioriza a via congestionada com tempo maior de sinal verde
- Resultado: redução do acúmulo crítico

### ❌ Cenário C — Erro/Exceção
- Entrada inválida (ex: número negativo de veículos ou ausência de dados)
- O sistema identifica erro e aplica valores padrão ou ignora leitura
- Resultado: prevenção de falhas no controle do semáforo

---

## 🚀 Tecnologias e Conceitos Utilizados

* **Modelagem:** Fluxogramas
* **Lógica:** Pseudocódigo (Portugol)
* **Conceitos:**
  - Estruturas condicionais
  - Estruturas de repetição
  - Tomada de decisão baseada em dados
  - Sistemas em tempo real
  - Cidades inteligentes

---

## 📊 Resultados e Aprendizados

- 📉 **Redução de congestionamentos** em cenários simulados
- 🔁 **Compreensão prática de algoritmos iterativos e condicionais**
- 🧩 **Capacidade de modelar problemas reais em lógica computacional**
- ⚙️ **Importância do tratamento de exceções em sistemas críticos**

---
[Voltar ao início](https://github.com/lucastfonseca-ai/portifolio-lucas-teodosio-da-fonseca/tree/main)
