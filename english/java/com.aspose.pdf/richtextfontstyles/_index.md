---
title: RichTextFontStyles
linktitle: RichTextFontStyles
second_title: Aspose.PDF for Java API Reference
description: Options for styling text fragments in RichText.
type: docs
weight: 4300
url: /java/com.aspose.pdf/richtextfontstyles/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.RichTextFontStyles, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.RichTextFontStyles, com.aspose.ms.System.Enum, com.aspose.pdf.RichTextFontStyles

```
public final class RichTextFontStyles extends com.aspose.ms.System.Enum
```

Options for styling text fragments in RichText.

## Fields

| Field | Description |
| --- | --- |
| [Bold](#Bold) | Option that specifies bold. |
| [ClearExisting](#ClearExisting) | If set, clears all existing styles before applying additional ones. When combined with other style flags (e.g., {@code RichTextFontStyles#Bold}), it first resets the styles, then applies the specified ones. Without this flag, new styles are added to the existing ones. |
| [Italic](#Italic) | Option that specifies italic. |
| [Underline](#Underline) | Option that specifies underline. |

## Methods

| Method | Description |
| --- | --- |
| [hasFlag](#hasFlag-int-int-) | Checks whether the specified flag is set. |

### Bold {#Bold}
```
public static final int Bold
```

Option that specifies bold.

### ClearExisting {#ClearExisting}
```
public static final int ClearExisting
```

If set, clears all existing styles before applying additional ones. When combined with other style flags (e.g., {@code RichTextFontStyles#Bold}), it first resets the styles, then applies the specified ones. Without this flag, new styles are added to the existing ones.

### Italic {#Italic}
```
public static final int Italic
```

Option that specifies italic.

### Underline {#Underline}
```
public static final int Underline
```

Option that specifies underline.

### hasFlag {#hasFlag-int-int-}
```
public static boolean hasFlag(int flag, int flagToCheck)
```

Checks whether the specified flag is set.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| flag |  | the enum value representing the flag to check |
| flagToCheck |  | the enum value representing the flag to check |

**Returns:**
{@code true} if the flag is set; {@code false} otherwise
