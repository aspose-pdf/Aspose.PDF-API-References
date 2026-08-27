---
title: "Matrix.Scale"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo Matrix. Scala x e y con la matrice usando la seguente formula x1  Ax  Cy y1  Bx  Dy"
type: docs
weight: 190
url: /it/net/aspose.pdf/matrix/scale/
---
## Scale(double, double, out double, out double)

Scala x e y con la matrice usando la seguente formula: x1 = A*x + C*y; y1 = B*x + D*y;

```csharp
public void Scale(double x, double y, out double x1, out double y1)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | Double | Coordinata X di input |
| y | Double | Coordinata Y di input |
| x1 | Double& | Coordinata X di output |
| y1 | Double& | Coordinata Y di output |

### Vedi anche

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Scale(double, double, Matrix)

Applica la scalatura alla matrice fornita.

```csharp
public static Matrix Scale(double sx, double sy, Matrix source)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sx | Double | Il fattore di scala per l'asse X. |
| sy | Double | Il fattore di scala per l'asse Y. |
| source | Matrix | La matrice da scalare. |

### Valore di ritorno

Una nuova matrice che è il risultato della scalatura della matrice sorgente.

### Vedi anche

* class [Matrix](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


