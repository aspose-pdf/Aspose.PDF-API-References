---
title: "Document.Pages"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Document 속성. 문서 페이지 컬렉션을 가져오거나 설정합니다. 컬렉션의 페이지 번호는 1부터 시작한다는 점에 유의하세요."
type: docs
weight: 490
url: /ko/net/aspose.pdf/document/pages/
---
## Document.Pages property

document 페이지 컬렉션을 가져오거나 설정합니다. 컬렉션에서 페이지 번호는 1부터 시작한다는 점에 유의하십시오.

```csharp
public PageCollection Pages { get; }
```

## 예제

아래 예제는 문서 페이지를 조작하는 방법을 보여줍니다: 페이지 수를 얻는 방법과 문서 시작 페이지의 사각형을 얻는 방법.

```csharp
Aspose.Pdf.Document document = new Aspose.Pdf.Document("sample.pdf");
Aspose.Pdf.PageCollection pages = document.Pages;
System.Console.WriteLine("Document contains " + pages.Count);
Page page = pages[1];
Rectangle rect = page.Rect;        
```

### 또 보기

* class [PageCollection](../../pagecollection/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


