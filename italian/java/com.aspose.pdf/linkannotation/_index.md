---
title: "LinkAnnotation"
linktitle: "LinkAnnotation"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta un collegamento ipertestuale a una destinazione altrove nel documento o un'azione da eseguire."
type: docs
weight: 2760
url: /it/java/com.aspose.pdf/linkannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.LinkAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.LinkAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.LinkAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class LinkAnnotation extends Annotation
```

Rappresenta un collegamento ipertestuale a una destinazione altrove nel documento o un'azione da eseguire.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [LinkAnnotation](#LinkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Crea una nuova annotazione Link nella pagina specificata. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accetta un oggetto visitor per elaborare l'annotazione. |
| [getAction](#getAction--) | Ottieni un'azione da eseguire quando l'annotazione link è attivata. |
| [getAnnotationType](#getAnnotationType--) | Ottiene il tipo di annotazione. |
| [getDestination](#getDestination--) | Ottieni una destinazione da visualizzare quando l'annotazione è attivata. |
| [getHighlighting](#getHighlighting--) | Ottieni l'effetto visivo da utilizzare quando il pulsante del mouse è premuto o tenuto premuto all'interno della sua area attiva. |
| [setAction](#setAction-com.aspose.pdf.PdfAction-) | Imposta un'azione da eseguire quando l'annotazione link è attivata. |
| [setDestination](#setDestination-com.aspose.pdf.IAppointment-) | Imposta una destinazione da visualizzare quando l'annotazione è attivata. |
| [setHighlighting](#setHighlighting-com.aspose.pdf.HighlightingMode-) | Imposta l'effetto visivo da utilizzare quando il pulsante del mouse è premuto o tenuto premuto all'interno della sua area attiva. |

### LinkAnnotation {#LinkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Crea una nuova annotazione Link nella pagina specificata.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accetta un oggetto visitor per elaborare l'annotazione.

### getAction {#getAction--}
```
public PdfAction getAction()
```

Ottieni un'azione da eseguire quando l'annotazione link è attivata.

**Returns:**
Valore PdfAction

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Ottiene il tipo di annotazione.

**Returns:**
Elemento AnnotationType @see AnnotationType

### getDestination {#getDestination--}
```
public IAppointment getDestination()
```

Ottieni una destinazione da visualizzare quando l'annotazione è attivata.

**Returns:**
valore IAppointment

### getHighlighting {#getHighlighting--}
```
public HighlightingMode getHighlighting()
```

Ottieni l'effetto visivo da utilizzare quando il pulsante del mouse è premuto o tenuto premuto all'interno della sua area attiva.

**Returns:**
Elemento HighlightingMode @see HighlightingMode

### setAction {#setAction-com.aspose.pdf.PdfAction-}
Imposta un'azione da eseguire quando l'annotazione link è attivata.

### setDestination {#setDestination-com.aspose.pdf.IAppointment-}
Imposta una destinazione da visualizzare quando l'annotazione è attivata.

### setHighlighting {#setHighlighting-com.aspose.pdf.HighlightingMode-}
Imposta l'effetto visivo da utilizzare quando il pulsante del mouse è premuto o tenuto premuto all'interno della sua area attiva.
