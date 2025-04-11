---
title: Matrix.Multiply
second_title: Aspose.PDF for .NET API Reference
description: 행렬 메서드. 다른 행렬로 행렬을 곱합니다.
type: docs
weight: 170
url: /ko/net/aspose.pdf/matrix/multiply/
---
## Matrix.Multiply 메서드

다른 행렬로 행렬을 곱합니다.

```csharp
public Matrix Multiply(Matrix other)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| other | Matrix | 곱셈 행렬. |

### 반환 값

곱셈 결과.

## 예제

```csharp
Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 });
Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } );
Matrix c= a.Multiply(b);
```

### 참조

* 클래스 [Matrix](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)