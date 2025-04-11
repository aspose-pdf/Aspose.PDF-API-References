---
title: Class OperatorCollection
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.OperatorCollection. Classe representa uma coleção de operadores
type: docs
weight: 7080
url: /pt/net/aspose.pdf/operatorcollection/
---
## Classe OperatorCollection

Classe representa uma coleção de operadores

```csharp
public class OperatorCollection : BaseOperatorCollection, IDisposable
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| override [Count](../../aspose.pdf/operatorcollection/count/) { get; } | Obtém a contagem de operadores na coleção. |
| override [IsFastTextExtractionMode](../../aspose.pdf/operatorcollection/isfasttextextractionmode/) { get; } | Indica se a coleção é limitada à extração rápida de texto |
| override [IsReadOnly](../../aspose.pdf/operatorcollection/isreadonly/) { get; } | Obtém um valor que indica se a coleção é somente leitura. |
| override [Item](../../aspose.pdf/operatorcollection/item/) { get; set; } | Obtém o operador pelo seu índice. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [Accept](../../aspose.pdf/operatorcollection/accept/)(IOperatorSelector) | Aceita o objeto visitante IOperatorSelector para processar operadores. |
| [Add](../../aspose.pdf/operatorcollection/add/#add_2)(ICollection&lt;Operator&gt;) | Adiciona à coleção todos os operadores de outra coleção. |
| override [Add](../../aspose.pdf/operatorcollection/add/#add)(Operator) | Adiciona um novo operador à coleção. |
| [Add](../../aspose.pdf/operatorcollection/add/#add_1)(Operator[]) | Adiciona operadores ao final dos operadores de conteúdo. |
| override [CancelUpdate](../../aspose.pdf/operatorcollection/cancelupdate/)() | Cancela a última atualização. Este método pode ser chamado quando a alteração não deve gerar atualização de conteúdo. |
| override [Clear](../../aspose.pdf/operatorcollection/clear/)() | Remove todos os operadores da lista. |
| override [Contains](../../aspose.pdf/operatorcollection/contains/)(Operator) | Retorna verdadeiro se a coleção contém o operador dado. |
| override [CopyTo](../../aspose.pdf/operatorcollection/copyto/)(Operator[], int) | Copia operadores para a lista de operadores. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete_2)(IList&lt;Operator&gt;) | Exclui operadores da coleção. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete_1)(int) | Exclui o operador da coleção. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete)(Operator[]) | Exclui operadores da coleção. |
| [Dispose](../../aspose.pdf/operatorcollection/dispose/)() | Realiza tarefas definidas pela aplicação associadas à liberação, liberação ou redefinição de recursos não gerenciados. |
| override [GetEnumerator](../../aspose.pdf/operatorcollection/getenumerator/)() | Retorna o enumerador para a coleção |
| [Insert](../../aspose.pdf/operatorcollection/insert/#insert_2)(int, IList&lt;Operator&gt;) | Insere operadores na posição dada. |
| override [Insert](../../aspose.pdf/operatorcollection/insert/#insert)(int, Operator) | Insere o operador na coleção. |
| [Insert](../../aspose.pdf/operatorcollection/insert/#insert_1)(int, Operator[]) | Insere operadores na posição dada. |
| override [Remove](../../aspose.pdf/operatorcollection/remove/)(Operator) | Remove o operador da coleção. |
| [Replace](../../aspose.pdf/operatorcollection/replace/)(IList&lt;Operator&gt;) | Substitui operadores na coleção por outros operadores. |
| override [ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate/#resumeupdate)() | Retoma a atualização do documento. Atualiza o fluxo de conteúdo caso haja alterações pendentes. |
| [ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate/#resumeupdate_1)(bool) | Retoma a atualização do documento. Atualiza o fluxo de conteúdo caso haja alterações pendentes. Marca todos os operadores como "alterados" se o parâmetro invalidate for verdadeiro. |
| override [SuppressUpdate](../../aspose.pdf/operatorcollection/suppressupdate/)() | Suprime a atualização dos dados de conteúdo. O fluxo de conteúdo não é atualizado até que ResumeUpdate seja chamado. |
| override [ToString](../../aspose.pdf/operatorcollection/tostring/)() | Retorna a representação textual do operador. |

### Veja Também

* classe [BaseOperatorCollection](../baseoperatorcollection/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)