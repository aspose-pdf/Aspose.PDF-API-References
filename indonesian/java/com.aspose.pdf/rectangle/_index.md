---
title: "Rectangle"
linktitle: "Rectangle"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang merepresentasikan persegi panjang."
type: docs
weight: 4100
url: /id/java/com.aspose.pdf/rectangle/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Rectangle

**All Implemented Interfaces:**
Cloneable, Comparable < Object >

```
public final class Rectangle extends Object implements Comparable < Object >, Cloneable
```

Kelas yang merepresentasikan persegi panjang.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Rectangle](#Rectangle-double-double-double-double-) | Konstruktor Rectangle. |
| [Rectangle](#Rectangle-double-double-double-double-boolean-) | Konstruktor Rectangle. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [_Intersect](#Z:Z_Intersect-com.aspose.pdf.Rectangle-) | Berinteraksi dengan persegi panjang. Metode usang. Silakan gunakan Intersect sebagai gantinya. |
| [center](#center--) | Mengembalikan koordinat pusat persegi panjang. |
| [clone](#clone--) | Mengkloning objek Rectangle. |
| [compareTo](#compareTo-java.lang.Object-) | CompareTo |
| [contains](#contains-com.aspose.pdf.Point-) | Menentukan apakah titik yang diberikan berada di dalam persegi panjang. |
| [contains](#contains-com.aspose.pdf.Point-boolean-) | Menentukan apakah titik yang diberikan berada di dalam persegi panjang. |
| [containsLine](#containsLine-double-double-double-double-) | Menentukan apakah persegi panjang berisi sebuah garis yang direpresentasikan oleh dua titik. |
| [containsPoint](#containsPoint-double-double-) | Menentukan apakah titik yang diberikan berada di dalam persegi panjang. |
| [deepClone](#deepClone--) | Mengkloning objek Rectangle. |
| [equals](#equals-java.lang.Object-) | Periksa apakah persegi panjang sama, yaitu memiliki posisi dan ukuran yang sama. |
| [fromRect](#fromRect-java.awt.Rectangle-) | Menginisialisasi persegi panjang baru dari instance System.Drawing.Rectangle yang diberikan. |
| [fromRect](#fromRect-java.awt.geom.Rectangle2D.Float-) | Menginisialisasi persegi panjang baru dari instance System.Drawing.Rectangle yang diberikan. |
| [fromRectInternal](#fromRectInternal-com.aspose.ms.System.Drawing.RectangleF-) |  |
| [getArea](#getArea--) | Menghitung luas persegi panjang. |
| [getEmpty](#getEmpty--) | Mendapatkan persegi panjang kosong |
| [getHeight](#getHeight--) | Dapatkan tinggi persegi panjang. |
| [getLLX](#getLLX--) | Mendapatkan koordinat X sudut kiri-bawah. |
| [getLLY](#getLLY--) | Mendapatkan koordinat Y sudut kiri-bawah. |
| [getTrivial](#getTrivial--) | Menginisialisasi persegi panjang trivial, yaitu persegi panjang dengan posisi dan ukuran nol. |
| [getURX](#getURX--) | Mendapatkan koordinat X sudut kanan-atas. |
| [getURY](#getURY--) | Mendapatkan koordinat Y sudut kanan-atas. |
| [getWidth](#getWidth--) | Mendapatkan lebar persegi panjang. |
| [hashCode](#hashCode--) | Mengembalikan nilai kode hash untuk objek. Metode ini didukung untuk kepentingan tabel hash seperti yang disediakan oleh {@link java.util.HashMap}. <p> Kontrak umum dari {@code hashCode} adalah: <ul> <li>Setiap kali dipanggil pada objek yang sama lebih dari satu kali selama eksekusi aplikasi Java, metode {@code hashCode} harus secara konsisten mengembalikan integer yang sama, dengan catatan tidak ada informasi yang digunakan dalam perbandingan {@code equals} pada objek yang diubah. Integer ini tidak harus tetap konsisten dari satu eksekusi aplikasi ke eksekusi lain dari aplikasi yang sama. <li>Jika dua objek sama menurut metode {@code equals(Object)}, maka memanggil metode {@code hashCode} pada masing‑masing kedua objek harus menghasilkan hasil integer yang sama. <li>Tidak <em>diwajibkan</em> bahwa jika dua objek tidak sama menurut metode {@link java.lang.Object#equals(java.lang.Object)}, maka memanggil metode {@code hashCode} pada masing‑masing kedua objek harus menghasilkan hasil integer yang berbeda. Namun, programmer harus menyadari bahwa menghasilkan hasil integer yang berbeda untuk objek yang tidak sama dapat meningkatkan kinerja tabel hash. </ul> <p> Sebisa mungkin secara praktis, metode hashCode yang didefinisikan oleh kelas {@code Object} memang mengembalikan integer yang berbeda untuk objek yang berbeda. (Ini biasanya diimplementasikan dengan mengonversi alamat internal objek menjadi sebuah integer, tetapi teknik implementasi ini tidak diwajibkan oleh bahasa pemrograman Java<span style=\"font-size:70%\"><sup>TM</sup></span>.) |
| [intersect](#intersect-com.aspose.pdf.Rectangle-) | Berinteraksi dengan dua persegi panjang. |
| [isEmpty](#isEmpty--) | Memeriksa apakah persegi panjang kosong. |
| [isInclude](#isInclude-com.aspose.pdf.Rectangle-double-) | Memeriksa bahwa persegi panjang ini mencakup seluruh persegi panjang lain. Yaitu seluruh persegi panjang lain berada di dalam persegi panjang ini. Perbedaan dengan metode IsIntersect adalah bahwa IsIntersect akan mengembalikan true untuk persegi panjang yang berpotongan sebagian, tetapi IsInclude akan mengembalikan false. |
| [isIntersect](#isIntersect-com.aspose.pdf.Rectangle-) | Menentukan apakah persegi panjang ini berinteraksi dengan persegi panjang lain. |
| [isPoint](#isPoint--) | Memeriksa apakah persegi panjang adalah titik yaitu LLX sama dengan URX dan LLY sama dengan URY. |
| [isTrivial](#isTrivial--) | Memeriksa apakah persegi panjang bersifat trivial yaitu memiliki ukuran dan posisi nol. |
| [join](#join-com.aspose.pdf.Rectangle-) | Menggabungkan persegi panjang. |
| [moveBy](#moveBy-double-double-) | Menggeser persegi panjang dengan delta yang ditentukan. |
| [nearEquals](#nearEquals-com.aspose.pdf.Rectangle-double-) | Memeriksa apakah persegi panjang hampir sama yaitu memiliki posisi dan ukuran yang hampir sama (hingga delta). |
| [parse](#parse-java.lang.String-) | Mencoba mengurai string dan mengekstrak komponen persegi panjang llx, lly, urx, ury darinya. |
| [rotate](#rotate-com.aspose.pdf.Rotation-) | Memutar persegi panjang dengan sudut yang ditentukan. |
| [rotateAngle](#rotateAngle-int-) | Memutar persegi panjang dengan sudut yang ditentukan. |
| [setLLX](#setLLX-double-) | Mengatur koordinat X sudut kiri bawah. |
| [setLLY](#setLLY-double-) | Mengatur koordinat Y sudut kiri bawah. |
| [setURX](#setURX-double-) | Mengatur koordinat X sudut kanan atas. |
| [setURY](#setURY-double-) | Mengatur koordinat Y sudut kanan atas. |
| [toArray](#toArray-com.aspose.pdf.engine.data.ITrailerable-) |  |
| [toPoints](#toPoints--) | Mengonversi persegi panjang menjadi array titik ("QuadPoints"). |
| [toRect](#toRect--) | Mengonversi persegi panjang menjadi instance System.Drawing.Rectangle. Posisi dan ukuran floating-point dipotong. |
| [toString](#toString--) | Mendapatkan representasi string persegi panjang. |

### Rectangle {#Rectangle-double-double-double-double-}
```
public Rectangle(double llx, double lly, double urx, double ury)
```

Konstruktor Rectangle.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| llx |  | X sudut kiri bawah. |
| lly |  | Y sudut kiri bawah. |
| urx |  | X sudut kanan atas. |
| ury |  | Y sudut kanan atas. |

### Rectangle {#Rectangle-double-double-double-double-boolean-}
```
public Rectangle(double llx, double lly, double urx, double ury, boolean normalizeCoordinates)
```

Konstruktor Rectangle.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| llx |  | X sudut kiri bawah. |
| lly |  | Y sudut kiri bawah. |
| urx |  | X sudut kanan atas. |
| ury |  | Y sudut kanan atas. |
| normalizeCoordinates |  | Normalisasi koordinat persegi panjang. |

### _Intersect {#Z:Z_Intersect-com.aspose.pdf.Rectangle-}
Berinteraksi dengan persegi panjang. Metode usang. Silakan gunakan Intersect sebagai gantinya.

### center {#center--}
```
public Point center()
```

Mengembalikan koordinat pusat persegi panjang.

**Returns:**
Titik yang merupakan pusat persegi panjang.

### clone {#clone--}
```
public Rectangle clone()
```

Mengkloning objek Rectangle.

**Returns:**
Klon objek.

### compareTo {#compareTo-java.lang.Object-}
CompareTo

### contains {#contains-com.aspose.pdf.Point-}
Menentukan apakah titik yang diberikan berada di dalam persegi panjang.

### contains {#contains-com.aspose.pdf.Point-boolean-}
Menentukan apakah titik yang diberikan berada di dalam persegi panjang.

### containsLine {#containsLine-double-double-double-double-}
```
public final boolean containsLine(double x1, double y1, double x2, double y2)
```

Menentukan apakah persegi panjang berisi sebuah garis yang direpresentasikan oleh dua titik.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x1 |  | Koordinat X dari titik awal garis. |
| y1 |  | Koordinat Y dari titik awal garis. |
| x2 |  | Koordinat X dari titik akhir garis. |
| y2 |  | Koordinat Y dari titik akhir garis. |

**Returns:**
{@code true} jika persegi panjang berisi garis; jika tidak, {@code false}.

### containsPoint {#containsPoint-double-double-}
```
public final boolean containsPoint(double x, double y)
```

Menentukan apakah titik yang diberikan berada di dalam persegi panjang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x |  | Koordinat X titik. |
| y |  | Koordinat Y titik. |

**Returns:**
{@code true} jika titik berada di dalam persegi panjang; jika tidak, {@code false}.

### deepClone {#deepClone--}
```
public Rectangle deepClone()
```

Mengkloning objek Rectangle.

**Returns:**
Klon objek.

### equals {#equals-java.lang.Object-}
Periksa apakah persegi panjang sama, yaitu memiliki posisi dan ukuran yang sama.

### fromRect {#fromRect-java.awt.Rectangle-}
Menginisialisasi persegi panjang baru dari instance System.Drawing.Rectangle yang diberikan.

### fromRect {#fromRect-java.awt.geom.Rectangle2D.Float-}
Menginisialisasi persegi panjang baru dari instance System.Drawing.Rectangle yang diberikan.

### fromRectInternal {#fromRectInternal-com.aspose.ms.System.Drawing.RectangleF-}


### getArea {#getArea--}
```
public final double getArea()
```

Menghitung luas persegi panjang.

**Returns:**
Luas persegi panjang sebagai double, dihitung dengan mengalikan lebar dan tinggi.

### getEmpty {#getEmpty--}
```
public static Rectangle getEmpty()
```

Mendapatkan persegi panjang kosong

**Returns:**
objek Rectangle baru

### getHeight {#getHeight--}
```
public double getHeight()
```

Dapatkan tinggi persegi panjang.

**Returns:**
nilai double

### getLLX {#getLLX--}
```
public double getLLX()
```

Mendapatkan koordinat X sudut kiri-bawah.

**Returns:**
nilai double

### getLLY {#getLLY--}
```
public double getLLY()
```

Mendapatkan koordinat Y sudut kiri-bawah.

**Returns:**
nilai double

### getTrivial {#getTrivial--}
```
public static Rectangle getTrivial()
```

Menginisialisasi persegi panjang trivial, yaitu persegi panjang dengan posisi dan ukuran nol.

**Returns:**
objek Rectangle baru

### getURX {#getURX--}
```
public double getURX()
```

Mendapatkan koordinat X sudut kanan-atas.

**Returns:**
nilai double

### getURY {#getURY--}
```
public double getURY()
```

Mendapatkan koordinat Y sudut kanan-atas.

**Returns:**
nilai double

### getWidth {#getWidth--}
```
public double getWidth()
```

Mendapatkan lebar persegi panjang.

**Returns:**
nilai double

### hashCode {#hashCode--}
```
public int hashCode()
```

Mengembalikan nilai kode hash untuk objek. Metode ini didukung untuk kepentingan tabel hash seperti yang disediakan oleh {@link java.util.HashMap}. <p> Kontrak umum dari {@code hashCode} adalah: <ul> <li>Setiap kali dipanggil pada objek yang sama lebih dari satu kali selama eksekusi aplikasi Java, metode {@code hashCode} harus secara konsisten mengembalikan integer yang sama, dengan catatan tidak ada informasi yang digunakan dalam perbandingan {@code equals} pada objek yang diubah. Integer ini tidak harus tetap konsisten dari satu eksekusi aplikasi ke eksekusi lain dari aplikasi yang sama. <li>Jika dua objek sama menurut metode {@code equals(Object)}, maka memanggil metode {@code hashCode} pada masing‑masing kedua objek harus menghasilkan hasil integer yang sama. <li>Tidak <em>diwajibkan</em> bahwa jika dua objek tidak sama menurut metode {@link java.lang.Object#equals(java.lang.Object)}, maka memanggil metode {@code hashCode} pada masing‑masing kedua objek harus menghasilkan hasil integer yang berbeda. Namun, programmer harus menyadari bahwa menghasilkan hasil integer yang berbeda untuk objek yang tidak sama dapat meningkatkan kinerja tabel hash. </ul> <p> Sebisa mungkin secara praktis, metode hashCode yang didefinisikan oleh kelas {@code Object} memang mengembalikan integer yang berbeda untuk objek yang berbeda. (Ini biasanya diimplementasikan dengan mengonversi alamat internal objek menjadi sebuah integer, tetapi teknik implementasi ini tidak diwajibkan oleh bahasa pemrograman Java<span style=\"font-size:70%\"><sup>TM</sup></span>.)

**Returns:**
nilai kode hash untuk objek ini. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode

### intersect {#intersect-com.aspose.pdf.Rectangle-}
Berinteraksi dengan dua persegi panjang.

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

Memeriksa apakah persegi panjang kosong.

**Returns:**
nilai boolean

### isInclude {#isInclude-com.aspose.pdf.Rectangle-double-}
Memeriksa bahwa persegi panjang ini mencakup seluruh persegi panjang lain. Yaitu seluruh persegi panjang lain berada di dalam persegi panjang ini. Perbedaan dengan metode IsIntersect adalah bahwa IsIntersect akan mengembalikan true untuk persegi panjang yang berpotongan sebagian, tetapi IsInclude akan mengembalikan false.

### isIntersect {#isIntersect-com.aspose.pdf.Rectangle-}
Menentukan apakah persegi panjang ini berinteraksi dengan persegi panjang lain.

### isPoint {#isPoint--}
```
public boolean isPoint()
```

Memeriksa apakah persegi panjang adalah titik yaitu LLX sama dengan URX dan LLY sama dengan URY.

**Returns:**
nilai boolean

### isTrivial {#isTrivial--}
```
public boolean isTrivial()
```

Memeriksa apakah persegi panjang bersifat trivial yaitu memiliki ukuran dan posisi nol.

**Returns:**
nilai boolean

### join {#join-com.aspose.pdf.Rectangle-}
Menggabungkan persegi panjang.

### moveBy {#moveBy-double-double-}
```
public final void moveBy(double dx, double dy)
```

Menggeser persegi panjang dengan delta yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dx |  | Nilai pergeseran pada sumbu X. |
| dy |  | Nilai pergeseran pada sumbu Y. |

### nearEquals {#nearEquals-com.aspose.pdf.Rectangle-double-}
Memeriksa apakah persegi panjang hampir sama yaitu memiliki posisi dan ukuran yang hampir sama (hingga delta).

### parse {#parse-java.lang.String-}
Mencoba mengurai string dan mengekstrak komponen persegi panjang llx, lly, urx, ury darinya.

### rotate {#rotate-com.aspose.pdf.Rotation-}
Memutar persegi panjang dengan sudut yang ditentukan.

### rotateAngle {#rotateAngle-int-}
```
public void rotateAngle(int angle)
```

Memutar persegi panjang dengan sudut yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sudut |  | Sudut rotasi dalam derajat antara 0 dan 360. |

### setLLX {#setLLX-double-}
```
public void setLLX(double value)
```

Mengatur koordinat X sudut kiri bawah.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setLLY {#setLLY-double-}
```
public void setLLY(double value)
```

Mengatur koordinat Y sudut kiri bawah.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setURX {#setURX-double-}
```
public void setURX(double value)
```

Mengatur koordinat X sudut kanan atas.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setURY {#setURY-double-}
```
public void setURY(double value)
```

Mengatur koordinat Y sudut kanan atas.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### toArray {#toArray-com.aspose.pdf.engine.data.ITrailerable-}


### toPoints {#toPoints--}
```
public final Point [] toPoints()
```

Mengonversi persegi panjang menjadi array titik ("QuadPoints").

**Returns:**
Array titik.

### toRect {#toRect--}
```
public Rectangle toRect()
```

Mengonversi persegi panjang menjadi instance System.Drawing.Rectangle. Posisi dan ukuran floating-point dipotong.

**Returns:**
Hasil konversi.

### toString {#toString--}
```
public String toString()
```

Mendapatkan representasi string persegi panjang.

**Returns:**
String memiliki format llx,lly,urx,ury.
