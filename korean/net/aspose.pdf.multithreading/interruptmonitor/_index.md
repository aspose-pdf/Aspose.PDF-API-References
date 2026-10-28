---
title: "클래스 InterruptMonitor"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Multithreading.InterruptMonitor 클래스. 중단에 대한 정보를 나타냅니다."
type: docs
weight: 7140
url: /ko/net/aspose.pdf.multithreading/interruptmonitor/
---
## InterruptMonitor class

중단에 대한 정보를 나타냅니다.

```csharp
public class InterruptMonitor : IInterruptMonitor
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [InterruptMonitor](interruptmonitor/)() | 기본 생성자. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [CancellationToken](../../aspose.pdf.multithreading/interruptmonitor/cancellationtoken/) { get; } | 프로세스 중단에 사용되는 Monitor의 취소 토큰입니다. 기본적으로 각 IInterruptMonitor는 자체 cancellationSource를 생성합니다. |
| static [ThreadLocalInstance](../../aspose.pdf.multithreading/interruptmonitor/threadlocalinstance/) { get; set; } | 각 스레드마다 고유한 IInterruptMonitor 인스턴스를 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Dispose](../../aspose.pdf.multithreading/interruptmonitor/dispose/)() | 사용된 리소스를 해제합니다. |
| virtual [Interrupt](../../aspose.pdf.multithreading/interruptmonitor/interrupt/)() | 작업을 중단하도록 요청을 보냅니다. |

### 또 보기

* interface [IInterruptMonitor](../iinterruptmonitor/)
* namespace [Aspose.Pdf.Multithreading](../../aspose.pdf.multithreading/)
* assembly [Aspose.PDF](../../)


