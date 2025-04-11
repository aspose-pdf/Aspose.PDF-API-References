---
title: Matrix3D.Matrix3D
second_title: Aspose.PDF for .NET API Reference
description: Matrix3D 생성자. 생성자는 표준 1 대 1 행렬을 생성합니다 A B C D E F G H I Tx Ty Tz   1 0 0 0 1 0 0 0 1 0 0  0
type: docs
weight: 10
url: /ko/net/aspose.pdf/matrix3d/matrix3d/
---
## Matrix3D() {#constructor}

생성자는 표준 1 대 1 행렬을 생성합니다: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0]

```csharp
public Matrix3D()
```

## 예제

```csharp
Matrix3D m = new Matrix3D();
```

### 참조

* 클래스 [Matrix3D](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)

---

## Matrix3D(double[]) {#constructor_3}

생성자는 다음 배열 표현을 가진 행렬을 허용합니다: [ A B C D E F G H I Tx Ty Tz]

```csharp
public Matrix3D(double[] matrix3DArray)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| matrix3DArray | Double[] | 행렬 데이터 배열. |

## 예제

```csharp
double[] c = new double[] { 1, 0, 0, 1, 10, 20, 1, 0, 0, 17, 40, 13 };
Matrix3D m = new Matrix3D(c);
```

### 참조

* 클래스 [Matrix3D](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)

---

## Matrix3D(Matrix3D) {#constructor_1}

생성자는 복사를 생성하기 위해 행렬을 허용합니다

```csharp
public Matrix3D(Matrix3D matrix)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| matrix | Matrix3D | Matrix3D 객체. |

### 참조

* 클래스 [Matrix3D](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)

---

## Matrix3D(double, double, double, double, double, double, double, double, double, double, double, double) {#constructor_2}

지정된 계수로 변환 행렬을 초기화합니다.

```csharp
public Matrix3D(double a, double b, double c, double d, double e, double f, double g, double h, 
    double i, double tx, double ty, double tz)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| a | Double | A 행렬 값. |
| b | Double | B 행렬 값. |
| c | Double | C 행렬 값. |
| d | Double | D 행렬 값. |
| e | Double | E 행렬 값. |
| f | Double | F 행렬 값. |
| g | Double | G 행렬 값. |
| h | Double | H 행렬 값. |
| i | Double | I 행렬 값. |
| tx | Double | TX 행렬 값. |
| ty | Double | TY 행렬 값. |
| tz | Double | TZ 행렬 값. |

## 예제

```csharp
Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
```

### 참조

* 클래스 [Matrix3D](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)