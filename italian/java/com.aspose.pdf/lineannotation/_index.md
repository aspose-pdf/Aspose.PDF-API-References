---
title: "LineAnnotation"
linktitle: "LineAnnotation"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta un'annotazione di linea."
type: docs
weight: 2710
url: /it/java/com.aspose.pdf/lineannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.LineAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.LineAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.LineAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.LineAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class LineAnnotation extends MarkupAnnotation
```

Classe che rappresenta un'annotazione di linea.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [LineAnnotation](#LineAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.Point-com.aspose.pdf.Point-) | Costruttore per l'uso con Generator. |
| [LineAnnotation](#LineAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.Point-com.aspose.pdf.Point-) | Crea una nuova annotazione Line nella pagina specificata. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accetta un visitatore per l'elaborazione dell'annotazione. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Aggiorna i punti di inizio e fine, secondo la trasformazione della matrice. |
| [getAnnotationType](#getAnnotationType--) | Ottiene il tipo di annotazione. |
| [getCaptionOffset](#getCaptionOffset--) | Ottiene lo spostamento del testo della didascalia dalla sua posizione normale. |
| [getCaptionPosition](#getCaptionPosition--) | Ottiene la posizione della didascalia dell'annotazione. |
| [getEnding](#getEnding--) | Ottiene il punto finale della linea. |
| [getEndingStyle](#getEndingStyle--) | Ottiene lo stile di chiusura per il punto finale della linea. |
| [getIntent](#getIntent--) | Ottiene l'intento dell'annotazione line. |
| [getInteriorColor](#getInteriorColor--) | Ottiene il colore interno dell'annotazione. |
| [getLeaderLine](#getLeaderLine--) | Ottiene la lunghezza della linea guida. |
| [getLeaderLineExtension](#getLeaderLineExtension--) | Ottiene la lunghezza dell'estensione della linea guida. |
| [getLeaderLineOffset](#getLeaderLineOffset--) | Ottiene lo spostamento della linea guida. |
| [getMeasure](#getMeasure--) | Unità di misura specificate per questa annotazione. |
| [getShowCaption](#getShowCaption--) | Ottiene il flag booleano che determina se il contenuto deve essere mostrato come didascalia. |
| [getStarting](#getStarting--) | Ottiene il punto di inizio della linea. |
| [getStartingStyle](#getStartingStyle--) | Ottiene lo stile di chiusura della linea per il punto di inizio della linea. |
| [setCaptionOffset](#setCaptionOffset-com.aspose.pdf.Point-) | Imposta lo spostamento del testo della didascalia dalla sua posizione normale. |
| [setCaptionPosition](#setCaptionPosition-com.aspose.pdf.CaptionPosition-) | Imposta la posizione della didascalia dell'annotazione. |
| [setEnding](#setEnding-com.aspose.pdf.Point-) | Imposta il punto finale della linea. |
| [setEndingStyle](#setEndingStyle-com.aspose.pdf.LineEnding-) | Imposta lo stile di chiusura per il punto finale della linea. |
| [setIntent](#setIntent-com.aspose.pdf.LineIntent-) | Imposta l'intento dell'annotazione line. |
| [setInteriorColor](#setInteriorColor-com.aspose.pdf.Color-) | Imposta il colore interno dell'annotazione. |
| [setLeaderLine](#setLeaderLine-double-) | Imposta la lunghezza della linea guida. |
| [setLeaderLineExtension](#setLeaderLineExtension-double-) | Imposta la lunghezza dell'estensione della linea guida. |
| [setLeaderLineOffset](#setLeaderLineOffset-double-) | Imposta l'offset della linea guida. |
| [setMeasure](#setMeasure-com.aspose.pdf.Measure-) | Unità di misura specificate per questa annotazione. |
| [setShowCaption](#setShowCaption-boolean-) | Imposta il flag booleano che determina se il contenuto deve essere mostrato come didascalia. |
| [setStarting](#setStarting-com.aspose.pdf.Point-) | Imposta il punto di partenza della linea. |
| [setStartingStyle](#setStartingStyle-com.aspose.pdf.LineEnding-) | Imposta lo stile di terminazione della linea per il punto di partenza della linea. |

### LineAnnotation {#LineAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.Point-com.aspose.pdf.Point-}
Costruttore per l'uso con Generator.

### LineAnnotation {#LineAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.Point-com.aspose.pdf.Point-}
Crea una nuova annotazione Line nella pagina specificata.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accetta un visitatore per l'elaborazione dell'annotazione.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Aggiorna i punti di inizio e fine, secondo la trasformazione della matrice.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Ottiene il tipo di annotazione.

**Returns:**
Elemento AnnotationType @see AnnotationType

### getCaptionOffset {#getCaptionOffset--}
```
public Point getCaptionOffset()
```

Ottiene lo spostamento del testo della didascalia dalla sua posizione normale.

**Returns:**
Oggetto Point

### getCaptionPosition {#getCaptionPosition--}
```
public CaptionPosition getCaptionPosition()
```

Ottiene la posizione della didascalia dell'annotazione.

**Returns:**
Elemento CaptionPosition @see CaptionPosition

### getEnding {#getEnding--}
```
public Point getEnding()
```

Ottiene il punto finale della linea.

**Returns:**
Valore del punto

### getEndingStyle {#getEndingStyle--}
```
public LineEnding getEndingStyle()
```

Ottiene lo stile di chiusura per il punto finale della linea.

**Returns:**
Elemento LineEnding @see LineEnding

### getIntent {#getIntent--}
```
public LineIntent getIntent()
```

Ottiene l'intento dell'annotazione line.

**Returns:**
Elemento LineIntent @see LineIntent

### getInteriorColor {#getInteriorColor--}
```
public Color getInteriorColor()
```

Ottiene il colore interno dell'annotazione.

**Returns:**
oggetto Color

### getLeaderLine {#getLeaderLine--}
```
public double getLeaderLine()
```

Ottiene la lunghezza della linea guida.

**Returns:**
valore double

### getLeaderLineExtension {#getLeaderLineExtension--}
```
public double getLeaderLineExtension()
```

Ottiene la lunghezza dell'estensione della linea guida.

**Returns:**
valore double

### getLeaderLineOffset {#getLeaderLineOffset--}
```
public double getLeaderLineOffset()
```

Ottiene lo spostamento della linea guida.

**Returns:**
valore double

### getMeasure {#getMeasure--}
```
public Measure getMeasure()
```

Unità di misura specificate per questa annotazione.

**Returns:**
Oggetto Measure

### getShowCaption {#getShowCaption--}
```
public boolean getShowCaption()
```

Ottiene il flag booleano che determina se il contenuto deve essere mostrato come didascalia.

**Returns:**
valore booleano

### getStarting {#getStarting--}
```
public Point getStarting()
```

Ottiene il punto di inizio della linea.

**Returns:**
Valore del punto

### getStartingStyle {#getStartingStyle--}
```
public LineEnding getStartingStyle()
```

Ottiene lo stile di chiusura della linea per il punto di inizio della linea.

**Returns:**
Elemento LineEnding @see LineEnding

### setCaptionOffset {#setCaptionOffset-com.aspose.pdf.Point-}
Imposta lo spostamento del testo della didascalia dalla sua posizione normale.

### setCaptionPosition {#setCaptionPosition-com.aspose.pdf.CaptionPosition-}
Imposta la posizione della didascalia dell'annotazione.

### setEnding {#setEnding-com.aspose.pdf.Point-}
Imposta il punto finale della linea.

### setEndingStyle {#setEndingStyle-com.aspose.pdf.LineEnding-}
Imposta lo stile di chiusura per il punto finale della linea.

### setIntent {#setIntent-com.aspose.pdf.LineIntent-}
Imposta l'intento dell'annotazione line.

### setInteriorColor {#setInteriorColor-com.aspose.pdf.Color-}
Imposta il colore interno dell'annotazione.

### setLeaderLine {#setLeaderLine-double-}
```
public void setLeaderLine(double value)
```

Imposta la lunghezza della linea guida.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setLeaderLineExtension {#setLeaderLineExtension-double-}
```
public void setLeaderLineExtension(double value)
```

Imposta la lunghezza dell'estensione della linea guida.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setLeaderLineOffset {#setLeaderLineOffset-double-}
```
public void setLeaderLineOffset(double value)
```

Imposta l'offset della linea guida.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setMeasure {#setMeasure-com.aspose.pdf.Measure-}
Unità di misura specificate per questa annotazione.

### setShowCaption {#setShowCaption-boolean-}
```
public void setShowCaption(boolean value)
```

Imposta il flag booleano che determina se il contenuto deve essere mostrato come didascalia.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setStarting {#setStarting-com.aspose.pdf.Point-}
Imposta il punto di partenza della linea.

### setStartingStyle {#setStartingStyle-com.aspose.pdf.LineEnding-}
Imposta lo stile di terminazione della linea per il punto di partenza della linea.
