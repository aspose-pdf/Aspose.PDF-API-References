---
title: "PrintPageSettings"
linktitle: "PrintPageSettings"
second_title: "Referência da API Aspose.PDF para Java"
description: "Especifica configurações que se aplicam a uma única página impressa."
type: docs
weight: 90
url: /pt/java/com.aspose.pdf.printing/printpagesettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PrintPageSettings

```
public class PrintPageSettings extends Object
```

Especifica configurações que se aplicam a uma única página impressa.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [PrintPageSettings](#PrintPageSettings--) | Inicializa uma nova instância da classe PageSettings usando a impressora padrão. |
| [PrintPageSettings](#PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | Inicializa uma nova instância da classe PageSettings usando a impressora padrão. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getBounds](#getBounds--) | Obtém o tamanho da página, levando em conta a orientação da página especificada pela propriedade Landscape. |
| [getHardMarginX](#getHardMarginX--) | Obtém a coordenada x, em centésimos de polegada, da margem fixa à esquerda da página. |
| [getHardMarginY](#getHardMarginY--) | Obtém a coordenada y, em centésimos de polegada, da margem fixa no topo da página. |
| [getMargins](#getMargins--) | Obtém as margens desta página. |
| [getPageSettings](#getPageSettings--) | Obtém as Configurações da Página. |
| [getPaperSize](#getPaperSize--) | Obtém o tamanho do papel para a página. |
| [getPaperSource](#getPaperSource--) | Obtém a fonte de papel da página; por exemplo, a bandeja superior da impressora. |
| [getPrintableArea](#getPrintableArea--) | Obtém os limites da área imprimível da página para a impressora. |
| [getPrinterResolution](#getPrinterResolution--) | Obtém a resolução da impressora para a página. |
| [getPrinterSettings](#getPrinterSettings--) | Obtém as configurações da impressora associadas à página. |
| [isColor](#isColor--) | Obtém ou define um valor que indica se a página deve ser impressa em cores. |
| [isLandscape](#isLandscape--) | Obtém ou define um valor que indica se a página é impressa em orientação paisagem ou retrato. |
| [setColor](#setColor-boolean-) | Obtém ou define um valor que indica se a página deve ser impressa em cores. |
| [setLandscape](#setLandscape-boolean-) | Obtém ou define um valor que indica se a página é impressa em orientação paisagem ou retrato. |
| [setMargins](#setMargins-com.aspose.pdf.printing.PrinterMargins-) | Define as margens desta página. |
| [setPaperSize](#setPaperSize-com.aspose.pdf.printing.PrintPaperSize-) | Define o tamanho do papel para a página. |
| [setPaperSource](#setPaperSource-com.aspose.pdf.printing.PrintPaperSource-) | Define a fonte de papel da página; por exemplo, a bandeja superior da impressora. |
| [setPrinterResolution](#setPrinterResolution-com.aspose.pdf.printing.PdfPrinterResolution-) | Define a resolução da impressora para a página. |
| [setPrinterSettings](#setPrinterSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | Define as configurações da impressora associadas à página. |

### PrintPageSettings {#PrintPageSettings--}
```
public PrintPageSettings()
```

Inicializa uma nova instância da classe PageSettings usando a impressora padrão.

### PrintPageSettings {#PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
Inicializa uma nova instância da classe PageSettings usando a impressora padrão.

### getBounds {#getBounds--}
```
public Rectangle getBounds()
```

Obtém o tamanho da página, levando em conta a orientação da página especificada pela propriedade Landscape.

**Returns:**
objeto Rectangle

### getHardMarginX {#getHardMarginX--}
```
public float getHardMarginX()
```

Obtém a coordenada x, em centésimos de polegada, da margem fixa à esquerda da página.

**Returns:**
valor float

### getHardMarginY {#getHardMarginY--}
```
public float getHardMarginY()
```

Obtém a coordenada y, em centésimos de polegada, da margem fixa no topo da página.

**Returns:**
valor float

### getMargins {#getMargins--}
```
public PrinterMargins getMargins()
```

Obtém as margens desta página.

**Returns:**
Objeto PrinterMargins

### getPageSettings {#getPageSettings--}
```
public com.aspose.ms.System.Drawing.Printing.PageSettings getPageSettings()
```

Obtém as Configurações da Página.

**Returns:**
Objeto PageSettings

### getPaperSize {#getPaperSize--}
```
public PrintPaperSize getPaperSize()
```

Obtém o tamanho do papel para a página.

**Returns:**
Objeto PrintPaperSize

### getPaperSource {#getPaperSource--}
```
public PrintPaperSource getPaperSource()
```

Obtém a fonte de papel da página; por exemplo, a bandeja superior da impressora.

**Returns:**
Objeto PrintPaperSource

### getPrintableArea {#getPrintableArea--}
```
public Rectangle getPrintableArea()
```

Obtém os limites da área imprimível da página para a impressora.

**Returns:**
objeto Rectangle

### getPrinterResolution {#getPrinterResolution--}
```
public PdfPrinterResolution getPrinterResolution()
```

Obtém a resolução da impressora para a página.

**Returns:**
Objeto PdfPrinterResolution

### getPrinterSettings {#getPrinterSettings--}
```
public PdfPrinterSettings getPrinterSettings()
```

Obtém as configurações da impressora associadas à página.

**Returns:**
Objeto PdfPrinterSettings

### isColor {#isColor--}
```
public boolean isColor()
```

Obtém ou define um valor que indica se a página deve ser impressa em cores.

**Returns:**
valor booleano

### isLandscape {#isLandscape--}
```
public boolean isLandscape()
```

Obtém ou define um valor que indica se a página é impressa em orientação paisagem ou retrato.

**Returns:**
valor booleano

### setColor {#setColor-boolean-}
```
public void setColor(boolean value)
```

Obtém ou define um valor que indica se a página deve ser impressa em cores.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setLandscape {#setLandscape-boolean-}
```
public void setLandscape(boolean value)
```

Obtém ou define um valor que indica se a página é impressa em orientação paisagem ou retrato.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setMargins {#setMargins-com.aspose.pdf.printing.PrinterMargins-}
Define as margens desta página.

### setPaperSize {#setPaperSize-com.aspose.pdf.printing.PrintPaperSize-}
Define o tamanho do papel para a página.

### setPaperSource {#setPaperSource-com.aspose.pdf.printing.PrintPaperSource-}
Define a fonte de papel da página; por exemplo, a bandeja superior da impressora.

### setPrinterResolution {#setPrinterResolution-com.aspose.pdf.printing.PdfPrinterResolution-}
Define a resolução da impressora para a página.

### setPrinterSettings {#setPrinterSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
Define as configurações da impressora associadas à página.
