---
title: "Page.Duration"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Page 속성. 페이지 표시 지속 시간을 가져오거나 설정합니다. 이는 프레젠테이션 중 페이지가 표시되는 시간(초)이며, 지속 시간이 정의되지 않은 경우 1을 반환합니다"
type: docs
weight: 110
url: /ko/net/aspose.pdf/page/duration/
---
## Page.Duration property

페이지 표시 지속 시간을 가져오거나 설정합니다. 이는 프레젠테이션 중에 페이지가 표시되는 시간(초)입니다. 지속 시간이 정의되지 않은 경우 -1을 반환합니다.

```csharp
public double Duration { get; set; }
```

## 예제

예제는 페이지 지속 시간을 가져오는 방법을 보여줍니다

```csharp
Document document = new Document("sample.pdf");
Page page = document.Pages[1];
int pageRect = page.Duration;
```

### 또 보기

* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


