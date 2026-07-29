---
title: "HtmlDiffOutputGenerator"
linktitle: "HtmlDiffOutputGenerator"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una classe per generare la rappresentazione HTML delle differenze tra i testi. Le interruzioni di riga eliminate sono indicate dal segno - di paragrafo."
type: docs
weight: 10
url: /it/java/com.aspose.pdf.comparison.outputgenerator/htmldiffoutputgenerator/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.outputgenerator.HtmlDiffOutputGenerator

**All Implemented Interfaces:**
IFileOutputGenerator, IStringOutputGenerator

```
public class HtmlDiffOutputGenerator extends Object implements IStringOutputGenerator , IFileOutputGenerator
```

Rappresenta una classe per generare la rappresentazione HTML delle differenze tra i testi. Le interruzioni di riga eliminate sono indicate dal segno - di paragrafo.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [HtmlDiffOutputGenerator](#HtmlDiffOutputGenerator--) | Crea un'istanza della classe {@link HtmlDiffOutputGenerator}. |
| [HtmlDiffOutputGenerator](#HtmlDiffOutputGenerator-com.aspose.pdf.comparison.outputgenerator.OutputTextStyle-) | Crea un'istanza della classe {@link HtmlDiffOutputGenerator}. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [generateOutput](#generateOutput-java.util.List-) | Genera l'output basato sulle differenze tra i testi e lo salva in un file. |
| [generateOutput](#generateOutput-java.util.List-java.lang.String-) | Genera l'output basato sulle differenze tra i testi e lo salva in un file. |
| [generateOutput1](#generateOutput1-java.util.List-) | Genera l'output basato sulle differenze tra i testi e lo salva in un file. |
| [generateOutput1](#generateOutput1-java.util.List-java.lang.String-) | Genera l'output basato sulle differenze tra i testi e lo salva in un file. |
| [generateOutputInternal](#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-) |  |
| [generateOutputInternal](#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-java.lang.String-) |  |
| [generateOutputInternal1](#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-) | Metodo interno |
| [generateOutputInternal1](#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-java.lang.String-) |  |
| [getDeleteStyle](#getDeleteStyle--) | Ottiene e imposta la stringa in stile CSS per l'operazione Delete. Esempio: color: #003300; background-color: #ccff66; |
| [getEqualStyle](#getEqualStyle--) | Ottiene e imposta la stringa in stile CSS per l'operazione Equal. Esempio: color: #003300; background-color: #ccff66; |
| [getInsertStyle](#getInsertStyle--) | Ottiene e imposta la stringa in stile CSS per l'operazione Insert. Esempio: color: #003300; background-color: #ccff66; |
| [getStrikethroughDeleted](#getStrikethroughDeleted--) | Ottieni o imposta lo stile text-decoration: line-through per l'operazione delete. Il valore predefinito è {@code False}. |
| [setDeleteStyle](#setDeleteStyle-java.lang.String-) | Ottiene e imposta la stringa in stile CSS per l'operazione Delete. Esempio: color: #003300; background-color: #ccff66; |
| [setEqualStyle](#setEqualStyle-java.lang.String-) | Ottiene e imposta la stringa in stile CSS per l'operazione Equal. Esempio: color: #003300; background-color: #ccff66; |
| [setInsertStyle](#setInsertStyle-java.lang.String-) | Ottiene e imposta la stringa in stile CSS per l'operazione Insert. Esempio: color: #003300; background-color: #ccff66; |
| [setStrikethroughDeleted](#setStrikethroughDeleted-boolean-) | Ottieni o imposta lo stile text-decoration: line-through per l'operazione delete. Il valore predefinito è {@code False}. |

### HtmlDiffOutputGenerator {#HtmlDiffOutputGenerator--}
```
public HtmlDiffOutputGenerator()
```

Crea un'istanza della classe {@link HtmlDiffOutputGenerator}.

### HtmlDiffOutputGenerator {#HtmlDiffOutputGenerator-com.aspose.pdf.comparison.outputgenerator.OutputTextStyle-}
Crea un'istanza della classe {@link HtmlDiffOutputGenerator}.

### generateOutput {#generateOutput-java.util.List-}
Genera l'output basato sulle differenze tra i testi e lo salva in un file.

### generateOutput {#generateOutput-java.util.List-java.lang.String-}
Genera l'output basato sulle differenze tra i testi e lo salva in un file.

### generateOutput1 {#generateOutput1-java.util.List-}
Genera l'output basato sulle differenze tra i testi e lo salva in un file.

### generateOutput1 {#generateOutput1-java.util.List-java.lang.String-}
Genera l'output basato sulle differenze tra i testi e lo salva in un file.

### generateOutputInternal {#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-}


### generateOutputInternal {#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-java.lang.String-}


### generateOutputInternal1 {#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-}
Metodo interno

### generateOutputInternal1 {#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-java.lang.String-}


### getDeleteStyle {#getDeleteStyle--}
```
public final String getDeleteStyle()
```

Ottiene e imposta la stringa in stile CSS per l'operazione Delete. Esempio: color: #003300; background-color: #ccff66;

**Returns:**
valore String

### getEqualStyle {#getEqualStyle--}
```
public final String getEqualStyle()
```

Ottiene e imposta la stringa in stile CSS per l'operazione Equal. Esempio: color: #003300; background-color: #ccff66;

**Returns:**
valore String

### getInsertStyle {#getInsertStyle--}
```
public final String getInsertStyle()
```

Ottiene e imposta la stringa in stile CSS per l'operazione Insert. Esempio: color: #003300; background-color: #ccff66;

**Returns:**
valore String

### getStrikethroughDeleted {#getStrikethroughDeleted--}
```
public final boolean getStrikethroughDeleted()
```

Ottieni o imposta lo stile text-decoration: line-through per l'operazione delete. Il valore predefinito è {@code False}.

**Returns:**
valore booleano

### setDeleteStyle {#setDeleteStyle-java.lang.String-}
Ottiene e imposta la stringa in stile CSS per l'operazione Delete. Esempio: color: #003300; background-color: #ccff66;

### setEqualStyle {#setEqualStyle-java.lang.String-}
Ottiene e imposta la stringa in stile CSS per l'operazione Equal. Esempio: color: #003300; background-color: #ccff66;

### setInsertStyle {#setInsertStyle-java.lang.String-}
Ottiene e imposta la stringa in stile CSS per l'operazione Insert. Esempio: color: #003300; background-color: #ccff66;

### setStrikethroughDeleted {#setStrikethroughDeleted-boolean-}
```
public final void setStrikethroughDeleted(boolean value)
```

Ottieni o imposta lo stile text-decoration: line-through per l'operazione delete. Il valore predefinito è {@code False}.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |
