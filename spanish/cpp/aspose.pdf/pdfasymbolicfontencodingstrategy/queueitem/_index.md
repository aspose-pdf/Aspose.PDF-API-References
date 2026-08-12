---
title: "Aspose::Pdf::PdfASymbolicFontEncodingStrategy::QueueItem clase"
linktitle: "QueueItem"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::PdfASymbolicFontEncodingStrategy::QueueItem clase. Especifica la subtabla de codificación. Cada subtabla de codificación tiene una combinación única de parámetros (PlatformID, PlatformSpecificId). La enumeración CMapEncodingTableType y la propiedad CMapEncodingTable fueron implementadas para facilitar la configuración de la subtabla de codificación necesaria en C++."
type: docs
weight: 600
url: /es/cpp/aspose.pdf/pdfasymbolicfontencodingstrategy/queueitem/
---
## QueueItem class


Especifica la subtabla de codificación. Cada subtabla de codificación tiene una combinación única de parámetros (PlatformID, PlatformSpecificId). La enumeración [CMapEncodingTableType](./cmapencodingtabletype/) y la propiedad [CMapEncodingTable](../) fueron implementadas para facilitar la configuración de la subtabla de codificación necesaria.

```cpp
class QueueItem : public System::Object
```

## Enums

| Enumeración | Descripción |
| --- | --- |
| [CMapEncodingTableType](./cmapencodingtabletype/) | Declara un conjunto de algunas subtablas de codificación conocidas. |
## Métodos

| Método | Descripción |
| --- | --- |
| [get_CMapEncodingTable](./get_cmapencodingtable/)() const | Especifica la subtabla de codificación mediante la enumeración [CMapEncodingTableType](./cmapencodingtabletype/). |
| [get_PlatformId](./get_platformid/)() const | Identificador de plataforma para la subtabla de codificación. |
| [get_PlatformSpecificId](./get_platformspecificid/)() const | Identificador de codificación específico de la plataforma para la subtabla de codificación. |
| [QueueItem](./queueitem/)() | Constructor, especifica la subtabla mac(1,0) por defecto. |
| [QueueItem](./queueitem/)(uint16_t, uint16_t) | Constructor. |
| [QueueItem](./queueitem/)(PdfASymbolicFontEncodingStrategy::QueueItem::CMapEncodingTableType) | Constructor. |
| [set_CMapEncodingTable](./set_cmapencodingtable/)(PdfASymbolicFontEncodingStrategy::QueueItem::CMapEncodingTableType) | Especifica la subtabla de codificación mediante la enumeración [CMapEncodingTableType](./cmapencodingtabletype/). |
| [set_PlatformId](./set_platformid/)(uint16_t) | Identificador de plataforma para la subtabla de codificación. |
| [set_PlatformSpecificId](./set_platformspecificid/)(uint16_t) | Identificador de codificación específico de la plataforma para la subtabla de codificación. |
## Ver también

* Class [Object](../../../system/object/)
* Class [PdfASymbolicFontEncodingStrategy](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
