---
title: "TextReplaceOptions.ReplaceAdjustment"
linktitle: "TextReplaceOptions.ReplaceAdjustment"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Determina l'azione che verrà eseguita dopo la sostituzione di un frammento di testo più breve. None - nessuna azione, il testo sostituito può sovrapporsi al resto della riga; AdjustSpaceWidth - tenta di."
type: docs
weight: 5270
url: /it/java/com.aspose.pdf/textreplaceoptions.replaceadjustment/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment, com.aspose.ms.System.Enum, com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment

```
public static final class TextReplaceOptions.ReplaceAdjustment extends com.aspose.ms.System.Enum
```

Determina l'azione da eseguire dopo la sostituzione di un frammento di testo con uno più corto. None - nessuna azione, il testo sostituito può sovrapporsi al resto della riga; AdjustSpaceWidth - tenta di regolare gli spazi tra le parole per mantenere la lunghezza della riga; WholeWordsHyphenation - tenta di distribuire le parole tra le righe del paragrafo per mantenere il margine destro del paragrafo; ShiftRestOfLine - sposta il resto della riga in base alla variazione della lunghezza del testo, la lunghezza della riga può essere modificata; Il valore predefinito è ShiftRestOfLine.

## Campi

| Campo | Descrizione |
| --- | --- |
| [AdjustSpaceWidth](#AdjustSpaceWidth) | Cerca di regolare gli spazi tra le parole per mantenere la lunghezza della riga |
| [IsFormFillingMode](#IsFormFillingMode) | Cerca di distribuire le parole nello spazio bianco disponibile usando la larghezza del paragrafo. Se il testo supera il limite, verrà nascosto. |
| [None](#None) | Nessuna azione, il testo sostituito può sovrapporsi al resto della riga |
| [ShiftRestOfLine](#ShiftRestOfLine) | (Predefinito) Sposta il resto della riga in base alla variazione della lunghezza del testo, la lunghezza della riga può cambiare |
| [WholeWordsHyphenation](#WholeWordsHyphenation) | Cerca di distribuire le parole tra le linee del paragrafo per mantenere il margine destro del paragrafo |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [hasFlag](#hasFlag-int-int-) |  |

### AdjustSpaceWidth {#AdjustSpaceWidth}
```
public static final int AdjustSpaceWidth
```

Cerca di regolare gli spazi tra le parole per mantenere la lunghezza della riga

### IsFormFillingMode {#IsFormFillingMode}
```
public static final int IsFormFillingMode
```

Cerca di distribuire le parole nello spazio bianco disponibile usando la larghezza del paragrafo. Se il testo supera il limite, verrà nascosto.

### None {#None}
```
public static final int None
```

Nessuna azione, il testo sostituito può sovrapporsi al resto della riga

### ShiftRestOfLine {#ShiftRestOfLine}
```
public static final int ShiftRestOfLine
```

(Predefinito) Sposta il resto della riga in base alla variazione della lunghezza del testo, la lunghezza della riga può cambiare

### WholeWordsHyphenation {#WholeWordsHyphenation}
```
public static final int WholeWordsHyphenation
```

Cerca di distribuire le parole tra le linee del paragrafo per mantenere il margine destro del paragrafo

### hasFlag {#hasFlag-int-int-}
```
public static boolean hasFlag(int flag, int flagToCheck)
```



**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flag |  |  |
| flagToCheck |  |  |
