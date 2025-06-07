# 🧬 Classificação de Doença com RNA-seq usando Python e Scikit-learn

Este projeto demonstra como aplicar um pipeline de ciência de dados para prever o status de doença (ex: paciente vs controle) com base em dados de expressão gênica (RNA-seq). Os dados utilizados são simulados e contêm a expressão de 100 genes em 100 indivíduos, classificados em dois grupos: Controle e Doença.

## 🎯 Objetivos
- Aplicar técnicas de pré-processamento em dados ômicos.
- Usar machine learning para classificar indivíduos com base na expressão gênica.
- Realizar análise exploratória (PCA, ANOVA).
- Preparar o projeto para visualização e futuras etapas de modelagem.

## 🛠️ Tecnologias utilizadas
- Python
- pandas, numpy, matplotlib, seaborn
- scikit-learn

## 📁 Estrutura
rna-seq-classification-disease-python/
├── 01_preprocessing.ipynb # Notebook com análise exploratória
├── data/
│ └── simulated_rnaseq_data.csv
├── README.md
├── requirements.txt


## 📈 Resultados
- Visualização por PCA
- Top 10 genes mais relevantes por ANOVA
- Base para modelagem futura

## ▶️ Como rodar
```bash
# Clone o repositório
git clone https://github.com/GiovannaPrezia/rna-seq-classification-disease-python.git
cd rna-seq-classification-disease-python

# Crie um ambiente virtual (opcional)
python -m venv .venv
source .venv/bin/activate  # Linux/Mac
.venv\\Scripts\\activate   # Windows

# Instale as dependências
pip install -r requirements.txt

# Execute o notebook
jupyter notebook
