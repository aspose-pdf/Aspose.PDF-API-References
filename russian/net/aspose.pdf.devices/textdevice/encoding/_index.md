---
title: "TextDevice.Encoding"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство TextDevice. Получает или задаёт кодировку извлечённого текста."
type: docs
weight: 20
url: /ru/net/aspose.pdf.devices/textdevice/encoding/
---
## TextDevice.Encoding property

Получает или задаёт кодировку извлечённого текста.

```csharp
public Encoding Encoding { get; set; }
```

## Примеры

Пример демонстрирует, как представить извлечённый текст в кодировке UTF-8.

```csharp
Document doc = new Document(inFile);
string extractedText;

// создать текстовое устройство
TextDevice device = new TextDevice(Encoding.UTF8);

// преобразовать страницу и сохранить текст в поток
device.Process(doc.Pages[1], outFile);

// использовать извлечённый текст
extractedText = File.ReadAllText(outFile, Encoding.UTF8);
```

### См. также

* class [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)


