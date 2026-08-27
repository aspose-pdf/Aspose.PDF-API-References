---
title: "Klass FontCollection"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Text.FontCollection-klass. Representerar teckensnittssamling"
type: docs
weight: 10710
url: /sv/net/aspose.pdf.text/fontcollection/
---
## FontCollection class

Representerar en teckensnittssamling.

```csharp
public sealed class FontCollection : ICollection<Font>
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Count](../../aspose.pdf.text/fontcollection/count/) { get; } | Hämtar antalet [`Font`](../font/)-objektelement som faktiskt finns i samlingen. |
| [IsReadOnly](../../aspose.pdf.text/fontcollection/isreadonly/) { get; } | Hämtar ett värde som indikerar om samlingen är skrivskyddad |
| [IsSynchronized](../../aspose.pdf.text/fontcollection/issynchronized/) { get; } | Hämtar ett värde som indikerar om åtkomst till samlingen är synkroniserad (trådsäker). |
| [Item](../../aspose.pdf.text/fontcollection/item/) { get; } | Hämtar teckensnittselementet på det angivna indexet. (2 indexers) |
| [SyncRoot](../../aspose.pdf.text/fontcollection/syncroot/) { get; } | Hämtar ett objekt som kan användas för att synkronisera åtkomst till samlingen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Add](../../aspose.pdf.text/fontcollection/add/)(Font, out string) | Lägger till ett nytt teckensnitt till teckensnittsresurser och returnerar automatiskt tilldelat namn på teckensnittsresursen. |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains)(Font) | Bestämmer om samlingen innehåller ett specifikt värde. |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains_1)(string) | Kontrollerar om teckensnittet finns i teckensnittssamlingen. |
| [CopyTo](../../aspose.pdf.text/fontcollection/copyto/)(Font[], int) | Kopierar hela samlingen till en kompatibel endimensionell array, med start vid det angivna indexet i målarrayen |
| [GetEnumerator](../../aspose.pdf.text/fontcollection/getenumerator/)() | Returnerar en enumerator för hela samlingen. |
| [Remove](../../aspose.pdf.text/fontcollection/remove/)(Font) | Tar bort angivet objekt från samlingen. |

## Anmärkningar

Teckensnittssamlingar som representeras av `FontCollection`-klassen används i flera scenarier. Till exempel i resurser med [`Fonts`](../../aspose.pdf/resources/fonts/) egenskap.

## Exempel

Exemplet visar hur man gör alla teckensnitt som deklarerats på sidan inbäddade.

```csharp
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// se till att alla teckensnitt som deklarerats i sidresurser är inbäddade
// observera att om teckensnitt deklareras i formulärresurser är de inte åtkomliga från sidresurser
foreach(Aspose.Pdf.Txt.Font font in doc.Pages[1].Resources.Fonts)
{
    if(!font.IsEmbedded)
        font.IsEmbedded = true;
}

doc.Save(@"D:\Tests\input.pdf");
```

### Se även

* class [Font](../font/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


