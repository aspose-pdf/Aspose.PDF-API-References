---
title: "Matrix.Skew"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Matrix 메서드. 지정된 회전 각도에 대한 행렬을 생성합니다"
type: docs
weight: 30
url: /ko/net/aspose.pdf/matrix/skew/
---
## Matrix.Skew method

주어진 회전 각도에 대한 Matrix를 생성합니다.

```csharp
public static Matrix Skew(double alpha, double beta)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| alpha | Double | Skew x 각도(라디안). |
| beta | Double | Skew y 각도(라디안). |

### 반환 값

변환 행렬.

## 예제

```csharp
Matrix m = Matrix.Skew(Math.PI / 2, Math.PI / 2);
```

### 또 보기

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


