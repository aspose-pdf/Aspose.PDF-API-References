---
title: Class Element
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Structure.Element klass. Klass som representerar baselementet i den logiska strukturen
type: docs
weight: 10140
url: /sv/net/aspose.pdf.structure/element/
---
## Element klass

Klass som representerar baselementet i den logiska strukturen.

```csharp
public abstract class Element
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| virtual [ActualText](../../aspose.pdf.structure/element/actualtext/) { get; set; } | (Valfritt; PDF 1.4) Text som är en exakt ersättning för strukturelementet och dess barn. Denna ersättningstext (som bör tillämpas på så liten del av innehållet som möjligt) är användbar när man extraherar dokumentets innehåll för att stödja tillgänglighet för användare med funktionsnedsättningar eller för andra ändamål. |
| virtual [Alt](../../aspose.pdf.structure/element/alt/) { get; set; } | (Valfritt) En alternativ beskrivning av strukturelementet och dess barn i läsbar form, vilket är användbart när man extraherar dokumentets innehåll för att stödja tillgänglighet för användare med funktionsnedsättningar eller för andra ändamål. |
| [Children](../../aspose.pdf.structure/element/children/) { get; } | Hämtar samlingen av barn-element. |
| virtual [E](../../aspose.pdf.structure/element/e/) { get; set; } | (Valfritt; PDF 1.5) Den utvidgade formen av en förkortning. |
| virtual [Lang](../../aspose.pdf.structure/element/lang/) { get; set; } | (Valfritt; PDF 1.4) Ett språk som specificerar det naturliga språket för all text i strukturelementet utom där det åsidosätts av språkspecifikationer för nästlade strukturelement eller markerat innehåll. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Remove](../../aspose.pdf.structure/element/remove/)() | Ta bort element. |

### Se Även

* namespace [Aspose.Pdf.Structure](../../aspose.pdf.structure/)
* assembly [Aspose.PDF](../../)