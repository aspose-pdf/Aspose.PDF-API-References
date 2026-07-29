---
title: "Signet"
linktitle: "Signet"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente un signet."
type: docs
weight: 60
url: /fr/java/com.aspose.pdf.facades/bookmark/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Bookmark

```
public final class Bookmark extends Object
```

Représente un signet.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Bookmark](#Bookmark--) | Initialise une nouvelle instance de la classe {@code Bookmark}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getAction](#getAction--) | Obtient l'action liée au signet. Si PageNumber est présent, l'action ne peut pas être spécifiée. Le type d'action comprend : "GoTo", "GoToR", "Launch", "Named". |
| [getBoldFlag](#getBoldFlag--) | Obtient le drapeau gras du titre du signet. |
| [getChildItem](#getChildItem--) | Obtient les enfants du signet. Obsolète("Utilisez la propriété getChildItems() à la place de celle-ci.") |
| [getChildItems](#getChildItems--) | Obtient les enfants du signet. |
| [getCustomAcorbatViewerMenuActionName](#getCustomAcorbatViewerMenuActionName--) | Pas encore pris en charge. Le nom d'action correspondant à l'exécution d'un élément de menu dans le visualiseur Acrobat. |
| [getDestination](#getDestination--) | Obtient la page de destination du signet. Requise si l'action est définie comme "". |
| [getItalicFlag](#getItalicFlag--) | Obtient le drapeau italique du titre du signet. |
| [getLevel](#getLevel--) | Obtient le niveau hiérarchique du signet. |
| [getPageDisplay_Bottom](#getPageDisplay_Bottom--) | Obtient la coordonnée inférieure de l'affichage de la page. |
| [getPageDisplay_Left](#getPageDisplay_Left--) | Obtient la coordonnée gauche de l'affichage de la page. |
| [getPageDisplay_Right](#getPageDisplay_Right--) | Obtient la coordonnée droite de l'affichage de la page. |
| [getPageDisplay_Top](#getPageDisplay_Top--) | Obtient la coordonnée supérieure de l'affichage de la page. |
| [getPageDisplay_Zoom](#getPageDisplay_Zoom--) | Obtient le facteur de zoom de l'affichage de la page. |
| [getPageDisplay](#getPageDisplay--) | Obtient le type de page de destination du signet d'affichage. |
| [getPageNumber](#getPageNumber--) | Obtient le numéro de la page de destination du signet. |
| [getRemoteFile](#getRemoteFile--) | Obtient le fichier (chemin) requis pour l'action "GoToR" du signet. |
| [getTitle](#getTitle--) | Obtient le titre du signet. |
| [getTitleColor](#getTitleColor--) | Obtient la couleur du titre du signet. |
| [isOpen](#isOpen--) | Obtient l'état du signet (ouvert, fermé). |
| [setAction](#setAction-java.lang.String-) | Définit l'action liée au signet. Si PageNumber est présent, l'action ne peut pas être spécifiée. Le type d'action comprend : "GoTo", "GoToR", "Launch", "Named". |
| [setBoldFlag](#setBoldFlag-boolean-) | Définit le drapeau gras du titre du signet. |
| [setChildItem](#setChildItem-com.aspose.pdf.facades.Bookmarks-) | Définit les enfants du signet. Obsolete("Use setChildItems() property instead of this one.") |
| [setChildItems](#setChildItems-com.aspose.pdf.facades.Bookmarks-) | Définit les enfants du signet. |
| [setCustomAcorbatViewerMenuActionName](#setCustomAcorbatViewerMenuActionName-int:A-) | Pas encore pris en charge. Définit le nom de l'action correspondant à l'exécution d'un élément de menu dans le visualiseur Acrobat. |
| [setDestination](#setDestination-java.lang.String-) | Définit la page de destination du signet. Requis si l'action est définie comme "". |
| [setItalicFlag](#setItalicFlag-boolean-) | Définit le drapeau italique du titre du signet. |
| [setLevel](#setLevel-int-) | Définit le niveau hiérarchique du signet. |
| [setOpen](#setOpen-boolean-) | Définit l'état du signet (ouvert, fermé). |
| [setPageDisplay_Bottom](#setPageDisplay_Bottom-int-) | Définit la coordonnée inférieure de l'affichage de la page. |
| [setPageDisplay_Left](#setPageDisplay_Left-int-) | Définit la coordonnée gauche de l'affichage de la page. |
| [setPageDisplay_Right](#setPageDisplay_Right-int-) | Définit la coordonnée droite de l'affichage de la page. |
| [setPageDisplay_Top](#setPageDisplay_Top-int-) | Définit la coordonnée supérieure de l'affichage de la page. |
| [setPageDisplay_Zoom](#setPageDisplay_Zoom-int-) | Définit le facteur de zoom de l'affichage de la page. |
| [setPageDisplay](#setPageDisplay-java.lang.String-) | Définit le type de page de destination du signet d'affichage. |
| [setPageNumber](#setPageNumber-int-) | Définit le numéro de la page de destination du signet. |
| [setRemoteFile](#setRemoteFile-java.lang.String-) | Définit le fichier (chemin) requis pour l'action "GoToR" du signet. |
| [setTitle](#setTitle-java.lang.String-) | Définit le titre du signet. |
| [setTitleColor](#setTitleColor-java.awt.Color-) | Définit la couleur du titre du signet. |
| [toOutlineItemCollection](#toOutlineItemCollection-com.aspose.pdf.IDocument-) | convertir en OutlineItemCollection |

### Bookmark {#Bookmark--}
```
public Bookmark()
```

Initialise une nouvelle instance de la classe {@code Bookmark}.

### getAction {#getAction--}
```
public String getAction()
```

Obtient l'action liée au signet. Si PageNumber est présent, l'action ne peut pas être spécifiée. Le type d'action comprend : "GoTo", "GoToR", "Launch", "Named".

**Returns:**
valeur String

### getBoldFlag {#getBoldFlag--}
```
public boolean getBoldFlag()
```

Obtient le drapeau gras du titre du signet.

**Returns:**
valeur booléenne

### getChildItem {#getChildItem--}
```
@Deprecated public Bookmarks getChildItem()
```

Obtient les enfants du signet. Obsolète("Utilisez la propriété getChildItems() à la place de celle-ci.")

**Returns:**
Élément Bookmarks

### getChildItems {#getChildItems--}
```
public Bookmarks getChildItems()
```

Obtient les enfants du signet.

**Returns:**
Éléments enfants du signet.

### getCustomAcorbatViewerMenuActionName {#getCustomAcorbatViewerMenuActionName--}
```
public int[] getCustomAcorbatViewerMenuActionName()
```

Pas encore pris en charge. Le nom d'action correspondant à l'exécution d'un élément de menu dans le visualiseur Acrobat.

**Returns:**
tableau de valeurs int

### getDestination {#getDestination--}
```
public String getDestination()
```

Obtient la page de destination du signet. Requise si l'action est définie comme "".

**Returns:**
valeur String

### getItalicFlag {#getItalicFlag--}
```
public boolean getItalicFlag()
```

Obtient le drapeau italique du titre du signet.

**Returns:**
valeur booléenne

### getLevel {#getLevel--}
```
public int getLevel()
```

Obtient le niveau hiérarchique du signet.

**Returns:**
valeur int

### getPageDisplay_Bottom {#getPageDisplay_Bottom--}
```
public int getPageDisplay_Bottom()
```

Obtient la coordonnée inférieure de l'affichage de la page.

**Returns:**
valeur int

### getPageDisplay_Left {#getPageDisplay_Left--}
```
public int getPageDisplay_Left()
```

Obtient la coordonnée gauche de l'affichage de la page.

**Returns:**
valeur int

### getPageDisplay_Right {#getPageDisplay_Right--}
```
public int getPageDisplay_Right()
```

Obtient la coordonnée droite de l'affichage de la page.

**Returns:**
valeur int

### getPageDisplay_Top {#getPageDisplay_Top--}
```
public int getPageDisplay_Top()
```

Obtient la coordonnée supérieure de l'affichage de la page.

**Returns:**
valeur int

### getPageDisplay_Zoom {#getPageDisplay_Zoom--}
```
public int getPageDisplay_Zoom()
```

Obtient le facteur de zoom de l'affichage de la page.

**Returns:**
valeur int

### getPageDisplay {#getPageDisplay--}
```
public String getPageDisplay()
```

Obtient le type de page de destination du signet d'affichage.

**Returns:**
valeur String

### getPageNumber {#getPageNumber--}
```
public int getPageNumber()
```

Obtient le numéro de la page de destination du signet.

**Returns:**
valeur int

### getRemoteFile {#getRemoteFile--}
```
public String getRemoteFile()
```

Obtient le fichier (chemin) requis pour l'action "GoToR" du signet.

**Returns:**
valeur String

### getTitle {#getTitle--}
```
public String getTitle()
```

Obtient le titre du signet.

**Returns:**
valeur String

### getTitleColor {#getTitleColor--}
```
public Color getTitleColor()
```

Obtient la couleur du titre du signet.

**Returns:**
Élément couleur

### isOpen {#isOpen--}
```
public boolean isOpen()
```

Obtient l'état du signet (ouvert, fermé).

**Returns:**
valeur booléenne

### setAction {#setAction-java.lang.String-}
Définit l'action liée au signet. Si PageNumber est présent, l'action ne peut pas être spécifiée. Le type d'action comprend : "GoTo", "GoToR", "Launch", "Named".

### setBoldFlag {#setBoldFlag-boolean-}
```
public void setBoldFlag(boolean value)
```

Définit le drapeau gras du titre du signet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setChildItem {#setChildItem-com.aspose.pdf.facades.Bookmarks-}
Définit les enfants du signet. Obsolete("Use setChildItems() property instead of this one.")

### setChildItems {#setChildItems-com.aspose.pdf.facades.Bookmarks-}
Définit les enfants du signet.

### setCustomAcorbatViewerMenuActionName {#setCustomAcorbatViewerMenuActionName-int:A-}
```
public void setCustomAcorbatViewerMenuActionName(int[] value)
```

Pas encore pris en charge. Définit le nom de l'action correspondant à l'exécution d'un élément de menu dans le visualiseur Acrobat.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | tableau de valeurs int |

### setDestination {#setDestination-java.lang.String-}
Définit la page de destination du signet. Requis si l'action est définie comme "".

### setItalicFlag {#setItalicFlag-boolean-}
```
public void setItalicFlag(boolean value)
```

Définit le drapeau italique du titre du signet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setLevel {#setLevel-int-}
```
public void setLevel(int value)
```

Définit le niveau hiérarchique du signet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

Définit l'état du signet (ouvert, fermé).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setPageDisplay_Bottom {#setPageDisplay_Bottom-int-}
```
public void setPageDisplay_Bottom(int value)
```

Définit la coordonnée inférieure de l'affichage de la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setPageDisplay_Left {#setPageDisplay_Left-int-}
```
public void setPageDisplay_Left(int value)
```

Définit la coordonnée gauche de l'affichage de la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setPageDisplay_Right {#setPageDisplay_Right-int-}
```
public void setPageDisplay_Right(int value)
```

Définit la coordonnée droite de l'affichage de la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setPageDisplay_Top {#setPageDisplay_Top-int-}
```
public void setPageDisplay_Top(int value)
```

Définit la coordonnée supérieure de l'affichage de la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setPageDisplay_Zoom {#setPageDisplay_Zoom-int-}
```
public void setPageDisplay_Zoom(int value)
```

Définit le facteur de zoom de l'affichage de la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setPageDisplay {#setPageDisplay-java.lang.String-}
Définit le type de page de destination du signet d'affichage.

### setPageNumber {#setPageNumber-int-}
```
public void setPageNumber(int value)
```

Définit le numéro de la page de destination du signet.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setRemoteFile {#setRemoteFile-java.lang.String-}
Définit le fichier (chemin) requis pour l'action "GoToR" du signet.

### setTitle {#setTitle-java.lang.String-}
Définit le titre du signet.

### setTitleColor {#setTitleColor-java.awt.Color-}
Définit la couleur du titre du signet.

### toOutlineItemCollection {#toOutlineItemCollection-com.aspose.pdf.IDocument-}
convertir en OutlineItemCollection
