---
title: "Encabezado"
linktitle: "Encabezado"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa el encabezado."
type: docs
weight: 1890
url: /es/java/com.aspose.pdf/heading/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.TextFragment com.aspose.pdf.Heading, com.aspose.pdf.BaseParagraph, com.aspose.pdf.TextFragment com.aspose.pdf.Heading, com.aspose.pdf.TextFragment, com.aspose.pdf.Heading

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Heading extends TextFragment
```

Representa el encabezado.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [Heading](#Heading--) | Solo para uso interno |
| [Heading](#Heading-int-) | Inicializa una nueva instancia de la clase Cell. |

## Métodos

| Método | Descripción |
| --- | --- |
| [cloneWithSegments](#cloneWithSegments--) | Clona el encabezado con todos los segmentos. |
| [deepClone](#deepClone--) | Clona el encabezado. |
| [getDestinationPage](#getDestinationPage--) | Obtiene la página de destino. |
| [getLevel](#getLevel--) | Obtiene el nivel. |
| [getStartNumber](#getStartNumber--) | Obtiene el número de inicio del encabezado. |
| [getStyle](#getStyle--) | Obtiene o establece el estilo. |
| [getTocPage](#getTocPage--) | Obtiene la página que contiene este encabezado. |
| [getTop](#getTop--) | Obtiene el valor Y superior de este encabezado (para uso interno). |
| [getUserLabel](#getUserLabel--) | Obtiene o establece la etiqueta de usuario. |
| [isAutoSequence](#isAutoSequence--) | Obtiene si el encabezado debe numerarse automáticamente. |
| [isInList](#isInList--) | Obtiene si el encabezado debe estar en la lista de índice. |
| [setAutoSequence](#setAutoSequence-boolean-) | Establece si el encabezado debe numerarse automáticamente. |
| [setDestinationPage](#setDestinationPage-com.aspose.pdf.Page-) | Establece la página de destino. |
| [setInList](#setInList-boolean-) | Establece si el encabezado debe estar en la lista de índice. |
| [setLevel](#setLevel-int-) | establece el nivel. |
| [setStartNumber](#setStartNumber-int-) | Obtiene el número de inicio del encabezado. Valor: El startNumber. |
| [setStyle](#setStyle-com.aspose.pdf.NumberingStyle-) | establece o establece el estilo. |
| [setTocPage](#setTocPage-com.aspose.pdf.Page-) | Establece la página que contiene este encabezado. |
| [setTop](#setTop-double-) | establece la coordenada Y superior de estos encabezados (para uso interno). |
| [setUserLabel](#setUserLabel-com.aspose.pdf.TextSegment-) | Obtiene o establece la etiqueta de usuario. |

### Heading {#Heading--}
```
public Heading()
```

Solo para uso interno

### Heading {#Heading-int-}
```
public Heading(int level)
```

Inicializa una nueva instancia de la clase Cell.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| level |  | El nivel de los encabezados. |

### cloneWithSegments {#cloneWithSegments--}
```
public Object cloneWithSegments()
```

Clona el encabezado con todos los segmentos.

**Returns:**
El objeto clonado

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clona el encabezado.

**Returns:**
El objeto clonado

### getDestinationPage {#getDestinationPage--}
```
public Page getDestinationPage()
```

Obtiene la página de destino.

**Returns:**
La página de destino.

### getLevel {#getLevel--}
```
public int getLevel()
```

Obtiene el nivel.

**Returns:**
El nivel del encabezado.

### getStartNumber {#getStartNumber--}
```
public int getStartNumber()
```

Obtiene el número de inicio del encabezado.

**Returns:**
Valor: El startNumber.

### getStyle {#getStyle--}
```
public NumberingStyle getStyle()
```

Obtiene o establece el estilo.

**Returns:**
El estilo del encabezado.

### getTocPage {#getTocPage--}
```
public Page getTocPage()
```

Obtiene la página que contiene este encabezado.

**Returns:**
La página.

### getTop {#getTop--}
```
public double getTop()
```

Obtiene el valor Y superior de este encabezado (para uso interno).

**Returns:**
El valor Y superior

### getUserLabel {#getUserLabel--}
```
public TextSegment getUserLabel()
```

Obtiene o establece la etiqueta de usuario.

**Returns:**
Objeto TextSegment

### isAutoSequence {#isAutoSequence--}
```
public boolean isAutoSequence()
```

Obtiene si el encabezado debe numerarse automáticamente.

**Returns:**
El IsAutoSequens.

### isInList {#isInList--}
```
public boolean isInList()
```

Obtiene si el encabezado debe estar en la lista de índice.

**Returns:**
El IsInList.

### setAutoSequence {#setAutoSequence-boolean-}
```
public void setAutoSequence(boolean value)
```

Establece si el encabezado debe numerarse automáticamente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | El IsAutoSequens. |

### setDestinationPage {#setDestinationPage-com.aspose.pdf.Page-}
Establece la página de destino.

### setInList {#setInList-boolean-}
```
public void setInList(boolean value)
```

Establece si el encabezado debe estar en la lista de índice.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | El IsInList. |

### setLevel {#setLevel-int-}
```
public void setLevel(int value)
```

establece el nivel.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | El nivel del encabezado. |

### setStartNumber {#setStartNumber-int-}
```
public void setStartNumber(int value)
```

Obtiene el número de inicio del encabezado. Valor: El startNumber.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | El startNumber. |

### setStyle {#setStyle-com.aspose.pdf.NumberingStyle-}
establece o establece el estilo.

### setTocPage {#setTocPage-com.aspose.pdf.Page-}
Establece la página que contiene este encabezado.

### setTop {#setTop-double-}
```
public void setTop(double value)
```

establece la coordenada Y superior de estos encabezados (para uso interno).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | El valor Y superior |

### setUserLabel {#setUserLabel-com.aspose.pdf.TextSegment-}
Obtiene o establece la etiqueta de usuario.
