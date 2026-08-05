---
title: "BaseOperatorCollection"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Representa classe base para coleção de operadores."
type: docs
weight: 70
url: /pt/python-net/aspose.pdf/baseoperatorcollection/
---

## BaseOperatorCollection class

Representa classe base para coleção de operadores.

O tipo BaseOperatorCollection expõe os seguintes membros:
## Propriedades
| Nome | Descrição |
| :- | :- |
| is_fast_text_extraction_mode | Indica se a coleção está limitada à extração rápida de texto |
## Indexer
| Nome | Descrição |
| :- | :- |
| [index] | Obtém o operador pelo seu índice. |
## Métodos
| Nome | Descrição |
| :- | :- |
| suppress_update() | Suprime a atualização dos dados de conteúdo.<br/>            O fluxo de conteúdo não é atualizado até que ResumeUpdate seja chamado. |
| resume_update() | Retoma a atualização do documento.<br/>            Atualiza o fluxo de conteúdo caso haja alterações pendentes. |
| insert(index, op) | Insere o operador na coleção. |
| cancel_update() | Cancela a última atualização.<br/>            Este método pode ser chamado quando a alteração não deve disparar a atualização de conteúdo. |

### Veja Também

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

