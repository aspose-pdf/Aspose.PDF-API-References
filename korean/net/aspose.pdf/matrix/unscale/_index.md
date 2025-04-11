---
title: Matrix.UnScale
second_title: Aspose.PDF for .NET API Reference
description: Matrix 메서드. 다음 공식을 사용하여 x1과 y1을 다시 조정하고 행렬 변환 이전의 x와 y를 반환합니다: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B);
type: docs
weight: 220
url: /ko/net/aspose.pdf/matrix/unscale/
---
## Matrix.UnScale 메서드

다음 공식을 사용하여 x1과 y1을 다시 조정하고 행렬 변환 이전의 x와 y를 반환합니다: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B);

```csharp
public void UnScale(double x1, double y1, out double x, out double y)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x1 | Double | 입력 X 좌표 |
| y1 | Double | 입력 Y 좌표 |
| x | Double& | 출력 X 좌표 |
| y | Double& | 출력 Y 좌표 |

### 참조

* 클래스 [Matrix](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)