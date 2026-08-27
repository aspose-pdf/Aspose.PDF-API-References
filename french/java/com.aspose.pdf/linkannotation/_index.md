---
title: "LinkAnnotation"
linktitle: "LinkAnnotation"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente soit un lien hypertexte vers une destination ailleurs dans le document, soit une action à exécuter."
type: docs
weight: 2760
url: /fr/java/com.aspose.pdf/linkannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.LinkAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.LinkAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.LinkAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class LinkAnnotation extends Annotation
```

Représente soit un lien hypertexte vers une destination ailleurs dans le document, soit une action à exécuter.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [LinkAnnotation](#LinkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Crée une nouvelle annotation Link sur la page spécifiée. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepte un objet visiteur pour traiter l'annotation. |
| [getAction](#getAction--) | Obtient une action à exécuter lorsque l'annotation de lien est activée. |
| [getAnnotationType](#getAnnotationType--) | Obtient le type de l'annotation. |
| [getDestination](#getDestination--) | Obtient une destination à afficher lorsque l'annotation est activée. |
| [getHighlighting](#getHighlighting--) | Obtient l'effet visuel à utiliser lorsque le bouton de la souris est pressé ou maintenu enfoncé à l'intérieur de sa zone active. |
| [setAction](#setAction-com.aspose.pdf.PdfAction-) | Définit une action à exécuter lorsque l'annotation de lien est activée. |
| [setDestination](#setDestination-com.aspose.pdf.IAppointment-) | Définit une destination à afficher lorsque l'annotation est activée. |
| [setHighlighting](#setHighlighting-com.aspose.pdf.HighlightingMode-) | Définit l'effet visuel à utiliser lorsque le bouton de la souris est pressé ou maintenu enfoncé à l'intérieur de sa zone active. |

### LinkAnnotation {#LinkAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Crée une nouvelle annotation Link sur la page spécifiée.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepte un objet visiteur pour traiter l'annotation.

### getAction {#getAction--}
```
public PdfAction getAction()
```

Obtient une action à exécuter lorsque l'annotation de lien est activée.

**Returns:**
Valeur PdfAction

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtient le type de l'annotation.

**Returns:**
Élément AnnotationType @see AnnotationType

### getDestination {#getDestination--}
```
public IAppointment getDestination()
```

Obtient une destination à afficher lorsque l'annotation est activée.

**Returns:**
Valeur IAppointment

### getHighlighting {#getHighlighting--}
```
public HighlightingMode getHighlighting()
```

Obtient l'effet visuel à utiliser lorsque le bouton de la souris est pressé ou maintenu enfoncé à l'intérieur de sa zone active.

**Returns:**
élément HighlightingMode @see HighlightingMode

### setAction {#setAction-com.aspose.pdf.PdfAction-}
Définit une action à exécuter lorsque l'annotation de lien est activée.

### setDestination {#setDestination-com.aspose.pdf.IAppointment-}
Définit une destination à afficher lorsque l'annotation est activée.

### setHighlighting {#setHighlighting-com.aspose.pdf.HighlightingMode-}
Définit l'effet visuel à utiliser lorsque le bouton de la souris est pressé ou maintenu enfoncé à l'intérieur de sa zone active.
