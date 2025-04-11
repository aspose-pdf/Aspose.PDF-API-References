---
title: Matrix.Rotation
second_title: Aspose.PDF for .NET API Reference
description: 행렬 메서드. 주어진 회전 각도에 대한 행렬을 생성합니다.
type: docs
weight: 20
url: /ko/net/aspose.pdf/matrix/rotation/
---
## Rotation(double) {#rotation_1}

주어진 회전 각도에 대한 행렬을 생성합니다.

```csharp
public static Matrix Rotation(double alpha)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| alpha | Double | 라디안 단위의 회전 각도. |

### 반환 값

변환 행렬.

## 예제

```csharp
Matrix m = Matrix.Rotation(Math.PI / 2);
```

### 참조

* 클래스 [Matrix](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)

---

## Rotation(Rotation) {#rotation}

주어진 회전에 대한 행렬을 생성합니다.

```csharp
public static Matrix Rotation(Rotation rotation)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rotation | Rotation | 회전. 유효한 값은: None, on90, on180, on270 |

### 반환 값

회전이 포함된 행렬.

### 참조

* 열거형 [Rotation](../../rotation/)
* 클래스 [Matrix](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)