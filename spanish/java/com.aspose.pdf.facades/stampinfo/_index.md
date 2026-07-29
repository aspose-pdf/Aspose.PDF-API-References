---
title: "StampInfo"
linktitle: "StampInfo"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa información de sello."
type: docs
weight: 710
url: /es/java/com.aspose.pdf.facades/stampinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.StampInfo

```
public final class StampInfo extends Object
```

Clase que representa información de sello.

## Métodos

| Método | Descripción |
| --- | --- |
| [getForm](#getForm--) | Obtiene XForm del sello. |
| [getImage](#getImage--) | Obtiene la imagen del sello. Puede ser nulo si el sello no contiene imágenes (por ejemplo, para un sello de texto). |
| [getImageInternal](#getImageInternal--) | Obtiene la imagen del sello. Puede ser nulo si el sello no contiene imágenes (por ejemplo, para un sello de texto). |
| [getIndexOnPage](#getIndexOnPage--) | Obtiene el índice del sello en la página. |
| [getRectangle](#getRectangle--) | Obtiene el rectángulo donde se coloca el sello. |
| [getStampId](#getStampId--) | Obtiene el identificador del sello. |
| [getStampType](#getStampType--) | Obtiene el tipo de sello (imagen / formulario). |
| [getText](#getText--) | Obtiene el texto del sello. |
| [getVisible](#getVisible--) | Obtiene la visibilidad del sello. Si es false, el sello está oculto (con HideStampById). El sello oculto puede restaurarse con ShowStampById. |

### getForm {#getForm--}
```
public XForm getForm()
```

Obtiene XForm del sello.

**Returns:**
objeto XForm

### getImage {#getImage--}
```
public BufferedImage getImage()
```

Obtiene la imagen del sello. Puede ser nulo si el sello no contiene imágenes (por ejemplo, para un sello de texto).

**Returns:**
Objeto BufferedImage

### getImageInternal {#getImageInternal--}
```
public com.aspose.ms.System.Drawing.Image getImageInternal()
```

Obtiene la imagen del sello. Puede ser nulo si el sello no contiene imágenes (por ejemplo, para un sello de texto).

**Returns:**
Objeto Image

### getIndexOnPage {#getIndexOnPage--}
```
public int getIndexOnPage()
```

Obtiene el índice del sello en la página.

**Returns:**
valor int

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Obtiene el rectángulo donde se coloca el sello.

**Returns:**
Elemento rectángulo

### getStampId {#getStampId--}
```
public int getStampId()
```

Obtiene el identificador del sello.

**Returns:**
valor int

### getStampType {#getStampType--}
```
public StampType getStampType()
```

Obtiene el tipo de sello (imagen / formulario).

**Returns:**
Elemento StampType @see StampType

### getText {#getText--}
```
public String getText()
```

Obtiene el texto del sello.

**Returns:**
valor String

### getVisible {#getVisible--}
```
public boolean getVisible()
```

Obtiene la visibilidad del sello. Si es false, el sello está oculto (con HideStampById). El sello oculto puede restaurarse con ShowStampById.

**Returns:**
valor booleano
