---
title: "PdfActionCollection"
linktitle: "PdfActionCollection"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase describe lista de acciones."
type: docs
weight: 3680
url: /es/java/com.aspose.pdf/pdfactioncollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfActionCollection

**All Implemented Interfaces:**
Iterable < PdfAction >

```
public class PdfActionCollection extends Object implements Iterable < PdfAction >
```

Clase describe lista de acciones.

## Métodos

| Método | Descripción |
| --- | --- |
| [add](#add-com.aspose.pdf.PdfAction-) | Agregar acción a la lista de acciones. |
| [delete](#delete-int-) | Eliminar acción por índice. |
| [get_Item](#get_Item-int-) | Obtiene la acción por su índice. |
| [getCount](#getCount--) | Obtiene el recuento de acciones. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Método interno |
| [iterator](#iterator--) | Obtiene el enumerador. |

### add {#add-com.aspose.pdf.PdfAction-}
Agregar acción a la lista de acciones.

### delete {#delete-int-}
```
public void delete(int index)
```

Eliminar acción por índice.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index |  | Índice de la acción a eliminar. |

### get_Item {#get_Item-int-}
```
public PdfAction get_Item(int index)
```

Obtiene la acción por su índice.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index |  | Valor del índice de acción. |

**Returns:**
Índice de PdfAction si se encuentra; de lo contrario, lanza @throws IndexOutOfRangeException IndexOutOfRangeException

### getCount {#getCount--}
```
public int getCount()
```

Obtiene el recuento de acciones.

**Returns:**
valor int

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator< PdfAction > iterator_Rename_Namesake()
```

Método interno

**Returns:**
objeto interno.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< PdfAction > iterator()
```

Obtiene el enumerador.

**Returns:**
Enumerador de PDfAction.
