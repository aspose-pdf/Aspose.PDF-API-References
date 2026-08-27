---
title: "InkAnnotation"
linktitle: "InkAnnotation"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta un \\\"scribble\\\" a mano libera composto da uno o più percorsi disgiunti."
type: docs
weight: 2430
url: /it/java/com.aspose.pdf/inkannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.InkAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.InkAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.InkAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.InkAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class InkAnnotation extends MarkupAnnotation
```

Rappresenta uno \"scarabocchio\" a mano libera composto da uno o più percorsi disgiunti.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [InkAnnotation](#InkAnnotation-com.aspose.pdf.IDocument-java.util.List-) | Costruttore per l'annotazione Ink per Generator. |
| [InkAnnotation](#InkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.util.List-) | Crea una nuova annotazione Ink nella pagina specificata. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accetta un oggetto visitor per elaborare l'annotazione. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Aggiorna i punti in InkList, secondo la trasformazione della matrice. |
| [getAnnotationType](#getAnnotationType--) | Ottiene il tipo di annotazione. |
| [getCapStyle](#getCapStyle--) | ottieni lo stile delle terminazioni di linea dell'annotazione Ink. |
| [getInkList](#getInkList--) | <p> Restituisce l'elenco dei gesti che sono linee indipendenti rappresentate da array Point[]. </p> |
| [setCapStyle](#setCapStyle-com.aspose.pdf.CapStyle-) | Imposta lo stile delle terminazioni delle linee di annotazione a inchiostro. |
| [setInkList](#setInkList-java.util.List-) | Imposta l'elenco dei gesti che sono linee indipendenti rappresentate da array Point[]. |
| [updateAppearance](#updateAppearance--) | Aggiorna l'Aspetto dopo che il testo è stato modificato/spostato. |

### InkAnnotation {#InkAnnotation-com.aspose.pdf.IDocument-java.util.List-}
Costruttore per l'annotazione Ink per Generator.

### InkAnnotation {#InkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.util.List-}
Crea una nuova annotazione Ink nella pagina specificata.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accetta un oggetto visitor per elaborare l'annotazione.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Aggiorna i punti in InkList, secondo la trasformazione della matrice.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Ottiene il tipo di annotazione.

**Returns:**
Elemento AnnotationType @see AnnotationType

### getCapStyle {#getCapStyle--}
```
public CapStyle getCapStyle()
```

ottieni lo stile delle terminazioni di linea dell'annotazione Ink.

**Returns:**
Elemento CapStyle @see CapStyle

### getInkList {#getInkList--}
```
public List < Point []> getInkList()
```

<p> Restituisce l'elenco dei gesti che sono linee indipendenti rappresentate da array Point[]. </p>

**Returns:**
{@code List<Point[]>} oggetto

### setCapStyle {#setCapStyle-com.aspose.pdf.CapStyle-}
Imposta lo stile delle terminazioni delle linee di annotazione a inchiostro.

### setInkList {#setInkList-java.util.List-}
Imposta l'elenco dei gesti che sono linee indipendenti rappresentate da array Point[].

### updateAppearance {#updateAppearance--}
```
public void updateAppearance()
```

Aggiorna l'Aspetto dopo che il testo è stato modificato/spostato.
