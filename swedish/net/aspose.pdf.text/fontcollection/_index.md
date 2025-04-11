---
title: Class FontCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.FontCollection klass. Representerar teckensnittssamling
type: docs
weight: 10530
url: /sv/net/aspose.pdf.text/fontcollection/
---
## FontCollection klass

Representerar teckensnittssamling.

```csharp
public sealed class FontCollection : ICollection<Font>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Count](../../aspose.pdf.text/fontcollection/count/) { get; } | Hämtar antalet [`Font`](../font/) objekt som faktiskt finns i samlingen. |
| [IsReadOnly](../../aspose.pdf.text/fontcollection/isreadonly/) { get; } | Hämtar ett värde som indikerar om samlingen är skrivskyddad |
| [IsSynchronized](../../aspose.pdf.text/fontcollection/issynchronized/) { get; } | Hämtar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). |
| [Item](../../aspose.pdf.text/fontcollection/item/) { get; } | Hämtar teckensnittsobjektet vid det angivna indexet. (2 indexerare) |
| [SyncRoot](../../aspose.pdf.text/fontcollection/syncroot/) { get; } | Hämtar ett objekt som kan användas för att synkronisera åtkomst till samlingen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Add](../../aspose.pdf.text/fontcollection/add/)(Font, out string) | Lägger till ett nytt teckensnitt till teckensnittresurser och returnerar det automatiskt tilldelade namnet på teckensnittsresursen. |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains)(Font) | Bestämmer om samlingen innehåller ett specifikt värde. |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains_1)(string) | Kontrollerar om teckensnittet finns i teckensnittssamlingen. |
| [CopyTo](../../aspose.pdf.text/fontcollection/copyto/)(Font[], int) | Kopierar hela samlingen till en kompatibel en-dimensionell Array, som börjar vid det angivna indexet i målarrayen |
| [GetEnumerator](../../aspose.pdf.text/fontcollection/getenumerator/)() | Returnerar en enumerator för hela samlingen. |
| [Remove](../../aspose.pdf.text/fontcollection/remove/)(Font) | Tar bort det angivna objektet från samlingen. |

## Kommentarer

Teckensnittssamlingar som representeras av `FontCollection` klassen används i flera scenarier. Till exempel, i resurser med [`Fonts`](../../aspose.pdf/resources/fonts/) egenskap.

## Exempel

Exemplet visar hur man gör alla teckensnitt som deklarerats på sidan som inbäddade.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// ensure all fonts declared on page resources are embedded
// note that if fonts are declared on form resources they are not accessible from page resources
foreach(Aspose.Pdf.Txt.Font font in doc.Pages[1].Resources.Fonts)
{
    if(!font.IsEmbedded)
        font.IsEmbedded = true;
}

doc.Save(@"D:\Tests\input.pdf");
```

### Se Även

* klass [Font](../font/)
* namnrymd [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)