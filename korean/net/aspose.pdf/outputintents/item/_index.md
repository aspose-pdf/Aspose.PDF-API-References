---
title: OutputIntents.Item
second_title: Aspose.PDF for .NET API Reference
description: OutputIntents 속성. 지정된 인덱스에서 출력 의도를 가져옵니다.
type: docs
weight: 30
url: /ko/net/aspose.pdf/outputintents/item/
---
## OutputIntents 인덱서

지정된 *인덱스*에서 출력 의도를 가져옵니다.

```csharp
public OutputIntent this[int index] { get; }
```

| 매개변수 | 설명 |
| --- | --- |
| index | 가져올 출력 의도의 0 기반 인덱스입니다. |

### 반환 값

지정된 *인덱스*에서의 출력 의도입니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentOutOfRangeException | *index*가 0보다 작거나 *index*가 [`Count`](../count/)와 같거나 큰 경우입니다. |
| InvalidOperationException | 컬렉션을 포함하는 문서에 OutputIntents에 접근할 수 있는 카탈로그가 없습니다. |

### 참조

* 클래스 [OutputIntent](../../outputintent/)
* 클래스 [OutputIntents](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)