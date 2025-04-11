---
title: TextDevice.ExtractionOptions
second_title: Aspose.PDF for .NET API Reference
description: Свойство TextDevice. Получает или устанавливает параметры извлечения текста
type: docs
weight: 30
url: /ru/net/aspose.pdf.devices/textdevice/extractionoptions/
---
## Свойство TextDevice.ExtractionOptions

Получает или устанавливает параметры извлечения текста.

```csharp
public TextExtractionOptions ExtractionOptions { get; set; }
```

## Примеры

Пример демонстрирует, как извлечь текст в сыром порядке.

```csharp
Document doc = new Document(inFile);
string extractedText;

// create text device
TextDevice device = new TextDevice(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Raw));

// convert the page and save text to the stream
device.Process(doc.Pages[1], outFile);

// use the extracted text
extractedText = File.ReadAllText(outFile, Encoding.Unicode); 
```

### См. также

* класс [TextExtractionOptions](../../../aspose.pdf.text/textextractionoptions/)
* класс [TextDevice](../)
* пространство имен [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* сборка [Aspose.PDF](../../../)