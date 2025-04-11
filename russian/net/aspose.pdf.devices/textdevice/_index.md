---
title: Class TextDevice
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Devices.TextDevice. Представляет класс для преобразования страниц pdf документа в текст
type: docs
weight: 3680
url: /ru/net/aspose.pdf.devices/textdevice/
---
## Класс TextDevice

Представляет класс для преобразования страниц pdf документа в текст.

```csharp
public sealed class TextDevice : PageDevice
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextDevice](textdevice/#constructor)() | Инициализирует новый экземпляр `TextDevice` с режимом форматирования сырого текста и кодировкой текста Unicode. |
| [TextDevice](textdevice/#constructor_3)(Encoding) | Инициализирует новый экземпляр `TextDevice` для указанной кодировки. |
| [TextDevice](textdevice/#constructor_1)(TextExtractionOptions) | Инициализирует новый экземпляр `TextDevice` с параметрами извлечения текста. |
| [TextDevice](textdevice/#constructor_2)(TextExtractionOptions, Encoding) | Инициализирует новый экземпляр `TextDevice` для указанной кодировки с параметрами извлечения текста. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Encoding](../../aspose.pdf.devices/textdevice/encoding/) { get; set; } | Получает или задает кодировку извлеченного текста. |
| [ExtractionOptions](../../aspose.pdf.devices/textdevice/extractionoptions/) { get; set; } | Получает или задает параметры извлечения текста. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Process](../../aspose.pdf.devices/textdevice/process/#process)(Page, Stream) | Преобразует страницу и сохраняет ее как текстовый поток. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Выполняет некоторую операцию на данной странице и сохраняет результаты в файл. |

## Замечания

Объект `TextDevice` в основном используется для извлечения текста из страницы pdf.

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

* класс [PageDevice](../pagedevice/)
* пространство имен [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* сборка [Aspose.PDF](../../)