---
title: "Matrix3D"
linktitle: "Matrix3D"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass representerar transformationsmatris."
type: docs
weight: 2910
url: /sv/java/com.aspose.pdf/matrix3d/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Matrix3D

```
public final class Matrix3D extends Object
```

Klass representerar transformationsmatris.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Matrix3D](#Matrix3D--) | <p> Konstruktorn skapar en standard 1 till 1-matris: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre> |
| [Matrix3D](#Matrix3D-double:A-) | <p> Konstruktorn accepterar en matris med följande arrayrepresentation: [ A B C D E F G H I Tx Ty Tz] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20, 1, 0, 0, 17, 40, 13 }; Matrix3D m = new Matrix3D(c); </pre> |
| [Matrix3D](#Matrix3D-double-double-double-double-double-double-double-double-double-double-double-double-) | <p> Initierar transformationsmatris med angivna koefficienter. </p> <hr> <pre> Matrix m = new Matrix(1, 0, 0, 1, 3, 3); </pre> |
| [Matrix3D](#Matrix3D-com.aspose.pdf.Matrix3D-) | <p> Konstruktorn skapar en standard 1 till 1-matris: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre> |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add](#add-com.aspose.pdf.Matrix3D-) | <p> Lägger till matris till en annan matris. </p> <hr> |
| [equals](#equals-java.lang.Object-) | Jämför matris med ett annat objekt. |
| [getA](#getA--) | A-medlem i transformationsmatrisen. |
| [getAngle](#getAngle-com.aspose.pdf.Rotation-) | <p> Översätter rotation till vinkel (grader) </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre> |
| [getB](#getB--) | B-medlem i transformationsmatrisen. |
| [getC](#getC--) | C-medlem i transformationsmatrisen. |
| [getD](#getD--) | D-medlem i transformationsmatrisen. |
| [getE](#getE--) | E-medlem i transformationsmatrisen. |
| [getF](#getF--) | F-medlem i transformationsmatrisen. |
| [getG](#getG--) | G-medlem i transformationsmatrisen. |
| [getH](#getH--) | H-medlem i transformationsmatrisen. |
| [getI](#getI--) | I-medlem i transformationsmatrisen. |
| [getTx](#getTx--) | Tx-medlem i transformationsmatrisen. |
| [getTy](#getTy--) | Ty-medlem i transformationsmatrisen. |
| [getTz](#getTz--) | Tz-medlem i transformationsmatrisen. |
| [hashCode](#hashCode--) | <p> Hash-kod för objekt. </p> <hr> |
| [setA](#setA-double-) | A-medlem i transformationsmatrisen. |
| [setB](#setB-double-) | B-medlem i transformationsmatrisen. |
| [setC](#setC-double-) | C-medlem i transformationsmatrisen. |
| [setD](#setD-double-) | D-medlem i transformationsmatrisen. |
| [setE](#setE-double-) | E-medlem i transformationsmatrisen. |
| [setF](#setF-double-) | F-medlem i transformationsmatrisen. |
| [setG](#setG-double-) | G-medlem i transformationsmatrisen. |
| [setH](#setH-double-) | H-medlem i transformationsmatrisen. |
| [setI](#setI-double-) | I-medlem i transformationsmatrisen. |
| [setTx](#setTx-double-) | Tx-medlem i transformationsmatrisen. |
| [setTy](#setTy-double-) | Ty-medlem i transformationsmatrisen. |
| [setTz](#setTz-double-) | Tz-medlem i transformationsmatrisen. |
| [toString](#toString--) | Returnerar textrepresentation av matrisen. |

### Matrix3D {#Matrix3D--}
```
public Matrix3D()
```

<p> Konstruktorn skapar en standard 1 till 1-matris: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre>

### Matrix3D {#Matrix3D-double:A-}
```
public Matrix3D(double[] matrix3DArray)
```

<p> Konstruktorn accepterar en matris med följande arrayrepresentation: [ A B C D E F G H I Tx Ty Tz] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20, 1, 0, 0, 17, 40, 13 }; Matrix3D m = new Matrix3D(c); </pre>

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrix3DArray |  | Matrisens dataarray. |

### Matrix3D {#Matrix3D-double-double-double-double-double-double-double-double-double-double-double-double-}
```
public Matrix3D(double a, double b, double c, double d, double e, double f, double g, double h, double i, double tx, double ty, double tz)
```

<p> Initierar transformationsmatris med angivna koefficienter. </p> <hr> <pre> Matrix m = new Matrix(1, 0, 0, 1, 3, 3); </pre>

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a |  | Ett matrisvärde. |
| b |  | B matrisvärde. |
| c |  | C matrisvärde. |
| d |  | D matrisvärde. |
| e |  | E matrisvärde. |
| f |  | F matrisvärde. |
| g |  | G matrisvärde. |
| h |  | H matrisvärde. |
| i |  | I matrisvärde. |
| tx |  | TX matrisvärde. |
| ty |  | TX matrisvärde. |
| tz |  | TY matrisvärde. |

### Matrix3D {#Matrix3D-com.aspose.pdf.Matrix3D-}
<p> Konstruktorn skapar en standard 1 till 1-matris: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre>

### add {#add-com.aspose.pdf.Matrix3D-}
<p> Lägger till matris till en annan matris. </p> <hr>

### equals {#equals-java.lang.Object-}
Jämför matris med ett annat objekt.

### getA {#getA--}
```
public double getA()
```

A-medlem i transformationsmatrisen.

**Returns:**
double-värde

### getAngle {#getAngle-com.aspose.pdf.Rotation-}
<p> Översätter rotation till vinkel (grader) </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre>

### getB {#getB--}
```
public double getB()
```

B-medlem i transformationsmatrisen.

**Returns:**
double-värde

### getC {#getC--}
```
public double getC()
```

C-medlem i transformationsmatrisen.

**Returns:**
double-värde

### getD {#getD--}
```
public double getD()
```

D-medlem i transformationsmatrisen.

**Returns:**
double-värde

### getE {#getE--}
```
public double getE()
```

E-medlem i transformationsmatrisen.

**Returns:**
double-värde

### getF {#getF--}
```
public double getF()
```

F-medlem i transformationsmatrisen.

**Returns:**
double-värde

### getG {#getG--}
```
public double getG()
```

G-medlem i transformationsmatrisen.

**Returns:**
double-värde

### getH {#getH--}
```
public double getH()
```

H-medlem i transformationsmatrisen.

**Returns:**
double-värde

### getI {#getI--}
```
public double getI()
```

I-medlem i transformationsmatrisen.

**Returns:**
double-värde

### getTx {#getTx--}
```
public double getTx()
```

Tx-medlem i transformationsmatrisen.

**Returns:**
double-värde

### getTy {#getTy--}
```
public double getTy()
```

Ty-medlem i transformationsmatrisen.

**Returns:**
double-värde

### getTz {#getTz--}
```
public double getTz()
```

Tz-medlem i transformationsmatrisen.

**Returns:**
double-värde

### hashCode {#hashCode--}
```
public int hashCode()
```

<p> Hash-kod för objekt. </p> <hr>

**Returns:**
Hashkod.

### setA {#setA-double-}
```
public void setA(double value)
```

A-medlem i transformationsmatrisen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setB {#setB-double-}
```
public void setB(double value)
```

B-medlem i transformationsmatrisen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setC {#setC-double-}
```
public void setC(double value)
```

C-medlem i transformationsmatrisen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setD {#setD-double-}
```
public void setD(double value)
```

D-medlem i transformationsmatrisen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setE {#setE-double-}
```
public void setE(double value)
```

E-medlem i transformationsmatrisen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setF {#setF-double-}
```
public void setF(double value)
```

F-medlem i transformationsmatrisen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setG {#setG-double-}
```
public void setG(double value)
```

G-medlem i transformationsmatrisen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setH {#setH-double-}
```
public void setH(double value)
```

H-medlem i transformationsmatrisen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setI {#setI-double-}
```
public void setI(double value)
```

I-medlem i transformationsmatrisen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setTx {#setTx-double-}
```
public void setTx(double value)
```

Tx-medlem i transformationsmatrisen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setTy {#setTy-double-}
```
public void setTy(double value)
```

Ty-medlem i transformationsmatrisen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setTz {#setTz-double-}
```
public void setTz(double value)
```

Tz-medlem i transformationsmatrisen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### toString {#toString--}
```
public String toString()
```

Returnerar textrepresentation av matrisen.

**Returns:**
Strängrepresentation för matrisen
