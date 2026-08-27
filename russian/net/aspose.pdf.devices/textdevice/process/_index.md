---
title: "TextDevice.Process"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Метод TextDevice. Преобразует страницу и сохраняет её как текстовый поток."
type: docs
weight: 40
url: /ru/net/aspose.pdf.devices/textdevice/process/
---
## TextDevice.Process method

Преобразовать страницу и сохранить её как текстовый поток.

```csharp
public override void Process(Page page, Stream output)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| страница | Страница | Страница для преобразования. |
| output | Stream | Поток результата. |

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

* class [Page](../../../aspose.pdf/page/)
* class [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)


