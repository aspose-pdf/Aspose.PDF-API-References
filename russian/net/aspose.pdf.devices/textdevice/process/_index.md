---
title: TextDevice.Process
second_title: Aspose.PDF for .NET API Reference
description: Метод TextDevice. Преобразовать страницу и сохранить её как текстовый поток
type: docs
weight: 40
url: /ru/net/aspose.pdf.devices/textdevice/process/
---
## Метод TextDevice.Process

Преобразовать страницу и сохранить её как текстовый поток.

```csharp
public override void Process(Page page, Stream output)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| page | Page | Страница для преобразования. |
| output | Stream | Результирующий поток. |

## Примеры

Пример демонстрирует, как извлечь текст на первой странице PDF документа.

```csharp
Document doc = new Document(inFile);
string extractedText;

using (MemoryStream ms = new MemoryStream())
{
    // create text device
    TextDevice device = new TextDevice();

    // convert the page and save text to the stream
    device.Process(doc.Pages[1], ms);

    // use the extracted text
    ms.Close();
    extractedText = Encoding.Unicode.GetString(ms.ToArray());
}
```

### См. также

* класс [Page](../../../aspose.pdf/page/)
* класс [TextDevice](../)
* пространство имен [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* сборка [Aspose.PDF](../../../)