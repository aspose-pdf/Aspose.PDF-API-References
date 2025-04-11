---
title: TextAbsorber.Text
second_title: Aspose.PDF for .NET API Reference
description: Свойство TextAbsorber. Получает извлеченный текст, который TextAbsorber извлекает из PDF-документа или страницы
type: docs
weight: 50
url: /ru/net/aspose.pdf.text/textabsorber/text/
---
## Свойство TextAbsorber.Text

Получает извлеченный текст, который [`TextAbsorber`](../) извлекает из PDF-документа или страницы.

```csharp
public virtual string Text { get; }
```

## Примеры

Пример демонстрирует, как извлечь текст со всех страниц PDF-документа.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
doc.Pages.Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;

```

### См. также

* класс [TextAbsorber](../)
* пространство имен [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* сборка [Aspose.PDF](../../../)