---
title: Matrix3D
second_title: Aspose.PDF for Java API Reference
description: Class represents transformation matrix.
type: docs
weight: 213
url: /java/com.aspose.pdf/matrix3d/
---
**Inheritance:**
java.lang.Object
```
public final class Matrix3D
```

Class represents transformation matrix.
## Constructors

| Constructor | Description |
| --- | --- |
| [Matrix3D()](#Matrix3D--) | Constructor creates standard 1 to 1 matrix: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] |
| [Matrix3D(double[] matrix3DArray)](#Matrix3D-double---) | Constructor accepts a matrix with following array representation: [ A B C D E F G H I Tx Ty Tz] |
| [Matrix3D(Matrix3D matrix)](#Matrix3D-com.aspose.pdf.Matrix3D-) | Constructor accepts a matrix to create a copy |
| [Matrix3D(double a, double b, double c, double d, double e, double f, double g, double h, double i, double tx, double ty, double tz)](#Matrix3D-double-double-double-double-double-double-double-double-double-double-double-double-) | Transforms point using this matrix. |
## Methods

| Method | Description |
| --- | --- |
| [getA()](#getA--) | A member of the transformation matrix. |
| [setA(double value)](#setA-double-) | A member of the transformation matrix. |
| [getB()](#getB--) | B member of the transformation matrix. |
| [setB(double value)](#setB-double-) | B member of the transformation matrix. |
| [getC()](#getC--) | C member of the transformation matrix. |
| [setC(double value)](#setC-double-) | C member of the transformation matrix. |
| [getD()](#getD--) | D member of the transformation matrix. |
| [setD(double value)](#setD-double-) | D member of the transformation matrix. |
| [getE()](#getE--) | E member of the transformation matrix. |
| [setE(double value)](#setE-double-) | E member of the transformation matrix. |
| [getF()](#getF--) | F member of the transformation matrix. |
| [setF(double value)](#setF-double-) | F member of the transformation matrix. |
| [getG()](#getG--) | G member of the transformation matrix. |
| [setG(double value)](#setG-double-) | G member of the transformation matrix. |
| [getH()](#getH--) | H member of the transformation matrix. |
| [setH(double value)](#setH-double-) | H member of the transformation matrix. |
| [getI()](#getI--) | I member of the transformation matrix. |
| [setI(double value)](#setI-double-) | I member of the transformation matrix. |
| [getTx()](#getTx--) | Tx member of the transformation matrix. |
| [setTx(double value)](#setTx-double-) | Tx member of the transformation matrix. |
| [getTy()](#getTy--) | Ty member of the transformation matrix. |
| [setTy(double value)](#setTy-double-) | Ty member of the transformation matrix. |
| [getTz()](#getTz--) | Tz member of the transformation matrix. |
| [setTz(double value)](#setTz-double-) | Tz member of the transformation matrix. |
| [toString()](#toString--) | Returns text representation of the matrix. |
| [equals(Object obj)](#equals-java.lang.Object-) | Compares matrix against other object. |
| [getAngle(int rotation)](#getAngle-int-) | Creates matrix for given rotation angle. |
| [add(Matrix3D other)](#add-com.aspose.pdf.Matrix3D-) | Multiplies the matrix by other matrix. |
| [hashCode()](#hashCode--) | Calculates reverse matrix. |
### Matrix3D() {#Matrix3D--}
```
public Matrix3D()
```


Constructor creates standard 1 to 1 matrix: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0]

--------------------

```
Matrix3D m = new Matrix3D();
```

### Matrix3D(double[] matrix3DArray) {#Matrix3D-double---}
```
public Matrix3D(double[] matrix3DArray)
```


Constructor accepts a matrix with following array representation: [ A B C D E F G H I Tx Ty Tz]

--------------------

```
double[] c = new double[] { 1, 0, 0, 1, 10, 20, 1, 0, 0, 17, 40, 13 };
 Matrix3D m = new Matrix3D(c);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| matrix3DArray | double[] | Matrix data array. |

### Matrix3D(Matrix3D matrix) {#Matrix3D-com.aspose.pdf.Matrix3D-}
```
public Matrix3D(Matrix3D matrix)
```


Constructor accepts a matrix to create a copy

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| matrix | [Matrix3D](../../com.aspose.pdf/matrix3d) | Matrix3D object. |

### Matrix3D(double a, double b, double c, double d, double e, double f, double g, double h, double i, double tx, double ty, double tz) {#Matrix3D-double-double-double-double-double-double-double-double-double-double-double-double-}
```
public Matrix3D(double a, double b, double c, double d, double e, double f, double g, double h, double i, double tx, double ty, double tz)
```


Transforms point using this matrix.

Transforms rectangle. If angle is not 90 \* N degrees then bounding rectangle is returned.

Initializes transformation matrix with specified coefficients.

--------------------

```
Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
  Point p = new Point(5, 5);
  Point p1 = m.transform(p);
```

--------------------

```
Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
  Rectangle r = new Rectangle(0, 0, 100, 100);
  Rectangle r1 = m.transform(r1);
```

--------------------

```
Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | double | A matrix value. |
| b | double | B matrix value. |
| c | double | C matrix value. |
| d | double | D matrix value. |
| e | double | E matrix value. |
| f | double | F matrix value. |
| g | double | G matrix value. |
| h | double | H matrix value. |
| i | double | I matrix value. |
| tx | double | TX matrix value. |
| ty | double | TX matrix value. |
| tz | double | TY matrix value. |

### getA() {#getA--}
```
public double getA()
```


A member of the transformation matrix.

**Returns:**
double - double value
### setA(double value) {#setA-double-}
```
public void setA(double value)
```


A member of the transformation matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getB() {#getB--}
```
public double getB()
```


B member of the transformation matrix.

**Returns:**
double - double value
### setB(double value) {#setB-double-}
```
public void setB(double value)
```


B member of the transformation matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getC() {#getC--}
```
public double getC()
```


C member of the transformation matrix.

**Returns:**
double - double value
### setC(double value) {#setC-double-}
```
public void setC(double value)
```


C member of the transformation matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getD() {#getD--}
```
public double getD()
```


D member of the transformation matrix.

**Returns:**
double - double value
### setD(double value) {#setD-double-}
```
public void setD(double value)
```


D member of the transformation matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getE() {#getE--}
```
public double getE()
```


E member of the transformation matrix.

**Returns:**
double - double value
### setE(double value) {#setE-double-}
```
public void setE(double value)
```


E member of the transformation matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getF() {#getF--}
```
public double getF()
```


F member of the transformation matrix.

**Returns:**
double - double value
### setF(double value) {#setF-double-}
```
public void setF(double value)
```


F member of the transformation matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getG() {#getG--}
```
public double getG()
```


G member of the transformation matrix.

**Returns:**
double - double value
### setG(double value) {#setG-double-}
```
public void setG(double value)
```


G member of the transformation matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getH() {#getH--}
```
public double getH()
```


H member of the transformation matrix.

**Returns:**
double - double value
### setH(double value) {#setH-double-}
```
public void setH(double value)
```


H member of the transformation matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getI() {#getI--}
```
public double getI()
```


I member of the transformation matrix.

**Returns:**
double - double value
### setI(double value) {#setI-double-}
```
public void setI(double value)
```


I member of the transformation matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getTx() {#getTx--}
```
public double getTx()
```


Tx member of the transformation matrix.

**Returns:**
double - double value
### setTx(double value) {#setTx-double-}
```
public void setTx(double value)
```


Tx member of the transformation matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getTy() {#getTy--}
```
public double getTy()
```


Ty member of the transformation matrix.

**Returns:**
double - double value
### setTy(double value) {#setTy-double-}
```
public void setTy(double value)
```


Ty member of the transformation matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getTz() {#getTz--}
```
public double getTz()
```


Tz member of the transformation matrix.

**Returns:**
double - double value
### setTz(double value) {#setTz-double-}
```
public void setTz(double value)
```


Tz member of the transformation matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### toString() {#toString--}
```
public String toString()
```


Returns text representation of the matrix.

**Returns:**
java.lang.String - String representation for the matrix
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Compares matrix against other object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Object to compare. |

**Returns:**
boolean - Returns true is other object is Matrix3D and all matrix members are equal to corresponding members of the matrix
### getAngle(int rotation) {#getAngle-int-}
```
public static double getAngle(int rotation)
```


Creates matrix for given rotation angle.

Creates matrix for given rotation angle.

Creates matrix for given scale.

Translates rotation into angle (degrees)

--------------------

```
Matrix m = Matrix.Rotation(Math.PI / 2);
```

--------------------

```
Matrix m = Matrix.skew(Math.PI / 2, Math.PI / 2);
```

--------------------

```
Matrix m = Matrix.scale(x, y);
```

--------------------

```
double angle = Matrix.getAngle(Rotation.on90);
 Matrix m = Matrix.rotation(angle);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rotation | int | Rotation value. |

**Returns:**
double - Angle value.
### add(Matrix3D other) {#add-com.aspose.pdf.Matrix3D-}
```
public Matrix3D add(Matrix3D other)
```


Multiplies the matrix by other matrix.

Adds matrix to other matrix.

--------------------

```
Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 });
  Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } );
  Matrix c= a.Multiply(b);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [Matrix3D](../../com.aspose.pdf/matrix3d) | Matrix to be added. |

**Returns:**
[Matrix3D](../../com.aspose.pdf/matrix3d) - Result of matrix add.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Calculates reverse matrix.

Hash-code for object.

--------------------

```
Matrix m = Matrix.Rotation(Math.PI / 2);
  Matrix m1 = m.reverse();
```

**Returns:**
int - Hash-code.
