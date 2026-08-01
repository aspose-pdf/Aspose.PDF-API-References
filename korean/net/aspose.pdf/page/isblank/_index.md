---
title: "Page.IsBlank"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Page 메서드. 페이지가 빈 페이지인지 여부를 나타내는 플래그를 가져옵니다."
type: docs
weight: 490
url: /ko/net/aspose.pdf/page/isblank/
---
## Page.IsBlank method

페이지가 비어 있는지 여부를 나타내는 플래그를 가져옵니다.

```csharp
public bool IsBlank(double fillThresholdFactor)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fillThresholdFactor | Double | 감지 민감도를 관리하는 채움 임계값이며, 범위는 [0..1)이어야 합니다. |

### 반환 값

True - 페이지가 빈 경우; 그렇지 않으면 false.

## 비고

페이지가 비었는지 여부를 판단하기 위해, 채워진 공간과 페이지 전체 공간의 비율을 계산합니다. 이 비율을 fillThresholdFactor 매개변수와 비교하여 작으면 페이지가 비어있는 것으로 간주됩니다.

### 또 보기

* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


