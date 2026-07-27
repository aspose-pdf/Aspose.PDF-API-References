---
title: "PdfPrinterSettings"
linktitle: "PdfPrinterSettings"
second_title: "Referência da API Aspose.PDF para Java"
description: "Especifica informações sobre como um documento é impresso, incluindo a impressora que o imprime."
type: docs
weight: 50
url: /pt/java/com.aspose.pdf.printing/pdfprintersettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PdfPrinterSettings

```
public class PdfPrinterSettings extends Object
```

Especifica informações sobre como um documento é impresso, incluindo a impressora que o imprime.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [PdfPrinterSettings](#PdfPrinterSettings--) | Inicializa uma nova instância da classe PrinterSettings. |

## Métodos

| Método | Descrição |
| --- | --- |
| [canDuplex](#canDuplex--) | Obtém um valor que indica se a impressora suporta impressão duplex. |
| [createMeasurementGraphics](#createMeasurementGraphics--) | Obter objeto Graphics2D |
| [createMeasurementGraphics](#createMeasurementGraphics-boolean-) | Obter objeto Graphics2D |
| [createMeasurementGraphics](#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-) | Obter objeto Graphics2D |
| [createMeasurementGraphics](#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-boolean-) | Obter objeto Graphics2D |
| [deepClone](#deepClone--) | Obter objeto clonado |
| [getCopies](#getCopies--) | Obtém o número de cópias do documento a imprimir. |
| [getDefaultPageSettings](#getDefaultPageSettings--) | Obtém as configurações de página padrão para esta impressora. |
| [getDuplex](#getDuplex--) | Obtém ou define a configuração da impressora para impressão duplex. |
| [getFromPage](#getFromPage--) | Obtém ou define o número da página da primeira página a ser impressa. |
| [getInstalledPrinters](#getInstalledPrinters--) | Obtém os nomes de todas as impressoras instaladas no computador. |
| [getLandscapeAngle](#getLandscapeAngle--) | Obtém o ângulo, em graus, que a orientação retrato é girada para produzir a orientação paisagem. |
| [getMaximumCopies](#getMaximumCopies--) | Obtém o número máximo de cópias que a impressora permite ao usuário imprimir de uma vez. |
| [getMaximumPage](#getMaximumPage--) | Obtém ou define o máximo FromPage ou ToPage que pode ser selecionado em um PrintDialog. |
| [getMinimumPage](#getMinimumPage--) | Obtém ou define o mínimo FromPage ou ToPage que pode ser selecionado em um PrintDialog. |
| [getPaperSizes](#getPaperSizes--) | Obtém os tamanhos de papel suportados por esta impressora. |
| [getPaperSources](#getPaperSources--) | Obtém as bandejas de origem de papel disponíveis na impressora. |
| [getPrinterName](#getPrinterName--) | Obtém ou define o nome da impressora a ser usada. |
| [getPrinterResolutions](#getPrinterResolutions--) | Obtém todas as resoluções suportadas por esta impressora. |
| [getPrinterSettings](#getPrinterSettings--) | Retorna o objeto PrinterSettings |
| [getPrintFileName](#getPrintFileName--) | Obtém ou define o nome do arquivo ao imprimir para um arquivo. |
| [getPrintRange](#getPrintRange--) | Obtém ou define os números de página que o usuário especificou para impressão. |
| [getSelectedPages](#getSelectedPages--) | Obtém o número de páginas selecionadas para imprimir. |
| [getToPage](#getToPage--) | Obtém ou define o número da última página a ser impressa. |
| [isCollate](#isCollate--) | Obtém ou define um valor que indica se o documento impresso está agrupado. |
| [isDefaultPrinter](#isDefaultPrinter--) | Obtém um valor que indica se a propriedade PrinterName designa a impressora padrão, exceto quando o usuário define explicitamente o PrinterName. |
| [isDirectPrintingSupported](#isDirectPrintingSupported-com.aspose.pdf.ImageType-) | Obtém um valor que indica se a impressora suporta DirectPrinting. |
| [isDirectPrintingSupported](#isDirectPrintingSupported-java.lang.String-) | Obtém um valor que indica se a impressora suporta DirectPrinting. |
| [isPlotter](#isPlotter--) | Obtém um valor que indica se a impressora é um plotter. |
| [isPrintToFile](#isPrintToFile--) | Obtém um valor que indica se a saída de impressão é enviada para um arquivo em vez de uma porta. |
| [isSupportsColor](#isSupportsColor--) | Obtém um valor que indica se esta impressora suporta impressão colorida. |
| [isValid](#isValid--) | Obtém um valor que indica se a propriedade PrinterName designa uma impressora válida. |
| [setCollate](#setCollate-boolean-) | Obtém ou define um valor que indica se o documento impresso está agrupado. |
| [setCopies](#setCopies-short-) | Define o número de cópias do documento a ser impresso. |
| [setDuplex](#setDuplex-int-) | Obtém ou define a configuração da impressora para impressão duplex. |
| [setFromPage](#setFromPage-int-) | Obtém ou define o número da página da primeira página a ser impressa. |
| [setMaximumPage](#setMaximumPage-int-) | Obtém ou define o máximo FromPage ou ToPage que pode ser selecionado em um PrintDialog. |
| [setMinimumPage](#setMinimumPage-int-) | Obtém ou define o mínimo FromPage ou ToPage que pode ser selecionado em um PrintDialog. |
| [setPrinterName](#setPrinterName-java.lang.String-) | Define o nome da impressora a ser usada. |
| [setPrintFileName](#setPrintFileName-java.lang.String-) | Define o nome do arquivo a ser impresso. |
| [setPrintRange](#setPrintRange-int-) | Define os números das páginas que o usuário especificou para impressão. |
| [setPrintToFile](#setPrintToFile-boolean-) | Define um valor que indica se a saída de impressão é enviada para um arquivo em vez de uma porta. |
| [setSelectedPages](#setSelectedPages-int:A-) | Define o número de páginas selecionadas para impressão. |
| [setToPage](#setToPage-int-) | Define o número da última página a ser impressa. |

### PdfPrinterSettings {#PdfPrinterSettings--}
```
public PdfPrinterSettings()
```

Inicializa uma nova instância da classe PrinterSettings.

### canDuplex {#canDuplex--}
```
public boolean canDuplex()
```

Obtém um valor que indica se a impressora suporta impressão duplex.

**Returns:**
valor booleano

### createMeasurementGraphics {#createMeasurementGraphics--}
```
public Graphics2D createMeasurementGraphics()
```

Obter objeto Graphics2D

**Returns:**
Objeto Graphics2D

### createMeasurementGraphics {#createMeasurementGraphics-boolean-}
```
public Graphics2D createMeasurementGraphics(boolean value)
```

Obter objeto Graphics2D

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

**Returns:**
Objeto Graphics2D

### createMeasurementGraphics {#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-}
Obter objeto Graphics2D

**Returns:**
Objeto Graphics2D

### createMeasurementGraphics {#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-boolean-}
Obter objeto Graphics2D

**Returns:**
Objeto Graphics2D

### deepClone {#deepClone--}
```
public PdfPrinterSettings deepClone()
```

Obter objeto clonado

**Returns:**
Objeto PdfPrinterSettings

### getCopies {#getCopies--}
```
public short getCopies()
```

Obtém o número de cópias do documento a imprimir.

**Returns:**
número de cópias

### getDefaultPageSettings {#getDefaultPageSettings--}
```
public PrintPageSettings getDefaultPageSettings()
```

Obtém as configurações de página padrão para esta impressora.

**Returns:**
configurações de página padrão

### getDuplex {#getDuplex--}
```
public int getDuplex()
```

Obtém ou define a configuração da impressora para impressão duplex.

**Returns:**
valor int @see DuplexKind

### getFromPage {#getFromPage--}
```
public int getFromPage()
```

Obtém ou define o número da página da primeira página a ser impressa.

**Returns:**
valor int

### getInstalledPrinters {#getInstalledPrinters--}
```
public static ArrayList < String > getInstalledPrinters()
```

Obtém os nomes de todas as impressoras instaladas no computador.

**Returns:**
objeto {@code ArrayList<String>}

### getLandscapeAngle {#getLandscapeAngle--}
```
public int getLandscapeAngle()
```

Obtém o ângulo, em graus, que a orientação retrato é girada para produzir a orientação paisagem.

**Returns:**
valor int

### getMaximumCopies {#getMaximumCopies--}
```
public int getMaximumCopies()
```

Obtém o número máximo de cópias que a impressora permite ao usuário imprimir de uma vez.

**Returns:**
valor int

### getMaximumPage {#getMaximumPage--}
```
public int getMaximumPage()
```

Obtém ou define o máximo FromPage ou ToPage que pode ser selecionado em um PrintDialog.

**Returns:**
valor int

### getMinimumPage {#getMinimumPage--}
```
public int getMinimumPage()
```

Obtém ou define o mínimo FromPage ou ToPage que pode ser selecionado em um PrintDialog.

**Returns:**
valor int

### getPaperSizes {#getPaperSizes--}
```
public ArrayList < PrintPaperSize > getPaperSizes()
```

Obtém os tamanhos de papel suportados por esta impressora.

**Returns:**
objeto {@code ArrayList<PrintPaperSize> }

### getPaperSources {#getPaperSources--}
```
public ArrayList < PrintPaperSource > getPaperSources()
```

Obtém as bandejas de origem de papel disponíveis na impressora.

**Returns:**
objeto {@code ArrayList<PrintPaperSource> }

### getPrinterName {#getPrinterName--}
```
public String getPrinterName()
```

Obtém ou define o nome da impressora a ser usada.

**Returns:**
objeto string

### getPrinterResolutions {#getPrinterResolutions--}
```
public com.aspose.ms.System.Drawing.Printing.PrinterSettings.PrinterResolutionCollection getPrinterResolutions()
```

Obtém todas as resoluções suportadas por esta impressora.

**Returns:**
objeto PrinterResolutionCollection

### getPrinterSettings {#getPrinterSettings--}
```
public com.aspose.ms.System.Drawing.Printing.PrinterSettings getPrinterSettings()
```

Retorna o objeto PrinterSettings

**Returns:**
objeto PrinterSettings

### getPrintFileName {#getPrintFileName--}
```
public String getPrintFileName()
```

Obtém ou define o nome do arquivo ao imprimir para um arquivo.

**Returns:**
objeto string

### getPrintRange {#getPrintRange--}
```
public int getPrintRange()
```

Obtém ou define os números de página que o usuário especificou para impressão.

**Returns:**
valor int @see PdfPrintRange

### getSelectedPages {#getSelectedPages--}
```
public int[] getSelectedPages()
```

Obtém o número de páginas selecionadas para imprimir.

**Returns:**
array int pagesList @see PdfPrintRange

### getToPage {#getToPage--}
```
public int getToPage()
```

Obtém ou define o número da última página a ser impressa.

**Returns:**
valor int

### isCollate {#isCollate--}
```
public boolean isCollate()
```

Obtém ou define um valor que indica se o documento impresso está agrupado.

**Returns:**
valor booleano

### isDefaultPrinter {#isDefaultPrinter--}
```
public boolean isDefaultPrinter()
```

Obtém um valor que indica se a propriedade PrinterName designa a impressora padrão, exceto quando o usuário define explicitamente o PrinterName.

**Returns:**
valor booleano

### isDirectPrintingSupported {#isDirectPrintingSupported-com.aspose.pdf.ImageType-}
Obtém um valor que indica se a impressora suporta DirectPrinting.

### isDirectPrintingSupported {#isDirectPrintingSupported-java.lang.String-}
Obtém um valor que indica se a impressora suporta DirectPrinting.

### isPlotter {#isPlotter--}
```
public boolean isPlotter()
```

Obtém um valor que indica se a impressora é um plotter.

**Returns:**
valor booleano

### isPrintToFile {#isPrintToFile--}
```
public boolean isPrintToFile()
```

Obtém um valor que indica se a saída de impressão é enviada para um arquivo em vez de uma porta.

**Returns:**
valor booleano

### isSupportsColor {#isSupportsColor--}
```
public boolean isSupportsColor()
```

Obtém um valor que indica se esta impressora suporta impressão colorida.

**Returns:**
valor booleano

### isValid {#isValid--}
```
public boolean isValid()
```

Obtém um valor que indica se a propriedade PrinterName designa uma impressora válida.

**Returns:**
valor booleano

### setCollate {#setCollate-boolean-}
```
public void setCollate(boolean value)
```

Obtém ou define um valor que indica se o documento impresso está agrupado.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setCopies {#setCopies-short-}
```
public void setCopies(short value)
```

Define o número de cópias do documento a ser impresso.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | número de cópias |

### setDuplex {#setDuplex-int-}
```
public void setDuplex(int value)
```

Obtém ou define a configuração da impressora para impressão duplex.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int @see DuplexKind |

### setFromPage {#setFromPage-int-}
```
public void setFromPage(int value)
```

Obtém ou define o número da página da primeira página a ser impressa.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setMaximumPage {#setMaximumPage-int-}
```
public void setMaximumPage(int value)
```

Obtém ou define o máximo FromPage ou ToPage que pode ser selecionado em um PrintDialog.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setMinimumPage {#setMinimumPage-int-}
```
public void setMinimumPage(int value)
```

Obtém ou define o mínimo FromPage ou ToPage que pode ser selecionado em um PrintDialog.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setPrinterName {#setPrinterName-java.lang.String-}
Define o nome da impressora a ser usada.

### setPrintFileName {#setPrintFileName-java.lang.String-}
Define o nome do arquivo a ser impresso.

### setPrintRange {#setPrintRange-int-}
```
public void setPrintRange(int value)
```

Define os números das páginas que o usuário especificou para impressão.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | elemento PdfPrintRange @see PdfPrintRange |

### setPrintToFile {#setPrintToFile-boolean-}
```
public void setPrintToFile(boolean value)
```

Define um valor que indica se a saída de impressão é enviada para um arquivo em vez de uma porta.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setSelectedPages {#setSelectedPages-int:A-}
```
public void setSelectedPages(int[] pagesList)
```

Define o número de páginas selecionadas para impressão.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| pagesList |  | array int @see PdfPrintRange |

### setToPage {#setToPage-int-}
```
public void setToPage(int value)
```

Define o número da última página a ser impressa.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | elemento PdfPrintRange @see PdfPrintRange |
