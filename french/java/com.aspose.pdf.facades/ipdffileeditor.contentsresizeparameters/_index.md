---
title: "IPdfFileEditor.ContentsResizeParameters"
linktitle: "IPdfFileEditor.ContentsResizeParameters"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe pour spécifier les paramètres de redimensionnement de page. Permet de définir les paramètres suivants : taille de la page résultante (largeur, hauteur) en unités d'espace par défaut ou en pourcentage des pages initiales."
type: docs
weight: 300
url: /fr/java/com.aspose.pdf.facades/ipdffileeditor.contentsresizeparameters/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters

```
public static class IPdfFileEditor.ContentsResizeParameters extends Object
```

Classe permettant de spécifier les paramètres de redimensionnement de page. Autorise la définition des paramètres suivants : taille de la page résultante (largeur, hauteur) en unités d'espace par défaut ou en pourcentage de la taille de la page initiale ; marges gauche, haut, bas et droite en unités d'espace par défaut ou en pourcentage de la taille de la page initiale ; certaines valeurs peuvent être laissées nulles pour un calcul automatique. Ces valeurs seront calculées à partir du reste de la taille de la page après le calcul des valeurs explicitement spécifiées. Par exemple : si la largeur de la page = 100 et que la nouvelle largeur de page spécifiée est 60 unités, alors les marges gauche et droite sont calculées automatiquement : (100 - 60) / 2 = 15. Cette classe est utilisée dans la méthode ResizeContents.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ContentsResizeParameters](#ContentsResizeParameters--) | Crée des paramètres de redimensionnement où toutes les valeurs sont définies sur "auto". Les marges et la taille du contenu peuvent être spécifiées ultérieurement si nécessaire. |
| [ContentsResizeParameters](#ContentsResizeParameters-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Crée des paramètres de redimensionnement où toutes les valeurs sont définies sur "auto". Les marges et la taille du contenu peuvent être spécifiées ultérieurement si nécessaire. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [contentSize](#contentSize-double-double-) | Crée des paramètres de redimensionnement avec la taille du contenu spécifiée. |
| [contentSizePercent](#contentSizePercent-double-double-) | Crée des paramètres de redimensionnement avec la taille du contenu spécifiée en pourcentage de la taille de la page initiale. Les marges sont calculées automatiquement. |
| [getBottomMargin](#getBottomMargin--) | Obtient ou définit la marge inférieure sur la page résultante. |
| [getContentsHeight](#getContentsHeight--) | Obtient ou définit la hauteur du contenu de la page source sur la page résultante. |
| [getContentsWidth](#getContentsWidth--) | Obtient ou définit la largeur du contenu de la page source sur la page résultante. |
| [getLeftMargin](#getLeftMargin--) | Obtient ou définit la marge gauche sur la page résultante. |
| [getRightMargin](#getRightMargin--) | Obtient ou définit la marge droite sur la page résultante. |
| [getTopMargin](#getTopMargin--) | Obtient ou définit la marge supérieure sur la page résultante. |
| [isChangeMediaBox](#isChangeMediaBox--) | Obtient si l'on doit ajuster le MediaBox d'une page PDF pendant l'opération de redimensionnement. La valeur par défaut est {@code false}. La définition de ce paramètre active l'ajustement du MediaBox à la valeur du CropBox lors du redimensionnement. |
| [margins](#margins-double-double-double-double-) | Crée des paramètres de redimensionnement avec la valeur des marges spécifiée. La taille du contenu est calculée automatiquement. |
| [marginsPercent](#marginsPercent-double-double-double-double-) | Crée des paramètres de redimensionnement. Les marges sont spécifiées en pourcentage de la taille initiale de la page. |
| [pageResize](#pageResize-double-double-) | Crée des paramètres de redimensionnement pour le redimensionnement de la page. |
| [pageResizePct](#pageResizePct-double-double-) | Crée des paramètres de redimensionnement pour le redimensionnement de la page. Les nouvelles tailles sont spécifiées en pourcentage. |
| [setBottomMargin](#setBottomMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Obtient ou définit la marge inférieure sur la page résultante. |
| [setChangeMediaBox](#setChangeMediaBox-boolean-) | Définit s'il faut ajuster le MediaBox d'une page PDF pendant l'opération de redimensionnement. La valeur par défaut est {@code false}. Le réglage de ce paramètre permet d'adapter le MediaBox à la valeur du CropBox lors du redimensionnement. |
| [setContentsHeight](#setContentsHeight-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Obtient ou définit la hauteur du contenu de la page source sur la page résultante. |
| [setContentsWidth](#setContentsWidth-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Obtient ou définit la largeur du contenu de la page source sur la page résultante. |
| [setLeftMargin](#setLeftMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Obtient ou définit la marge gauche sur la page résultante. |
| [setRightMargin](#setRightMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Obtient ou définit la marge droite sur la page résultante. |
| [setTopMargin](#setTopMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | Obtient ou définit la marge supérieure sur la page résultante. |

### ContentsResizeParameters {#ContentsResizeParameters--}
```
public ContentsResizeParameters()
```

Crée des paramètres de redimensionnement où toutes les valeurs sont définies sur "auto". Les marges et la taille du contenu peuvent être spécifiées ultérieurement si nécessaire.

### ContentsResizeParameters {#ContentsResizeParameters-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Crée des paramètres de redimensionnement où toutes les valeurs sont définies sur "auto". Les marges et la taille du contenu peuvent être spécifiées ultérieurement si nécessaire.

### contentSize {#contentSize-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters contentSize(double width, double height)
```

Crée des paramètres de redimensionnement avec la taille du contenu spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| largeur |  | Nouvelle largeur du contenu. |
| hauteur |  | Nouvelle hauteur du contenu. |

**Returns:**
Renvoie de nouveaux paramètres de redimensionnement.

### contentSizePercent {#contentSizePercent-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters contentSizePercent(double width, double height)
```

Crée des paramètres de redimensionnement avec la taille du contenu spécifiée en pourcentage de la taille de la page initiale. Les marges sont calculées automatiquement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| largeur |  | Nouvelle largeur du contenu en pourcentage. |
| hauteur |  | Nouvelle hauteur du contenu en pourcentage. |

**Returns:**
Nouveaux paramètres de redimensionnement.

### getBottomMargin {#getBottomMargin--}
```
public IPdfFileEditor.ContentsResizeValue getBottomMargin()
```

Obtient ou définit la marge inférieure sur la page résultante.

**Returns:**
Objet ContentsResizeValue

### getContentsHeight {#getContentsHeight--}
```
public IPdfFileEditor.ContentsResizeValue getContentsHeight()
```

Obtient ou définit la hauteur du contenu de la page source sur la page résultante.

**Returns:**
Objet ContentsResizeValue

### getContentsWidth {#getContentsWidth--}
```
public IPdfFileEditor.ContentsResizeValue getContentsWidth()
```

Obtient ou définit la largeur du contenu de la page source sur la page résultante.

**Returns:**
Objet ContentsResizeValue

### getLeftMargin {#getLeftMargin--}
```
public IPdfFileEditor.ContentsResizeValue getLeftMargin()
```

Obtient ou définit la marge gauche sur la page résultante.

**Returns:**
Objet ContentsResizeValue

### getRightMargin {#getRightMargin--}
```
public IPdfFileEditor.ContentsResizeValue getRightMargin()
```

Obtient ou définit la marge droite sur la page résultante.

**Returns:**
Objet ContentsResizeValue

### getTopMargin {#getTopMargin--}
```
public IPdfFileEditor.ContentsResizeValue getTopMargin()
```

Obtient ou définit la marge supérieure sur la page résultante.

**Returns:**
Objet ContentsResizeValue

### isChangeMediaBox {#isChangeMediaBox--}
```
public final boolean isChangeMediaBox()
```

Obtient si l'on doit ajuster le MediaBox d'une page PDF pendant l'opération de redimensionnement. La valeur par défaut est {@code false}. La définition de ce paramètre active l'ajustement du MediaBox à la valeur du CropBox lors du redimensionnement.

**Returns:**
s'il faut ajuster le MediaBox d'une page PDF pendant l'opération de redimensionnement.

### margins {#margins-double-double-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters margins(double left, double right, double top, double bottom)
```

Crée des paramètres de redimensionnement avec la valeur des marges spécifiée. La taille du contenu est calculée automatiquement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| gauche |  | Marge gauche. |
| droite |  | Marge droite. |
| haut |  | Marge supérieure. |
| bas |  | Marge inférieure. |

**Returns:**
Paramètres de redimensionnement créés.

### marginsPercent {#marginsPercent-double-double-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters marginsPercent(double left, double right, double top, double bottom)
```

Crée des paramètres de redimensionnement. Les marges sont spécifiées en pourcentage de la taille initiale de la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| gauche |  | Marge gauche (en pourcentage de la largeur de la page). |
| droite |  | Marge droite (en pourcentage de la hauteur de la page). |
| haut |  | Marge supérieure (en pourcentage de la hauteur de la page). |
| bas |  | Marge inférieure (en pourcentage de la hauteur de la page). |

**Returns:**
Renvoie de nouveaux paramètres de redimensionnement.

### pageResize {#pageResize-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters pageResize(double width, double height)
```

Crée des paramètres de redimensionnement pour le redimensionnement de la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| largeur |  | Nouvelle largeur de page en unités. |
| hauteur |  | Nouvelle hauteur de page en unités. |

**Returns:**
Nouveaux paramètres de redimensionnement.

### pageResizePct {#pageResizePct-double-double-}
```
public IPdfFileEditor.ContentsResizeParameters pageResizePct(double widthPct, double heightPct)
```

Crée des paramètres de redimensionnement pour le redimensionnement de la page. Les nouvelles tailles sont spécifiées en pourcentage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| widthPct |  | Nouvelle largeur de page en pourcentage. |
| heightPct |  | Nouvelle hauteur de page en pourcentage. |

**Returns:**
Nouveaux paramètres de redimensionnement.

### setBottomMargin {#setBottomMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Obtient ou définit la marge inférieure sur la page résultante.

### setChangeMediaBox {#setChangeMediaBox-boolean-}
```
public final void setChangeMediaBox(boolean value)
```

Définit s'il faut ajuster le MediaBox d'une page PDF pendant l'opération de redimensionnement. La valeur par défaut est {@code false}. Le réglage de ce paramètre permet d'adapter le MediaBox à la valeur du CropBox lors du redimensionnement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | s'il faut ajuster le MediaBox d'une page PDF pendant l'opération de redimensionnement. |

### setContentsHeight {#setContentsHeight-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Obtient ou définit la hauteur du contenu de la page source sur la page résultante.

### setContentsWidth {#setContentsWidth-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Obtient ou définit la largeur du contenu de la page source sur la page résultante.

### setLeftMargin {#setLeftMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Obtient ou définit la marge gauche sur la page résultante.

### setRightMargin {#setRightMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Obtient ou définit la marge droite sur la page résultante.

### setTopMargin {#setTopMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
Obtient ou définit la marge supérieure sur la page résultante.
