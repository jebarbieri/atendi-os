---
id: produto.pdv.realizar-venda
titulo: Como realizar uma venda no PDV
descricao: Ensina como registrar e finalizar uma venda no PDV do Atendi OS.
tipo: tutorial
solucao: pdv
status: rascunho
publico:
  - cliente
  - equipe
  - ia
palavras_chave:
  - como realizar uma venda no pdv
  - como registrar uma venda
  - vender no caixa
  - finalizar venda no pdv
atualizado_em: 2026-07-20
---
# Como realizar uma venda no PDV

Este tutorial explica como registrar e finalizar uma venda no PDV do Atendi OS.

## Objetivo

Ensinar o usuario a registrar e finalizar uma venda no PDV.

## Quando utilizar

Use este procedimento sempre que uma venda presencial precisar ser registrada no caixa.

## Antes de comecar

- O caixa precisa estar aberto.
- Deve existir pelo menos um produto cadastrado.

## Passo a passo

### 1. Abrir o PDV

Acesse o PDV para iniciar o registro da venda.

### 2. Pesquisar o produto

Pesquise o produto pelo nome, codigo ou codigo de barras.

Confirme se o item correto aparece no resultado antes de continuar.

### 3. Selecionar o produto e informar a quantidade

Selecione o produto encontrado e informe a quantidade desejada para a venda.

Revise os itens adicionados antes de seguir para o pagamento.

### 4. Escolher a forma de pagamento

Selecione a forma de pagamento que sera usada para concluir a venda.

Este documento nao afirma integracao automatica com maquininhas de cartao, pois essa informacao nao foi confirmada na base fornecida.

### 5. Finalizar a venda

Conclua a operacao para registrar a venda no sistema.

## Resultado esperado

A venda deve ser registrada com sucesso.

Quando houver area operacional configurada, o pedido deve seguir para a Central de Pedidos.

## O que acontece na operacao

Depois da finalizacao, a venda passa a fazer parte do fluxo operacional da loja.

Quando existir area operacional configurada, o pedido segue para a Central de Pedidos para dar continuidade ao atendimento.

## Problemas comuns

### Produto nao aparece na pesquisa

Verifique se existe pelo menos um produto cadastrado e se a busca foi feita pelo nome, codigo ou codigo de barras corretos.

Se o produto continuar sem aparecer, revise o cadastro do item antes de tentar novamente.

### Pedido nao segue para a area operacional

Verifique se existe uma area operacional configurada para receber o pedido apos a venda.

Se a configuracao estiver ausente ou incorreta, o fluxo para a Central de Pedidos pode nao acontecer como esperado.

## Conteudos relacionados

- [PDV do Atendi OS](../pdv-visao-geral.md)
- [Produtos e categorias](../../../07-configuracao/produtos-e-categorias/produtos-categorias-configurar.md)
- [Formas de pagamento](../../../07-configuracao/formas-de-pagamento/formas-pagamento-configurar.md)
- [Central de pedidos](../../../03-gestao-de-pedidos/central-de-pedidos/central-pedidos-visao-geral.md)
- [Areas de producao](../../../07-configuracao/areas-de-producao/areas-producao-configurar.md)

## Pendencias de validacao

- Confirmar os nomes oficiais das telas, campos e botoes usados para pesquisar produtos, escolher a forma de pagamento e finalizar a venda.
- Validar se as imagens `tela-pdv.png`, `busca-produto.png` e `finalizar-venda.png` existem e devem ser movidas para `atendi-os/02-canais-de-entrada/pdv/realizar-venda/imagens/` com nomenclatura final padronizada.
- Confirmar se existe alguma validacao adicional no fechamento da venda que precise ser descrita no passo a passo.
