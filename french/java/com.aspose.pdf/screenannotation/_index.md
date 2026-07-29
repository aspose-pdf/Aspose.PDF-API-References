---
title: "ScreenAnnotation"
linktitle: "ScreenAnnotation"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Une annotation d'écran qui spécifie une région d'une page sur laquelle des clips multimédias peuvent être lus."
type: docs
weight: 4470
url: /fr/java/com.aspose.pdf/screenannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.ScreenAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.ScreenAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.ScreenAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class ScreenAnnotation extends Annotation implements com.aspose.pdf.engine.ITitledAnnotation
```

Une annotation d'écran qui spécifie une région d'une page sur laquelle des clips multimédias peuvent être lus.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ScreenAnnotation](#ScreenAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-) | Crée une nouvelle annotation Screen sur la page spécifiée. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Représente la méthode accept |
| [getAction](#getAction--) | Obtient une action à exécuter lorsque l'annotation est activée. |
| [getAnnotationType](#getAnnotationType--) | Obtient le type de l'annotation. |
| [getTitle](#getTitle--) | Obtient le titre de l'annotation screen. |
| [setAction](#setAction-com.aspose.pdf.PdfAction-) | Définit une action à exécuter lorsque l'annotation est activée. |
| [setTitle](#setTitle-java.lang.String-) | Définit le titre de l'annotation screen. |

### ScreenAnnotation {#ScreenAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-java.lang.String-}
Crée une nouvelle annotation Screen sur la page spécifiée.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Représente la méthode accept

### getAction {#getAction--}
```
public PdfAction getAction()
```

Obtient une action à exécuter lorsque l'annotation est activée.

**Returns:**
objet PdfAction

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtient le type de l'annotation.

**Returns:**
Élément AnnotationType @see AnnotationType

### getTitle {#getTitle--}
```
public String getTitle()
```

Obtient le titre de l'annotation screen.

**Returns:**
valeur String

### setAction {#setAction-com.aspose.pdf.PdfAction-}
Définit une action à exécuter lorsque l'annotation est activée.

### setTitle {#setTitle-java.lang.String-}
Définit le titre de l'annotation screen.
