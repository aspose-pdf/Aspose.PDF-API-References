---
title: "Matrix.Matrix"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Matrix 생성자. 생성자는 표준 1 대 1 행렬을 생성합니다  A B C D E F    1 0 0 1 0 0"
type: docs
weight: 10
url: /ko/net/aspose.pdf/matrix/matrix/
---
## Matrix() {#constructor}

생성자는 표준 1 대 1 Matrix를 생성합니다: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0]

```csharp
public Matrix()
```

## 예제

```csharp
Matrix m = new Matrix();
```

### 또 보기

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(double[]) {#constructor_3}

생성자는 다음 배열 표현을 가진 Matrix를 허용합니다: [ A B C D E F ]

```csharp
public Matrix(double[] matrixArray)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| matrixArray | Double[] | Matrix 데이터 배열. |

## 예제

```csharp
double[] c = new double[] { 1, 0, 0, 1, 10, 20 };
Matrix m = new Matrix(c);
```

### 또 보기

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(float[]) {#constructor_4}

생성자는 다음 배열 표현을 가진 Matrix를 허용합니다: [ A B C D E F ]

```csharp
public Matrix(float[] matrixArray)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| matrixArray | Single[] | Matrix 데이터 배열. |

### 또 보기

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(Matrix) {#constructor_1}

생성자는 복사를 만들기 위해 Matrix를 허용합니다

```csharp
public Matrix(Matrix matrix)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| matrix | Matrix | Matrix 객체. |

### 또 보기

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Matrix(double, double, double, double, double, double) {#constructor_2}

지정된 계수를 사용하여 변환 Matrix를 초기화합니다.

```csharp
public Matrix(double a, double b, double c, double d, double e, double f)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| a | Double | 하나의 매트릭스 값. |
| b | Double | B 매트릭스 값. |
| c | Double | C 매트릭스 값. |
| d | Double | D 매트릭스 값. |
| e | Double | E 매트릭스 값. |
| f | Double | F 매트릭스 값. |

## 예제

```csharp
Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
```

### 또 보기

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


