---
title: "CaretAnnotation"
linktitle: "CaretAnnotation"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta l'annotazione Caret."
type: docs
weight: 470
url: /it/java/com.aspose.pdf/caretannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.CaretAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.CaretAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.CaretAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.CaretAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class CaretAnnotation extends MarkupAnnotation
```

Classe che rappresenta l'annotazione Caret.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [CaretAnnotation](#CaretAnnotation-com.aspose.pdf.IDocument-) | Costruttore per l'uso in Generator. |
| [CaretAnnotation](#CaretAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Crea una nuova annotazione Caret nella pagina specificata. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accetta un oggetto visitor per elaborare l'annotazione. |
| [getAnnotationType](#getAnnotationType--) | Ottiene il tipo di annotazione. |
| [getFrame](#getFrame--) | Ottiene il rettangolo del cursore. |
| [getSymbol](#getSymbol--) | Ottiene il simbolo associato al cursore. {@code CaretSymbol} |
| [setFrame](#setFrame-com.aspose.pdf.Rectangle-) | Imposta il rettangolo del cursore. |
| [setSymbol](#setSymbol-com.aspose.pdf.CaretSymbol-) | Imposta la dimensione della pagina di output per l'importazione. |

### CaretAnnotation {#CaretAnnotation-com.aspose.pdf.IDocument-}
Costruttore per l'uso in Generator.

### CaretAnnotation {#CaretAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Crea una nuova annotazione Caret nella pagina specificata.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accetta un oggetto visitor per elaborare l'annotazione.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Ottiene il tipo di annotazione.

**Returns:**
AnnotationType elemento

### getFrame {#getFrame--}
```
public Rectangle getFrame()
```

Ottiene il rettangolo del cursore.

**Returns:**
rettangolo del cursore.

### getSymbol {#getSymbol--}
```
public CaretSymbol getSymbol()
```

Ottiene il simbolo associato al cursore. {@code CaretSymbol}

**Returns:**
CaretSymbol elemento @see CaretSymbol

### setFrame {#setFrame-com.aspose.pdf.Rectangle-}
Imposta il rettangolo del cursore.

### setSymbol {#setSymbol-com.aspose.pdf.CaretSymbol-}
Imposta la dimensione della pagina di output per l'importazione.
