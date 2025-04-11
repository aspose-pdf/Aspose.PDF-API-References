---
title: Class BaseOperatorCollection
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.BaseOperatorCollection. Representa a classe base para a coleção de operadores
type: docs
weight: 2830
url: /pt/net/aspose.pdf/baseoperatorcollection/
---
## Classe BaseOperatorCollection

Representa a classe base para a coleção de operadores.

```csharp
public abstract class BaseOperatorCollection : ICollection<Operator>
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| abstract [Count](../../aspose.pdf/baseoperatorcollection/count/) { get; } | Obtém a contagem de operadores na coleção. |
| abstract [IsFastTextExtractionMode](../../aspose.pdf/baseoperatorcollection/isfasttextextractionmode/) { get; } | Indica se a coleção é limitada à extração rápida de texto |
| abstract [IsReadOnly](../../aspose.pdf/baseoperatorcollection/isreadonly/) { get; } | Retorna verdadeiro se a coleção for somente leitura. |
| abstract [Item](../../aspose.pdf/baseoperatorcollection/item/) { get; set; } | Obtém o operador pelo seu índice. |

## Métodos

| Nome | Descrição |
| --- | --- |
| abstract [Add](../../aspose.pdf/baseoperatorcollection/add/)(Operator) | Adiciona um novo operador à coleção. |
| abstract [CancelUpdate](../../aspose.pdf/baseoperatorcollection/cancelupdate/)() | Cancela a última atualização. Este método pode ser chamado quando a alteração não deve gerar atualização de conteúdos. |
| abstract [Clear](../../aspose.pdf/baseoperatorcollection/clear/)() | Limpa a coleção. |
| abstract [Contains](../../aspose.pdf/baseoperatorcollection/contains/)(Operator) | Verifica se o operador existe na coleção. |
| abstract [CopyTo](../../aspose.pdf/baseoperatorcollection/copyto/)(Operator[], int) | Copia operadores para a lista de operadores. |
| abstract [GetEnumerator](../../aspose.pdf/baseoperatorcollection/getenumerator/)() | Retorna um enumerador para a coleção |
| abstract [Insert](../../aspose.pdf/baseoperatorcollection/insert/)(int, Operator) | Insere um operador na coleção. |
| abstract [Remove](../../aspose.pdf/baseoperatorcollection/remove/)(Operator) | Remove um operador da coleção. |
| abstract [ResumeUpdate](../../aspose.pdf/baseoperatorcollection/resumeupdate/)() | Retoma a atualização do documento. Atualiza o fluxo de conteúdos caso haja alterações pendentes. |
| abstract [SuppressUpdate](../../aspose.pdf/baseoperatorcollection/suppressupdate/)() | Suprime a atualização dos dados de conteúdo. O fluxo de conteúdos não é atualizado até que ResumeUpdate seja chamado. |

### Veja Também

* classe [Operator](../operator/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)