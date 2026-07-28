---
title: "PDF3DCrossSectionArray"
linktitle: "PDF3DCrossSectionArray"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Clase PDF3DCrossSectionArray."
type: docs
weight: 3600
url: /es/java/com.aspose.pdf/pdf3dcrosssectionarray/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PDF3DCrossSectionArray

```
public class PDF3DCrossSectionArray extends Object
```

Clase PDF3DCrossSectionArray.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PDF3DCrossSectionArray](#PDF3DCrossSectionArray-com.aspose.pdf.IDocument-) | Inicializa una nueva instancia de la clase {@code PDF3DCrossSectionArray}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [add](#add-com.aspose.pdf.PDF3DCrossSection-) | Agrega la sección transversal especificada al arreglo de vistas. |
| [get_Item](#get_Item-int-) | Obtiene o establece el {@code PDF3DCrossSection} en el índice especificado. |
| [getCount](#getCount--) | Obtiene el recuento de secciones transversales. |
| [removeAll](#removeAll--) | Elimina todas las secciones transversales del arreglo. |
| [removeAt](#removeAt-int-) | Elimina la sección transversal del arreglo en el índice especificado. |
| [set_Item](#set_Item-int-com.aspose.pdf.PDF3DCrossSection-) | Obtiene o establece el {@code PDF3DCrossSection} en el índice especificado. |

### PDF3DCrossSectionArray {#PDF3DCrossSectionArray-com.aspose.pdf.IDocument-}
Inicializa una nueva instancia de la clase {@code PDF3DCrossSectionArray}.

### add {#add-com.aspose.pdf.PDF3DCrossSection-}
Agrega la sección transversal especificada al arreglo de vistas.

### get_Item {#get_Item-int-}
```
public PDF3DCrossSection get_Item(int index)
```

Obtiene o establece el {@code PDF3DCrossSection} en el índice especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index |  | El índice. |

**Returns:**
Sección transversal. @throws IndexOutOfRangeException Índice inválido: el índice debe estar en el rango [1..n] donde n es igual al número de secciones transversales.

### getCount {#getCount--}
```
public int getCount()
```

Obtiene el recuento de secciones transversales.

**Returns:**
int value: El recuento de secciones transversales.

### removeAll {#removeAll--}
```
public void removeAll()
```

Elimina todas las secciones transversales del arreglo.

### removeAt {#removeAt-int-}
```
public void removeAt(int index)
```

Elimina la sección transversal del arreglo en el índice especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index |  | El índice de la sección transversal eliminada en la matriz. @throws IndexOutOfRangeException Índice inválido: el índice debe estar en el rango [1..n] donde n es igual al número de secciones transversales. |

### set_Item {#set_Item-int-com.aspose.pdf.PDF3DCrossSection-}
Obtiene o establece el {@code PDF3DCrossSection} en el índice especificado.
