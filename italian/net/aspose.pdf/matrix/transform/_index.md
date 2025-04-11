---
title: Matrix.Transform
second_title: Aspose.PDF for .NET API Reference
description: Metodo Matrix. Trasforma il punto utilizzando questa matrice
type: docs
weight: 210
url: /it/net/aspose.pdf/matrix/transform/
---
## Transform(Point) {#transform}

Trasforma il punto utilizzando questa matrice.

```csharp
public Point Transform(Point p)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| p | Point | Punto che sarà trasformato. |

### Valore di ritorno

Risultato della trasformazione.

## Esempi

```csharp
Aspose.Pdf.DOM.Matrix m = new Aspose.Pdf.DOM.Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
Aspose.Pdf.Rectangle r = new Aspose.Pdf.Rectangle(0, 0, 100, 100);
Aspose.Pdf.Rectangle r1 = m.Transform(r);
```

### Vedi anche

* classe [Point](../../point/)
* classe [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Transform(double, double, out double, out double) {#transform_2}

Trasforma le coordinate utilizzando questa matrice.

```csharp
public void Transform(double x, double y, out double x1, out double y1)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | Double | Coordinata X. |
| y | Double | Coordinata Y. |
| x1 | Double& | Coordinata X trasformata. |
| y1 | Double& | Coordinata Y trasformata. |

## Esempi

```csharp
Aspose.Pdf.Matrix m = new Aspose.Pdf.Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
double x, y, x1, y1;
m.Transform(double x, double y, out double x1, out double y1);
```

### Vedi anche

* classe [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Transform(Rectangle) {#transform_1}

Trasforma il rettangolo. Se l'angolo non è di 90 * N gradi, allora viene restituito il rettangolo di delimitazione.

```csharp
public Rectangle Transform(Rectangle rect)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | Rectangle | Rettangolo da trasformare. |

### Valore di ritorno

Rettangolo trasformato.

## Esempi

```csharp
Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
Rectangle r = new Rectangle(0, 0, 100, 100);
Rectangle r1 = m.Transform(r1);
```

### Vedi anche

* classe [Rectangle](../../rectangle/)
* classe [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)