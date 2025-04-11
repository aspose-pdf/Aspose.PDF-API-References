---
title: Matrix.Transform
second_title: Aspose.PDF for .NET API Reference
description: Méthode Matrix. Transforme le point en utilisant cette matrice
type: docs
weight: 210
url: /fr/net/aspose.pdf/matrix/transform/
---
## Transform(Point) {#transform}

Transforme le point en utilisant cette matrice.

```csharp
public Point Transform(Point p)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| p | Point | Point qui sera transformé. |

### Valeur de retour

Résultat de la transformation.

## Exemples

```csharp
Aspose.Pdf.DOM.Matrix m = new Aspose.Pdf.DOM.Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
Aspose.Pdf.Rectangle r = new Aspose.Pdf.Rectangle(0, 0, 100, 100);
Aspose.Pdf.Rectangle r1 = m.Transform(r);
```

### Voir aussi

* classe [Point](../../point/)
* classe [Matrix](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Transform(double, double, out double, out double) {#transform_2}

Transforme les coordonnées en utilisant cette matrice.

```csharp
public void Transform(double x, double y, out double x1, out double y1)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| x | Double | Coordonnée X. |
| y | Double | Coordonnée Y. |
| x1 | Double& | Coordonnée X transformée. |
| y1 | Double& | Coordonnée Y transformée. |

## Exemples

```csharp
Aspose.Pdf.Matrix m = new Aspose.Pdf.Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
double x, y, x1, y1;
m.Transform(double x, double y, out double x1, out double y1);
```

### Voir aussi

* classe [Matrix](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Transform(Rectangle) {#transform_1}

Transforme le rectangle. Si l'angle n'est pas de 90 * N degrés, alors le rectangle englobant est retourné.

```csharp
public Rectangle Transform(Rectangle rect)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | Rectangle | Rectangle à transformer. |

### Valeur de retour

Rectangle transformé.

## Exemples

```csharp
Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
Rectangle r = new Rectangle(0, 0, 100, 100);
Rectangle r1 = m.Transform(r1);
```

### Voir aussi

* classe [Rectangle](../../rectangle/)
* classe [Matrix](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)