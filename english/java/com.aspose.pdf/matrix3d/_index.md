---
title: Matrix3D
linktitle: Matrix3D
second_title: Aspose.PDF for Java API Reference
description: Class represents transformation matrix.
type: docs
weight: 2910
url: /java/com.aspose.pdf/matrix3d/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Matrix3D

```
public final class Matrix3D extends Object
```

Class represents transformation matrix.

## Constructors

| Constructor | Description |
| --- | --- |
| [Matrix3D](#Matrix3D--) | <p> Constructor creates standard 1 to 1 matrix: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre> |
| [Matrix3D](#Matrix3D-double:A-) | <p> Constructor accepts a matrix with following array representation: [ A B C D E F G H I Tx Ty Tz] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20, 1, 0, 0, 17, 40, 13 }; Matrix3D m = new Matrix3D(c); </pre> |
| [Matrix3D](#Matrix3D-double-double-double-double-double-double-double-double-double-double-double-double-) | <p> Initializes transformation matrix with specified coefficients. </p> <hr> <pre> Matrix m = new Matrix(1, 0, 0, 1, 3, 3); </pre> |
| [Matrix3D](#Matrix3D-com.aspose.pdf.Matrix3D-) | <p> Constructor creates standard 1 to 1 matrix: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre> |

## Methods

| Method | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.Matrix3D-) | <p> Adds matrix to other matrix. </p> <hr> |
| [equals](#equals-java.lang.Object-) | Compares matrix against other object. |
| [getA](#getA--) | A member of the transformation matrix. |
| [getAngle](#getAngle-com.aspose.pdf.Rotation-) | <p> Translates rotation into angle (degrees) </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre> |
| [getB](#getB--) | B member of the transformation matrix. |
| [getC](#getC--) | C member of the transformation matrix. |
| [getD](#getD--) | D member of the transformation matrix. |
| [getE](#getE--) | E member of the transformation matrix. |
| [getF](#getF--) | F member of the transformation matrix. |
| [getG](#getG--) | G member of the transformation matrix. |
| [getH](#getH--) | H member of the transformation matrix. |
| [getI](#getI--) | I member of the transformation matrix. |
| [getTx](#getTx--) | Tx member of the transformation matrix. |
| [getTy](#getTy--) | Ty member of the transformation matrix. |
| [getTz](#getTz--) | Tz member of the transformation matrix. |
| [hashCode](#hashCode--) | <p> Hash-code for object. </p> <hr> |
| [setA](#setA-double-) | A member of the transformation matrix. |
| [setB](#setB-double-) | B member of the transformation matrix. |
| [setC](#setC-double-) | C member of the transformation matrix. |
| [setD](#setD-double-) | D member of the transformation matrix. |
| [setE](#setE-double-) | E member of the transformation matrix. |
| [setF](#setF-double-) | F member of the transformation matrix. |
| [setG](#setG-double-) | G member of the transformation matrix. |
| [setH](#setH-double-) | H member of the transformation matrix. |
| [setI](#setI-double-) | I member of the transformation matrix. |
| [setTx](#setTx-double-) | Tx member of the transformation matrix. |
| [setTy](#setTy-double-) | Ty member of the transformation matrix. |
| [setTz](#setTz-double-) | Tz member of the transformation matrix. |
| [toString](#toString--) | Returns text representation of the matrix. |

### Matrix3D {#Matrix3D--}
```
public Matrix3D()
```

<p> Constructor creates standard 1 to 1 matrix: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre>

### Matrix3D {#Matrix3D-double:A-}
```
public Matrix3D(double[] matrix3DArray)
```

<p> Constructor accepts a matrix with following array representation: [ A B C D E F G H I Tx Ty Tz] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20, 1, 0, 0, 17, 40, 13 }; Matrix3D m = new Matrix3D(c); </pre>

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| matrix3DArray |  | Matrix data array. |

### Matrix3D {#Matrix3D-double-double-double-double-double-double-double-double-double-double-double-double-}
```
public Matrix3D(double a, double b, double c, double d, double e, double f, double g, double h, double i, double tx, double ty, double tz)
```

<p> Initializes transformation matrix with specified coefficients. </p> <hr> <pre> Matrix m = new Matrix(1, 0, 0, 1, 3, 3); </pre>

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a |  | A matrix value. |
| b |  | B matrix value. |
| c |  | C matrix value. |
| d |  | D matrix value. |
| e |  | E matrix value. |
| f |  | F matrix value. |
| g |  | G matrix value. |
| h |  | H matrix value. |
| i |  | I matrix value. |
| tx |  | TX matrix value. |
| ty |  | TX matrix value. |
| tz |  | TY matrix value. |

### Matrix3D {#Matrix3D-com.aspose.pdf.Matrix3D-}
<p> Constructor creates standard 1 to 1 matrix: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre>

### add {#add-com.aspose.pdf.Matrix3D-}
<p> Adds matrix to other matrix. </p> <hr>

### equals {#equals-java.lang.Object-}
Compares matrix against other object.

### getA {#getA--}
```
public double getA()
```

A member of the transformation matrix.

**Returns:**
double value

### getAngle {#getAngle-com.aspose.pdf.Rotation-}
<p> Translates rotation into angle (degrees) </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre>

### getB {#getB--}
```
public double getB()
```

B member of the transformation matrix.

**Returns:**
double value

### getC {#getC--}
```
public double getC()
```

C member of the transformation matrix.

**Returns:**
double value

### getD {#getD--}
```
public double getD()
```

D member of the transformation matrix.

**Returns:**
double value

### getE {#getE--}
```
public double getE()
```

E member of the transformation matrix.

**Returns:**
double value

### getF {#getF--}
```
public double getF()
```

F member of the transformation matrix.

**Returns:**
double value

### getG {#getG--}
```
public double getG()
```

G member of the transformation matrix.

**Returns:**
double value

### getH {#getH--}
```
public double getH()
```

H member of the transformation matrix.

**Returns:**
double value

### getI {#getI--}
```
public double getI()
```

I member of the transformation matrix.

**Returns:**
double value

### getTx {#getTx--}
```
public double getTx()
```

Tx member of the transformation matrix.

**Returns:**
double value

### getTy {#getTy--}
```
public double getTy()
```

Ty member of the transformation matrix.

**Returns:**
double value

### getTz {#getTz--}
```
public double getTz()
```

Tz member of the transformation matrix.

**Returns:**
double value

### hashCode {#hashCode--}
```
public int hashCode()
```

<p> Hash-code for object. </p> <hr>

**Returns:**
Hash-code.

### setA {#setA-double-}
```
public void setA(double value)
```

A member of the transformation matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setB {#setB-double-}
```
public void setB(double value)
```

B member of the transformation matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setC {#setC-double-}
```
public void setC(double value)
```

C member of the transformation matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setD {#setD-double-}
```
public void setD(double value)
```

D member of the transformation matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setE {#setE-double-}
```
public void setE(double value)
```

E member of the transformation matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setF {#setF-double-}
```
public void setF(double value)
```

F member of the transformation matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setG {#setG-double-}
```
public void setG(double value)
```

G member of the transformation matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setH {#setH-double-}
```
public void setH(double value)
```

H member of the transformation matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setI {#setI-double-}
```
public void setI(double value)
```

I member of the transformation matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setTx {#setTx-double-}
```
public void setTx(double value)
```

Tx member of the transformation matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setTy {#setTy-double-}
```
public void setTy(double value)
```

Ty member of the transformation matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setTz {#setTz-double-}
```
public void setTz(double value)
```

Tz member of the transformation matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### toString {#toString--}
```
public String toString()
```

Returns text representation of the matrix.

**Returns:**
String representation for the matrix
