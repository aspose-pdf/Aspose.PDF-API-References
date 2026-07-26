---
title: "BaseParagraph"
linktitle: "BaseParagraph"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta un oggetto base astratto che può essere aggiunto alla pagina (doc.Paragraphs.Add())."
type: docs
weight: 280
url: /it/java/com.aspose.pdf/baseparagraph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public abstract class BaseParagraph extends Object implements com.aspose.ms.System.ICloneable
```

Rappresenta un oggetto base astratto che può essere aggiunto alla pagina (doc.Paragraphs.Add()).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [BaseParagraph](#BaseParagraph--) |  |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [deepClone](#deepClone--) | Clona questa istanza. Metodo virtuale. Restituisce sempre null. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Ottiene un allineamento orizzontale del paragrafo |
| [getHyperlink](#getHyperlink--) | / * / * Ottiene o imposta se un paragrafo è una nota a piè di pagina. Il valore predefinito è false.(per la generazione PDF) / * / * |
| [getMargin](#getMargin--) | Ottiene un margine esterno per il paragrafo (per la generazione PDF) |
| [getVerticalAlignment](#getVerticalAlignment--) | Ottiene un allineamento verticale del paragrafo |
| [getZIndex](#getZIndex--) | Ottiene un valore int che indica l'ordine Z del grafico. Un grafico con ZIndex più grande verrà posizionato sopra il grafico con ZIndex più piccolo. ZIndex può essere negativo. Un grafico con ZIndex negativo verrà posizionato dietro il testo nella pagina. |
| [isFirstParagraphInColumn](#isFirstParagraphInColumn--) | Ottiene o imposta un valore bool che indica se questo paragrafo sarà nella colonna successiva. Il valore predefinito è false.(per la generazione PDF) |
| [isInLineParagraph](#isInLineParagraph--) | Ottiene se un paragrafo è in linea. Il valore predefinito è false.(per la generazione PDF) |
| [isInNewPage](#isInNewPage--) | Restituisce un valore bool che forza questo paragrafo a generarsi in una nuova pagina. Il valore predefinito è false. (per la generazione PDF) |
| [isKeptWithNext](#isKeptWithNext--) | Restituisce un valore booleano che indica se il paragrafo corrente rimane nella stessa pagina insieme al paragrafo successivo. Il valore predefinito è false. (per la generazione PDF) |
| [setFirstParagraphInColumn](#setFirstParagraphInColumn-boolean-) | Ottiene o imposta un valore bool che indica se questo paragrafo sarà nella colonna successiva. Il valore predefinito è false.(per la generazione PDF) |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Imposta l'allineamento orizzontale del paragrafo |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | Imposta il collegamento ipertestuale (per il generatore PDF). |
| [setInLineParagraph](#setInLineParagraph-boolean-) | Imposta che un paragrafo sia in linea. Il valore predefinito è false. (per la generazione PDF) |
| [setInNewPage](#setInNewPage-boolean-) | Imposta un valore booleano che forza questo paragrafo a generarsi in una nuova pagina. Il valore predefinito è false. (per la generazione PDF) |
| [setKeptWithNext](#setKeptWithNext-boolean-) | Imposta un valore booleano che indica se il paragrafo corrente rimane nella stessa pagina insieme al paragrafo successivo. Il valore predefinito è false. (per la generazione PDF) |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Imposta un margine esterno per il paragrafo (per la generazione PDF) |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Imposta l'allineamento verticale del paragrafo |
| [setZIndex](#setZIndex-int-) | Imposta un valore int che indica l'ordine Z del grafico. Un grafico con ZIndex più grande verrà posizionato sopra un grafico con ZIndex più piccolo. ZIndex può essere negativo. Un grafico con ZIndex negativo verrà posizionato dietro il testo nella pagina. |

### BaseParagraph {#BaseParagraph--}
```
public BaseParagraph()
```



### deepClone {#deepClone--}
```
public Object deepClone()
```

Clona questa istanza. Metodo virtuale. Restituisce sempre null.

**Returns:**
Null

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Ottiene un allineamento orizzontale del paragrafo

**Returns:**
Valore HorizontalAlignment @see HorizontalAlignment

### getHyperlink {#getHyperlink--}
```
public Hyperlink getHyperlink()
```

/ * / * Ottiene o imposta se un paragrafo è una nota a piè di pagina. Il valore predefinito è false.(per la generazione PDF) / * / *

**Returns:**
valore booleano /

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

Ottiene un margine esterno per il paragrafo (per la generazione PDF)

**Returns:**
Valore MarginInfo

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Ottiene un allineamento verticale del paragrafo

**Returns:**
Elemento VerticalAlignment @see VerticalAlignment

### getZIndex {#getZIndex--}
```
public int getZIndex()
```

Ottiene un valore int che indica l'ordine Z del grafico. Un grafico con ZIndex più grande verrà posizionato sopra il grafico con ZIndex più piccolo. ZIndex può essere negativo. Un grafico con ZIndex negativo verrà posizionato dietro il testo nella pagina.

**Returns:**
valore int

### isFirstParagraphInColumn {#isFirstParagraphInColumn--}
```
public boolean isFirstParagraphInColumn()
```

Ottiene o imposta un valore bool che indica se questo paragrafo sarà nella colonna successiva. Il valore predefinito è false.(per la generazione PDF)

**Returns:**
valore booleano

### isInLineParagraph {#isInLineParagraph--}
```
public boolean isInLineParagraph()
```

Ottiene se un paragrafo è in linea. Il valore predefinito è false.(per la generazione PDF)

**Returns:**
valore booleano

### isInNewPage {#isInNewPage--}
```
public boolean isInNewPage()
```

Restituisce un valore bool che forza questo paragrafo a generarsi in una nuova pagina. Il valore predefinito è false. (per la generazione PDF)

**Returns:**
valore booleano

### isKeptWithNext {#isKeptWithNext--}
```
public boolean isKeptWithNext()
```

Restituisce un valore booleano che indica se il paragrafo corrente rimane nella stessa pagina insieme al paragrafo successivo. Il valore predefinito è false. (per la generazione PDF)

**Returns:**
valore booleano

### setFirstParagraphInColumn {#setFirstParagraphInColumn-boolean-}
```
public void setFirstParagraphInColumn(boolean value)
```

Ottiene o imposta un valore bool che indica se questo paragrafo sarà nella colonna successiva. Il valore predefinito è false.(per la generazione PDF)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Imposta l'allineamento orizzontale del paragrafo

### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
Imposta il collegamento ipertestuale (per il generatore PDF).

### setInLineParagraph {#setInLineParagraph-boolean-}
```
public void setInLineParagraph(boolean value)
```

Imposta che un paragrafo sia in linea. Il valore predefinito è false. (per la generazione PDF)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setInNewPage {#setInNewPage-boolean-}
```
public void setInNewPage(boolean value)
```

Imposta un valore booleano che forza questo paragrafo a generarsi in una nuova pagina. Il valore predefinito è false. (per la generazione PDF)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setKeptWithNext {#setKeptWithNext-boolean-}
```
public final void setKeptWithNext(boolean value)
```

Imposta un valore booleano che indica se il paragrafo corrente rimane nella stessa pagina insieme al paragrafo successivo. Il valore predefinito è false. (per la generazione PDF)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Imposta un margine esterno per il paragrafo (per la generazione PDF)

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Imposta l'allineamento verticale del paragrafo

### setZIndex {#setZIndex-int-}
```
public void setZIndex(int value)
```

Imposta un valore int che indica l'ordine Z del grafico. Un grafico con ZIndex più grande verrà posizionato sopra un grafico con ZIndex più piccolo. ZIndex può essere negativo. Un grafico con ZIndex negativo verrà posizionato dietro il testo nella pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |
