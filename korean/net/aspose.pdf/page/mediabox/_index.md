---
title: Page.MediaBox
second_title: Aspose.PDF for .NET API Reference
description: 페이지 속성. 페이지의 미디어 박스를 가져오거나 설정합니다.
type: docs
weight: 180
url: /ko/net/aspose.pdf/page/mediabox/
---
## Page.MediaBox 속성

페이지의 미디어 박스를 가져오거나 설정합니다.

```csharp
public Rectangle MediaBox { get; set; }
```

## 예제

예제는 페이지의 미디어 박스를 가져오는 방법을 보여줍니다:

```csharp
Document document = new Document("sample.pdf");
Rectangle mediaBox = document.Pages[1].MediaBox;
```

### 참조

* 클래스 [Rectangle](../../rectangle/)
* 클래스 [Page](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)