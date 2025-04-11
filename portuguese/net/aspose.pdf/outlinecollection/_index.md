---
title: Class OutlineCollection
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.OutlineCollection. Representa a hierarquia de contornos do documento
type: docs
weight: 8000
url: /pt/net/aspose.pdf/outlinecollection/
---
## Classe OutlineCollection

Representa a hierarquia de contornos do documento.

```csharp
public sealed class OutlineCollection : Outlines
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| override [Count](../../aspose.pdf/outlinecollection/count/) { get; } | Contagem de itens da coleção. Por favor, não confunda com VisibleCount: VisibleCount obtém o número de itens de contorno visíveis em todos os níveis. |
| [First](../../aspose.pdf/outlinecollection/first/) { get; } | Obtém um item de contorno representando o primeiro item de nível superior no contorno. |
| override [IsReadOnly](../../aspose.pdf/outlinecollection/isreadonly/) { get; } | Obtém um valor indicando se a coleção é somente leitura. |
| [IsSynchronized](../../aspose.pdf/outlinecollection/issynchronized/) { get; } | Obtém um valor indicando se o acesso a esta coleção é sincronizado (seguro para threads). |
| [Item](../../aspose.pdf/outlinecollection/item/) { get; } | Obtém um item de contorno da coleção pelo índice. |
| [Last](../../aspose.pdf/outlinecollection/last/) { get; } | Obtém um item de contorno representando o último item de nível superior no contorno. |
| [SyncRoot](../../aspose.pdf/outlinecollection/syncroot/) { get; } | Obtém um objeto que pode ser usado para sincronizar o acesso a esta coleção. |
| override [VisibleCount](../../aspose.pdf/outlinecollection/visiblecount/) { get; } | A contagem é a soma do número de itens de contorno descendentes visíveis em todos os níveis. Nota: por favor, não confunda com Count, que é o número de itens na coleção. |

## Métodos

| Nome | Descrição |
| --- | --- |
| override [Add](../../aspose.pdf/outlinecollection/add/)(OutlineItemCollection) | Adiciona um item de contorno à coleção. |
| override [Clear](../../aspose.pdf/outlinecollection/clear/)() | Limpa todos os itens da coleção. |
| override [Contains](../../aspose.pdf/outlinecollection/contains/)(OutlineItemCollection) | Verifica se a coleção contém o item dado. |
| override [CopyTo](../../aspose.pdf/outlinecollection/copyto/)(OutlineItemCollection[], int) | Copia os itens de contorno para um System.Array, começando em um índice específico do System.Array. |
| [Delete](../../aspose.pdf/outlinecollection/delete/#delete)() | Exclui todos os itens de contorno do contorno do documento. |
| [Delete](../../aspose.pdf/outlinecollection/delete/#delete_1)(string) | Exclui o item de contorno com o título especificado do contorno do documento. |
| override [GetEnumerator](../../aspose.pdf/outlinecollection/getenumerator/)() | Retorna um enumerador que itera pela coleção. |
| [Remove](../../aspose.pdf/outlinecollection/remove/#remove_1)(int) | Remove o item pelo índice. |
| override [Remove](../../aspose.pdf/outlinecollection/remove/#remove)(OutlineItemCollection) | Sempre lança NotImplementedException |

### Veja Também

* classe [Outlines](../outlines/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)