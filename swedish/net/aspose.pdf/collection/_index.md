---
title: "Klass Collection"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Collection-klass. Representerar klassen för Collection12.3.5 Collections."
type: docs
weight: 3130
url: /sv/net/aspose.pdf/collection/
---
## Collection class

Representerar en klass för Collection (12.3.5 Collections).

```csharp
public class Collection : EmbeddedFileCollection
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Collection](collection/)() | Initierar ett nytt Collection-objekt. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Count](../../aspose.pdf/embeddedfilecollection/count/) { get; } | Hämtar antalet inbäddade filer i samlingen. |
| [DefaultEntry](../../aspose.pdf/collection/defaultentry/) { get; } | Standardnamn för inbäddad fil. |
| [IsSynchronized](../../aspose.pdf/embeddedfilecollection/issynchronized/) { get; } | Hämtar ett värde som indikerar om åtkomst till denna samling är synkroniserad (trådsäker). |
| [Item](../../aspose.pdf/embeddedfilecollection/item/) { get; } | Hämtar inbäddad fil efter dess index. (2 indexerare) |
| [Keys](../../aspose.pdf/embeddedfilecollection/keys/) { get; } | Returnerar en lista med nycklar för filbilagor. |
| [Schema](../../aspose.pdf/collection/schema/) { get; } | Hämtar ett "Schema" av en dokumentsamling. |
| [SyncRoot](../../aspose.pdf/embeddedfilecollection/syncroot/) { get; } | Hämtar ett objekt som kan användas för att synkronisera åtkomst till denna samling. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Add](../../aspose.pdf/embeddedfilecollection/add/)(FileSpecification) | Lägger till inbäddad filspecificering i samlingen. |
| [Add](../../aspose.pdf/embeddedfilecollection/add/)(string, FileSpecification) | Lägger till fil i inbäddade filer med den angivna nyckeln. |
| [CopyTo](../../aspose.pdf/embeddedfilecollection/copyto/)(FileSpecification[], int) | Kopierar array av FileSpecification-objekt till colleciton. |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/)() | Ta bort alla inbäddade filer från dokumentet. |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/)(string) | Radera inbäddad fil efter namn. |
| [DeleteByKey](../../aspose.pdf/embeddedfilecollection/deletebykey/)(string) | Raderar fil från samlingen med dess nyckel i samlingen. |
| [FindByName](../../aspose.pdf/embeddedfilecollection/findbyname/)(string) | Returnerar inbäddad fil efter dess namn. |
| [GetEnumerator](../../aspose.pdf/embeddedfilecollection/getenumerator/)() | Returnerar colleciton-enumerator. |
| [GetSortedCollection](../../aspose.pdf/collection/getsortedcollection/)() | Hämtar en samling filer sorterade enligt specifikationen. |

### Se även

* class [EmbeddedFileCollection](../embeddedfilecollection/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


