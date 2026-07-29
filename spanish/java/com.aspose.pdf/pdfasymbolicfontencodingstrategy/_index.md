---
title: "PdfASymbolicFontEncodingStrategy"
linktitle: "PdfASymbolicFontEncodingStrategy"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Esta clase describe reglas que pueden usarse para ajustar el proceso de copia de datos de codificación en casos en que la fuente simbólica TrueType tiene más de una codificación. Algunos documentos PDF después."
type: docs
weight: 3690
url: /es/java/com.aspose.pdf/pdfasymbolicfontencodingstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfASymbolicFontEncodingStrategy

```
public class PdfASymbolicFontEncodingStrategy extends Object
```

Esta clase describe reglas que pueden usarse para ajustar el proceso de copia de datos de codificación en casos en que una fuente TrueType simbólica tiene más de una codificación. Algunos documentos PDF después de la conversión al formato PDF/A pueden generar un error \"More than one encoding in symbolic TrueType font's cmap\". ¿Cuál es la razón de este error? Todas las fuentes TrueType simbólicas tienen una tabla especial \"cmap\" en sus datos internos. Esta tabla asigna códigos de caracteres a índices de glifos. Y esta tabla puede contener diferentes subtablas de codificación que describen las codificaciones usadas. Consulte información avanzada sobre las tablas cmap en https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html. Normalmente la tabla cmap contiene varias subtablas de codificación, pero la norma PDF/A requiere que o bien solo quede una subtabla de codificación para esta fuente en el documento PDF/A o que exista una subtabla de codificación (3,0) entre las subtablas de esta fuente. Y la pregunta clave aquí: ¿qué datos deben tomarse de otras subtablas para copiar en la tabla de codificación de destino (3,0)? La mayoría de las fuentes tienen tablas cmap "bien formadas" donde cada subtabla de codificación es completamente consistente con otra subtabla. Pero algunas fuentes tienen tablas cmap con colisiones, por ejemplo una subtabla tiene el índice de glifo 100 para unicode 100, pero otra subtabla tiene el índice de glifo 200 para el mismo unicode 100. Para resolver estos problemas se necesita una estrategia especial. Por defecto se usa la siguiente estrategia: se busca la subtabla mac (1,0). Si se encuentra esta tabla, solo esos datos se usan para rellenar la tabla de destino (3,0). Si la subtabla mac no se encuentra, entonces se iteran todas las subtablas excepto la (3,0) y se usan para copiar datos a la subtabla de destino (3,0). Además, el mapeo para cada unicode (unicode, índice de glifo) se copia a la tabla de destino solo si la tabla de destino no tiene ese unicode en ese momento. Así, por ejemplo, si la primera subtabla tiene el índice de glifo 100 para unicode 100, y la siguiente subtabla tiene el índice de glifo 200 para el mismo unicode 100, solo se copiarán los datos de la primera subtabla (unicode=100, índice de glifo = 100). Por lo tanto, cada subtabla anterior tiene precedencia sobre la siguiente. Las propiedades de esta clase { PdfASymbolicFontEncodingStrategy} ayudan a ajustar el comportamiento predeterminado. Si la propiedad {PreferredCmapEncodingTable}({ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable}/ { PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable}) de tipo { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} está establecida, entonces la subtabla relevante se usará con precedencia sobre la subtabla mac (1,0). El valor 'MacTable' de la enumeración {PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType} no tiene sentido en este caso, ya que apunta a la misma subtabla mac (1,0) que se usa por defecto. La propiedad {CmapEncodingTablesPriorityQueue}({ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue}/ {PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}) descarta todas las prioridades para cualquier subtabla. Si esta propiedad está establecida, solo se usarán las subtablas de la cola declarada en el orden especificado. Si las subtablas especificadas no se encuentran, se usará la iteración predeterminada de todas las subtablas y la estrategia de copia descrita arriba. El objeto { PdfASymbolicFontEncodingStrategy.QueueItem} especifica la subtabla de codificación utilizada. Esta subtabla puede establecerse mediante una combinación de miembros (PlatformID, PlatformSpecificId) o mediante la enumeración { PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType}. En caso de que la fuente no tenga subtabla (3,0), se usará otra subtabla para mantener la compatibilidad PDF/A. La elección de la subtabla a usar se realiza bajo las mismas reglas descritas anteriormente, de modo que las propiedades {@code PreferredCmapEncodingTable}({ PdfASymbolicFontEncodingStrategy#getPreferredCmapEncodingTable}/ {PdfASymbolicFontEncodingStrategy#setPreferredCmapEncodingTable}) y {@code CmapEncodingTablesPriorityQueue}({ PdfASymbolicFontEncodingStrategy#getCmapEncodingTablesPriorityQueue}/ { PdfASymbolicFontEncodingStrategy#setCmapEncodingTablesPriorityQueue}) se utilizan para determinar la subtabla resultante, y si la fuente no tiene la(s) subtabla(s) solicitada(s), se usará cualquier subtabla existente.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [PdfASymbolicFontEncodingStrategy](#PdfASymbolicFontEncodingStrategy--) | Constructor. Establece la subtabla predeterminada (mac 1,0) |
| [PdfASymbolicFontEncodingStrategy](#PdfASymbolicFontEncodingStrategy-com.aspose.ms.System.Collections.Generic.Queue-) | Constructor. Establece la subtabla predeterminada (mac 1,0) |
| [PdfASymbolicFontEncodingStrategy](#PdfASymbolicFontEncodingStrategy-short-) | Constructor |

## Métodos

| Método | Descripción |
| --- | --- |
| [getCmapEncodingTablesPriorityQueue](#getCmapEncodingTablesPriorityQueue--) | Especifica la cola de subtablas de codificación a procesar. |
| [getPreferredCmapEncodingTable](#getPreferredCmapEncodingTable--) | Especifica la subtabla que se usará con precedencia sobre la subtabla mac(1,0). El valor 'MacTable' de la enumeración {@code QueueItem.CMapEncodingTableType} no tiene sentido en este caso. |
| [setCmapEncodingTablesPriorityQueue](#setCmapEncodingTablesPriorityQueue-com.aspose.ms.System.Collections.Generic.Queue-) | Especifica la cola de subtablas de codificación a procesar. |
| [setPreferredCmapEncodingTable](#setPreferredCmapEncodingTable-short-) | Especifica la subtabla que se usará con precedencia sobre la subtabla mac(1,0). El valor 'MacTable' de la enumeración {@code QueueItem.CMapEncodingTableType} no tiene sentido en este caso. |

### PdfASymbolicFontEncodingStrategy {#PdfASymbolicFontEncodingStrategy--}
```
public PdfASymbolicFontEncodingStrategy()
```

Constructor. Establece la subtabla predeterminada (mac 1,0)

### PdfASymbolicFontEncodingStrategy {#PdfASymbolicFontEncodingStrategy-com.aspose.ms.System.Collections.Generic.Queue-}
Constructor. Establece la subtabla predeterminada (mac 1,0)

### PdfASymbolicFontEncodingStrategy {#PdfASymbolicFontEncodingStrategy-short-}
```
public PdfASymbolicFontEncodingStrategy(short preferredEncodingTable)
```

Constructor

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| preferredEncodingTable |  | subtabla de codificación que se usará con precedencia sobre la subtabla mac(1,0) @see PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType |

### getCmapEncodingTablesPriorityQueue {#getCmapEncodingTablesPriorityQueue--}
```
public com.aspose.ms.System.Collections.Generic.Queue< PdfASymbolicFontEncodingStrategy.QueueItem > getCmapEncodingTablesPriorityQueue()
```

Especifica la cola de subtablas de codificación a procesar.

**Returns:**
Cola de QueueItem

### getPreferredCmapEncodingTable {#getPreferredCmapEncodingTable--}
```
public short getPreferredCmapEncodingTable()
```

Especifica la subtabla que se usará con precedencia sobre la subtabla mac(1,0). El valor 'MacTable' de la enumeración {@code QueueItem.CMapEncodingTableType} no tiene sentido en este caso.

**Returns:**
CMapEncodingTableType elemento @see PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType

### setCmapEncodingTablesPriorityQueue {#setCmapEncodingTablesPriorityQueue-com.aspose.ms.System.Collections.Generic.Queue-}
Especifica la cola de subtablas de codificación a procesar.

### setPreferredCmapEncodingTable {#setPreferredCmapEncodingTable-short-}
```
public void setPreferredCmapEncodingTable(short value)
```

Especifica la subtabla que se usará con precedencia sobre la subtabla mac(1,0). El valor 'MacTable' de la enumeración {@code QueueItem.CMapEncodingTableType} no tiene sentido en este caso.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | subtabla de codificación preferredEncodingTable que se usará con precedencia sobre la subtabla mac(1,0) @see PdfASymbolicFontEncodingStrategy.QueueItem.CMapEncodingTableType |
