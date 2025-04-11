---
title: Page.Rect
second_title: Aspose.PDF for .NET API Reference
description: 페이지 속성. 페이지의 사각형을 가져오거나 설정합니다. 가져올 때는 지정된 경우 페이지 크롭 박스가 반환되고, 그렇지 않으면 페이지 미디어 박스가 반환됩니다. 설정할 때는 페이지 미디어 박스가 항상 설정됩니다. 이 속성은 페이지 회전을 고려하지 않음을 유의하시기 바랍니다. 회전을 고려한 페이지 사각형을 얻으려면 ActualRect를 사용하십시오.
type: docs
weight: 230
url: /ko/net/aspose.pdf/page/rect/
---
## Page.Rect 속성

페이지의 사각형을 가져오거나 설정합니다. 가져올 때: 지정된 경우 페이지 크롭 박스가 반환되고, 그렇지 않으면 페이지 미디어 박스가 반환됩니다. 설정할 때: 페이지 미디어 박스가 항상 설정됩니다. 이 속성은 페이지 회전을 고려하지 않음을 유의하시기 바랍니다. 회전을 고려한 페이지 사각형을 얻으려면 ActualRect를 사용하십시오.

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

### 참조

* 클래스 [Rectangle](../../rectangle/)
* 클래스 [Page](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)