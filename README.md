# FiscalPeek — instaladores

Este repositório guarda **apenas os instaladores publicados** do FiscalPeek.
Não há código-fonte aqui: ele existe para que o programa instalado consiga
verificar sozinho se há versão nova, sem precisar de credencial nenhuma.

**[Baixar a versão mais recente](https://github.com/rodrigohsr/fiscal-peek-releases/releases/latest)**

## O que é o FiscalPeek

Um programa para Windows que abre o XML de um documento fiscal eletrônico,
mostra o documento no layout oficial e gera o PDF. Atende NF-e, NFC-e, CT-e,
NFS-e (padrão nacional e municipal ABRASF), eventos e inutilização de numeração.

Também renomeia uma pasta inteira de XMLs para `<número> - <razão social>.xml`,
pelo menu do botão direito do Explorer.

## Qual arquivo baixar

| Arquivo | Para quê |
|---|---|
| `FiscalPeek-Setup.exe` | Instalação normal. Associa os arquivos `.xml` e acrescenta o item de renomear em lote ao menu de pastas. |
| `FiscalPeek-portatil.zip` | Sem instalar: descompacte e rode. Não associa nada. |

O instalador serve tanto para uma conta só quanto para todas as contas do
computador — a escolha é a primeira tela. Para instalar num servidor pela linha
de comando, `FiscalPeek-Setup.exe /ALLUSERS`.

## Licença

O FiscalPeek é distribuído sob a **AGPL-3.0**. Quem recebe o binário tem direito
ao código-fonte correspondente; peça pelas issues deste repositório.
