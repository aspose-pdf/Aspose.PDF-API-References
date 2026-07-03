---
title: Matrix
second_title: Aspose.PDF for Java API Reference
description: Class represents transformation matrix.
type: docs
weight: 2900
url: /java/com.aspose.pdf/matrix/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Matrix

```
public final class Matrix extends Object
```

Class represents transformation matrix.

## Constructors

| Constructor | Description |
| --- | --- |
| [Matrix](#Matrix--) | <p> Constructor creates stanrard 1 to 1 matrix: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre> |
| [Matrix](#Matrix-double:A-) | <p> Constructor accepts a matrix with following array representation: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre> |
| [Matrix](#Matrix-double-double-double-double-double-double-) | <p> Initializes transformation matrix with specified coefficients. </p> <hr> <pre> Matrix m = new Matrix(1, 0, 0, 1, 3, 3); </pre> |
| [Matrix](#Matrix-float:A-) | <p> Constructor accepts a matrix with following array representation: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre> |
| [Matrix](#Matrix-com.aspose.pdf.Matrix-) | <p> Constructor creates stanrard 1 to 1 matrix: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre> |
| [Matrix](#Matrix-com.aspose.ms.System.Drawing.Drawing2D.Matrix-) | <p> Constructor creates stanrard 1 to 1 matrix: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre> |

## Methods

| Method | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.Matrix-) | Adds matrix to other matrix. |
| [equals](#equals-java.lang.Object-) | Compares matrix agains other object. |
| [getA](#getA--) | Get A member of the transformation matrix. |
| [getAngle](#getAngle-com.aspose.pdf.Rotation-) | <p> Transaltes rotation into angle (degrees) </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre> |
| [getB](#getB--) | Get B member of the transformation matrix. |
| [getC](#getC--) | Get C member of the transformation matrix. |
| [getD](#getD--) | Get D member of the transformation matrix. |
| [getData](#getData--) | Gets data of Matrix as array. |
| [getE](#getE--) | Get E member of the transformation matrix. |
| [getElements](#getElements--) | Elements of the matrix. |
| [getF](#getF--) | Get F member of the transformation matrix. |
| [getFlipMatrix](#getFlipMatrix--) | Gets the flipping matrix. |
| [getMatrix](#getMatrix-com.aspose.pdf.engine.data.ITrailerable-) | Translates matrix into PDF array obect. |
| [hashCode](#hashCode--) | Hash-code for object. |
| [isIdentity](#isIdentity--) | Checks whether this matrix is identity. |
| [isInt16](#isInt16-double-) | For Internal usage only |
| [isInt16Values](#isInt16Values--) | For Internal usage only |
| [multiply](#multiply-com.aspose.pdf.Matrix-) | <p> Multiplies the matrix by other matrix. </p> <hr> <pre> Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 }); Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } ); Matrix c= a.multiply(b); </pre> |
| [reverse](#reverse--) | <p> Calculates reverse matrix. </p> <hr> <pre> Matrix m = Matrix.rotation(Math.PI / 2); Matrix m1 = m.reverse(); </pre> |
| [rotation](#rotation-double-) | <p> Creates matrix for given rotation angle. </p> <hr> <pre> Matrix m = Matrix.Rotation(Math.PI / 2); </pre> |
| [rotation](#rotation-com.aspose.pdf.Rotation-) | Creates matrix for given rotation. |
| [scale](#scale-double-double-) | <p> Creates matrix for given scale. </p> <hr> <pre> Matrix m = Matrix.scale(x, y); </pre> |
| [scale](#scale-double-double-double:A-double:A-) | Scales x and y with the matrix using the following formula: x1 = A*x + C*y; y1 = B*x + D*y; |
| [scale](#scale-double-double-com.aspose.pdf.Matrix-) | Applies scaling to the given matrix. |
| [setA](#setA-double-) | Set A member of the transformation matrix. |
| [setB](#setB-double-) | Set B member of the transformation matrix. |
| [setC](#setC-double-) | Set C member of the transformation matrix. |
| [setD](#setD-double-) | Set D member of the transformation matrix. |
| [setE](#setE-double-) | Set E member of the transformation matrix. |
| [setF](#setF-double-) | Set F member of the transformation matrix. |
| [skew](#skew-double-double-) | Creates matrix for given rotation angle. Matrix m = Matrix.skew(Math.PI / 2, Math.PI / 2); |
| [toString](#toString--) | Returns text representation of the matrix. |
| [transform](#transform-double-double-double:A-double:A-) | Transforms coordinates using this matrix. Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); double x, y, x1, y1; m.transform(double x, double y, out double x1, out double y1); |
| [transform](#transform-com.aspose.pdf.Point-) | Transforms point using this matrix. Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); Point p = new Point(5, 5); Point p1 = m.transform(p); |
| [transform](#transform-com.aspose.pdf.Rectangle-) | Transforms rectangle. |
| [translate](#translate-double-double-com.aspose.pdf.Matrix-) | Translates a matrix by the specified amount in the x and y direction. |
| [unScale](#unScale-double-double-double:A-double:A-) | Scales back x1 and y1 and returns x and y before the matrix transformation using the following formula: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B); |
| [unTransform](#unTransform-double-double-double:A-double:A-) | Transforms back x1 and y1 and returns x and y before the matrix transformation using the following formula: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B). |

### Matrix {#Matrix--}
```
public Matrix()
```

<p> Constructor creates stanrard 1 to 1 matrix: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre>

### Matrix {#Matrix-double:A-}
```
public Matrix(double[] matrixArray)
```

<p> Constructor accepts a matrix with following array representation: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre>

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| matrixArray |  | Matrix data array. |

### Matrix {#Matrix-double-double-double-double-double-double-}
```
public Matrix(double a, double b, double c, double d, double e, double f)
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

### Matrix {#Matrix-float:A-}
```
public Matrix(float[] matrixArray)
```

<p> Constructor accepts a matrix with following array representation: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre>

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| matrixArray |  | Matrix data array. |

### Matrix {#Matrix-com.aspose.pdf.Matrix-}
<p> Constructor creates stanrard 1 to 1 matrix: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre>

### Matrix {#Matrix-com.aspose.ms.System.Drawing.Drawing2D.Matrix-}
<p> Constructor creates stanrard 1 to 1 matrix: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre>

### add {#add-com.aspose.pdf.Matrix-}
Adds matrix to other matrix.

### equals {#equals-java.lang.Object-}
Compares matrix agains other object.

### getA {#getA--}
```
public double getA()
```

Get A member of the transformation matrix.

**Returns:**
double value

### getAngle {#getAngle-com.aspose.pdf.Rotation-}
<p> Transaltes rotation into angle (degrees) </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre>

### getB {#getB--}
```
public double getB()
```

Get B member of the transformation matrix.

**Returns:**
double value

### getC {#getC--}
```
public double getC()
```

Get C member of the transformation matrix.

**Returns:**
double value

### getD {#getD--}
```
public double getD()
```

Get D member of the transformation matrix.

**Returns:**
double value

### getData {#getData--}
```
public final double[] getData()
```

Gets data of Matrix as array.

**Returns:**
array of double values

### getE {#getE--}
```
public double getE()
```

Get E member of the transformation matrix.

**Returns:**
double value

### getElements {#getElements--}
```
public float[] getElements()
```

Elements of the matrix.

**Returns:**
float[] array

### getF {#getF--}
```
public double getF()
```

Get F member of the transformation matrix.

**Returns:**
double value

### getFlipMatrix {#getFlipMatrix--}
```
public final Matrix getFlipMatrix()
```

Gets the flipping matrix.

**Returns:**
Matrix instance

### getMatrix {#getMatrix-com.aspose.pdf.engine.data.ITrailerable-}
Translates matrix into PDF array obect.

### hashCode {#hashCode--}
```
public int hashCode()
```

Hash-code for object.

**Returns:**
Hash-code.

### isIdentity {#isIdentity--}
```
public final boolean isIdentity()
```

Checks whether this matrix is identity.

**Returns:**
boolean value

### isInt16 {#isInt16-double-}
```
public static boolean isInt16(double value)
```

For Internal usage only

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

**Returns:**
boolean value

### isInt16Values {#isInt16Values--}
```
public boolean isInt16Values()
```

For Internal usage only

**Returns:**
boolean value

### multiply {#multiply-com.aspose.pdf.Matrix-}
<p> Multiplies the matrix by other matrix. </p> <hr> <pre> Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 }); Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } ); Matrix c= a.multiply(b); </pre>

### reverse {#reverse--}
```
public Matrix reverse()
```

<p> Calculates reverse matrix. </p> <hr> <pre> Matrix m = Matrix.rotation(Math.PI / 2); Matrix m1 = m.reverse(); </pre>

**Returns:**
Reverse matrix.

### rotation {#rotation-double-}
```
public static Matrix rotation(double alpha)
```

<p> Creates matrix for given rotation angle. </p> <hr> <pre> Matrix m = Matrix.Rotation(Math.PI / 2); </pre>

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| alpha |  | Rotation angle in radians. |

**Returns:**
Transformation matrix.

### rotation {#rotation-com.aspose.pdf.Rotation-}
Creates matrix for given rotation.

### scale {#scale-double-double-}
```
public static Matrix scale(double x, double y)
```

<p> Creates matrix for given scale. </p> <hr> <pre> Matrix m = Matrix.scale(x, y); </pre>

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x |  | Scale x. |
| y |  | Scale y. |

**Returns:**
Transformation matrix.

### scale {#scale-double-double-double:A-double:A-}
```
public final void scale(double x, double y, double[] x1, double[] y1)
```

Scales x and y with the matrix using the following formula: x1 = A*x + C*y; y1 = B*x + D*y;

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x |  | Input X coordinate |
| y |  | Input Y coordinate |
| x1 |  | Output X coordinate |
| y1 |  | Output Y coordinate |

### scale {#scale-double-double-com.aspose.pdf.Matrix-}
Applies scaling to the given matrix.

### setA {#setA-double-}
```
public void setA(double value)
```

Set A member of the transformation matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setB {#setB-double-}
```
public void setB(double value)
```

Set B member of the transformation matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setC {#setC-double-}
```
public void setC(double value)
```

Set C member of the transformation matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setD {#setD-double-}
```
public void setD(double value)
```

Set D member of the transformation matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setE {#setE-double-}
```
public void setE(double value)
```

Set E member of the transformation matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setF {#setF-double-}
```
public void setF(double value)
```

Set F member of the transformation matrix.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### skew {#skew-double-double-}
```
public static Matrix skew(double alpha, double beta)
```

Creates matrix for given rotation angle. Matrix m = Matrix.skew(Math.PI / 2, Math.PI / 2);

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| alpha |  | Skew x angle in radians. |
| beta |  | Skew y angle in radians. |

**Returns:**
Transformation matrix.

### toString {#toString--}
```
public String toString()
```

Returns text representation of the matrix.

**Returns:**
String representation for the matrix

### transform {#transform-double-double-double:A-double:A-}
```
public final void transform(double x, double y, double[] x1, double[] y1)
```

Transforms coordinates using this matrix. Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); double x, y, x1, y1; m.transform(double x, double y, out double x1, out double y1);

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x |  | X coordinate. |
| y |  | Y coordinate. |
| x1 |  | Transformed X coordinate. |
| y1 |  | Transformed Y coordinate. |

### transform {#transform-com.aspose.pdf.Point-}
Transforms point using this matrix. Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); Point p = new Point(5, 5); Point p1 = m.transform(p);

### transform {#transform-com.aspose.pdf.Rectangle-}
Transforms rectangle.

### translate {#translate-double-double-com.aspose.pdf.Matrix-}
Translates a matrix by the specified amount in the x and y direction.

### unScale {#unScale-double-double-double:A-double:A-}
```
public final void unScale(double x1, double y1, double[] x, double[] y)
```

Scales back x1 and y1 and returns x and y before the matrix transformation using the following formula: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B);

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x1 |  | Input X coordinate |
| y1 |  | Input Y coordinate |
| x |  | Output X coordinate |
| y |  | Output Y coordinate |

### unTransform {#unTransform-double-double-double:A-double:A-}
```
public final void unTransform(double x1, double y1, double[] x, double[] y)
```

Transforms back x1 and y1 and returns x and y before the matrix transformation using the following formula: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| x1 |  | Input X coordinate |
| y1 |  | Input Y coordinate |
| x |  | Output X coordinate |
| y |  | Output Y coordinate |
