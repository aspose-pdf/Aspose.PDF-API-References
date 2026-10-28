---
title: "Matrix.Transform"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Matrix 메서드. 이 매트릭스를 사용하여 점을 변환합니다."
type: docs
weight: 210
url: /ko/net/aspose.pdf/matrix/transform/
---
## Transform(Point) {#transform}

이 행렬을 사용하여 점을 변환합니다.

```csharp
public Point Transform(Point p)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| p | Point | 변환될 점. |

### 반환 값

변환 결과.

## 예제

```csharp
Aspose.Pdf.DOM.Matrix m = new Aspose.Pdf.DOM.Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
Aspose.Pdf.Rectangle r = new Aspose.Pdf.Rectangle(0, 0, 100, 100);
Aspose.Pdf.Rectangle r1 = m.Transform(r);
```

### 또 보기

* class [Point](../../point/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Transform(double, double, out double, out double) {#transform_2}

이 행렬을 사용하여 좌표를 변환합니다.

```csharp
public void Transform(double x, double y, out double x1, out double y1)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | Double | X 좌표. |
| y | Double | Y 좌표. |
| x1 | Double& | 변환된 X 좌표. |
| y1 | Double& | 변환된 Y 좌표. |

## 예제

```csharp
Aspose.Pdf.Matrix m = new Aspose.Pdf.Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
double x, y, x1, y1;
m.Transform(double x, double y, out double x1, out double y1);
```

### 또 보기

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Transform(Rectangle) {#transform_1}

사각형을 변환합니다. 각도가 90 * N도 가 아니면 경계 사각형이 반환됩니다.

```csharp
public Rectangle Transform(Rectangle rect)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | Rectangle | 변환될 사각형. |

### 반환 값

변환된 사각형.

## 예제

```csharp
Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
Rectangle r = new Rectangle(0, 0, 100, 100);
Rectangle r1 = m.Transform(r1);
```

### 또 보기

* class [Rectangle](../../rectangle/)
* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


