# Projeto Rusty Bargain - Modelo de Precificação de Carros Usados

![Rusty Bargain](/img/Bargain.png)

## Índice

1. [Como usar](#1-como-usar)
2. [Sobre o Projeto](#2-sobre-o-projeto)
    - [Objetivo do Projeto](#objetivo-do-projeto)
    - [Instruções do Projeto](#instruções-do-projeto)
    - [Descrição dos Dados](#descrição-dos-dados)
    - [Avaliação do Projeto](#avaliação-do-projeto)

## 1. Como usar

- Primeiramente, instale todas as dependências do projeto rodando no terminal o comando:

    ```bash
    pip install -r requirements.txt
    ```

- O arquivo [rusty-bargain.ipynb](rusty-bargain.ipynb) contém os códigos utilizados para a conclusão do projeto.
- O dataset do projeto pode ser encontrado na pasta [dataset](./datasets/). 

## 2. Sobre o Projeto

O projeto Rusty Bargain envolve a construção de um modelo para determinar o valor de mercado de carros usados. Como parte do desenvolvimento de um aplicativo para atrair novos clientes, o objetivo é fornecer aos usuários uma maneira rápida e precisa de avaliar o preço de seus veículos.

### Objetivo do Projeto

O principal objetivo é treinar modelos de aprendizado de máquina para prever o preço de carros usados com base em diversas características. Os principais pontos de interesse para Rusty Bargain incluem a qualidade da predição, a velocidade da predição e o tempo necessário para o treinamento dos modelos.

### Instruções do Projeto

O projeto segue as seguintes etapas:

1. **Preparação dos Dados:** Baixe e visualize os dados, prepare-os para análise e modelagem.

2. **Treinamento de Modelos:** Treine diferentes modelos de aprendizado de máquina com diversos hiperparâmetros. Compare métodos de gradient boosting com floresta aleatória, árvore de decisão e regressão linear.

3. **Análise dos Modelos:** Avalie a velocidade e a qualidade dos modelos, utilizando a métrica REQM (Erro Quadrático Médio Relativo).

### Descrição dos Dados

Os dados estão armazenados no arquivo `/datasets/car_data.csv`. [Clique aqui para baixar o conjunto de dados](https://practicum-content.s3.us-west-1.amazonaws.com/datasets/car_data.csv). O dataset inclui diversas características dos carros, como tipo de carroçaria, ano de matrícula, potência, quilometragem, entre outros. O objetivo é prever o preço do carro em euros.

#### Características

- **DateCrawled:** Data em que o perfil foi baixado do banco de dados
- **VehicleType:** Tipo de carroçaria do veículo
- **RegistrationYear:** Ano de matrícula do veículo
- **Gearbox:** Tipo de caixa de transmissão
- **Power:** Potência (hp)
- **Model:** Modelo do veículo
- **Mileage:** Quilometragem (medida em km devido às especificidades regionais do conjunto de dados)
- **RegistrationMonth:** Mês de registro do veículo
- **FuelType:** Tipo de combustível
- **Brand:** Marca do veículo
- **NotRepaired:** Veículo reparado ou não
- **DateCreated:** Data de criação do perfil
- **NumberOfPictures:** Número de fotos do veículo
- **PostalCode:** Código postal do proprietário do perfil (usuário)
- **LastSeen:** Data da última atividade do usuário

#### Objetivo

- **Price:** Preço (Euro)

### Avaliação do Projeto

A avaliação do projeto inclui critérios como seguir as instruções fornecidas, a preparação adequada dos dados, a consideração de diferentes modelos e hiperparâmetros, a organização do código e das conclusões, a manutenção da estrutura do projeto e a limpeza do código.

Com tudo isso em mente, desejo sucesso em seu projeto! Estou aqui para ajudar se precisar de alguma orientação ou suporte. Boa sorte!
