---
title: "Matrix3D"
linktitle: "Matrix3D"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas mewakili matriks transformasi."
type: docs
weight: 2910
url: /id/java/com.aspose.pdf/matrix3d/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Matrix3D

```
public final class Matrix3D extends Object
```

Kelas mewakili matriks transformasi.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Matrix3D](#Matrix3D--) | <p> Konstruktor membuat matriks standar 1 ke 1: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre> |
| [Matrix3D](#Matrix3D-double:A-) | <p> Konstruktor menerima matriks dengan representasi array berikut: [ A B C D E F G H I Tx Ty Tz] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20, 1, 0, 0, 17, 40, 13 }; Matrix3D m = new Matrix3D(c); </pre> |
| [Matrix3D](#Matrix3D-double-double-double-double-double-double-double-double-double-double-double-double-) | <p> Menginisialisasi matriks transformasi dengan koefisien yang ditentukan. </p> <hr> <pre> Matrix m = new Matrix(1, 0, 0, 1, 3, 3); </pre> |
| [Matrix3D](#Matrix3D-com.aspose.pdf.Matrix3D-) | <p> Konstruktor membuat matriks standar 1 ke 1: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre> |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [add](#add-com.aspose.pdf.Matrix3D-) | <p> Menambahkan matriks ke matriks lain. </p> <hr> |
| [equals](#equals-java.lang.Object-) | Membandingkan matriks dengan objek lain. |
| [getA](#getA--) | Anggota A dari matriks transformasi. |
| [getAngle](#getAngle-com.aspose.pdf.Rotation-) | <p> Menerjemahkan rotasi menjadi sudut (derajat) </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre> |
| [getB](#getB--) | Anggota B dari matriks transformasi. |
| [getC](#getC--) | Anggota C dari matriks transformasi. |
| [getD](#getD--) | Anggota D dari matriks transformasi. |
| [getE](#getE--) | Anggota E dari matriks transformasi. |
| [getF](#getF--) | Anggota F dari matriks transformasi. |
| [getG](#getG--) | Anggota G dari matriks transformasi. |
| [getH](#getH--) | Anggota H dari matriks transformasi. |
| [getI](#getI--) | Anggota I dari matriks transformasi. |
| [getTx](#getTx--) | Anggota Tx dari matriks transformasi. |
| [getTy](#getTy--) | Anggota Ty dari matriks transformasi. |
| [getTz](#getTz--) | Anggota Tz dari matriks transformasi. |
| [hashCode](#hashCode--) | <p> Hash-code untuk objek. </p> <hr> |
| [setA](#setA-double-) | Anggota A dari matriks transformasi. |
| [setB](#setB-double-) | Anggota B dari matriks transformasi. |
| [setC](#setC-double-) | Anggota C dari matriks transformasi. |
| [setD](#setD-double-) | Anggota D dari matriks transformasi. |
| [setE](#setE-double-) | Anggota E dari matriks transformasi. |
| [setF](#setF-double-) | Anggota F dari matriks transformasi. |
| [setG](#setG-double-) | Anggota G dari matriks transformasi. |
| [setH](#setH-double-) | Anggota H dari matriks transformasi. |
| [setI](#setI-double-) | Anggota I dari matriks transformasi. |
| [setTx](#setTx-double-) | Anggota Tx dari matriks transformasi. |
| [setTy](#setTy-double-) | Anggota Ty dari matriks transformasi. |
| [setTz](#setTz-double-) | Anggota Tz dari matriks transformasi. |
| [toString](#toString--) | Mengembalikan representasi teks dari matriks. |

### Matrix3D {#Matrix3D--}
```
public Matrix3D()
```

<p> Konstruktor membuat matriks standar 1 ke 1: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre>

### Matrix3D {#Matrix3D-double:A-}
```
public Matrix3D(double[] matrix3DArray)
```

<p> Konstruktor menerima matriks dengan representasi array berikut: [ A B C D E F G H I Tx Ty Tz] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20, 1, 0, 0, 17, 40, 13 }; Matrix3D m = new Matrix3D(c); </pre>

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| matrix3DArray |  | Array data matriks. |

### Matrix3D {#Matrix3D-double-double-double-double-double-double-double-double-double-double-double-double-}
```
public Matrix3D(double a, double b, double c, double d, double e, double f, double g, double h, double i, double tx, double ty, double tz)
```

<p> Menginisialisasi matriks transformasi dengan koefisien yang ditentukan. </p> <hr> <pre> Matrix m = new Matrix(1, 0, 0, 1, 3, 3); </pre>

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| a |  | Nilai matriks A. |
| b |  | Nilai matriks B. |
| c |  | Nilai matriks C. |
| d |  | Nilai matriks D. |
| e |  | Nilai matriks E. |
| f |  | Nilai matriks F. |
| g |  | nilai matriks G. |
| h |  | nilai matriks H. |
| i |  | nilai matriks I. |
| tx |  | nilai matriks TX. |
| ty |  | nilai matriks TX. |
| tz |  | nilai matriks TY. |

### Matrix3D {#Matrix3D-com.aspose.pdf.Matrix3D-}
<p> Konstruktor membuat matriks standar 1 ke 1: [ A B C D E F G H I Tx Ty Tz] = [ 1, 0, 0, 0, 1, 0, 0, 0, 1, 0, 0 , 0] </p> <hr> <pre> Matrix3D m = new Matrix3D(); </pre>

### add {#add-com.aspose.pdf.Matrix3D-}
<p> Menambahkan matriks ke matriks lain. </p> <hr>

### equals {#equals-java.lang.Object-}
Membandingkan matriks dengan objek lain.

### getA {#getA--}
```
public double getA()
```

Anggota A dari matriks transformasi.

**Returns:**
nilai double

### getAngle {#getAngle-com.aspose.pdf.Rotation-}
<p> Menerjemahkan rotasi menjadi sudut (derajat) </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre>

### getB {#getB--}
```
public double getB()
```

Anggota B dari matriks transformasi.

**Returns:**
nilai double

### getC {#getC--}
```
public double getC()
```

Anggota C dari matriks transformasi.

**Returns:**
nilai double

### getD {#getD--}
```
public double getD()
```

Anggota D dari matriks transformasi.

**Returns:**
nilai double

### getE {#getE--}
```
public double getE()
```

Anggota E dari matriks transformasi.

**Returns:**
nilai double

### getF {#getF--}
```
public double getF()
```

Anggota F dari matriks transformasi.

**Returns:**
nilai double

### getG {#getG--}
```
public double getG()
```

Anggota G dari matriks transformasi.

**Returns:**
nilai double

### getH {#getH--}
```
public double getH()
```

Anggota H dari matriks transformasi.

**Returns:**
nilai double

### getI {#getI--}
```
public double getI()
```

Anggota I dari matriks transformasi.

**Returns:**
nilai double

### getTx {#getTx--}
```
public double getTx()
```

Anggota Tx dari matriks transformasi.

**Returns:**
nilai double

### getTy {#getTy--}
```
public double getTy()
```

Anggota Ty dari matriks transformasi.

**Returns:**
nilai double

### getTz {#getTz--}
```
public double getTz()
```

Anggota Tz dari matriks transformasi.

**Returns:**
nilai double

### hashCode {#hashCode--}
```
public int hashCode()
```

<p> Hash-code untuk objek. </p> <hr>

**Returns:**
Kode hash.

### setA {#setA-double-}
```
public void setA(double value)
```

Anggota A dari matriks transformasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setB {#setB-double-}
```
public void setB(double value)
```

Anggota B dari matriks transformasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setC {#setC-double-}
```
public void setC(double value)
```

Anggota C dari matriks transformasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setD {#setD-double-}
```
public void setD(double value)
```

Anggota D dari matriks transformasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setE {#setE-double-}
```
public void setE(double value)
```

Anggota E dari matriks transformasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setF {#setF-double-}
```
public void setF(double value)
```

Anggota F dari matriks transformasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setG {#setG-double-}
```
public void setG(double value)
```

Anggota G dari matriks transformasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setH {#setH-double-}
```
public void setH(double value)
```

Anggota H dari matriks transformasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setI {#setI-double-}
```
public void setI(double value)
```

Anggota I dari matriks transformasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setTx {#setTx-double-}
```
public void setTx(double value)
```

Anggota Tx dari matriks transformasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setTy {#setTy-double-}
```
public void setTy(double value)
```

Anggota Ty dari matriks transformasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setTz {#setTz-double-}
```
public void setTz(double value)
```

Anggota Tz dari matriks transformasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### toString {#toString--}
```
public String toString()
```

Mengembalikan representasi teks dari matriks.

**Returns:**
Representasi string untuk matriks
