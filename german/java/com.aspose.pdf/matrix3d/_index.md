---
title: "Matrix3D"
linktitle: "Matrix3D"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse stellt eine Transformationsmatrix dar."
type: docs
weight: 2910
url: /de/java/com.aspose.pdf/matrix3d/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Matrix3D

```
public final class Matrix3D extends Object
```

Klasse stellt eine Transformationsmatrix dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Matrix3D](#Matrix3D--) | <p> Konstruktor erstellt eine Standard-1-zu-1-Matrix: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre> |
| [Matrix3D](#Matrix3D-double:A-) | <p> Konstruktor akzeptiert eine Matrix mit folgender Array-Darstellung: [ A B C D E F G H I Tx Ty Tz] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20, 1, 0, 0, 17, 40, 13 }; Matrix3D m = new Matrix3D(c); </pre> |
| [Matrix3D](#Matrix3D-double-double-double-double-double-double-double-double-double-double-double-double-) | <p> Initialisiert Transformationsmatrix mit angegebenen Koeffizienten. </p> <hr> <pre> Matrix m = new Matrix(1, 0, 0, 1, 3, 3); </pre> |
| [Matrix3D](#Matrix3D-com.aspose.pdf.Matrix3D-) | <p> Konstruktor erstellt eine Standard-1-zu-1-Matrix: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre> |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [add](#add-com.aspose.pdf.Matrix3D-) | <p> Addiert die Matrix zu einer anderen Matrix. </p> <hr> |
| [equals](#equals-java.lang.Object-) | Vergleicht die Matrix mit einem anderen Objekt. |
| [getA](#getA--) | A ist ein Mitglied der Transformationsmatrix. |
| [getAngle](#getAngle-com.aspose.pdf.Rotation-) | <p> Übersetzt die Rotation in einen Winkel (Grad) </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre> |
| [getB](#getB--) | B ist ein Mitglied der Transformationsmatrix. |
| [getC](#getC--) | C ist ein Mitglied der Transformationsmatrix. |
| [getD](#getD--) | D ist ein Mitglied der Transformationsmatrix. |
| [getE](#getE--) | E ist ein Mitglied der Transformationsmatrix. |
| [getF](#getF--) | F ist ein Mitglied der Transformationsmatrix. |
| [getG](#getG--) | G ist ein Mitglied der Transformationsmatrix. |
| [getH](#getH--) | H ist ein Mitglied der Transformationsmatrix. |
| [getI](#getI--) | I ist ein Mitglied der Transformationsmatrix. |
| [getTx](#getTx--) | Tx ist ein Mitglied der Transformationsmatrix. |
| [getTy](#getTy--) | Ty ist ein Mitglied der Transformationsmatrix. |
| [getTz](#getTz--) | Tz ist ein Mitglied der Transformationsmatrix. |
| [hashCode](#hashCode--) | <p> Hash-Code für Objekt. </p> <hr> |
| [setA](#setA-double-) | A ist ein Mitglied der Transformationsmatrix. |
| [setB](#setB-double-) | B ist ein Mitglied der Transformationsmatrix. |
| [setC](#setC-double-) | C ist ein Mitglied der Transformationsmatrix. |
| [setD](#setD-double-) | D ist ein Mitglied der Transformationsmatrix. |
| [setE](#setE-double-) | E ist ein Mitglied der Transformationsmatrix. |
| [setF](#setF-double-) | F ist ein Mitglied der Transformationsmatrix. |
| [setG](#setG-double-) | G ist ein Mitglied der Transformationsmatrix. |
| [setH](#setH-double-) | H ist ein Mitglied der Transformationsmatrix. |
| [setI](#setI-double-) | I ist ein Mitglied der Transformationsmatrix. |
| [setTx](#setTx-double-) | Tx ist ein Mitglied der Transformationsmatrix. |
| [setTy](#setTy-double-) | Ty ist ein Mitglied der Transformationsmatrix. |
| [setTz](#setTz-double-) | Tz ist ein Mitglied der Transformationsmatrix. |
| [toString](#toString--) | Gibt die Textdarstellung der Matrix zurück. |

### Matrix3D {#Matrix3D--}
```
public Matrix3D()
```

<p> Konstruktor erstellt eine Standard-1-zu-1-Matrix: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre>

### Matrix3D {#Matrix3D-double:A-}
```
public Matrix3D(double[] matrix3DArray)
```

<p> Konstruktor akzeptiert eine Matrix mit folgender Array-Darstellung: [ A B C D E F G H I Tx Ty Tz] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20, 1, 0, 0, 17, 40, 13 }; Matrix3D m = new Matrix3D(c); </pre>

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| matrix3DArray |  | Matrix-Datenarray. |

### Matrix3D {#Matrix3D-double-double-double-double-double-double-double-double-double-double-double-double-}
```
public Matrix3D(double a, double b, double c, double d, double e, double f, double g, double h, double i, double tx, double ty, double tz)
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
| g |  | G-Matrixwert. |
| h |  | H-Matrixwert. |
| i |  | I-Matrixwert. |
| tx |  | TX-Matrixwert. |
| ty |  | TX-Matrixwert. |
| tz |  | TY-Matrixwert. |

### Matrix3D {#Matrix3D-com.aspose.pdf.Matrix3D-}
<p> Konstruktor erstellt eine Standard-1-zu-1-Matrix: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre>

### add {#add-com.aspose.pdf.Matrix3D-}
<p> Addiert die Matrix zu einer anderen Matrix. </p> <hr>

### equals {#equals-java.lang.Object-}
Vergleicht die Matrix mit einem anderen Objekt.

### getA {#getA--}
```
public double getA()
```

A ist ein Mitglied der Transformationsmatrix.

**Returns:**
double-Wert

### getAngle {#getAngle-com.aspose.pdf.Rotation-}
<p> Übersetzt die Rotation in einen Winkel (Grad) </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre>

### getB {#getB--}
```
public double getB()
```

B ist ein Mitglied der Transformationsmatrix.

**Returns:**
double-Wert

### getC {#getC--}
```
public double getC()
```

C ist ein Mitglied der Transformationsmatrix.

**Returns:**
double-Wert

### getD {#getD--}
```
public double getD()
```

D ist ein Mitglied der Transformationsmatrix.

**Returns:**
double-Wert

### getE {#getE--}
```
public double getE()
```

E ist ein Mitglied der Transformationsmatrix.

**Returns:**
double-Wert

### getF {#getF--}
```
public double getF()
```

F ist ein Mitglied der Transformationsmatrix.

**Returns:**
double-Wert

### getG {#getG--}
```
public double getG()
```

G ist ein Mitglied der Transformationsmatrix.

**Returns:**
double-Wert

### getH {#getH--}
```
public double getH()
```

H ist ein Mitglied der Transformationsmatrix.

**Returns:**
double-Wert

### getI {#getI--}
```
public double getI()
```

I ist ein Mitglied der Transformationsmatrix.

**Returns:**
double-Wert

### getTx {#getTx--}
```
public double getTx()
```

Tx ist ein Mitglied der Transformationsmatrix.

**Returns:**
double-Wert

### getTy {#getTy--}
```
public double getTy()
```

Ty ist ein Mitglied der Transformationsmatrix.

**Returns:**
double-Wert

### getTz {#getTz--}
```
public double getTz()
```

Tz ist ein Mitglied der Transformationsmatrix.

**Returns:**
double-Wert

### hashCode {#hashCode--}
```
public int hashCode()
```

<p> Hash-Code für Objekt. </p> <hr>

**Returns:**
Hash-Code.

### setA {#setA-double-}
```
public void setA(double value)
```

A ist ein Mitglied der Transformationsmatrix.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setB {#setB-double-}
```
public void setB(double value)
```

B ist ein Mitglied der Transformationsmatrix.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setC {#setC-double-}
```
public void setC(double value)
```

C ist ein Mitglied der Transformationsmatrix.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setD {#setD-double-}
```
public void setD(double value)
```

D ist ein Mitglied der Transformationsmatrix.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setE {#setE-double-}
```
public void setE(double value)
```

E ist ein Mitglied der Transformationsmatrix.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setF {#setF-double-}
```
public void setF(double value)
```

F ist ein Mitglied der Transformationsmatrix.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setG {#setG-double-}
```
public void setG(double value)
```

G ist ein Mitglied der Transformationsmatrix.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setH {#setH-double-}
```
public void setH(double value)
```

H ist ein Mitglied der Transformationsmatrix.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setI {#setI-double-}
```
public void setI(double value)
```

I ist ein Mitglied der Transformationsmatrix.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setTx {#setTx-double-}
```
public void setTx(double value)
```

Tx ist ein Mitglied der Transformationsmatrix.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setTy {#setTy-double-}
```
public void setTy(double value)
```

Ty ist ein Mitglied der Transformationsmatrix.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setTz {#setTz-double-}
```
public void setTz(double value)
```

Tz ist ein Mitglied der Transformationsmatrix.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### toString {#toString--}
```
public String toString()
```

Gibt die Textdarstellung der Matrix zurück.

**Returns:**
String-Darstellung der Matrix
