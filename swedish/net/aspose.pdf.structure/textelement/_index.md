---
title: Class TextElement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Structure.TextElement klass. Allmän textkomponent av dokumentets logiska struktur
type: docs
weight: 10190
url: /sv/net/aspose.pdf.structure/textelement/
---
## TextElement klass

Allmän textkomponent av dokumentets logiska struktur.

```csharp
public class TextElement : Element
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| virtual [ActualText](../../aspose.pdf.structure/element/actualtext/) { get; set; } | (Valfritt; PDF 1.4) Text som är en exakt ersättning för strukturkomponenten och dess barn. Denna ersättningstext (som bör tillämpas på så liten del av innehållet som möjligt) är användbar när man extraherar dokumentets innehåll för att stödja tillgänglighet för användare med funktionsnedsättningar eller för andra ändamål. |
| virtual [Alt](../../aspose.pdf.structure/element/alt/) { get; set; } | (Valfritt) En alternativ beskrivning av strukturkomponenten och dess barn i människoläsbar form, vilket är användbart när man extraherar dokumentets innehåll för att stödja tillgänglighet för användare med funktionsnedsättningar eller för andra ändamål. |
| [Children](../../aspose.pdf.structure/element/children/) { get; } | Hämtar samlingen av barnkomponenter. |
| virtual [E](../../aspose.pdf.structure/element/e/) { get; set; } | (Valfritt; PDF 1.5) Den utvidgade formen av en förkortning. |
| virtual [Lang](../../aspose.pdf.structure/element/lang/) { get; set; } | (Valfritt; PDF 1.4) Ett språk som specificerar det naturliga språket för all text i strukturkomponenten utom där det åsidosätts av språkspecifikationer för nästlade strukturkomponenter eller markerat innehåll. |
| [Text](../../aspose.pdf.structure/textelement/text/) { get; } | Hämtar värdet av textstrukturkomponenten. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Remove](../../aspose.pdf.structure/element/remove/)() | Ta bort komponent. |

### Se Även

* klass [Element](../element/)
* namnrymd [Aspose.Pdf.Structure](../../aspose.pdf.structure/)
* sammansättning [Aspose.PDF](../../)