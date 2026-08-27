---
title: "Класс TextDevice"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Devices.TextDevice. Представляет класс для преобразования страниц PDF‑документа в текст"
type: docs
weight: 3800
url: /ru/net/aspose.pdf.devices/textdevice/
---
## TextDevice class

Представляет класс для преобразования страниц pdf‑документа в текст.

```csharp
public sealed class TextDevice : PageDevice
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TextDevice](textdevice/#constructor)() | Инициализирует новый экземпляр `TextDevice` с режимом форматирования Raw text и кодировкой Unicode. |
| [TextDevice](textdevice/#constructor_3)(Encoding) | Инициализирует новый экземпляр `TextDevice` для указанной кодировки. |
| [TextDevice](textdevice/#constructor_1)(TextExtractionOptions) | Инициализирует новый экземпляр `TextDevice` с параметрами извлечения текста. |
| [TextDevice](textdevice/#constructor_2)(TextExtractionOptions, Encoding) | Инициализирует новый экземпляр `TextDevice` для указанной кодировки с параметрами извлечения текста. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Encoding](../../aspose.pdf.devices/textdevice/encoding/) { get; set; } | Получает или задаёт кодировку извлечённого текста. |
| [ExtractionOptions](../../aspose.pdf.devices/textdevice/extractionoptions/) { get; set; } | Получает или задаёт параметры извлечения текста. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Process](../../aspose.pdf.devices/textdevice/process/#process)(Page, Stream) | Преобразовать страницу и сохранить её как текстовый поток. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Выполняет некоторую операцию на указанной странице и сохраняет результаты в файл. |

## Примечания

Объект `TextDevice` в основном используется для извлечения текста из страницы PDF.

## Примеры

Пример демонстрирует, как извлечь текст на первой странице PDF‑документа.

```csharp
Document doc = new Document(inFile);
string extractedText;

using (MemoryStream ms = new MemoryStream())
{
    // создать текстовое устройство
    TextDevice device = new TextDevice();

    // преобразовать страницу и сохранить текст в поток
    device.Process(doc.Pages[1], ms);

    // использовать извлечённый текст
    ms.Close();
    extractedText = Encoding.Unicode.GetString(ms.ToArray());
}
```

### См. также

* class [PageDevice](../pagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


