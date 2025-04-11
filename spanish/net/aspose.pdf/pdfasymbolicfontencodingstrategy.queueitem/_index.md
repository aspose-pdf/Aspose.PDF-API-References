---
title: Class PdfASymbolicFontEncodingStrategy.QueueItem
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.PdfASymbolicFontEncodingStrategyQueueItem. Especifica la subtabla de codificación. Cada subtabla de codificación tiene una combinación única de parámetros PlatformID PlatformSpecificId. La enumeración CMapEncodingTableType y la propiedad CMapEncodingTable se implementaron para facilitar el conjunto de subtabla de codificación necesario.
type: docs
weight: 8340
url: /es/net/aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/
---
## Clase PdfASymbolicFontEncodingStrategy.QueueItem

Especifica la subtabla de codificación. Cada subtabla de codificación tiene una combinación única de parámetros (PlatformID, PlatformSpecificId). La enumeración [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) y la propiedad [`CMapEncodingTable`](./cmapencodingtable/) se implementaron para facilitar el conjunto de subtabla de codificación necesario.

```csharp
public class QueueItem
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor)() | Constructor, especifica la subtabla mac(1,0) por defecto |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor_1)(CMapEncodingTableType) | Constructor |
| [QueueItem](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/.ctor#constructor_2)(ushort, ushort) | Constructor |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CMapEncodingTable](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/cmapencodingtable) { get; set; } | Especifica la subtabla de codificación a través de la enumeración [`CMapEncodingTableType`](../pdfasymbolicfontencodingstrategy.queueitem.cmapencodingtabletype/) |
| [PlatformId](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/platformid) { get; set; } | Identificador de plataforma para la subtabla de codificación |
| [PlatformSpecificId](../../aspose.pdf/pdfasymbolicfontencodingstrategy.queueitem/platformspecificid) { get; set; } | Identificador de codificación específico de la plataforma para la subtabla de codificación |

### Ver También

* clase [PdfASymbolicFontEncodingStrategy](../pdfasymbolicfontencodingstrategy/)
* espacio de nombres [Aspose.Pdf](../../aspose.pdf/)
* ensamblaje [Aspose.PDF](../../)