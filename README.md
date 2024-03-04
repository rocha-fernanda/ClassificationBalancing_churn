# 🚀 Antecipação de Churn Bancário com Aprendizado de Máquina e Técnicas de Balanceamento 📊

## Desenvolvido por: Fernanda Paula Rocha

### Introdução 🌐

Com a intensificação da concorrência no setor bancário, a retenção de clientes torna-se uma prioridade estratégica. O churn, ou perda de clientes, pode impactar negativamente a estabilidade e o crescimento do banco. Neste projeto, utilizo técnicas avançadas de análise de dados e aprendizado de máquina para antecipar o churn bancário, explorando um conjunto de dados abrangente com diversos atributos relacionados aos clientes.

### Modelos de Aprendizado de Máquina 🤖

Emprego uma abordagem abrangente com cinco modelos de aprendizado de máquina:

1. **Decision Tree Classifier:**
   - *Justificativa:* Mapeia relações complexas, sendo eficaz na identificação de padrões não lineares em problemas de churn.

2. **Gaussian Naive Bayes:**
   - *Justificativa:* Eficiente na manipulação de dados de alta dimensionalidade, é escolhido quando há independência condicional entre os atributos.

3. **HistGradient Boosting Classifier:**
   - *Justificativa:* Uma variação otimizada do Gradient Boosting, com construção eficiente de árvores de decisão, resultando em treinamento mais rápido.

4. **Logistic Regression:**
   - *Justificativa:* Clássica para classificação binária, é escolhida pela interpretabilidade e eficácia na modelagem de relações lineares entre variáveis.

5. **Random Forest Classifier:**
   - *Justificativa:* Extensão das árvores de decisão, lida com sobreajuste e é robusta em dados não lineares.

### Técnicas de Balanceamento ⚖️

Considerando o desequilíbrio no conjunto de dados, aplico quatro técnicas de oversampling:

1. **Desbalanceado:**
   - Conjunto de dados original.

2. **SMOTE (Synthetic Minority Over-sampling Technique):**
   - Gera exemplos sintéticos da classe minoritária para equilibrar as classes.

3. **ADASYN (Adaptive Synthetic Sampling):**
   - Similar ao SMOTE, mas com uma abordagem adaptativa, gerando exemplos próximos aos pontos de fronteira.

4. **SMOTETomek:**
   - Combinação de SMOTE com remoção de exemplos Tomek, visando equilibrar as classes e remover ambiguidades na fronteira de decisão.

Essa abordagem busca avaliar a influência do desequilíbrio de classes nos resultados dos modelos, proporcionando insights sobre a eficácia dessas abordagens na previsão de churn bancário. 

Este projeto visa não apenas antecipar a perda de clientes, mas também entender como diferentes técnicas de aprendizado de máquina e balanceamento de dados impactam a eficácia da previsão de churn no contexto bancário. 🚀💼
