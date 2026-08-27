---
title: "Page.ArtBox"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Page 속성. 페이지의 아트 박스를 가져오거나 설정합니다."
type: docs
weight: 30
url: /ko/net/aspose.pdf/page/artbox/
---
## Page.ArtBox property

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

### 또 보기

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


