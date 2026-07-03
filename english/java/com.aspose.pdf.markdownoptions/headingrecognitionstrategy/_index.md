---
title: HeadingRecognitionStrategy
linktitle: HeadingRecognitionStrategy
second_title: Aspose.PDF for Java API Reference
description: Represents types of header recognition strategies.
type: docs
weight: 30
url: /java/com.aspose.pdf.markdownoptions/headingrecognitionstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.markdownoptions.HeadingRecognitionStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.markdownoptions.HeadingRecognitionStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.markdownoptions.HeadingRecognitionStrategy

```
public final class HeadingRecognitionStrategy extends com.aspose.ms.System.Enum
```

Represents types of header recognition strategies.

## Fields

| Field | Description |
| --- | --- |
| [Auto](#Auto) | Provides an automatic header recognition strategy selection. This is the default option. If the document contains bookmarks, the {@link HeadingRecognitionStrategy#Outlines} strategy will be selected, otherwise {@link HeadingRecognitionStrategy#Heuristic} |
| [Heuristic](#Heuristic) | Represents the header recognition strategy by means of heuristics rules and font size statistic. |
| [None](#None) | Do not recognize headers. This option can be useful in complexly formatted documents. |
| [Outlines](#Outlines) | Represents the header recognition strategy by means of outlines. |

### Auto {#Auto}
```
public static final int Auto
```

Provides an automatic header recognition strategy selection. This is the default option. If the document contains bookmarks, the {@link HeadingRecognitionStrategy#Outlines} strategy will be selected, otherwise {@link HeadingRecognitionStrategy#Heuristic}

### Heuristic {#Heuristic}
```
public static final int Heuristic
```

Represents the header recognition strategy by means of heuristics rules and font size statistic.

### None {#None}
```
public static final int None
```

Do not recognize headers. This option can be useful in complexly formatted documents.

### Outlines {#Outlines}
```
public static final int Outlines
```

Represents the header recognition strategy by means of outlines.
