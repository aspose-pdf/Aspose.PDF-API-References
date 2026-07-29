---
title: "PolyAnnotation"
linktitle: "PolyAnnotation"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe base astratta per le poliannotazioni."
type: docs
weight: 3890
url: /it/java/com.aspose.pdf/polyannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.PolyAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.PolyAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.PolyAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.PolyAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public abstract class PolyAnnotation extends MarkupAnnotation
```

Classe base astratta per le poliannotazioni.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Aggiorna i punti in Vertices, secondo la trasformazione della matrice. |
| [getEndingStyle](#getEndingStyle--) | Ottiene lo stile della fine della seconda linea. |
| [getIntent](#getIntent--) | Ottiene l'intento dell'annotazione poligono o polilinea. |
| [getInteriorColor](#getInteriorColor--) | Ottiene il colore interno con cui riempire le estremità delle linee dell'annotazione. |
| [getMeasure](#getMeasure--) | Unità di misura specificate per questa annotazione. |
| [getStartingStyle](#getStartingStyle--) | Ottiene lo stile della fine della prima linea. |
| [getVertices](#getVertices--) | Ottiene un array di punti che rappresentano le coordinate orizzontali e verticali di ciascun vertice. |
| [setEndingStyle](#setEndingStyle-com.aspose.pdf.LineEnding-) | Imposta lo stile della fine della seconda linea. |
| [setIntent](#setIntent-com.aspose.pdf.PolyIntent-) | Imposta l'intento dell'annotazione poligono o polilinea. |
| [setInteriorColor](#setInteriorColor-com.aspose.pdf.Color-) | Imposta il colore interno con cui riempire le estremità delle linee dell'annotazione. |
| [setMeasure](#setMeasure-com.aspose.pdf.Measure-) | Unità di misura specificate per questa annotazione. |
| [setStartingStyle](#setStartingStyle-com.aspose.pdf.LineEnding-) | Imposta lo stile della fine della prima linea. |
| [setVertices](#setVertices-com.aspose.pdf.Point:A-) | Imposta un array di punti che rappresentano le coordinate orizzontali e verticali di ciascun vertice. |

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Aggiorna i punti in Vertices, secondo la trasformazione della matrice.

### getEndingStyle {#getEndingStyle--}
```
public LineEnding getEndingStyle()
```

Ottiene lo stile della fine della seconda linea.

**Returns:**
Elemento LineEnding @see LineEnding

### getIntent {#getIntent--}
```
public PolyIntent getIntent()
```

Ottiene l'intento dell'annotazione poligono o polilinea.

**Returns:**
Elemento PolyIntent @see PolyIntent

### getInteriorColor {#getInteriorColor--}
```
public Color getInteriorColor()
```

Ottiene il colore interno con cui riempire le estremità delle linee dell'annotazione.

**Returns:**
oggetto Color

### getMeasure {#getMeasure--}
```
public Measure getMeasure()
```

Unità di misura specificate per questa annotazione.

**Returns:**
Istanza Measure

### getStartingStyle {#getStartingStyle--}
```
public LineEnding getStartingStyle()
```

Ottiene lo stile della fine della prima linea.

**Returns:**
Elemento LineEnding @see LineEnding

### getVertices {#getVertices--}
```
public Point [] getVertices()
```

Ottiene un array di punti che rappresentano le coordinate orizzontali e verticali di ciascun vertice.

**Returns:**
array di valore Point

### setEndingStyle {#setEndingStyle-com.aspose.pdf.LineEnding-}
Imposta lo stile della fine della seconda linea.

### setIntent {#setIntent-com.aspose.pdf.PolyIntent-}
Imposta l'intento dell'annotazione poligono o polilinea.

### setInteriorColor {#setInteriorColor-com.aspose.pdf.Color-}
Imposta il colore interno con cui riempire le estremità delle linee dell'annotazione.

### setMeasure {#setMeasure-com.aspose.pdf.Measure-}
Unità di misura specificate per questa annotazione.

### setStartingStyle {#setStartingStyle-com.aspose.pdf.LineEnding-}
Imposta lo stile della fine della prima linea.

### setVertices {#setVertices-com.aspose.pdf.Point:A-}
Imposta un array di punti che rappresentano le coordinate orizzontali e verticali di ciascun vertice.
