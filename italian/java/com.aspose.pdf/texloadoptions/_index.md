---
title: "TeXLoadOptions"
linktitle: "TeXLoadOptions"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta le opzioni per caricare/importare un file TeX in un documento PDF."
type: docs
weight: 4870
url: /it/java/com.aspose.pdf/texloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.TeXLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.TeXLoadOptions

```
public class TeXLoadOptions extends LoadOptions
```

Rappresenta le opzioni per caricare/importare un file TeX in un documento PDF.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TeXLoadOptions](#TeXLoadOptions--) | Crea le opzioni di caricamento predefinite per convertire il file TeX in documento PDF. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getDateTime](#getDateTime--) | Ottiene/imposta un determinato valore per le primitive data/ora come anno, mese, giorno e ora. |
| [getInputDirectory](#getInputDirectory--) | Ottiene/imposta la directory di input TeX. |
| [getJobName](#getJobName--) | Ottiene/imposta il nome del lavoro. |
| [getLoadResult](#getLoadResult--) | Ottiene il risultato del caricamento e della compilazione TeX - tutto è andato senza problemi o ci sono stati commenti/errori. |
| [getNoLigatures](#getNoLigatures--) | Ottiene/imposta un flag che annulla le legature in tutti i font. |
| [getOutputDirectory](#getOutputDirectory--) | Ottiene/imposta la directory di output TeX. |
| [getRasterizeFormulas](#getRasterizeFormulas--) | Ottiene/imposta un flag che consente di rasterizzare le formule matematiche. |
| [getRepeat](#getRepeat--) | Ottiene/imposta il flag che indica se è necessario eseguire il lavoro TeX due volte nel caso, ad esempio, ci siano riferimenti nei file TeX di input. In generale, questo comportamento è utile quando il motore raccoglie alcuni dati durante il processo di composizione e li memorizza in un file ausiliario al primo avvio. E al secondo avvio, il motore utilizza in qualche modo tali dati. |
| [getRequiredInputDirectory](#getRequiredInputDirectory--) | Ottiene/imposta la directory di input richiesta da TeX. L'input richiesto sono i file che vengono in qualche modo inclusi nel file .tex principale, ad esempio i pacchetti per i quali non esiste supporto integrato. |
| [getShowTerminalOutput](#getShowTerminalOutput--) | Ottiene/imposta il flag che indica se mostrare l'output del terminale sulla console. |
| [getSubsetFonts](#getSubsetFonts--) | Ottiene/Imposta il flag che indica se sottosettare i caratteri nel file di output o meno. |
| [setDateTime](#setDateTime-java.util.Date-) | Ottiene/imposta un determinato valore per le primitive data/ora come anno, mese, giorno e ora. |
| [setInputDirectory](#setInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-) | Ottiene/imposta la directory di input TeX. |
| [setJobName](#setJobName-java.lang.String-) | Ottiene/imposta il nome del lavoro. |
| [setNoLigatures](#setNoLigatures-boolean-) | Ottiene/imposta un flag che annulla le legature in tutti i font. |
| [setOutputDirectory](#setOutputDirectory-com.aspose.pdf.tex.ITeXOutputDirectory-) | Ottiene/imposta la directory di output TeX. |
| [setRasterizeFormulas](#setRasterizeFormulas-boolean-) | Ottiene/imposta un flag che consente di rasterizzare le formule matematiche. |
| [setRepeat](#setRepeat-boolean-) | Ottiene/imposta il flag che indica se è necessario eseguire il lavoro TeX due volte nel caso, ad esempio, ci siano riferimenti nei file TeX di input. In generale, questo comportamento è utile quando il motore raccoglie alcuni dati durante il processo di composizione e li memorizza in un file ausiliario al primo avvio. E al secondo avvio, il motore utilizza in qualche modo tali dati. |
| [setRequiredInputDirectory](#setRequiredInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-) | Ottiene/imposta la directory di input richiesta da TeX. L'input richiesto sono i file che vengono in qualche modo inclusi nel file .tex principale, ad esempio i pacchetti per i quali non esiste supporto integrato. |
| [setShowTerminalOutput](#setShowTerminalOutput-boolean-) | Ottiene/imposta il flag che indica se mostrare l'output del terminale sulla console. |
| [setSubsetFonts](#setSubsetFonts-boolean-) | Ottiene/Imposta il flag che indica se sottosettare i caratteri nel file di output o meno. |

### TeXLoadOptions {#TeXLoadOptions--}
```
public TeXLoadOptions()
```

Crea le opzioni di caricamento predefinite per convertire il file TeX in documento PDF.

### getDateTime {#getDateTime--}
```
public final Date getDateTime()
```

Ottiene/imposta un determinato valore per le primitive data/ora come anno, mese, giorno e ora.

**Returns:**
istanza Date

### getInputDirectory {#getInputDirectory--}
```
public final ITeXInputDirectory getInputDirectory()
```

Ottiene/imposta la directory di input TeX.

**Returns:**
istanza di ITeXInputDirectory

### getJobName {#getJobName--}
```
public final String getJobName()
```

Ottiene/imposta il nome del lavoro.

**Returns:**
valore String

### getLoadResult {#getLoadResult--}
```
public final int getLoadResult()
```

Ottiene il risultato del caricamento e della compilazione TeX - tutto è andato senza problemi o ci sono stati commenti/errori.

**Returns:**
elemento TeXLoadResult

### getNoLigatures {#getNoLigatures--}
```
public final boolean getNoLigatures()
```

Ottiene/imposta un flag che annulla le legature in tutti i font.

**Returns:**
valore booleano

### getOutputDirectory {#getOutputDirectory--}
```
public final ITeXOutputDirectory getOutputDirectory()
```

Ottiene/imposta la directory di output TeX.

**Returns:**
istanza di ITeXOutputDirectory

### getRasterizeFormulas {#getRasterizeFormulas--}
```
public final boolean getRasterizeFormulas()
```

Ottiene/imposta un flag che consente di rasterizzare le formule matematiche.

**Returns:**
valore booleano

### getRepeat {#getRepeat--}
```
public final boolean getRepeat()
```

Ottiene/imposta il flag che indica se è necessario eseguire il lavoro TeX due volte nel caso, ad esempio, ci siano riferimenti nei file TeX di input. In generale, questo comportamento è utile quando il motore raccoglie alcuni dati durante il processo di composizione e li memorizza in un file ausiliario al primo avvio. E al secondo avvio, il motore utilizza in qualche modo tali dati.

**Returns:**
valore booleano

### getRequiredInputDirectory {#getRequiredInputDirectory--}
```
public final ITeXInputDirectory getRequiredInputDirectory()
```

Ottiene/imposta la directory di input richiesta da TeX. L'input richiesto sono i file che vengono in qualche modo inclusi nel file .tex principale, ad esempio i pacchetti per i quali non esiste supporto integrato.

**Returns:**
istanza di ITeXInputDirectory

### getShowTerminalOutput {#getShowTerminalOutput--}
```
public final boolean getShowTerminalOutput()
```

Ottiene/imposta il flag che indica se mostrare l'output del terminale sulla console.

**Returns:**
valore booleano

### getSubsetFonts {#getSubsetFonts--}
```
public final boolean getSubsetFonts()
```

Ottiene/Imposta il flag che indica se sottosettare i caratteri nel file di output o meno.

**Returns:**
valore booleano

### setDateTime {#setDateTime-java.util.Date-}
Ottiene/imposta un determinato valore per le primitive data/ora come anno, mese, giorno e ora.

### setInputDirectory {#setInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-}
Ottiene/imposta la directory di input TeX.

### setJobName {#setJobName-java.lang.String-}
Ottiene/imposta il nome del lavoro.

### setNoLigatures {#setNoLigatures-boolean-}
```
public final void setNoLigatures(boolean value)
```

Ottiene/imposta un flag che annulla le legature in tutti i font.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setOutputDirectory {#setOutputDirectory-com.aspose.pdf.tex.ITeXOutputDirectory-}
Ottiene/imposta la directory di output TeX.

### setRasterizeFormulas {#setRasterizeFormulas-boolean-}
```
public final void setRasterizeFormulas(boolean value)
```

Ottiene/imposta un flag che consente di rasterizzare le formule matematiche.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setRepeat {#setRepeat-boolean-}
```
public final void setRepeat(boolean value)
```

Ottiene/imposta il flag che indica se è necessario eseguire il lavoro TeX due volte nel caso, ad esempio, ci siano riferimenti nei file TeX di input. In generale, questo comportamento è utile quando il motore raccoglie alcuni dati durante il processo di composizione e li memorizza in un file ausiliario al primo avvio. E al secondo avvio, il motore utilizza in qualche modo tali dati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setRequiredInputDirectory {#setRequiredInputDirectory-com.aspose.pdf.tex.ITeXInputDirectory-}
Ottiene/imposta la directory di input richiesta da TeX. L'input richiesto sono i file che vengono in qualche modo inclusi nel file .tex principale, ad esempio i pacchetti per i quali non esiste supporto integrato.

### setShowTerminalOutput {#setShowTerminalOutput-boolean-}
```
public final void setShowTerminalOutput(boolean value)
```

Ottiene/imposta il flag che indica se mostrare l'output del terminale sulla console.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setSubsetFonts {#setSubsetFonts-boolean-}
```
public final void setSubsetFonts(boolean value)
```

Ottiene/Imposta il flag che indica se sottosettare i caratteri nel file di output o meno.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |
