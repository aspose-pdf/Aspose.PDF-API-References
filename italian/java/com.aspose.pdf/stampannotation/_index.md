---
title: "StampAnnotation"
linktitle: "StampAnnotation"
second_title: "Riferimento API Aspose.PDF per Java"
description: "<p> Rappresenta un'annotazione di timbro di gomma. Questo tipo di annotazione visualizza testo o grafica destinati a sembrare come se fossero stati timbrati sulla pagina con un timbro di gomma. </p> <hr>."
type: docs
weight: 4630
url: /it/java/com.aspose.pdf/stampannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.StampAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.StampAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.StampAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.StampAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class StampAnnotation extends MarkupAnnotation
```

<p> Rappresenta l'annotazione di timbro di gomma. Questo tipo di annotazione visualizza testo o grafica destinati a sembrare come se fossero stati timbrati sulla pagina con un timbro di gomma. </p> <hr> <pre> Il prossimo frammento di codice dimostra come aggiungere 2 timbri nella prima pagina del documento PDF. Il documento di input proviene da inFile e le modifiche vengono salvate in outFile. Il primo timbro ha l'icona NotForPublicRelease e il secondo proviene dall'immagine rubber.jpg. Document document = new Document(inFile); StampAnnotation stamp1 = new StampAnnotation(StampIcon.NotForPublicRelease); stamp1.setRect ( new Rectangle(100, 100, 120, 120)) document.getPages().get(1).getAnnotations().add(stamp1); StampAnnotation stamp2 = new StampAnnotation(new FileStream("rubber.jpg", FileMode.Open)); stamp2.setRect ( new Rectangle(200, 200, 220, 220)) document.getPages().get(1).getAnnotations().add(stamp2); document.save(outFile); </pre>

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [StampAnnotation](#StampAnnotation-com.aspose.pdf.IDocument-) | Costruttore |
| [StampAnnotation](#StampAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Crea una nuova annotazione Stamp nella pagina specificata. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accetta il visitatore {@code AnnotationSelector} durante l'esplorazione della collezione di annotazioni. |
| [clear](#clear--) | Cancella le istanze statiche |
| [getAnnotationType](#getAnnotationType--) | Ottiene il tipo di annotazione. |
| [getIcon](#getIcon--) | Ottiene l'icona per il timbro di gomma. |
| [getImage](#getImage--) | Ottiene l'immagine dell'annotazione. |
| [setBase64SVGImage](#setBase64SVGImage-java.lang.String-) | Imposta l'immagine SVG dell'annotazione in stringa Base64. |
| [setIcon](#setIcon-com.aspose.pdf.StampIcon-) | Imposta l'icona per il timbro di gomma. |
| [setImage](#setImage-java.io.InputStream-) | Imposta l'immagine dell'annotazione. |

### StampAnnotation {#StampAnnotation-com.aspose.pdf.IDocument-}
Costruttore

### StampAnnotation {#StampAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Crea una nuova annotazione Stamp nella pagina specificata.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accetta il visitatore {@code AnnotationSelector} durante l'esplorazione della collezione di annotazioni.

### clear {#clear--}
```
public static void clear()
```

Cancella le istanze statiche

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Ottiene il tipo di annotazione.

**Returns:**
Elemento AnnotationType @see AnnotationType

### getIcon {#getIcon--}
```
public StampIcon getIcon()
```

Ottiene l'icona per il timbro di gomma.

**Returns:**
StampIcon valore

### getImage {#getImage--}
```
public InputStream getImage()
```

Ottiene l'immagine dell'annotazione.

**Returns:**
Oggetto InputStream

### setBase64SVGImage {#setBase64SVGImage-java.lang.String-}
Imposta l'immagine SVG dell'annotazione in stringa Base64.

### setIcon {#setIcon-com.aspose.pdf.StampIcon-}
Imposta l'icona per il timbro di gomma.

### setImage {#setImage-java.io.InputStream-}
Imposta l'immagine dell'annotazione.
