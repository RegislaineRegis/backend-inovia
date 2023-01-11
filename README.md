# backend-inovia

Desafio Full Stack. O objetivo foi elaborar uma solução ponta-a-ponta, desde a criação do banco de dados,
passando pela criação da API de comunicação, interface web de interação.

# **Técnologias usadas**

Back-end:
> Desenvolvido usando: **NODE.JS**, **POSTGRESQL**, **DOCKER**, **MONGODB**, **EXPRESS**, **TYPESCRIPT**, **GIT**, **JAVASCRIPT**, **CORS**, **JWT**, **BCRYPT**;


## Identified use-cases (CSU)

- user
  - login
  - refresh
- customer
  - getFullCustomer
  - addCustomer
  - editCustomer
  - removeCustomer
  - searchCustomer
- products
  - getFullProduct
  - addProduct
  - editProduct
  - removeProduct
  - searchProduct
- sales
  - getFullSale
  - addSale
  - editSale
  - removeSale
  - searchSale

## Modeling (DER) 

![inovia-backend drawio](https://user-images.githubusercontent.com/94489726/210282622-1ee56331-0752-4a50-8528-1067e0d0f4a9.png)

## A solução a ser desenvolvida consiste em um sistema de vendas web conforme especificado abaixo:

## Escopo do Projeto

- [Requisitos do projeto](#requisitos-do-projeto)

      `Requisitos`
    
    - [x] [1. Os usuários devem se autenticar utilizando JWT e devem permanecer conectados por no máximo 15 minutos. Após esse tempo, o usuário precisa renovar o login ou perderá acesso ao sistema](#1-Os-usuários-devem-se-autenticar-utilizando-JWT-e-devem-permanecer-conectados-por-no-máximo-15-minutos-Após-esse-tempo-o-usuário-precisa-renovar-o-login-ou-perderá-acesso-ao-sistema)
    
