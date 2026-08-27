---
title: "Page.Resources"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Page 속성. 페이지 리소스를 가져옵니다. Resources 객체는 이미지, 폼 및 폰트 컬렉션을 포함합니다. Resources"
type: docs
weight: 240
url: /ko/net/aspose.pdf/page/resources/
---
## Page.Resources property

페이지 리소스를 가져옵니다. Resources 객체는 이미지, 폼 및 글꼴 컬렉션을 포함합니다. `Resources`

```csharp
public Resources Resources { get; }
```

## 예제

예제는 페이지 이미지 스캔을 보여줍니다:

```csharp
Document document = new Document("sample.pdf");
DocumentActions actions = document.Actions;
Resources resources = document.Pages[1].Resources;
foreach(XImage image in resources.Images)
{
  Console.WriteLine(image.Width + ":" + image.Height);
}
```

### 또 보기

* class [Resources](../../resources/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


