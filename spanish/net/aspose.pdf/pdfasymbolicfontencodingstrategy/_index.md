---
title: Class PdfASymbolicFontEncodingStrategy
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfASymbolicFontEncodingStrategy class. Esta clase describe las reglas que se pueden utilizar para ajustar el proceso de copiado de datos de codificación en casos cuando una fuente simbólica TrueType tiene más de una codificación.
type: docs
weight: 8330
url: /es/net/aspose.pdf/pdfasymbolicfontencodingstrategy/
---
## Clase PdfASymbolicFontEncodingStrategy

Esta clase describe las reglas que se pueden utilizar para ajustar el proceso de copiado de datos de codificación en casos cuando una fuente simbólica TrueType tiene más de una codificación. Algunos documentos PDF, después de la conversión al formato PDF/A, podrían generar un error "More than one encoding in symbolic TrueType font's cmap". ¿Cuál es la razón de este error? Todas las fuentes simbólicas TrueType tienen una tabla especial "cmap" en sus datos internos. Esta tabla mapea los códigos de caracteres a índices de glifos. Y esta tabla podría contener diferentes subtablas de codificación que describen las codificaciones utilizadas. Consulta información avanzada sobre las tablas cmap en https://developer.apple.com/fonts/TrueType-Reference-Manual/RM06/Chap6cmap.html. Usualmente, la tabla cmap contiene varias subtablas de codificación, pero la norma PDF/A requiere que o bien sólo se deje una subtabla de codificación para esta fuente en el documento PDF/A, o bien debe existir una subtabla de codificación (3,0) entre las subtablas de esta fuente. Y la pregunta clave aquí es: ¿qué datos deben tomarse de las otras subtablas para copiarse a la tabla de codificación de destino (3,0)? La mayoría de las fuentes tienen tablas cmap 'well-formed' en las que cada subtabla de codificación es completamente consistente con las demás. Pero algunas fuentes tienen tablas cmap con colisiones; por ejemplo, una subtabla puede tener el índice de glifo 100 para el unicode 100, mientras que otra subtabla tiene el índice de glifo 200 para el mismo unicode 100. Para resolver estos problemas se necesita una estrategia especial. Por defecto se utiliza la siguiente estrategia: se busca la subtabla mac (1,0). Si se encuentra esta tabla, sólo se usan estos datos para llenar la tabla de destino (3,0). Si no se encuentra la subtabla mac, entonces se iteran todas las subtablas excepto la (3,0) y se usan para copiar datos en la subtabla de destino (3,0). Además, el mapeo de cada unicode (unicode, índice de glifo) se copia en la tabla de destino sólo si ésta no tiene ese unicode en ese momento. Así, por ejemplo, si la primera subtabla tiene el índice de glifo 100 para el unicode 100 y la siguiente subtabla tiene el índice de glifo 200 para el mismo unicode 100, sólo se copiarán los datos de la primera subtabla (unicode=100, índice de glifo = 100). De modo que cada subtabla anterior tiene prioridad sobre la siguiente. Las propiedades de esta clase `PdfASymbolicFontEncodingStrategy` ayudan a afinar el comportamiento por defecto. Si se establece la propiedad [`PreferredCmapEncodingTable`](./preferredcmapencodingtable/) de tipo [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/), entonces se utilizará la subtabla correspondiente con prioridad sobre la subtabla mac (1,0). El valor 'MacTable' de la enumeración [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) no tiene sentido en este caso, ya que apunta a la misma subtabla mac (1,0) que se utilizará por defecto. La propiedad [`CmapEncodingTablesPriorityQueue`](./cmapencodingtablespriorityqueue/) descarta todas las prioridades de cualquier subtabla. Si se establece esta propiedad, entonces sólo se utilizarán las subtablas de la cola declarada en el orden especificado. Si las subtablas especificadas no se encuentran, se utilizará la iteración por defecto de todas las subtablas y la estrategia de copiado descrita anteriormente. El objeto [`QueueItem`](../pdfasymbolicfontencodingstrategy.queueitem/) especifica la subtabla de codificación utilizada. Esta subtabla se puede establecer mediante la combinación de los miembros (PlatformID, PlatformSpecificId) o mediante la enumeración [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/). En el caso de que la fuente no tenga la subtabla (3,0), se utilizará alguna otra subtabla para mantener la compatibilidad con PDF/A. La elección de la subtabla a utilizar se realiza bajo las mismas reglas descritas anteriormente, de modo que las propiedades [`PreferredCmapEncodingTable`](./preferredcmapencodingtable/) y [`CmapEncodingTablesPriorityQueue`](./cmapencodingtablespriorityqueue/) se utilizan para determinar la subtabla resultante, y si la fuente tampoco tiene la(s) subtabla(s) solicitada(s), se usará cualquier otra subtabla existente.

```csharp
public class PdfASymbolicFontEncodingStrategy
```

## Constructores

| Name | Description |
| --- | --- |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy/#constructor)() | Constructor. Establece la subtabla predeterminada (mac 1,0) |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy/#constructor_1)(CMapEncodingTableType) | Constructor |
| [PdfASymbolicFontEncodingStrategy](pdfasymbolicfontencodingstrategy/#constructor_2)(Queue&lt;QueueItem&gt;) | Constructor |

## Propiedades

| Name | Description |
| --- | --- |
| [CmapEncodingTablesPriorityQueue](../../aspose.pdf/pdfasymbolicfontencodingstrategy/cmapencodingtablespriorityqueue/) { get; set; } | Especifica la cola de subtablas de codificación a procesar. |
| [PreferredCmapEncodingTable](../../aspose.pdf/pdfasymbolicfontencodingstrategy/preferredcmapencodingtable/) { get; set; } | Especifica la subtabla que se utilizará con prioridad sobre la subtabla mac (1,0). El valor 'MacTable' de la enumeración [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) no tiene sentido en este caso. |

### Véase También

* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../)