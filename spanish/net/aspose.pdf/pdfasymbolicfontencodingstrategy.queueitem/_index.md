---
title: PdfASymbolicFontEncodingStrategy.QueueItem
second_title: Referencia de API de Aspose.PDF para .NET
description: Especifica la subtabla de codificación. Cada subtabla de codificación tiene una combinación única de parámetros PlatformID PlatformSpecificId. EnumeraciónCMapEncodingTableType./pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype y propiedadCMapEncodingTable./pdfasymbolicfontencodingstrategy.queueitem/cmapencodingtable se implementaron para facilitar conjunto de subtablas de codificación necesarias.
type: docs
weight: 5990
url: /es/net/aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/
---
## PdfASymbolicFontEncodingStrategy.QueueItem class

Especifica la subtabla de codificación. Cada subtabla de codificación tiene una combinación única de parámetros (PlatformID, PlatformSpecificId). Enumeración[`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype) y propiedad[`CMapEncodingTable`](./cmapencodingtable) se implementaron para facilitar conjunto de subtablas de codificación necesarias.

```csharp
public class QueueItem
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [QueueItem](queueitem#constructor)() | Constructor, especifica mac subtable(1,0) por defecto |
| [QueueItem](queueitem#constructor_1)(CMapEncodingTableType) | Constructor |
| [QueueItem](queueitem#constructor_2)(ushort, ushort) | Constructor |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CMapEncodingTable](../../aspose.pdf/queueitem/cmapencodingtable) { get; set; } | Especifica la subtabla de codificación mediante[`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype) enumeración |
| [PlatformId](../../aspose.pdf/queueitem/platformid) { get; set; } | Identificador de plataforma para codificar subtabla |
| [PlatformSpecificId](../../aspose.pdf/queueitem/platformspecificid) { get; set; } | Identificador de codificación específico de la plataforma para codificar subtable |

### Ver también

* class [PdfASymbolicFontEncodingStrategy](../pdfasymbolicfontencodingstrategy)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->