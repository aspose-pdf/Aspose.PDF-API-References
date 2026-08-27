---
title: "GraphicalPdfComparer"
linktitle: "GraphicalPdfComparer"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una classe per confrontare graficamente i documenti PDF. Dovrebbe essere usata per cercare piccole modifiche, principalmente di natura grafica. Per confrontare le modifiche al contenuto testuale, utilizzare altre."
type: docs
weight: 10
url: /it/java/com.aspose.pdf.comparison.graphicalcomparison/graphicalpdfcomparer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.graphicalcomparison.GraphicalPdfComparer

```
public class GraphicalPdfComparer extends Object
```

Rappresenta una classe per confrontare graficamente i documenti PDF. Deve essere usata per cercare piccole modifiche, principalmente di natura grafica. Per confrontare le modifiche al contenuto testuale, utilizzare altre classi di confronto PDF.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [GraphicalPdfComparer](#GraphicalPdfComparer--) | Crea un'istanza della classe {@link GraphicalPdfComparer}. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [compareDocumentsToImages](#compareDocumentsToImages-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-java.lang.String-com.aspose.ms.System.Drawing.Imaging.ImageFormat-) | Confronta i documenti graficamente. |
| [compareDocumentsToPdf](#compareDocumentsToPdf-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-) | Confronta i documenti graficamente. Il risultato del confronto è inserito in un documento PDF. |
| [comparePagesToImage](#comparePagesToImage-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-) | Confronta le pagine graficamente. Il risultato del confronto è inserito in un'immagine. |
| [comparePagesToPdf](#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-com.aspose.pdf.Document-) | Confronta le pagine graficamente. Il risultato del confronto è inserito in un documento PDF. |
| [comparePagesToPdf](#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-) | Confronta le pagine graficamente. Il risultato del confronto è inserito in un documento PDF. |
| [getColor](#getColor--) | Ottiene e imposta il colore della bandiera di modifica. Il colore predefinito è rosso. |
| [getDifference](#getDifference-com.aspose.pdf.Page-com.aspose.pdf.Page-) | Ottiene le differenze tra le immagini delle pagine. Il risultato contiene un'immagine della prima pagina confrontata e un array di differenze. |
| [getResolution](#getResolution--) | Ottiene e imposta la risoluzione delle immagini risultanti. Il valore predefinito è 150 dpi. |
| [getThreshold](#getThreshold--) | Ottiene e imposta il valore soglia in percentuale. Questo valore consente di ignorare piccole modifiche se non sono significative per te. Il valore predefinito è 0%. |
| [setColor](#setColor-com.aspose.pdf.Color-) | Ottiene e imposta il colore della bandiera di modifica. Il colore predefinito è rosso. |
| [setResolution](#setResolution-com.aspose.pdf.devices.Resolution-) | Ottiene e imposta la risoluzione delle immagini risultanti. Il valore predefinito è 150 dpi. |
| [setThreshold](#setThreshold-double-) | Ottiene e imposta il valore soglia in percentuale. Questo valore consente di ignorare piccole modifiche se non sono significative per te. Il valore predefinito è 0%. |

### GraphicalPdfComparer {#GraphicalPdfComparer--}
```
public GraphicalPdfComparer()
```

Crea un'istanza della classe {@link GraphicalPdfComparer}.

### compareDocumentsToImages {#compareDocumentsToImages-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-java.lang.String-com.aspose.ms.System.Drawing.Imaging.ImageFormat-}
Confronta i documenti graficamente.

### compareDocumentsToPdf {#compareDocumentsToPdf-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-}
Confronta i documenti graficamente. Il risultato del confronto è inserito in un documento PDF.

### comparePagesToImage {#comparePagesToImage-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-}
Confronta le pagine graficamente. Il risultato del confronto è inserito in un'immagine.

### comparePagesToPdf {#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-com.aspose.pdf.Document-}
Confronta le pagine graficamente. Il risultato del confronto è inserito in un documento PDF.

### comparePagesToPdf {#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-}
Confronta le pagine graficamente. Il risultato del confronto è inserito in un documento PDF.

### getColor {#getColor--}
```
public final Color getColor()
```

Ottiene e imposta il colore della bandiera di modifica. Il colore predefinito è rosso.

**Returns:**
Istanza di Color

### getDifference {#getDifference-com.aspose.pdf.Page-com.aspose.pdf.Page-}
Ottiene le differenze tra le immagini delle pagine. Il risultato contiene un'immagine della prima pagina confrontata e un array di differenze.

### getResolution {#getResolution--}
```
public final Resolution getResolution()
```

Ottiene e imposta la risoluzione delle immagini risultanti. Il valore predefinito è 150 dpi.

**Returns:**
Istanza Resolution

### getThreshold {#getThreshold--}
```
public final double getThreshold()
```

Ottiene e imposta il valore soglia in percentuale. Questo valore consente di ignorare piccole modifiche se non sono significative per te. Il valore predefinito è 0%.

**Returns:**
valore double

### setColor {#setColor-com.aspose.pdf.Color-}
Ottiene e imposta il colore della bandiera di modifica. Il colore predefinito è rosso.

### setResolution {#setResolution-com.aspose.pdf.devices.Resolution-}
Ottiene e imposta la risoluzione delle immagini risultanti. Il valore predefinito è 150 dpi.

### setThreshold {#setThreshold-double-}
```
public final void setThreshold(double value)
```

Ottiene e imposta il valore soglia in percentuale. Questo valore consente di ignorare piccole modifiche se non sono significative per te. Il valore predefinito è 0%.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |
