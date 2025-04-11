---
title: Class TextExtractionErrorLocation
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextExtractionErrorLocation klass. Representerar platsen i PDF-dokumentet där textutvinningsfel har uppstått
type: docs
weight: 10880
url: /sv/net/aspose.pdf.text/textextractionerrorlocation/
---
## TextExtractionErrorLocation klass

Representerar platsen i PDF-dokumentet där textutvinningsfel har uppstått.

```csharp
public sealed class TextExtractionErrorLocation
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [FontUsedKey](../../aspose.pdf.text/textextractionerrorlocation/fontusedkey/) { get; } | Nyckel (namn) för PDF-teckensnittobjektet som används för att visa operatören som orsakar textutvinningsfel. |
| [FormKey](../../aspose.pdf.text/textextractionerrorlocation/formkey/) { get; } | Nyckel (namn) för PDF Form XObject där innehållsströmmen har lokaliserat textutvinningsfelet. Inte tom om ObjectType == 'xForm'. |
| [ObjectType](../../aspose.pdf.text/textextractionerrorlocation/objecttype/) { get; } | Typ av PDF-objekt (Sida eller xForm) där innehållsströmmen har lokaliserat textutvinningsfelet. |
| [OperatorIndex](../../aspose.pdf.text/textextractionerrorlocation/operatorindex/) { get; } | Index för textvisande operatör i innehållsströmmen (operatörssamling) som orsakar textutvinningsfel. |
| [OperatorString](../../aspose.pdf.text/textextractionerrorlocation/operatorstring/) { get; } | Textvisande operatör som orsakar textutvinningsfel. |
| [PageNumber](../../aspose.pdf.text/textextractionerrorlocation/pagenumber/) { get; } | Nummer på dokumentets sida där textutvinningsfelet har lokaliserats. |
| [Path](../../aspose.pdf.text/textextractionerrorlocation/path/) { get; } | Plats i PDF-dokumentet där textutvinningsfel har uppstått. |
| [TextStartPoint](../../aspose.pdf.text/textextractionerrorlocation/textstartpoint/) { get; } | Nyckel (namn) för PDF-teckensnittobjektet som används för att visa operatören som orsakar textutvinningsfel. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [ToString](../../aspose.pdf.text/textextractionerrorlocation/tostring/)() | Returnerar strängrepresentation. |

### Se Även

* namnrymd [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)