---
title: "Matrix"
linktitle: "Matrix"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse stellt eine Transformationsmatrix dar."
type: docs
weight: 2900
url: /de/java/com.aspose.pdf/matrix/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Matrix

```
public final class Matrix extends Object
```

Klasse stellt eine Transformationsmatrix dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Matrix](#Matrix--) | <p> Der Konstruktor erstellt eine Standard-1-zu-1-Matrix: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre> |
| [Matrix](#Matrix-double:A-) | <p> Der Konstruktor akzeptiert eine Matrix mit folgender Array-Darstellung: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre> |
| [Matrix](#Matrix-double-double-double-double-double-double-) | <p> Initialisiert Transformationsmatrix mit angegebenen Koeffizienten. </p> <hr> <pre> Matrix m = new Matrix(1, 0, 0, 1, 3, 3); </pre> |
| [Matrix](#Matrix-float:A-) | <p> Der Konstruktor akzeptiert eine Matrix mit folgender Array-Darstellung: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre> |
| [Matrix](#Matrix-com.aspose.pdf.Matrix-) | <p> Der Konstruktor erstellt eine Standard-1-zu-1-Matrix: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre> |
| [Matrix](#Matrix-com.aspose.ms.System.Drawing.Drawing2D.Matrix-) | <p> Der Konstruktor erstellt eine Standard-1-zu-1-Matrix: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre> |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [add](#add-com.aspose.pdf.Matrix-) | Fügt Matrix zu einer anderen Matrix hinzu. |
| [equals](#equals-java.lang.Object-) | Vergleicht Matrix mit einem anderen Objekt. |
| [getA](#getA--) | Erhalte das A-Element der Transformationsmatrix. |
| [getAngle](#getAngle-com.aspose.pdf.Rotation-) | <p> Übersetzt Rotation in Winkel (Grad) </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre> |
| [getB](#getB--) | Erhalte das B-Element der Transformationsmatrix. |
| [getC](#getC--) | Erhalte das C-Element der Transformationsmatrix. |
| [getD](#getD--) | Erhalte das D-Element der Transformationsmatrix. |
| [getData](#getData--) | Gibt die Daten der Matrix als Array zurück. |
| [getE](#getE--) | Erhalte das E-Element der Transformationsmatrix. |
| [getElements](#getElements--) | Elemente der Matrix. |
| [getF](#getF--) | Erhalte das F-Element der Transformationsmatrix. |
| [getFlipMatrix](#getFlipMatrix--) | Gibt die Spiegelmatrix zurück. |
| [getMatrix](#getMatrix-com.aspose.pdf.engine.data.ITrailerable-) | Übersetzt Matrix in ein PDF-Array-Objekt. |
| [hashCode](#hashCode--) | Hashcode für Objekt. |
| [isIdentity](#isIdentity--) | Überprüft, ob diese Matrix die Einheitsmatrix ist. |
| [isInt16](#isInt16-double-) | Nur für den internen Gebrauch |
| [isInt16Values](#isInt16Values--) | Nur für den internen Gebrauch |
| [multiply](#multiply-com.aspose.pdf.Matrix-) | <p> Multipliziert die Matrix mit einer anderen Matrix. </p> <hr> <pre> Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 }); Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } ); Matrix c= a.multiply(b); </pre> |
| [reverse](#reverse--) | <p> Berechnet die umgekehrte Matrix. </p> <hr> <pre> Matrix m = Matrix.rotation(Math.PI / 2); Matrix m1 = m.reverse(); </pre> |
| [rotation](#rotation-double-) | <p> Erstellt eine Matrix für den gegebenen Rotationswinkel. </p> <hr> <pre> Matrix m = Matrix.Rotation(Math.PI / 2); </pre> |
| [rotation](#rotation-com.aspose.pdf.Rotation-) | Erstellt eine Matrix für die gegebene Drehung. |
| [scale](#scale-double-double-) | <p> Erstellt eine Matrix für die angegebene Skalierung. </p> <hr> <pre> Matrix m = Matrix.scale(x, y); </pre> |
| [scale](#scale-double-double-double:A-double:A-) | Skaliert x und y mit der Matrix nach folgender Formel: x1 = A*x + C*y; y1 = B*x + D*y; |
| [scale](#scale-double-double-com.aspose.pdf.Matrix-) | Wendet Skalierung auf die gegebene Matrix an. |
| [setA](#setA-double-) | Setzt das A-Mitglied der Transformationsmatrix. |
| [setB](#setB-double-) | Setzt das B-Mitglied der Transformationsmatrix. |
| [setC](#setC-double-) | Setzt das C-Mitglied der Transformationsmatrix. |
| [setD](#setD-double-) | Setzt das D-Mitglied der Transformationsmatrix. |
| [setE](#setE-double-) | Setzt das E-Mitglied der Transformationsmatrix. |
| [setF](#setF-double-) | Setzt das F-Mitglied der Transformationsmatrix. |
| [skew](#skew-double-double-) | Erstellt eine Matrix für den angegebenen Rotationswinkel. Matrix m = Matrix.skew(Math.PI / 2, Math.PI / 2); |
| [toString](#toString--) | Gibt die Textdarstellung der Matrix zurück. |
| [transform](#transform-double-double-double:A-double:A-) | Transformiert Koordinaten mit dieser Matrix. Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); double x, y, x1, y1; m.transform(double x, double y, out double x1, out double y1); |
| [transform](#transform-com.aspose.pdf.Point-) | Transformiert Punkt mit dieser Matrix. Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); Point p = new Point(5, 5); Point p1 = m.transform(p); |
| [transform](#transform-com.aspose.pdf.Rectangle-) | Transformiert Rechteck. |
| [translate](#translate-double-double-com.aspose.pdf.Matrix-) | Verschiebt eine Matrix um den angegebenen Betrag in x- und y-Richtung. |
| [unScale](#unScale-double-double-double:A-double:A-) | Skaliert x1 und y1 zurück und gibt x und y vor der Matrixtransformation zurück nach folgender Formel: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C * B); |
| [unTransform](#unTransform-double-double-double:A-double:A-) | Transformiert x1 und y1 zurück und gibt x und y vor der Matrixtransformation zurück nach folgender Formel: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B). |

### Matrix {#Matrix--}
```
public Matrix()
```

<p> Der Konstruktor erstellt eine Standard-1-zu-1-Matrix: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre>

### Matrix {#Matrix-double:A-}
```
public Matrix(double[] matrixArray)
```

<p> Der Konstruktor akzeptiert eine Matrix mit folgender Array-Darstellung: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre>

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrixArray |  | Matrix-Datenarray. |

### Matrix {#Matrix-double-double-double-double-double-double-}
```
public Matrix(double a, double b, double c, double d, double e, double f)
```

<p> Initialisiert Transformationsmatrix mit angegebenen Koeffizienten. </p> <hr> <pre> Matrix m = new Matrix(1, 0, 0, 1, 3, 3); </pre>

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| a |  | Ein Matrixwert. |
| b |  | Ein B-Matrixwert. |
| c |  | Ein C-Matrixwert. |
| d |  | Ein D-Matrixwert. |
| e |  | E-Matrixwert. |
| f |  | F-Matrixwert. |

### Matrix {#Matrix-float:A-}
```
public Matrix(float[] matrixArray)
```

<p> Der Konstruktor akzeptiert eine Matrix mit folgender Array-Darstellung: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre>

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrixArray |  | Matrix-Datenarray. |

### Matrix {#Matrix-com.aspose.pdf.Matrix-}
<p> Der Konstruktor erstellt eine Standard-1-zu-1-Matrix: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre>

### Matrix {#Matrix-com.aspose.ms.System.Drawing.Drawing2D.Matrix-}
<p> Der Konstruktor erstellt eine Standard-1-zu-1-Matrix: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre>

### add {#add-com.aspose.pdf.Matrix-}
Fügt Matrix zu einer anderen Matrix hinzu.

### equals {#equals-java.lang.Object-}
Vergleicht Matrix mit einem anderen Objekt.

### getA {#getA--}
```
public double getA()
```

Erhalte das A-Element der Transformationsmatrix.

**Returns:**
double-Wert

### getAngle {#getAngle-com.aspose.pdf.Rotation-}
<p> Übersetzt Rotation in Winkel (Grad) </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre>

### getB {#getB--}
```
public double getB()
```

Erhalte das B-Element der Transformationsmatrix.

**Returns:**
double-Wert

### getC {#getC--}
```
public double getC()
```

Erhalte das C-Element der Transformationsmatrix.

**Returns:**
double-Wert

### getD {#getD--}
```
public double getD()
```

Erhalte das D-Element der Transformationsmatrix.

**Returns:**
double-Wert

### getData {#getData--}
```
public final double[] getData()
```

Gibt die Daten der Matrix als Array zurück.

**Returns:**
Array von double-Werten

### getE {#getE--}
```
public double getE()
```

Erhalte das E-Element der Transformationsmatrix.

**Returns:**
double-Wert

### getElements {#getElements--}
```
public float[] getElements()
```

Elemente der Matrix.

**Returns:**
float[] array

### getF {#getF--}
```
public double getF()
```

Erhalte das F-Element der Transformationsmatrix.

**Returns:**
double-Wert

### getFlipMatrix {#getFlipMatrix--}
```
public final Matrix getFlipMatrix()
```

Gibt die Spiegelmatrix zurück.

**Returns:**
Matrixinstanz

### getMatrix {#getMatrix-com.aspose.pdf.engine.data.ITrailerable-}
Übersetzt Matrix in ein PDF-Array-Objekt.

### hashCode {#hashCode--}
```
public int hashCode()
```

Hashcode für Objekt.

**Returns:**
Hash-Code.

### isIdentity {#isIdentity--}
```
public final boolean isIdentity()
```

Überprüft, ob diese Matrix die Einheitsmatrix ist.

**Returns:**
boolescher Wert

### isInt16 {#isInt16-double-}
```
public static boolean isInt16(double value)
```

Nur für den internen Gebrauch

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

**Returns:**
boolescher Wert

### isInt16Values {#isInt16Values--}
```
public boolean isInt16Values()
```

Nur für den internen Gebrauch

**Returns:**
boolescher Wert

### multiply {#multiply-com.aspose.pdf.Matrix-}
<p> Multipliziert die Matrix mit einer anderen Matrix. </p> <hr> <pre> Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 }); Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } ); Matrix c= a.multiply(b); </pre>

### reverse {#reverse--}
```
public Matrix reverse()
```

<p> Berechnet die umgekehrte Matrix. </p> <hr> <pre> Matrix m = Matrix.rotation(Math.PI / 2); Matrix m1 = m.reverse(); </pre>

**Returns:**
Umgekehrte Matrix.

### rotation {#rotation-double-}
```
public static Matrix rotation(double alpha)
```

<p> Erstellt eine Matrix für den gegebenen Rotationswinkel. </p> <hr> <pre> Matrix m = Matrix.Rotation(Math.PI / 2); </pre>

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| alpha |  | Rotationswinkel in Radianten. |

**Returns:**
Transformationsmatrix.

### rotation {#rotation-com.aspose.pdf.Rotation-}
Erstellt eine Matrix für die gegebene Drehung.

### scale {#scale-double-double-}
```
public static Matrix scale(double x, double y)
```

<p> Erstellt eine Matrix für die angegebene Skalierung. </p> <hr> <pre> Matrix m = Matrix.scale(x, y); </pre>

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x |  | Skalierung x. |
| y |  | Skalierung y. |

**Returns:**
Transformationsmatrix.

### scale {#scale-double-double-double:A-double:A-}
```
public final void scale(double x, double y, double[] x1, double[] y1)
```

Skaliert x und y mit der Matrix nach folgender Formel: x1 = A*x + C*y; y1 = B*x + D*y;

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x |  | Eingabe X-Koordinate |
| y |  | Eingabe Y-Koordinate |
| x1 |  | Ausgabe X-Koordinate |
| y1 |  | Ausgabe Y-Koordinate |

### scale {#scale-double-double-com.aspose.pdf.Matrix-}
Wendet Skalierung auf die gegebene Matrix an.

### setA {#setA-double-}
```
public void setA(double value)
```

Setzt das A-Mitglied der Transformationsmatrix.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setB {#setB-double-}
```
public void setB(double value)
```

Setzt das B-Mitglied der Transformationsmatrix.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setC {#setC-double-}
```
public void setC(double value)
```

Setzt das C-Mitglied der Transformationsmatrix.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setD {#setD-double-}
```
public void setD(double value)
```

Setzt das D-Mitglied der Transformationsmatrix.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setE {#setE-double-}
```
public void setE(double value)
```

Setzt das E-Mitglied der Transformationsmatrix.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setF {#setF-double-}
```
public void setF(double value)
```

Setzt das F-Mitglied der Transformationsmatrix.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### skew {#skew-double-double-}
```
public static Matrix skew(double alpha, double beta)
```

Erstellt eine Matrix für den angegebenen Rotationswinkel. Matrix m = Matrix.skew(Math.PI / 2, Math.PI / 2);

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| alpha |  | Schrägstellung x-Winkel in Radianten. |
| Beta |  | Schrägstellung y-Winkel in Radianten. |

**Returns:**
Transformationsmatrix.

### toString {#toString--}
```
public String toString()
```

Gibt die Textdarstellung der Matrix zurück.

**Returns:**
String-Darstellung der Matrix

### transform {#transform-double-double-double:A-double:A-}
```
public final void transform(double x, double y, double[] x1, double[] y1)
```

Transformiert Koordinaten mit dieser Matrix. Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); double x, y, x1, y1; m.transform(double x, double y, out double x1, out double y1);

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x |  | X-Koordinate. |
| y |  | Y-Koordinate. |
| x1 |  | Transformierte X-Koordinate. |
| y1 |  | Transformierte Y-Koordinate. |

### transform {#transform-com.aspose.pdf.Point-}
Transformiert Punkt mit dieser Matrix. Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); Point p = new Point(5, 5); Point p1 = m.transform(p);

### transform {#transform-com.aspose.pdf.Rectangle-}
Transformiert Rechteck.

### translate {#translate-double-double-com.aspose.pdf.Matrix-}
Verschiebt eine Matrix um den angegebenen Betrag in x- und y-Richtung.

### unScale {#unScale-double-double-double:A-double:A-}
```
public final void unScale(double x1, double y1, double[] x, double[] y)
```

Skaliert x1 und y1 zurück und gibt x und y vor der Matrixtransformation zurück nach folgender Formel: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C * B);

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x1 |  | Eingabe X-Koordinate |
| y1 |  | Eingabe Y-Koordinate |
| x |  | Ausgabe X-Koordinate |
| y |  | Ausgabe Y-Koordinate |

### unTransform {#unTransform-double-double-double:A-double:A-}
```
public final void unTransform(double x1, double y1, double[] x, double[] y)
```

Transformiert x1 und y1 zurück und gibt x und y vor der Matrixtransformation zurück nach folgender Formel: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x1 |  | Eingabe X-Koordinate |
| y1 |  | Eingabe Y-Koordinate |
| x |  | Ausgabe X-Koordinate |
| y |  | Ausgabe Y-Koordinate |
