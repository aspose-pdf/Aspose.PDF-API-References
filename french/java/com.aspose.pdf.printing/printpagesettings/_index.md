---
title: "PrintPageSettings"
linktitle: "PrintPageSettings"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Spécifie les paramètres qui s'appliquent à une seule page imprimée."
type: docs
weight: 90
url: /fr/java/com.aspose.pdf.printing/printpagesettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PrintPageSettings

```
public class PrintPageSettings extends Object
```

Spécifie les paramètres qui s'appliquent à une seule page imprimée.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PrintPageSettings](#PrintPageSettings--) | Initialise une nouvelle instance de la classe PageSettings en utilisant l'imprimante par défaut. |
| [PrintPageSettings](#PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | Initialise une nouvelle instance de la classe PageSettings en utilisant l'imprimante par défaut. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getBounds](#getBounds--) | Obtient la taille de la page, en tenant compte de l'orientation de la page spécifiée par la propriété Landscape. |
| [getHardMarginX](#getHardMarginX--) | Obtient la coordonnée x, en centièmes de pouce, de la marge fixe à gauche de la page. |
| [getHardMarginY](#getHardMarginY--) | Obtient la coordonnée y, en centièmes de pouce, de la marge fixe en haut de la page. |
| [getMargins](#getMargins--) | Obtient les marges de cette page. |
| [getPageSettings](#getPageSettings--) | Obtient les paramètres de page |
| [getPaperSize](#getPaperSize--) | Obtient la taille du papier pour la page. |
| [getPaperSource](#getPaperSource--) | Obtient la source du papier de la page ; par exemple, le plateau supérieur de l'imprimante. |
| [getPrintableArea](#getPrintableArea--) | Obtient les limites de la zone imprimable de la page pour l'imprimante. |
| [getPrinterResolution](#getPrinterResolution--) | Obtient la résolution de l'imprimante pour la page. |
| [getPrinterSettings](#getPrinterSettings--) | Obtient les paramètres d'imprimante associés à la page. |
| [isColor](#isColor--) | Obtient ou définit une valeur indiquant si la page doit être imprimée en couleur. |
| [isLandscape](#isLandscape--) | Obtient ou définit une valeur indiquant si la page est imprimée en orientation paysage ou portrait. |
| [setColor](#setColor-boolean-) | Obtient ou définit une valeur indiquant si la page doit être imprimée en couleur. |
| [setLandscape](#setLandscape-boolean-) | Obtient ou définit une valeur indiquant si la page est imprimée en orientation paysage ou portrait. |
| [setMargins](#setMargins-com.aspose.pdf.printing.PrinterMargins-) | Définit les marges de cette page. |
| [setPaperSize](#setPaperSize-com.aspose.pdf.printing.PrintPaperSize-) | Définit la taille du papier pour la page. |
| [setPaperSource](#setPaperSource-com.aspose.pdf.printing.PrintPaperSource-) | Définit la source du papier de la page ; par exemple, le plateau supérieur de l'imprimante. |
| [setPrinterResolution](#setPrinterResolution-com.aspose.pdf.printing.PdfPrinterResolution-) | Définit la résolution de l'imprimante pour la page. |
| [setPrinterSettings](#setPrinterSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | Définit les paramètres d'imprimante associés à la page. |

### PrintPageSettings {#PrintPageSettings--}
```
public PrintPageSettings()
```

Initialise une nouvelle instance de la classe PageSettings en utilisant l'imprimante par défaut.

### PrintPageSettings {#PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
Initialise une nouvelle instance de la classe PageSettings en utilisant l'imprimante par défaut.

### getBounds {#getBounds--}
```
public Rectangle getBounds()
```

Obtient la taille de la page, en tenant compte de l'orientation de la page spécifiée par la propriété Landscape.

**Returns:**
objet Rectangle

### getHardMarginX {#getHardMarginX--}
```
public float getHardMarginX()
```

Obtient la coordonnée x, en centièmes de pouce, de la marge fixe à gauche de la page.

**Returns:**
Valeur flottante

### getHardMarginY {#getHardMarginY--}
```
public float getHardMarginY()
```

Obtient la coordonnée y, en centièmes de pouce, de la marge fixe en haut de la page.

**Returns:**
Valeur flottante

### getMargins {#getMargins--}
```
public PrinterMargins getMargins()
```

Obtient les marges de cette page.

**Returns:**
Objet PrinterMargins

### getPageSettings {#getPageSettings--}
```
public com.aspose.ms.System.Drawing.Printing.PageSettings getPageSettings()
```

Obtient les paramètres de page

**Returns:**
Objet PageSettings

### getPaperSize {#getPaperSize--}
```
public PrintPaperSize getPaperSize()
```

Obtient la taille du papier pour la page.

**Returns:**
Objet PrintPaperSize

### getPaperSource {#getPaperSource--}
```
public PrintPaperSource getPaperSource()
```

Obtient la source du papier de la page ; par exemple, le plateau supérieur de l'imprimante.

**Returns:**
Objet PrintPaperSource

### getPrintableArea {#getPrintableArea--}
```
public Rectangle getPrintableArea()
```

Obtient les limites de la zone imprimable de la page pour l'imprimante.

**Returns:**
objet Rectangle

### getPrinterResolution {#getPrinterResolution--}
```
public PdfPrinterResolution getPrinterResolution()
```

Obtient la résolution de l'imprimante pour la page.

**Returns:**
Objet PdfPrinterResolution

### getPrinterSettings {#getPrinterSettings--}
```
public PdfPrinterSettings getPrinterSettings()
```

Obtient les paramètres d'imprimante associés à la page.

**Returns:**
Objet PdfPrinterSettings

### isColor {#isColor--}
```
public boolean isColor()
```

Obtient ou définit une valeur indiquant si la page doit être imprimée en couleur.

**Returns:**
valeur booléenne

### isLandscape {#isLandscape--}
```
public boolean isLandscape()
```

Obtient ou définit une valeur indiquant si la page est imprimée en orientation paysage ou portrait.

**Returns:**
valeur booléenne

### setColor {#setColor-boolean-}
```
public void setColor(boolean value)
```

Obtient ou définit une valeur indiquant si la page doit être imprimée en couleur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setLandscape {#setLandscape-boolean-}
```
public void setLandscape(boolean value)
```

Obtient ou définit une valeur indiquant si la page est imprimée en orientation paysage ou portrait.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setMargins {#setMargins-com.aspose.pdf.printing.PrinterMargins-}
Définit les marges de cette page.

### setPaperSize {#setPaperSize-com.aspose.pdf.printing.PrintPaperSize-}
Définit la taille du papier pour la page.

### setPaperSource {#setPaperSource-com.aspose.pdf.printing.PrintPaperSource-}
Définit la source du papier de la page ; par exemple, le plateau supérieur de l'imprimante.

### setPrinterResolution {#setPrinterResolution-com.aspose.pdf.printing.PdfPrinterResolution-}
Définit la résolution de l'imprimante pour la page.

### setPrinterSettings {#setPrinterSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
Définit les paramètres d'imprimante associés à la page.
