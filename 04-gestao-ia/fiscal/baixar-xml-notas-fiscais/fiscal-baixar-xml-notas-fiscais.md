---
id: produto.fiscal.baixar-xml-notas-fiscais
titulo: Como baixar os XMLs das notas fiscais
title: Como baixar os XMLs das notas fiscais
descricao: Ensina como acessar a area fiscal, selecionar as notas emitidas e solicitar o download em lote dos XMLs no Atendi OS.
description: Ensina como acessar a area fiscal, selecionar as notas emitidas e solicitar o download em lote dos XMLs no Atendi OS.
tipo: tutorial
solucao: fiscal
status: rascunho
publico:
  - cliente
  - equipe
  - ia
palavras_chave:
  - baixar xml
  - baixar xml das notas
  - download de xml
  - xml nfce
  - baixar notas fiscais
atualizado_em: 2026-07-22
pagina_url: https://os.atendi.com.br/04-gestao-ia/fiscal/baixar-xml-notas-fiscais/fiscal-baixar-xml-notas-fiscais
video_url: https://atendi.com.br/atendios/04-gestao-ia/fiscal/baixar-xml-notas-fiscais/videos/fiscal-baixar-xml-notas-fiscais.mp4
---
# Como baixar os XMLs das notas fiscais

Este tutorial explica como acessar a area fiscal, localizar as notas emitidas e solicitar o download em lote dos XMLs no Atendi OS.

## Objetivo

Baixar os arquivos XML das notas fiscais emitidas para consulta, conferencia ou armazenamento externo.

## Quando utilizar

Use este procedimento quando for necessario reunir os XMLs de um periodo, de uma empresa ou de um conjunto especifico de notas fiscais emitidas.

## Antes de comecar

- Tenha acesso ao modulo fiscal do sistema.
- Confirme quais notas ou qual periodo precisam entrar no download.
- Valide se o tipo de documento selecionado corresponde aos XMLs que voce precisa baixar.

## Passo a passo

### 1. Acessar o menu Fiscal e abrir NFC-e Emitidas

No menu lateral, acesse **Fiscal** e depois selecione **NFC-e Emitidas** para abrir a listagem das notas fiscais disponiveis.

![Menu Fiscal com a opcao NFC-e Emitidas visivel](https://atendi.com.br/atendios/04-gestao-ia/fiscal/baixar-xml-notas-fiscais/imagens/01-menu-fiscal.png)

Na imagem, o menu fiscal aparece expandido com a opcao **NFC-e Emitidas**. Use esse caminho para chegar ate a tela onde as notas podem ser selecionadas.

### 2. Selecionar as notas desejadas

Na listagem de notas emitidas, marque os registros que devem entrar no download. Depois, use a barra de acoes superior para iniciar a rotina de exportacao.

![Tela de NFC-e Emitidas com notas selecionadas e acoes disponiveis](https://atendi.com.br/atendios/04-gestao-ia/fiscal/baixar-xml-notas-fiscais/imagens/02-notas-selecionadas.png)

Na imagem, a tela mostra uma ou mais notas marcadas na grade e a barra de acoes com a opcao de baixar XML. Revise a selecao antes de continuar para evitar gerar arquivos desnecessarios.

### 3. Abrir a tela de baixar arquivos em lote

Depois de iniciar a acao de download, o sistema abre a tela **Baixar Arquivos em Lote**, onde os pedidos de exportacao ficam disponiveis para consulta e download.

![Tela de Baixar Arquivos em Lote com registro disponivel](https://atendi.com.br/atendios/04-gestao-ia/fiscal/baixar-xml-notas-fiscais/imagens/03-baixar-arquivos-em-lote.png)

Na imagem, a tela mostra a lista de lotes gerados, com colunas como periodo, conclusao e total de arquivos. Quando o lote estiver pronto, o download fica disponivel na ultima coluna da grade.

### 4. Definir os filtros do download

Se precisar gerar um novo lote, abra a busca avancada e preencha os filtros necessarios, como empresa, status, tipo de documento e periodo.

![Tela de Baixar Arquivos em Lote com filtros para gerar XML](https://atendi.com.br/atendios/04-gestao-ia/fiscal/baixar-xml-notas-fiscais/imagens/04-filtros-download-xml.png)

Na imagem, a busca avancada permite ajustar os filtros do lote antes de confirmar a geracao. Verifique principalmente o tipo de documento e o periodo escolhido para garantir que o sistema monte o arquivo correto.

### 5. Solicitar o download dos XMLs

Depois de preencher os filtros, selecione **Baixar Arquivos** para iniciar o processamento da solicitacao.

![Tela de processamento da solicitacao de download dos XMLs](https://atendi.com.br/atendios/04-gestao-ia/fiscal/baixar-xml-notas-fiscais/imagens/05-processamento-download-xml.png)

Na imagem, o sistema mostra uma janela de processamento da solicitacao. Aguarde a conclusao do lote e acompanhe a disponibilizacao do arquivo para download na propria tela de lotes.

## Resultado esperado

Ao final do processo, o lote deve aparecer como concluido na tela **Baixar Arquivos em Lote**, com o download do arquivo disponivel na coluna final da grade.

## O que acontece na operacao

Esse fluxo centraliza a exportacao de XMLs fiscais em lote, facilitando consultas posteriores, envio para contabilidade e guarda dos documentos emitidos.

## Problemas comuns

### Lote nao aparece para download

Se o lote ainda nao estiver concluido, aguarde o processamento terminar e atualize a tela antes de tentar baixar o arquivo.

### Filtro retorna menos arquivos do que o esperado

Revise o tipo de documento, o periodo selecionado e a empresa informada na busca avancada para confirmar se o lote foi configurado corretamente.

## Conteudos relacionados

- [Fiscal do Atendi OS](../fiscal-visao-geral.md)
- [FAQ fiscal](../../../06-suporte/faq-fiscal/faq-fiscal-suporte.md)

## Video

<video
  controls
  className="w-full aspect-video rounded-xl"
  src="https://atendi.com.br/atendios/04-gestao-ia/fiscal/baixar-xml-notas-fiscais/videos/fiscal-baixar-xml-notas-fiscais.mp4"
>
  Seu navegador nao suporta reproducao de video embutido.
</video>

## Pendencias de validacao

- Confirmar o nome oficial do tipo de documento que deve ser usado no filtro para baixar os XMLs desejados.
- Confirmar se o arquivo final e baixado diretamente pelo navegador ou se tambem pode ser enviado por e-mail em alguns cenarios.
- Validar se a rotina cobre apenas NFC-e ou se tambem atende outros documentos fiscais com o mesmo fluxo.
