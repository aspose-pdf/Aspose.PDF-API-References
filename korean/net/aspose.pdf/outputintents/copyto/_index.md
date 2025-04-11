---
title: OutputIntents.CopyTo
second_title: Aspose.PDF for .NET API Reference
description: OutputIntents 메서드. 특정 arrayIndex에서 배열로 컬렉션의 요소를 복사합니다.
type: docs
weight: 70
url: /ko/net/aspose.pdf/outputintents/copyto/
---
## OutputIntents.CopyTo 메서드

컬렉션의 요소를 *array*에 복사하며, 특정 *arrayIndex*에서 배열로 복사합니다.

```csharp
public void CopyTo(OutputIntent[] array, int arrayIndex)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| array | OutputIntent[] | 컬렉션에서 복사된 출력 의도가 저장될 일차원 배열입니다. 배열은 0 기반 인덱싱을 가져야 합니다. |
| arrayIndex | Int32 | 복사가 시작되는 *array*의 0 기반 인덱스입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *array*가 null입니다. |
| ArgumentOutOfRangeException | *arrayIndex*가 0보다 작습니다. |
| ArgumentException | 소스 [`OutputIntents`](../)의 요소 수가 *arrayIndex*에서 대상 *array*의 끝까지 사용 가능한 공간보다 큽니다. |

### 참조

* 클래스 [OutputIntent](../../outputintent/)
* 클래스 [OutputIntents](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)