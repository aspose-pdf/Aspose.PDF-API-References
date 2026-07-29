---
title: "Champ"
linktitle: "Champ"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe de base pour les champs de formulaire acro."
type: docs
weight: 1380
url: /fr/java/com.aspose.pdf/field/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class Field extends WidgetAnnotation implements com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, Cloneable
```

Classe de base pour les champs de formulaire acro.

## Champs

| Champ | Description |
| --- | --- |
| [_FileSelect](#Z:Z_FileSelect) | _FileSelect |
| [_Password](#Z:Z_Password) | _Password |

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Field](#Field-com.aspose.pdf.IDocument-) | Crée un champ à utiliser dans Generator. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.WidgetAnnotation-) |  |
| [clear](#clear--) |  |
| [contains](#contains-com.aspose.pdf.WidgetAnnotation-) |  |
| [copyTo_Rename_Namesake](#copyTo_Rename_Namesake-com.aspose.pdf.WidgetAnnotation:A-int-) | Copie les sous‑champs de ce champ dans un tableau à partir de l’index spécifié. |
| [copyTo](#copyTo-com.aspose.pdf.Field:A-int-) | Copie les sous‑champs de ce champ dans un tableau à partir de l’index spécifié. |
| [copyTo](#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-) |  |
| [executeFieldJavaScript](#executeFieldJavaScript-com.aspose.pdf.JavascriptAction-) | Exécute une action JavaScript spécifiée pour le champ. |
| [flatten](#flatten--) | Supprime ce champ et place sa valeur directement sur la page. |
| [get_Item](#get_Item-int-) | Obtient le sous‑champ contenu dans ce champ par index. |
| [get_Item](#get_Item-java.lang.String-) | Obtient le sous‑champ contenu dans ce champ par le nom du sous‑champ. |
| [getAlternateName](#getAlternateName--) | Obtient le nom alternatif du champ (Un nom de champ alternatif qui doit être utilisé à la place du nom réel du champ partout où le champ doit être identifié dans l’interface utilisateur). Le nom alternatif est utilisé comme infobulle du champ dans Adobe Acrobat. |
| [getAnnotationIndex](#getAnnotationIndex--) | Obtient l’index de cette annotation sur la page. |
| [getMappingName](#getMappingName--) | Obtient le nom de mappage du champ qui doit être utilisé lors de l’exportation des données de champs de formulaire interactif depuis le document. |
| [getMaxFontSize](#getMaxFontSize--) | Taille de police maximale pouvant être utilisée pour le contenu du champ. -1 pour ne pas vérifier la taille. |
| [getMinFontSize](#getMinFontSize--) | Taille de police minimale pouvant être utilisée pour le contenu du champ. -1 pour ne pas vérifier la taille. |
| [getPageIndex](#getPageIndex--) | Obtient l’index de la page contenant ce champ. |
| [getPartialName](#getPartialName--) | Obtient le nom partiel du champ. |
| [getRect](#getRect--) | Obtient le rectangle du champ. |
| [getSyncRoot](#getSyncRoot--) | Objet de synchronisation. |
| [getTabOrder](#getTabOrder--) | Obtient ou définit l’ordre de tabulation du champ. |
| [getValue](#getValue--) | Obtient la valeur du champ. |
| [isFitIntoRectangle](#isFitIntoRectangle--) | Si vrai, la taille de police sera réduite pour ajuster le texte au rectangle spécifié. |
| [isGroup](#isGroup--) | Obtient la valeur booléenne indiquant si ce champ est un champ non terminal, c’est‑à‑dire un groupe de champs. |
| [isReadOnly](#isReadOnly--) |  |
| [isSharedField](#isSharedField--) | Propriété pour la prise en charge de Generator. Utilisée lorsque le champ est ajouté à l’en‑tête ou au pied de page. Si vrai, ce champ sera créé une fois et son apparence sera visible sur toutes les pages du document. Si faux, un champ séparé sera créé pour chaque page du document. |
| [isSynchronized](#isSynchronized--) | Renvoie vrai si le dictionnaire est synchronisé. |
| [iterator](#iterator--) | Renvoie l’énumérateur des champs contenus. |
| [recalculate](#recalculate--) | Recalcule tous les champs calculés du formulaire. |
| [remove](#remove-com.aspose.pdf.WidgetAnnotation-) |  |
| [setAlternateName](#setAlternateName-java.lang.String-) | Définit le nom alternatif du champ (Un nom de champ alternatif qui doit être utilisé à la place du nom réel du champ partout où le champ doit être identifié dans l'interface utilisateur). Le nom alternatif est utilisé comme info-bulle du champ dans Adobe Acrobat. |
| [setAnnotationIndex](#setAnnotationIndex-int-) | Définit l'index de cette annotation sur la page. |
| [setFitIntoRectangle](#setFitIntoRectangle-boolean-) | Si vrai, la taille de police sera réduite pour ajuster le texte au rectangle spécifié. |
| [setMappingName](#setMappingName-java.lang.String-) | Définit le nom de mappage du champ qui doit être utilisé lors de l'exportation des données de champs de formulaire interactif depuis le document. |
| [setMaxFontSize](#setMaxFontSize-double-) | Taille de police maximale pouvant être utilisée pour le contenu du champ. -1 pour ne pas vérifier la taille. |
| [setMinFontSize](#setMinFontSize-double-) | Taille de police minimale pouvant être utilisée pour le contenu du champ. -1 pour ne pas vérifier la taille. |
| [setPartialName](#setPartialName-java.lang.String-) | Définit le nom partiel du champ. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Définit la position du champ. |
| [setRect](#setRect-com.aspose.pdf.Rectangle-) | Définit le rectangle du champ. |
| [setSharedField](#setSharedField-boolean-) | Propriété pour la prise en charge de Generator. Utilisée lorsque le champ est ajouté à l’en‑tête ou au pied de page. Si vrai, ce champ sera créé une fois et son apparence sera visible sur toutes les pages du document. Si faux, un champ séparé sera créé pour chaque page du document. |
| [setTabOrder](#setTabOrder-int-) | Obtient ou définit l’ordre de tabulation du champ. |
| [setValue](#setValue-java.lang.String-) | Définit la valeur. |
| [size](#size--) | Obtient le nombre de sous‑champs dans ce champ. (Par exemple le nombre d'éléments dans un champ bouton radio). |
| [updateAppearances](#updateAppearances--) | Met à jour la valeur des apparences. |

### _FileSelect {#Z:Z_FileSelect}
```
public static final int _FileSelect
```

_FileSelect

### _Password {#Z:Z_Password}
```
public static final int _Password
```

_Password

### Field {#Field-com.aspose.pdf.IDocument-}
Crée un champ à utiliser dans Generator.

### add {#add-com.aspose.pdf.WidgetAnnotation-}


### clear {#clear--}
```
public void clear()
```



### contains {#contains-com.aspose.pdf.WidgetAnnotation-}


### copyTo_Rename_Namesake {#copyTo_Rename_Namesake-com.aspose.pdf.WidgetAnnotation:A-int-}
Copie les sous‑champs de ce champ dans un tableau à partir de l’index spécifié.

### copyTo {#copyTo-com.aspose.pdf.Field:A-int-}
Copie les sous‑champs de ce champ dans un tableau à partir de l’index spécifié.

### copyTo {#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-}


### executeFieldJavaScript {#executeFieldJavaScript-com.aspose.pdf.JavascriptAction-}
Exécute une action JavaScript spécifiée pour le champ.

### flatten {#flatten--}
```
public void flatten()
```

Supprime ce champ et place sa valeur directement sur la page.

### get_Item {#get_Item-int-}
```
public WidgetAnnotation get_Item(int index)
```

Obtient le sous‑champ contenu dans ce champ par index.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| index |  | Index du sous‑champ demandé. |

**Returns:**
Instance du champ.

### get_Item {#get_Item-java.lang.String-}
Obtient le sous‑champ contenu dans ce champ par le nom du sous‑champ.

### getAlternateName {#getAlternateName--}
```
public String getAlternateName()
```

Obtient le nom alternatif du champ (Un nom de champ alternatif qui doit être utilisé à la place du nom réel du champ partout où le champ doit être identifié dans l’interface utilisateur). Le nom alternatif est utilisé comme infobulle du champ dans Adobe Acrobat.

**Returns:**
valeur String

### getAnnotationIndex {#getAnnotationIndex--}
```
public int getAnnotationIndex()
```

Obtient l’index de cette annotation sur la page.

**Returns:**
valeur int

### getMappingName {#getMappingName--}
```
public String getMappingName()
```

Obtient le nom de mappage du champ qui doit être utilisé lors de l’exportation des données de champs de formulaire interactif depuis le document.

**Returns:**
valeur String

### getMaxFontSize {#getMaxFontSize--}
```
public static double getMaxFontSize()
```

Taille de police maximale pouvant être utilisée pour le contenu du champ. -1 pour ne pas vérifier la taille.

**Returns:**
valeur double

### getMinFontSize {#getMinFontSize--}
```
public static double getMinFontSize()
```

Taille de police minimale pouvant être utilisée pour le contenu du champ. -1 pour ne pas vérifier la taille.

**Returns:**
valeur double

### getPageIndex {#getPageIndex--}
```
public int getPageIndex()
```

Obtient l’index de la page contenant ce champ.

**Returns:**
valeur int

### getPartialName {#getPartialName--}
```
public String getPartialName()
```

Obtient le nom partiel du champ.

**Returns:**
valeur String

### getRect {#getRect--}
```
public Rectangle getRect()
```

Obtient le rectangle du champ.

**Returns:**
le rectangle du champ.

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Objet de synchronisation.

**Returns:**
valeur de l'objet

### getTabOrder {#getTabOrder--}
```
public int getTabOrder()
```

Obtient ou définit l’ordre de tabulation du champ.

**Returns:**
valeur int

### getValue {#getValue--}
```
public String getValue()
```

Obtient la valeur du champ.

**Returns:**
valeur String

### isFitIntoRectangle {#isFitIntoRectangle--}
```
public static boolean isFitIntoRectangle()
```

Si vrai, la taille de police sera réduite pour ajuster le texte au rectangle spécifié.

**Returns:**
valeur booléenne

### isGroup {#isGroup--}
```
public boolean isGroup()
```

Obtient la valeur booléenne indiquant si ce champ est un champ non terminal, c’est‑à‑dire un groupe de champs.

**Returns:**
valeur booléenne

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```



### isSharedField {#isSharedField--}
```
public boolean isSharedField()
```

Propriété pour la prise en charge de Generator. Utilisée lorsque le champ est ajouté à l’en‑tête ou au pied de page. Si vrai, ce champ sera créé une fois et son apparence sera visible sur toutes les pages du document. Si faux, un champ séparé sera créé pour chaque page du document.

**Returns:**
valeur booléenne

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Renvoie vrai si le dictionnaire est synchronisé.

**Returns:**
valeur booléenne

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.List.Enumerator< WidgetAnnotation > iterator()
```

Renvoie l’énumérateur des champs contenus.

**Returns:**
Objet énumérateur.

### recalculate {#recalculate--}
```
public boolean recalculate()
```

Recalcule tous les champs calculés du formulaire.

**Returns:**
vrai si la valeur du champ a été modifiée lors du recalcul.

### remove {#remove-com.aspose.pdf.WidgetAnnotation-}


### setAlternateName {#setAlternateName-java.lang.String-}
Définit le nom alternatif du champ (Un nom de champ alternatif qui doit être utilisé à la place du nom réel du champ partout où le champ doit être identifié dans l'interface utilisateur). Le nom alternatif est utilisé comme info-bulle du champ dans Adobe Acrobat.

### setAnnotationIndex {#setAnnotationIndex-int-}
```
public void setAnnotationIndex(int value)
```

Définit l'index de cette annotation sur la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setFitIntoRectangle {#setFitIntoRectangle-boolean-}
```
public static void setFitIntoRectangle(boolean value)
```

Si vrai, la taille de police sera réduite pour ajuster le texte au rectangle spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setMappingName {#setMappingName-java.lang.String-}
Définit le nom de mappage du champ qui doit être utilisé lors de l'exportation des données de champs de formulaire interactif depuis le document.

### setMaxFontSize {#setMaxFontSize-double-}
```
public static void setMaxFontSize(double value)
```

Taille de police maximale pouvant être utilisée pour le contenu du champ. -1 pour ne pas vérifier la taille.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setMinFontSize {#setMinFontSize-double-}
```
public static void setMinFontSize(double value)
```

Taille de police minimale pouvant être utilisée pour le contenu du champ. -1 pour ne pas vérifier la taille.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setPartialName {#setPartialName-java.lang.String-}
Définit le nom partiel du champ.

### setPosition {#setPosition-com.aspose.pdf.Point-}
Définit la position du champ.

### setRect {#setRect-com.aspose.pdf.Rectangle-}
Définit le rectangle du champ.

### setSharedField {#setSharedField-boolean-}
```
public void setSharedField(boolean value)
```

Propriété pour la prise en charge de Generator. Utilisée lorsque le champ est ajouté à l’en‑tête ou au pied de page. Si vrai, ce champ sera créé une fois et son apparence sera visible sur toutes les pages du document. Si faux, un champ séparé sera créé pour chaque page du document.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setTabOrder {#setTabOrder-int-}
```
public void setTabOrder(int value)
```

Obtient ou définit l’ordre de tabulation du champ.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setValue {#setValue-java.lang.String-}
Définit la valeur.

### size {#size--}
```
public int size()
```

Obtient le nombre de sous‑champs dans ce champ. (Par exemple le nombre d'éléments dans un champ bouton radio).

**Returns:**
valeur int

### updateAppearances {#updateAppearances--}
```
public void updateAppearances()
```

Met à jour la valeur des apparences.
