---
title: "ImageStamp"
linktitle: "ImageStamp"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa un sello gráfico."
type: docs
weight: 2360
url: /es/java/com.aspose.pdf/imagestamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp com.aspose.pdf.ImageStamp, com.aspose.pdf.Stamp, com.aspose.pdf.ImageStamp

```
public final class ImageStamp extends Stamp
```

Representa un sello gráfico.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [ImageStamp](#ImageStamp-java.io.InputStream-) | Inicializa una nueva instancia de la clase {@code ImageStamp}. |
| [ImageStamp](#ImageStamp-java.lang.String-) | Crea un sello de imagen a partir de una imagen en el archivo especificado. |

## Métodos

| Método | Descripción |
| --- | --- |
| [close](#close--) | Cierra esta instancia |
| [getAlternativeText](#getAlternativeText--) | Obtiene el Texto Alternativo para el sello de imagen. |
| [getHeight](#getHeight--) | Obtiene la altura de la imagen. Configurar esta imagen permite escalar la imagen verticalmente. |
| [getImage](#getImage--) | Obtiene el flujo de imagen utilizado para el sellado. |
| [getQuality](#getQuality--) | Obtiene la calidad del sello de imagen en porcentaje. Los valores válidos son 0..100%. |
| [getWidth](#getWidth--) | Obtiene el ancho de la imagen. Configurar esta propiedad permite escalar la imagen horizontalmente. |
| [getXIndent](#getXIndent--) | Obtiene y establece la coordenada horizontal del sello, comenzando desde la izquierda. |
| [getYIndent](#getYIndent--) | Obtiene y establece la coordenada vertical del sello, comenzando desde la parte inferior. |
| [put](#put-com.aspose.pdf.Page-) | Agrega un sello gráfico en la página. |
| [setAlternativeText](#setAlternativeText-java.lang.String-) | Establece el Texto Alternativo para el sello de imagen. |
| [setHeight](#setHeight-double-) | Establece la altura de la imagen. Configurar esta imagen permite escalar la imagen verticalmente. |
| [setQuality](#setQuality-int-) | Establece la calidad del sello de imagen en porcentaje. Los valores válidos son 0..100%. |
| [setWidth](#setWidth-double-) | Establece el ancho de la imagen. Configurar esta propiedad permite escalar la imagen horizontalmente. |
| [setXIndent](#setXIndent-double-) | Obtiene y establece la coordenada horizontal del sello, comenzando desde la izquierda. |
| [setYIndent](#setYIndent-double-) | Obtiene y establece la coordenada vertical del sello, comenzando desde la parte inferior. |

### ImageStamp {#ImageStamp-java.io.InputStream-}
Inicializa una nueva instancia de la clase {@code ImageStamp}.

### ImageStamp {#ImageStamp-java.lang.String-}
Crea un sello de imagen a partir de una imagen en el archivo especificado.

### close {#close--}
```
public void close()
```

Cierra esta instancia

### getAlternativeText {#getAlternativeText--}
```
public final String getAlternativeText()
```

Obtiene el Texto Alternativo para el sello de imagen.

**Returns:**
valor String

### getHeight {#getHeight--}
```
public double getHeight()
```

Obtiene la altura de la imagen. Configurar esta imagen permite escalar la imagen verticalmente.

**Returns:**
valor double

### getImage {#getImage--}
```
public InputStream getImage()
```

Obtiene el flujo de imagen utilizado para el sellado.

**Returns:**
Objeto InputStream

### getQuality {#getQuality--}
```
public int getQuality()
```

Obtiene la calidad del sello de imagen en porcentaje. Los valores válidos son 0..100%.

**Returns:**
valor int

### getWidth {#getWidth--}
```
public double getWidth()
```

Obtiene el ancho de la imagen. Configurar esta propiedad permite escalar la imagen horizontalmente.

**Returns:**
valor double

### getXIndent {#getXIndent--}
```
public double getXIndent()
```

Obtiene y establece la coordenada horizontal del sello, comenzando desde la izquierda.

**Returns:**
valor double

### getYIndent {#getYIndent--}
```
public double getYIndent()
```

Obtiene y establece la coordenada vertical del sello, comenzando desde la parte inferior.

**Returns:**
valor double

### put {#put-com.aspose.pdf.Page-}
Agrega un sello gráfico en la página.

### setAlternativeText {#setAlternativeText-java.lang.String-}
Establece el Texto Alternativo para el sello de imagen.

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Establece la altura de la imagen. Configurar esta imagen permite escalar la imagen verticalmente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setQuality {#setQuality-int-}
```
public void setQuality(int value)
```

Establece la calidad del sello de imagen en porcentaje. Los valores válidos son 0..100%.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Establece el ancho de la imagen. Configurar esta propiedad permite escalar la imagen horizontalmente.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setXIndent {#setXIndent-double-}
```
public void setXIndent(double value)
```

Obtiene y establece la coordenada horizontal del sello, comenzando desde la izquierda.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |

### setYIndent {#setYIndent-double-}
```
public void setYIndent(double value)
```

Obtiene y establece la coordenada vertical del sello, comenzando desde la parte inferior.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor double |
