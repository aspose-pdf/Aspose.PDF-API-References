---
title: Page.Duration
second_title: Aspose.PDF for .NET API Reference
description: 페이지 속성. 설정된 페이지 표시 지속 시간을 가져옵니다. 이는 프레젠테이션 중에 페이지가 표시되는 시간(초)입니다. 지속 시간이 정의되지 않은 경우 1을 반환합니다.
type: docs
weight: 110
url: /ko/net/aspose.pdf/page/duration/
---
## Page.Duration 속성

설정된 페이지 표시 지속 시간을 가져옵니다. 이는 프레젠테이션 중에 페이지가 표시되는 시간(초)입니다. 지속 시간이 정의되지 않은 경우 -1을 반환합니다.

```csharp
public double Duration { get; set; }
```

## 예제

예제는 페이지 지속 시간을 가져오는 방법을 보여줍니다.

```csharp
Document document = new Document("sample.pdf");
Page page = document.Pages[1];
int pageRect = page.Duration;
```

### 참조

* 클래스 [Page](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)