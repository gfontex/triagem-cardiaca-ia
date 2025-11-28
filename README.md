# 🫀 Aplicação de Machine Learning para Triagem Cardíaca

Este repositório contém o código-fonte do projeto desenvolvido para a disciplina de Inteligência Artificial do curso de Engenharia de Computação da **FHO | Fundação Hermínio Ometto**.

O objetivo foi criar um modelo preditivo capaz de auxiliar no diagnóstico precoce de doenças cardíacas utilizando dados clínicos.

## 📊 Resultados Alcançados

O modelo treinado (Random Forest) obteve os seguintes resultados nos testes:

| Métrica | Resultado |
| :--- | :--- |
| **Acurácia** | 86,89% |
| **Sensibilidade (Recall)** | 88,00% |
| **Fator de Risco Principal** | Depressão do Segmento ST (Oldpeak) |

> A alta sensibilidade (Recall) indica que o modelo é seguro para triagem médica, minimizando falsos negativos.

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** Python 3
* **Bibliotecas:** Pandas, Scikit-Learn, Matplotlib, Seaborn
* **Algoritmo:** Random Forest Classifier (Otimizado via Grid Search)
* **Ambiente:** Kaggle Notebooks

## 🚀 Como Executar

1.  Baixe o arquivo `Triagem_Cardiaca_IA.ipynb`.
2.  Abra no Google Colab, Jupyter Notebook ou VS Code.
3.  Certifique-se de ter o dataset `heart.csv` (UCI Heart Disease) na mesma pasta ou carregado no ambiente.

## 👨‍💻 Autores

* **Gabriel Fontes** - *Aluno de Engenharia de Computação"
* **Renato Luciano Cagnin** - *Orientação Acadêmica*

---
*Projeto desenvolvido em Novembro de 2025.*
