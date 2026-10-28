---
title: "Matrix.Multiply"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Matrix 메서드. 매트릭스를 다른 매트릭스와 곱합니다."
type: docs
weight: 170
url: /ko/net/aspose.pdf/matrix/multiply/
---
## Matrix.Multiply method

다른 행렬에 행렬을 곱합니다.

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

### 또 보기

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


