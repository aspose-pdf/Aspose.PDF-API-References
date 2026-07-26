---
title: "TextFormattingOptions"
linktitle: "TextFormattingOptions"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta le opzioni di formattazione del testo"
type: docs
weight: 5080
url: /it/java/com.aspose.pdf/textformattingoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextFormattingOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextFormattingOptions

```
public final class TextFormattingOptions extends TextOptions
```

Rappresenta le opzioni di formattazione del testo

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TextFormattingOptions](#TextFormattingOptions--) | Inizializza una nuova istanza dell'oggetto {@code TextFormattingOptions} con modalità di a capo parole non definita. |
| [TextFormattingOptions](#TextFormattingOptions-int-) | Inizializza una nuova istanza dell'oggetto {@code TextFormattingOptions} per la modalità di a capo parole specificata. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFirstLineIndent](#getFirstLineIndent--) | Ottiene o imposta il valore del rientro della prima riga. |
| [getHyphenSymbol](#getHyphenSymbol--) | <p> Ottiene o imposta il simbolo di trattino usato nel processo di sillabazione. </p><hr> Per eliminare il disegno del trattino (con la procedura di avvolgimento ancora attiva) impostare una stringa vuota string.Empty per HyphenSymbol. |
| [getLineSpacing](#getLineSpacing--) | Ottiene la modalità di interlinea. Il valore predefinito è LineSpacingMode.FontSize |
| [getSubsequentLinesIndent](#getSubsequentLinesIndent--) | Ottiene o imposta il valore di rientro delle righe successive. |
| [getWrapMode](#getWrapMode--) | Ottiene la modalità di a capo automatico. Il valore predefinito è WordWrapMode.NoWrap |
| [setFirstLineIndent](#setFirstLineIndent-float-) | Ottiene o imposta il valore del rientro della prima riga. |
| [setHyphenSymbol](#setHyphenSymbol-java.lang.String-) | <p> Ottiene o imposta il simbolo di trattino usato nel processo di sillabazione. </p><hr> Per eliminare il disegno del trattino (con la procedura di avvolgimento ancora attiva) impostare una stringa vuota string.Empty per HyphenSymbol. |
| [setLineSpacing](#setLineSpacing-int-) | Imposta la modalità di interlinea. Il valore predefinito è LineSpacingMode.FontSize |
| [setSubsequentLinesIndent](#setSubsequentLinesIndent-float-) | Ottiene o imposta il valore di rientro delle righe successive. |
| [setWrapMode](#setWrapMode-int-) | Imposta la modalità di a capo automatico. Il valore predefinito è WordWrapMode.NoWrap |

### TextFormattingOptions {#TextFormattingOptions--}
```
public TextFormattingOptions()
```

Inizializza una nuova istanza dell'oggetto {@code TextFormattingOptions} con modalità di a capo parole non definita.

### TextFormattingOptions {#TextFormattingOptions-int-}
```
public TextFormattingOptions(int wrapMode)
```

Inizializza una nuova istanza dell'oggetto {@code TextFormattingOptions} per la modalità di a capo parole specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| wrapMode |  | Modalità di a capo automatico. @see WordWrapMode |

### getFirstLineIndent {#getFirstLineIndent--}
```
public final float getFirstLineIndent()
```

Ottiene o imposta il valore del rientro della prima riga.

**Returns:**
valore float

### getHyphenSymbol {#getHyphenSymbol--}
```
public final String getHyphenSymbol()
```

<p> Ottiene o imposta il simbolo di trattino usato nel processo di sillabazione. </p><hr> Per eliminare il disegno del trattino (con la procedura di avvolgimento ancora attiva) impostare una stringa vuota string.Empty per HyphenSymbol.

**Returns:**
valore String

### getLineSpacing {#getLineSpacing--}
```
public int getLineSpacing()
```

Ottiene la modalità di interlinea. Il valore predefinito è LineSpacingMode.FontSize

**Returns:**
valore int @see LineSpacingMode

### getSubsequentLinesIndent {#getSubsequentLinesIndent--}
```
public float getSubsequentLinesIndent()
```

Ottiene o imposta il valore di rientro delle righe successive.

**Returns:**
valore float

### getWrapMode {#getWrapMode--}
```
public int getWrapMode()
```

Ottiene la modalità di a capo automatico. Il valore predefinito è WordWrapMode.NoWrap

**Returns:**
valore WordWrapMode @see WordWrapMode

### setFirstLineIndent {#setFirstLineIndent-float-}
```
public final void setFirstLineIndent(float value)
```

Ottiene o imposta il valore del rientro della prima riga.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore float |

### setHyphenSymbol {#setHyphenSymbol-java.lang.String-}
<p> Ottiene o imposta il simbolo di trattino usato nel processo di sillabazione. </p><hr> Per eliminare il disegno del trattino (con la procedura di avvolgimento ancora attiva) impostare una stringa vuota string.Empty per HyphenSymbol.

### setLineSpacing {#setLineSpacing-int-}
```
public void setLineSpacing(int value)
```

Imposta la modalità di interlinea. Il valore predefinito è LineSpacingMode.FontSize

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int @see LineSpacingMode |

### setSubsequentLinesIndent {#setSubsequentLinesIndent-float-}
```
public void setSubsequentLinesIndent(float value)
```

Ottiene o imposta il valore di rientro delle righe successive.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore float |

### setWrapMode {#setWrapMode-int-}
```
public void setWrapMode(int value)
```

Imposta la modalità di a capo automatico. Il valore predefinito è WordWrapMode.NoWrap

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore WordWrapMode @see WordWrapMode |
