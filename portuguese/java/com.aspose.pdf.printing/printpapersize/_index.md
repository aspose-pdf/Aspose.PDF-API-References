---
title: "PrintPaperSize"
linktitle: "PrintPaperSize"
second_title: "Referência da API Aspose.PDF para Java"
description: "Especifica o tamanho de uma folha de papel."
type: docs
weight: 100
url: /pt/java/com.aspose.pdf.printing/printpapersize/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PrintPaperSize

```
public class PrintPaperSize extends Object
```

Especifica o tamanho de uma folha de papel.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [PrintPaperSize](#PrintPaperSize--) | Inicializa uma nova instância da classe PaperSize. |
| [PrintPaperSize](#PrintPaperSize-int-java.lang.String-int-int-) | Inicializa uma nova instância da classe PaperSize. |
| [PrintPaperSize](#PrintPaperSize-java.lang.String-int-int-) | Inicializa uma nova instância da classe PaperSize. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getHeight](#getHeight--) | Obtém ou define a altura do papel, em centésimos de polegada. |
| [getKind](#getKind--) | Obtém o tipo de papel. |
| [getPaperName](#getPaperName--) | Obtém ou define o nome do tipo de papel. |
| [getRawKind](#getRawKind--) | Obtém ou define um inteiro que representa um dos valores de PaperSize ou um valor personalizado. |
| [getWidth](#getWidth--) | Obtém ou define a largura do papel, em centésimos de polegada. |
| [setHeight](#setHeight-int-) | Obtém ou define a altura do papel, em centésimos de polegada. |
| [setPaperName](#setPaperName-java.lang.String-) | Obtém o nome do tipo de papel. |
| [setWidth](#setWidth-int-) | Define a largura do papel, em centésimos de polegada. |
| [toNativePaperSize](#toNativePaperSize-com.aspose.pdf.printing.PrintPaperSize-) | Converte {@link PaperSize} para System.Drawing.Printing.PaperSize específico do Windows. |
| [toString](#toString--) | Obtém o nome desta instância. |

### PrintPaperSize {#PrintPaperSize--}
```
public PrintPaperSize()
```

Inicializa uma nova instância da classe PaperSize.

### PrintPaperSize {#PrintPaperSize-int-java.lang.String-int-int-}
Inicializa uma nova instância da classe PaperSize.

### PrintPaperSize {#PrintPaperSize-java.lang.String-int-int-}
Inicializa uma nova instância da classe PaperSize.

### getHeight {#getHeight--}
```
public int getHeight()
```

Obtém ou define a altura do papel, em centésimos de polegada.

**Returns:**
valor int

### getKind {#getKind--}
```
public int getKind()
```

Obtém o tipo de papel.

**Returns:**
int value @see PrinterPaperKind

### getPaperName {#getPaperName--}
```
public String getPaperName()
```

Obtém ou define o nome do tipo de papel.

**Returns:**
valor String

### getRawKind {#getRawKind--}
```
public int getRawKind()
```

Obtém ou define um inteiro que representa um dos valores de PaperSize ou um valor personalizado.

**Returns:**
valor int

### getWidth {#getWidth--}
```
public int getWidth()
```

Obtém ou define a largura do papel, em centésimos de polegada.

**Returns:**
valor int

### setHeight {#setHeight-int-}
```
public void setHeight(int value)
```

Obtém ou define a altura do papel, em centésimos de polegada.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setPaperName {#setPaperName-java.lang.String-}
Obtém o nome do tipo de papel.

### setWidth {#setWidth-int-}
```
public void setWidth(int value)
```

Define a largura do papel, em centésimos de polegada.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### toNativePaperSize {#toNativePaperSize-com.aspose.pdf.printing.PrintPaperSize-}
Converte {@link PaperSize} para System.Drawing.Printing.PaperSize específico do Windows.

### toString {#toString--}
```
public String toString()
```

Obtém o nome desta instância.

**Returns:**
valor String
