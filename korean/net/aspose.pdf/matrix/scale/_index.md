---
title: Matrix.Scale
second_title: Aspose.PDF for .NET API Reference
description: Matrix 메서드. 다음 공식을 사용하여 행렬로 x와 y를 스케일합니다: x1 = Ax + Cy, y1 = Bx + Dy
type: docs
weight: 190
url: /ko/net/aspose.pdf/matrix/scale/
---
## Scale(double, double, out double, out double)

다음 공식을 사용하여 행렬로 x와 y를 스케일합니다: x1 = A*x + C*y; y1 = B*x + D*y;

```csharp
public void Scale(double x, double y, out double x1, out double y1)
```

| Parameter | Type | Description |
| --- | --- | --- |
| x | Double | 입력 X 좌표 |
| y | Double | 입력 Y 좌표 |
| x1 | Double& | 출력 X 좌표 |
| y1 | Double& | 출력 Y 좌표 |

### See Also

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Scale(double, double, Matrix)

주어진 행렬에 스케일링을 적용합니다.

```csharp
public static Matrix Scale(double sx, double sy, Matrix source)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sx | Double | X축의 스케일링 계수. |
| sy | Double | Y축의 스케일링 계수. |
| source | Matrix | 스케일할 행렬. |

### Return Value

소스 행렬을 스케일링한 결과인 새로운 행렬입니다.

### See Also

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)