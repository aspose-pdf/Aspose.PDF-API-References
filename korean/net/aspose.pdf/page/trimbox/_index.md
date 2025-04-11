---
title: Page.TrimBox
second_title: Aspose.PDF for .NET API Reference
description: 페이지 속성. 페이지의 트림 박스를 가져오거나 설정합니다.
type: docs
weight: 290
url: /ko/net/aspose.pdf/page/trimbox/
---
## Page.TrimBox 속성

페이지의 트림 박스를 가져오거나 설정합니다.

```csharp
public Rectangle TrimBox { get; set; }
```

## 예제

예제는 페이지의 트림 박스를 가져오는 방법을 보여줍니다:

```csharp
Document document = new Document("sample.pdf");
Rectangle trimBox = document.Pages[1].TrimBox;
```

### 참조

* 클래스 [Rectangle](../../rectangle/)
* 클래스 [Page](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)