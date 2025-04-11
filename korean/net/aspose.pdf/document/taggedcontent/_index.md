---
title: Document.TaggedContent
second_title: Aspose.PDF for .NET API Reference
description: 문서 속성. TaggedPdf 콘텐츠에 접근합니다.
type: docs
weight: 520
url: /ko/net/aspose.pdf/document/taggedcontent/
---
## Document.TaggedContent 속성

TaggedPdf 콘텐츠에 접근합니다.

```csharp
public ITaggedContent TaggedContent { get; }
```

## 예제

이 예제는 헤더, 단락 및 이미지를 포함한 새 문서를 만들기 위해 태그가 있는 콘텐츠를 사용하는 방법을 보여줍니다.

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

### 참조

* 인터페이스 [ITaggedContent](../../../aspose.pdf.tagged/itaggedcontent/)
* 클래스 [Document](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)