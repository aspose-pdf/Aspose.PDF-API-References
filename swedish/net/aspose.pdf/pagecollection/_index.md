---
title: "Klass PageCollection"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.PageCollection-klass. Samling av PDF-dokumentets sidor"
type: docs
weight: 8220
url: /sv/net/aspose.pdf/pagecollection/
---
## PageCollection class

Samling av PDF-dokumentsidor.

```csharp
public sealed class PageCollection : ICollection<Page>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Count](../../aspose.pdf/pagecollection/count/) { get; } | Hämtar antalet sidor i dokumentet. |
| [IsReadOnly](../../aspose.pdf/pagecollection/isreadonly/) { get; } | Hämtar värdet som indikerar om samlingen är skrivskyddad. Returnerar alltid falskt. |
| [IsSynchronized](../../aspose.pdf/pagecollection/issynchronized/) { get; } | Returnerar true om objektet är synkroniserat. |
| [Item](../../aspose.pdf/pagecollection/item/) { get; } | Hämtar sida efter index. |
| [SyncRoot](../../aspose.pdf/pagecollection/syncroot/) { get; } | Hämtar synkroniseringsobjektet för samlingen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept)(AnnotationSelector) | Accepterar [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/) besökarobjekt som tillhandahåller funktionalitet för att arbeta med annotationer. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_1)(ImagePlacementAbsorber) | Accepterar [`ImagePlacementAbsorber`](../imageplacementabsorber/) besökarobjekt som tillhandahåller funktionalitet för att arbeta med bildplaceringsobjekt. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_2)(TextAbsorber) | Accepterar [`TextAbsorber`](../../aspose.pdf.text/textabsorber/) besökarobjekt som tillhandahåller funktionalitet för att arbeta med textobjekt. |
| [Accept](../../aspose.pdf/pagecollection/accept/#accept_3)(TextFragmentAbsorber) | Accepterar [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) besökarobjekt som tillhandahåller funktionalitet för att arbeta med textobjekt. |
| [Add](../../aspose.pdf/pagecollection/add/#add)() | Lägger till en tom sida. Om dokumentet redan innehåller sidor med olika storlekar, kommer storleken på den mest förekommande sidan att väljas. Om det bara finns två olika sidor, kommer storleken på den första sidan att användas. |
| [Add](../../aspose.pdf/pagecollection/add/#add_3)(ICollection&lt;Page&gt;) | Lägger till alla sidor från listan i samlingen. |
| [Add](../../aspose.pdf/pagecollection/add/#add_1)(Page) | Lägger till en sida i samlingen. |
| [Add](../../aspose.pdf/pagecollection/add/#add_2)(Page[]) | Lägger till alla sidor från arrayen i samlingen. |
| [Clear](../../aspose.pdf/pagecollection/clear/)() | Rensa sidinsamlingen. |
| [Contains](../../aspose.pdf/pagecollection/contains/)(Page) | Bestämmer om den här instansen innehåller objektet. |
| [CopyTo](../../aspose.pdf/pagecollection/copyto/)(Page[], int) | Kopierar sidor till dokumentet. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete)() | Tar bort alla sidor från samlingen. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete_1)(int) | Ta bort angiven sida. |
| [Delete](../../aspose.pdf/pagecollection/delete/#delete_2)(int[]) | Ta bort sidor vars nummer är angivna i en array. |
| [Flatten](../../aspose.pdf/pagecollection/flatten/)() | Tar bort alla fält som finns på sidorna och placerar deras värden istället. |
| [FreeMemory](../../aspose.pdf/pagecollection/freememory/)() | Rensar cachad data |
| [GetEnumerator](../../aspose.pdf/pagecollection/getenumerator/)() | Returnerar en enumerator för sidor. |
| [IndexOf](../../aspose.pdf/pagecollection/indexof/)(Page) | Returnerar index för den angivna sidan. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert)(int) | Infoga en tom sida i samlingen på den angivna positionen. Om dokumentet redan innehåller sidor med olika storlekar kommer storleken på den mest förekommande sidan att väljas. Om det bara finns två olika sidor kommer storleken på den första sidan att användas. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_3)(int, ICollection&lt;Page&gt;) | Infogar sidor från samlingen i dokumentet. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_1)(int, Page) | Infogar en sida i sidinsamlingen på angiven plats. |
| [Insert](../../aspose.pdf/pagecollection/insert/#insert_2)(int, Page[]) | Infogar sidor från arrayen i dokumentet. |
| [Remove](../../aspose.pdf/pagecollection/remove/)(Page) | Tar bort det angivna objektet, kastar NotSupportedException. |

### Se även

* class [Page](../page/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


