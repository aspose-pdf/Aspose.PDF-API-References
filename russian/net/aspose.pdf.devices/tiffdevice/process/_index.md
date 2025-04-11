---
title: TiffDevice.Process
second_title: Aspose.PDF for .NET API Reference
description: Метод TiffDevice. Преобразует определенные страницы документа в tiff и сохраняет их в выходном потоке
type: docs
weight: 90
url: /ru/net/aspose.pdf.devices/tiffdevice/process/
---
## Process(Document, int, int, Stream) {#process}

Преобразует определенные страницы документа в tiff и сохраняет их в выходном потоке.

```csharp
public override void Process(Document document, int fromPage, int toPage, Stream output)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| document | Document | Документ для преобразования. |
| fromPage | Int32 | Определяет номер страницы, с которой начнется преобразование. |
| toPage | Int32 | Определяет номер страницы, на которой завершится преобразование. |
| output | Stream | Выходной поток с изображением tiff. |

### См. также

* класс [Document](../../../aspose.pdf/document/)
* класс [TiffDevice](../)
* пространство имен [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* сборка [Aspose.PDF](../../../)

---

## Process(Page, Stream) {#process_4}

```csharp
public override void Process(Page page, Stream output)
```

### См. также

* класс [Page](../../../aspose.pdf/page/)
* класс [TiffDevice](../)
* пространство имен [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* сборка [Aspose.PDF](../../../)