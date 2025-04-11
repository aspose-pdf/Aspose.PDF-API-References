---
title: TextDevice.Encoding
second_title: Aspose.PDF for .NET API Reference
description: Свойство TextDevice. Получает или задает кодировку извлеченного текста
type: docs
weight: 20
url: /ru/net/aspose.pdf.devices/textdevice/encoding/
---
## Свойство TextDevice.Encoding

Получает или задает кодировку извлеченного текста.

```csharp
public Encoding Encoding { get; set; }
```

## Примеры

Пример демонстрирует, как представить извлеченный текст в кодировке UTF-8.

```csharp
Document doc = new Document(inFile);
string extractedText;

// create text device
TextDevice device = new TextDevice(Encoding.UTF8);

// convert the page and save text to the stream
device.Process(doc.Pages[1], outFile);

// use the extracted text
extractedText = File.ReadAllText(outFile, Encoding.UTF8);
```

### См. также

* класс [TextDevice](../)
* пространство имен [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* сборка [Aspose.PDF](../../../)