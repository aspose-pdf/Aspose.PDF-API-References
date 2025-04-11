---
title: Document.OpenAction
second_title: Aspose.PDF for .NET API Reference
description: 문서 속성. 문서 열기 시 수행되는 작업을 가져오거나 설정합니다.
type: docs
weight: 390
url: /ko/net/aspose.pdf/document/openaction/
---
## Document.OpenAction 속성

문서 열기 시 수행되는 작업을 가져오거나 설정합니다.

```csharp
public IAppointment OpenAction { get; set; }
```

## 예제

예제는 CenterWindow 플래그를 가져오는 방법을 보여줍니다:

```csharp
Document document = new Document("sample.pdf");
IAppointment value = document.OpenAction;
```

### 참조

* 인터페이스 [IAppointment](../../../aspose.pdf.annotations/iappointment/)
* 클래스 [Document](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)