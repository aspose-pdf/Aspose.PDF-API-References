---
title: "Matrix"
linktitle: "Matrix"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass representerar transformationsmatris."
type: docs
weight: 2900
url: /sv/java/com.aspose.pdf/matrix/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Matrix

```
public final class Matrix extends Object
```

Klass representerar transformationsmatris.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Matrix](#Matrix--) | <p> Konstruktorn skapar standard 1 till 1-matris: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre> |
| [Matrix](#Matrix-double:A-) | <p> Konstruktorn accepterar en matris med följande arrayrepresentation: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre> |
| [Matrix](#Matrix-double-double-double-double-double-double-) | <p> Initierar transformationsmatris med angivna koefficienter. </p> <hr> <pre> Matrix m = new Matrix(1, 0, 0, 1, 3, 3); </pre> |
| [Matrix](#Matrix-float:A-) | <p> Konstruktorn accepterar en matris med följande arrayrepresentation: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre> |
| [Matrix](#Matrix-com.aspose.pdf.Matrix-) | <p> Konstruktorn skapar standard 1 till 1-matris: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre> |
| [Matrix](#Matrix-com.aspose.ms.System.Drawing.Drawing2D.Matrix-) | <p> Konstruktorn skapar standard 1 till 1-matris: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre> |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add](#add-com.aspose.pdf.Matrix-) | Lägger till matris till en annan matris. |
| [equals](#equals-java.lang.Object-) | Jämför matris med annat objekt. |
| [getA](#getA--) | Hämta A-medlemmen i transformationsmatrisen. |
| [getAngle](#getAngle-com.aspose.pdf.Rotation-) | <p> Översätter rotation till vinkel (grader) </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre> |
| [getB](#getB--) | Hämta B-medlemmen i transformationsmatrisen. |
| [getC](#getC--) | Hämta C-medlemmen i transformationsmatrisen. |
| [getD](#getD--) | Hämta D-medlemmen i transformationsmatrisen. |
| [getData](#getData--) | Hämtar data från Matrix som array. |
| [getE](#getE--) | Hämta E-medlemmen i transformationsmatrisen. |
| [getElements](#getElements--) | Element i matrisen. |
| [getF](#getF--) | Hämta F-medlemmen i transformationsmatrisen. |
| [getFlipMatrix](#getFlipMatrix--) | Hämtar vändningsmatrisen. |
| [getMatrix](#getMatrix-com.aspose.pdf.engine.data.ITrailerable-) | Översätter matris till PDF-arrayobjekt. |
| [hashCode](#hashCode--) | Hashkod för objekt. |
| [isIdentity](#isIdentity--) | Kontrollerar om denna matris är identitet. |
| [isInt16](#isInt16-double-) | Endast för intern användning |
| [isInt16Values](#isInt16Values--) | Endast för intern användning |
| [multiply](#multiply-com.aspose.pdf.Matrix-) | <p> Multiplicerar matrisen med en annan matris. </p> <hr> <pre> Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 }); Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } ); Matrix c= a.multiply(b); </pre> |
| [reverse](#reverse--) | <p> Beräknar omvänd matris. </p> <hr> <pre> Matrix m = Matrix.rotation(Math.PI / 2); Matrix m1 = m.reverse(); </pre> |
| [rotation](#rotation-double-) | <p> Skapar matris för given rotationsvinkel. </p> <hr> <pre> Matrix m = Matrix.Rotation(Math.PI / 2); </pre> |
| [rotation](#rotation-com.aspose.pdf.Rotation-) | Skapar matris för given rotation. |
| [scale](#scale-double-double-) | <p> Skapar matris för given skalning. </p> <hr> <pre> Matrix m = Matrix.scale(x, y); </pre> |
| [scale](#scale-double-double-double:A-double:A-) | Skalar x och y med matrisen med följande formel: x1 = A*x + C*y; y1 = B*x + D*y; |
| [scale](#scale-double-double-com.aspose.pdf.Matrix-) | Tillämpar skalning på den givna matrisen. |
| [setA](#setA-double-) | Sätt A-medlemmen i transformationsmatrisen. |
| [setB](#setB-double-) | Sätt B-medlemmen i transformationsmatrisen. |
| [setC](#setC-double-) | Sätt C-medlemmen i transformationsmatrisen. |
| [setD](#setD-double-) | Sätt D-medlemmen i transformationsmatrisen. |
| [setE](#setE-double-) | Sätt E-medlemmen i transformationsmatrisen. |
| [setF](#setF-double-) | Sätt F-medlemmen i transformationsmatrisen. |
| [skew](#skew-double-double-) | Skapar matris för given rotationsvinkel. Matrix m = Matrix.skew(Math.PI / 2, Math.PI / 2); |
| [toString](#toString--) | Returnerar textrepresentation av matrisen. |
| [transform](#transform-double-double-double:A-double:A-) | Transformerar koordinater med denna matris. Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); double x, y, x1, y1; m.transform(double x, double y, out double x1, out double y1); |
| [transform](#transform-com.aspose.pdf.Point-) | Transformerar punkt med denna matris. Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); Point p = new Point(5, 5); Point p1 = m.transform(p); |
| [transform](#transform-com.aspose.pdf.Rectangle-) | Transformerar rektangel. |
| [translate](#translate-double-double-com.aspose.pdf.Matrix-) | Översätter en matris med den angivna mängden i x- och y-riktning. |
| [unScale](#unScale-double-double-double:A-double:A-) | Skalar tillbaka x1 och y1 och returnerar x och y före matrisomvandlingen med hjälp av följande formel: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B); |
| [unTransform](#unTransform-double-double-double:A-double:A-) | Transformerar tillbaka x1 och y1 och returnerar x och y före matrisomvandlingen med hjälp av följande formel: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B). |

### Matrix {#Matrix--}
```
public Matrix()
```

<p> Konstruktorn skapar standard 1 till 1-matris: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre>

### Matrix {#Matrix-double:A-}
```
public Matrix(double[] matrixArray)
```

<p> Konstruktorn accepterar en matris med följande arrayrepresentation: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre>

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrixArray |  | Matrisens dataarray. |

### Matrix {#Matrix-double-double-double-double-double-double-}
```
public Matrix(double a, double b, double c, double d, double e, double f)
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

### Matrix {#Matrix-float:A-}
```
public Matrix(float[] matrixArray)
```

<p> Konstruktorn accepterar en matris med följande arrayrepresentation: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre>

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| matrixArray |  | Matrisens dataarray. |

### Matrix {#Matrix-com.aspose.pdf.Matrix-}
<p> Konstruktorn skapar standard 1 till 1-matris: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre>

### Matrix {#Matrix-com.aspose.ms.System.Drawing.Drawing2D.Matrix-}
<p> Konstruktorn skapar standard 1 till 1-matris: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre>

### add {#add-com.aspose.pdf.Matrix-}
Lägger till matris till en annan matris.

### equals {#equals-java.lang.Object-}
Jämför matris med annat objekt.

### getA {#getA--}
```
public double getA()
```

Hämta A-medlemmen i transformationsmatrisen.

**Returns:**
double-värde

### getAngle {#getAngle-com.aspose.pdf.Rotation-}
<p> Översätter rotation till vinkel (grader) </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre>

### getB {#getB--}
```
public double getB()
```

Hämta B-medlemmen i transformationsmatrisen.

**Returns:**
double-värde

### getC {#getC--}
```
public double getC()
```

Hämta C-medlemmen i transformationsmatrisen.

**Returns:**
double-värde

### getD {#getD--}
```
public double getD()
```

Hämta D-medlemmen i transformationsmatrisen.

**Returns:**
double-värde

### getData {#getData--}
```
public final double[] getData()
```

Hämtar data från Matrix som array.

**Returns:**
array av doublevärden

### getE {#getE--}
```
public double getE()
```

Hämta E-medlemmen i transformationsmatrisen.

**Returns:**
double-värde

### getElements {#getElements--}
```
public float[] getElements()
```

Element i matrisen.

**Returns:**
float[] array

### getF {#getF--}
```
public double getF()
```

Hämta F-medlemmen i transformationsmatrisen.

**Returns:**
double-värde

### getFlipMatrix {#getFlipMatrix--}
```
public final Matrix getFlipMatrix()
```

Hämtar vändningsmatrisen.

**Returns:**
Matrisinstans

### getMatrix {#getMatrix-com.aspose.pdf.engine.data.ITrailerable-}
Översätter matris till PDF-arrayobjekt.

### hashCode {#hashCode--}
```
public int hashCode()
```

Hashkod för objekt.

**Returns:**
Hashkod.

### isIdentity {#isIdentity--}
```
public final boolean isIdentity()
```

Kontrollerar om denna matris är identitet.

**Returns:**
booleskt värde

### isInt16 {#isInt16-double-}
```
public static boolean isInt16(double value)
```

Endast för intern användning

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

**Returns:**
booleskt värde

### isInt16Values {#isInt16Values--}
```
public boolean isInt16Values()
```

Endast för intern användning

**Returns:**
booleskt värde

### multiply {#multiply-com.aspose.pdf.Matrix-}
<p> Multiplicerar matrisen med en annan matris. </p> <hr> <pre> Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 }); Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } ); Matrix c= a.multiply(b); </pre>

### reverse {#reverse--}
```
public Matrix reverse()
```

<p> Beräknar omvänd matris. </p> <hr> <pre> Matrix m = Matrix.rotation(Math.PI / 2); Matrix m1 = m.reverse(); </pre>

**Returns:**
Omvänd matris.

### rotation {#rotation-double-}
```
public static Matrix rotation(double alpha)
```

<p> Skapar matris för given rotationsvinkel. </p> <hr> <pre> Matrix m = Matrix.Rotation(Math.PI / 2); </pre>

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| alpha |  | Rotationsvinkel i radianer. |

**Returns:**
Transformationsmatris.

### rotation {#rotation-com.aspose.pdf.Rotation-}
Skapar matris för given rotation.

### scale {#scale-double-double-}
```
public static Matrix scale(double x, double y)
```

<p> Skapar matris för given skalning. </p> <hr> <pre> Matrix m = Matrix.scale(x, y); </pre>

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x |  | Skala x. |
| y |  | Skala y. |

**Returns:**
Transformationsmatris.

### scale {#scale-double-double-double:A-double:A-}
```
public final void scale(double x, double y, double[] x1, double[] y1)
```

Skalar x och y med matrisen med följande formel: x1 = A*x + C*y; y1 = B*x + D*y;

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x |  | Indata X-koordinat |
| y |  | Indata Y-koordinat |
| x1 |  | Utdata X-koordinat |
| y1 |  | Utdata Y-koordinat |

### scale {#scale-double-double-com.aspose.pdf.Matrix-}
Tillämpar skalning på den givna matrisen.

### setA {#setA-double-}
```
public void setA(double value)
```

Sätt A-medlemmen i transformationsmatrisen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setB {#setB-double-}
```
public void setB(double value)
```

Sätt B-medlemmen i transformationsmatrisen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setC {#setC-double-}
```
public void setC(double value)
```

Sätt C-medlemmen i transformationsmatrisen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setD {#setD-double-}
```
public void setD(double value)
```

Sätt D-medlemmen i transformationsmatrisen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setE {#setE-double-}
```
public void setE(double value)
```

Sätt E-medlemmen i transformationsmatrisen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setF {#setF-double-}
```
public void setF(double value)
```

Sätt F-medlemmen i transformationsmatrisen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### skew {#skew-double-double-}
```
public static Matrix skew(double alpha, double beta)
```

Skapar matris för given rotationsvinkel. Matrix m = Matrix.skew(Math.PI / 2, Math.PI / 2);

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| alpha |  | Snedvinkel för x i radianer. |
| beta |  | Snedvinkel för y i radianer. |

**Returns:**
Transformationsmatris.

### toString {#toString--}
```
public String toString()
```

Returnerar textrepresentation av matrisen.

**Returns:**
Strängrepresentation för matrisen

### transform {#transform-double-double-double:A-double:A-}
```
public final void transform(double x, double y, double[] x1, double[] y1)
```

Transformerar koordinater med denna matris. Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); double x, y, x1, y1; m.transform(double x, double y, out double x1, out double y1);

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x |  | X-koordinat. |
| y |  | Y-koordinat. |
| x1 |  | Transformerad X-koordinat. |
| y1 |  | Transformerad Y-koordinat. |

### transform {#transform-com.aspose.pdf.Point-}
Transformerar punkt med denna matris. Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); Point p = new Point(5, 5); Point p1 = m.transform(p);

### transform {#transform-com.aspose.pdf.Rectangle-}
Transformerar rektangel.

### translate {#translate-double-double-com.aspose.pdf.Matrix-}
Översätter en matris med den angivna mängden i x- och y-riktning.

### unScale {#unScale-double-double-double:A-double:A-}
```
public final void unScale(double x1, double y1, double[] x, double[] y)
```

Skalar tillbaka x1 och y1 och returnerar x och y före matrisomvandlingen med hjälp av följande formel: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B);

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x1 |  | Indata X-koordinat |
| y1 |  | Indata Y-koordinat |
| x |  | Utdata X-koordinat |
| y |  | Utdata Y-koordinat |

### unTransform {#unTransform-double-double-double:A-double:A-}
```
public final void unTransform(double x1, double y1, double[] x, double[] y)
```

Transformerar tillbaka x1 och y1 och returnerar x och y före matrisomvandlingen med hjälp av följande formel: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x1 |  | Indata X-koordinat |
| y1 |  | Indata Y-koordinat |
| x |  | Utdata X-koordinat |
| y |  | Utdata Y-koordinat |
