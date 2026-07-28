---
title: "PageNumber"
linktitle: "PageNumber"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa un formato de número de página que incluye un índice, el número total de páginas y un delimitador."
type: docs
weight: 150
url: /es/java/com.aspose.pdf.artifacts.pagination/pagenumber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.artifacts.pagination.PageNumber

```
public final class PageNumber extends Object
```

Representa un formato de número de página que incluye un índice, el número total de páginas y un delimitador.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PageNumber](#PageNumber--) |  |

## Métodos

| Método | Descripción |
| --- | --- |
| [getDelimiter](#getDelimiter--) | Obtiene o establece el delimitador usado en el formato del número de página. La cadena formateada se actualizará según el delimitador especificado. |
| [getIndex](#getIndex--) | Obtiene o establece el componente de índice de página del formato del número de página. La cadena formateada incluirá un marcador de posición para el índice de página. |
| [getOffset](#getOffset--) | Obtiene o establece el desplazamiento que se añadirá al índice de página. |
| [getPageNumberString](#getPageNumberString-int-int-) | Devuelve una cadena formateada que representa el número de página según la configuración actual. |
| [getTotalNum](#getTotalNum--) | Obtiene o establece el componente del número total de páginas del formato del número de página. La cadena formateada incluirá un marcador de posición para el número total de páginas. |
| [setDelimiter](#setDelimiter-java.lang.String-) | Obtiene o establece el delimitador usado en el formato del número de página. La cadena formateada se actualizará según el delimitador especificado. |
| [setIndex](#setIndex-com.aspose.pdf.artifacts.pagination.PageNumber.PageIndex-) | Obtiene o establece el componente de índice de página del formato del número de página. |
| [setOffset](#setOffset-int-) | Obtiene o establece el desplazamiento que se añadirá al índice de página. |
| [setTotalNum](#setTotalNum-com.aspose.pdf.artifacts.pagination.PageNumber.PageTotalNum-) | Obtiene o establece el componente del número total de páginas del formato del número de página. |

### PageNumber {#PageNumber--}
```
public PageNumber()
```



### getDelimiter {#getDelimiter--}
```
public final String getDelimiter()
```

Obtiene o establece el delimitador usado en el formato del número de página. La cadena formateada se actualizará según el delimitador especificado.

**Returns:**
valor String

### getIndex {#getIndex--}
```
public final PageNumber.PageIndex getIndex()
```

Obtiene o establece el componente de índice de página del formato del número de página. La cadena formateada incluirá un marcador de posición para el índice de página.

**Returns:**
instancia de PageIndex

### getOffset {#getOffset--}
```
public final int getOffset()
```

Obtiene o establece el desplazamiento que se añadirá al índice de página.

**Returns:**
valor int

### getPageNumberString {#getPageNumberString-int-int-}
```
public final String getPageNumberString(int pageNumber, int count)
```

Devuelve una cadena formateada que representa el número de página según la configuración actual.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageNumber |  | El número de página actual. |
| conteo |  | El número total de páginas. |

**Returns:**
Una cadena de número de página formateada.

### getTotalNum {#getTotalNum--}
```
public final PageNumber.PageTotalNum getTotalNum()
```

Obtiene o establece el componente del número total de páginas del formato del número de página. La cadena formateada incluirá un marcador de posición para el número total de páginas.

**Returns:**
instancia de PageTotalNum

### setDelimiter {#setDelimiter-java.lang.String-}
Obtiene o establece el delimitador usado en el formato del número de página. La cadena formateada se actualizará según el delimitador especificado.

### setIndex {#setIndex-com.aspose.pdf.artifacts.pagination.PageNumber.PageIndex-}
Obtiene o establece el componente de índice de página del formato del número de página.

### setOffset {#setOffset-int-}
```
public final void setOffset(int value)
```

Obtiene o establece el desplazamiento que se añadirá al índice de página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setTotalNum {#setTotalNum-com.aspose.pdf.artifacts.pagination.PageNumber.PageTotalNum-}
Obtiene o establece el componente del número total de páginas del formato del número de página.
