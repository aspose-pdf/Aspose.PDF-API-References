---
title: "PrintPaperSize"
linktitle: "PrintPaperSize"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Spécifie la taille d'une feuille de papier."
type: docs
weight: 100
url: /fr/java/com.aspose.pdf.printing/printpapersize/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PrintPaperSize

```
public class PrintPaperSize extends Object
```

Spécifie la taille d'une feuille de papier.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PrintPaperSize](#PrintPaperSize--) | Initialise une nouvelle instance de la classe PaperSize. |
| [PrintPaperSize](#PrintPaperSize-int-java.lang.String-int-int-) | Initialise une nouvelle instance de la classe PaperSize. |
| [PrintPaperSize](#PrintPaperSize-java.lang.String-int-int-) | Initialise une nouvelle instance de la classe PaperSize. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getHeight](#getHeight--) | Obtient ou définit la hauteur du papier, en centièmes de pouce. |
| [getKind](#getKind--) | Obtient le type de papier. |
| [getPaperName](#getPaperName--) | Obtient ou définit le nom du type de papier. |
| [getRawKind](#getRawKind--) | Obtient ou définit un entier représentant l'une des valeurs de PaperSize ou une valeur personnalisée. |
| [getWidth](#getWidth--) | Obtient ou définit la largeur du papier, en centièmes de pouce. |
| [setHeight](#setHeight-int-) | Obtient ou définit la hauteur du papier, en centièmes de pouce. |
| [setPaperName](#setPaperName-java.lang.String-) | Obtient le nom du type de papier. |
| [setWidth](#setWidth-int-) | Définit la largeur du papier, en centièmes de pouce. |
| [toNativePaperSize](#toNativePaperSize-com.aspose.pdf.printing.PrintPaperSize-) | Convertit {@link PaperSize} en System.Drawing.Printing.PaperSize spécifique à Windows. |
| [toString](#toString--) | Obtient le nom de cette instance. |

### PrintPaperSize {#PrintPaperSize--}
```
public PrintPaperSize()
```

Initialise une nouvelle instance de la classe PaperSize.

### PrintPaperSize {#PrintPaperSize-int-java.lang.String-int-int-}
Initialise une nouvelle instance de la classe PaperSize.

### PrintPaperSize {#PrintPaperSize-java.lang.String-int-int-}
Initialise une nouvelle instance de la classe PaperSize.

### getHeight {#getHeight--}
```
public int getHeight()
```

Obtient ou définit la hauteur du papier, en centièmes de pouce.

**Returns:**
valeur int

### getKind {#getKind--}
```
public int getKind()
```

Obtient le type de papier.

**Returns:**
int value @see PrinterPaperKind

### getPaperName {#getPaperName--}
```
public String getPaperName()
```

Obtient ou définit le nom du type de papier.

**Returns:**
valeur String

### getRawKind {#getRawKind--}
```
public int getRawKind()
```

Obtient ou définit un entier représentant l'une des valeurs de PaperSize ou une valeur personnalisée.

**Returns:**
valeur int

### getWidth {#getWidth--}
```
public int getWidth()
```

Obtient ou définit la largeur du papier, en centièmes de pouce.

**Returns:**
valeur int

### setHeight {#setHeight-int-}
```
public void setHeight(int value)
```

Obtient ou définit la hauteur du papier, en centièmes de pouce.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setPaperName {#setPaperName-java.lang.String-}
Obtient le nom du type de papier.

### setWidth {#setWidth-int-}
```
public void setWidth(int value)
```

Définit la largeur du papier, en centièmes de pouce.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### toNativePaperSize {#toNativePaperSize-com.aspose.pdf.printing.PrintPaperSize-}
Convertit {@link PaperSize} en System.Drawing.Printing.PaperSize spécifique à Windows.

### toString {#toString--}
```
public String toString()
```

Obtient le nom de cette instance.

**Returns:**
valeur String
