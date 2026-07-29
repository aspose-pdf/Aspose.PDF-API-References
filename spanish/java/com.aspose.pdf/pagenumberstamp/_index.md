---
title: "PageNumberStamp"
linktitle: "PageNumberStamp"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa el sello de número de página y se usa para numerar páginas."
type: docs
weight: 3440
url: /es/java/com.aspose.pdf/pagenumberstamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp com.aspose.pdf.TextStamp com.aspose.pdf.PageNumberStamp, com.aspose.pdf.Stamp, com.aspose.pdf.TextStamp com.aspose.pdf.PageNumberStamp, com.aspose.pdf.TextStamp, com.aspose.pdf.PageNumberStamp

```
public final class PageNumberStamp extends TextStamp
```

Representa el sello de número de página y se usa para numerar páginas.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PageNumberStamp](#PageNumberStamp--) | Inicializa una nueva instancia de la clase {@code PageNumberStamp}. El formato se establece en "#". |
| [PageNumberStamp](#PageNumberStamp-com.aspose.pdf.facades.FormattedText-) | Inicializa una nueva instancia de la clase {@code PageNumberStamp}. El formato se establece en "#". |
| [PageNumberStamp](#PageNumberStamp-java.lang.String-) | Inicializa una nueva instancia de la clase {@code PageNumberStamp}. El formato se establece en "#". |

## Métodos

| Método | Descripción |
| --- | --- |
| [getFormat](#getFormat--) | Obtiene el valor String para estampar números de página. El valor debe incluir el carácter '#' que se reemplaza con el número de página durante el proceso de estampado. |
| [getNumberingStyle](#getNumberingStyle--) | Estilo de numeración que usa este sello. |
| [getStartingNumber](#getStartingNumber--) | Obtiene el valor del número de página inicial. Las demás páginas se numerarán a partir de este valor. |
| [put](#put-com.aspose.pdf.Page-) | Agrega el número de página. |
| [setFormat](#setFormat-java.lang.String-) | Establece el valor de cadena para estampar los números de página. El valor debe incluir el carácter '#' que se reemplaza con el número de página durante el proceso de estampado. |
| [setNumberingStyle](#setNumberingStyle-com.aspose.pdf.NumberingStyle-) | Estilo de numeración que usa este sello. |
| [setStartingNumber](#setStartingNumber-int-) | Establece el valor del número de página inicial. Las demás páginas se numerarán a partir de este valor. |

### PageNumberStamp {#PageNumberStamp--}
```
public PageNumberStamp()
```

Inicializa una nueva instancia de la clase {@code PageNumberStamp}. El formato se establece en "#".

### PageNumberStamp {#PageNumberStamp-com.aspose.pdf.facades.FormattedText-}
Inicializa una nueva instancia de la clase {@code PageNumberStamp}. El formato se establece en "#".

### PageNumberStamp {#PageNumberStamp-java.lang.String-}
Inicializa una nueva instancia de la clase {@code PageNumberStamp}. El formato se establece en "#".

### getFormat {#getFormat--}
```
public String getFormat()
```

Obtiene el valor String para estampar números de página. El valor debe incluir el carácter '#' que se reemplaza con el número de página durante el proceso de estampado.

**Returns:**
valor String

### getNumberingStyle {#getNumberingStyle--}
```
public NumberingStyle getNumberingStyle()
```

Estilo de numeración que usa este sello.

**Returns:**
Valor de NumberingStyle @see NumberingStyle

### getStartingNumber {#getStartingNumber--}
```
public int getStartingNumber()
```

Obtiene el valor del número de página inicial. Las demás páginas se numerarán a partir de este valor.

**Returns:**
valor int

### put {#put-com.aspose.pdf.Page-}
Agrega el número de página.

### setFormat {#setFormat-java.lang.String-}
Establece el valor de cadena para estampar los números de página. El valor debe incluir el carácter '#' que se reemplaza con el número de página durante el proceso de estampado.

### setNumberingStyle {#setNumberingStyle-com.aspose.pdf.NumberingStyle-}
Estilo de numeración que usa este sello.

### setStartingNumber {#setStartingNumber-int-}
```
public void setStartingNumber(int value)
```

Establece el valor del número de página inicial. Las demás páginas se numerarán a partir de este valor.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |
