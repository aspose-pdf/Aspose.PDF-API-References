---
title: "HtmlFragment"
linktitle: "HtmlFragment"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt ein HTML‑Fragment dar."
type: docs
weight: 1950
url: /de/java/com.aspose.pdf/htmlfragment/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.FormattedFragment com.aspose.pdf.HtmlFragment, com.aspose.pdf.BaseParagraph, com.aspose.pdf.FormattedFragment com.aspose.pdf.HtmlFragment, com.aspose.pdf.FormattedFragment, com.aspose.pdf.HtmlFragment

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class HtmlFragment extends FormattedFragment
```

Stellt ein HTML‑Fragment dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [HtmlFragment](#HtmlFragment-java.lang.String-) | Initialisiert eine neue Instanz der HtmlFragment-Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [deepClone](#deepClone--) | Klont HTML-Fragment. |
| [getHtmlLoadOptions](#getHtmlLoadOptions--) | Ruft HtmlLoadOptions ab, die zum Laden (und Rendern) von HTML in diese Klasseninstanz verwendet werden. Bitte verwenden Sie sie, wenn es notwendig ist, eine spezifische Einstellung für den Import von HTML für diese oder jene Instanz zu nutzen (z. B. wenn diese oder jene Instanz einen bestimmten BasePath für importiertes HTML verwenden soll oder einen bestimmten Loader für externe Ressourcen). Wenn der Parameter standardmäßig (null) ist, werden die Standard‑HTML‑Ladeoptionen verwendet. |
| [getRectangle](#getRectangle--) | Ruft das Rechteck des HtmlFragment ab |
| [getTextState](#getTextState--) | Ruft die Schriftart ab oder legt sie fest |
| [isBreakWords](#isBreakWords--) | Ruft den Wortumbruch ab oder legt ihn fest |
| [isParagraphHasMargin](#isParagraphHasMargin--) | Ruft ab, ob der Absatz den Standardrand hat, oder legt ihn fest; andernfalls ist der Rand 0 |
| [setBreakWords](#setBreakWords-boolean-) | Ruft den Wortumbruch ab oder legt ihn fest |
| [setHtmlLoadOptions](#setHtmlLoadOptions-com.aspose.pdf.HtmlLoadOptions-) | Setzt HtmlLoadOptions, die zum Laden (und Rendern) von HTML in diese Klasseninstanz verwendet werden. Bitte verwenden Sie sie, wenn es notwendig ist, eine spezifische Einstellung für den Import von HTML für diese oder jene Instanz zu nutzen (z. B. wenn diese oder jene Instanz einen bestimmten BasePath für importiertes HTML verwenden soll oder einen bestimmten Loader für externe Ressourcen). Wenn der Parameter standardmäßig (null) ist, werden die Standard‑HTML‑Ladeoptionen verwendet. |
| [setParagraphHasMargin](#setParagraphHasMargin-boolean-) | Ruft ab, ob der Absatz den Standardrand hat, oder legt ihn fest; andernfalls ist der Rand 0 |
| [setTextState](#setTextState-com.aspose.pdf.TextState-) | Ruft die Schriftart ab oder legt sie fest |

### HtmlFragment {#HtmlFragment-java.lang.String-}
Initialisiert eine neue Instanz der HtmlFragment-Klasse.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Klont HTML-Fragment.

**Returns:**
Kloniertes HTML-Fragment-Objekt.

### getHtmlLoadOptions {#getHtmlLoadOptions--}
```
public HtmlLoadOptions getHtmlLoadOptions()
```

Ruft HtmlLoadOptions ab, die zum Laden (und Rendern) von HTML in diese Klasseninstanz verwendet werden. Bitte verwenden Sie sie, wenn es notwendig ist, eine spezifische Einstellung für den Import von HTML für diese oder jene Instanz zu nutzen (z. B. wenn diese oder jene Instanz einen bestimmten BasePath für importiertes HTML verwenden soll oder einen bestimmten Loader für externe Ressourcen). Wenn der Parameter standardmäßig (null) ist, werden die Standard‑HTML‑Ladeoptionen verwendet.

**Returns:**
HtmlLoadOptions-Wert

### getRectangle {#getRectangle--}
```
public final Rectangle2D.Float getRectangle()
```

Ruft das Rechteck des HtmlFragment ab

**Returns:**
java.awt.geom.Rectangle2D.Float-Instanz

### getTextState {#getTextState--}
```
public TextState getTextState()
```

Ruft die Schriftart ab oder legt sie fest

**Returns:**
TextState-Objekt

### isBreakWords {#isBreakWords--}
```
public final boolean isBreakWords()
```

Ruft den Wortumbruch ab oder legt ihn fest

**Returns:**
boolescher Wert

### isParagraphHasMargin {#isParagraphHasMargin--}
```
public final boolean isParagraphHasMargin()
```

Ruft ab, ob der Absatz den Standardrand hat, oder legt ihn fest; andernfalls ist der Rand 0

**Returns:**
boolescher Wert

### setBreakWords {#setBreakWords-boolean-}
```
public final void setBreakWords(boolean value)
```

Ruft den Wortumbruch ab oder legt ihn fest

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setHtmlLoadOptions {#setHtmlLoadOptions-com.aspose.pdf.HtmlLoadOptions-}
Setzt HtmlLoadOptions, die zum Laden (und Rendern) von HTML in diese Klasseninstanz verwendet werden. Bitte verwenden Sie sie, wenn es notwendig ist, eine spezifische Einstellung für den Import von HTML für diese oder jene Instanz zu nutzen (z. B. wenn diese oder jene Instanz einen bestimmten BasePath für importiertes HTML verwenden soll oder einen bestimmten Loader für externe Ressourcen). Wenn der Parameter standardmäßig (null) ist, werden die Standard‑HTML‑Ladeoptionen verwendet.

### setParagraphHasMargin {#setParagraphHasMargin-boolean-}
```
public final void setParagraphHasMargin(boolean value)
```

Ruft ab, ob der Absatz den Standardrand hat, oder legt ihn fest; andernfalls ist der Rand 0

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setTextState {#setTextState-com.aspose.pdf.TextState-}
Ruft die Schriftart ab oder legt sie fest
