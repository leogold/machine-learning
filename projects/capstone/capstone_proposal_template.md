# Machine Learning Engineer Nanodegree
## Capstone Proposal
Leonardo Goldstein  
June 11st, 2018

## Proposal

Desenvolver uma solução completa para medir, avaliar e classificar produtos fora dos parametros de qualidade pre-definidos. 
Este projeto visa solucionar especificamente através de visão computacional a classificação de pontas diamantadas.

1a. Etapa - desenvolver sistema para capturar imagem das pontas. O desafio está em desenvolver um dispositivo para facilitar a tomada de imagem para posterior adequação em processo produtivo. Dentro desta etapa ainda precisamos qualificar uma camera qua consiga capturar as fotos (objeto é muito pequeno e cilindrico).
O dispositivo precisará disponibilizar a ponta de maneira que seja facil a captura da imagem nos 360 graus do objeto.

2a. Etapa - Capturar imagem das pontas. Para o projeto avaliaremos apenas 1 modelo. Cada ponta deverá ter 3 imagens a cada 120 graus. Dentre as pontas separadas com defeito, separar as imagens onde o defeito aparece e classificar as imagens como defeituosas. (Futuramente deveremos classificar as imagens por tipo de defeito - muito níquel, falta de diamante e fora de medida)

3a. Etapa - Desenvolver o algoritimo baseados nos conhecimentos adquiridos em Deep Learning utilizando Redes Neurais convolucionais. 

4a. Etapa - Utilizar uma rede neural robusta e adaptar ao projeto.

5a. etapa - Comparar os sistemas e recomendar a melhor solução.


### Domain Background

Observando uma pessoas olhar diariamente a milhares de pontas diamantadas, me parece claro que além de insalubre a performance e eficácia podem ser melhoradas através de um sistema de recomhecimento visual computacional utilizando Redes Neurais.


### Problem Statement

Inspeção e Controle de qualidade em pontas diamantadas

O objetivo é conseguir melhorar a classificação e separação de pontas e discos com menos recursos e maior assertividade.
Atualmente essas pontas são classificadas visualmente com o auxilio de uma lente de aumento por um grupo de colaboradores.
![](image4.jpeg?raw=true)


### Datasets and Inputs

Através de produtos recolhidos, irei desenvolver um sistema para fotografar e classificar essas pontas. 
![](image2.jpeg?raw=true)
![](image1.jpeg?raw=true)


### Solution Statement

Classificar os produtos como conformes ou não conformes. No caso de não conformes classificá-los pelo tipo de falha/problema.


### Benchmark Model

Alem de desenvolver uma rede neural convolucional especifica para o caso, irei buscar uma rede robusta para comparar resultados e concluir qual o melhor caminho a seguir.


### Evaluation Metrics

A idéia é colocar em série após a classificação manual para uma reclassificação e comparar resultados.


### Project Design

O projeto engloba desde a criação do dispositivo para fotografar, a busca do hardware para fotografar e finalmente a elaboração do sistema de reconhecimento de imagens utilizando a técnica de CNNs.

-----------
