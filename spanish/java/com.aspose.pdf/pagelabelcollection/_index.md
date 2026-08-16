---
title: "PageLabelCollection"
linktitle: "PageLabelCollection"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase que representa la colección de page label."
type: docs
weight: 3400
url: /es/java/com.aspose.pdf/pagelabelcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PageLabelCollection

```
public class PageLabelCollection extends Object
```

Clase que representa la colección de page label.

## Métodos

| Método | Descripción |
| --- | --- |
| [getLabel](#getLabel-int-) | Obtiene la etiqueta de página por índice de página (el índice de página comienza en 0). |
| [getPages](#getPages--) | Obtiene los índices de página en la colección. |
| [removeLabel](#removeLabel-int-) | Elimina la etiqueta por índice de página (el índice de página comienza en 0). |
| [updateLabel](#updateLabel-int-com.aspose.pdf.PageLabel-) | Actualiza la etiqueta para el índice de página dado (el índice de página comienza en 0). |

### getLabel {#getLabel-int-}
```
public PageLabel getLabel(int pageIndex)
```

Obtiene la etiqueta de página por índice de página (el índice de página comienza en 0).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageIndex |  | Índice de la página. |

**Returns:**
Etiqueta de página para el índice de página especificado o null si la etiqueta de página no existe.

### getPages {#getPages--}
```
public int[] getPages()
```

Obtiene los índices de página en la colección.

**Returns:**
Arreglo de enteros que contiene los índices de las páginas.

### removeLabel {#removeLabel-int-}
```
public boolean removeLabel(int pageIndex)
```

Elimina la etiqueta por índice de página (el índice de página comienza en 0).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pageIndex |  | Índice de la página donde la etiqueta debe ser eliminada. |

**Returns:**
true si la operación se ejecutó con éxito.

### updateLabel {#updateLabel-int-com.aspose.pdf.PageLabel-}
Actualiza la etiqueta para el índice de página dado (el índice de página comienza en 0).
