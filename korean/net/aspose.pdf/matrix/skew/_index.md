---
title: Matrix.Skew
second_title: Aspose.PDF for .NET API Reference
description: 행렬 메서드. 주어진 회전 각도에 대한 행렬을 생성합니다.
type: docs
weight: 30
url: /ko/net/aspose.pdf/matrix/skew/
---
## Matrix.Skew 메서드

주어진 회전 각도에 대한 행렬을 생성합니다.

```csharp
public static Matrix Skew(double alpha, double beta)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| alpha | Double | 라디안 단위의 x 방향 기울기 각도. |
| beta | Double | 라디안 단위의 y 방향 기울기 각도. |

### 반환 값

변환 행렬.

## 예제

```csharp
Matrix m = Matrix.Skew(Math.PI / 2, Math.PI / 2);
```

### 참조

* 클래스 [Matrix](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)