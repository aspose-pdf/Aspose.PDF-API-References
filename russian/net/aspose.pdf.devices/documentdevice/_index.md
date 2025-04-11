---
title: Class DocumentDevice
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Devices.DocumentDevice. Абстрактный класс для всех устройств, которые используются для обработки всего pdf документа
type: docs
weight: 3570
url: /ru/net/aspose.pdf.devices/documentdevice/
---
## DocumentDevice class

Абстрактный класс для всех устройств, которые используются для обработки всего pdf документа.

```csharp
public abstract class DocumentDevice : PageDevice
```

## Methods

| Name | Description |
| --- | --- |
| [Process](../../aspose.pdf.devices/documentdevice/process/#process_2)(Document, Stream) | Обрабатывает весь документ и сохраняет результаты в поток. |
| [Process](../../aspose.pdf.devices/documentdevice/process/#process_3)(Document, string) | Обрабатывает весь документ и сохраняет результаты в файл. |
| abstract [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, Stream) | Выполняет некоторую операцию на данной странице, например, конвертирует страницу в графическое изображение. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Выполняет некоторую операцию на данной странице и сохраняет результаты в файл. |
| abstract [Process](../../aspose.pdf.devices/documentdevice/process/#process)(Document, int, int, Stream) | Каждое устройство представляет собой некоторую операцию над документом, например, мы можем конвертировать pdf документ в другой формат. |
| [Process](../../aspose.pdf.devices/documentdevice/process/#process_1)(Document, int, int, string) | Обрабатывает определенные страницы документа и сохраняет результаты в файл. |

### See Also

* class [PageDevice](../pagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)