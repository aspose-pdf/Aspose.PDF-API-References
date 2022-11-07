---
title: Matrix
second_title: Aspose.PDF for Java API Reference
description: Class represents transformation matrix.
type: docs
weight: 174
url: /java/com.aspose.pdf/matrix/
---
**Inheritance:**
java.lang.Object
```
public final class Matrix
```

Class represents transformation matrix.
## Constructors

| Constructor | Description |
| --- | --- |
| [Matrix()](#Matrix--) | Constructor creates stanrard 1 to 1 matrix: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] |
| [Matrix(double[] matrixArray)](#Matrix-double---) | Constructor accepts a matrix with following array representation: [ A B C D E F ] |
| [Matrix(Matrix matrix)](#Matrix-com.aspose.pdf.Matrix-) | Constructor accepts a matrix to create a copy |
| [Matrix(double a, double b, double c, double d, double e, double f)](#Matrix-double-double-double-double-double-double-) | Initializes transformation matrix with specified coefficients. |
## Methods

| Method | Description |
| --- | --- |
| [getA()](#getA--) | Get A member of the transformation matrix. |
| [setA(double value)](#setA-double-) | Set A member of the transformation matrix. |
| [getB()](#getB--) | Get B member of the transformation matrix. |
| [setB(double value)](#setB-double-) | Set B member of the transformation matrix. |
| [getC()](#getC--) | Get C member of the transformation matrix. |
| [setC(double value)](#setC-double-) | Set C member of the transformation matrix. |
| [getD()](#getD--) | Set D member of the transformation matrix. |
| [setD(double value)](#setD-double-) | Get D member of the transformation matrix. |
| [getE()](#getE--) | Get E member of the transformation matrix. |
| [setE(double value)](#setE-double-) | Set E member of the transformation matrix. |
| [getF()](#getF--) | Get F member of the transformation matrix. |
| [setF(double value)](#setF-double-) | Set F member of the transformation matrix. |
| [toString()](#toString--) | Returns text reporesentation of the matrix. |
| [equals(Object obj)](#equals-java.lang.Object-) | Compares matrix agains other object. |
| [getMatrix(ITrailerable trailer)](#getMatrix-com.aspose.pdf.engine.data.ITrailerable-) | Translates matrix into PDF array obect. |
| [rotation(double alpha)](#rotation-double-) | Creates matrix for given rotation angle. |
| [getAngle(int rotation)](#getAngle-int-) | Transaltes rotation into angle (degrees) |
| [multiply(Matrix other)](#multiply-com.aspose.pdf.Matrix-) | Multiplies the matrix by other matrix. |
| [transform(Point p)](#transform-com.aspose.pdf.Point-) | Transforms point using this matrix. |
| [transform(Rectangle rect)](#transform-com.aspose.pdf.Rectangle-) | Transformes rectangle. |
| [reverse()](#reverse--) | Calculates reverse matrix. |
| [hashCode()](#hashCode--) | Hash-code for object. |
| [skew(double alpha, double beta)](#skew-double-double-) | Creates matrix for given rotation angle. |
| [scale(double x, double y)](#scale-double-double-) | Creates matrix for given scale. |
### Matrix() {#Matrix--}
```
public Matrix()
```


Constructor creates stanrard 1 to 1 matrix: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0]

--------------------

> ```
> Matrix m = new Matrix();
> ```

### Matrix(double[] matrixArray) {#Matrix-double---}
```
public Matrix(double[] matrixArray)
```


Constructor accepts a matrix with following array representation: [ A B C D E F ]

--------------------

> ```
> double[] c = new double[] { 1, 0, 0, 1, 10, 20 };
>  Matrix m = new Matrix(c);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| matrixArray | double[] |  |

### Matrix(Matrix matrix) {#Matrix-com.aspose.pdf.Matrix-}
```
public Matrix(Matrix matrix)
```


Constructor accepts a matrix to create a copy

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.pdf/matrix) |  |

### Matrix(double a, double b, double c, double d, double e, double f) {#Matrix-double-double-double-double-double-double-}
```
public Matrix(double a, double b, double c, double d, double e, double f)
```


Initializes transformation matrix with specified coefficients.

--------------------

> ```
> Matrix m = new Matrix(1, 0, 0, 1, 3, 3);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| a | double | A |
| b | double | B |
| c | double | C |
| d | double | D |
| e | double | E |
| f | double | F |

### getA() {#getA--}
```
public double getA()
```


Get A member of the transformation matrix.

**Returns:**
double
### setA(double value) {#setA-double-}
```
public void setA(double value)
```


Set A member of the transformation matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getB() {#getB--}
```
public double getB()
```


Get B member of the transformation matrix.

**Returns:**
double
### setB(double value) {#setB-double-}
```
public void setB(double value)
```


Set B member of the transformation matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getC() {#getC--}
```
public double getC()
```


Get C member of the transformation matrix.

**Returns:**
double
### setC(double value) {#setC-double-}
```
public void setC(double value)
```


Set C member of the transformation matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getD() {#getD--}
```
public double getD()
```


Set D member of the transformation matrix.

**Returns:**
double
### setD(double value) {#setD-double-}
```
public void setD(double value)
```


Get D member of the transformation matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getE() {#getE--}
```
public double getE()
```


Get E member of the transformation matrix.

**Returns:**
double
### setE(double value) {#setE-double-}
```
public void setE(double value)
```


Set E member of the transformation matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getF() {#getF--}
```
public double getF()
```


Get F member of the transformation matrix.

**Returns:**
double
### setF(double value) {#setF-double-}
```
public void setF(double value)
```


Set F member of the transformation matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### toString() {#toString--}
```
public String toString()
```


Returns text reporesentation of the matrix.

**Returns:**
java.lang.String
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Compares matrix agains other object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean - Returns true is other object is Matrix and all matrix member are equal to correspondim members of the matrix
### getMatrix(ITrailerable trailer) {#getMatrix-com.aspose.pdf.engine.data.ITrailerable-}
```
public IPdfArray getMatrix(ITrailerable trailer)
```


Translates matrix into PDF array obect.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| trailer | [ITrailerable](../../com.aspose.pdf.engine.data/itrailerable) | Trailerable object |

**Returns:**
[IPdfArray](../../com.aspose.pdf.engine.data/ipdfarray) - Result of converting
### rotation(double alpha) {#rotation-double-}
```
public static Matrix rotation(double alpha)
```


Creates matrix for given rotation angle.

--------------------

> ```
> Matrix m = Matrix.Rotation(Math.PI / 2);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| alpha | double | Rotation angle in radians. |

**Returns:**
[Matrix](../../com.aspose.pdf/matrix) - Transformation matrix.
### getAngle(int rotation) {#getAngle-int-}
```
public static double getAngle(int rotation)
```


Transaltes rotation into angle (degrees)

--------------------

> ```
> double angle = Matrix.GetAngle(Rotation.on90);
>  Matrix m = Matrix.Rotation(angle);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rotation | int |  |

**Returns:**
double - 
### multiply(Matrix other) {#multiply-com.aspose.pdf.Matrix-}
```
public Matrix multiply(Matrix other)
```


Multiplies the matrix by other matrix.

--------------------

> ```
> Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 });
>  Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } );
>  Matrix c= a.Multiply(b);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [Matrix](../../com.aspose.pdf/matrix) | Multiplier matrix. |

**Returns:**
[Matrix](../../com.aspose.pdf/matrix) - Result of multiplication.
### transform(Point p) {#transform-com.aspose.pdf.Point-}
```
public Point transform(Point p)
```


Transforms point using this matrix.

--------------------

> ```
> Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
>  Point p = new Point(5, 5);
>  Point p1 = m.Transform(p);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| p | [Point](../../com.aspose.pdf/point) | Point which will be transformed. |

**Returns:**
[Point](../../com.aspose.pdf/point) - Transformation result.
### transform(Rectangle rect) {#transform-com.aspose.pdf.Rectangle-}
```
public Rectangle transform(Rectangle rect)
```


Transformes rectangle. If angle is not 90 \* N degrees then bounding rectangle is returned.

--------------------

> ```
> Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
>  Rectangle r = new Rectangle(0, 0, 100, 100);
>  Rectangle r1 = m.Transform(r1);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle to be transformed. |

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - Transformed rectangle.
### reverse() {#reverse--}
```
public Matrix reverse()
```


Calculates reverse matrix.

--------------------

> ```
> Matrix m = Matrix.Rotation(Math.PI / 2);
>  Matrix m1 = m.Reverse();
> ```

**Returns:**
[Matrix](../../com.aspose.pdf/matrix) - Reverse matrix.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hash-code for object.

**Returns:**
int - Hash-code.
### skew(double alpha, double beta) {#skew-double-double-}
```
public static Matrix skew(double alpha, double beta)
```


Creates matrix for given rotation angle.

```
Matrix m = Matrix.skew(Math.PI / 2, Math.PI / 2);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| alpha | double | Skew x angle in radians. |
| beta | double | Skew y angle in radians. |

**Returns:**
[Matrix](../../com.aspose.pdf/matrix) - Transformation matrix.
### scale(double x, double y) {#scale-double-double-}
```
public static Matrix scale(double x, double y)
```


Creates matrix for given scale.

--------------------

```
Matrix m = Matrix.scale(x, y);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | double | Scale x. |
| y | double | Scale y. |

**Returns:**
[Matrix](../../com.aspose.pdf/matrix) - Transformation matrix.
