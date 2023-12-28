---
title: Matrix
second_title: Aspose.PDF for Java API Reference
description: Class represents transformation matrix.
type: docs
weight: 208
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
| [Matrix(float[] matrixArray)](#Matrix-float---) | Constructor accepts a matrix with following array representation: [ A B C D E F ] |
| [Matrix(Matrix matrix)](#Matrix-com.aspose.pdf.Matrix-) | Constructor accepts a matrix to create a copy |
| [Matrix(System.Drawing.Drawing2D.Matrix matrix)](#Matrix-com.aspose.ms.System.Drawing.Drawing2D.Matrix-) | Constructor accepts a matrix to create a copy |
| [Matrix(double a, double b, double c, double d, double e, double f)](#Matrix-double-double-double-double-double-double-) | Initializes transformation matrix with specified coefficients. |
## Methods

| Method | Description |
| --- | --- |
| [getData()](#getData--) | Gets data of Matrix as array. |
| [getA()](#getA--) | Get A member of the transformation matrix. |
| [setA(double value)](#setA-double-) | Set A member of the transformation matrix. |
| [getB()](#getB--) | Get B member of the transformation matrix. |
| [setB(double value)](#setB-double-) | Set B member of the transformation matrix. |
| [getC()](#getC--) | Get C member of the transformation matrix. |
| [setC(double value)](#setC-double-) | Set C member of the transformation matrix. |
| [getD()](#getD--) | Get D member of the transformation matrix. |
| [setD(double value)](#setD-double-) | Set D member of the transformation matrix. |
| [getE()](#getE--) | Get E member of the transformation matrix. |
| [setE(double value)](#setE-double-) | Set E member of the transformation matrix. |
| [getF()](#getF--) | Get F member of the transformation matrix. |
| [setF(double value)](#setF-double-) | Set F member of the transformation matrix. |
| [isIdentity()](#isIdentity--) | Checks whether this matrix is identity. |
| [getElements()](#getElements--) | Elements of the matrix. |
| [toString()](#toString--) | Returns text representation of the matrix. |
| [equals(Object obj)](#equals-java.lang.Object-) | Compares matrix agains other object. |
| [getMatrix(ITrailerable trailer)](#getMatrix-com.aspose.pdf.engine.data.ITrailerable-) | Translates matrix into PDF array obect. |
| [rotation(double alpha)](#rotation-double-) | Creates matrix for given rotation angle. |
| [rotation(int rotation)](#rotation-int-) | Creates matrix for given rotation. |
| [skew(double alpha, double beta)](#skew-double-double-) | Creates matrix for given rotation angle. |
| [scale(double x, double y)](#scale-double-double-) | Creates matrix for given scale. |
| [scale(double x, double y, double[] x1, double[] y1)](#scale-double-double-double---double---) | Scales x and y with the matrix using the following formula: x1 = A\*x + C\*y; y1 = B\*x + D\*y; |
| [unScale(double x1, double y1, double[] x, double[] y)](#unScale-double-double-double---double---) | Scales back x1 and y1 and returns x and y before the matrix transformation using the following formula: x = (D \* x1 - C \* y1) / (A \* D - C \* B); y = (A\* y1 - B\* x1) / (A\* D - C\* B); |
| [getAngle(int rotation)](#getAngle-int-) | Transaltes rotation into angle (degrees) |
| [multiply(Matrix other)](#multiply-com.aspose.pdf.Matrix-) | Multiplies the matrix by other matrix. |
| [add(Matrix other)](#add-com.aspose.pdf.Matrix-) | Adds matrix to other matrix. |
| [transform(Point p)](#transform-com.aspose.pdf.Point-) | Transforms point using this matrix. |
| [transform(double x, double y, double[] x1, double[] y1)](#transform-double-double-double---double---) | Transforms coordinates using this matrix. |
| [unTransform(double x1, double y1, double[] x, double[] y)](#unTransform-double-double-double---double---) | Transforms back x1 and y1 and returns x and y before the matrix transformation using the following formula: x = (D \* x1 - C \* y1 + C \* F) / (A \* D - C \* B) y = (A \* y1 - B \* x1 + B \* E) / (A \* D - C \* B). |
| [transform(Rectangle rect)](#transform-com.aspose.pdf.Rectangle-) | Transforms rectangle. |
| [reverse()](#reverse--) | Calculates reverse matrix. |
| [hashCode()](#hashCode--) | Hash-code for object. |
| [isInt16(double value)](#isInt16-double-) | For Internal usage only |
| [isInt16Values()](#isInt16Values--) | For Internal usage only |
### Matrix() {#Matrix--}
```
public Matrix()
```


Constructor creates stanrard 1 to 1 matrix: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0]

--------------------

```
Matrix m = new Matrix();
```

### Matrix(double[] matrixArray) {#Matrix-double---}
```
public Matrix(double[] matrixArray)
```


Constructor accepts a matrix with following array representation: [ A B C D E F ]

--------------------

```
double[] c = new double[] { 1, 0, 0, 1, 10, 20 };
 Matrix m = new Matrix(c);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| matrixArray | double[] | Matrix data array. |

### Matrix(float[] matrixArray) {#Matrix-float---}
```
public Matrix(float[] matrixArray)
```


Constructor accepts a matrix with following array representation: [ A B C D E F ]

--------------------

```
double[] c = new double[] { 1, 0, 0, 1, 10, 20 };
 Matrix m = new Matrix(c);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| matrixArray | float[] | Matrix data array. |

### Matrix(Matrix matrix) {#Matrix-com.aspose.pdf.Matrix-}
```
public Matrix(Matrix matrix)
```


Constructor accepts a matrix to create a copy

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.pdf/matrix) | Matrix object. |

### Matrix(System.Drawing.Drawing2D.Matrix matrix) {#Matrix-com.aspose.ms.System.Drawing.Drawing2D.Matrix-}
```
public Matrix(System.Drawing.Drawing2D.Matrix matrix)
```


Constructor accepts a matrix to create a copy

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| matrix | com.aspose.ms.System.Drawing.Drawing2D.Matrix | Matrix object. |

### Matrix(double a, double b, double c, double d, double e, double f) {#Matrix-double-double-double-double-double-double-}
```
public Matrix(double a, double b, double c, double d, double e, double f)
```


Initializes transformation matrix with specified coefficients.

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

### getData() {#getData--}
```
public final double[] getData()
```


Gets data of Matrix as array.

**Returns:**
double[] - array of double values
### getA() {#getA--}
```
public double getA()
```


Get A member of the transformation matrix.

**Returns:**
double - double value
### setA(double value) {#setA-double-}
```
public void setA(double value)
```


Set A member of the transformation matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getB() {#getB--}
```
public double getB()
```


Get B member of the transformation matrix.

**Returns:**
double - double value
### setB(double value) {#setB-double-}
```
public void setB(double value)
```


Set B member of the transformation matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getC() {#getC--}
```
public double getC()
```


Get C member of the transformation matrix.

**Returns:**
double - double value
### setC(double value) {#setC-double-}
```
public void setC(double value)
```


Set C member of the transformation matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getD() {#getD--}
```
public double getD()
```


Get D member of the transformation matrix.

**Returns:**
double - double value
### setD(double value) {#setD-double-}
```
public void setD(double value)
```


Set D member of the transformation matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getE() {#getE--}
```
public double getE()
```


Get E member of the transformation matrix.

**Returns:**
double - double value
### setE(double value) {#setE-double-}
```
public void setE(double value)
```


Set E member of the transformation matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getF() {#getF--}
```
public double getF()
```


Get F member of the transformation matrix.

**Returns:**
double - double value
### setF(double value) {#setF-double-}
```
public void setF(double value)
```


Set F member of the transformation matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### isIdentity() {#isIdentity--}
```
public final boolean isIdentity()
```


Checks whether this matrix is identity.

**Returns:**
boolean - boolean value
### getElements() {#getElements--}
```
public float[] getElements()
```


Elements of the matrix.

**Returns:**
float[] - float[] array
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


Compares matrix agains other object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Object to compare. |

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

```
Matrix m = Matrix.Rotation(Math.PI / 2);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| alpha | double | Rotation angle in radians. |

**Returns:**
[Matrix](../../com.aspose.pdf/matrix) - Transformation matrix.
### rotation(int rotation) {#rotation-int-}
```
public static Matrix rotation(int rotation)
```


Creates matrix for given rotation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rotation | int | Rotation. Valid values are: None, on90, on180, on270 |

**Returns:**
[Matrix](../../com.aspose.pdf/matrix) - Matrix instance with rotation.
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
### scale(double x, double y, double[] x1, double[] y1) {#scale-double-double-double---double---}
```
public final void scale(double x, double y, double[] x1, double[] y1)
```


Scales x and y with the matrix using the following formula: x1 = A\*x + C\*y; y1 = B\*x + D\*y;

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | double | Input X coordinate |
| y | double | Input Y coordinate |
| x1 | double[] | Output X coordinate |
| y1 | double[] | Output Y coordinate |

### unScale(double x1, double y1, double[] x, double[] y) {#unScale-double-double-double---double---}
```
public final void unScale(double x1, double y1, double[] x, double[] y)
```


Scales back x1 and y1 and returns x and y before the matrix transformation using the following formula: x = (D \* x1 - C \* y1) / (A \* D - C \* B); y = (A\* y1 - B\* x1) / (A\* D - C\* B);

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x1 | double | Input X coordinate |
| y1 | double | Input Y coordinate |
| x | double[] | Output X coordinate |
| y | double[] | Output Y coordinate |

### getAngle(int rotation) {#getAngle-int-}
```
public static double getAngle(int rotation)
```


Transaltes rotation into angle (degrees)

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
### multiply(Matrix other) {#multiply-com.aspose.pdf.Matrix-}
```
public Matrix multiply(Matrix other)
```


Multiplies the matrix by other matrix.

--------------------

```
Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 });
 Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } );
 Matrix c= a.multiply(b);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [Matrix](../../com.aspose.pdf/matrix) | Multiplier matrix. |

**Returns:**
[Matrix](../../com.aspose.pdf/matrix) - Result of multiplication.
### add(Matrix other) {#add-com.aspose.pdf.Matrix-}
```
public Matrix add(Matrix other)
```


Adds matrix to other matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [Matrix](../../com.aspose.pdf/matrix) | Matrix to be added. |

**Returns:**
[Matrix](../../com.aspose.pdf/matrix) - Result of matrix add.
### transform(Point p) {#transform-com.aspose.pdf.Point-}
```
public Point transform(Point p)
```


Transforms point using this matrix.

```
Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
 Point p = new Point(5, 5);
 Point p1 = m.transform(p);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| p | [Point](../../com.aspose.pdf/point) | Point which will be transformed. |

**Returns:**
[Point](../../com.aspose.pdf/point) - Transformation result.
### transform(double x, double y, double[] x1, double[] y1) {#transform-double-double-double---double---}
```
public final void transform(double x, double y, double[] x1, double[] y1)
```


Transforms coordinates using this matrix.

```
Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
 double x, y, x1, y1;
 m.transform(double x, double y, out double x1, out double y1);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | double | X coordinate. |
| y | double | Y coordinate. |
| x1 | double[] | Transformed X coordinate. |
| y1 | double[] | Transformed Y coordinate. |

### unTransform(double x1, double y1, double[] x, double[] y) {#unTransform-double-double-double---double---}
```
public final void unTransform(double x1, double y1, double[] x, double[] y)
```


Transforms back x1 and y1 and returns x and y before the matrix transformation using the following formula: x = (D \* x1 - C \* y1 + C \* F) / (A \* D - C \* B) y = (A \* y1 - B \* x1 + B \* E) / (A \* D - C \* B).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x1 | double | Input X coordinate |
| y1 | double | Input Y coordinate |
| x | double[] | Output X coordinate |
| y | double[] | Output Y coordinate |

### transform(Rectangle rect) {#transform-com.aspose.pdf.Rectangle-}
```
public Rectangle transform(Rectangle rect)
```


Transforms rectangle. If angle is not 90 \* N degrees then bounding rectangle is returned.

--------------------

```
Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } );
 Rectangle r = new Rectangle(0, 0, 100, 100);
 Rectangle r1 = m.transform(r1);
```

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

```
Matrix m = Matrix.rotation(Math.PI / 2);
 Matrix m1 = m.reverse();
```

**Returns:**
[Matrix](../../com.aspose.pdf/matrix) - Reverse matrix.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hash-code for object.

**Returns:**
int - Hash-code.
### isInt16(double value) {#isInt16-double-}
```
public static boolean isInt16(double value)
```


For Internal usage only

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

**Returns:**
boolean - boolean value
### isInt16Values() {#isInt16Values--}
```
public boolean isInt16Values()
```


For Internal usage only

**Returns:**
boolean - boolean value
