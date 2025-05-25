# 📊 Projeto de Machine Learning para Previsão de Churn - Beta Bank
**Autora: Marcia Bayardino Weyne**  
**Data: 2025**

---

## 📝 Descrição do Projeto
Este projeto é uma tarefa de Machine Learning para a empresa fictícia **Beta Bank**, com o objetivo de prever clientes que possam deixar o banco. Ele foi desenvolvido como parte do portfólio do curso de Cientista de Dados na Tripleten e demonstra, na prática, o uso de modelos preditivos com foco em churn.

---

## 📑 Tabela de Conteúdo
- [Objetivo](#objetivo)
- [Resultados](#resultados)
- [Ferramentas Utilizadas](#ferramentas-utilizadas)
- [Metodologia](#metodologia)
- [Como Executar o Projeto](#como-executar-o-projeto)
- [Aprendizados](#aprendizados)
- [Contato](#contato)

---

## Objetivo 🏔
Desenvolver um modelo de Machine Learning capaz de prever quais clientes do banco estão propensos a encerrar o contrato, utilizando um conjunto de dados com informações históricas de clientes.

**Métricas principais:**
- F1-score ≥ 0.59
- AUC-ROC ≥ 0.85

---

## Resultados 🏁
🎯 O modelo com melhores resultados foi o **Random Forest com SMOTE**, alcançando:
- F1-score acima de 0.59 no conjunto de teste
- AUC-ROC superior a 0.85

O projeto também implementou uma comparação entre o modelo original e modelos com técnicas de balanceamento de classes (`class_weight` e `SMOTE`), garantindo melhor sensibilidade para a classe minoritária (clientes que saem).

---

## Ferramentas Utilizadas 🧰
- **Caderno de desenvolvimento**: Jupyter Notebook
- **Linguagem de programação**: Python
- **Bibliotecas principais**: pandas • numpy • scikit-learn • imbalanced-learn • matplotlib
- **Ambiente de edição**: VS Code

---

## Metodologia 🔍

### 1. Coleta e Preparação dos Dados
- Leitura de dados CSV
- Remoção de colunas irrelevantes
- Codificação de variáveis categóricas (One-Hot Encoding)
- Normalização com StandardScaler

### 2. Modelagem
- Separação em treino e teste (80/20 com stratify)
- Treinamento com Random Forest
- Aplicação de técnicas de balanceamento: class_weight e SMOTE

### 3. Avaliação
- Métricas: F1-score, Recall, Acurácia e AUC-ROC
- Comparação entre modelos com e sem balanceamento

---

## Como Executar o Projeto 💽

1. **Pré-requisitos**:
   - Python 3.10+
   - Jupyter Notebook
   - Bibliotecas do `requirements.txt`

2. **Instale as dependências**:
```bash
pip install -r requirements.txt
```

3. **Execute o Jupyter Notebook**:
```bash
jupyter notebook
```

Abra o arquivo `P9_Churn_completo.ipynb` e execute as células.

---

## Aprendizados 📝

### Habilidades Técnicas:
- Modelagem supervisionada com Random Forest
- Correção de desbalanceamento com SMOTE
- Avaliação com F1-score e AUC-ROC
- Manipulação e transformação de dados com pandas

### Habilidades Analíticas:
- Identificação de padrões de evasão de clientes
- Geração de insights a partir das variáveis de comportamento

### Habilidades Profissionais:
- Organização do projeto com README, requisitos e documentação
- Publicação e versionamento no GitHub

---

## Contato 😄
**Marcia Bayardino Weyne**  
📫 mbweyne@gmail.com  
[![GitHub](https://img.shields.io/badge/-GitHub-181717?logo=github&logoColor=white&style=flat)](https://github.com/mbweyne)  
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?logo=linkedin&logoColor=white&style=flat)](https://www.linkedin.com/in/marcia-bayardino-weyne)