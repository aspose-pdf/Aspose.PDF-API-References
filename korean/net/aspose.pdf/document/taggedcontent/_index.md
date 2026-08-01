---
title: "Document.TaggedContent"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Document 속성. TaggedPdf 콘텐츠에 대한 접근을 가져옵니다"
type: docs
weight: 540
url: /ko/net/aspose.pdf/document/taggedcontent/
---
## Document.TaggedContent property

TaggedPdf 콘텐츠에 대한 접근을 가져옵니다.

```csharp
public ITaggedContent TaggedContent { get; }
```

## 예제

예제는 헤더, 단락 및 이미지가 포함된 새 문서를 만들기 위해 태그된 콘텐츠를 사용하는 방법을 보여줍니다.

```csharp
// 새 문서 만들기
Document document = new Document();

// 태그된 콘텐츠 가져오기
ITaggedContent taggedContent = document.TaggedContent;

// 문서의 언어 설정
taggedContent.SetLanguage("en-US");

// PDF 문서의 제목 설정
taggedContent.SetTitle("Example document");

// 섹션 생성 및 추가
SectElement sect = taggedContent.CreateSectElement();
taggedContent.RootElement.AppendChild(sect);

// 헤더 만들기
HeaderElement h1 = taggedContent.CreateHeaderElement(1);
h1.SetText("The Header");
sect.AppendChild(h1);

// 단락 만들기
ParagraphElement p = taggedContent.CreateParagraphElement();
p.SetTag("Paragraph");
p.SetText("The text of paragraph.");
sect.AppendChild(p);

// 삽화 만들기
IllustrationElement figure1 = taggedContent.CreateFigureElement();
sect.AppendChild(figure1);
figure1.AlternativeText = "Figure 1";
figure1.Title = "Image 1";
figure1.SetTag("Fig");
figure1.SetImage("path/of/image.jpg");

// 문서 저장
document.Save("example.pdf");
```

### 또 보기

* interface [ITaggedContent](../../../aspose.pdf.tagged/itaggedcontent/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


