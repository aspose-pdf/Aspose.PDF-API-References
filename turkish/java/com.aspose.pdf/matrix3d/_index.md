---
title: "Matrix3D"
linktitle: "Matrix3D"
second_title: "Aspose.PDF for Java API Referansı"
description: "Sınıf, dönüşüm matrisini temsil eder."
type: docs
weight: 2910
url: /tr/java/com.aspose.pdf/matrix3d/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Matrix3D

```
public final class Matrix3D extends Object
```

Sınıf, dönüşüm matrisini temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Matrix3D](#Matrix3D--) | <p> Yapıcı, standart 1'e 1 matris oluşturur: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre> |
| [Matrix3D](#Matrix3D-double:A-) | <p> Yapıcı, aşağıdaki dizi temsiline sahip bir matrisi kabul eder: [ A B C D E F G H I Tx Ty Tz] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20, 1, 0, 0, 17, 40, 13 }; Matrix3D m = new Matrix3D(c); </pre> |
| [Matrix3D](#Matrix3D-double-double-double-double-double-double-double-double-double-double-double-double-) | <p> Belirtilen katsayılarla dönüşüm matrisini başlatır. </p> <hr> <pre> Matrix m = new Matrix(1, 0, 0, 1, 3, 3); </pre> |
| [Matrix3D](#Matrix3D-com.aspose.pdf.Matrix3D-) | <p> Yapıcı, standart 1'e 1 matris oluşturur: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre> |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add](#add-com.aspose.pdf.Matrix3D-) | <p> Matrisi diğer matrise ekler. </p> <hr> |
| [equals](#equals-java.lang.Object-) | Matrisi diğer nesneye karşı karşılaştırır. |
| [getA](#getA--) | A, dönüşüm matrisinin bir üyesidir. |
| [getAngle](#getAngle-com.aspose.pdf.Rotation-) | <p> Rotasyonu açıya (derece) çevirir </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre> |
| [getB](#getB--) | B, dönüşüm matrisinin bir üyesidir. |
| [getC](#getC--) | C, dönüşüm matrisinin bir üyesidir. |
| [getD](#getD--) | D, dönüşüm matrisinin bir üyesidir. |
| [getE](#getE--) | E, dönüşüm matrisinin bir üyesidir. |
| [getF](#getF--) | F, dönüşüm matrisinin bir üyesidir. |
| [getG](#getG--) | G, dönüşüm matrisinin bir üyesidir. |
| [getH](#getH--) | H, dönüşüm matrisinin bir üyesidir. |
| [getI](#getI--) | I, dönüşüm matrisinin bir üyesidir. |
| [getTx](#getTx--) | Tx, dönüşüm matrisinin bir üyesidir. |
| [getTy](#getTy--) | Ty, dönüşüm matrisinin bir üyesidir. |
| [getTz](#getTz--) | Tz, dönüşüm matrisinin bir üyesidir. |
| [hashCode](#hashCode--) | <p> Nesne için hash kodu. </p> <hr> |
| [setA](#setA-double-) | A, dönüşüm matrisinin bir üyesidir. |
| [setB](#setB-double-) | B, dönüşüm matrisinin bir üyesidir. |
| [setC](#setC-double-) | C, dönüşüm matrisinin bir üyesidir. |
| [setD](#setD-double-) | D, dönüşüm matrisinin bir üyesidir. |
| [setE](#setE-double-) | E, dönüşüm matrisinin bir üyesidir. |
| [setF](#setF-double-) | F, dönüşüm matrisinin bir üyesidir. |
| [setG](#setG-double-) | G, dönüşüm matrisinin bir üyesidir. |
| [setH](#setH-double-) | H, dönüşüm matrisinin bir üyesidir. |
| [setI](#setI-double-) | I, dönüşüm matrisinin bir üyesidir. |
| [setTx](#setTx-double-) | Tx, dönüşüm matrisinin bir üyesidir. |
| [setTy](#setTy-double-) | Ty, dönüşüm matrisinin bir üyesidir. |
| [setTz](#setTz-double-) | Tz, dönüşüm matrisinin bir üyesidir. |
| [toString](#toString--) | Matrisin metin temsilini döndürür. |

### Matrix3D {#Matrix3D--}
```
public Matrix3D()
```

<p> Yapıcı, standart 1'e 1 matris oluşturur: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre>

### Matrix3D {#Matrix3D-double:A-}
```
public Matrix3D(double[] matrix3DArray)
```

<p> Yapıcı, aşağıdaki dizi temsiline sahip bir matrisi kabul eder: [ A B C D E F G H I Tx Ty Tz] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20, 1, 0, 0, 17, 40, 13 }; Matrix3D m = new Matrix3D(c); </pre>

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| matrix3DArray |  | Matris veri dizisi. |

### Matrix3D {#Matrix3D-double-double-double-double-double-double-double-double-double-double-double-double-}
```
public Matrix3D(double a, double b, double c, double d, double e, double f, double g, double h, double i, double tx, double ty, double tz)
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
| g |  | G matris değeri. |
| h |  | H matris değeri. |
| i |  | I matris değeri. |
| tx |  | TX matris değeri. |
| ty |  | TX matris değeri. |
| tz |  | TY matris değeri. |

### Matrix3D {#Matrix3D-com.aspose.pdf.Matrix3D-}
<p> Yapıcı, standart 1'e 1 matris oluşturur: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre>

### add {#add-com.aspose.pdf.Matrix3D-}
<p> Matrisi diğer matrise ekler. </p> <hr>

### equals {#equals-java.lang.Object-}
Matrisi diğer nesneye karşı karşılaştırır.

### getA {#getA--}
```
public double getA()
```

A, dönüşüm matrisinin bir üyesidir.

**Returns:**
double değer

### getAngle {#getAngle-com.aspose.pdf.Rotation-}
<p> Rotasyonu açıya (derece) çevirir </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre>

### getB {#getB--}
```
public double getB()
```

B, dönüşüm matrisinin bir üyesidir.

**Returns:**
double değer

### getC {#getC--}
```
public double getC()
```

C, dönüşüm matrisinin bir üyesidir.

**Returns:**
double değer

### getD {#getD--}
```
public double getD()
```

D, dönüşüm matrisinin bir üyesidir.

**Returns:**
double değer

### getE {#getE--}
```
public double getE()
```

E, dönüşüm matrisinin bir üyesidir.

**Returns:**
double değer

### getF {#getF--}
```
public double getF()
```

F, dönüşüm matrisinin bir üyesidir.

**Returns:**
double değer

### getG {#getG--}
```
public double getG()
```

G, dönüşüm matrisinin bir üyesidir.

**Returns:**
double değer

### getH {#getH--}
```
public double getH()
```

H, dönüşüm matrisinin bir üyesidir.

**Returns:**
double değer

### getI {#getI--}
```
public double getI()
```

I, dönüşüm matrisinin bir üyesidir.

**Returns:**
double değer

### getTx {#getTx--}
```
public double getTx()
```

Tx, dönüşüm matrisinin bir üyesidir.

**Returns:**
double değer

### getTy {#getTy--}
```
public double getTy()
```

Ty, dönüşüm matrisinin bir üyesidir.

**Returns:**
double değer

### getTz {#getTz--}
```
public double getTz()
```

Tz, dönüşüm matrisinin bir üyesidir.

**Returns:**
double değer

### hashCode {#hashCode--}
```
public int hashCode()
```

<p> Nesne için hash kodu. </p> <hr>

**Returns:**
Karma kodu.

### setA {#setA-double-}
```
public void setA(double value)
```

A, dönüşüm matrisinin bir üyesidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setB {#setB-double-}
```
public void setB(double value)
```

B, dönüşüm matrisinin bir üyesidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setC {#setC-double-}
```
public void setC(double value)
```

C, dönüşüm matrisinin bir üyesidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setD {#setD-double-}
```
public void setD(double value)
```

D, dönüşüm matrisinin bir üyesidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setE {#setE-double-}
```
public void setE(double value)
```

E, dönüşüm matrisinin bir üyesidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setF {#setF-double-}
```
public void setF(double value)
```

F, dönüşüm matrisinin bir üyesidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setG {#setG-double-}
```
public void setG(double value)
```

G, dönüşüm matrisinin bir üyesidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setH {#setH-double-}
```
public void setH(double value)
```

H, dönüşüm matrisinin bir üyesidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setI {#setI-double-}
```
public void setI(double value)
```

I, dönüşüm matrisinin bir üyesidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setTx {#setTx-double-}
```
public void setTx(double value)
```

Tx, dönüşüm matrisinin bir üyesidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setTy {#setTy-double-}
```
public void setTy(double value)
```

Ty, dönüşüm matrisinin bir üyesidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setTz {#setTz-double-}
```
public void setTz(double value)
```

Tz, dönüşüm matrisinin bir üyesidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### toString {#toString--}
```
public String toString()
```

Matrisin metin temsilini döndürür.

**Returns:**
Matrisin dize temsili
