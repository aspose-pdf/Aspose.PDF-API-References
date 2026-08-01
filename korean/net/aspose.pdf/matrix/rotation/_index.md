---
title: "Matrix.Rotation"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Matrix 메서드. 지정된 회전 각도에 대한 행렬을 생성합니다"
type: docs
weight: 20
url: /ko/net/aspose.pdf/matrix/rotation/
---
## Rotation(double) {#rotation_1}

주어진 회전 각도에 대한 Matrix를 생성합니다.

```csharp
public static Matrix Rotation(double alpha)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| alpha | Double | 라디안 단위 회전 각도. |

### 반환 값

변환 행렬.

## 예제

```csharp
Matrix m = Matrix.Rotation(Math.PI / 2);
```

### 또 보기

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Rotation(Rotation) {#rotation}

주어진 회전에 대한 Matrix를 생성합니다.

```csharp
public static Matrix Rotation(Rotation rotation)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 회전 | 회전 | 회전. 유효값: None, on90, on180, on270 |

### 반환 값

회전이 적용된 Matrix.

### 또 보기

* enum [Rotation](../../rotation/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


