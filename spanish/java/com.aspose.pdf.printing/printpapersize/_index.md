---
title: "PrintPaperSize"
linktitle: "PrintPaperSize"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Especifica el tamaño de una hoja de papel."
type: docs
weight: 100
url: /es/java/com.aspose.pdf.printing/printpapersize/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PrintPaperSize

```
public class PrintPaperSize extends Object
```

Especifica el tamaño de una hoja de papel.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PrintPaperSize](#PrintPaperSize--) | Inicializa una nueva instancia de la clase PaperSize. |
| [PrintPaperSize](#PrintPaperSize-int-java.lang.String-int-int-) | Inicializa una nueva instancia de la clase PaperSize. |
| [PrintPaperSize](#PrintPaperSize-java.lang.String-int-int-) | Inicializa una nueva instancia de la clase PaperSize. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getHeight](#getHeight--) | Obtiene o establece la altura del papel, en centésimas de pulgada. |
| [getKind](#getKind--) | Obtiene el tipo de papel. |
| [getPaperName](#getPaperName--) | Obtiene o establece el nombre del tipo de papel. |
| [getRawKind](#getRawKind--) | Obtiene o establece un entero que representa uno de los valores de PaperSize o un valor personalizado. |
| [getWidth](#getWidth--) | Obtiene o establece el ancho del papel, en centésimas de pulgada. |
| [setHeight](#setHeight-int-) | Obtiene o establece la altura del papel, en centésimas de pulgada. |
| [setPaperName](#setPaperName-java.lang.String-) | Obtiene el nombre del tipo de papel. |
| [setWidth](#setWidth-int-) | Establece el ancho del papel, en centésimas de pulgada. |
| [toNativePaperSize](#toNativePaperSize-com.aspose.pdf.printing.PrintPaperSize-) | Convierte {@link PaperSize} a System.Drawing.Printing.PaperSize específico de Windows. |
| [toString](#toString--) | Obtiene el nombre de esta instancia. |

### PrintPaperSize {#PrintPaperSize--}
```
public PrintPaperSize()
```

Inicializa una nueva instancia de la clase PaperSize.

### PrintPaperSize {#PrintPaperSize-int-java.lang.String-int-int-}
Inicializa una nueva instancia de la clase PaperSize.

### PrintPaperSize {#PrintPaperSize-java.lang.String-int-int-}
Inicializa una nueva instancia de la clase PaperSize.

### getHeight {#getHeight--}
```
public int getHeight()
```

Obtiene o establece la altura del papel, en centésimas de pulgada.

**Returns:**
valor int

### getKind {#getKind--}
```
public int getKind()
```

Obtiene el tipo de papel.

**Returns:**
valor int @see PrinterPaperKind

### getPaperName {#getPaperName--}
```
public String getPaperName()
```

Obtiene o establece el nombre del tipo de papel.

**Returns:**
valor String

### getRawKind {#getRawKind--}
```
public int getRawKind()
```

Obtiene o establece un entero que representa uno de los valores de PaperSize o un valor personalizado.

**Returns:**
valor int

### getWidth {#getWidth--}
```
public int getWidth()
```

Obtiene o establece el ancho del papel, en centésimas de pulgada.

**Returns:**
valor int

### setHeight {#setHeight-int-}
```
public void setHeight(int value)
```

Obtiene o establece la altura del papel, en centésimas de pulgada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setPaperName {#setPaperName-java.lang.String-}
Obtiene el nombre del tipo de papel.

### setWidth {#setWidth-int-}
```
public void setWidth(int value)
```

Establece el ancho del papel, en centésimas de pulgada.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### toNativePaperSize {#toNativePaperSize-com.aspose.pdf.printing.PrintPaperSize-}
Convierte {@link PaperSize} a System.Drawing.Printing.PaperSize específico de Windows.

### toString {#toString--}
```
public String toString()
```

Obtiene el nombre de esta instancia.

**Returns:**
valor String
