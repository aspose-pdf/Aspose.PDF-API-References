---
title: Document.TaggedContent
second_title: Aspose.PDF for .NET API Reference
description: Свойство документа. Получает доступ к содержимому TaggedPdf
type: docs
weight: 520
url: /ru/net/aspose.pdf/document/taggedcontent/
---
## Свойство Document.TaggedContent

Получает доступ к содержимому TaggedPdf.

```csharp
public ITaggedContent TaggedContent { get; }
```

## Примеры

Пример демонстрирует, как использовать помеченное содержимое для создания нового документа с заголовком, абзацами и изображениями.

```csharp
// Create new document
Document document = new Document();

// Get the tagged content
ITaggedContent taggedContent = document.TaggedContent;

// Set language for document
taggedContent.SetLanguage("en-US");

// Set title for PDF document
taggedContent.SetTitle("Example document");

// Creating and adding Section
SectElement sect = taggedContent.CreateSectElement();
taggedContent.RootElement.AppendChild(sect);

// Create Header
HeaderElement h1 = taggedContent.CreateHeaderElement(1);
h1.SetText("The Header");
sect.AppendChild(h1);

// Create paragraph
ParagraphElement p = taggedContent.CreateParagraphElement();
p.SetTag("Paragraph");
p.SetText("The text of paragraph.");
sect.AppendChild(p);

// Create illustration
IllustrationElement figure1 = taggedContent.CreateFigureElement();
sect.AppendChild(figure1);
figure1.AlternativeText = "Figure 1";
figure1.Title = "Image 1";
figure1.SetTag("Fig");
figure1.SetImage("path/of/image.jpg");

// Save document
document.Save("example.pdf");
```

### См. также

* интерфейс [ITaggedContent](../../../aspose.pdf.tagged/itaggedcontent/)
* класс [Document](../)
* пространство имен [Aspose.Pdf](../../../aspose.pdf/)
* сборка [Aspose.PDF](../../../)