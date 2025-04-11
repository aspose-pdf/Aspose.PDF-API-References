---
title: Document.Pages
second_title: Aspose.PDF for .NET API Reference
description: 문서 속성. 문서 페이지 컬렉션을 가져오거나 설정합니다. 페이지는 컬렉션에서 1부터 번호가 매겨진다는 점에 유의하십시오.
type: docs
weight: 470
url: /ko/net/aspose.pdf/document/pages/
---
## Document.Pages 속성

문서 페이지 컬렉션을 가져오거나 설정합니다. 페이지는 컬렉션에서 1부터 번호가 매겨진다는 점에 유의하십시오.

```csharp
public PageCollection Pages { get; }
```

## 예제

아래 예제는 문서 페이지를 다루는 방법을 보여줍니다: 페이지 수를 얻는 방법과 문서의 시작 페이지의 사각형을 얻는 방법.

```csharp
Aspose.Pdf.Document document = new Aspose.Pdf.Document("sample.pdf");
Aspose.Pdf.PageCollection pages = document.Pages;
System.Console.WriteLine("Document contains " + pages.Count);
Page page = pages[1];
Rectangle rect = page.Rect;        
```

### 참조

* class [PageCollection](../../pagecollection/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)