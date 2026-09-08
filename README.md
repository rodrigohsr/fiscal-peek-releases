# DanfeTec — instaladores

Este repositório guarda **apenas os instaladores publicados** do DanfeTec. Não
há código-fonte aqui: ele existe para que o programa instalado consiga verificar
se há versão nova, sem precisar de credencial nenhuma.

**[Baixar a versão mais recente](https://github.com/rodrigohsr/fiscal-peek-releases/releases/latest)**

## O que é o DanfeTec

Um programa para Windows que abre o XML de um documento fiscal eletrônico,
mostra o documento no layout oficial e gera o PDF. Atende NF-e, NFC-e, CT-e,
NFS-e (padrão nacional e municipal ABRASF), eventos e inutilização de numeração.

Uma pasta inteira também se abre, como lista para escolher — com o número, o
emitente, a data e a situação de cada nota. E o botão direito do Explorer
renomeia uma árvore de XMLs para `<número> - <razão social>.xml`, incluindo as
subpastas.

Os arquivos não saem do seu computador: tudo é lido e desenhado na máquina.

## Qual arquivo baixar

`DanfeTec-Setup.exe` é o único. Ele associa os arquivos `.xml` e acrescenta o
item de renomear em lote ao menu do Explorer.

A escolha entre instalar para uma conta só ou para todas as contas do computador
é a primeira tela. Para instalar num servidor pela linha de comando:

```
DanfeTec-Setup.exe /ALLUSERS
```

## Licença

O DanfeTec é distribuído sob **licença proprietária** — o texto acompanha o
programa, em `LICENSE`. Não há código-fonte publicado.

Até a versão 1.14.0 o programa foi distribuído sob a AGPL-3.0. **As cópias
recebidas naquele período continuam sob ela**: a licença nova vale daqui para a
frente e não retira direito já concedido.

## Nome anterior

O programa se chamava **FiscalPeek** até agosto de 2026. O endereço deste
repositório é do nome antigo e continua funcionando; o programa é o mesmo.
