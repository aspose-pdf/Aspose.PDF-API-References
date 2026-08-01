---
title: "Page.Rect"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Page 속성. 페이지의 사각형을 가져오거나 설정합니다. 가져올 경우 지정된 경우 페이지 크롭 박스가 반환되고, 그렇지 않으면 페이지 미디어 박스가 반환됩니다. 설정할 경우 항상 페이지 미디어 박스를 설정합니다. 이 속성은 페이지 회전을 고려하지 않음을 유의하십시오. 회전을 고려한 페이지 사각형을 얻으려면 ActualRect를 사용하십시오."
type: docs
weight: 230
url: /ko/net/aspose.pdf/page/rect/
---
## Page.Rect property

페이지의 사각형을 가져오거나 설정합니다. 가져올 때: 지정된 경우 페이지 크롭 박스를 반환하고, 그렇지 않으면 페이지 미디어 박스를 반환합니다. 설정할 때: 페이지 미디어 박스를 항상 설정합니다. 이 속성은 페이지 회전을 고려하지 않으므로, 회전을 고려한 페이지 사각형을 얻으려면 ActualRect를 사용하십시오.

```csharp
public Rectangle Rect { get; set; }
```

## 예제

예제는 페이지 사각형을 가져오는 방법을 보여줍니다:

```csharp
Document document = new Document("sample.pdf");
Page page = document.Pages[1];
Rectangle pageRect = page.Rect;
```

### 또 보기

* class [Rectangle](../../rectangle/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


