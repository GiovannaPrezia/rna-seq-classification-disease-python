# Classificação de Doença com RNA-seq usando Python e Scikit-learn

🔬 Este projeto demonstra como aplicar um pipeline de ciência de dados para prever o status de doença (ex: paciente vs controle) com base em dados de expressão gênica (RNA-seq). 

## Objetivos
- Aplicar técnicas de pré-processamento em dados ômicos.
- Usar machine learning para classificar indivíduos com base no perfil de expressão gênica.
- Validar e visualizar os resultados com métricas apropriadas.

## Tecnologias utilizadas
- Python, pandas, numpy
- Scikit-learn
- Matplotlib, seaborn
- [opcional] Streamlit

## Estrutura
- `notebooks/`: Jupyter Notebooks organizados por etapa
- `src/`: Funções reutilizáveis
- `data/`: Dados utilizados
- `results/`: Resultados e gráficos gerados

## Conjunto de dados
Este projeto usa dados simulados ou extraídos de bases públicas como o [TARGET](https://ocg.cancer.gov/programs/target) ou [TCGA](https://www.cancer.gov/ccg/research/genome-sequencing/tcga).

## Como rodar
```bash
git clone https://github.com/seuusuario/rna-seq-classification-disease-python.git
cd rna-seq-classification-disease-python
pip install -r requirements.txt
jupyter notebook
