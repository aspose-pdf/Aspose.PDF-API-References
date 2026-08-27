---
title: "OutputIntents.CopyTo"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "OutputIntents 메서드. 컬렉션의 요소를 특정 arrayIndex에서 시작하여 배열에 복사합니다."
type: docs
weight: 70
url: /ko/net/aspose.pdf/outputintents/copyto/
---
## OutputIntents.CopyTo method

컬렉션의 요소를 *array*에 복사하고, 특정 *arrayIndex*부터 배열에 삽입합니다.

```csharp
public void CopyTo(OutputIntent[] array, int arrayIndex)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 배열 | OutputIntent[] | 컬렉션에서 복사된 출력 의도의 대상이 되는 1차원 배열입니다. 배열은 0부터 시작하는 인덱스를 가져야 합니다. |
| arrayIndex | Int32 | *array*에서 복사가 시작되는 0 기반 인덱스입니다. |

### 예외

| 예외 | 조건 |
| --- | --- |
| ArgumentNullException | *array*이 null입니다. |
| ArgumentOutOfRangeException | *arrayIndex*이 0보다 작습니다. |
| ArgumentException | 소스 [`OutputIntents`](../)의 요소 수가 *arrayIndex*부터 대상 *array* 끝까지 사용 가능한 공간보다 많습니다. |

### 또 보기

* class [OutputIntent](../../outputintent/)
* class [OutputIntents](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


