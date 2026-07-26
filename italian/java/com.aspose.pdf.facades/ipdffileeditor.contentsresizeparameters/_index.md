---
title: "IPdfFileEditor.ContentsResizeParameters"
linktitle: "IPdfFileEditor.ContentsResizeParameters"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe per specificare i parametri di ridimensionamento della pagina. Consente di impostare i seguenti parametri: dimensione della pagina risultante (larghezza, altezza) in unità di spazio predefinite o in percentuale delle pagine iniziali."
type: docs
weight: 300
url: /it/java/com.aspose.pdf.facades/ipdffileeditor.contentsresizeparameters/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters

```
public static class IPdfFileEditor.ContentsResizeParameters extends Object
```

Classe per specificare i parametri di ridimensionamento della pagina. Consente di impostare i seguenti parametri: dimensione della pagina risultante (larghezza, altezza) in unità di spazio predefinite o in percentuale della dimensione della pagina iniziale; margini sinistro, superiore, inferiore e destro in unità di spazio predefinite o in percentuale della dimensione della pagina iniziale; alcuni valori possono essere lasciati null per il calcolo automatico. Questi valori saranno calcolati dal resto della dimensione della pagina dopo il calcolo dei valori specificati esplicitamente. Per esempio: se la larghezza della pagina = 100 e la nuova larghezza della pagina specificata è 60 unità, i margini sinistro e destro vengono calcolati automaticamente: (100 - 60) / 2 = 15. Questa classe è utilizzata nel metodo ResizeContents.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ContentsResizeParameters](#ContentsResizeParameters--) | Crea parametri di ridimensionamento in cui tutti i valori sono impostati su "auto". Successivamente i margini e la dimensione del contenuto possono essere specificati se necessario. |
| [ContentsResizeParameters](#ContentsResizeParameters-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Crea parametri di ridimensionamento in cui tutti i valori sono impostati su "auto". Successivamente i margini e la dimensione del contenuto possono essere specificati se necessario. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [contentSize](#contentSize-double-double-) | Crea parametri di ridimensionamento con la dimensione del contenuto specificata. |
| [contentSizePercent](#contentSizePercent-double-double-) | Crea parametri di ridimensionamento con la dimensione del contenuto specificata in percentuale della dimensione della pagina iniziale. I margini sono calcolati automaticamente. |
| [getBottomMargin](#getBottomMargin--) | Ottiene o imposta il margine inferiore sulla pagina risultante. |
| [getContentsHeight](#getContentsHeight--) | Ottiene o imposta l'altezza del contenuto della pagina di origine sulla pagina risultante. |
| [getContentsWidth](#getContentsWidth--) | Ottiene o imposta la larghezza del contenuto della pagina di origine sulla pagina risultante. |
| [getLeftMargin](#getLeftMargin--) | Ottiene o imposta il margine sinistro sulla pagina risultante. |
| [getRightMargin](#getRightMargin--) | Ottiene o imposta il margine destro sulla pagina risultante. |
| [getTopMargin](#getTopMargin--) | Ottiene o imposta il margine superiore sulla pagina risultante. |
| [isChangeMediaBox](#isChangeMediaBox--) | Ottiene se regolare il MediaBox di una pagina PDF durante l'operazione di ridimensionamento. Il valore predefinito è {@code false}. Impostare questo parametro consente di adattare il MediaBox al valore del CropBox durante il ridimensionamento. |
| [margins](#margins-double-double-double-double-) | Crea parametri di ridimensionamento con il valore dei margini specificato. La dimensione del contenuto è calcolata automaticamente. |
| [marginsPercent](#marginsPercent-double-double-double-double-) | Crea i parametri di ridimensionamento. I margini sono specificati in percentuale della dimensione iniziale della pagina. |
| [pageResize](#pageResize-double-double-) | Crea i parametri di ridimensionamento per il ridimensionamento della pagina. |
| [pageResizePct](#pageResizePct-double-double-) | Crea i parametri di ridimensionamento per il ridimensionamento della pagina. Le nuove dimensioni sono specificate in percentuale. |
| [setBottomMargin](#setBottomMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Ottiene o imposta il margine inferiore sulla pagina risultante. |
| [setChangeMediaBox](#setChangeMediaBox-boolean-) | Imposta se regolare il MediaBox di una pagina PDF durante l'operazione di ridimensionamento. Il valore predefinito è {@code false}. Impostare questo parametro consente di adattare il MediaBox al valore del CropBox durante il ridimensionamento. |
| [setContentsHeight](#setContentsHeight-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Ottiene o imposta l'altezza del contenuto della pagina di origine sulla pagina risultante. |
| [setContentsWidth](#setContentsWidth-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Ottiene o imposta la larghezza del contenuto della pagina di origine sulla pagina risultante. |
| [setLeftMargin](#setLeftMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Ottiene o imposta il margine sinistro sulla pagina risultante. |
| [setRightMargin](#setRightMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Ottiene o imposta il margine destro sulla pagina risultante. |
| [setTopMargin](#setTopMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Ottiene o imposta il margine superiore sulla pagina risultante. |

### ContentsResizeParameters {#ContentsResizeParameters--}
```
public ContentsResizeParameters()
```

Crea parametri di ridimensionamento in cui tutti i valori sono impostati su "auto". Successivamente i margini e la dimensione del contenuto possono essere specificati se necessario.

### ContentsResizeParameters {#ContentsResizeParameters-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Crea parametri di ridimensionamento in cui tutti i valori sono impostati su "auto". Successivamente i margini e la dimensione del contenuto possono essere specificati se necessario.

### contentSize {#contentSize-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters contentSize(double width, double height)
```

Crea parametri di ridimensionamento con la dimensione del contenuto specificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| larghezza |  | Nuova larghezza del contenuto. |
| altezza |  | Nuova altezza del contenuto. |

**Returns:**
Restituisce i nuovi parametri di ridimensionamento.

### contentSizePercent {#contentSizePercent-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters contentSizePercent(double width, double height)
```

Crea parametri di ridimensionamento con la dimensione del contenuto specificata in percentuale della dimensione della pagina iniziale. I margini sono calcolati automaticamente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| larghezza |  | Nuova larghezza del contenuto in percentuale. |
| altezza |  | Nuova altezza del contenuto in percentuale. |

**Returns:**
Nuovi parametri di ridimensionamento.

### getBottomMargin {#getBottomMargin--}
```
public IPdfFileEditor.ContentsResizeValue getBottomMargin()
```

Ottiene o imposta il margine inferiore sulla pagina risultante.

**Returns:**
Oggetto ContentsResizeValue

### getContentsHeight {#getContentsHeight--}
```
public IPdfFileEditor.ContentsResizeValue getContentsHeight()
```

Ottiene o imposta l'altezza del contenuto della pagina di origine sulla pagina risultante.

**Returns:**
Oggetto ContentsResizeValue

### getContentsWidth {#getContentsWidth--}
```
public IPdfFileEditor.ContentsResizeValue getContentsWidth()
```

Ottiene o imposta la larghezza del contenuto della pagina di origine sulla pagina risultante.

**Returns:**
Oggetto ContentsResizeValue

### getLeftMargin {#getLeftMargin--}
```
public IPdfFileEditor.ContentsResizeValue getLeftMargin()
```

Ottiene o imposta il margine sinistro sulla pagina risultante.

**Returns:**
Oggetto ContentsResizeValue

### getRightMargin {#getRightMargin--}
```
public IPdfFileEditor.ContentsResizeValue getRightMargin()
```

Ottiene o imposta il margine destro sulla pagina risultante.

**Returns:**
Oggetto ContentsResizeValue

### getTopMargin {#getTopMargin--}
```
public IPdfFileEditor.ContentsResizeValue getTopMargin()
```

Ottiene o imposta il margine superiore sulla pagina risultante.

**Returns:**
Oggetto ContentsResizeValue

### isChangeMediaBox {#isChangeMediaBox--}
```
public final boolean isChangeMediaBox()
```

Ottiene se regolare il MediaBox di una pagina PDF durante l'operazione di ridimensionamento. Il valore predefinito è {@code false}. Impostare questo parametro consente di adattare il MediaBox al valore del CropBox durante il ridimensionamento.

**Returns:**
se regolare il MediaBox di una pagina PDF durante l'operazione di ridimensionamento.

### margins {#margins-double-double-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters margins(double left, double right, double top, double bottom)
```

Crea parametri di ridimensionamento con il valore dei margini specificato. La dimensione del contenuto è calcolata automaticamente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sinistra |  | Margine sinistro. |
| destro |  | Margine destro. |
| alto |  | Margine superiore. |
| inferiore |  | Margine inferiore. |

**Returns:**
Parametri di ridimensionamento creati.

### marginsPercent {#marginsPercent-double-double-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters marginsPercent(double left, double right, double top, double bottom)
```

Crea i parametri di ridimensionamento. I margini sono specificati in percentuale della dimensione iniziale della pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sinistra |  | Margine sinistro (in percentuale della larghezza della pagina). |
| destro |  | Margine destro (in percentuale dell'altezza della pagina). |
| alto |  | Margine superiore (in percentuale dell'altezza della pagina). |
| inferiore |  | Margine inferiore (in percentuale dell'altezza della pagina). |

**Returns:**
Restituisce i nuovi parametri di ridimensionamento.

### pageResize {#pageResize-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters pageResize(double width, double height)
```

Crea i parametri di ridimensionamento per il ridimensionamento della pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| larghezza |  | Nuova larghezza della pagina in unità. |
| altezza |  | Nuova altezza della pagina in unità. |

**Returns:**
Nuovi parametri di ridimensionamento.

### pageResizePct {#pageResizePct-double-double-}
```
public IPdfFileEditor.ContentsResizeParameters pageResizePct(double widthPct, double heightPct)
```

Crea i parametri di ridimensionamento per il ridimensionamento della pagina. Le nuove dimensioni sono specificate in percentuale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| widthPct |  | Nuova larghezza della pagina in percentuale. |
| heightPct |  | Nuova altezza della pagina in percentuale. |

**Returns:**
Nuovi parametri di ridimensionamento.

### setBottomMargin {#setBottomMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Ottiene o imposta il margine inferiore sulla pagina risultante.

### setChangeMediaBox {#setChangeMediaBox-boolean-}
```
public final void setChangeMediaBox(boolean value)
```

Imposta se regolare il MediaBox di una pagina PDF durante l'operazione di ridimensionamento. Il valore predefinito è {@code false}. Impostare questo parametro consente di adattare il MediaBox al valore del CropBox durante il ridimensionamento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | se regolare il MediaBox di una pagina PDF durante l'operazione di ridimensionamento. |

### setContentsHeight {#setContentsHeight-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Ottiene o imposta l'altezza del contenuto della pagina di origine sulla pagina risultante.

### setContentsWidth {#setContentsWidth-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Ottiene o imposta la larghezza del contenuto della pagina di origine sulla pagina risultante.

### setLeftMargin {#setLeftMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Ottiene o imposta il margine sinistro sulla pagina risultante.

### setRightMargin {#setRightMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Ottiene o imposta il margine destro sulla pagina risultante.

### setTopMargin {#setTopMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Ottiene o imposta il margine superiore sulla pagina risultante.
