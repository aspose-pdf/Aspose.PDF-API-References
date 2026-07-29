---
title: "Sello"
linktitle: "Sello"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa un sello."
type: docs
weight: 700
url: /es/java/com.aspose.pdf.facades/stamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Stamp

```
public final class Stamp extends Object
```

Clase que representa un sello.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [Stamp](#Stamp--) | Constructor para el objeto Stamp. |

## Métodos

| Método | Descripción |
| --- | --- |
| [bindImage](#bindImage-java.io.InputStream-) | Establece la imagen que se utilizará como sello. |
| [bindImage](#bindImage-java.lang.String-) | <p> Establece la imagen como una marca. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); stamp.bindImage("image.jpg"); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [bindLogo](#bindLogo-com.aspose.pdf.facades.FormattedText-) | Establece el texto como marca. |
| [bindPdf](#bindPdf-java.io.InputStream-int-) | <p> Establece el archivo PDF y el número de página que se usará como marca. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); //First page will be used as stamp. InputStream stream = new FileInputStream("stamp.pdf"); stamp.bindPdf(stream, 1); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [bindPdf](#bindPdf-java.lang.String-int-) | <p> Establece el archivo PDF y el número de página que se usará como marca. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); //First page will be used as stamp. stamp.bindPdf("stamp.pdf", 1); stamp.isBackground (true); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [bindTextState](#bindTextState-com.aspose.pdf.TextState-) | Establece el estado del texto de la marca. |
| [close](#close--) | Cierra esta instancia |
| [getBlendingSpace](#getBlendingSpace--) | Obtiene un valor BlendingColorSpace que define un espacio de color que se utiliza para realizar operaciones de transparencia y mezcla en la página. |
| [getOpacity](#getOpacity--) | Obtiene la opacidad de la marca. |
| [getPageNumber](#getPageNumber--) | Obtiene el número de página. |
| [getPages](#getPages--) | Obtiene una matriz con los números de páginas que serán afectadas por la marca. |
| [getQuality](#getQuality--) | Obtiene la calidad de la marca de imagen en porcentaje. Valores válidos 0..100%. |
| [getRotation](#getRotation--) | Obtiene la rotación de la marca en grados. |
| [getStampId](#getStampId--) | Obtiene el identificador de la marca. |
| [isBackground](#isBackground--) | Obtiene el estado de fondo. Si es true, la marca se colocará como fondo de la página estampada. Por defecto está configurado a false. |
| [setBackground](#setBackground-boolean-) | Establece el estado de fondo. Si es true, la marca se colocará como fondo de la página estampada. Por defecto está configurado a false. |
| [setBlendingSpace](#setBlendingSpace-com.aspose.pdf.facades.BlendingColorSpace-) | Establece un valor BlendingColorSpace que define un espacio de color que se utiliza para realizar operaciones de transparencia y mezcla en la página. |
| [setImageSize](#setImageSize-float-float-) | Establece el tamaño de la marca de imagen. La imagen se escalará según los valores especificados. |
| [setOpacity](#setOpacity-float-) | Establece la opacidad de la marca. |
| [setOrigin](#setOrigin-float-float-) | Establece la posición en la página donde se colocará la marca. |
| [setPageNumber](#setPageNumber-int-) | Establece el número de página. |
| [setPages](#setPages-int:A-) | <p> Establece una matriz con los números de páginas que serán afectadas por la marca. Si Pages = null, todas las páginas del documento son afectadas. </p> |
| [setQuality](#setQuality-int-) | Establece la calidad de la marca de imagen en porcentaje. Valores válidos 0..100%. |
| [setRotation](#setRotation-float-) | <p> Obtiene o establece la rotación de la marca en grados. </p> |
| [setStampId](#setStampId-int-) | Establece el identificador de la marca. |

### Stamp {#Stamp--}
```
public Stamp()
```

Constructor para el objeto Stamp.

### bindImage {#bindImage-java.io.InputStream-}
Establece la imagen que se utilizará como sello.

### bindImage {#bindImage-java.lang.String-}
<p> Establece la imagen como una marca. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); stamp.bindImage("image.jpg"); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### bindLogo {#bindLogo-com.aspose.pdf.facades.FormattedText-}
Establece el texto como marca.

### bindPdf {#bindPdf-java.io.InputStream-int-}
<p> Establece el archivo PDF y el número de página que se usará como marca. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); //First page will be used as stamp. InputStream stream = new FileInputStream("stamp.pdf"); stamp.bindPdf(stream, 1); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### bindPdf {#bindPdf-java.lang.String-int-}
<p> Establece el archivo PDF y el número de página que se usará como marca. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); //First page will be used as stamp. stamp.bindPdf("stamp.pdf", 1); stamp.isBackground (true); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### bindTextState {#bindTextState-com.aspose.pdf.TextState-}
Establece el estado del texto de la marca.

### close {#close--}
```
public void close()
```

Cierra esta instancia

### getBlendingSpace {#getBlendingSpace--}
```
public BlendingColorSpace getBlendingSpace()
```

Obtiene un valor BlendingColorSpace que define un espacio de color que se utiliza para realizar operaciones de transparencia y mezcla en la página.

**Returns:**
valor int @see BlendingColorSpace

### getOpacity {#getOpacity--}
```
public float getOpacity()
```

Obtiene la opacidad de la marca.

**Returns:**
valor flotante

### getPageNumber {#getPageNumber--}
```
public int getPageNumber()
```

Obtiene el número de página.

**Returns:**
valor int

### getPages {#getPages--}
```
public int[] getPages()
```

Obtiene una matriz con los números de páginas que serán afectadas por la marca.

**Returns:**
matriz de int

### getQuality {#getQuality--}
```
public int getQuality()
```

Obtiene la calidad de la marca de imagen en porcentaje. Valores válidos 0..100%.

**Returns:**
valor int

### getRotation {#getRotation--}
```
public float getRotation()
```

Obtiene la rotación de la marca en grados.

**Returns:**
valor flotante

### getStampId {#getStampId--}
```
public int getStampId()
```

Obtiene el identificador de la marca.

**Returns:**
valor int

### isBackground {#isBackground--}
```
public boolean isBackground()
```

Obtiene el estado de fondo. Si es true, la marca se colocará como fondo de la página estampada. Por defecto está configurado a false.

**Returns:**
valor booleano

### setBackground {#setBackground-boolean-}
```
public void setBackground(boolean value)
```

Establece el estado de fondo. Si es true, la marca se colocará como fondo de la página estampada. Por defecto está configurado a false.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setBlendingSpace {#setBlendingSpace-com.aspose.pdf.facades.BlendingColorSpace-}
Establece un valor BlendingColorSpace que define un espacio de color que se utiliza para realizar operaciones de transparencia y mezcla en la página.

### setImageSize {#setImageSize-float-float-}
```
public void setImageSize(float width, float height)
```

Establece el tamaño de la marca de imagen. La imagen se escalará según los valores especificados.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| ancho |  | Ancho de la imagen. |
| altura |  | Altura de la imagen. |

### setOpacity {#setOpacity-float-}
```
public void setOpacity(float value)
```

Establece la opacidad de la marca.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor flotante |

### setOrigin {#setOrigin-float-float-}
```
public void setOrigin(float originX, float originY)
```

Establece la posición en la página donde se colocará la marca.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| originX |  | Coordenada X del sello. |
| originY |  | Coordenada Y del sello. |

### setPageNumber {#setPageNumber-int-}
```
public void setPageNumber(int value)
```

Establece el número de página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setPages {#setPages-int:A-}
```
public void setPages(int[] value)
```

<p> Establece una matriz con los números de páginas que serán afectadas por la marca. Si Pages = null, todas las páginas del documento son afectadas. </p>

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | matriz de int <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new com.aspose.pdf.facades.Stamp(); stamp.bindLogo(new FormattedText(text)); //colocar sello solo en la 1ª, 4ª y 6ª página. stamp.setPages(new int[] { 1, 4, 6 }); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |

### setQuality {#setQuality-int-}
```
public void setQuality(int value)
```

Establece la calidad de la marca de imagen en porcentaje. Valores válidos 0..100%.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |

### setRotation {#setRotation-float-}
```
public void setRotation(float value)
```

<p> Obtiene o establece la rotación de la marca en grados. </p>

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor flotante <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); stamp.bindLogo(new FormattedText("STAMP")); stamp.setRotation(90); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |

### setStampId {#setStampId-int-}
```
public void setStampId(int value)
```

Establece el identificador de la marca.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |
