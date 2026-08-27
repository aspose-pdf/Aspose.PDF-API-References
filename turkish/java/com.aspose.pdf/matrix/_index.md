---
title: "Matris"
linktitle: "Matris"
second_title: "Aspose.PDF for Java API Referansı"
description: "Sınıf, dönüşüm matrisini temsil eder."
type: docs
weight: 2900
url: /tr/java/com.aspose.pdf/matrix/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Matrix

```
public final class Matrix extends Object
```

Sınıf, dönüşüm matrisini temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Matrix](#Matrix--) | <p> Yapıcı, standart 1'e 1 matris oluşturur: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre> |
| [Matrix](#Matrix-double:A-) | <p> Yapıcı, aşağıdaki dizi temsiline sahip bir matrisi kabul eder: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre> |
| [Matrix](#Matrix-double-double-double-double-double-double-) | <p> Belirtilen katsayılarla dönüşüm matrisini başlatır. </p> <hr> <pre> Matrix m = new Matrix(1, 0, 0, 1, 3, 3); </pre> |
| [Matrix](#Matrix-float:A-) | <p> Yapıcı, aşağıdaki dizi temsiline sahip bir matrisi kabul eder: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre> |
| [Matrix](#Matrix-com.aspose.pdf.Matrix-) | <p> Yapıcı, standart 1'e 1 matris oluşturur: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre> |
| [Matrix](#Matrix-com.aspose.ms.System.Drawing.Drawing2D.Matrix-) | <p> Yapıcı, standart 1'e 1 matris oluşturur: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre> |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add](#add-com.aspose.pdf.Matrix-) | Matrisi başka bir matrise ekler. |
| [equals](#equals-java.lang.Object-) | Matrisi başka bir nesneyle karşılaştırır. |
| [getA](#getA--) | Dönüşüm matrisinin A üyesini al. |
| [getAngle](#getAngle-com.aspose.pdf.Rotation-) | <p> Rotasyonu açıya (derece) çevirir </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre> |
| [getB](#getB--) | Dönüşüm matrisinin B üyesini al. |
| [getC](#getC--) | Dönüşüm matrisinin C üyesini al. |
| [getD](#getD--) | Dönüşüm matrisinin D üyesini al. |
| [getData](#getData--) | Matrix'in verilerini dizi olarak alır. |
| [getE](#getE--) | Dönüşüm matrisinin E üyesini al. |
| [getElements](#getElements--) | Matrisin elemanları. |
| [getF](#getF--) | Dönüşüm matrisinin F üyesini al. |
| [getFlipMatrix](#getFlipMatrix--) | Flipleme matrisini al. |
| [getMatrix](#getMatrix-com.aspose.pdf.engine.data.ITrailerable-) | Matrisi PDF dizi nesnesine çevirir. |
| [hashCode](#hashCode--) | Nesne için hash kodu. |
| [isIdentity](#isIdentity--) | Bu matrisin birim matris olup olmadığını kontrol eder. |
| [isInt16](#isInt16-double-) | Yalnızca dahili kullanım için |
| [isInt16Values](#isInt16Values--) | Yalnızca dahili kullanım için |
| [multiply](#multiply-com.aspose.pdf.Matrix-) | <p> Matrisi başka bir matrisle çarpar. </p> <hr> <pre> Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 }); Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } ); Matrix c= a.multiply(b); </pre> |
| [reverse](#reverse--) | <p> Ters matrisi hesaplar. </p> <hr> <pre> Matrix m = Matrix.rotation(Math.PI / 2); Matrix m1 = m.reverse(); </pre> |
| [rotation](#rotation-double-) | <p> Verilen dönüş açısı için matris oluşturur. </p> <hr> <pre> Matrix m = Matrix.Rotation(Math.PI / 2); </pre> |
| [rotation](#rotation-com.aspose.pdf.Rotation-) | Verilen dönüş için matris oluşturur. |
| [scale](#scale-double-double-) | <p> Verilen ölçek için matris oluşturur. </p> <hr> <pre> Matrix m = Matrix.scale(x, y); </pre> |
| [scale](#scale-double-double-double:A-double:A-) | Matris ile x ve y'yi aşağıdaki formülü kullanarak ölçeklendirir: x1 = A*x + C*y; y1 = B*x + D*y; |
| [scale](#scale-double-double-com.aspose.pdf.Matrix-) | Verilen matrise ölçekleme uygular. |
| [setA](#setA-double-) | Dönüşüm matrisinin A üyesini ayarla. |
| [setB](#setB-double-) | Dönüşüm matrisinin B üyesini ayarla. |
| [setC](#setC-double-) | Dönüşüm matrisinin C üyesini ayarla. |
| [setD](#setD-double-) | Dönüşüm matrisinin D üyesini ayarla. |
| [setE](#setE-double-) | Dönüşüm matrisinin E üyesini ayarla. |
| [setF](#setF-double-) | Dönüşüm matrisinin F üyesini ayarla. |
| [skew](#skew-double-double-) | Verilen dönüş açısı için matris oluşturur. Matrix m = Matrix.skew(Math.PI / 2, Math.PI / 2); |
| [toString](#toString--) | Matrisin metin temsilini döndürür. |
| [transform](#transform-double-double-double:A-double:A-) | Bu matrisi kullanarak koordinatları dönüştürür. Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); double x, y, x1, y1; m.transform(double x, double y, out double x1, out double y1); |
| [transform](#transform-com.aspose.pdf.Point-) | Bu matrisi kullanarak noktayı dönüştürür. Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); Point p = new Point(5, 5); Point p1 = m.transform(p); |
| [transform](#transform-com.aspose.pdf.Rectangle-) | Dikdörtgeni dönüştürür. |
| [translate](#translate-double-double-com.aspose.pdf.Matrix-) | Bir matrisi x ve y yönlerinde belirtilen miktarda kaydırır. |
| [unScale](#unScale-double-double-double:A-double:A-) | x1 ve y1'i ölçeklendirir ve aşağıdaki formülü kullanarak matris dönüşümünden önceki x ve y'yi döndürür: x = (D * x1 - C * y1) / (A * D - C * B); y = (A * y1 - B * x1) / (A * D - C * B); |
| [unTransform](#unTransform-double-double-double:A-double:A-) | x1 ve y1'i geri dönüştürür ve aşağıdaki formülü kullanarak matris dönüşümünden önceki x ve y'yi döndürür: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B). |

### Matrix {#Matrix--}
```
public Matrix()
```

<p> Yapıcı, standart 1'e 1 matris oluşturur: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre>

### Matrix {#Matrix-double:A-}
```
public Matrix(double[] matrixArray)
```

<p> Yapıcı, aşağıdaki dizi temsiline sahip bir matrisi kabul eder: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre>

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| matrixArray |  | Matris veri dizisi. |

### Matrix {#Matrix-double-double-double-double-double-double-}
```
public Matrix(double a, double b, double c, double d, double e, double f)
```

<p> Belirtilen katsayılarla dönüşüm matrisini başlatır. </p> <hr> <pre> Matrix m = new Matrix(1, 0, 0, 1, 3, 3); </pre>

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| a |  | Bir matris değeri. |
| b |  | B matris değeri. |
| c |  | C matris değeri. |
| d |  | D matris değeri. |
| e |  | E matris değeri. |
| f |  | F matris değeri. |

### Matrix {#Matrix-float:A-}
```
public Matrix(float[] matrixArray)
```

<p> Yapıcı, aşağıdaki dizi temsiline sahip bir matrisi kabul eder: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre>

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| matrixArray |  | Matris veri dizisi. |

### Matrix {#Matrix-com.aspose.pdf.Matrix-}
<p> Yapıcı, standart 1'e 1 matris oluşturur: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre>

### Matrix {#Matrix-com.aspose.ms.System.Drawing.Drawing2D.Matrix-}
<p> Yapıcı, standart 1'e 1 matris oluşturur: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre>

### add {#add-com.aspose.pdf.Matrix-}
Matrisi başka bir matrise ekler.

### equals {#equals-java.lang.Object-}
Matrisi başka bir nesneyle karşılaştırır.

### getA {#getA--}
```
public double getA()
```

Dönüşüm matrisinin A üyesini al.

**Returns:**
double değer

### getAngle {#getAngle-com.aspose.pdf.Rotation-}
<p> Rotasyonu açıya (derece) çevirir </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre>

### getB {#getB--}
```
public double getB()
```

Dönüşüm matrisinin B üyesini al.

**Returns:**
double değer

### getC {#getC--}
```
public double getC()
```

Dönüşüm matrisinin C üyesini al.

**Returns:**
double değer

### getD {#getD--}
```
public double getD()
```

Dönüşüm matrisinin D üyesini al.

**Returns:**
double değer

### getData {#getData--}
```
public final double[] getData()
```

Matrix'in verilerini dizi olarak alır.

**Returns:**
double değerlerden oluşan dizi

### getE {#getE--}
```
public double getE()
```

Dönüşüm matrisinin E üyesini al.

**Returns:**
double değer

### getElements {#getElements--}
```
public float[] getElements()
```

Matrisin elemanları.

**Returns:**
float[] array

### getF {#getF--}
```
public double getF()
```

Dönüşüm matrisinin F üyesini al.

**Returns:**
double değer

### getFlipMatrix {#getFlipMatrix--}
```
public final Matrix getFlipMatrix()
```

Flipleme matrisini al.

**Returns:**
Matris örneği

### getMatrix {#getMatrix-com.aspose.pdf.engine.data.ITrailerable-}
Matrisi PDF dizi nesnesine çevirir.

### hashCode {#hashCode--}
```
public int hashCode()
```

Nesne için hash kodu.

**Returns:**
Karma kodu.

### isIdentity {#isIdentity--}
```
public final boolean isIdentity()
```

Bu matrisin birim matris olup olmadığını kontrol eder.

**Returns:**
boolean değer

### isInt16 {#isInt16-double-}
```
public static boolean isInt16(double value)
```

Yalnızca dahili kullanım için

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

**Returns:**
boolean değer

### isInt16Values {#isInt16Values--}
```
public boolean isInt16Values()
```

Yalnızca dahili kullanım için

**Returns:**
boolean değer

### multiply {#multiply-com.aspose.pdf.Matrix-}
<p> Matrisi başka bir matrisle çarpar. </p> <hr> <pre> Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 }); Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } ); Matrix c= a.multiply(b); </pre>

### reverse {#reverse--}
```
public Matrix reverse()
```

<p> Ters matrisi hesaplar. </p> <hr> <pre> Matrix m = Matrix.rotation(Math.PI / 2); Matrix m1 = m.reverse(); </pre>

**Returns:**
Matrisi ters çevir.

### rotation {#rotation-double-}
```
public static Matrix rotation(double alpha)
```

<p> Verilen dönüş açısı için matris oluşturur. </p> <hr> <pre> Matrix m = Matrix.Rotation(Math.PI / 2); </pre>

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| alpha |  | Radyan cinsinden dönüş açısı. |

**Returns:**
Dönüşüm matrisi.

### rotation {#rotation-com.aspose.pdf.Rotation-}
Verilen dönüş için matris oluşturur.

### scale {#scale-double-double-}
```
public static Matrix scale(double x, double y)
```

<p> Verilen ölçek için matris oluşturur. </p> <hr> <pre> Matrix m = Matrix.scale(x, y); </pre>

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x |  | x ölçeği. |
| y |  | y ölçeği. |

**Returns:**
Dönüşüm matrisi.

### scale {#scale-double-double-double:A-double:A-}
```
public final void scale(double x, double y, double[] x1, double[] y1)
```

Matris ile x ve y'yi aşağıdaki formülü kullanarak ölçeklendirir: x1 = A*x + C*y; y1 = B*x + D*y;

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x |  | Giriş X koordinatı |
| y |  | Giriş Y koordinatı |
| x1 |  | Çıktı X koordinatı |
| y1 |  | Çıktı Y koordinatı |

### scale {#scale-double-double-com.aspose.pdf.Matrix-}
Verilen matrise ölçekleme uygular.

### setA {#setA-double-}
```
public void setA(double value)
```

Dönüşüm matrisinin A üyesini ayarla.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setB {#setB-double-}
```
public void setB(double value)
```

Dönüşüm matrisinin B üyesini ayarla.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setC {#setC-double-}
```
public void setC(double value)
```

Dönüşüm matrisinin C üyesini ayarla.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setD {#setD-double-}
```
public void setD(double value)
```

Dönüşüm matrisinin D üyesini ayarla.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setE {#setE-double-}
```
public void setE(double value)
```

Dönüşüm matrisinin E üyesini ayarla.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setF {#setF-double-}
```
public void setF(double value)
```

Dönüşüm matrisinin F üyesini ayarla.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### skew {#skew-double-double-}
```
public static Matrix skew(double alpha, double beta)
```

Verilen dönüş açısı için matris oluşturur. Matrix m = Matrix.skew(Math.PI / 2, Math.PI / 2);

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| alpha |  | Radyan cinsinden x eğim açısı. |
| beta |  | Radyan cinsinden y eğim açısı. |

**Returns:**
Dönüşüm matrisi.

### toString {#toString--}
```
public String toString()
```

Matrisin metin temsilini döndürür.

**Returns:**
Matrisin dize temsili

### transform {#transform-double-double-double:A-double:A-}
```
public final void transform(double x, double y, double[] x1, double[] y1)
```

Bu matrisi kullanarak koordinatları dönüştürür. Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); double x, y, x1, y1; m.transform(double x, double y, out double x1, out double y1);

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x |  | X koordinatı. |
| y |  | Y koordinatı. |
| x1 |  | Dönüştürülmüş X koordinatı. |
| y1 |  | Dönüştürülmüş Y koordinatı. |

### transform {#transform-com.aspose.pdf.Point-}
Bu matrisi kullanarak noktayı dönüştürür. Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); Point p = new Point(5, 5); Point p1 = m.transform(p);

### transform {#transform-com.aspose.pdf.Rectangle-}
Dikdörtgeni dönüştürür.

### translate {#translate-double-double-com.aspose.pdf.Matrix-}
Bir matrisi x ve y yönlerinde belirtilen miktarda kaydırır.

### unScale {#unScale-double-double-double:A-double:A-}
```
public final void unScale(double x1, double y1, double[] x, double[] y)
```

x1 ve y1'i ölçeklendirir ve aşağıdaki formülü kullanarak matris dönüşümünden önceki x ve y'yi döndürür: x = (D * x1 - C * y1) / (A * D - C * B); y = (A * y1 - B * x1) / (A * D - C * B);

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x1 |  | Giriş X koordinatı |
| y1 |  | Giriş Y koordinatı |
| x |  | Çıktı X koordinatı |
| y |  | Çıktı Y koordinatı |

### unTransform {#unTransform-double-double-double:A-double:A-}
```
public final void unTransform(double x1, double y1, double[] x, double[] y)
```

x1 ve y1'i geri dönüştürür ve aşağıdaki formülü kullanarak matris dönüşümünden önceki x ve y'yi döndürür: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x1 |  | Giriş X koordinatı |
| y1 |  | Giriş Y koordinatı |
| x |  | Çıktı X koordinatı |
| y |  | Çıktı Y koordinatı |
