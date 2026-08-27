---
title: "TextAbsorber.ExtractionOptions"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство TextAbsorber. Получает или задает параметры извлечения текста"
type: docs
weight: 30
url: /ru/net/aspose.pdf.text/textabsorber/extractionoptions/
---
## TextAbsorber.ExtractionOptions property

Получает или задаёт параметры извлечения текста.

```csharp
public virtual TextExtractionOptions ExtractionOptions { get; set; }
```

## Примечания

Позволяет задать режим форматирования текста [`TextExtractionOptions`](../../textextractionoptions/) во время извлечения. Режим по умолчанию — Pure

## Примеры

Пример демонстрирует, как установить режим форматирования текста Pure и выполнить извлечение текста.

```csharp
// открыть документ
Document doc = new Document(inFile);

// создать объект TextAbsorber для извлечения текста с форматированием
TextAbsorber absorber = new TextAbsorber();

// установить режим чистого форматирования текста
absorber.ExtractionOptions = new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure);

// принять поглотитель для всех страниц документа
doc.Pages.Accept(absorber);

// получить извлечённый текст
string extractedText = absorber.Text;
```

### См. также

* class [TextExtractionOptions](../../textextractionoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


