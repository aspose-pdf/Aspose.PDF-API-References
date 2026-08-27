---
title: "TextDevice.ExtractionOptions"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство TextDevice. Получает или задаёт параметры извлечения текста."
type: docs
weight: 30
url: /ru/net/aspose.pdf.devices/textdevice/extractionoptions/
---
## TextDevice.ExtractionOptions property

Получает или задаёт параметры извлечения текста.

```csharp
public TextExtractionOptions ExtractionOptions { get; set; }
```

## Примеры

Пример демонстрирует, как извлечь текст в исходном порядке.

```csharp
Document doc = new Document(inFile);
string extractedText;

// создать текстовое устройство
TextDevice device = new TextDevice(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Raw));

// преобразовать страницу и сохранить текст в поток
device.Process(doc.Pages[1], outFile);

// использовать извлечённый текст
extractedText = File.ReadAllText(outFile, Encoding.Unicode); 
```

### См. также

* class [TextExtractionOptions](../../../aspose.pdf.text/textextractionoptions/)
* class [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)


