---
title: Matrix.Matrix
second_title: Aspose.PDF for .NET API Reference
description: Matrix 생성자. 생성자는 표준 1 대 1 행렬을 생성합니다 A B C D E F    1 0 0 1 0 0
type: docs
weight: 10
url: /ko/net/aspose.pdf/matrix/matrix/
---
## Matrix() {#constructor}

생성자는 표준 1 대 1 행렬을 생성합니다: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0]

```csharp
public Matrix()
```

## 예제

```csharp
Matrix m = new Matrix();
```

### 참조

* 클래스 [Matrix](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)

---

## Matrix(double[]) {#constructor_3}

생성자는 다음 배열 표현을 가진 행렬을 허용합니다: [ A B C D E F ]

```csharp
public Matrix(double[] matrixArray)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| matrixArray | Double[] | 행렬 데이터 배열. |

## 예제

```csharp
double[] c = new double[] { 1, 0, 0, 1, 10, 20 };
Matrix m = new Matrix(c);
```

### 참조

* 클래스 [Matrix](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)

---

## Matrix(float[]) {#constructor_4}

생성자는 다음 배열 표현을 가진 행렬을 허용합니다: [ A B C D E F ]

```csharp
public Matrix(float[] matrixArray)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| matrixArray | Single[] | 행렬 데이터 배열. |

### 참조

* 클래스 [Matrix](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)

---

## Matrix(Matrix) {#constructor_1}

생성자는 복사본을 만들기 위해 행렬을 허용합니다.

```csharp
public Matrix(Matrix matrix)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| matrix | Matrix | 행렬 객체. |

### 참조

* 클래스 [Matrix](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)

---

## Matrix(double, double, double, double, double, double) {#constructor_2}

지정된 계수로 변환 행렬을 초기화합니다.

```csharp
public Matrix(double a, double b, double c, double d, double e, double f)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| a | Double | A 행렬 값. |
| b | Double | B 행렬 값. |
| c | Double | C 행렬 값. |
| d | Double | D 행렬 값. |
| e | Double | E 행렬 값. |
| f | Double | F 행렬 값. |

## 예제

```csharp
Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
```

### 참조

* 클래스 [Matrix](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)