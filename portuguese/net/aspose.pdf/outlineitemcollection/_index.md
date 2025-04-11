---
title: Class OutlineItemCollection
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.OutlineItemCollection. Representa a entrada do índice na hierarquia de índice do documento PDF
type: docs
weight: 8010
url: /pt/net/aspose.pdf/outlineitemcollection/
---
## Classe OutlineItemCollection

Representa a entrada do índice na hierarquia de índice do documento PDF.

```csharp
public sealed class OutlineItemCollection : Outlines
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [OutlineItemCollection](outlineitemcollection/)(OutlineCollection) | Inicializa a instância do item de índice usando o objeto da hierarquia raiz. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Action](../../aspose.pdf/outlineitemcollection/action/) { get; set; } | Obtém ou define a ação para este item de índice. |
| [Bold](../../aspose.pdf/outlineitemcollection/bold/) { get; set; } | Obtém ou define a flag de negrito para o texto do título deste item de índice |
| [Color](../../aspose.pdf/outlineitemcollection/color/) { get; set; } | Obtém ou define a cor para o texto do título deste item de índice. |
| override [Count](../../aspose.pdf/outlineitemcollection/count/) { get; } | Contagem dos itens da coleção. Por favor, não confunda com VisibleCount: VisibleCount obtém o número de itens de índice visíveis em todos os níveis. |
| [Destination](../../aspose.pdf/outlineitemcollection/destination/) { get; set; } | Obtém ou define o destino para este item de índice. |
| [First](../../aspose.pdf/outlineitemcollection/first/) { get; } | Obtém o item de índice que representa o primeiro item de nível superior na hierarquia de índice. |
| [HasNext](../../aspose.pdf/outlineitemcollection/hasnext/) { get; } | Verifica se o item de índice representa o próximo item em relação a este item na hierarquia de índice. |
| override [IsReadOnly](../../aspose.pdf/outlineitemcollection/isreadonly/) { get; } | Obtém um valor que indica se a coleção é somente leitura. |
| [IsSynchronized](../../aspose.pdf/outlineitemcollection/issynchronized/) { get; } | Obtém o valor que indica se o acesso a esta coleção é sincronizado (seguro para threads). |
| [Italic](../../aspose.pdf/outlineitemcollection/italic/) { get; set; } | Obtém ou define a flag de itálico para o texto do título deste item de índice |
| [Item](../../aspose.pdf/outlineitemcollection/item/) { get; } | Obtém o item de índice da coleção usando o índice. |
| [Last](../../aspose.pdf/outlineitemcollection/last/) { get; } | Obtém o item de índice que representa o último item de nível superior na hierarquia de índice. |
| [Level](../../aspose.pdf/outlineitemcollection/level/) { get; } | Obtém o nível da hierarquia do item de índice. |
| [Next](../../aspose.pdf/outlineitemcollection/next/) { get; } | Obtém o item de índice que representa o próximo item em relação a este item na hierarquia de índice. |
| [Open](../../aspose.pdf/outlineitemcollection/open/) { get; set; } | Obtém ou define o status de aberto (true/false) para o item de índice. |
| [Parent](../../aspose.pdf/outlineitemcollection/parent/) { get; } | Obtém o objeto pai deste item de índice na hierarquia de índice. |
| [Prev](../../aspose.pdf/outlineitemcollection/prev/) { get; } | Obtém o item de índice que representa o item anterior em relação a este item na hierarquia de índice. |
| [SyncRoot](../../aspose.pdf/outlineitemcollection/syncroot/) { get; } | Obtém o objeto que pode ser usado para sincronizar o acesso a esta coleção. |
| [Title](../../aspose.pdf/outlineitemcollection/title/) { get; set; } | Obtém ou define o título para este item de índice. |
| override [VisibleCount](../../aspose.pdf/outlineitemcollection/visiblecount/) { get; } | Obtém o número total de itens de índice em todos os níveis na hierarquia de índice do documento. |

## Métodos

| Nome | Descrição |
| --- | --- |
| override [Add](../../aspose.pdf/outlineitemcollection/add/)(OutlineItemCollection) | Adiciona um item de índice à coleção. |
| override [Clear](../../aspose.pdf/outlineitemcollection/clear/)() | Limpa todos os itens da coleção. |
| override [Contains](../../aspose.pdf/outlineitemcollection/contains/)(OutlineItemCollection) | Verifica se a coleção contém o item dado. |
| override [CopyTo](../../aspose.pdf/outlineitemcollection/copyto/)(OutlineItemCollection[], int) | Copia as entradas do índice para um System.Array, começando em um índice específico do System.Array. |
| [Delete](../../aspose.pdf/outlineitemcollection/delete/#delete)() | Exclui este item de índice da hierarquia de índice do documento. |
| [Delete](../../aspose.pdf/outlineitemcollection/delete/#delete_1)(string) | Exclui a entrada do índice com o nome especificado da hierarquia de índice do documento. |
| override [GetEnumerator](../../aspose.pdf/outlineitemcollection/getenumerator/)() | Retorna um enumerador que itera pela coleção. |
| [Insert](../../aspose.pdf/outlineitemcollection/insert/)(int, OutlineItemCollection) | Insere o item de índice na coleção no local especificado. |
| [Remove](../../aspose.pdf/outlineitemcollection/remove/#remove_1)(int) | Remove o item pelo índice. |
| override [Remove](../../aspose.pdf/outlineitemcollection/remove/#remove)(OutlineItemCollection) | Remove o item da coleção de índice. |

### Veja Também

* classe [Outlines](../outlines/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)