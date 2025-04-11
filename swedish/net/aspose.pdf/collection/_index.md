---
title: Class Collection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Collection klass. Representerar klass för Collection12.3.5 Samlingar
type: docs
weight: 3020
url: /sv/net/aspose.pdf/collection/
---
## Samling klass

Representerar klass för Collection(12.3.5 Samlingar).

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
| [Keys](../../aspose.pdf/embeddedfilecollection/keys/) { get; } | Returnerar lista över filbilagans nycklar. |
| [Schema](../../aspose.pdf/collection/schema/) { get; } | Hämtar ett "Schema" för en dokumentsamling. |
| [SyncRoot](../../aspose.pdf/embeddedfilecollection/syncroot/) { get; } | Hämtar ett objekt som kan användas för att synkronisera åtkomst till denna samling. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Add](../../aspose.pdf/embeddedfilecollection/add/)(FileSpecification) | Lägger till inbäddad filspecifikation i samlingen. |
| [Add](../../aspose.pdf/embeddedfilecollection/add/)(string, FileSpecification) | Lägger till fil i inbäddade filer med den angivna nyckeln. |
| [CopyTo](../../aspose.pdf/embeddedfilecollection/copyto/)(FileSpecification[], int) | Kopierar array av FileSpecification-objekt till samlingen. |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/)() | Tar bort alla inbäddade filer från dokumentet. |
| [Delete](../../aspose.pdf/embeddedfilecollection/delete/)(string) | Tar bort inbäddad fil efter namn. |
| [DeleteByKey](../../aspose.pdf/embeddedfilecollection/deletebykey/)(string) | Tar bort fil från samlingen efter dess nyckel i samlingen. |
| [FindByName](../../aspose.pdf/embeddedfilecollection/findbyname/)(string) | Returnerar inbäddad fil efter dess namn. |
| [GetEnumerator](../../aspose.pdf/embeddedfilecollection/getenumerator/)() | Returnerar samlingsenumerator. |
| [GetSortedCollection](../../aspose.pdf/collection/getsortedcollection/)() | Hämtar en samling av filer sorterade enligt specifikationen. |

### Se Även

* klass [EmbeddedFileCollection](../embeddedfilecollection/)
* namnrymd [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)