---
title: "RichTextFontStyles"
linktitle: "RichTextFontStyles"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Optionen zum Stylen von Textfragmenten in RichText."
type: docs
weight: 4300
url: /de/java/com.aspose.pdf/richtextfontstyles/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.RichTextFontStyles, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.RichTextFontStyles, com.aspose.ms.System.Enum, com.aspose.pdf.RichTextFontStyles

```
public final class RichTextFontStyles extends com.aspose.ms.System.Enum
```

Optionen zum Stylen von Textfragmenten in RichText.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [Bold](#Bold) | Option, die Fettschrift angibt. |
| [ClearExisting](#ClearExisting) | Wenn gesetzt, werden alle vorhandenen Stile gelöscht, bevor zusätzliche angewendet werden. In Kombination mit anderen Stil-Flags (z. B. {@code RichTextFontStyles#Bold}) werden zunächst die Stile zurückgesetzt und anschließend die angegebenen angewendet. Ohne dieses Flag werden neue Stile zu den bestehenden hinzugefügt. |
| [Italic](#Italic) | Option, die Kursivschrift angibt. |
| [Underline](#Underline) | Option, die Unterstreichung angibt. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [hasFlag](#hasFlag-int-int-) | Prüft, ob das angegebene Flag gesetzt ist. |

### Bold {#Bold}
```
public static final int Bold
```

Option, die Fettschrift angibt.

### ClearExisting {#ClearExisting}
```
public static final int ClearExisting
```

Wenn gesetzt, werden alle vorhandenen Stile gelöscht, bevor zusätzliche angewendet werden. In Kombination mit anderen Stil-Flags (z. B. {@code RichTextFontStyles#Bold}) werden zunächst die Stile zurückgesetzt und anschließend die angegebenen angewendet. Ohne dieses Flag werden neue Stile zu den bestehenden hinzugefügt.

### Italic {#Italic}
```
public static final int Italic
```

Option, die Kursivschrift angibt.

### Underline {#Underline}
```
public static final int Underline
```

Option, die Unterstreichung angibt.

### hasFlag {#hasFlag-int-int-}
```
public static boolean hasFlag(int flag, int flagToCheck)
```

Prüft, ob das angegebene Flag gesetzt ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Flag |  | der Aufzählungswert, der das zu prüfende Flag repräsentiert |
| flagToCheck |  | der Aufzählungswert, der das zu prüfende Flag repräsentiert |

**Returns:**
{@code true}, wenn das Flag gesetzt ist; {@code false} sonst
