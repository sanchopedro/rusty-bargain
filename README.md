#  Projeto Rusty Bargain - Modelo de Precificação de Carros Usados

![Rusty Bargain](/img/Bargain.png)

O projeto Rusty Bargain envolve a construção de um modelo para determinar o valor de mercado de carros usados. Como parte do desenvolvimento de um aplicativo para atrair novos clientes, o objetivo é fornecer aos usuários uma maneira rápida e precisa de avaliar o preço de seus veículos.

## Objetivo do Projeto

O principal objetivo é treinar modelos de aprendizado de máquina para prever o preço de carros usados com base em diversas características. Os principais pontos de interesse para Rusty Bargain incluem a qualidade da predição, a velocidade da predição e o tempo necessário para o treinamento dos modelos.

## Instruções do Projeto
O projeto segue as seguintes etapas:

1. **Preparação dos Dados:** Baixe e visualize os dados, prepare-os para análise e modelagem.

2. **Treinamento de Modelos:** Treine diferentes modelos de aprendizado de máquina com diversos hiperparâmetros. Compare métodos de gradient boosting com floresta aleatória, árvore de decisão e regressão linear.

3. **Análise dos Modelos:** Avalie a velocidade e a qualidade dos modelos, utilizando a métrica REQM (Erro Quadrático Médio Relativo).

## Descrição dos Dados

Os dados estão armazenados no arquivo `/datasets/car_data.csv` . [Clique aqui para baixar o conjunto de dados](https://practicum-content.s3.us-west-1.amazonaws.com/datasets/car_data.csv) e incluem diversas características dos carros, como tipo de carroçaria, ano de matrícula, potência, quilometragem, entre outros. O objetivo é prever o preço do carro em euros.

- **Características**

    - DateCrawled — data em que o perfil foi baixado do banco de dados

    - VehicleType — tipo de carroçaria do veículo

    - RegistrationYear — ano de matrícula do veículo

    - Gearbox — tipo de caixa de transmissão

    - Power — potência (hp)

    - Model — modelo do veículo

    - Mileage — quilometragem (medida em km devido às especificidades regionais do conjunto de dados)

    - RegistrationMonth — mês de registro do veículo

    - FuelType — tipo de combustível

    - Brand — marca do veículo

    - NotRepaired — veículo reparado ou não

    - DateCreated — data de criação do perfil

    - NumberOfPictures — número de fotos do veículo

    - PostalCode — código postal do proprietário do perfil (usuário)

    - LastSeen — data da última atividade do usuário

- **Objetivo**

    - Price — preço (Euro)

## Avaliação do Projeto

A avaliação do projeto inclui critérios como seguir as instruções fornecidas, a preparação adequada dos dados, a consideração de diferentes modelos e hiperparâmetros, a organização do código e das conclusões, a manutenção da estrutura do projeto e a limpeza do código.

Com tudo isso em mente, desejo sucesso em seu projeto! Estou aqui para ajudar se precisar de alguma orientação ou suporte. Boa sorte!
