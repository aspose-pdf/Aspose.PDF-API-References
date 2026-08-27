---
title: "PsLoadOptions"
linktitle: "PsLoadOptions"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta le opzioni per il caricamento/importazione di file .mht in un documento pdf."
type: docs
weight: 4060
url: /it/java/com.aspose.pdf/psloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.PsLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.PsLoadOptions

```
public final class PsLoadOptions extends LoadOptions
```

Rappresenta le opzioni per il caricamento/importazione di file .mht in un documento pdf.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PsLoadOptions](#PsLoadOptions--) | Crea le opzioni di caricamento per convertire PostScript in un documento PDF con percorso base vuoto. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFontsFolders](#getFontsFolders--) | Ottiene i percorsi delle cartelle dei font. Le cartelle con font aggiuntivi per la conversione. |
| [isConvertFontsToTTF](#isConvertFontsToTTF--) | Specifica se salvare i font non TrueType in TTF. Riduce significativamente il volume del documento risultante nella conversione da PS a PDF e aumenta la velocità di conversione dei file PS con una grande quantità di testo in font non TrueType in qualsiasi formato di output. Tuttavia, c'è un piccolo spostamento verticale del testo durante la conversione di un file PostSctipt in immagine. |
| [setConvertFontsToTTF](#setConvertFontsToTTF-boolean-) | Specifica se salvare i font non TrueType in TTF. Riduce significativamente il volume del documento risultante nella conversione da PS a PDF e aumenta la velocità di conversione dei file PS con una grande quantità di testo in font non TrueType in qualsiasi formato di output. Tuttavia, c'è un piccolo spostamento verticale del testo durante la conversione di un file PostSctipt in immagine. |
| [setFontsFolders](#setFontsFolders-java.lang.String:A-) | Imposta i percorsi delle cartelle dei font. Le cartelle con font aggiuntivi per la conversione. |

### PsLoadOptions {#PsLoadOptions--}
```
public PsLoadOptions()
```

Crea le opzioni di caricamento per convertire PostScript in un documento PDF con percorso base vuoto.

### getFontsFolders {#getFontsFolders--}
```
public String [] getFontsFolders()
```

Ottiene i percorsi delle cartelle dei font. Le cartelle con font aggiuntivi per la conversione.

**Returns:**
array di valori String

### isConvertFontsToTTF {#isConvertFontsToTTF--}
```
public final boolean isConvertFontsToTTF()
```

Specifica se salvare i font non TrueType in TTF. Riduce significativamente il volume del documento risultante nella conversione da PS a PDF e aumenta la velocità di conversione dei file PS con una grande quantità di testo in font non TrueType in qualsiasi formato di output. Tuttavia, c'è un piccolo spostamento verticale del testo durante la conversione di un file PostSctipt in immagine.

**Returns:**
valore booleano

### setConvertFontsToTTF {#setConvertFontsToTTF-boolean-}
```
public final void setConvertFontsToTTF(boolean value)
```

Specifica se salvare i font non TrueType in TTF. Riduce significativamente il volume del documento risultante nella conversione da PS a PDF e aumenta la velocità di conversione dei file PS con una grande quantità di testo in font non TrueType in qualsiasi formato di output. Tuttavia, c'è un piccolo spostamento verticale del testo durante la conversione di un file PostSctipt in immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setFontsFolders {#setFontsFolders-java.lang.String:A-}
Imposta i percorsi delle cartelle dei font. Le cartelle con font aggiuntivi per la conversione.
