# Projeto de Previsão de Inadimplência de Empréstimos

Este projeto utiliza Machine Learning para prever a probabilidade de inadimplência em empréstimos, utilizando um conjunto de dados de 9.578 amostras.

## Instalação

Para executar este projeto localmente:

```bash
# Clone o repositório
git clone https://github.com/calebewerneckcouto/SupportVetorMachinesPython.git

# Crie e ative o ambiente virtual
python -m venv venv
source venv/bin/activate  # No Windows: venv\Scripts\activate

# Instale as dependências
pip install -r requirements.txt
```

## Dependências

O projeto utiliza as seguintes bibliotecas:

```markdown
- pandas==1.5.2
- numpy==1.24.2
- scikit-learn==2.0.0
- matplotlib==3.8.1
```

## Estrutura do Projeto

```markdown
projeto/
├── data/
│   └── loan_data.csv
├── notebooks/
│   ├── exploratory_analysis.ipynb
│   ├── preprocessing.ipynb
│   └── modeling.ipynb
├── src/
│   ├── preprocessing.py
│   └── modeling.py
├── requirements.txt
└── README.md
```

## Metodologia

O projeto utiliza o seguinte pipeline:

1. Pré-processamento:
   - Codificação de variáveis categóricas
   - Normalização dos dados
   - Divisão em conjuntos de treino e teste (70/30)

2. Modelagem:
   - SVM com kernel linear
   - Acurácia de 82% no conjunto de teste

## Resultados

O modelo alcançou uma acurácia de 82% na previsão de inadimplência, demonstrando eficácia na identificação de clientes de alto risco.

## Limitações

- O tempo de treinamento é significativo para grandes conjuntos de dados
- O modelo pode ser otimizado com técnicas de redução de dimensionalidade

## Contribuições

Contribuições são bem-vindas! Para contribuir:

1. Faça um fork do projeto
2. Crie uma branch com suas alterações
3. Abra um pull request

## Licença

Este projeto utiliza a licença MIT.

## Autores

- Calebe Werneck Couto - (calebewerneck@hotmai.com)
