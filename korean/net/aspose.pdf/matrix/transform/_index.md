---
title: Matrix.Transform
second_title: Aspose.PDF for .NET API Reference
description: 매트릭스 메서드. 이 매트릭스를 사용하여 점을 변환합니다.
type: docs
weight: 210
url: /ko/net/aspose.pdf/matrix/transform/
---
## Transform(Point) {#transform}

이 매트릭스를 사용하여 점을 변환합니다.

```csharp
public Point Transform(Point p)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| p | Point | 변환될 점입니다. |

### 반환 값

변환 결과입니다.

## 예제

```csharp
Aspose.Pdf.DOM.Matrix m = new Aspose.Pdf.DOM.Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
Aspose.Pdf.Rectangle r = new Aspose.Pdf.Rectangle(0, 0, 100, 100);
Aspose.Pdf.Rectangle r1 = m.Transform(r);
```

### 참조

* 클래스 [Point](../../point/)
* 클래스 [Matrix](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)

---

## Transform(double, double, out double, out double) {#transform_2}

이 매트릭스를 사용하여 좌표를 변환합니다.

```csharp
public void Transform(double x, double y, out double x1, out double y1)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| x | Double | X 좌표입니다. |
| y | Double | Y 좌표입니다. |
| x1 | Double& | 변환된 X 좌표입니다. |
| y1 | Double& | 변환된 Y 좌표입니다. |

## 예제

```csharp
Aspose.Pdf.Matrix m = new Aspose.Pdf.Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
double x, y, x1, y1;
m.Transform(double x, double y, out double x1, out double y1);
```

### 참조

* 클래스 [Matrix](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)

---

## Transform(Rectangle) {#transform_1}

사각형을 변환합니다. 각도가 90 * N도 가 아닐 경우 경계 사각형이 반환됩니다.

```csharp
public Rectangle Transform(Rectangle rect)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rect | Rectangle | 변환될 사각형입니다. |

### 반환 값

변환된 사각형입니다.

## 예제

```csharp
Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
Rectangle r = new Rectangle(0, 0, 100, 100);
Rectangle r1 = m.Transform(r1);
```

### 참조

* 클래스 [Rectangle](../../rectangle/)
* 클래스 [Matrix](../)
* 네임스페이스 [Aspose.Pdf](../../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../../)