---
title: "Matrice"
linktitle: "Matrice"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "La classe représente une matrice de transformation."
type: docs
weight: 2900
url: /fr/java/com.aspose.pdf/matrix/
---
**Inheritance:**
<p> Le constructeur crée une matrice standard 1 à 1 : [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre>

```
public final class Matrix extends Object
```

La classe représente une matrice de transformation.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Matrix](#Matrix--) | <p> Le constructeur accepte une matrice avec la représentation de tableau suivante : [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre> |
| [Matrix](#Matrix-double:A-) | <p> Initialise la matrice de transformation avec les coefficients spécifiés. </p> <hr> <pre> Matrix m = new Matrix(1, 0, 0, 1, 3, 3); </pre> |
| [Matrix](#Matrix-double-double-double-double-double-double-) | Ajoute une matrice à une autre matrice. |
| [Matrix](#Matrix-float:A-) | <p> Initialise la matrice de transformation avec les coefficients spécifiés. </p> <hr> <pre> Matrix m = new Matrix(1, 0, 0, 1, 3, 3); </pre> |
| [Matrix](#Matrix-com.aspose.pdf.Matrix-) | <p> Le constructeur accepte une matrice avec la représentation de tableau suivante : [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre> |
| [Matrix](#Matrix-com.aspose.ms.System.Drawing.Drawing2D.Matrix-) | <p> Le constructeur accepte une matrice avec la représentation de tableau suivante : [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre> |

## Méthodes

| Méthode | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.Matrix-) | Compare la matrice à un autre objet. |
| [equals](#equals-java.lang.Object-) | Obtient le membre A de la matrice de transformation. |
| [getA](#getA--) | <p> Traduit la rotation en angle (degrés) </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre> |
| [getAngle](#getAngle-com.aspose.pdf.Rotation-) | Obtient le membre B de la matrice de transformation. |
| [getB](#getB--) | Obtient le membre C de la matrice de transformation. |
| [getC](#getC--) | Obtient le membre D de la matrice de transformation. |
| [getD](#getD--) | Obtenez le membre D de la matrice de transformation. |
| [getData](#getData--) | Obtient les données de la Matrix sous forme de tableau. |
| [getE](#getE--) | Obtenir le membre E de la matrice de transformation. |
| [getElements](#getElements--) | Éléments de la matrice. |
| [getF](#getF--) | Obtenir le membre F de la matrice de transformation. |
| [getFlipMatrix](#getFlipMatrix--) | Obtient la matrice de retournement. |
| [getMatrix](#getMatrix-com.aspose.pdf.engine.data.ITrailerable-) | Traduit la matrice en objet tableau PDF. |
| [hashCode](#hashCode--) | Code de hachage pour l'objet. |
| [isIdentity](#isIdentity--) | Vérifie si cette matrice est l'identité. |
| [isInt16](#isInt16-double-) | Pour usage interne uniquement |
| [isInt16Values](#isInt16Values--) | Pour usage interne uniquement |
| [multiply](#multiply-com.aspose.pdf.Matrix-) | <p> Multiplie la matrice par une autre matrice. </p> <hr> <pre> Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 }); Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } ); Matrix c= a.multiply(b); </pre> |
| [reverse](#reverse--) | <p> Calcule la matrice inverse. </p> <hr> <pre> Matrix m = Matrix.rotation(Math.PI / 2); Matrix m1 = m.reverse(); </pre> |
| [rotation](#rotation-double-) | <p> Crée une matrice pour l'angle de rotation donné. </p> <hr> <pre> Matrix m = Matrix.Rotation(Math.PI / 2); </pre> |
| [rotation](#rotation-com.aspose.pdf.Rotation-) | Crée une matrice pour la rotation donnée. |
| [scale](#scale-double-double-) | <p> Crée une matrice pour l'échelle donnée. </p> <hr> <pre> Matrix m = Matrix.scale(x, y); </pre> |
| [scale](#scale-double-double-double:A-double:A-) | Met à l'échelle x et y avec la matrice en utilisant la formule suivante : x1 = A*x + C*y; y1 = B*x + D*y; |
| [scale](#scale-double-double-com.aspose.pdf.Matrix-) | Applique l'échelle à la matrice donnée. |
| [setA](#setA-double-) | Définir le membre A de la matrice de transformation. |
| [setB](#setB-double-) | Définir le membre B de la matrice de transformation. |
| [setC](#setC-double-) | Définir le membre C de la matrice de transformation. |
| [setD](#setD-double-) | Définir le membre D de la matrice de transformation. |
| [setE](#setE-double-) | Définir le membre E de la matrice de transformation. |
| [setF](#setF-double-) | Définir le membre F de la matrice de transformation. |
| [skew](#skew-double-double-) | Crée une matrice pour l'angle de rotation donné. Matrix m = Matrix.skew(Math.PI / 2, Math.PI / 2); |
| [toString](#toString--) | Renvoie la représentation textuelle de la matrice. |
| [transform](#transform-double-double-double:A-double:A-) | Transforme les coordonnées en utilisant cette matrice. Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); double x, y, x1, y1; m.transform(double x, double y, out double x1, out double y1); |
| [transform](#transform-com.aspose.pdf.Point-) | Transforme le point en utilisant cette matrice. Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); Point p = new Point(5, 5); Point p1 = m.transform(p); |
| [transform](#transform-com.aspose.pdf.Rectangle-) | Transforme le rectangle. |
| [translate](#translate-double-double-com.aspose.pdf.Matrix-) | Translater une matrice du montant spécifié dans les directions x et y. |
| [unScale](#unScale-double-double-double:A-double:A-) | Ramène x1 et y1 à l'échelle et renvoie x et y avant la transformation de la matrice en utilisant la formule suivante : x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C * B); |
| [unTransform](#unTransform-double-double-double:A-double:A-) | Ramène x1 et y1 à la transformation et renvoie x et y avant la transformation de la matrice en utilisant la formule suivante : x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B). |

### Matrix {#Matrix--}
```
public Matrix()
```

<p> Le constructeur accepte une matrice avec la représentation de tableau suivante : [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre>

### Matrix {#Matrix-double:A-}
```
public Matrix(double[] matrixArray)
```

<p> Initialise la matrice de transformation avec les coefficients spécifiés. </p> <hr> <pre> Matrix m = new Matrix(1, 0, 0, 1, 3, 3); </pre>

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrixArray |  | Tableau de données de la matrice. |

### Matrix {#Matrix-double-double-double-double-double-double-}
```
public Matrix(double a, double b, double c, double d, double e, double f)
```

Ajoute une matrice à une autre matrice.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| a |  | Une valeur de matrice. |
| b |  | Valeur de la matrice B. |
| c |  | Valeur de la matrice C. |
| d |  | Valeur de la matrice D. |
| e |  | Valeur de la matrice E. |
| f |  | Valeur de la matrice F. |

### Matrix {#Matrix-float:A-}
```
public Matrix(float[] matrixArray)
```

<p> Initialise la matrice de transformation avec les coefficients spécifiés. </p> <hr> <pre> Matrix m = new Matrix(1, 0, 0, 1, 3, 3); </pre>

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| matrixArray |  | Tableau de données de la matrice. |

### Matrix {#Matrix-com.aspose.pdf.Matrix-}
<p> Le constructeur accepte une matrice avec la représentation de tableau suivante : [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre>

### Matrix {#Matrix-com.aspose.ms.System.Drawing.Drawing2D.Matrix-}
<p> Le constructeur accepte une matrice avec la représentation de tableau suivante : [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre>

### add {#add-com.aspose.pdf.Matrix-}
Compare la matrice à un autre objet.

### equals {#equals-java.lang.Object-}
Obtient le membre A de la matrice de transformation.

### getA {#getA--}
```
public double getA()
```

<p> Traduit la rotation en angle (degrés) </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre>

**Returns:**
valeur double

### getAngle {#getAngle-com.aspose.pdf.Rotation-}
Obtient le membre B de la matrice de transformation.

### getB {#getB--}
```
public double getB()
```

Obtient le membre C de la matrice de transformation.

**Returns:**
valeur double

### getC {#getC--}
```
public double getC()
```

Obtient le membre D de la matrice de transformation.

**Returns:**
valeur double

### getD {#getD--}
```
public double getD()
```

Obtenez le membre D de la matrice de transformation.

**Returns:**
valeur double

### getData {#getData--}
```
public final double[] getData()
```

Obtient les données de la Matrix sous forme de tableau.

**Returns:**
tableau de valeurs double

### getE {#getE--}
```
public double getE()
```

Obtenir le membre E de la matrice de transformation.

**Returns:**
valeur double

### getElements {#getElements--}
```
public float[] getElements()
```

Éléments de la matrice.

**Returns:**
float[] tableau

### getF {#getF--}
```
public double getF()
```

Obtenir le membre F de la matrice de transformation.

**Returns:**
valeur double

### getFlipMatrix {#getFlipMatrix--}
```
public final Matrix getFlipMatrix()
```

Obtient la matrice de retournement.

**Returns:**
Instance de matrice

### getMatrix {#getMatrix-com.aspose.pdf.engine.data.ITrailerable-}
Traduit la matrice en objet tableau PDF.

### hashCode {#hashCode--}
```
public int hashCode()
```

Code de hachage pour l'objet.

**Returns:**
Code de hachage.

### isIdentity {#isIdentity--}
```
public final boolean isIdentity()
```

Vérifie si cette matrice est l'identité.

**Returns:**
valeur booléenne

### isInt16 {#isInt16-double-}
```
public static boolean isInt16(double value)
```

Pour usage interne uniquement

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

**Returns:**
valeur booléenne

### isInt16Values {#isInt16Values--}
```
public boolean isInt16Values()
```

Pour usage interne uniquement

**Returns:**
valeur booléenne

### multiply {#multiply-com.aspose.pdf.Matrix-}
<p> Multiplie la matrice par une autre matrice. </p> <hr> <pre> Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 }); Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } ); Matrix c= a.multiply(b); </pre>

### reverse {#reverse--}
```
public Matrix reverse()
```

<p> Calcule la matrice inverse. </p> <hr> <pre> Matrix m = Matrix.rotation(Math.PI / 2); Matrix m1 = m.reverse(); </pre>

**Returns:**
Matrice inversée.

### rotation {#rotation-double-}
```
public static Matrix rotation(double alpha)
```

<p> Crée une matrice pour l'angle de rotation donné. </p> <hr> <pre> Matrix m = Matrix.Rotation(Math.PI / 2); </pre>

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| alpha |  | Angle de rotation en radians. |

**Returns:**
Matrice de transformation.

### rotation {#rotation-com.aspose.pdf.Rotation-}
Crée une matrice pour la rotation donnée.

### scale {#scale-double-double-}
```
public static Matrix scale(double x, double y)
```

<p> Crée une matrice pour l'échelle donnée. </p> <hr> <pre> Matrix m = Matrix.scale(x, y); </pre>

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x |  | Échelle x. |
| y |  | Échelle y. |

**Returns:**
Matrice de transformation.

### scale {#scale-double-double-double:A-double:A-}
```
public final void scale(double x, double y, double[] x1, double[] y1)
```

Met à l'échelle x et y avec la matrice en utilisant la formule suivante : x1 = A*x + C*y; y1 = B*x + D*y;

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x |  | Coordonnée X d'entrée |
| y |  | Coordonnée Y d'entrée |
| x1 |  | Coordonnée X de sortie |
| y1 |  | Coordonnée Y de sortie |

### scale {#scale-double-double-com.aspose.pdf.Matrix-}
Applique l'échelle à la matrice donnée.

### setA {#setA-double-}
```
public void setA(double value)
```

Définir le membre A de la matrice de transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setB {#setB-double-}
```
public void setB(double value)
```

Définir le membre B de la matrice de transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setC {#setC-double-}
```
public void setC(double value)
```

Définir le membre C de la matrice de transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setD {#setD-double-}
```
public void setD(double value)
```

Définir le membre D de la matrice de transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setE {#setE-double-}
```
public void setE(double value)
```

Définir le membre E de la matrice de transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setF {#setF-double-}
```
public void setF(double value)
```

Définir le membre F de la matrice de transformation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### skew {#skew-double-double-}
```
public static Matrix skew(double alpha, double beta)
```

Crée une matrice pour l'angle de rotation donné. Matrix m = Matrix.skew(Math.PI / 2, Math.PI / 2);

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| alpha |  | Angle d'inclinaison x en radians. |
| beta |  | Angle d'inclinaison y en radians. |

**Returns:**
Matrice de transformation.

### toString {#toString--}
```
public String toString()
```

Renvoie la représentation textuelle de la matrice.

**Returns:**
Représentation sous forme de chaîne de la matrice

### transform {#transform-double-double-double:A-double:A-}
```
public final void transform(double x, double y, double[] x1, double[] y1)
```

Transforme les coordonnées en utilisant cette matrice. Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); double x, y, x1, y1; m.transform(double x, double y, out double x1, out double y1);

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x |  | Coordonnée X. |
| y |  | Coordonnée Y. |
| x1 |  | Coordonnée X transformée. |
| y1 |  | Coordonnée Y transformée. |

### transform {#transform-com.aspose.pdf.Point-}
Transforme le point en utilisant cette matrice. Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); Point p = new Point(5, 5); Point p1 = m.transform(p);

### transform {#transform-com.aspose.pdf.Rectangle-}
Transforme le rectangle.

### translate {#translate-double-double-com.aspose.pdf.Matrix-}
Translater une matrice du montant spécifié dans les directions x et y.

### unScale {#unScale-double-double-double:A-double:A-}
```
public final void unScale(double x1, double y1, double[] x, double[] y)
```

Ramène x1 et y1 à l'échelle et renvoie x et y avant la transformation de la matrice en utilisant la formule suivante : x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C * B);

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x1 |  | Coordonnée X d'entrée |
| y1 |  | Coordonnée Y d'entrée |
| x |  | Coordonnée X de sortie |
| y |  | Coordonnée Y de sortie |

### unTransform {#unTransform-double-double-double:A-double:A-}
```
public final void unTransform(double x1, double y1, double[] x, double[] y)
```

Ramène x1 et y1 à la transformation et renvoie x et y avant la transformation de la matrice en utilisant la formule suivante : x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x1 |  | Coordonnée X d'entrée |
| y1 |  | Coordonnée Y d'entrée |
| x |  | Coordonnée X de sortie |
| y |  | Coordonnée Y de sortie |
