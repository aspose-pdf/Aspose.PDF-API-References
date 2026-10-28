---
title: "Matrix.UnTransform"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Matrix 메서드. 다음 공식을 사용하여 x1 및 y1을 역변환하고 행렬 변환 이전의 x와 y를 반환합니다 x  D  x1  C  y1  C  F / A  D  C  B y  A  y1  B  x1  B  E / A  D  C  B"
type: docs
weight: 230
url: /ko/net/aspose.pdf/matrix/untransform/
---
## Matrix.UnTransform method

다음 공식을 사용하여 x1과 y1을 역변환하고 행렬 변환 이전의 x와 y를 반환합니다: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B).

```csharp
public void UnTransform(double x1, double y1, out double x, out double y)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x1 | Double | 입력 X 좌표 |
| y1 | Double | 입력 Y 좌표 |
| x | Double& | 출력 X 좌표 |
| y | Double& | 출력 Y 좌표 |

### 또 보기

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


