---
title: "PdfPrinterSettings"
linktitle: "PdfPrinterSettings"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Spécifie les informations sur la façon dont un document est imprimé, y compris l'imprimante qui l'imprime."
type: docs
weight: 50
url: /fr/java/com.aspose.pdf.printing/pdfprintersettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PdfPrinterSettings

```
public class PdfPrinterSettings extends Object
```

Spécifie les informations sur la façon dont un document est imprimé, y compris l'imprimante qui l'imprime.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PdfPrinterSettings](#PdfPrinterSettings--) | Initialise une nouvelle instance de la classe PrinterSettings. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [canDuplex](#canDuplex--) | Obtient une valeur indiquant si l'imprimante prend en charge l'impression recto verso. |
| [createMeasurementGraphics](#createMeasurementGraphics--) | Obtenir l'objet Graphics2D |
| [createMeasurementGraphics](#createMeasurementGraphics-boolean-) | Obtenir l'objet Graphics2D |
| [createMeasurementGraphics](#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-) | Obtenir l'objet Graphics2D |
| [createMeasurementGraphics](#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-boolean-) | Obtenir l'objet Graphics2D |
| [deepClone](#deepClone--) | Obtenir l'objet cloné |
| [getCopies](#getCopies--) | Obtient le nombre de copies du document à imprimer. |
| [getDefaultPageSettings](#getDefaultPageSettings--) | Obtient les paramètres de page par défaut pour cette imprimante. |
| [getDuplex](#getDuplex--) | Obtient ou définit le paramètre d'imprimante pour l'impression recto verso. |
| [getFromPage](#getFromPage--) | Obtient ou définit le numéro de page de la première page à imprimer. |
| [getInstalledPrinters](#getInstalledPrinters--) | Obtient les noms de toutes les imprimantes installées sur l'ordinateur. |
| [getLandscapeAngle](#getLandscapeAngle--) | Obtient l'angle, en degrés, selon lequel l'orientation portrait est pivotée pour produire l'orientation paysage. |
| [getMaximumCopies](#getMaximumCopies--) | Obtient le nombre maximal de copies que l'imprimante permet à l'utilisateur d'imprimer en une fois. |
| [getMaximumPage](#getMaximumPage--) | Obtient ou définit le maximum FromPage ou ToPage qui peut être sélectionné dans une boîte de dialogue d'impression. |
| [getMinimumPage](#getMinimumPage--) | Obtient ou définit le minimum FromPage ou ToPage qui peut être sélectionné dans une boîte de dialogue d'impression. |
| [getPaperSizes](#getPaperSizes--) | Obtient les formats de papier pris en charge par cette imprimante. |
| [getPaperSources](#getPaperSources--) | Obtient les bacs d'alimentation papier disponibles sur l'imprimante. |
| [getPrinterName](#getPrinterName--) | Obtient ou définit le nom de l'imprimante à utiliser. |
| [getPrinterResolutions](#getPrinterResolutions--) | Obtient toutes les résolutions prises en charge par cette imprimante. |
| [getPrinterSettings](#getPrinterSettings--) | Renvoie l'objet PrinterSettings |
| [getPrintFileName](#getPrintFileName--) | Obtient ou définit le nom de fichier, lors de l'impression vers un fichier. |
| [getPrintRange](#getPrintRange--) | Obtient ou définit les numéros de page que l'utilisateur a spécifiés pour l'impression. |
| [getSelectedPages](#getSelectedPages--) | Obtient le nombre de pages sélectionnées à imprimer. |
| [getToPage](#getToPage--) | Obtient ou définit le numéro de la dernière page à imprimer. |
| [isCollate](#isCollate--) | Obtient ou définit une valeur indiquant si le document imprimé est assemblé. |
| [isDefaultPrinter](#isDefaultPrinter--) | Obtient une valeur indiquant si la propriété PrinterName désigne l'imprimante par défaut, sauf lorsque l'utilisateur définit explicitement PrinterName. |
| [isDirectPrintingSupported](#isDirectPrintingSupported-com.aspose.pdf.ImageType-) | Obtient une valeur indiquant si l'imprimante est Supported DirectPrinting |
| [isDirectPrintingSupported](#isDirectPrintingSupported-java.lang.String-) | Obtient une valeur indiquant si l'imprimante est Supported DirectPrinting |
| [isPlotter](#isPlotter--) | Obtient une valeur indiquant si l'imprimante est un traceur. |
| [isPrintToFile](#isPrintToFile--) | Obtient une valeur indiquant si la sortie d'impression est envoyée vers un fichier au lieu d'un port. |
| [isSupportsColor](#isSupportsColor--) | Obtient une valeur indiquant si cette imprimante prend en charge l'impression couleur. |
| [isValid](#isValid--) | Obtient une valeur indiquant si la propriété PrinterName désigne une imprimante valide. |
| [setCollate](#setCollate-boolean-) | Obtient ou définit une valeur indiquant si le document imprimé est assemblé. |
| [setCopies](#setCopies-short-) | Définit le nombre de copies du document à imprimer. |
| [setDuplex](#setDuplex-int-) | Obtient ou définit le paramètre d'imprimante pour l'impression recto verso. |
| [setFromPage](#setFromPage-int-) | Obtient ou définit le numéro de page de la première page à imprimer. |
| [setMaximumPage](#setMaximumPage-int-) | Obtient ou définit le maximum FromPage ou ToPage qui peut être sélectionné dans une boîte de dialogue d'impression. |
| [setMinimumPage](#setMinimumPage-int-) | Obtient ou définit le minimum FromPage ou ToPage qui peut être sélectionné dans une boîte de dialogue d'impression. |
| [setPrinterName](#setPrinterName-java.lang.String-) | Définit le nom de l'imprimante à utiliser. |
| [setPrintFileName](#setPrintFileName-java.lang.String-) | Définit le nom de fichier à imprimer. |
| [setPrintRange](#setPrintRange-int-) | Définit les numéros de page que l'utilisateur a spécifiés pour l'impression. |
| [setPrintToFile](#setPrintToFile-boolean-) | Définit une valeur indiquant si la sortie d'impression est envoyée vers un fichier au lieu d'un port. |
| [setSelectedPages](#setSelectedPages-int:A-) | Définit le nombre de pages sélectionnées à imprimer. |
| [setToPage](#setToPage-int-) | Définit le numéro de la dernière page à imprimer. |

### PdfPrinterSettings {#PdfPrinterSettings--}
```
public PdfPrinterSettings()
```

Initialise une nouvelle instance de la classe PrinterSettings.

### canDuplex {#canDuplex--}
```
public boolean canDuplex()
```

Obtient une valeur indiquant si l'imprimante prend en charge l'impression recto verso.

**Returns:**
valeur booléenne

### createMeasurementGraphics {#createMeasurementGraphics--}
```
public Graphics2D createMeasurementGraphics()
```

Obtenir l'objet Graphics2D

**Returns:**
Objet Graphics2D

### createMeasurementGraphics {#createMeasurementGraphics-boolean-}
```
public Graphics2D createMeasurementGraphics(boolean value)
```

Obtenir l'objet Graphics2D

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

**Returns:**
Objet Graphics2D

### createMeasurementGraphics {#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-}
Obtenir l'objet Graphics2D

**Returns:**
Objet Graphics2D

### createMeasurementGraphics {#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-boolean-}
Obtenir l'objet Graphics2D

**Returns:**
Objet Graphics2D

### deepClone {#deepClone--}
```
public PdfPrinterSettings deepClone()
```

Obtenir l'objet cloné

**Returns:**
Objet PdfPrinterSettings

### getCopies {#getCopies--}
```
public short getCopies()
```

Obtient le nombre de copies du document à imprimer.

**Returns:**
nombre de copies

### getDefaultPageSettings {#getDefaultPageSettings--}
```
public PrintPageSettings getDefaultPageSettings()
```

Obtient les paramètres de page par défaut pour cette imprimante.

**Returns:**
paramètres de page par défaut

### getDuplex {#getDuplex--}
```
public int getDuplex()
```

Obtient ou définit le paramètre d'imprimante pour l'impression recto verso.

**Returns:**
valeur int @see DuplexKind

### getFromPage {#getFromPage--}
```
public int getFromPage()
```

Obtient ou définit le numéro de page de la première page à imprimer.

**Returns:**
valeur int

### getInstalledPrinters {#getInstalledPrinters--}
```
public static ArrayList < String > getInstalledPrinters()
```

Obtient les noms de toutes les imprimantes installées sur l'ordinateur.

**Returns:**
objet {@code ArrayList<String>}

### getLandscapeAngle {#getLandscapeAngle--}
```
public int getLandscapeAngle()
```

Obtient l'angle, en degrés, selon lequel l'orientation portrait est pivotée pour produire l'orientation paysage.

**Returns:**
valeur int

### getMaximumCopies {#getMaximumCopies--}
```
public int getMaximumCopies()
```

Obtient le nombre maximal de copies que l'imprimante permet à l'utilisateur d'imprimer en une fois.

**Returns:**
valeur int

### getMaximumPage {#getMaximumPage--}
```
public int getMaximumPage()
```

Obtient ou définit le maximum FromPage ou ToPage qui peut être sélectionné dans une boîte de dialogue d'impression.

**Returns:**
valeur int

### getMinimumPage {#getMinimumPage--}
```
public int getMinimumPage()
```

Obtient ou définit le minimum FromPage ou ToPage qui peut être sélectionné dans une boîte de dialogue d'impression.

**Returns:**
valeur int

### getPaperSizes {#getPaperSizes--}
```
public ArrayList < PrintPaperSize > getPaperSizes()
```

Obtient les formats de papier pris en charge par cette imprimante.

**Returns:**
objet {@code ArrayList<PrintPaperSize> }

### getPaperSources {#getPaperSources--}
```
public ArrayList < PrintPaperSource > getPaperSources()
```

Obtient les bacs d'alimentation papier disponibles sur l'imprimante.

**Returns:**
objet {@code ArrayList<PrintPaperSource> }

### getPrinterName {#getPrinterName--}
```
public String getPrinterName()
```

Obtient ou définit le nom de l'imprimante à utiliser.

**Returns:**
objet string

### getPrinterResolutions {#getPrinterResolutions--}
```
public com.aspose.ms.System.Drawing.Printing.PrinterSettings.PrinterResolutionCollection getPrinterResolutions()
```

Obtient toutes les résolutions prises en charge par cette imprimante.

**Returns:**
Objet PrinterResolutionCollection

### getPrinterSettings {#getPrinterSettings--}
```
public com.aspose.ms.System.Drawing.Printing.PrinterSettings getPrinterSettings()
```

Renvoie l'objet PrinterSettings

**Returns:**
Objet PrinterSettings

### getPrintFileName {#getPrintFileName--}
```
public String getPrintFileName()
```

Obtient ou définit le nom de fichier, lors de l'impression vers un fichier.

**Returns:**
objet string

### getPrintRange {#getPrintRange--}
```
public int getPrintRange()
```

Obtient ou définit les numéros de page que l'utilisateur a spécifiés pour l'impression.

**Returns:**
valeur int @see PdfPrintRange

### getSelectedPages {#getSelectedPages--}
```
public int[] getSelectedPages()
```

Obtient le nombre de pages sélectionnées à imprimer.

**Returns:**
tableau d'entiers pagesList @see PdfPrintRange

### getToPage {#getToPage--}
```
public int getToPage()
```

Obtient ou définit le numéro de la dernière page à imprimer.

**Returns:**
valeur int

### isCollate {#isCollate--}
```
public boolean isCollate()
```

Obtient ou définit une valeur indiquant si le document imprimé est assemblé.

**Returns:**
valeur booléenne

### isDefaultPrinter {#isDefaultPrinter--}
```
public boolean isDefaultPrinter()
```

Obtient une valeur indiquant si la propriété PrinterName désigne l'imprimante par défaut, sauf lorsque l'utilisateur définit explicitement PrinterName.

**Returns:**
valeur booléenne

### isDirectPrintingSupported {#isDirectPrintingSupported-com.aspose.pdf.ImageType-}
Obtient une valeur indiquant si l'imprimante est Supported DirectPrinting

### isDirectPrintingSupported {#isDirectPrintingSupported-java.lang.String-}
Obtient une valeur indiquant si l'imprimante est Supported DirectPrinting

### isPlotter {#isPlotter--}
```
public boolean isPlotter()
```

Obtient une valeur indiquant si l'imprimante est un traceur.

**Returns:**
valeur booléenne

### isPrintToFile {#isPrintToFile--}
```
public boolean isPrintToFile()
```

Obtient une valeur indiquant si la sortie d'impression est envoyée vers un fichier au lieu d'un port.

**Returns:**
valeur booléenne

### isSupportsColor {#isSupportsColor--}
```
public boolean isSupportsColor()
```

Obtient une valeur indiquant si cette imprimante prend en charge l'impression couleur.

**Returns:**
valeur booléenne

### isValid {#isValid--}
```
public boolean isValid()
```

Obtient une valeur indiquant si la propriété PrinterName désigne une imprimante valide.

**Returns:**
valeur booléenne

### setCollate {#setCollate-boolean-}
```
public void setCollate(boolean value)
```

Obtient ou définit une valeur indiquant si le document imprimé est assemblé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setCopies {#setCopies-short-}
```
public void setCopies(short value)
```

Définit le nombre de copies du document à imprimer.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | nombre de copies |

### setDuplex {#setDuplex-int-}
```
public void setDuplex(int value)
```

Obtient ou définit le paramètre d'imprimante pour l'impression recto verso.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int @see DuplexKind |

### setFromPage {#setFromPage-int-}
```
public void setFromPage(int value)
```

Obtient ou définit le numéro de page de la première page à imprimer.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setMaximumPage {#setMaximumPage-int-}
```
public void setMaximumPage(int value)
```

Obtient ou définit le maximum FromPage ou ToPage qui peut être sélectionné dans une boîte de dialogue d'impression.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setMinimumPage {#setMinimumPage-int-}
```
public void setMinimumPage(int value)
```

Obtient ou définit le minimum FromPage ou ToPage qui peut être sélectionné dans une boîte de dialogue d'impression.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setPrinterName {#setPrinterName-java.lang.String-}
Définit le nom de l'imprimante à utiliser.

### setPrintFileName {#setPrintFileName-java.lang.String-}
Définit le nom de fichier à imprimer.

### setPrintRange {#setPrintRange-int-}
```
public void setPrintRange(int value)
```

Définit les numéros de page que l'utilisateur a spécifiés pour l'impression.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | élément PdfPrintRange @see PdfPrintRange |

### setPrintToFile {#setPrintToFile-boolean-}
```
public void setPrintToFile(boolean value)
```

Définit une valeur indiquant si la sortie d'impression est envoyée vers un fichier au lieu d'un port.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setSelectedPages {#setSelectedPages-int:A-}
```
public void setSelectedPages(int[] pagesList)
```

Définit le nombre de pages sélectionnées à imprimer.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pagesList |  | tableau d'entiers @see PdfPrintRange |

### setToPage {#setToPage-int-}
```
public void setToPage(int value)
```

Définit le numéro de la dernière page à imprimer.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | élément PdfPrintRange @see PdfPrintRange |
