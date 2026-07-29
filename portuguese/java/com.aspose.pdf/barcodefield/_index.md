---
title: "BarcodeField"
linktitle: "BarcodeField"
second_title: "Referência da API Aspose.PDF para Java"
description: "Classe que representa um campo de código de barras."
type: docs
weight: 250
url: /pt/java/com.aspose.pdf/barcodefield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.Field, com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.TextBoxField, com.aspose.pdf.BarcodeField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public final class BarcodeField extends TextBoxField
```

Classe que representa um campo de código de barras.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [BarcodeField](#BarcodeField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Inicializa uma nova instância da classe {@code BarcodeField}. |
| [BarcodeField](#BarcodeField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Inicializa uma nova instância da classe {@code BarcodeField}. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getCaption](#getCaption--) | Obtém a legenda do objeto de código de barras. |
| [getECC](#getECC--) | Obtém um valor inteiro que representa o coeficiente de correção de erro. Para PDF417, deve estar entre 0 e 8. Para QRCode, deve estar entre 0 e 3 (0 para 'L', 1 para 'M', 2 para 'Q' e 3 para 'H'). |
| [getResolution](#getResolution--) | Obtém a resolução, em pontos por polegada (dpi), na qual o objeto de código de barras é renderizado. |
| [getSymbology](#getSymbology--) | Especifica qual tecnologia de código de barras ou glifo deve ser usada nesta anotação, veja {@code Symbology} para detalhes. |
| [getXSymHeight](#getXSymHeight--) | Obtém a distância vertical entre dois módulos de código de barras, medida em pixels. A proporção XSymHeight/XSymWidth deve ser um valor inteiro. Para PDF417, a faixa de proporção aceitável é de 1 a 4. Para QRCode e DataMatrix, essa proporção deve ser sempre 1 |
| [getXSymWidth](#getXSymWidth--) | Obtém a distância horizontal, em pixels, entre dois módulos de código de barras. |

### BarcodeField {#BarcodeField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Inicializa uma nova instância da classe {@code BarcodeField}.

### BarcodeField {#BarcodeField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Inicializa uma nova instância da classe {@code BarcodeField}.

### getCaption {#getCaption--}
```
public String getCaption()
```

Obtém a legenda do objeto de código de barras.

**Returns:**
valor String

### getECC {#getECC--}
```
public int getECC()
```

Obtém um valor inteiro que representa o coeficiente de correção de erro. Para PDF417, deve estar entre 0 e 8. Para QRCode, deve estar entre 0 e 3 (0 para 'L', 1 para 'M', 2 para 'Q' e 3 para 'H').

**Returns:**
valor int

### getResolution {#getResolution--}
```
public int getResolution()
```

Obtém a resolução, em pontos por polegada (dpi), na qual o objeto de código de barras é renderizado.

**Returns:**
valor int

### getSymbology {#getSymbology--}
```
public int getSymbology()
```

Especifica qual tecnologia de código de barras ou glifo deve ser usada nesta anotação, veja {@code Symbology} para detalhes.

**Returns:**
Elemento Symbology @see Symbology

### getXSymHeight {#getXSymHeight--}
```
public int getXSymHeight()
```

Obtém a distância vertical entre dois módulos de código de barras, medida em pixels. A proporção XSymHeight/XSymWidth deve ser um valor inteiro. Para PDF417, a faixa de proporção aceitável é de 1 a 4. Para QRCode e DataMatrix, essa proporção deve ser sempre 1

**Returns:**
valor int

### getXSymWidth {#getXSymWidth--}
```
public int getXSymWidth()
```

Obtém a distância horizontal, em pixels, entre dois módulos de código de barras.

**Returns:**
valor int
