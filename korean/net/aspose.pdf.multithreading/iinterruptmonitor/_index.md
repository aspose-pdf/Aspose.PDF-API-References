---
title: "인터페이스 IInterruptMonitor"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Multithreading.IInterruptMonitor 인터페이스. 중단에 대한 정보를 나타냅니다."
type: docs
weight: 7130
url: /ko/net/aspose.pdf.multithreading/iinterruptmonitor/
---
## IInterruptMonitor interface

중단에 대한 정보를 나타냅니다.

```csharp
public interface IInterruptMonitor : IDisposable
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [CancellationToken](../../aspose.pdf.multithreading/iinterruptmonitor/cancellationtoken/) { get; } | 프로세스 중단에 사용되는 모니터의 취소 토큰입니다. 기본적으로 각 IInterruptMonitor는 자체 cancellationSource를 생성합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Interrupt](../../aspose.pdf.multithreading/iinterruptmonitor/interrupt/)() | 작업을 중단하도록 요청을 보냅니다. |

### 또 보기

* namespace [Aspose.Pdf.Multithreading](../../aspose.pdf.multithreading/)
* assembly [Aspose.PDF](../../)


