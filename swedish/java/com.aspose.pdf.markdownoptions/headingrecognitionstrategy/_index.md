---
title: "HeadingRecognitionStrategy"
linktitle: "HeadingRecognitionStrategy"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar typer av strategier för rubrikigenkänning."
type: docs
weight: 30
url: /sv/java/com.aspose.pdf.markdownoptions/headingrecognitionstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.markdownoptions.HeadingRecognitionStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.markdownoptions.HeadingRecognitionStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.markdownoptions.HeadingRecognitionStrategy

```
public final class HeadingRecognitionStrategy extends com.aspose.ms.System.Enum
```

Representerar typer av strategier för rubrikigenkänning.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [Auto](#Auto) | Tillhandahåller ett automatiskt val av rubrikigenkänningsstrategi. Detta är standardalternativet. Om dokumentet innehåller bokmärken kommer {@link HeadingRecognitionStrategy#Outlines} strategin att väljas, annars {@link HeadingRecognitionStrategy#Heuristic} |
| [Heuristic](#Heuristic) | Representerar rubrikigenkänningsstrategin genom heuristiska regler och teckenstorleksstatistik. |
| [None](#None) | Känn inte igen rubriker. Detta alternativ kan vara användbart i komplext formaterade dokument. |
| [Outlines](#Outlines) | Representerar rubrikigenkänningsstrategin genom konturer. |

### Auto {#Auto}
```
public static final int Auto
```

Tillhandahåller ett automatiskt val av rubrikigenkänningsstrategi. Detta är standardalternativet. Om dokumentet innehåller bokmärken kommer {@link HeadingRecognitionStrategy#Outlines} strategin att väljas, annars {@link HeadingRecognitionStrategy#Heuristic}

### Heuristic {#Heuristic}
```
public static final int Heuristic
```

Representerar rubrikigenkänningsstrategin genom heuristiska regler och teckenstorleksstatistik.

### None {#None}
```
public static final int None
```

Känn inte igen rubriker. Detta alternativ kan vara användbart i komplext formaterade dokument.

### Outlines {#Outlines}
```
public static final int Outlines
```

Representerar rubrikigenkänningsstrategin genom konturer.
