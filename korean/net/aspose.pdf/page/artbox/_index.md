---
title: Page.ArtBox
second_title: Aspose.PDF for .NET API Reference
description: 페이지 속성. 페이지의 아트 박스를 가져오거나 설정합니다.
type: docs
weight: 30
url: /ko/net/aspose.pdf/page/artbox/
---
## Page.ArtBox 속성

페이지의 아트 박스를 가져오거나 설정합니다.

```csharp
public Rectangle ArtBox { get; set; }
```

## 예제

예제는 페이지의 아트 박스를 가져오는 방법을 보여줍니다:

```csharp
Document document = new Document("sample.pdf");
Rectangle artBox = document.Pages[1].ArtBox;
```

### 참조

* 클래스 [Rectangle](../../rectangle/)
* 클래스 [Page](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)