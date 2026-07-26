---
title: "RedactionAnnotation"
linktitle: "RedactionAnnotation"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta l'annotazione Redact."
type: docs
weight: 4120
url: /it/java/com.aspose.pdf/redactionannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.RedactionAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.RedactionAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.RedactionAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.RedactionAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class RedactionAnnotation extends MarkupAnnotation
```

Rappresenta l'annotazione Redact.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [RedactionAnnotation](#RedactionAnnotation-com.aspose.pdf.IDocument-) | Costruttore per RedactionAnnotation. Per l'uso in Generator. |
| [RedactionAnnotation](#RedactionAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Costruttore per RedactAnnotation. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accetta un oggetto visitor per elaborare l'annotazione. |
| [flatten](#flatten--) | Appiattisce l'annotazione, cioè rimuove l'annotazione e aggiunge il suo contenuto |
| [getAnnotationType](#getAnnotationType--) | Ottiene il tipo di annotazione. |
| [getBorderColor](#getBorderColor--) | Ottiene il colore del bordo che viene disegnato quando la redazione non è attiva. |
| [getDefaultAppearance](#getDefaultAppearance--) | Ottiene o imposta la stringa di aspetto predefinito da utilizzare nella formattazione del testo. |
| [getFillColor](#getFillColor--) | Ottiene il colore per riempire l'annotazione. |
| [getFontSize](#getFontSize--) | Ottiene la dimensione del carattere per OverlayText. |
| [getOverlayText](#getOverlayText--) | Ottiene il testo da stampare sull'annotazione di redazione. |
| [getQuadPoint](#getQuadPoint--) | Un array di numeri 8xN che specifica le coordinate della regione di contenuto destinata a essere rimossa. |
| [getQuadPoints](#getQuadPoints--) | Restituisce un array di punti che specificano le coordinate di n quadrilateri. Ogni quadrilatero comprende una parola o un gruppo di parole contigue nel testo sottostante l'annotazione. |
| [getTextAlignment](#getTextAlignment--) | Ottiene l'allineamento di Overlay Text. |
| [isRepeat](#isRepeat--) | Se vero, il testo overlay verrà ripetuto sull'annotazione. |
| [redact](#redact--) | Appiattisce l'annotazione e redige i contenuti della pagina (cioè rimuove testo e contenuto immagine sotto l'annotazione redatta) |
| [redactExact](#redactExact--) | Appiattisce l'annotazione e redige i contenuti della pagina (cioè rimuove testo e contenuto immagine esattamente sotto l'annotazione redatta) |
| [setBorderColor](#setBorderColor-com.aspose.pdf.Color-) | Imposta il colore del bordo che viene disegnato quando la redazione non è attiva. |
| [setDefaultAppearance](#setDefaultAppearance-java.lang.String-) | Ottiene o imposta la stringa di aspetto predefinito da utilizzare nella formattazione del testo. |
| [setFillColor](#setFillColor-com.aspose.pdf.Color-) | Imposta il colore per riempire l'annotazione. |
| [setFontSize](#setFontSize-float-) | Imposta la dimensione del carattere per OverlayText. Il valore predefinito è 10. |
| [setOverlayText](#setOverlayText-java.lang.String-) | Imposta il testo da stampare sull'annotazione di redazione. |
| [setQuadPoint](#setQuadPoint-com.aspose.pdf.Point:A-) | Un array di numeri 8xN che specifica le coordinate della regione di contenuto destinata a essere rimossa. |
| [setQuadPoints](#setQuadPoints-com.aspose.pdf.Point:A-) | Imposta un array di punti che specificano le coordinate di n quadrilateri. Ogni quadrilatero comprende una parola o un gruppo di parole contigue nel testo sottostante l'annotazione. |
| [setRepeat](#setRepeat-boolean-) | Se vero, il testo overlay verrà ripetuto sull'annotazione. |
| [setTextAlignment](#setTextAlignment-com.aspose.pdf.HorizontalAlignment-) | Imposta l'allineamento di Overlay Text. |

### RedactionAnnotation {#RedactionAnnotation-com.aspose.pdf.IDocument-}
Costruttore per RedactionAnnotation. Per l'uso in Generator.

### RedactionAnnotation {#RedactionAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Costruttore per RedactAnnotation.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accetta un oggetto visitor per elaborare l'annotazione.

### flatten {#flatten--}
```
public void flatten()
```

Appiattisce l'annotazione, cioè rimuove l'annotazione e aggiunge il suo contenuto

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Ottiene il tipo di annotazione.

**Returns:**
Elemento AnnotationType @see AnnotationType

### getBorderColor {#getBorderColor--}
```
public Color getBorderColor()
```

Ottiene il colore del bordo che viene disegnato quando la redazione non è attiva.

**Returns:**
Valore colore

### getDefaultAppearance {#getDefaultAppearance--}
```
public final String getDefaultAppearance()
```

Ottiene o imposta la stringa di aspetto predefinito da utilizzare nella formattazione del testo.

**Returns:**
valore String

### getFillColor {#getFillColor--}
```
public Color getFillColor()
```

Ottiene il colore per riempire l'annotazione.

**Returns:**
valore colore

### getFontSize {#getFontSize--}
```
public final float getFontSize()
```

Ottiene la dimensione del carattere per OverlayText.

**Returns:**
valore int

### getOverlayText {#getOverlayText--}
```
public String getOverlayText()
```

Ottiene il testo da stampare sull'annotazione di redazione.

**Returns:**
valore stringa

### getQuadPoint {#getQuadPoint--}
```
public Point [] getQuadPoint()
```

Un array di numeri 8xN che specifica le coordinate della regione di contenuto destinata a essere rimossa.

**Returns:**
array di punti

### getQuadPoints {#getQuadPoints--}
```
@Deprecated public Point [] getQuadPoints()
```

Restituisce un array di punti che specificano le coordinate di n quadrilateri. Ogni quadrilatero comprende una parola o un gruppo di parole contigue nel testo sottostante l'annotazione.

**Returns:**
array di valore Point

### getTextAlignment {#getTextAlignment--}
```
public HorizontalAlignment getTextAlignment()
```

Ottiene l'allineamento di Overlay Text.

**Returns:**
Valore HorizontalAlignment @see HorizontalAlignment

### isRepeat {#isRepeat--}
```
public boolean isRepeat()
```

Se vero, il testo overlay verrà ripetuto sull'annotazione.

**Returns:**
valore booleano

### redact {#redact--}
```
public void redact()
```

Appiattisce l'annotazione e redige i contenuti della pagina (cioè rimuove testo e contenuto immagine sotto l'annotazione redatta)

### redactExact {#redactExact--}
```
public void redactExact()
```

Appiattisce l'annotazione e redige i contenuti della pagina (cioè rimuove testo e contenuto immagine esattamente sotto l'annotazione redatta)

### setBorderColor {#setBorderColor-com.aspose.pdf.Color-}
Imposta il colore del bordo che viene disegnato quando la redazione non è attiva.

### setDefaultAppearance {#setDefaultAppearance-java.lang.String-}
Ottiene o imposta la stringa di aspetto predefinito da utilizzare nella formattazione del testo.

### setFillColor {#setFillColor-com.aspose.pdf.Color-}
Imposta il colore per riempire l'annotazione.

### setFontSize {#setFontSize-float-}
```
public final void setFontSize(float fontSize)
```

Imposta la dimensione del carattere per OverlayText. Il valore predefinito è 10.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontSize |  | valore int |

### setOverlayText {#setOverlayText-java.lang.String-}
Imposta il testo da stampare sull'annotazione di redazione.

### setQuadPoint {#setQuadPoint-com.aspose.pdf.Point:A-}
Un array di numeri 8xN che specifica le coordinate della regione di contenuto destinata a essere rimossa.

### setQuadPoints {#setQuadPoints-com.aspose.pdf.Point:A-}
Imposta un array di punti che specificano le coordinate di n quadrilateri. Ogni quadrilatero comprende una parola o un gruppo di parole contigue nel testo sottostante l'annotazione.

### setRepeat {#setRepeat-boolean-}
```
public void setRepeat(boolean value)
```

Se vero, il testo overlay verrà ripetuto sull'annotazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setTextAlignment {#setTextAlignment-com.aspose.pdf.HorizontalAlignment-}
Imposta l'allineamento di Overlay Text.
