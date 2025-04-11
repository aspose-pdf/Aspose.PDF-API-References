---
title: Page.Resources
second_title: Aspose.PDF for .NET API Reference
description: 페이지 속성. 페이지 리소스를 가져옵니다. 리소스 객체는 이미지, 양식 및 글꼴의 컬렉션을 포함합니다. 리소스
type: docs
weight: 240
url: /ko/net/aspose.pdf/page/resources/
---
## Page.Resources 속성

페이지 리소스를 가져옵니다. 리소스 객체는 이미지, 양식 및 글꼴의 컬렉션을 포함합니다. `Resources`

```csharp
public Resources Resources { get; }
```

## 예제

예제는 페이지 이미지를 스캔하는 방법을 보여줍니다:

```csharp
Document document = new Document("sample.pdf");
DocumentActions actions = document.Actions;
Resources resources = document.Pages[1].Resources;
foreach(XImage image in resources.Images)
{
  Console.WriteLine(image.Width + ":" + image.Height);
}
```

### 참조

* 클래스 [Resources](../../resources/)
* 클래스 [Page](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)