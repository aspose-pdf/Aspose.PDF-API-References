---
title: Page.Rotate
second_title: Aspose.PDF for .NET API Reference
description: 페이지 속성. 페이지의 회전을 가져오거나 설정합니다.
type: docs
weight: 250
url: /ko/net/aspose.pdf/page/rotate/
---
## Page.Rotate 속성

페이지의 회전을 가져오거나 설정합니다.

```csharp
public Rotation Rotate { get; set; }
```

## 예제

예제는 페이지 회전을 결정하는 방법을 보여줍니다.

```csharp
Document document = new Document("sample.pdf");
Console.WriteLine(document.Pages[1].Rotate);
```

### 참조

* enum [Rotation](../../rotation/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)