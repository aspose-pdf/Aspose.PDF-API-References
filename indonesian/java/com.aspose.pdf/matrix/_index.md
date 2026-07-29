---
title: "Matriks"
linktitle: "Matriks"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas mewakili matriks transformasi."
type: docs
weight: 2900
url: /id/java/com.aspose.pdf/matrix/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Matrix

```
public final class Matrix extends Object
```

Kelas mewakili matriks transformasi.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Matrix](#Matrix--) | <p> Konstruktor membuat matriks standar 1 ke 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre> |
| [Matrix](#Matrix-double:A-) | <p> Konstruktor menerima matriks dengan representasi array berikut: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre> |
| [Matrix](#Matrix-double-double-double-double-double-double-) | <p> Menginisialisasi matriks transformasi dengan koefisien yang ditentukan. </p> <hr> <pre> Matrix m = new Matrix(1, 0, 0, 1, 3, 3); </pre> |
| [Matrix](#Matrix-float:A-) | <p> Konstruktor menerima matriks dengan representasi array berikut: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre> |
| [Matrix](#Matrix-com.aspose.pdf.Matrix-) | <p> Konstruktor membuat matriks standar 1 ke 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre> |
| [Matrix](#Matrix-com.aspose.ms.System.Drawing.Drawing2D.Matrix-) | <p> Konstruktor membuat matriks standar 1 ke 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre> |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [add](#add-com.aspose.pdf.Matrix-) | Menambahkan matriks ke matriks lain. |
| [equals](#equals-java.lang.Object-) | Membandingkan matriks dengan objek lain. |
| [getA](#getA--) | Dapatkan anggota A dari matriks transformasi. |
| [getAngle](#getAngle-com.aspose.pdf.Rotation-) | <p> Menerjemahkan rotasi menjadi sudut (derajat) </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre> |
| [getB](#getB--) | Dapatkan anggota B dari matriks transformasi. |
| [getC](#getC--) | Dapatkan anggota C dari matriks transformasi. |
| [getD](#getD--) | Dapatkan anggota D dari matriks transformasi. |
| [getData](#getData--) | Mendapatkan data Matrix sebagai array. |
| [getE](#getE--) | Dapatkan anggota E dari matriks transformasi. |
| [getElements](#getElements--) | Elemen-elemen matriks. |
| [getF](#getF--) | Dapatkan anggota F dari matriks transformasi. |
| [getFlipMatrix](#getFlipMatrix--) | Mendapatkan matriks pembalik. |
| [getMatrix](#getMatrix-com.aspose.pdf.engine.data.ITrailerable-) | Menerjemahkan matriks menjadi objek array PDF. |
| [hashCode](#hashCode--) | Kode hash untuk objek. |
| [isIdentity](#isIdentity--) | Memeriksa apakah matriks ini adalah identitas. |
| [isInt16](#isInt16-double-) | Hanya untuk penggunaan internal |
| [isInt16Values](#isInt16Values--) | Hanya untuk penggunaan internal |
| [multiply](#multiply-com.aspose.pdf.Matrix-) | <p> Mengalikan matriks dengan matriks lain. </p> <hr> <pre> Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 }); Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } ); Matrix c= a.multiply(b); </pre> |
| [reverse](#reverse--) | <p> Menghitung matriks terbalik. </p> <hr> <pre> Matrix m = Matrix.rotation(Math.PI / 2); Matrix m1 = m.reverse(); </pre> |
| [rotation](#rotation-double-) | <p> Membuat matriks untuk sudut rotasi yang diberikan. </p> <hr> <pre> Matrix m = Matrix.Rotation(Math.PI / 2); </pre> |
| [rotation](#rotation-com.aspose.pdf.Rotation-) | Membuat matriks untuk rotasi yang diberikan. |
| [scale](#scale-double-double-) | <p> Membuat matriks untuk skala yang diberikan. </p> <hr> <pre> Matrix m = Matrix.scale(x, y); </pre> |
| [scale](#scale-double-double-double:A-double:A-) | Menskalakan x dan y dengan matriks menggunakan rumus berikut: x1 = A*x + C*y; y1 = B*x + D*y; |
| [scale](#scale-double-double-com.aspose.pdf.Matrix-) | Menerapkan skala pada matriks yang diberikan. |
| [setA](#setA-double-) | Setel anggota A dari matriks transformasi. |
| [setB](#setB-double-) | Setel anggota B dari matriks transformasi. |
| [setC](#setC-double-) | Setel anggota C dari matriks transformasi. |
| [setD](#setD-double-) | Setel anggota D dari matriks transformasi. |
| [setE](#setE-double-) | Setel anggota E dari matriks transformasi. |
| [setF](#setF-double-) | Setel anggota F dari matriks transformasi. |
| [skew](#skew-double-double-) | Membuat matriks untuk sudut rotasi yang diberikan. Matrix m = Matrix.skew(Math.PI / 2, Math.PI / 2); |
| [toString](#toString--) | Mengembalikan representasi teks dari matriks. |
| [transform](#transform-double-double-double:A-double:A-) | Mengubah koordinat menggunakan matriks ini. Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); double x, y, x1, y1; m.transform(double x, double y, out double x1, out double y1); |
| [transform](#transform-com.aspose.pdf.Point-) | Mengubah titik menggunakan matriks ini. Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); Point p = new Point(5, 5); Point p1 = m.transform(p); |
| [transform](#transform-com.aspose.pdf.Rectangle-) | Mengubah persegi panjang. |
| [translate](#translate-double-double-com.aspose.pdf.Matrix-) | Menerjemahkan matriks dengan jumlah yang ditentukan pada arah x dan y. |
| [unScale](#unScale-double-double-double:A-double:A-) | Skala kembali x1 dan y1 dan mengembalikan x dan y sebelum transformasi matriks menggunakan rumus berikut: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B); |
| [unTransform](#unTransform-double-double-double:A-double:A-) | Mengubah kembali x1 dan y1 dan mengembalikan x dan y sebelum transformasi matriks menggunakan rumus berikut: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B). |

### Matrix {#Matrix--}
```
public Matrix()
```

<p> Konstruktor membuat matriks standar 1 ke 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre>

### Matrix {#Matrix-double:A-}
```
public Matrix(double[] matrixArray)
```

<p> Konstruktor menerima matriks dengan representasi array berikut: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre>

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| matrixArray |  | Array data matriks. |

### Matrix {#Matrix-double-double-double-double-double-double-}
```
public Matrix(double a, double b, double c, double d, double e, double f)
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

### Matrix {#Matrix-float:A-}
```
public Matrix(float[] matrixArray)
```

<p> Konstruktor menerima matriks dengan representasi array berikut: [ A B C D E F ] </p> <hr> <pre> double[] c = new double[] { 1, 0, 0, 1, 10, 20 }; Matrix m = new Matrix(c); </pre>

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| matrixArray |  | Array data matriks. |

### Matrix {#Matrix-com.aspose.pdf.Matrix-}
<p> Konstruktor membuat matriks standar 1 ke 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre>

### Matrix {#Matrix-com.aspose.ms.System.Drawing.Drawing2D.Matrix-}
<p> Konstruktor membuat matriks standar 1 ke 1: [ A B C D E F ] = [ 1, 0, 0, 1, 0, 0] </p> <hr> <pre> Matrix m = new Matrix(); </pre>

### add {#add-com.aspose.pdf.Matrix-}
Menambahkan matriks ke matriks lain.

### equals {#equals-java.lang.Object-}
Membandingkan matriks dengan objek lain.

### getA {#getA--}
```
public double getA()
```

Dapatkan anggota A dari matriks transformasi.

**Returns:**
nilai double

### getAngle {#getAngle-com.aspose.pdf.Rotation-}
<p> Menerjemahkan rotasi menjadi sudut (derajat) </p> <hr> <pre> double angle = Matrix.getAngle(Rotation.on90); Matrix m = Matrix.rotation(angle); </pre>

### getB {#getB--}
```
public double getB()
```

Dapatkan anggota B dari matriks transformasi.

**Returns:**
nilai double

### getC {#getC--}
```
public double getC()
```

Dapatkan anggota C dari matriks transformasi.

**Returns:**
nilai double

### getD {#getD--}
```
public double getD()
```

Dapatkan anggota D dari matriks transformasi.

**Returns:**
nilai double

### getData {#getData--}
```
public final double[] getData()
```

Mendapatkan data Matrix sebagai array.

**Returns:**
array nilai double

### getE {#getE--}
```
public double getE()
```

Dapatkan anggota E dari matriks transformasi.

**Returns:**
nilai double

### getElements {#getElements--}
```
public float[] getElements()
```

Elemen-elemen matriks.

**Returns:**
float[] array

### getF {#getF--}
```
public double getF()
```

Dapatkan anggota F dari matriks transformasi.

**Returns:**
nilai double

### getFlipMatrix {#getFlipMatrix--}
```
public final Matrix getFlipMatrix()
```

Mendapatkan matriks pembalik.

**Returns:**
Instansi matriks

### getMatrix {#getMatrix-com.aspose.pdf.engine.data.ITrailerable-}
Menerjemahkan matriks menjadi objek array PDF.

### hashCode {#hashCode--}
```
public int hashCode()
```

Kode hash untuk objek.

**Returns:**
Kode hash.

### isIdentity {#isIdentity--}
```
public final boolean isIdentity()
```

Memeriksa apakah matriks ini adalah identitas.

**Returns:**
nilai boolean

### isInt16 {#isInt16-double-}
```
public static boolean isInt16(double value)
```

Hanya untuk penggunaan internal

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

**Returns:**
nilai boolean

### isInt16Values {#isInt16Values--}
```
public boolean isInt16Values()
```

Hanya untuk penggunaan internal

**Returns:**
nilai boolean

### multiply {#multiply-com.aspose.pdf.Matrix-}
<p> Mengalikan matriks dengan matriks lain. </p> <hr> <pre> Matrix a = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 }); Matrix b = new Matrix(new double[] { 0, -1, 1, 0, 0, 0 } ); Matrix c= a.multiply(b); </pre>

### reverse {#reverse--}
```
public Matrix reverse()
```

<p> Menghitung matriks terbalik. </p> <hr> <pre> Matrix m = Matrix.rotation(Math.PI / 2); Matrix m1 = m.reverse(); </pre>

**Returns:**
Matriks terbalik.

### rotation {#rotation-double-}
```
public static Matrix rotation(double alpha)
```

<p> Membuat matriks untuk sudut rotasi yang diberikan. </p> <hr> <pre> Matrix m = Matrix.Rotation(Math.PI / 2); </pre>

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| alpha |  | Sudut rotasi dalam radian. |

**Returns:**
Matriks transformasi.

### rotation {#rotation-com.aspose.pdf.Rotation-}
Membuat matriks untuk rotasi yang diberikan.

### scale {#scale-double-double-}
```
public static Matrix scale(double x, double y)
```

<p> Membuat matriks untuk skala yang diberikan. </p> <hr> <pre> Matrix m = Matrix.scale(x, y); </pre>

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x |  | Skala x. |
| y |  | Skala y. |

**Returns:**
Matriks transformasi.

### scale {#scale-double-double-double:A-double:A-}
```
public final void scale(double x, double y, double[] x1, double[] y1)
```

Menskalakan x dan y dengan matriks menggunakan rumus berikut: x1 = A*x + C*y; y1 = B*x + D*y;

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x |  | Koordinat X input |
| y |  | Koordinat Y input |
| x1 |  | Koordinat X output |
| y1 |  | Koordinat Y output |

### scale {#scale-double-double-com.aspose.pdf.Matrix-}
Menerapkan skala pada matriks yang diberikan.

### setA {#setA-double-}
```
public void setA(double value)
```

Setel anggota A dari matriks transformasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setB {#setB-double-}
```
public void setB(double value)
```

Setel anggota B dari matriks transformasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setC {#setC-double-}
```
public void setC(double value)
```

Setel anggota C dari matriks transformasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setD {#setD-double-}
```
public void setD(double value)
```

Setel anggota D dari matriks transformasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setE {#setE-double-}
```
public void setE(double value)
```

Setel anggota E dari matriks transformasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setF {#setF-double-}
```
public void setF(double value)
```

Setel anggota F dari matriks transformasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### skew {#skew-double-double-}
```
public static Matrix skew(double alpha, double beta)
```

Membuat matriks untuk sudut rotasi yang diberikan. Matrix m = Matrix.skew(Math.PI / 2, Math.PI / 2);

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| alpha |  | Sudut skew x dalam radian. |
| beta |  | Sudut skew y dalam radian. |

**Returns:**
Matriks transformasi.

### toString {#toString--}
```
public String toString()
```

Mengembalikan representasi teks dari matriks.

**Returns:**
Representasi string untuk matriks

### transform {#transform-double-double-double:A-double:A-}
```
public final void transform(double x, double y, double[] x1, double[] y1)
```

Mengubah koordinat menggunakan matriks ini. Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); double x, y, x1, y1; m.transform(double x, double y, out double x1, out double y1);

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x |  | Koordinat X. |
| y |  | Koordinat Y. |
| x1 |  | Koordinat X yang ditransformasi. |
| y1 |  | Koordinat Y yang ditransformasi. |

### transform {#transform-com.aspose.pdf.Point-}
Mengubah titik menggunakan matriks ini. Matrix m = new Matrix(new double[] { 1, 0, 0, 1, 10, 20 } ); Point p = new Point(5, 5); Point p1 = m.transform(p);

### transform {#transform-com.aspose.pdf.Rectangle-}
Mengubah persegi panjang.

### translate {#translate-double-double-com.aspose.pdf.Matrix-}
Menerjemahkan matriks dengan jumlah yang ditentukan pada arah x dan y.

### unScale {#unScale-double-double-double:A-double:A-}
```
public final void unScale(double x1, double y1, double[] x, double[] y)
```

Skala kembali x1 dan y1 dan mengembalikan x dan y sebelum transformasi matriks menggunakan rumus berikut: x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B);

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x1 |  | Koordinat X input |
| y1 |  | Koordinat Y input |
| x |  | Koordinat X output |
| y |  | Koordinat Y output |

### unTransform {#unTransform-double-double-double:A-double:A-}
```
public final void unTransform(double x1, double y1, double[] x, double[] y)
```

Mengubah kembali x1 dan y1 dan mengembalikan x dan y sebelum transformasi matriks menggunakan rumus berikut: x = (D * x1 - C * y1 + C * F) / (A * D - C * B) y = (A * y1 - B * x1 + B * E) / (A * D - C * B).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x1 |  | Koordinat X input |
| y1 |  | Koordinat Y input |
| x |  | Koordinat X output |
| y |  | Koordinat Y output |
