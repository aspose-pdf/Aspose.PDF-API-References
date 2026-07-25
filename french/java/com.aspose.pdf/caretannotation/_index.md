---
title: "CaretAnnotation"
linktitle: "CaretAnnotation"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant l'annotation de caret."
type: docs
weight: 470
url: /fr/java/com.aspose.pdf/caretannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.CaretAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.CaretAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.CaretAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.CaretAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class CaretAnnotation extends MarkupAnnotation
```

Classe représentant l'annotation de caret.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [CaretAnnotation](#CaretAnnotation-com.aspose.pdf.IDocument-) | Constructeur pour l'utilisation dans Generator. |
| [CaretAnnotation](#CaretAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Crée une nouvelle annotation Caret sur la page spécifiée. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepte un objet visiteur pour traiter l'annotation. |
| [getAnnotationType](#getAnnotationType--) | Obtient le type de l'annotation. |
| [getFrame](#getFrame--) | Obtient le rectangle du caret. |
| [getSymbol](#getSymbol--) | Obtient le symbole associé au caret. {@code CaretSymbol} |
| [setFrame](#setFrame-com.aspose.pdf.Rectangle-) | Définit le rectangle du caret. |
| [setSymbol](#setSymbol-com.aspose.pdf.CaretSymbol-) | Définit la taille de la page de sortie pour l'importation. |

### CaretAnnotation {#CaretAnnotation-com.aspose.pdf.IDocument-}
Constructeur pour l'utilisation dans Generator.

### CaretAnnotation {#CaretAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Crée une nouvelle annotation Caret sur la page spécifiée.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepte un objet visiteur pour traiter l'annotation.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtient le type de l'annotation.

**Returns:**
Élément AnnotationType

### getFrame {#getFrame--}
```
public Rectangle getFrame()
```

Obtient le rectangle du caret.

**Returns:**
rectangle du caret.

### getSymbol {#getSymbol--}
```
public CaretSymbol getSymbol()
```

Obtient le symbole associé au caret. {@code CaretSymbol}

**Returns:**
Élément CaretSymbol @see CaretSymbol

### setFrame {#setFrame-com.aspose.pdf.Rectangle-}
Définit le rectangle du caret.

### setSymbol {#setSymbol-com.aspose.pdf.CaretSymbol-}
Définit la taille de la page de sortie pour l'importation.
