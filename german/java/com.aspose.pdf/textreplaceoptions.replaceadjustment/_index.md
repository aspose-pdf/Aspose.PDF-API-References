---
title: "TextReplaceOptions.ReplaceAdjustment"
linktitle: "TextReplaceOptions.ReplaceAdjustment"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Bestimmt die Aktion, die nach dem Ersetzen eines Textfragmentes durch ein kürzeres durchgeführt wird. None – keine Aktion, der ersetzte Text kann den Rest der Zeile überlappen; AdjustSpaceWidth – versucht es."
type: docs
weight: 5270
url: /de/java/com.aspose.pdf/textreplaceoptions.replaceadjustment/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment, com.aspose.ms.System.Enum, com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment

```
public static final class TextReplaceOptions.ReplaceAdjustment extends com.aspose.ms.System.Enum
```

Bestimmt die Aktion, die nach dem Ersetzen eines Textfragments durch ein kürzeres ausgeführt wird. None - keine Aktion, ersetzter Text kann den Rest der Zeile überlappen; AdjustSpaceWidth - versucht, die Abstände zwischen den Wörtern anzupassen, um die Zeilenlänge beizubehalten; WholeWordsHyphenation - versucht, Wörter zwischen den Absatzzeilen zu verteilen, um das rechte Feld des Absatzes beizubehalten; ShiftRestOfLine - verschiebt den Rest der Zeile entsprechend der veränderten Textlänge, die Zeilenlänge kann geändert werden; Der Standardwert ist ShiftRestOfLine.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [AdjustSpaceWidth](#AdjustSpaceWidth) | Versucht, die Abstände zwischen Wörtern anzupassen, um die Zeilenlänge beizubehalten. |
| [IsFormFillingMode](#IsFormFillingMode) | Versucht, die Wörter im verfügbaren Weißraum anhand der Absatzbreite zu verteilen. Wenn der Text überläuft, wird er ausgeblendet. |
| [None](#None) | Keine Aktion, der ersetzte Text kann den Rest der Zeile überlappen |
| [ShiftRestOfLine](#ShiftRestOfLine) | (Standard) Verschiebt den Rest der Zeile entsprechend der veränderten Textlänge, die Zeilenlänge kann geändert werden |
| [WholeWordsHyphenation](#WholeWordsHyphenation) | Versucht, Wörter zwischen Absatzzeilen zu verteilen, um das rechte Feld des Absatzes beizubehalten |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [hasFlag](#hasFlag-int-int-) |  |

### AdjustSpaceWidth {#AdjustSpaceWidth}
```
public static final int AdjustSpaceWidth
```

Versucht, die Abstände zwischen Wörtern anzupassen, um die Zeilenlänge beizubehalten.

### IsFormFillingMode {#IsFormFillingMode}
```
public static final int IsFormFillingMode
```

Versucht, die Wörter im verfügbaren Weißraum anhand der Absatzbreite zu verteilen. Wenn der Text überläuft, wird er ausgeblendet.

### None {#None}
```
public static final int None
```

Keine Aktion, der ersetzte Text kann den Rest der Zeile überlappen

### ShiftRestOfLine {#ShiftRestOfLine}
```
public static final int ShiftRestOfLine
```

(Standard) Verschiebt den Rest der Zeile entsprechend der veränderten Textlänge, die Zeilenlänge kann geändert werden

### WholeWordsHyphenation {#WholeWordsHyphenation}
```
public static final int WholeWordsHyphenation
```

Versucht, Wörter zwischen Absatzzeilen zu verteilen, um das rechte Feld des Absatzes beizubehalten

### hasFlag {#hasFlag-int-int-}
```
public static boolean hasFlag(int flag, int flagToCheck)
```



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Flag |  |  |
| flagToCheck |  |  |
