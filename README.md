# **Projeto: Análise de Parada Cardíaca e Previsão de Crédito**

## **Objetivo**
O objetivo deste projeto é analisar o histórico de clientes e prever se um novo cliente pode ter crédito aprovado com base na probabilidade de parada cardíaca e outros fatores. A análise será feita utilizando Machine Learning para prever riscos e apoiar a decisão de concessão de crédito.

## **Tecnologias Utilizadas**
- **Linguagem**: Python  
- **Bibliotecas**: pandas, numpy, scikit-learn, Flask, matplotlib, seaborn  

## **Fases do Projeto**

### **1. Definição do Problema**
- Entendimento do impacto da parada cardíaca na concessão de crédito  
- Coleta de dados históricos de clientes (idade, histórico médico, renda, etc.)  
- Formulação do problema como uma tarefa de classificação binária  

### **2. Preparação dos Dados**
- Tratamento de valores ausentes (Missing Values)  
- Seleção de variáveis relevantes (Feature Selection)  
- Codificação de variáveis categóricas  
- Normalização/Escalonamento dos dados (se necessário)  

### **3. Criação do Modelo de Machine Learning**
- Uso do algoritmo **Random Forest** para classificação  
- Treinamento e ajuste de hiperparâmetros  
- Avaliação de métricas de desempenho:  
  - **Acurácia**  
  - **Precisão, Recall e F1-Score**  
  - **Matriz de Confusão**  
  - **Curva ROC-AUC**  

### **4. Colocando em Produção**
- Construção de uma API usando **Flask**  
- Deploy do modelo treinado para receber novos clientes e prever aprovação de crédito  
- Testes da API e validação da resposta do modelo  

## **Próximos Passos**
- Melhorar o modelo com novas features  
- Testar outros algoritmos além do Random Forest  
- Criar um dashboard para visualização das previsões  
