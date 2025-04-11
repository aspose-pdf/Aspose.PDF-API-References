---
title: Page.BleedBox
second_title: Aspose.PDF for .NET API Reference
description: 페이지 속성. 페이지의 블리드 박스를 가져오거나 설정합니다.
type: docs
weight: 70
url: /ko/net/aspose.pdf/page/bleedbox/
---
## Page.BleedBox 속성

페이지의 블리드 박스를 가져오거나 설정합니다.

```csharp
public Rectangle BleedBox { get; set; }
```

## 예제

예제는 페이지의 블리드 박스를 가져오는 방법을 보여줍니다:

```csharp
Document document = new Document("sample.pdf");
Rectangle bleedBox = document.Pages[1].BleedBox;
```

### 참조

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)