#  Summit-SVM-HeartDisease

Impacto da validação cruzada no desempenho do SVM para diagnóstico de doença cardíaca.

---

##  Contexto

Este repositório apresenta um estudo sobre o uso da **Máquina de Vetores de Suporte (SVM)** para diagnóstico de doenças cardíacas.  
O foco está em avaliar como a **validação cruzada** impacta no desempenho do modelo preditivo.

---

##  Estrutura do Projeto

- `SVM_HeartDisease.ipynb` → Notebook principal com a implementação do modelo.
- `README.md` → Documentação do projeto.

---

##  Base de Dados

O dataset utilizado já está disponível **na nuvem**, não sendo necessário realizar download manual.  
O notebook faz o carregamento direto, simplificando o processo de execução.

Origem: Conjunto de dados público sobre doenças cardíacas.

---

##  Como Executar o Projeto

### 🔗 Abrir no Google Colab
[![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1RC_c_uJC8qP1pB1ypTvevHufdQQitgmP?authuser=2)

### Passo a passo

1. **Clique no badge acima** para abrir diretamente o notebook no Colab.  
2. **Conecte o ambiente** no canto superior direito (*Connect*).  
3. **Configure o ambiente**:  
   - O notebook já possui as bibliotecas necessárias, mas, se precisar, rode:
     ```bash
     !pip install scikit-learn pandas matplotlib
     ```
4. **Execute as células** na ordem apresentada:  
   - Pré-processamento dos dados  
   - Treinamento com **SVM**  
   - Avaliação com **validação cruzada**  
   - Comparação de métricas de desempenho  

---

##  Resultados Esperados

- Métricas de avaliação do modelo (**acurácia, precisão, recall, F1-score**).  
- Impacto direto da validação cruzada nos resultados.  
- Visualizações gráficas para interpretação do desempenho.  

---

##  Requisitos

- Python 3.8+  
- Bibliotecas:  
  - `scikit-learn`  
  - `pandas`  
  - `numpy`  
  - `matplotlib`

---


