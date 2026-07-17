---
title: ComparisonMode
linktitle: ComparisonMode
second_title: Aspose.PDF for Java API Reference
description: The comparison mode enumeration.
type: docs
weight: 10
url: /java/com.aspose.pdf.comparison.sidebysidecomparison/comparisonmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.comparison.sidebysidecomparison.ComparisonMode, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.comparison.sidebysidecomparison.ComparisonMode, com.aspose.ms.System.Enum, com.aspose.pdf.comparison.sidebysidecomparison.ComparisonMode

```
public final class ComparisonMode extends com.aspose.ms.System.Enum
```

The comparison mode enumeration.

## Fields

| Field | Description |
| --- | --- |
| [IgnoreSpaces](#IgnoreSpaces) | All spaces are ignored. Changes are sought only in words. |
| [Normal](#Normal) | Normal mode. Only spaces within text fragments are taken into account (depending on the way the document is generated.) |
| [ParseSpaces](#ParseSpaces) | The mode is similar to normal, but attempts to account for visual spacing between text fragments based on distance. Recognizing the number of spaces between fragments may not be accurate because this greatly depends on how the documents are generated. If documents are created by different generators, there may be inaccuracies in comparing spaces between text fragments. This option may produce results that, while logical, differ from the expected comparison outcomes when applied to complexly structured documents. |

### IgnoreSpaces {#IgnoreSpaces}
```
public static final int IgnoreSpaces
```

All spaces are ignored. Changes are sought only in words.

### Normal {#Normal}
```
public static final int Normal
```

Normal mode. Only spaces within text fragments are taken into account (depending on the way the document is generated.)

### ParseSpaces {#ParseSpaces}
```
public static final int ParseSpaces
```

The mode is similar to normal, but attempts to account for visual spacing between text fragments based on distance. Recognizing the number of spaces between fragments may not be accurate because this greatly depends on how the documents are generated. If documents are created by different generators, there may be inaccuracies in comparing spaces between text fragments. This option may produce results that, while logical, differ from the expected comparison outcomes when applied to complexly structured documents.
