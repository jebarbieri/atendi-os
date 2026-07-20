---
id: produto.visao-geral.arquitetura-operacional
titulo: Arquitetura operacional da loja
title: Arquitetura operacional da loja
descricao: Descreve a leitura arquitetural do Atendi OS sobre canais, operacao, gestao e inteligencia da loja.
description: Descreve a leitura arquitetural do Atendi OS sobre canais, operacao, gestao e inteligencia da loja.
tipo: referencia
solucao: arquitetura-operacional
status: publicado
publico:
  - lead
  - cliente
  - equipe
  - ia
palavras_chave:
  - arquitetura operacional da loja
  - como o atendi os organiza a operacao
  - camadas do produto
atualizado_em: 2026-07-19
---
# Arquitetura operacional da loja

## O que e

Este documento registra a leitura conceitual da Atendi sobre como a operacao de uma loja se organiza dentro do Atendi OS.

## Como a arquitetura e organizada

A base atual apresenta tres grandes camadas:

- canais de entrada, onde o cliente inicia o pedido
- gestao de pedidos, onde a operacao executa e acompanha o fluxo
- gestao + IA, onde os dados da operacao se transformam em controle, analise e evolucao do negocio

## Como funciona na operacao

Na leitura atual da Atendi, os canais apenas geram pedidos.

A gestao de pedidos coordena status, filas, telas, impressoras, pagamentos, retirada, entrega e finalizacao.

Depois disso, os pedidos finalizados alimentam a camada de gestao e inteligencia.

## Areas operacionais citadas

A documentacao atual menciona exemplos como cozinha, bar, separacao, oficina, producao, servicos e expedicao.

## Quando consultar

Use este documento para explicar a arquitetura do produto, alinhar discursos de demonstracao e orientar a leitura das secoes seguintes.

## Conteudos relacionados

- [Visao do Atendi OS](../visao-do-atendi-os/atendi-os-visao-geral.md)
- [Solucoes oficiais do Atendi OS](../solucoes-oficiais-atendi-os/atendi-os-solucoes-oficiais.md)
- [Gestao de pedidos](../../03-gestao-de-pedidos/gestao-pedidos-visao-geral.md)
