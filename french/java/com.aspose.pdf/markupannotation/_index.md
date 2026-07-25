---
title: "MarkupAnnotation"
linktitle: "MarkupAnnotation"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe abstraite représentant une annotation de balisage."
type: docs
weight: 2870
url: /fr/java/com.aspose.pdf/markupannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public abstract class MarkupAnnotation extends Annotation implements com.aspose.pdf.engine.ITitledAnnotation
```

Classe abstraite représentant une annotation de balisage.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MarkupAnnotation](#MarkupAnnotation--) | Constructeur |
| [MarkupAnnotation](#MarkupAnnotation-com.aspose.pdf.IDocument-) | Constructeur |

## Méthodes

| Méthode | Description |
| --- | --- |
| [clearState](#clearState--) | Efface l'état et le modèle d'état de l'annotation. Par exemple, efface le statut de révision d'une annotation. Note, l'état stocké dans une autre annotation de texte qui possède les clés state et statemodel. |
| [getCreationDate](#getCreationDate--) | Obtient la date et l'heure de création de l'annotation. |
| [getInReplyTo](#getInReplyTo--) | Une référence à l'annotation que cette annotation \"in reply to\". Les deux annotations doivent être sur la même page du document. |
| [getOpacity](#getOpacity--) | Obtient la valeur d'opacité constante à utiliser lors du rendu de l'annotation. |
| [getPopup](#getPopup--) | Annotation Pop-up pour saisir ou modifier le texte associé à cette annotation. |
| [getReplyType](#getReplyType--) | Une chaîne spécifiant la relation (le \"reply type\") entre cette annotation et celle spécifiée par InReplyTo. |
| [getRichText](#getRichText--) | Obtient une chaîne de texte enrichi à afficher dans la fenêtre pop-up lorsque l'annotation est ouverte. |
| [getRichText](#getRichText-com.aspose.pdf.engine.data.IPdfDictionary-) | Obtient une chaîne de texte enrichi à afficher dans la fenêtre pop-up lorsque l'annotation est ouverte. |
| [getState](#getState--) | Obtient l'état de l'annotation. Note, l'état stocké dans une autre annotation de texte qui possède les clés state et statemodel. |
| [getStateModel](#getStateModel--) | Obtient le modèle d'état de l'annotation. Note, l'état stocké dans une autre annotation de texte qui possède les clés state et statemodel. |
| [getSubject](#getSubject--) | Obtient le texte représentant la description de l'objet. |
| [getTitle](#getTitle--) | Obtient une étiquette texte qui doit être affichée dans la barre de titre de la fenêtre pop-up de l'annotation lorsqu'elle est ouverte et active. Cette entrée doit identifier l'utilisateur qui a ajouté l'annotation. |
| [setCreationDate](#setCreationDate-java.util.Date-) | Obtient la date et l'heure de création de l'annotation. |
| [setInReplyTo](#setInReplyTo-com.aspose.pdf.Annotation-) | Une référence à l'annotation que cette annotation \"in reply to\". Les deux annotations doivent être sur la même page du document. |
| [setMarkedState](#setMarkedState-boolean-) | Définit l'état Marqué et Non marqué pour l'annotation. Note, l'état stocké dans une autre annotation de texte qui possède les clés state et statemodel. |
| [setOpacity](#setOpacity-double-) | Définit la valeur d'opacité constante à utiliser lors du rendu de l'annotation. |
| [setPopup](#setPopup-com.aspose.pdf.PopupAnnotation-) | Annotation Pop-up pour saisir ou modifier le texte associé à cette annotation. |
| [setReplyType](#setReplyType-com.aspose.pdf.ReplyType-) | Une chaîne spécifiant la relation (le \"reply type\") entre cette annotation et celle spécifiée par InReplyTo. |
| [setReviewState](#setReviewState-com.aspose.pdf.AnnotationState-) | Définit l'état de révision pour une annotation. Les états Marqué et Non marqué sont ignorés car ils n'appartiennent pas au Review StateModel. L'état est défini par l'utilisateur qui a créé l'annotation cible. La valeur est prise à partir de la propriété Title de l'annotation cible. Note, l'état stocké dans une autre annotation de texte qui possède les clés state et statemodel. |
| [setReviewState](#setReviewState-com.aspose.pdf.AnnotationState-java.lang.String-) | Définit l'état de révision pour une annotation. Les états Marqué et Non marqué sont ignorés car ils n'appartiennent pas au Review StateModel. Note, l'état stocké dans une autre annotation de texte qui possède les clés state et statemodel. |
| [setRichText](#setRichText-java.lang.String-) | Définit une chaîne de texte enrichi à afficher dans la fenêtre pop-up lorsque l'annotation est ouverte. |
| [setSubject](#setSubject-java.lang.String-) | Définit le texte représentant la description de l'objet. |
| [setTitle](#setTitle-java.lang.String-) | Définit une étiquette texte qui doit être affichée dans la barre de titre de la fenêtre pop-up de l'annotation lorsqu'elle est ouverte et active. Cette entrée doit identifier l'utilisateur qui a ajouté l'annotation. |

### MarkupAnnotation {#MarkupAnnotation--}
```
public MarkupAnnotation()
```

Constructeur

### MarkupAnnotation {#MarkupAnnotation-com.aspose.pdf.IDocument-}
Constructeur

### clearState {#clearState--}
```
public final void clearState()
```

Efface l'état et le modèle d'état de l'annotation. Par exemple, efface le statut de révision d'une annotation. Note, l'état stocké dans une autre annotation de texte qui possède les clés state et statemodel.

### getCreationDate {#getCreationDate--}
```
public Date getCreationDate()
```

Obtient la date et l'heure de création de l'annotation.

**Returns:**
Objet Date

### getInReplyTo {#getInReplyTo--}
```
public Annotation getInReplyTo()
```

Une référence à l'annotation que cette annotation \"in reply to\". Les deux annotations doivent être sur la même page du document.

**Returns:**
Valeur de l'annotation

### getOpacity {#getOpacity--}
```
public double getOpacity()
```

Obtient la valeur d'opacité constante à utiliser lors du rendu de l'annotation.

**Returns:**
valeur double

### getPopup {#getPopup--}
```
public PopupAnnotation getPopup()
```

Annotation Pop-up pour saisir ou modifier le texte associé à cette annotation.

**Returns:**
Valeur de PopupAnnotation

### getReplyType {#getReplyType--}
```
public ReplyType getReplyType()
```

Une chaîne spécifiant la relation (le \"reply type\") entre cette annotation et celle spécifiée par InReplyTo.

**Returns:**
Valeur ReplyType @see ReplyType

### getRichText {#getRichText--}
```
public final String getRichText()
```

Obtient une chaîne de texte enrichi à afficher dans la fenêtre pop-up lorsque l'annotation est ouverte.

**Returns:**
valeur String

### getRichText {#getRichText-com.aspose.pdf.engine.data.IPdfDictionary-}
Obtient une chaîne de texte enrichi à afficher dans la fenêtre pop-up lorsque l'annotation est ouverte.

**Returns:**
valeur String

### getState {#getState--}
```
public final AnnotationState getState()
```

Obtient l'état de l'annotation. Note, l'état stocké dans une autre annotation de texte qui possède les clés state et statemodel.

**Returns:**
État de l'annotation.

### getStateModel {#getStateModel--}
```
public final AnnotationStateModel getStateModel()
```

Obtient le modèle d'état de l'annotation. Note, l'état stocké dans une autre annotation de texte qui possède les clés state et statemodel.

**Returns:**
Modèle d'état d'annotation.

### getSubject {#getSubject--}
```
public String getSubject()
```

Obtient le texte représentant la description de l'objet.

**Returns:**
valeur String

### getTitle {#getTitle--}
```
public String getTitle()
```

Obtient une étiquette texte qui doit être affichée dans la barre de titre de la fenêtre pop-up de l'annotation lorsqu'elle est ouverte et active. Cette entrée doit identifier l'utilisateur qui a ajouté l'annotation.

**Returns:**
valeur String

### setCreationDate {#setCreationDate-java.util.Date-}
Obtient la date et l'heure de création de l'annotation.

### setInReplyTo {#setInReplyTo-com.aspose.pdf.Annotation-}
Une référence à l'annotation que cette annotation \"in reply to\". Les deux annotations doivent être sur la même page du document.

### setMarkedState {#setMarkedState-boolean-}
```
public final void setMarkedState(boolean marked)
```

Définit l'état Marqué et Non marqué pour l'annotation. Note, l'état stocké dans une autre annotation de texte qui possède les clés state et statemodel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| marqué |  | Vrai si définit l'état Marqué, et faux si définit l'état Non marqué. |

### setOpacity {#setOpacity-double-}
```
public void setOpacity(double value)
```

Définit la valeur d'opacité constante à utiliser lors du rendu de l'annotation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setPopup {#setPopup-com.aspose.pdf.PopupAnnotation-}
Annotation Pop-up pour saisir ou modifier le texte associé à cette annotation.

### setReplyType {#setReplyType-com.aspose.pdf.ReplyType-}
Une chaîne spécifiant la relation (le \"reply type\") entre cette annotation et celle spécifiée par InReplyTo.

### setReviewState {#setReviewState-com.aspose.pdf.AnnotationState-}
Définit l'état de révision pour une annotation. Les états Marqué et Non marqué sont ignorés car ils n'appartiennent pas au Review StateModel. L'état est défini par l'utilisateur qui a créé l'annotation cible. La valeur est prise à partir de la propriété Title de l'annotation cible. Note, l'état stocké dans une autre annotation de texte qui possède les clés state et statemodel.

### setReviewState {#setReviewState-com.aspose.pdf.AnnotationState-java.lang.String-}
Définit l'état de révision pour une annotation. Les états Marqué et Non marqué sont ignorés car ils n'appartiennent pas au Review StateModel. Note, l'état stocké dans une autre annotation de texte qui possède les clés state et statemodel.

### setRichText {#setRichText-java.lang.String-}
Définit une chaîne de texte enrichi à afficher dans la fenêtre pop-up lorsque l'annotation est ouverte.

### setSubject {#setSubject-java.lang.String-}
Définit le texte représentant la description de l'objet.

### setTitle {#setTitle-java.lang.String-}
Définit une étiquette texte qui doit être affichée dans la barre de titre de la fenêtre pop-up de l'annotation lorsqu'elle est ouverte et active. Cette entrée doit identifier l'utilisateur qui a ajouté l'annotation.
