---
title: "MovieAnnotation"
linktitle: "MovieAnnotation"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta un'annotazione video che contiene grafiche animate e suono da presentare sullo schermo del computer e attraverso gli altoparlanti. Quando l'annotazione è attivata, il."
type: docs
weight: 3090
url: /it/java/com.aspose.pdf/movieannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MovieAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MovieAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MovieAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class MovieAnnotation extends Annotation implements com.aspose.pdf.engine.ITitledAnnotation
```

Rappresenta un'annotazione video che contiene grafiche animate e suono da presentare sullo schermo del computer e attraverso gli altoparlanti. Quando l'annotazione è attivata, il video viene riprodotto.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MovieAnnotation](#MovieAnnotation-com.aspose.pdf.IDocument-java.lang.String-) | Costruttore per l'uso con Generator. |
| [MovieAnnotation](#MovieAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-) | Crea una nuova annotazione Sound nella pagina specificata. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accetta un oggetto visitor per elaborare l'annotazione. |
| [getAnnotationType](#getAnnotationType--) | Ottiene il tipo di annotazione. |
| [getAspect](#getAspect--) | Ottiene o imposta la larghezza e l'altezza del riquadro di delimitazione del film, in pixel. |
| [getFile](#getFile--) | Ottiene una specifica di file che identifica un file video auto-descrittivo. |
| [getPoster](#getPoster--) | Ottiene o imposta un flag o uno stream che specifica se e come deve essere visualizzata l'immagine poster che rappresenta il film. Se vero, l'immagine poster verrà recuperata dal file video; se falso, non verrà visualizzato alcun poster. |
| [getRotate](#getRotate--) | Ottiene o imposta il numero di gradi di cui il film deve essere ruotato in senso orario rispetto alla pagina. Il valore deve essere un multiplo di 90. |
| [getTitle](#getTitle--) | Ottiene il titolo dell'annotazione video. |
| [setAspect](#setAspect-com.aspose.pdf.Point-) | Ottiene o imposta la larghezza e l'altezza del riquadro di delimitazione del film, in pixel. |
| [setFile](#setFile-com.aspose.pdf.FileSpecification-) | Imposta una specifica di file che identifica un file video auto-descrittivo. |
| [setPoster](#setPoster-boolean-) | Ottiene o imposta un flag o uno stream che specifica se e come deve essere visualizzata l'immagine poster che rappresenta il film. Se vero, l'immagine poster verrà recuperata dal file video; se falso, non verrà visualizzato alcun poster. |
| [setRotate](#setRotate-int-) | Ottiene o imposta il numero di gradi di cui il film deve essere ruotato in senso orario rispetto alla pagina. Il valore deve essere un multiplo di 90. |
| [setTitle](#setTitle-java.lang.String-) | Imposta il titolo dell'annotazione video. |

### MovieAnnotation {#MovieAnnotation-com.aspose.pdf.IDocument-java.lang.String-}
Costruttore per l'uso con Generator.

### MovieAnnotation {#MovieAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-}
Crea una nuova annotazione Sound nella pagina specificata.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accetta un oggetto visitor per elaborare l'annotazione.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Ottiene il tipo di annotazione.

**Returns:**
Elemento AnnotationType come valore int @see AnnotationType

### getAspect {#getAspect--}
```
public final Point getAspect()
```

Ottiene o imposta la larghezza e l'altezza del riquadro di delimitazione del film, in pixel.

**Returns:**
Istanza di Point

### getFile {#getFile--}
```
public FileSpecification getFile()
```

Ottiene una specifica di file che identifica un file video auto-descrittivo.

**Returns:**
Valore FileSpecification

### getPoster {#getPoster--}
```
public final boolean getPoster()
```

Ottiene o imposta un flag o uno stream che specifica se e come deve essere visualizzata l'immagine poster che rappresenta il film. Se vero, l'immagine poster verrà recuperata dal file video; se falso, non verrà visualizzato alcun poster.

**Returns:**
valore booleano

### getRotate {#getRotate--}
```
public final int getRotate()
```

Ottiene o imposta il numero di gradi di cui il film deve essere ruotato in senso orario rispetto alla pagina. Il valore deve essere un multiplo di 90.

**Returns:**
valore int

### getTitle {#getTitle--}
```
public String getTitle()
```

Ottiene il titolo dell'annotazione video.

**Returns:**
valore String

### setAspect {#setAspect-com.aspose.pdf.Point-}
Ottiene o imposta la larghezza e l'altezza del riquadro di delimitazione del film, in pixel.

### setFile {#setFile-com.aspose.pdf.FileSpecification-}
Imposta una specifica di file che identifica un file video auto-descrittivo.

### setPoster {#setPoster-boolean-}
```
public final void setPoster(boolean value)
```

Ottiene o imposta un flag o uno stream che specifica se e come deve essere visualizzata l'immagine poster che rappresenta il film. Se vero, l'immagine poster verrà recuperata dal file video; se falso, non verrà visualizzato alcun poster.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setRotate {#setRotate-int-}
```
public final void setRotate(int value)
```

Ottiene o imposta il numero di gradi di cui il film deve essere ruotato in senso orario rispetto alla pagina. Il valore deve essere un multiplo di 90.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setTitle {#setTitle-java.lang.String-}
Imposta il titolo dell'annotazione video.
