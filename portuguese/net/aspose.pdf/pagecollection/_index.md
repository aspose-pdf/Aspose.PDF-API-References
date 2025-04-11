---
title: Class PageCollection
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.PageCollection. Coleção de páginas de documentos PDF
type: docs
weight: 8080
url: /pt/net/aspose.pdf/pagecollection/
---
## Classe PageCollection

Coleção de páginas de documentos PDF.

```csharp
public sealed class PageCollection : ICollection<Page>
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Count](../../aspose.pdf/pagecollection/count/) { get; } | Obtém a contagem de páginas no documento. |
| [IsReadOnly](../../aspose.pdf/pagecollection/isreadonly/) { get; } | Obtém o valor que indica se a coleção é somente leitura. Sempre retorna falso. |
| [IsSynchronized](../../aspose.pdf/pagecollection/issynchronized/) { get; } | Retorna verdadeiro se o objeto estiver sincronizado. |
| [Item](../../aspose.pdf/pagecollection/item/) { get; } | Obtém a página pelo índice. |
| [SyncRoot](../../aspose.pdf/pagecollection/syncroot/) { get; } | Obtém o objeto de sincronização da coleção. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept)(AnnotationSelector) | Aceita o objeto visitante [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/) que fornece funcionalidade para trabalhar com anotações. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_1)(ImagePlacementAbsorber) | Aceita o objeto visitante [`ImagePlacementAbsorber`](../imageplacementabsorber/) que fornece funcionalidade para trabalhar com objetos de colocação de imagem. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_2)(TextAbsorber) | Aceita o objeto visitante [`TextAbsorber`](../../aspose.pdf.text/textabsorber/) que fornece funcionalidade para trabalhar com objetos de texto. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_3)(TextFragmentAbsorber) | Aceita o objeto visitante [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) que fornece funcionalidade para trabalhar com objetos de texto. |
| [Add](../../aspose.pdf/pagecollection/add/#add)() | Adiciona uma página vazia. Se o documento já contém páginas com tamanhos variados, o tamanho da página que ocorre com mais frequência será selecionado. No caso de haver apenas duas páginas diferentes, o tamanho da primeira página será utilizado. |
| [Add](../../aspose.pdf/pagecollection/add/#add_3)(ICollection&lt;Page&gt;) | Adiciona à coleção todas as páginas da lista. |
| [Add](../../aspose.pdf/pagecollection/add/#add_1)(Page) | Adiciona a página à coleção. |
| [Add](../../aspose.pdf/pagecollection/add/#add_2)(Page[]) | Adiciona à coleção todas as páginas do array. |
| [Clear](../../aspose.pdf/pagecollection/clear/)() | Limpa a coleção de páginas. |
| [Contains](../../aspose.pdf/pagecollection/contains/)(Page) | Determina se esta instância contém o objeto. |
| [CopyTo](../../aspose.pdf/pagecollection/copyto/)(Page[], int) | Copia páginas para o documento. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete)() | Exclui todas as páginas da coleção. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete_1)(int) | Exclui a página especificada. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete_2)(int[]) | Exclui as páginas especificadas cujos números estão no array. |
| [Flatten](../../aspose.pdf/pagecollection/flatten/)() | Remove todos os campos localizados nas páginas e coloca seus valores no lugar. |
| [FreeMemory](../../aspose.pdf/pagecollection/freememory/)() | Limpa os dados em cache. |
| [GetEnumerator](../../aspose.pdf/pagecollection/getenumerator/)() | Retorna o enumerador de páginas. |
| [IndexOf](../../aspose.pdf/pagecollection/indexof/)(Page) | Retorna o índice da página especificada. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert)(int) | Insere uma página vazia na coleção na posição especificada. Se o documento já contém páginas com tamanhos variados, o tamanho da página que ocorre com mais frequência será selecionado. No caso de haver apenas duas páginas diferentes, o tamanho da primeira página será utilizado. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_3)(int, ICollection&lt;Page&gt;) | Insere páginas da coleção no documento. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_1)(int, Page) | Insere a página na coleção de páginas no local especificado. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_2)(int, Page[]) | Insere as páginas do array no documento. |
| [Remove](../../aspose.pdf/pagecollection/remove/)(Page) | Remove o item especificado, lança NotSupportedException. |

### Veja Também

* classe [Page](../page/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)