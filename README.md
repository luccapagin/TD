# Técnicas de Controle de Overfitting em Algoritmos Neurais: Um Referencial Prático

Este repositório contém o código e documentação do Trabalho de Conclusão de Curso (TCC) do curso de Ciência da Computação da PUC Minas - Campus Poços de Caldas que investiga e implementa técnicas de controle de overfitting em redes neurais.

## Sobre o Projeto

Este trabalho apresenta uma análise prática de diferentes técnicas utilizadas para controlar o overfitting em algoritmos neurais, incluindo:

- Regularização L1 e L2
- Dropout
- Early Stopping
- Data Augmentation
- Batch Normalization

## Estrutura do Repositório

- `Código com Outputs.ipynb`: Notebook Jupyter contendo o código completo com todas as saídas e resultados
- `Código sem Outputs.ipynb`: Versão limpa do notebook, sem as saídas de execução

## Instalação

1. Clone este repositório:
```bash
git clone https://github.com/luccapagin/TD.git
cd TD
```

2. Crie e ative um ambiente virtual:
```bash
# Windows
python -m venv .venv
.venv\Scripts\activate

# Linux/Mac
python -m venv .venv
source .venv/bin/activate
```

3. Instale as dependências:
```bash
pip install -r requirements.txt
```


## Como Reproduzir os Resultados

1. Abra o notebook Jupyter:
```bash
jupyter notebook
```

2. Execute o notebook `Código sem Outputs.ipynb` na seguinte ordem:
   - Importação das bibliotecas
   - Carregamento e pré-processamento dos dados
   - Implementação das técnicas de controle de overfitting
   - Treinamento dos modelos
   - Avaliação dos resultados

3. Os resultados serão exibidos em gráficos e tabelas comparativas, mostrando a eficácia de cada técnica.

## Estrutura do Código

O notebook está organizado nas seguintes seções:

1. **Configuração Inicial**
   - Importação de bibliotecas
   - Configuração de parâmetros

2. **Preparação dos Dados**
   - Carregamento do dataset
   - Pré-processamento
   - Divisão treino/teste

3. **Implementação das Técnicas**
   - Regularização L1/L2
   - Dropout
   - Early Stopping
   - Data Augmentation
   - Batch Normalization

4. **Treinamento e Avaliação**
   - Treinamento dos modelos
   - Métricas de avaliação
   - Visualização dos resultados

## Resultados

O trabalho apresenta uma análise comparativa das diferentes técnicas de controle de overfitting, demonstrando sua eficácia através de experimentos práticos e métricas de avaliação. Os resultados incluem:

- Gráficos de acurácia e loss durante o treinamento
- Tabelas comparativas das métricas finais
- Análise do impacto de cada técnica no overfitting


## Autor

Lucca Pagin Barbosa Rios

## Orientador

Prof. Dr. Márcio Leandro Gonçalves

