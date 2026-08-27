---
title: "PopupAnnotation"
linktitle: "PopupAnnotation"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente l'annotation pop-up qui affiche du texte dans une fenêtre pop-up pour la saisie et la modification."
type: docs
weight: 3930
url: /fr/java/com.aspose.pdf/popupannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.PopupAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.PopupAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.PopupAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class PopupAnnotation extends Annotation
```

Représente l'annotation pop-up qui affiche du texte dans une fenêtre pop-up pour la saisie et la modification.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PopupAnnotation](#PopupAnnotation-com.aspose.pdf.IDocument-) | Constructeur. pour utilisation dans le Generator. |
| [PopupAnnotation](#PopupAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Crée une nouvelle annotation Popup sur la page spécifiée. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepte un objet visiteur pour traiter l'annotation. |
| [getAnnotationType](#getAnnotationType--) | Obtient le type de l'annotation. |
| [getOpen](#getOpen--) | Obtient un indicateur spécifiant si l'annotation pop-up doit être affichée ouverte initialement. |
| [getParent](#getParent--) | Obtient l'annotation parent avec laquelle cette annotation pop-up doit être associée. Si cette entrée est présente, les entrées Contents, M, C et T de l'annotation parent remplaceront celles de l'annotation pop-up elle-même. |
| [setOpen](#setOpen-boolean-) | Définit un indicateur spécifiant si l'annotation pop-up doit être affichée ouverte initialement. |
| [setParent](#setParent-com.aspose.pdf.MarkupAnnotation-) | Définit l'annotation parent avec laquelle cette annotation pop-up doit être associée. Si cette entrée est présente, les entrées Contents, M, C et T de l'annotation parent remplaceront celles de l'annotation pop-up elle-même. |

### PopupAnnotation {#PopupAnnotation-com.aspose.pdf.IDocument-}
Constructeur. pour utilisation dans le Generator.

### PopupAnnotation {#PopupAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Crée une nouvelle annotation Popup sur la page spécifiée.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepte un objet visiteur pour traiter l'annotation.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtient le type de l'annotation.

**Returns:**
Élément AnnotationType @see AnnotationType

### getOpen {#getOpen--}
```
public boolean getOpen()
```

Obtient un indicateur spécifiant si l'annotation pop-up doit être affichée ouverte initialement.

**Returns:**
valeur booléenne

### getParent {#getParent--}
```
public Annotation getParent()
```

Obtient l'annotation parent avec laquelle cette annotation pop-up doit être associée. Si cette entrée est présente, les entrées Contents, M, C et T de l'annotation parent remplaceront celles de l'annotation pop-up elle-même.

**Returns:**
Objet MarkupAnnotation

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

Définit un indicateur spécifiant si l'annotation pop-up doit être affichée ouverte initialement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setParent {#setParent-com.aspose.pdf.MarkupAnnotation-}
Définit l'annotation parent avec laquelle cette annotation pop-up doit être associée. Si cette entrée est présente, les entrées Contents, M, C et T de l'annotation parent remplaceront celles de l'annotation pop-up elle-même.
