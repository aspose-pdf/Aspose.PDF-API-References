---
title: Matrix.Transform
second_title: Aspose.PDF for .NET API Reference
description: Método Matrix. Transforma ponto usando esta matriz
type: docs
weight: 210
url: /pt/net/aspose.pdf/matrix/transform/
---
## Transform(Point) {#transform}

Transforma ponto usando esta matriz.

```csharp
public Point Transform(Point p)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| p | Point | Ponto que será transformado. |

### Valor de Retorno

Resultado da transformação.

## Exemplos

```csharp
Aspose.Pdf.DOM.Matrix m = new Aspose.Pdf.DOM.Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
Aspose.Pdf.Rectangle r = new Aspose.Pdf.Rectangle(0, 0, 100, 100);
Aspose.Pdf.Rectangle r1 = m.Transform(r);
```

### Veja Também

* classe [Point](../../point/)
* classe [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Transform(double, double, out double, out double) {#transform_2}

Transforma coordenadas usando esta matriz.

```csharp
public void Transform(double x, double y, out double x1, out double y1)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | Double | Coordenada X. |
| y | Double | Coordenada Y. |
| x1 | Double& | Coordenada X transformada. |
| y1 | Double& | Coordenada Y transformada. |

## Exemplos

```csharp
Aspose.Pdf.Matrix m = new Aspose.Pdf.Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
double x, y, x1, y1;
m.Transform(double x, double y, out double x1, out double y1);
```

### Veja Também

* classe [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Transform(Rectangle) {#transform_1}

Transforma retângulo. Se o ângulo não for 90 * N graus, então o retângulo delimitador é retornado.

```csharp
public Rectangle Transform(Rectangle rect)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rect | Rectangle | Retângulo a ser transformado. |

### Valor de Retorno

Retângulo transformado.

## Exemplos

```csharp
Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
Rectangle r = new Rectangle(0, 0, 100, 100);
Rectangle r1 = m.Transform(r1);
```

### Veja Também

* classe [Rectangle](../../rectangle/)
* classe [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)