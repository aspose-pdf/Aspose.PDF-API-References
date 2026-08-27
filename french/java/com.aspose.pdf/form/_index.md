---
title: "Formulaire"
linktitle: "Formulaire"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant l'objet formulaire."
type: docs
weight: 1740
url: /fr/java/com.aspose.pdf/form/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Form

**All Implemented Interfaces:**
Iterable < WidgetAnnotation >

```
public final class Form extends Object implements Iterable < WidgetAnnotation >
```

Classe représentant l'objet formulaire.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Form](#Form-com.aspose.pdf.IDocument-) | Constructeur |

## Méthodes

| Méthode | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.Field-) | Ajoute un champ au formulaire. |
| [add](#add-com.aspose.pdf.Field-int-) | Ajoute un champ au formulaire. |
| [add](#add-com.aspose.pdf.Field-java.lang.String-int-) | Ajoute un nouveau champ au formulaire ; si ce champ est déjà placé sur un autre ou sur ce formulaire, une copie du champ est créée. |
| [add](#add-com.aspose.pdf.WidgetAnnotation-) | Ajoute un champ au formulaire. |
| [addFieldAppearance](#addFieldAppearance-com.aspose.pdf.Field-int-com.aspose.pdf.Rectangle-) | Ajoute une apparence supplémentaire du champ à la page spécifiée du document à l'emplacement indiqué. |
| [addFieldToAcroForm](#addFieldToAcroForm-com.aspose.pdf.Field-) | Ajoute une apparence supplémentaire du champ à la page spécifiée du document. |
| [assignXfa](#assignXfa-com.aspose.ms.System.Xml.XmlDocument-) | Définit le XFA du formulaire à la valeur spécifiée. |
| [clear](#clear--) | Supprime tous les champs du formulaire. Non pris en charge. |
| [contains](#contains-com.aspose.pdf.WidgetAnnotation-) | Détermine si le champ est présent sur le formulaire.. |
| [copyTo](#copyTo-com.aspose.pdf.Field:A-int-) | Copie les champs placés sur le formulaire dans un tableau. |
| [copyTo](#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-) | Copie les champs du formulaire dans un tableau. |
| [delete](#delete-com.aspose.pdf.Field-) | Supprime le champ du formulaire. |
| [delete](#delete-java.lang.String-) | Supprime le champ du formulaire par son nom. |
| [flatten](#flatten--) | Supprime tous les champs de formulaire statiques et place leurs valeurs directement sur la page. |
| [get_Item](#get_Item-int-) | Obtient le champ du formulaire par indice de champ. |
| [get_Item](#get_Item-java.lang.String-) | Obtient le champ du formulaire par nom de champ. Lance une exception si le champ n'a pas été trouvé. |
| [get_xfa](#get_xfa--) | À usage interne uniquement |
| [get](#get-int-) |  |
| [get](#get-java.lang.String-) | Recherche le champ par nom de champ. Retourne null si le champ n'a pas été trouvé. |
| [getAutoRecalculate](#getAutoRecalculate--) | Si défini, tous les champs du formulaire seront recalculés lorsqu'un champ est modifié. La valeur par défaut est true. Définissez à false afin d'augmenter les performances lors du remplissage du formulaire avec un grand nombre de champs calculés. |
| [getAutoRestoreForm](#getAutoRestoreForm--) | Si défini, les champs de formulaire absents seront automatiquement créés s'ils sont présents dans les annotations. |
| [getDefaultAppearance](#getDefaultAppearance--) | Obtient l'apparence par défaut du formulaire (objet qui décrit la police, la taille du texte et la couleur par défaut pour les champs du formulaire). |
| [getDefaultResources](#getDefaultResources--) | Obtient les ressources par défaut placées sur ce formulaire. |
| [getDocument](#getDocument--) | À usage interne uniquement |
| [getEmulateRequierdGroups](#getEmulateRequierdGroups--) | Si cette propriété est vraie, des rectangles rouges supplémentaires seront dessinés autour des conteneurs d'éléments requis Xfa exclGroup. Cette propriété a été introduite en raison de l'absence d'analogies pour le exclGroup lors de la conversion de la représentation Xfa des formulaires vers le standard. Elle est fausse par défaut. |
| [getFields](#getFields--) | Obtient la liste de tous les champs au niveau le plus bas du formulaire hiérarchique. |
| [getFieldsInRect](#getFieldsInRect-com.aspose.pdf.Rectangle-) | Renvoie les champs à l'intérieur du rectangle spécifié. |
| [getIgnoreNeedsRendering](#getIgnoreNeedsRendering--) | Si cette propriété est vraie, la valeur de la clé NeedsRendering sera ignorée lors de la conversion du formulaire XFA vers le formulaire Standard. Elle est fausse par défaut. |
| [getNeedsRendering](#getNeedsRendering--) | Obtient une valeur indiquant si le document nécessite la suppression du formulaire XFA dynamique. Cette propriété a été introduite pour déterminer si {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) doit être utilisé pour supprimer le formulaire XFA dans les cas où le formulaire XFA est présent et {@code NeedsRendering}({@link #getNeedsRendering}) est faux. |
| [getRemovePermission](#getRemovePermission--) | Si cette propriété est vraie, le dictionnaire \"Perms\" sera supprimé du document PDF après la conversion des documents dynamiques vers le standard. Le dictionnaire \"Perms\" peut contenir des règles qui perturbent l'affichage et la sélection des champs obligatoires dans le lecteur Adobe Acrobat. Elle est fausse par défaut. |
| [getSignaturesAppendOnly](#getSignaturesAppendOnly--) | Si défini, le document contient des signatures qui peuvent être invalidées si le fichier est enregistré (écrit) d'une manière qui modifie son contenu précédent, contrairement à une mise à jour incrémentielle. |
| [getSignaturesExist](#getSignaturesExist--) | Si défini, le document contient au moins un champ de signature. |
| [getSignDependentElementsRenderingModeWhenConverted](#getSignDependentElementsRenderingModeWhenConverted--) | Les formulaires peuvent contenir des informations de signature, c'est‑à‑dire qu'ils peuvent être signés ou non signés. Et la vue du formulaire doit parfois dépendre du fait que le formulaire soit signé ou non. Cette propriété indique au convertisseur de formulaire (par ex. lors de la conversion d'un formulaire XFA vers le formulaire Standard) si le formulaire résultant doit être rendu comme signé ou comme non signé. |
| [getSyncRoot](#getSyncRoot--) | Renvoie l'objet de synchronisation. |
| [getType](#getType--) | Obtient le type du formulaire. Les valeurs possibles sont : Standard, Static, Dynamic. |
| [getXFA](#getXFA--) | Obtient les données XFA du formulaire (si présentes). |
| [hasField](#hasField-com.aspose.pdf.Field-) | Vérifie si le formulaire possède déjà le champ spécifié. |
| [hasField](#hasField-java.lang.String-) | Détermine si le champ portant le nom spécifié a déjà été ajouté au formulaire. |
| [hasField](#hasField-java.lang.String-boolean-) | Détermine si le champ portant le nom spécifié a déjà été ajouté au formulaire, avec la possibilité d'examiner la hiérarchie des champs enfants. |
| [hasXfa](#hasXfa--) | Obtient une valeur indiquant si le document contient un formulaire XFA. Cette propriété a été introduite pour déterminer si {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) doit être utilisé pour supprimer le formulaire XFA dans les cas où le formulaire XFA est présent et {@code NeedsRendering}({@link #getNeedsRendering}) est faux. |
| [isReadOnly](#isReadOnly--) | Détermine si la collection est en lecture seule. Retourne toujours false. |
| [isSynchronized](#isSynchronized--) | Renvoie true si l'objet est thread‑safe. |
| [iterator](#iterator--) | Obtient l'énumération des champs du formulaire. |
| [makeFormAnnotationsIndependent](#makeFormAnnotationsIndependent-com.aspose.pdf.Page-) | / * / * Exporte les champs du formulaire PDF au format JSON et écrit le résultat dans le flux fourni. / * / * Document document = new Document("PdfDoc.pdf"); / * FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write); / * document.Form.ExportFormFieldsToJson(fs); / * fs.Close(); / * |
| [remove](#remove-com.aspose.pdf.WidgetAnnotation-) | Supprime le champ du formulaire. |
| [removeFieldAppearance](#removeFieldAppearance-com.aspose.pdf.Field-int-) | Supprime l'apparence du champ à l'index spécifié. S'il ne reste qu'une seule apparence enfant, la méthode l'intègre au champ. |
| [setAutoRecalculate](#setAutoRecalculate-boolean-) | Si défini, tous les champs du formulaire seront recalculés lorsqu'un champ est modifié. La valeur par défaut est true. Définissez à false afin d'augmenter les performances lors du remplissage du formulaire avec un grand nombre de champs calculés. |
| [setAutoRestoreForm](#setAutoRestoreForm-boolean-) | Si défini, les champs de formulaire absents seront automatiquement créés s'ils sont présents dans les annotations. |
| [setCalculatedFields](#setCalculatedFields-java.util.List-) | Permet de définir l'ordre de calcul des champs. |
| [setDefaultAppearance](#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-) | Définit l'apparence par défaut du formulaire (objet qui décrit la police, la taille du texte et la couleur par défaut pour les champs du formulaire). |
| [setEmulateRequierdGroups](#setEmulateRequierdGroups-boolean-) | Si cette propriété est vraie, des rectangles rouges supplémentaires seront dessinés autour des conteneurs d'éléments requis Xfa exclGroup. Cette propriété a été introduite en raison de l'absence d'analogies pour le exclGroup lors de la conversion de la représentation Xfa des formulaires vers le standard. Elle est fausse par défaut. |
| [setIgnoreNeedsRendering](#setIgnoreNeedsRendering-boolean-) | Si cette propriété est vraie, la valeur de la clé NeedsRendering sera ignorée lors de la conversion du formulaire XFA vers le formulaire Standard. Elle est fausse par défaut. |
| [setRemovePermission](#setRemovePermission-boolean-) | Si cette propriété est vraie, le dictionnaire \"Perms\" sera supprimé du document PDF après la conversion des documents dynamiques vers le standard. Le dictionnaire \"Perms\" peut contenir des règles qui perturbent l'affichage et la sélection des champs obligatoires dans le lecteur Adobe Acrobat. Elle est fausse par défaut. |
| [setSignaturesAppendOnly](#setSignaturesAppendOnly-boolean-) | Si défini, le document contient des signatures qui peuvent être invalidées si le fichier est enregistré (écrit) d'une manière qui modifie son contenu précédent, contrairement à une mise à jour incrémentielle. |
| [setSignaturesExist](#setSignaturesExist-boolean-) | Si défini, le document contient au moins un champ de signature. |
| [setSignDependentElementsRenderingModeWhenConverted](#setSignDependentElementsRenderingModeWhenConverted-int-) | Les formulaires peuvent contenir des informations de signature, c'est‑à‑dire qu'ils peuvent être signés ou non signés. Et la vue du formulaire doit parfois dépendre du fait que le formulaire soit signé ou non. Cette propriété indique au convertisseur de formulaire (par ex. lors de la conversion d'un formulaire XFA vers le formulaire Standard) si le formulaire résultant doit être rendu comme signé ou comme non signé. |
| [setType](#setType-com.aspose.pdf.FormType-) | Obtient le type du formulaire. Les valeurs possibles sont : Standard, Static, Dynamic. |
| [size](#size--) | Obtient le nombre de champs sur ce formulaire. |

### Form {#Form-com.aspose.pdf.IDocument-}
Constructeur

### add {#add-com.aspose.pdf.Field-}
Ajoute un champ au formulaire.

### add {#add-com.aspose.pdf.Field-int-}
Ajoute un champ au formulaire.

### add {#add-com.aspose.pdf.Field-java.lang.String-int-}
Ajoute un nouveau champ au formulaire ; si ce champ est déjà placé sur un autre ou sur ce formulaire, une copie du champ est créée.

### add {#add-com.aspose.pdf.WidgetAnnotation-}
Ajoute un champ au formulaire.

### addFieldAppearance {#addFieldAppearance-com.aspose.pdf.Field-int-com.aspose.pdf.Rectangle-}
Ajoute une apparence supplémentaire du champ à la page spécifiée du document à l'emplacement indiqué.

### addFieldToAcroForm {#addFieldToAcroForm-com.aspose.pdf.Field-}
Ajoute une apparence supplémentaire du champ à la page spécifiée du document.

### assignXfa {#assignXfa-com.aspose.ms.System.Xml.XmlDocument-}
Définit le XFA du formulaire à la valeur spécifiée.

### clear {#clear--}
```
public void clear()
```

Supprime tous les champs du formulaire. Non pris en charge.

### contains {#contains-com.aspose.pdf.WidgetAnnotation-}
Détermine si le champ est présent sur le formulaire..

### copyTo {#copyTo-com.aspose.pdf.Field:A-int-}
Copie les champs placés sur le formulaire dans un tableau.

### copyTo {#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-}
Copie les champs du formulaire dans un tableau.

### delete {#delete-com.aspose.pdf.Field-}
Supprime le champ du formulaire.

### delete {#delete-java.lang.String-}
Supprime le champ du formulaire par son nom.

### flatten {#flatten--}
```
public void flatten()
```

Supprime tous les champs de formulaire statiques et place leurs valeurs directement sur la page.

### get_Item {#get_Item-int-}
```
public WidgetAnnotation get_Item(int index)
```

Obtient le champ du formulaire par indice de champ.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | Indice du champ. |

**Returns:**
Champ récupéré.

### get_Item {#get_Item-java.lang.String-}
Obtient le champ du formulaire par nom de champ. Lance une exception si le champ n'a pas été trouvé.

### get_xfa {#get_xfa--}
```
public XFA get_xfa()
```

À usage interne uniquement

**Returns:**
Objet XFA

### get {#get-int-}
```
public WidgetAnnotation get(int index)
```



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  |  |

### get {#get-java.lang.String-}
Recherche le champ par nom de champ. Retourne null si le champ n'a pas été trouvé.

### getAutoRecalculate {#getAutoRecalculate--}
```
public final boolean getAutoRecalculate()
```

Si défini, tous les champs du formulaire seront recalculés lorsqu'un champ est modifié. La valeur par défaut est true. Définissez à false afin d'augmenter les performances lors du remplissage du formulaire avec un grand nombre de champs calculés.

**Returns:**
valeur booléenne

### getAutoRestoreForm {#getAutoRestoreForm--}
```
public final boolean getAutoRestoreForm()
```

Si défini, les champs de formulaire absents seront automatiquement créés s'ils sont présents dans les annotations.

**Returns:**
valeur booléenne

### getDefaultAppearance {#getDefaultAppearance--}
```
public DefaultAppearance getDefaultAppearance()
```

Obtient l'apparence par défaut du formulaire (objet qui décrit la police, la taille du texte et la couleur par défaut pour les champs du formulaire).

**Returns:**
objet DefaultAppearance

### getDefaultResources {#getDefaultResources--}
```
public Resources getDefaultResources()
```

Obtient les ressources par défaut placées sur ce formulaire.

**Returns:**
Valeur des ressources

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

À usage interne uniquement

**Returns:**
Objet IDocument

### getEmulateRequierdGroups {#getEmulateRequierdGroups--}
```
public boolean getEmulateRequierdGroups()
```

Si cette propriété est vraie, des rectangles rouges supplémentaires seront dessinés autour des conteneurs d'éléments requis Xfa exclGroup. Cette propriété a été introduite en raison de l'absence d'analogies pour le exclGroup lors de la conversion de la représentation Xfa des formulaires vers le standard. Elle est fausse par défaut.

**Returns:**
valeur booléenne

### getFields {#getFields--}
```
public Field [] getFields()
```

Obtient la liste de tous les champs au niveau le plus bas du formulaire hiérarchique.

**Returns:**
Tableau contenant les champs trouvés.

### getFieldsInRect {#getFieldsInRect-com.aspose.pdf.Rectangle-}
Renvoie les champs à l'intérieur du rectangle spécifié.

### getIgnoreNeedsRendering {#getIgnoreNeedsRendering--}
```
public boolean getIgnoreNeedsRendering()
```

Si cette propriété est vraie, la valeur de la clé NeedsRendering sera ignorée lors de la conversion du formulaire XFA vers le formulaire Standard. Elle est fausse par défaut.

**Returns:**
valeur booléenne

### getNeedsRendering {#getNeedsRendering--}
```
public final boolean getNeedsRendering()
```

Obtient une valeur indiquant si le document nécessite la suppression du formulaire XFA dynamique. Cette propriété a été introduite pour déterminer si {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) doit être utilisé pour supprimer le formulaire XFA dans les cas où le formulaire XFA est présent et {@code NeedsRendering}({@link #getNeedsRendering}) est faux.

**Returns:**
valeur booléenne

### getRemovePermission {#getRemovePermission--}
```
public boolean getRemovePermission()
```

Si cette propriété est vraie, le dictionnaire \"Perms\" sera supprimé du document PDF après la conversion des documents dynamiques vers le standard. Le dictionnaire \"Perms\" peut contenir des règles qui perturbent l'affichage et la sélection des champs obligatoires dans le lecteur Adobe Acrobat. Elle est fausse par défaut.

**Returns:**
valeur booléenne

### getSignaturesAppendOnly {#getSignaturesAppendOnly--}
```
public final boolean getSignaturesAppendOnly()
```

Si défini, le document contient des signatures qui peuvent être invalidées si le fichier est enregistré (écrit) d'une manière qui modifie son contenu précédent, contrairement à une mise à jour incrémentielle.

**Returns:**
valeur booléenne

### getSignaturesExist {#getSignaturesExist--}
```
public final boolean getSignaturesExist()
```

Si défini, le document contient au moins un champ de signature.

**Returns:**
valeur booléenne

### getSignDependentElementsRenderingModeWhenConverted {#getSignDependentElementsRenderingModeWhenConverted--}
```
public int getSignDependentElementsRenderingModeWhenConverted()
```

Les formulaires peuvent contenir des informations de signature, c'est‑à‑dire qu'ils peuvent être signés ou non signés. Et la vue du formulaire doit parfois dépendre du fait que le formulaire soit signé ou non. Cette propriété indique au convertisseur de formulaire (par ex. lors de la conversion d'un formulaire XFA vers le formulaire Standard) si le formulaire résultant doit être rendu comme signé ou comme non signé.

**Returns:**
Élément SignDependentElementsRenderingModes @see SignDependentElementsRenderingModes

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Renvoie l'objet de synchronisation.

**Returns:**
Objet pour la synchronisation

### getType {#getType--}
```
public FormType getType()
```

Obtient le type du formulaire. Les valeurs possibles sont : Standard, Static, Dynamic.

**Returns:**
Valeur FormType @see FormType

### getXFA {#getXFA--}
```
public XFA getXFA()
```

Obtient les données XFA du formulaire (si présentes).

**Returns:**
Valeur XFA

### hasField {#hasField-com.aspose.pdf.Field-}
Vérifie si le formulaire possède déjà le champ spécifié.

### hasField {#hasField-java.lang.String-}
Détermine si le champ portant le nom spécifié a déjà été ajouté au formulaire.

### hasField {#hasField-java.lang.String-boolean-}
Détermine si le champ portant le nom spécifié a déjà été ajouté au formulaire, avec la possibilité d'examiner la hiérarchie des champs enfants.

### hasXfa {#hasXfa--}
```
public final boolean hasXfa()
```

Obtient une valeur indiquant si le document contient un formulaire XFA. Cette propriété a été introduite pour déterminer si {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) doit être utilisé pour supprimer le formulaire XFA dans les cas où le formulaire XFA est présent et {@code NeedsRendering}({@link #getNeedsRendering}) est faux.

**Returns:**
valeur booléenne

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Détermine si la collection est en lecture seule. Retourne toujours false.

**Returns:**
valeur booléenne

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Renvoie true si l'objet est thread‑safe.

**Returns:**
valeur booléenne

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.List.Enumerator< WidgetAnnotation > iterator()
```

Obtient l'énumération des champs du formulaire.

**Returns:**
Énumérateur de champ.

### makeFormAnnotationsIndependent {#makeFormAnnotationsIndependent-com.aspose.pdf.Page-}
/ * / * Exporte les champs du formulaire PDF au format JSON et écrit le résultat dans le flux fourni. / * / * Document document = new Document("PdfDoc.pdf"); / * FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write); / * document.Form.ExportFormFieldsToJson(fs); / * fs.Close(); / *

### remove {#remove-com.aspose.pdf.WidgetAnnotation-}
Supprime le champ du formulaire.

### removeFieldAppearance {#removeFieldAppearance-com.aspose.pdf.Field-int-}
Supprime l'apparence du champ à l'index spécifié. S'il ne reste qu'une seule apparence enfant, la méthode l'intègre au champ.

### setAutoRecalculate {#setAutoRecalculate-boolean-}
```
public final void setAutoRecalculate(boolean value)
```

Si défini, tous les champs du formulaire seront recalculés lorsqu'un champ est modifié. La valeur par défaut est true. Définissez à false afin d'augmenter les performances lors du remplissage du formulaire avec un grand nombre de champs calculés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setAutoRestoreForm {#setAutoRestoreForm-boolean-}
```
public final void setAutoRestoreForm(boolean value)
```

Si défini, les champs de formulaire absents seront automatiquement créés s'ils sont présents dans les annotations.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setCalculatedFields {#setCalculatedFields-java.util.List-}
Permet de définir l'ordre de calcul des champs.

### setDefaultAppearance {#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-}
Définit l'apparence par défaut du formulaire (objet qui décrit la police, la taille du texte et la couleur par défaut pour les champs du formulaire).

### setEmulateRequierdGroups {#setEmulateRequierdGroups-boolean-}
```
public void setEmulateRequierdGroups(boolean value)
```

Si cette propriété est vraie, des rectangles rouges supplémentaires seront dessinés autour des conteneurs d'éléments requis Xfa exclGroup. Cette propriété a été introduite en raison de l'absence d'analogies pour le exclGroup lors de la conversion de la représentation Xfa des formulaires vers le standard. Elle est fausse par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setIgnoreNeedsRendering {#setIgnoreNeedsRendering-boolean-}
```
public void setIgnoreNeedsRendering(boolean value)
```

Si cette propriété est vraie, la valeur de la clé NeedsRendering sera ignorée lors de la conversion du formulaire XFA vers le formulaire Standard. Elle est fausse par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setRemovePermission {#setRemovePermission-boolean-}
```
public void setRemovePermission(boolean value)
```

Si cette propriété est vraie, le dictionnaire \"Perms\" sera supprimé du document PDF après la conversion des documents dynamiques vers le standard. Le dictionnaire \"Perms\" peut contenir des règles qui perturbent l'affichage et la sélection des champs obligatoires dans le lecteur Adobe Acrobat. Elle est fausse par défaut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setSignaturesAppendOnly {#setSignaturesAppendOnly-boolean-}
```
public final void setSignaturesAppendOnly(boolean value)
```

Si défini, le document contient des signatures qui peuvent être invalidées si le fichier est enregistré (écrit) d'une manière qui modifie son contenu précédent, contrairement à une mise à jour incrémentielle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setSignaturesExist {#setSignaturesExist-boolean-}
```
public final void setSignaturesExist(boolean value)
```

Si défini, le document contient au moins un champ de signature.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setSignDependentElementsRenderingModeWhenConverted {#setSignDependentElementsRenderingModeWhenConverted-int-}
```
public void setSignDependentElementsRenderingModeWhenConverted(int signDependentElementsRenderingModeWhenConverted)
```

Les formulaires peuvent contenir des informations de signature, c'est‑à‑dire qu'ils peuvent être signés ou non signés. Et la vue du formulaire doit parfois dépendre du fait que le formulaire soit signé ou non. Cette propriété indique au convertisseur de formulaire (par ex. lors de la conversion d'un formulaire XFA vers le formulaire Standard) si le formulaire résultant doit être rendu comme signé ou comme non signé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| signDependentElementsRenderingModeWhenConverted |  | Élément SignDependentElementsRenderingModes @see SignDependentElementsRenderingModes |

### setType {#setType-com.aspose.pdf.FormType-}
Obtient le type du formulaire. Les valeurs possibles sont : Standard, Static, Dynamic.

### size {#size--}
```
public final int size()
```

Obtient le nombre de champs sur ce formulaire.

**Returns:**
valeur int
