---
title: "OperatorCollection"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Classe representa coleção de operadores"
type: docs
weight: 1010
url: /pt/python-net/aspose.pdf/operatorcollection/
---

## OperatorCollection class

Classe representa coleção de operadores

O tipo OperatorCollection expõe os seguintes membros:
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
| insert(index, op) | Insere o operador na coleção. |
| insert(at, ops) | Insere operadores na posição indicada. |
| insert(at, ops) | Insere o operador na coleção. |
| delete(index) | Exclui o operador da coleção. |
| delete(ops) | Exclui operadores da coleção. |
| delete(list) | Nenhum |
| add(ops) | Adiciona operadores ao final dos operadores de conteúdo. |
| add(ops) | Adiciona um novo operador à coleção. |
| suppress_update() | Suprime a atualização dos dados de conteúdo.<br/>            O fluxo de conteúdo não é atualizado até que ResumeUpdate seja chamado. |
| resume_update() | Retoma a atualização do documento.<br/>            Atualiza o fluxo de conteúdo caso haja alterações pendentes. |
| cancel_update() | Cancela a última atualização.<br/>            Este método pode ser chamado quando a alteração não deve disparar a atualização de conteúdo. |
| accept(visitor) | Aceita o objeto visitante IOperatorSelector para processar operadores. |
| replace(operators) | Substitua operadores na coleção por outros operadores. |

### Veja Também

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

