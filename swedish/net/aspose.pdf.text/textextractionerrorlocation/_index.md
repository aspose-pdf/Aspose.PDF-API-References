---
title: "Class TextExtractionErrorLocation"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Text.TextExtractionErrorLocation class. Representerar platsen i PDF-dokumentet där ett textutvinningsfel har uppstått"
type: docs
weight: 11060
url: /sv/net/aspose.pdf.text/textextractionerrorlocation/
---
## TextExtractionErrorLocation class

Representerar platsen i PDF-dokumentet där felet vid textutdragning har uppstått.

```csharp
public sealed class TextExtractionErrorLocation
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [FontUsedKey](../../aspose.pdf.text/textextractionerrorlocation/fontusedkey/) { get; } | Nyckel (namn) för PDF Font-objektet som används för att visa operatorn som orsakar textutvinningsfel. |
| [FormKey](../../aspose.pdf.text/textextractionerrorlocation/formkey/) { get; } | Nyckel (namn) för PDF Form XObject där innehållsströmens textutvinningsfel har placerats. Inte tom om ObjectType == 'xForm'. |
| [ObjectType](../../aspose.pdf.text/textextractionerrorlocation/objecttype/) { get; } | Typ av PDF-objekt (Page eller xForm) där innehållsströmens textutvinningsfel har placerats. |
| [OperatorIndex](../../aspose.pdf.text/textextractionerrorlocation/operatorindex/) { get; } | Index för textvisningsoperator i innehållsströmmen (operator-samling) som orsakar textutvinningsfel. |
| [OperatorString](../../aspose.pdf.text/textextractionerrorlocation/operatorstring/) { get; } | Textvisningsoperator som orsakar textutvinningsfel. |
| [PageNumber](../../aspose.pdf.text/textextractionerrorlocation/pagenumber/) { get; } | Nummer på dokumentsidan där textutvinningsfelet har placerats. |
| [Path](../../aspose.pdf.text/textextractionerrorlocation/path/) { get; } | Plats för PDF-dokumentet där fel vid textutdragning har uppstått. |
| [TextStartPoint](../../aspose.pdf.text/textextractionerrorlocation/textstartpoint/) { get; } | Nyckel (namn) för PDF Font-objektet som används för att visa operatorn som orsakar textutvinningsfel. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [ToString](../../aspose.pdf.text/textextractionerrorlocation/tostring/)() | Returnerar strängrepresentation. |

### Se även

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


