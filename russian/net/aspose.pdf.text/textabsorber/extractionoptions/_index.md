---
title: TextAbsorber.ExtractionOptions
second_title: Aspose.PDF for .NET API Reference
description: Свойство TextAbsorber. Получает или устанавливает параметры извлечения текста
type: docs
weight: 30
url: /ru/net/aspose.pdf.text/textabsorber/extractionoptions/
---
## Свойство TextAbsorber.ExtractionOptions

Получает или устанавливает параметры извлечения текста.

```csharp
public virtual TextExtractionOptions ExtractionOptions { get; set; }
```

## Примечания

Позволяет определить режим форматирования текста [`TextExtractionOptions`](../../textextractionoptions/) во время извлечения. Режим по умолчанию - Pure

## Примеры

Пример демонстрирует, как установить режим форматирования текста Pure и выполнить извлечение текста.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text with formatting
TextAbsorber absorber = new TextAbsorber();

// set pure text formatting mode
absorber.ExtractionOptions = new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure);

// accept the absorber for all document's pages
doc.Pages.Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;
```

### См. также

* класс [TextExtractionOptions](../../textextractionoptions/)
* класс [TextAbsorber](../)
* пространство имен [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../../)