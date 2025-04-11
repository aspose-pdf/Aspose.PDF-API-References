---
title: Matrix.Transform
second_title: Aspose.PDF for .NET API Reference
description: Método de matriz. Transforma el punto usando esta matriz
type: docs
weight: 210
url: /es/net/aspose.pdf/matrix/transform/
---
## Transform(Point) {#transform}

Transforma el punto usando esta matriz.

```csharp
public Point Transform(Point p)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| p | Point | Punto que será transformado. |

### Valor de Retorno

Resultado de la transformación.

## Ejemplos

```csharp
Aspose.Pdf.DOM.Matrix m = new Aspose.Pdf.DOM.Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
Aspose.Pdf.Rectangle r = new Aspose.Pdf.Rectangle(0, 0, 100, 100);
Aspose.Pdf.Rectangle r1 = m.Transform(r);
```

### Ver También

* clase [Point](../../point/)
* clase [Matrix](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)

---

## Transform(double, double, out double, out double) {#transform_2}

Transforma las coordenadas usando esta matriz.

```csharp
public void Transform(double x, double y, out double x1, out double y1)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | Double | Coordenada X. |
| y | Double | Coordenada Y. |
| x1 | Double& | Coordenada X transformada. |
| y1 | Double& | Coordenada Y transformada. |

## Ejemplos

```csharp
Aspose.Pdf.Matrix m = new Aspose.Pdf.Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
double x, y, x1, y1;
m.Transform(double x, double y, out double x1, out double y1);
```

### Ver También

* clase [Matrix](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)

---

## Transform(Rectangle) {#transform_1}

Transforma el rectángulo. Si el ángulo no es 90 * N grados, entonces se devuelve el rectángulo delimitador.

```csharp
public Rectangle Transform(Rectangle rect)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | Rectangle | Rectángulo que será transformado. |

### Valor de Retorno

Rectángulo transformado.

## Ejemplos

```csharp
Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
Rectangle r = new Rectangle(0, 0, 100, 100);
Rectangle r1 = m.Transform(r1);
```

### Ver También

* clase [Rectangle](../../rectangle/)
* clase [Matrix](../)
* espacio de nombres [Aspose.Pdf](../../../aspose.pdf/)
* ensamblado [Aspose.PDF](../../../)