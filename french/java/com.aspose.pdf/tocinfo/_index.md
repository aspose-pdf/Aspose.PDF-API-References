---
title: "TocInfo"
linktitle: "TocInfo"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente les informations de la table des matières."
type: docs
weight: 5370
url: /fr/java/com.aspose.pdf/tocinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TocInfo

```
public final class TocInfo extends Object
```

Représente les informations de la table des matières.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TocInfo](#TocInfo--) | Initialise une nouvelle instance de la classe {@code TocInfo}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getColumnInfo](#getColumnInfo--) | Obtient les informations de colonne. |
| [getCopyToOutlines](#getCopyToOutlines--) | Obtient ou définit si la TOC est copiée dans les repères. |
| [getFormatArray](#getFormatArray--) | Obtient le tableau de formats pour la table des matières. |
| [getFormatArrayLength](#getFormatArrayLength--) | Obtient la longueur du tableau de formats |
| [getLevelIndentation](#getLevelIndentation--) | Obtenir l'indentation du niveau |
| [getLineDash](#getLineDash--) | Obtient ou définit le tiret de ligne de la TOC. |
| [getPageNumbersPrefix](#getPageNumbersPrefix--) | Obtient si un préfixe est présent avant le numéro de page. |
| [getTitle](#getTitle--) | Obtient le titre de la table des matières. |
| [isCountTocPages](#isCountTocPages--) | Obtient le nombre ou les pages passées de la TOC. |
| [isShowPageNumbers](#isShowPageNumbers--) | Obtient si l'affichage des numéros de page est activé dans la TOC. |
| [setColumnInfo](#setColumnInfo-com.aspose.pdf.ColumnInfo-) | Définit les informations de colonne. |
| [setCopyToOutlines](#setCopyToOutlines-boolean-) | Obtient ou définit si la TOC est copiée dans les repères. |
| [setCountTocPages](#setCountTocPages-boolean-) | Définit le nombre de pages du sommaire passées. |
| [setFormatArray](#setFormatArray-com.aspose.pdf.LevelFormat:A-) | Définit le tableau de formats pour la table des matières. |
| [setFormatArrayLength](#setFormatArrayLength-int-) | Définit la longueur du tableau de formats |
| [setLevelIndentation](#setLevelIndentation-int-) | Définit l'indentation du niveau |
| [setLineDash](#setLineDash-int-) | Obtient ou définit le tiret de ligne de la TOC. |
| [setPageNumbersPrefix](#setPageNumbersPrefix-java.lang.String-) | Définit le préfixe avant le numéro de page. |
| [setShowPageNumbers](#setShowPageNumbers-boolean-) | Définit l'affichage des numéros de page dans le sommaire. |
| [setTitle](#setTitle-com.aspose.pdf.TextFragment-) | Définit le titre de la table des matières. |

### TocInfo {#TocInfo--}
```
public TocInfo()
```

Initialise une nouvelle instance de la classe {@code TocInfo}.

### getColumnInfo {#getColumnInfo--}
```
public final ColumnInfo getColumnInfo()
```

Obtient les informations de colonne.

**Returns:**
Instance de ColumnInfo

### getCopyToOutlines {#getCopyToOutlines--}
```
public final boolean getCopyToOutlines()
```

Obtient ou définit si la TOC est copiée dans les repères.

**Returns:**
valeur booléenne

### getFormatArray {#getFormatArray--}
```
public final LevelFormat [] getFormatArray()
```

Obtient le tableau de formats pour la table des matières.

**Returns:**
Tableau LevelFormat

### getFormatArrayLength {#getFormatArrayLength--}
```
public final int getFormatArrayLength()
```

Obtient la longueur du tableau de formats

**Returns:**
valeur booléenne

### getLevelIndentation {#getLevelIndentation--}
```
public int getLevelIndentation()
```

Obtenir l'indentation du niveau

**Returns:**
valeur int

### getLineDash {#getLineDash--}
```
public final int getLineDash()
```

Obtient ou définit le tiret de ligne de la TOC.

**Returns:**
Valeur TabLeaderType

### getPageNumbersPrefix {#getPageNumbersPrefix--}
```
public final String getPageNumbersPrefix()
```

Obtient si un préfixe est présent avant le numéro de page.

**Returns:**
valeur String

### getTitle {#getTitle--}
```
public final TextFragment getTitle()
```

Obtient le titre de la table des matières.

**Returns:**
Instance de TextFragment

### isCountTocPages {#isCountTocPages--}
```
public final boolean isCountTocPages()
```

Obtient le nombre ou les pages passées de la TOC.

**Returns:**
valeur booléenne

### isShowPageNumbers {#isShowPageNumbers--}
```
public final boolean isShowPageNumbers()
```

Obtient si l'affichage des numéros de page est activé dans la TOC.

**Returns:**
valeur booléenne

### setColumnInfo {#setColumnInfo-com.aspose.pdf.ColumnInfo-}
Définit les informations de colonne.

### setCopyToOutlines {#setCopyToOutlines-boolean-}
```
public final void setCopyToOutlines(boolean value)
```

Obtient ou définit si la TOC est copiée dans les repères.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setCountTocPages {#setCountTocPages-boolean-}
```
public final void setCountTocPages(boolean value)
```

Définit le nombre de pages du sommaire passées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setFormatArray {#setFormatArray-com.aspose.pdf.LevelFormat:A-}
Définit le tableau de formats pour la table des matières.

### setFormatArrayLength {#setFormatArrayLength-int-}
```
public final void setFormatArrayLength(int value)
```

Définit la longueur du tableau de formats

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setLevelIndentation {#setLevelIndentation-int-}
```
public void setLevelIndentation(int value)
```

Définit l'indentation du niveau

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setLineDash {#setLineDash-int-}
```
public final void setLineDash(int value)
```

Obtient ou définit le tiret de ligne de la TOC.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur TabLeaderType |

### setPageNumbersPrefix {#setPageNumbersPrefix-java.lang.String-}
Définit le préfixe avant le numéro de page.

### setShowPageNumbers {#setShowPageNumbers-boolean-}
```
public final void setShowPageNumbers(boolean value)
```

Définit l'affichage des numéros de page dans le sommaire.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setTitle {#setTitle-com.aspose.pdf.TextFragment-}
Définit le titre de la table des matières.
