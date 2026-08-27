---
title: "StructureTextState"
linktitle: "StructureTextState"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta le impostazioni dello stato del testo per gli Elementi di Struttura del Testo e TaggedContent (ITextElement, ITaggedContent)"
type: docs
weight: 120
url: /it/java/com.aspose.pdf.tagged.logicalstructure.elements/structuretextstate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.StructureTextState

```
public class StructureTextState extends Object
```

Rappresenta le impostazioni dello stato del testo per gli Elementi di Struttura del Testo e TaggedContent (ITextElement, ITaggedContent)

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [StructureTextState](#StructureTextState--) | Costruttore predefinito |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createTextState](#createTextState--) | Crea stato del testo |
| [getBackgroundColor](#getBackgroundColor--) | Ottiene o imposta il colore di sfondo del testo. Può essere null. Usa null per ereditare la proprietà {@code BackgroundColor} dall'elemento strutturato genitore. |
| [getCharacterSpacing](#getCharacterSpacing--) | Ottiene o imposta la spaziatura dei caratteri del testo. Può essere null. Usa null per ereditare la proprietà {@code CharacterSpacing} dall'elemento strutturato genitore. |
| [getFont](#getFont--) | Ottiene o imposta il font del testo. Può essere null. Usa null per ereditare la proprietà {@code Font} dall'elemento strutturato genitore. |
| [getFontSize](#getFontSize--) | Ottiene o imposta la dimensione del font del testo. Può essere null. Usa null per ereditare la proprietà {@code FontSize} dall'elemento strutturato genitore. |
| [getFontStyle](#getFontStyle--) | Ottiene o imposta lo stile del font del testo. Può essere null. Usa null per ereditare la proprietà {@code FontStyle} dall'elemento strutturato genitore. |
| [getForegroundColor](#getForegroundColor--) | Ottiene o imposta il colore di primo piano del testo. Può essere null. Usa null per ereditare la proprietà {@code ForegroundColor} dall'elemento strutturato genitore. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Ottiene o imposta un allineamento orizzontale del paragrafo |
| [getHorizontalScaling](#getHorizontalScaling--) | Ottiene o imposta la scala orizzontale del testo. Può essere null. Usa null per ereditare la proprietà {@code HorizontalScaling} dall'elemento strutturato genitore. |
| [getLineSpacing](#getLineSpacing--) | Ottiene o imposta l'interlinea del testo. Può essere null. Usa null per ereditare la proprietà {@code LineSpacing} dall'elemento strutturato genitore. |
| [getMarginInfo](#getMarginInfo--) | Ottiene o imposta il margine per l'elemento di struttura a blocco. |
| [getStrikeOut](#getStrikeOut--) | Ottiene o imposta il barrato del testo. Può essere null. Usa null per ereditare la proprietà {@code StrikeOut} dall'elemento strutturato genitore. |
| [getSubscript](#getSubscript--) | Ottiene o imposta il pedice del testo. Può essere null. Usa null per ereditare la proprietà {@code Subscript} dall'elemento strutturato genitore. |
| [getSuperscript](#getSuperscript--) | Ottiene o imposta il apice del testo. Può essere null. Usa null per ereditare la proprietà {@code Superscript} dall'elemento strutturato genitore. |
| [getUnderline](#getUnderline--) | Ottiene o imposta la sottolineatura del testo. Può essere null. Usa null per ereditare la proprietà {@code Underline} dall'elemento strutturato genitore. |
| [getVerticalAlignment](#getVerticalAlignment--) | Ottiene o imposta un allineamento verticale del paragrafo |
| [getWordSpacing](#getWordSpacing--) | Ottiene o imposta la spaziatura delle parole del testo. Può essere null. Usa null per ereditare la proprietà {@code WordSpacing} dall'elemento strutturato genitore. |
| [isFirstParagraphInColumn](#isFirstParagraphInColumn--) | Ottiene o imposta un valore booleano che indica se questo paragrafo sarà nella colonna successiva. Il valore predefinito è false. |
| [isInLineParagraph](#isInLineParagraph--) | Ottiene o imposta se un paragrafo è in linea. Il valore predefinito è false. |
| [isInNewPage](#isInNewPage--) | Ottiene o imposta un valore booleano che forza la generazione di questo paragrafo in una nuova pagina. Il valore predefinito è false. |
| [isKeptWithNext](#isKeptWithNext--) | Ottiene o imposta un valore booleano che indica se il paragrafo corrente rimane nella stessa pagina insieme al paragrafo successivo. Il valore predefinito è false. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Ottiene o imposta il colore di sfondo del testo. Può essere null. Usa null per ereditare la proprietà {@code BackgroundColor} dall'elemento strutturato genitore. |
| [setCharacterSpacing](#setCharacterSpacing-com.aspose.ms.System.Nullable-) | Ottiene o imposta la spaziatura dei caratteri del testo. |
| [setFont](#setFont-com.aspose.pdf.Font-) | Ottiene o imposta il font del testo. Può essere null. Usa null per ereditare la proprietà {@code Font} dall'elemento strutturato genitore. |
| [setFontSize](#setFontSize-com.aspose.ms.System.Nullable-) | Ottiene o imposta la dimensione del font del testo. |
| [setFontStyle](#setFontStyle-com.aspose.ms.System.Nullable-) | Ottiene o imposta lo stile del font del testo. |
| [setForegroundColor](#setForegroundColor-com.aspose.pdf.Color-) | Ottiene o imposta il colore di primo piano del testo. Può essere null. Usa null per ereditare la proprietà {@code ForegroundColor} dall'elemento strutturato genitore. |
| [setHorizontalScaling](#setHorizontalScaling-com.aspose.ms.System.Nullable-) | Ottiene o imposta la scala orizzontale del testo. |
| [setLineSpacing](#setLineSpacing-com.aspose.ms.System.Nullable-) | Ottiene o imposta l'interlinea del testo. |
| [setMarginInfo](#setMarginInfo-com.aspose.pdf.MarginInfo-) | Ottiene o imposta il margine per l'elemento di struttura a blocco. |
| [setStrikeOut](#setStrikeOut-com.aspose.ms.System.Nullable-) | Ottiene o imposta il barrato per il testo. |
| [setSubscript](#setSubscript-com.aspose.ms.System.Nullable-) | Ottiene o imposta il pedice del testo. |
| [setSuperscript](#setSuperscript-com.aspose.ms.System.Nullable-) | Ottiene o imposta il apice del testo. |
| [setUnderline](#setUnderline-com.aspose.ms.System.Nullable-) | Ottiene o imposta la sottolineatura per il testo. |
| [setWordSpacing](#setWordSpacing-com.aspose.ms.System.Nullable-) | Ottiene o imposta la spaziatura delle parole del testo. |
| [update](#update-com.aspose.pdf.tagged.logicalstructure.elements.StructureTextState-) | Aggiorna gli elementi |

### StructureTextState {#StructureTextState--}
```
public StructureTextState()
```

Costruttore predefinito

### createTextState {#createTextState--}
```
public final TextState createTextState()
```

Crea stato del testo

**Returns:**
istanza TextState

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Ottiene o imposta il colore di sfondo del testo. Può essere null. Usa null per ereditare la proprietà {@code BackgroundColor} dall'elemento strutturato genitore.

**Returns:**
Istanza di Color

### getCharacterSpacing {#getCharacterSpacing--}
```
public final com.aspose.ms.System.Nullable< Float > getCharacterSpacing()
```

Ottiene o imposta la spaziatura dei caratteri del testo. Può essere null. Usa null per ereditare la proprietà {@code CharacterSpacing} dall'elemento strutturato genitore.

**Returns:**
Array di float

### getFont {#getFont--}
```
public final Font getFont()
```

Ottiene o imposta il font del testo. Può essere null. Usa null per ereditare la proprietà {@code Font} dall'elemento strutturato genitore.

**Returns:**
Font istanza

### getFontSize {#getFontSize--}
```
public final com.aspose.ms.System.Nullable< Float > getFontSize()
```

Ottiene o imposta la dimensione del font del testo. Può essere null. Usa null per ereditare la proprietà {@code FontSize} dall'elemento strutturato genitore.

**Returns:**
Array di float

### getFontStyle {#getFontStyle--}
```
public final com.aspose.ms.System.Nullable< Integer > getFontStyle()
```

Ottiene o imposta lo stile del font del testo. Può essere null. Usa null per ereditare la proprietà {@code FontStyle} dall'elemento strutturato genitore.

**Returns:**
Array di interi

### getForegroundColor {#getForegroundColor--}
```
public final Color getForegroundColor()
```

Ottiene o imposta il colore di primo piano del testo. Può essere null. Usa null per ereditare la proprietà {@code ForegroundColor} dall'elemento strutturato genitore.

**Returns:**
Istanza di Color

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public final com.aspose.ms.System.Nullable< HorizontalAlignment > getHorizontalAlignment()
```

Ottiene o imposta un allineamento orizzontale del paragrafo

**Returns:**
Elemento HorizontalAlignment

### getHorizontalScaling {#getHorizontalScaling--}
```
public final com.aspose.ms.System.Nullable< Float > getHorizontalScaling()
```

Ottiene o imposta la scala orizzontale del testo. Può essere null. Usa null per ereditare la proprietà {@code HorizontalScaling} dall'elemento strutturato genitore.

**Returns:**
Array di float

### getLineSpacing {#getLineSpacing--}
```
public final com.aspose.ms.System.Nullable< Float > getLineSpacing()
```

Ottiene o imposta l'interlinea del testo. Può essere null. Usa null per ereditare la proprietà {@code LineSpacing} dall'elemento strutturato genitore.

**Returns:**
Array di float

### getMarginInfo {#getMarginInfo--}
```
@Deprecated public final MarginInfo getMarginInfo()
```

Ottiene o imposta il margine per l'elemento di struttura a blocco.

**Returns:**
Istanza MarginInfo @deprecated Usa il metodo IAdjustPosition.AdjustPosition(PositionSettings positionSettings) per impostare le impostazioni di posizione

### getStrikeOut {#getStrikeOut--}
```
public final com.aspose.ms.System.Nullable< Boolean > getStrikeOut()
```

Ottiene o imposta il barrato del testo. Può essere null. Usa null per ereditare la proprietà {@code StrikeOut} dall'elemento strutturato genitore.

**Returns:**
Array di booleani

### getSubscript {#getSubscript--}
```
public final com.aspose.ms.System.Nullable< Boolean > getSubscript()
```

Ottiene o imposta il pedice del testo. Può essere null. Usa null per ereditare la proprietà {@code Subscript} dall'elemento strutturato genitore.

**Returns:**
Array di booleani

### getSuperscript {#getSuperscript--}
```
public final com.aspose.ms.System.Nullable< Boolean > getSuperscript()
```

Ottiene o imposta il apice del testo. Può essere null. Usa null per ereditare la proprietà {@code Superscript} dall'elemento strutturato genitore.

**Returns:**
Array di booleani

### getUnderline {#getUnderline--}
```
public final com.aspose.ms.System.Nullable< Boolean > getUnderline()
```

Ottiene o imposta la sottolineatura del testo. Può essere null. Usa null per ereditare la proprietà {@code Underline} dall'elemento strutturato genitore.

**Returns:**
Array di booleani

### getVerticalAlignment {#getVerticalAlignment--}
```
public final com.aspose.ms.System.Nullable< VerticalAlignment > getVerticalAlignment()
```

Ottiene o imposta un allineamento verticale del paragrafo

**Returns:**
Elemento VerticalAlignment

### getWordSpacing {#getWordSpacing--}
```
public final com.aspose.ms.System.Nullable< Float > getWordSpacing()
```

Ottiene o imposta la spaziatura delle parole del testo. Può essere null. Usa null per ereditare la proprietà {@code WordSpacing} dall'elemento strutturato genitore.

**Returns:**
Array di float

### isFirstParagraphInColumn {#isFirstParagraphInColumn--}
```
public final com.aspose.ms.System.Nullable< Boolean > isFirstParagraphInColumn()
```

Ottiene o imposta un valore booleano che indica se questo paragrafo sarà nella colonna successiva. Il valore predefinito è false.

**Returns:**
Valore booleano

### isInLineParagraph {#isInLineParagraph--}
```
public final com.aspose.ms.System.Nullable< Boolean > isInLineParagraph()
```

Ottiene o imposta se un paragrafo è in linea. Il valore predefinito è false.

**Returns:**
Valore booleano

### isInNewPage {#isInNewPage--}
```
public final com.aspose.ms.System.Nullable< Boolean > isInNewPage()
```

Ottiene o imposta un valore booleano che forza la generazione di questo paragrafo in una nuova pagina. Il valore predefinito è false.

**Returns:**
Valore booleano

### isKeptWithNext {#isKeptWithNext--}
```
public final com.aspose.ms.System.Nullable< Boolean > isKeptWithNext()
```

Ottiene o imposta un valore booleano che indica se il paragrafo corrente rimane nella stessa pagina insieme al paragrafo successivo. Il valore predefinito è false.

**Returns:**
Valore booleano

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Ottiene o imposta il colore di sfondo del testo. Può essere null. Usa null per ereditare la proprietà {@code BackgroundColor} dall'elemento strutturato genitore.

### setCharacterSpacing {#setCharacterSpacing-com.aspose.ms.System.Nullable-}
Ottiene o imposta la spaziatura dei caratteri del testo.

### setFont {#setFont-com.aspose.pdf.Font-}
Ottiene o imposta il font del testo. Può essere null. Usa null per ereditare la proprietà {@code Font} dall'elemento strutturato genitore.

### setFontSize {#setFontSize-com.aspose.ms.System.Nullable-}
Ottiene o imposta la dimensione del font del testo.

### setFontStyle {#setFontStyle-com.aspose.ms.System.Nullable-}
Ottiene o imposta lo stile del font del testo.

### setForegroundColor {#setForegroundColor-com.aspose.pdf.Color-}
Ottiene o imposta il colore di primo piano del testo. Può essere null. Usa null per ereditare la proprietà {@code ForegroundColor} dall'elemento strutturato genitore.

### setHorizontalScaling {#setHorizontalScaling-com.aspose.ms.System.Nullable-}
Ottiene o imposta la scala orizzontale del testo.

### setLineSpacing {#setLineSpacing-com.aspose.ms.System.Nullable-}
Ottiene o imposta l'interlinea del testo.

### setMarginInfo {#setMarginInfo-com.aspose.pdf.MarginInfo-}
Ottiene o imposta il margine per l'elemento di struttura a blocco.

### setStrikeOut {#setStrikeOut-com.aspose.ms.System.Nullable-}
Ottiene o imposta il barrato per il testo.

### setSubscript {#setSubscript-com.aspose.ms.System.Nullable-}
Ottiene o imposta il pedice del testo.

### setSuperscript {#setSuperscript-com.aspose.ms.System.Nullable-}
Ottiene o imposta il apice del testo.

### setUnderline {#setUnderline-com.aspose.ms.System.Nullable-}
Ottiene o imposta la sottolineatura per il testo.

### setWordSpacing {#setWordSpacing-com.aspose.ms.System.Nullable-}
Ottiene o imposta la spaziatura delle parole del testo.

### update {#update-com.aspose.pdf.tagged.logicalstructure.elements.StructureTextState-}
Aggiorna gli elementi
