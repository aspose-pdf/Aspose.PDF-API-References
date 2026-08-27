---
title: "Document.TaggedContent"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Свойство Document. Возвращает доступ к содержимому TaggedPdf."
type: docs
weight: 540
url: /ru/net/aspose.pdf/document/taggedcontent/
---
## Document.TaggedContent property

Получает доступ к содержимому TaggedPdf.

```csharp
public ITaggedContent TaggedContent { get; }
```

## Примеры

Пример демонстрирует, как использовать помеченный контент для создания нового документа с заголовком, абзацами и изображениями.

```csharp
// Создать новый документ
Document document = new Document();

// Получить тегированное содержимое
ITaggedContent taggedContent = document.TaggedContent;

// Установить язык для документа
taggedContent.SetLanguage("en-US");

// Установить заголовок для PDF-документа
taggedContent.SetTitle("Example document");

// Создание и добавление раздела
SectElement sect = taggedContent.CreateSectElement();
taggedContent.RootElement.AppendChild(sect);

// Создать заголовок
HeaderElement h1 = taggedContent.CreateHeaderElement(1);
h1.SetText("The Header");
sect.AppendChild(h1);

// Создать абзац
ParagraphElement p = taggedContent.CreateParagraphElement();
p.SetTag("Paragraph");
p.SetText("The text of paragraph.");
sect.AppendChild(p);

// Создать иллюстрацию
IllustrationElement figure1 = taggedContent.CreateFigureElement();
sect.AppendChild(figure1);
figure1.AlternativeText = "Figure 1";
figure1.Title = "Image 1";
figure1.SetTag("Fig");
figure1.SetImage("path/of/image.jpg");

// Сохранить документ
document.Save("example.pdf");
```

### См. также

* interface [ITaggedContent](../../../aspose.pdf.tagged/itaggedcontent/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


