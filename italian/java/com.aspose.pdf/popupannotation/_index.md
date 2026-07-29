---
title: "PopupAnnotation"
linktitle: "PopupAnnotation"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta l'annotazione pop-up che visualizza il testo in una finestra pop-up per l'inserimento e la modifica."
type: docs
weight: 3930
url: /it/java/com.aspose.pdf/popupannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.PopupAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.PopupAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.PopupAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class PopupAnnotation extends Annotation
```

Rappresenta l'annotazione pop-up che visualizza il testo in una finestra pop-up per l'inserimento e la modifica.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PopupAnnotation](#PopupAnnotation-com.aspose.pdf.IDocument-) | Costruttore. per l'uso in Generator. |
| [PopupAnnotation](#PopupAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Crea una nuova annotazione Popup nella pagina specificata. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accetta un oggetto visitor per elaborare l'annotazione. |
| [getAnnotationType](#getAnnotationType--) | Ottiene il tipo di annotazione. |
| [getOpen](#getOpen--) | Restituisce un flag che specifica se l'annotazione pop-up dovrebbe essere visualizzata aperta inizialmente. |
| [getParent](#getParent--) | Restituisce l'annotazione padre con cui questa annotazione pop-up deve essere associata. Se questa voce è presente, le voci Contents, M, C e T dell'annotazione padre sovrascriveranno quelle dell'annotazione pop-up stessa. |
| [setOpen](#setOpen-boolean-) | Imposta un flag che specifica se l'annotazione pop-up dovrebbe essere visualizzata aperta inizialmente. |
| [setParent](#setParent-com.aspose.pdf.MarkupAnnotation-) | Imposta l'annotazione padre con cui questa annotazione pop-up deve essere associata. Se questa voce è presente, le voci Contents, M, C e T dell'annotazione padre sovrascriveranno quelle dell'annotazione pop-up stessa. |

### PopupAnnotation {#PopupAnnotation-com.aspose.pdf.IDocument-}
Costruttore. per l'uso in Generator.

### PopupAnnotation {#PopupAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Crea una nuova annotazione Popup nella pagina specificata.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accetta un oggetto visitor per elaborare l'annotazione.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Ottiene il tipo di annotazione.

**Returns:**
Elemento AnnotationType @see AnnotationType

### getOpen {#getOpen--}
```
public boolean getOpen()
```

Restituisce un flag che specifica se l'annotazione pop-up dovrebbe essere visualizzata aperta inizialmente.

**Returns:**
valore booleano

### getParent {#getParent--}
```
public Annotation getParent()
```

Restituisce l'annotazione padre con cui questa annotazione pop-up deve essere associata. Se questa voce è presente, le voci Contents, M, C e T dell'annotazione padre sovrascriveranno quelle dell'annotazione pop-up stessa.

**Returns:**
Oggetto MarkupAnnotation

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

Imposta un flag che specifica se l'annotazione pop-up dovrebbe essere visualizzata aperta inizialmente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setParent {#setParent-com.aspose.pdf.MarkupAnnotation-}
Imposta l'annotazione padre con cui questa annotazione pop-up deve essere associata. Se questa voce è presente, le voci Contents, M, C e T dell'annotazione padre sovrascriveranno quelle dell'annotazione pop-up stessa.
