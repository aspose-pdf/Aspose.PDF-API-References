---
title: Interface IInterruptMonitor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Multithreading.IInterruptMonitor 인터페이스. 중단에 대한 정보를 나타냅니다.
type: docs
weight: 6990
url: /ko/net/aspose.pdf.multithreading/iinterruptmonitor/
---
## IInterruptMonitor 인터페이스

중단에 대한 정보를 나타냅니다.

```csharp
public interface IInterruptMonitor : IDisposable
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [CancellationToken](../../aspose.pdf.multithreading/iinterruptmonitor/cancellationtoken/) { get; } | 프로세스 중단에 사용되는 모니터의 취소 토큰. 기본적으로 각 IInterruptMonitor는 자체 취소 소스를 생성합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Interrupt](../../aspose.pdf.multithreading/iinterruptmonitor/interrupt/)() | 작업 중단 요청을 보냅니다. |

### 참조

* 네임스페이스 [Aspose.Pdf.Multithreading](../../aspose.pdf.multithreading/)
* 어셈블리 [Aspose.PDF](../../)