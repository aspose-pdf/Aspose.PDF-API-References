---
title: "WidgetAnnotation"
linktitle: "WidgetAnnotation"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant une annotation de widget."
type: docs
weight: 5540
url: /fr/java/com.aspose.pdf/widgetannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class WidgetAnnotation extends Annotation
```

Classe représentant une annotation de widget.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [WidgetAnnotation](#WidgetAnnotation-com.aspose.pdf.IDocument-) | Créer une annotation (used for Generator) |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepte le visiteur. |
| [getAnnotationActions](#getAnnotationActions--) | Obtient les actions de l'annotation. |
| [getAnnotationType](#getAnnotationType--) | Obtient le type de l'annotation. |
| [getCheckedStateName](#getCheckedStateName--) | Renvoie le nom de l'état "checked" selon les noms d'états existants. |
| [getDefaultAppearance](#getDefaultAppearance--) | Obtient l'apparence par défaut du champ. |
| [getExportable](#getExportable--) | Obtient le drapeau exportable du champ. |
| [getHighlighting](#getHighlighting--) | Mode de surlignage de l'annotation. |
| [getOnActivated](#getOnActivated--) | Obtenez une action qui doit être exécutée lorsque l'annotation est activée. |
| [getParent](#getParent--) | Obtient le parent de l'annotation. |
| [getReadOnly](#getReadOnly--) | Obtient le statut en lecture seule du champ. |
| [getRequired](#getRequired--) | Obtient le statut requis du champ. |
| [setDefaultAppearance](#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-) | Définit l'apparence par défaut du champ. |
| [setExportable](#setExportable-boolean-) | Définit le statut en lecture seule du champ. |
| [setHighlighting](#setHighlighting-com.aspose.pdf.HighlightingMode-) | Mode de surlignage de l'annotation. |
| [setOnActivated](#setOnActivated-com.aspose.pdf.PdfAction-) | Définissez une action qui doit être exécutée lorsque l'annotation est activée. |
| [setReadOnly](#setReadOnly-boolean-) | Définit le statut en lecture seule du champ. |
| [setRequired](#setRequired-boolean-) | Définit le statut en lecture seule du champ. |

### WidgetAnnotation {#WidgetAnnotation-com.aspose.pdf.IDocument-}
Créer une annotation (used for Generator)

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepte le visiteur.

### getAnnotationActions {#getAnnotationActions--}
```
public AnnotationActionCollection getAnnotationActions()
```

Obtient les actions de l'annotation.

**Returns:**
Objet AnnotationActionCollection

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Obtient le type de l'annotation.

**Returns:**
Élément AnnotationType @see AnnotationType

### getCheckedStateName {#getCheckedStateName--}
```
public final String getCheckedStateName()
```

Renvoie le nom de l'état "checked" selon les noms d'états existants.

**Returns:**
Le nom de l'état "checked" pour cette annotation.

### getDefaultAppearance {#getDefaultAppearance--}
```
public DefaultAppearance getDefaultAppearance()
```

Obtient l'apparence par défaut du champ.

**Returns:**
objet DefaultAppearance

### getExportable {#getExportable--}
```
public boolean getExportable()
```

Obtient le drapeau exportable du champ.

**Returns:**
valeur booléenne

### getHighlighting {#getHighlighting--}
```
public HighlightingMode getHighlighting()
```

Mode de surlignage de l'annotation.

**Returns:**
Valeur HighlightingMode @see HighlightingMode

### getOnActivated {#getOnActivated--}
```
public PdfAction getOnActivated()
```

Obtenez une action qui doit être exécutée lorsque l'annotation est activée.

**Returns:**
objet PdfAction

### getParent {#getParent--}
```
public Field getParent()
```

Obtient le parent de l'annotation.

**Returns:**
Objet Field

### getReadOnly {#getReadOnly--}
```
public boolean getReadOnly()
```

Obtient le statut en lecture seule du champ.

**Returns:**
valeur booléenne

### getRequired {#getRequired--}
```
public boolean getRequired()
```

Obtient le statut requis du champ.

**Returns:**
valeur booléenne

### setDefaultAppearance {#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-}
Définit l'apparence par défaut du champ.

### setExportable {#setExportable-boolean-}
```
public void setExportable(boolean value)
```

Définit le statut en lecture seule du champ.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setHighlighting {#setHighlighting-com.aspose.pdf.HighlightingMode-}
Mode de surlignage de l'annotation.

### setOnActivated {#setOnActivated-com.aspose.pdf.PdfAction-}
Définissez une action qui doit être exécutée lorsque l'annotation est activée.

### setReadOnly {#setReadOnly-boolean-}
```
public void setReadOnly(boolean value)
```

Définit le statut en lecture seule du champ.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setRequired {#setRequired-boolean-}
```
public void setRequired(boolean value)
```

Définit le statut en lecture seule du champ.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |
