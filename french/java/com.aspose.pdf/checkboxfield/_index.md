---
title: "CheckboxField"
linktitle: "CheckboxField"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant le champ case à cocher."
type: docs
weight: 580
url: /fr/java/com.aspose.pdf/checkboxfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.CheckboxField, com.aspose.pdf.Field, com.aspose.pdf.CheckboxField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class CheckboxField extends Field
```

Classe représentant le champ case à cocher.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [CheckboxField](#CheckboxField--) | Créer une instance de CheckboxField. @deprecated Pour une fonctionnalité complète du champ, une liaison au document est requise - utilisez CheckboxField(Document doc) |
| [CheckboxField](#CheckboxField-com.aspose.pdf.IDocument-) | Créer une instance de CheckboxField. @deprecated Pour une fonctionnalité complète du champ, une liaison au document est requise - utilisez CheckboxField(Document doc) |
| [CheckboxField](#CheckboxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Créer une instance de CheckboxField. @deprecated Pour une fonctionnalité complète du champ, une liaison au document est requise - utilisez CheckboxField(Document doc) |
| [CheckboxField](#CheckboxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Créer une instance de CheckboxField. @deprecated Pour une fonctionnalité complète du champ, une liaison au document est requise - utilisez CheckboxField(Document doc) |

## Méthodes

| Méthode | Description |
| --- | --- |
| [addOption](#addOption-java.lang.String-) | Ajoute une nouvelle case à cocher dans un groupe de cases à cocher, dans lequel au maximum une case peut être cochée à la fois. La nouvelle case à cocher est ajoutée au bas du groupe. |
| [addOption](#addOption-java.lang.String-int-com.aspose.pdf.Rectangle-) | Ajoute une nouvelle case à cocher dans un groupe de cases à cocher, dans lequel au maximum une case peut être cochée à la fois. |
| [addOption](#addOption-java.lang.String-com.aspose.pdf.Rectangle-) | Ajoute une nouvelle case à cocher dans un groupe de cases à cocher, dans lequel au maximum une case peut être cochée à la fois. |
| [deepClone](#deepClone--) | Cloner la case à cocher. |
| [getActiveState](#getActiveState--) | Obtient l'état d'apparence actuel de l'annotation. |
| [getAllowedStates](#getAllowedStates--) | Renvoie la liste des états autorisés. |
| [getChecked](#getChecked--) | Obtient l'état de la case à cocher. |
| [getExportValue](#getExportValue--) | Obtient ou définit la valeur d'exportation du champ CheckBox. |
| [getNormalCaption](#getNormalCaption--) | Obtient la légende normale du champ. |
| [getOnState](#getOnState--) | Renvoie le nom de l'état qui est l'état \"Checked\" de la case à cocher. C'est \"Yes\" s'il est présent ou toute autre valeur autre que \"Off\" et \"No\"; |
| [getStyle](#getStyle--) | Obtient le style de la case à cocher. |
| [getValue](#getValue--) | Obtient la valeur du champ de case à cocher. |
| [setActiveState](#setActiveState-java.lang.String-) | Définit l'état actuel de l'apparence de l'annotation. |
| [setChecked](#setChecked-boolean-) | Définit l'état de la case à cocher. |
| [setExportValue](#setExportValue-java.lang.String-) | Obtient ou définit la valeur d'exportation du champ CheckBox. |
| [setStyle](#setStyle-com.aspose.pdf.BoxStyle-) | Définit le style de la case à cocher. |
| [setValue](#setValue-java.lang.String-) | Définit la valeur du champ de case à cocher. |

### CheckboxField {#CheckboxField--}
```
@Deprecated public CheckboxField()
```

Créer une instance de CheckboxField. @deprecated Pour une fonctionnalité complète du champ, une liaison au document est requise - utilisez CheckboxField(Document doc)

### CheckboxField {#CheckboxField-com.aspose.pdf.IDocument-}
Créer une instance de CheckboxField. @deprecated Pour une fonctionnalité complète du champ, une liaison au document est requise - utilisez CheckboxField(Document doc)

### CheckboxField {#CheckboxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Créer une instance de CheckboxField. @deprecated Pour une fonctionnalité complète du champ, une liaison au document est requise - utilisez CheckboxField(Document doc)

### CheckboxField {#CheckboxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Créer une instance de CheckboxField. @deprecated Pour une fonctionnalité complète du champ, une liaison au document est requise - utilisez CheckboxField(Document doc)

### addOption {#addOption-java.lang.String-}
Ajoute une nouvelle case à cocher dans un groupe de cases à cocher, dans lequel au maximum une case peut être cochée à la fois. La nouvelle case à cocher est ajoutée au bas du groupe.

### addOption {#addOption-java.lang.String-int-com.aspose.pdf.Rectangle-}
Ajoute une nouvelle case à cocher dans un groupe de cases à cocher, dans lequel au maximum une case peut être cochée à la fois.

### addOption {#addOption-java.lang.String-com.aspose.pdf.Rectangle-}
Ajoute une nouvelle case à cocher dans un groupe de cases à cocher, dans lequel au maximum une case peut être cochée à la fois.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Cloner la case à cocher.

**Returns:**
L'objet cloné

### getActiveState {#getActiveState--}
```
public String getActiveState()
```

Obtient l'état d'apparence actuel de l'annotation.

**Returns:**
valeur String

### getAllowedStates {#getAllowedStates--}
```
public List < String > getAllowedStates()
```

Renvoie la liste des états autorisés.

**Returns:**
liste de valeurs String

### getChecked {#getChecked--}
```
public boolean getChecked()
```

Obtient l'état de la case à cocher.

**Returns:**
valeur booléenne

### getExportValue {#getExportValue--}
```
public final String getExportValue()
```

Obtient ou définit la valeur d'exportation du champ CheckBox.

**Returns:**
valeur String

### getNormalCaption {#getNormalCaption--}
```
public String getNormalCaption()
```

Obtient la légende normale du champ.

**Returns:**
valeur String

### getOnState {#getOnState--}
```
public String getOnState()
```

Renvoie le nom de l'état qui est l'état \"Checked\" de la case à cocher. C'est \"Yes\" s'il est présent ou toute autre valeur autre que \"Off\" et \"No\";

**Returns:**
valeur String

### getStyle {#getStyle--}
```
public BoxStyle getStyle()
```

Obtient le style de la case à cocher.

**Returns:**
style de la case à cocher. @see BoxStyle

### getValue {#getValue--}
```
public String getValue()
```

Obtient la valeur du champ de case à cocher.

**Returns:**
valeur String

### setActiveState {#setActiveState-java.lang.String-}
Définit l'état actuel de l'apparence de l'annotation.

### setChecked {#setChecked-boolean-}
```
public void setChecked(boolean value)
```

Définit l'état de la case à cocher.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setExportValue {#setExportValue-java.lang.String-}
Obtient ou définit la valeur d'exportation du champ CheckBox.

### setStyle {#setStyle-com.aspose.pdf.BoxStyle-}
Définit le style de la case à cocher.

### setValue {#setValue-java.lang.String-}
Définit la valeur du champ de case à cocher.
