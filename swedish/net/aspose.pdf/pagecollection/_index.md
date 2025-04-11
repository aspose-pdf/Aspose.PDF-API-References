---
title: Class PageCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PageCollection klass. Samling av PDF-dokument sidor
type: docs
weight: 8080
url: /sv/net/aspose.pdf/pagecollection/
---
## PageCollection klass

Samling av PDF-dokument sidor.

```csharp
public sealed class PageCollection : ICollection<Page>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Count](../../aspose.pdf/pagecollection/count/) { get; } | Hämtar antalet sidor i dokumentet. |
| [IsReadOnly](../../aspose.pdf/pagecollection/isreadonly/) { get; } | Hämtar värde som indikerar om samlingen är skrivskyddad. Återger alltid false. |
| [IsSynchronized](../../aspose.pdf/pagecollection/issynchronized/) { get; } | Återger true om objektet är synkroniserat. |
| [Item](../../aspose.pdf/pagecollection/item/) { get; } | Hämtar sidan efter index. |
| [SyncRoot](../../aspose.pdf/pagecollection/syncroot/) { get; } | Hämtar synkroniseringsobjektet för samlingen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept)(AnnotationSelector) | Accepterar [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/) besöksobjekt som tillhandahåller funktionalitet för att arbeta med anteckningar. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_1)(ImagePlacementAbsorber) | Accepterar [`ImagePlacementAbsorber`](../imageplacementabsorber/) besöksobjekt som tillhandahåller funktionalitet för att arbeta med bildplacering objekt. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_2)(TextAbsorber) | Accepterar [`TextAbsorber`](../../aspose.pdf.text/textabsorber/) besöksobjekt som tillhandahåller funktionalitet för att arbeta med textobjekt. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_3)(TextFragmentAbsorber) | Accepterar [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) besöksobjekt som tillhandahåller funktionalitet för att arbeta med textobjekt. |
| [Add](../../aspose.pdf/pagecollection/add/#add)() | Lägger till en tom sida. Om dokumentet redan innehåller sidor med varierande storlekar kommer storleken på den mest frekvent förekommande sidan att väljas. Om det bara finns två olika sidor kommer storleken på den första sidan att användas. |
| [Add](../../aspose.pdf/pagecollection/add/#add_3)(ICollection&lt;Page&gt;) | Lägger till alla sidor från listan till samlingen. |
| [Add](../../aspose.pdf/pagecollection/add/#add_1)(Page) | Lägger till sidan i samlingen. |
| [Add](../../aspose.pdf/pagecollection/add/#add_2)(Page[]) | Lägger till alla sidor från arrayen till samlingen. |
| [Clear](../../aspose.pdf/pagecollection/clear/)() | Rensar sidinsamlingen. |
| [Contains](../../aspose.pdf/pagecollection/contains/)(Page) | Bestämmer om denna instans innehåller objektet. |
| [CopyTo](../../aspose.pdf/pagecollection/copyto/)(Page[], int) | Kopierar sidor till dokumentet. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete)() | Tar bort alla sidor från samlingen. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete_1)(int) | Tar bort angiven sida. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete_2)(int[]) | Tar bort sidor som anges i arrayen. |
| [Flatten](../../aspose.pdf/pagecollection/flatten/)() | Tar bort alla fält som finns på sidorna och placerar deras värden istället. |
| [FreeMemory](../../aspose.pdf/pagecollection/freememory/)() | Rensar cachelagrad data |
| [GetEnumerator](../../aspose.pdf/pagecollection/getenumerator/)() | Återger en uppräkning av sidor. |
| [IndexOf](../../aspose.pdf/pagecollection/indexof/)(Page) | Återger index för den angivna sidan. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert)(int) | Infogar en tom sida i samlingen på den angivna positionen. Om dokumentet redan innehåller sidor med varierande storlekar kommer storleken på den mest frekvent förekommande sidan att väljas. Om det bara finns två olika sidor kommer storleken på den första sidan att användas. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_3)(int, ICollection&lt;Page&gt;) | Infogar sidor från samlingen till dokumentet. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_1)(int, Page) | Infogar sidan i sidinsamlingen på angiven plats. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_2)(int, Page[]) | Infogar sidorna från arrayen till dokumentet. |
| [Remove](../../aspose.pdf/pagecollection/remove/)(Page) | Tar bort det angivna objektet, kastar NotSupportedException. |

### Se Även

* klass [Page](../page/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* sammansättning [Aspose.PDF](../../)