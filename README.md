# Java CoinGecko API

Este projeto é um exercício em **Java** que utiliza as classes `HttpClient`, `HttpRequest` e `HttpResponse` para consumir a **API CoinGecko**.

O programa solicita ao usuário o **ID de uma criptomoeda** e exibe no terminal a **cotação atual em dólar (USD)** retornada pela API.

## 🛠 Tecnologias utilizadas
- Java 11 ou superior
- CoinGecko API
- java.net.http

## 📌 Como funciona
1. O usuário informa o ID da criptomoeda (ex: `bitcoin`, `ethereum`)
2. O programa realiza uma requisição HTTP GET para a API CoinGecko
3. A resposta da API é exibida no terminal em formato JSON

## 🎯 Objetivo
Projeto desenvolvido para fins de estudo, com foco em:
- Consumo de APIs REST em Java
- Uso das classes HTTP nativas da linguagem
- Integração com serviços externos

## 📚 Observação
A API CoinGecko utiliza IDs específicos para as criptomoedas, geralmente em letras minúsculas.
