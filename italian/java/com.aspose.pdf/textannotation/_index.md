---
title: "TextAnnotation"
linktitle: "TextAnnotation"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta un'annotazione di testo che è una \\\"nota adesiva\\\" collegata a un punto nel documento PDF."
type: docs
weight: 4920
url: /it/java/com.aspose.pdf/textannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.TextAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.TextAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class TextAnnotation extends MarkupAnnotation
```

Rappresenta un'annotazione di testo che è una \"nota adesiva\" allegata a un punto nel documento PDF.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TextAnnotation](#TextAnnotation--) | Crea un'istanza di TextAnnotation |
| [TextAnnotation](#TextAnnotation-com.aspose.pdf.IDocument-) | Crea un'istanza di TextAnnotation |
| [TextAnnotation](#TextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Crea un'istanza di TextAnnotation |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accetta un oggetto visitor per elaborare l'annotazione. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Sovrascrive la definizione nella classe base con un corpo vuoto. |
| [getAnnotationType](#getAnnotationType--) | Ottiene il tipo di annotazione. |
| [getIcon](#getIcon--) | Ottiene un'icona da utilizzare nella visualizzazione dell'annotazione. |
| [getOpen](#getOpen--) | Ottiene un flag che specifica se l'annotazione deve essere visualizzata aperta inizialmente. |
| [setIcon](#setIcon-int-) | Imposta un'icona da utilizzare nella visualizzazione dell'annotazione. |
| [setOpen](#setOpen-boolean-) | Imposta un flag che specifica se l'annotazione deve essere visualizzata aperta inizialmente. |

### TextAnnotation {#TextAnnotation--}
```
public TextAnnotation()
```

Crea un'istanza di TextAnnotation

### TextAnnotation {#TextAnnotation-com.aspose.pdf.IDocument-}
Crea un'istanza di TextAnnotation

### TextAnnotation {#TextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Crea un'istanza di TextAnnotation

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accetta un oggetto visitor per elaborare l'annotazione.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Sovrascrive la definizione nella classe base con un corpo vuoto.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Ottiene il tipo di annotazione.

**Returns:**
Valore AnnotationType @see AnnotationState

### getIcon {#getIcon--}
```
public int getIcon()
```

Ottiene un'icona da utilizzare nella visualizzazione dell'annotazione.

**Returns:**
Valore TextIcon @see TextIcon

### getOpen {#getOpen--}
```
public boolean getOpen()
```

Ottiene un flag che specifica se l'annotazione deve essere visualizzata aperta inizialmente.

**Returns:**
valore booleano

### setIcon {#setIcon-int-}
```
public void setIcon(int value)
```

Imposta un'icona da utilizzare nella visualizzazione dell'annotazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Valore TextIcon @see TextIcon |

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

Imposta un flag che specifica se l'annotazione deve essere visualizzata aperta inizialmente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |
