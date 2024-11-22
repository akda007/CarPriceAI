# CarPriceAI

O **CarPriceAI** é um projeto de Inteligência Artificial desenvolvido para prever os preços de carros com base em suas características (features). O modelo utiliza redes neurais com 5 camadas, sendo 3 delas camadas escondidas, e foi testado com duas funções de ativação: **ELU** (Exponential Linear Unit) e **ReLU** (Rectified Linear Unit).

## Funcionalidades

- Previsão do preço de carros a partir de dados de características como ID, preço, fabricante, ano de produção, tipo de combustível, volume do motor, entre outros.
- Utilização de redes neurais com múltiplas camadas para uma análise mais precisa.
- Teste de funções de ativação **ELU** e **ReLU** para otimizar o desempenho do modelo.

## Estrutura do Projeto

O projeto está estruturado da seguinte maneira:

```
CarPriceAI/
│
├── elu.ipynb                          # Teste 1 com ELU
│
├── elu2.ipynb                         # Teste 2 com ELU
│
├── relu.ipynb                         # Teste 1 com RELU
│
├── relu2.ipynb                        # Teste 2 com RELU
│
│
├── car_price_prediction.csv           # Dataset utilizado para treinar a IA
├── requirements.txt                   # Dependências do projeto
└── README.md                          # Este arquivo
```

## Como Rodar o Projeto

### Pré-requisitos

1. Instale as dependências do projeto utilizando o arquivo `requirements.txt`:

```bash
pip install -r requirements.txt
```

2. Certifique-se de ter o Python 3.12.x instalado em sua máquina.

### Rodando Localmente

1. Clone o repositório:

```bash
git clone https://github.com/akda007/CarPriceAI.git
cd CarPriceAI
```

2. Os códigos de cada verção da IA estão contidos nos arquivos `.ipynb`.

## Teste de Funções de Ativação

Durante o treinamento, foram testadas as funções de ativação **ELU** e **ReLU** para otimizar o desempenho do modelo. Os resultados podem ser comparados no notebook para observar qual função trouxe o melhor desempenho em termos de precisão.

## Autores

- `Andrey Koch de Araujo`
- `Izabelle Rondon`
