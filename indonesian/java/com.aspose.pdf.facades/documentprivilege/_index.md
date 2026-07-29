---
title: "DocumentPrivilege"
linktitle: "DocumentPrivilege"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili hak istimewa untuk mengakses file Pdf. Lihat{@code PdfFileSecurity}. Ada 4 cara menggunakan kelas ini: 1.Menggunakan hak istimewa yang telah ditentukan secara langsung. 2.Berdasarkan a."
type: docs
weight: 110
url: /id/java/com.aspose.pdf.facades/documentprivilege/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.DocumentPrivilege

**All Implemented Interfaces:**
Comparable < Object >

```
public final class DocumentPrivilege extends Object implements Comparable < Object >
```

Mewakili hak istimewa untuk mengakses file Pdf. Lihat {@code PdfFileSecurity}. Ada 4 cara menggunakan kelas ini: 1. Menggunakan hak istimewa yang telah ditentukan secara langsung. 2. Berdasarkan hak istimewa yang telah ditentukan dan mengubah beberapa izin tertentu. 3. Berdasarkan hak istimewa yang telah ditentukan dan mengubah kombinasi izin Adobe Professional tertentu. 4. Menggabungkan cara 2 dan cara 3. //Way1: Menggunakan hak istimewa yang telah ditentukan secara langsung. DocumentPrivilege privilege = DocumentPrivilege.getPrint(); //Way2: Berdasarkan hak istimewa yang telah ditentukan dan mengubah beberapa izin tertentu. DocumentPrivilege privilege = DocumentPrivilege.getAllowAll(); privilege.setAllowPrint(false); privilege.setAllowModifyContents(false); //Way3: Berdasarkan hak istimewa yang telah ditentukan dan mengubah kombinasi izin Adobe Professional tertentu. DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setPrintAllowLevel(2); //Way4: Menggabungkan cara 2 dan cara 3 DocumentPrivilege privilege = DocumentPrivilege.getForbidAll(); privilege.setChangeAllowLevel(1); privilege.setAllowPrint(true);

## Metode

| Metode | Deskripsi |
| --- | --- |
| [compareTo](#compareTo-java.lang.Object-) | Membandingkan dua objek {@code DocumentPrivilege}. |
| [equals](#equals-java.lang.Object-) | Menunjukkan apakah objek lain "sama dengan" objek ini. <p> Metode <code>equals</code> mengimplementasikan relasi ekivalensi pada referensi objek yang tidak null: <ul> <li>It is <i>reflexive</i>: untuk setiap nilai referensi yang tidak null <code>x</code>, <code>x.equals(x)</code> harus mengembalikan <code>true</code>. <li>It is <i>symmetric</i>: untuk setiap nilai referensi yang tidak null <code>x</code> dan <code>y</code>, <code>x.equals(y)</code> harus mengembalikan <code>true</code> jika dan hanya jika <code>y.equals(x)</code> mengembalikan <code>true</code>. <li>It is <i>transitive</i>: untuk setiap nilai referensi yang tidak null <code>x</code>, <code>y</code>, dan <code>z</code>, jika <code>x.equals(y)</code> mengembalikan <code>true</code> dan <code>y.equals(z)</code> mengembalikan <code>true</code>, maka <code>x.equals(z)</code> harus mengembalikan <code>true</code>. <li>It is <i>consistent</i>: untuk setiap nilai referensi yang tidak null <code>x</code> dan <code>y</code>, pemanggilan berulang <tt>x.equals(y)</tt> secara konsisten mengembalikan <code>true</code> atau secara konsisten mengembalikan <code>false</code>, dengan catatan tidak ada informasi yang digunakan dalam perbandingan <code>equals</code> pada objek yang diubah. <li>Untuk setiap nilai referensi yang tidak null <code>x</code>, <code>x.equals(null)</code> harus mengembalikan <code>false</code>. </ul> <p> Metode <tt>equals</tt> untuk kelas <code>Object</code> mengimplementasikan relasi ekivalensi paling diskriminatif yang mungkin pada objek; yaitu, untuk setiap nilai referensi yang tidak null <code>x</code> dan <code>y</code>, metode ini mengembalikan <code>true</code> jika dan hanya jika <code>x</code> dan <code>y</code> merujuk ke objek yang sama (<code>x == y</code> memiliki nilai <code>true</code>). <p> Catatan bahwa biasanya diperlukan untuk mengganti metode <tt>hashCode</tt> setiap kali metode ini diganti, sehingga kontrak umum untuk metode <tt>hashCode</tt> dipertahankan, yang menyatakan bahwa objek yang sama harus memiliki kode hash yang sama. |
| [getAllowAll](#getAllowAll--) | Semua diizinkan. |
| [getAssembly](#getAssembly--) | Mengizinkan perakitan file. |
| [getChangeAllowLevel](#getChangeAllowLevel--) | Mendapatkan dan mengatur tingkat perubahan hak istimewa dokumen. Sama seperti pengaturan Changes Allowed pada Adobe Professional. 0: Tidak ada. 1: Menyisipkan, Menghapus, dan Memutar halaman. 2: Mengisi bidang formulir dan menandatangani bidang tanda tangan yang ada. 3: Mengomentari, mengisi bidang formulir, dan menandatangani bidang tanda tangan yang ada. 4: Semua kecuali mengekstrak halaman. Jika properti memiliki nilai -1, maka tingkat tidak terdefinisi. |
| [getCopy](#getCopy--) | Mengizinkan penyalinan file. |
| [getCopyAllowLevel](#getCopyAllowLevel--) | Mendapatkan dan mengatur tingkat penyalinan hak istimewa dokumen. Sama seperti pengaturan izin pada Adobe Professional. 0: Tidak ada. 1: Mengaktifkan akses teks untuk perangkat pembaca layar bagi penyandang gangguan penglihatan. 2: Mengaktifkan penyalinan teks, gambar, dan konten lainnya. Jika properti memiliki nilai -1, maka tingkat tidak terdefinisi. |
| [getDegradedPrinting](#getDegradedPrinting--) | Mengizinkan pencetakan terdegradasi. |
| [getFillIn](#getFillIn--) | Mengizinkan pengisian formulir dalam file. |
| [getForbidAll](#getForbidAll--) | Semua Dilarang. |
| [getModifyAnnotations](#getModifyAnnotations--) | Mengizinkan memodifikasi anotasi file. |
| [getModifyContents](#getModifyContents--) | Mengizinkan memodifikasi file. |
| [getPrint](#getPrint--) | Mengizinkan pencetakan file. |
| [getPrintAllowLevel](#getPrintAllowLevel--) | Mendapatkan dan mengatur tingkat pencetakan hak istimewa dokumen. Sama seperti pengaturan Printing Allowed pada Adobe Professional. 0: Tidak ada. 1: Resolusi Rendah (150 dpi). 2: Resolusi Tinggi. Jika properti memiliki nilai -1, maka tingkat tidak terdefinisi. |
| [getScreenReaders](#getScreenReaders--) | Mengizinkan hanya membaca di layar. |
| [getValue](#getValue--) |  |
| [hashCode](#hashCode--) | Mengembalikan nilai kode hash untuk objek. Metode ini didukung untuk kepentingan tabel hash seperti yang disediakan oleh <code>java.util.Hashtable</code>. <p> Kontrak umum dari <code>hashCode</code> adalah: <ul> <li>Setiap kali dipanggil pada objek yang sama lebih dari satu kali selama eksekusi aplikasi Java, metode <tt>hashCode</tt> harus secara konsisten mengembalikan integer yang sama, dengan catatan tidak ada informasi yang digunakan dalam perbandingan <tt>equals</tt> pada objek yang diubah. Integer ini tidak harus tetap konsisten dari satu eksekusi aplikasi ke eksekusi lain dari aplikasi yang sama. <li>Jika dua objek sama menurut metode <tt>equals(Object)</tt>, maka memanggil metode <code>hashCode</code> pada masing‑masing dua objek harus menghasilkan hasil integer yang sama. <li>Itu <em>tidak</em> diwajibkan bahwa jika dua objek tidak sama menurut metode {@link java.lang.Object#equals(java.lang.Object)}, maka memanggil metode <tt>hashCode</tt> pada masing‑masing dua objek harus menghasilkan hasil integer yang berbeda. Namun, programmer harus menyadari bahwa menghasilkan hasil integer yang berbeda untuk objek yang tidak sama dapat meningkatkan kinerja tabel hash. </ul> <p> Selama memungkinkan secara praktis, metode hashCode yang didefinisikan oleh kelas <tt>Object</tt> memang mengembalikan integer yang berbeda untuk objek yang berbeda. (Ini biasanya diimplementasikan dengan mengonversi alamat internal objek menjadi sebuah integer, tetapi teknik implementasi ini tidak diwajibkan oleh bahasa pemrograman Java<span style=\"font-size:70%\"><sup>TM</sup></span>.) |
| [isAllowAssembly](#isAllowAssembly--) | Mengatur izin yang memungkinkan perakitan atau tidak. true berarti mengizinkan dan false berarti dilarang. |
| [isAllowCopy](#isAllowCopy--) | Mengatur izin yang memungkinkan penyalinan atau tidak. true berarti mengizinkan dan false berarti dilarang. |
| [isAllowDegradedPrinting](#isAllowDegradedPrinting--) | Mengatur izin yang memungkinkan pencetakan terdegradasi atau tidak. true berarti mengizinkan dan false berarti dilarang. Ketika diatur, pencetakan akan dibatasi pada representasi tingkat rendah dari tampilan, mungkin dengan kualitas yang terdegradasi. |
| [isAllowFillIn](#isAllowFillIn--) | Mengatur izin yang memungkinkan mengisi formulir atau tidak. true berarti mengizinkan dan false berarti dilarang. |
| [isAllowModifyAnnotations](#isAllowModifyAnnotations--) | Mengatur izin yang memungkinkan memodifikasi anotasi atau tidak. true berarti mengizinkan dan false berarti dilarang. |
| [isAllowModifyContents](#isAllowModifyContents--) | Mengatur izin yang memungkinkan memodifikasi konten atau tidak. true berarti mengizinkan dan false berarti dilarang. |
| [isAllowPrint](#isAllowPrint--) | Mengatur izin yang memungkinkan pencetakan atau tidak. true berarti mengizinkan dan false berarti dilarang. |
| [isAllowScreenReaders](#isAllowScreenReaders--) | Mengatur izin yang memungkinkan pembaca layar atau tidak. true berarti mengizinkan dan false berarti dilarang. |
| [setAllowAssembly](#setAllowAssembly-boolean-) | Mengatur izin yang memungkinkan perakitan atau tidak. true berarti mengizinkan dan false berarti dilarang. |
| [setAllowCopy](#setAllowCopy-boolean-) | Mengatur izin yang memungkinkan penyalinan atau tidak. true berarti mengizinkan dan false berarti dilarang. |
| [setAllowDegradedPrinting](#setAllowDegradedPrinting-boolean-) | Mengatur izin yang memungkinkan pencetakan terdegradasi atau tidak. true berarti mengizinkan dan false berarti dilarang. Ketika diatur, pencetakan akan dibatasi pada representasi tingkat rendah dari tampilan, mungkin dengan kualitas yang terdegradasi. |
| [setAllowFillIn](#setAllowFillIn-boolean-) | Mengatur izin yang memungkinkan mengisi formulir atau tidak. true berarti mengizinkan dan false berarti dilarang. |
| [setAllowModifyAnnotations](#setAllowModifyAnnotations-boolean-) | Mengatur izin yang memungkinkan memodifikasi anotasi atau tidak. true berarti mengizinkan dan false berarti dilarang. |
| [setAllowModifyContents](#setAllowModifyContents-boolean-) | Mengatur izin yang memungkinkan memodifikasi konten atau tidak. true berarti mengizinkan dan false berarti dilarang. |
| [setAllowPrint](#setAllowPrint-boolean-) | Mengatur izin yang memungkinkan pencetakan atau tidak. true berarti mengizinkan dan false berarti dilarang. |
| [setAllowScreenReaders](#setAllowScreenReaders-boolean-) | Mengatur izin yang memungkinkan pembaca layar atau tidak. true berarti mengizinkan dan false berarti dilarang. |
| [setChangeAllowLevel](#setChangeAllowLevel-int-) | Mendapatkan dan mengatur tingkat perubahan hak istimewa dokumen. Sama seperti pengaturan Changes Allowed pada Adobe Professional. 0: Tidak ada. 1: Menyisipkan, Menghapus, dan Memutar halaman. 2: Mengisi bidang formulir dan menandatangani bidang tanda tangan yang ada. 3: Mengomentari, mengisi bidang formulir, dan menandatangani bidang tanda tangan yang ada. 4: Semua kecuali mengekstrak halaman. Jika properti memiliki nilai -1, maka tingkat tidak terdefinisi. |
| [setCopyAllowLevel](#setCopyAllowLevel-int-) | Mendapatkan dan mengatur tingkat penyalinan hak istimewa dokumen. Sama seperti pengaturan izin pada Adobe Professional. 0: Tidak ada. 1: Mengaktifkan akses teks untuk perangkat pembaca layar bagi penyandang gangguan penglihatan. 2: Mengaktifkan penyalinan teks, gambar, dan konten lainnya. Jika properti memiliki nilai -1, maka tingkat tidak terdefinisi. |
| [setPrintAllowLevel](#setPrintAllowLevel-int-) | Mendapatkan dan mengatur tingkat pencetakan hak istimewa dokumen. Sama seperti pengaturan Printing Allowed pada Adobe Professional. 0: Tidak ada. 1: Resolusi Rendah (150 dpi). 2: Resolusi Tinggi. Jika properti memiliki nilai -1, maka tingkat tidak terdefinisi. |

### compareTo {#compareTo-java.lang.Object-}
Membandingkan dua objek {@code DocumentPrivilege}.

### equals {#equals-java.lang.Object-}
Menunjukkan apakah objek lain "sama dengan" objek ini. <p> Metode <code>equals</code> mengimplementasikan relasi ekivalensi pada referensi objek yang tidak null: <ul> <li>It is <i>reflexive</i>: untuk setiap nilai referensi yang tidak null <code>x</code>, <code>x.equals(x)</code> harus mengembalikan <code>true</code>. <li>It is <i>symmetric</i>: untuk setiap nilai referensi yang tidak null <code>x</code> dan <code>y</code>, <code>x.equals(y)</code> harus mengembalikan <code>true</code> jika dan hanya jika <code>y.equals(x)</code> mengembalikan <code>true</code>. <li>It is <i>transitive</i>: untuk setiap nilai referensi yang tidak null <code>x</code>, <code>y</code>, dan <code>z</code>, jika <code>x.equals(y)</code> mengembalikan <code>true</code> dan <code>y.equals(z)</code> mengembalikan <code>true</code>, maka <code>x.equals(z)</code> harus mengembalikan <code>true</code>. <li>It is <i>consistent</i>: untuk setiap nilai referensi yang tidak null <code>x</code> dan <code>y</code>, pemanggilan berulang <tt>x.equals(y)</tt> secara konsisten mengembalikan <code>true</code> atau secara konsisten mengembalikan <code>false</code>, dengan catatan tidak ada informasi yang digunakan dalam perbandingan <code>equals</code> pada objek yang diubah. <li>Untuk setiap nilai referensi yang tidak null <code>x</code>, <code>x.equals(null)</code> harus mengembalikan <code>false</code>. </ul> <p> Metode <tt>equals</tt> untuk kelas <code>Object</code> mengimplementasikan relasi ekivalensi paling diskriminatif yang mungkin pada objek; yaitu, untuk setiap nilai referensi yang tidak null <code>x</code> dan <code>y</code>, metode ini mengembalikan <code>true</code> jika dan hanya jika <code>x</code> dan <code>y</code> merujuk ke objek yang sama (<code>x == y</code> memiliki nilai <code>true</code>). <p> Catatan bahwa biasanya diperlukan untuk mengganti metode <tt>hashCode</tt> setiap kali metode ini diganti, sehingga kontrak umum untuk metode <tt>hashCode</tt> dipertahankan, yang menyatakan bahwa objek yang sama harus memiliki kode hash yang sama.

### getAllowAll {#getAllowAll--}
```
public static DocumentPrivilege getAllowAll()
```

Semua diizinkan.

**Returns:**
Elemen DocumentPrivilege

### getAssembly {#getAssembly--}
```
public static DocumentPrivilege getAssembly()
```

Mengizinkan perakitan file.

**Returns:**
Elemen DocumentPrivilege

### getChangeAllowLevel {#getChangeAllowLevel--}
```
public final int getChangeAllowLevel()
```

Mendapatkan dan mengatur tingkat perubahan hak istimewa dokumen. Sama seperti pengaturan Changes Allowed pada Adobe Professional. 0: Tidak ada. 1: Menyisipkan, Menghapus, dan Memutar halaman. 2: Mengisi bidang formulir dan menandatangani bidang tanda tangan yang ada. 3: Mengomentari, mengisi bidang formulir, dan menandatangani bidang tanda tangan yang ada. 4: Semua kecuali mengekstrak halaman. Jika properti memiliki nilai -1, maka tingkat tidak terdefinisi.

**Returns:**
nilai int

### getCopy {#getCopy--}
```
public static DocumentPrivilege getCopy()
```

Mengizinkan penyalinan file.

**Returns:**
Elemen DocumentPrivilege

### getCopyAllowLevel {#getCopyAllowLevel--}
```
public final int getCopyAllowLevel()
```

Mendapatkan dan mengatur tingkat penyalinan hak istimewa dokumen. Sama seperti pengaturan izin pada Adobe Professional. 0: Tidak ada. 1: Mengaktifkan akses teks untuk perangkat pembaca layar bagi penyandang gangguan penglihatan. 2: Mengaktifkan penyalinan teks, gambar, dan konten lainnya. Jika properti memiliki nilai -1, maka tingkat tidak terdefinisi.

**Returns:**
nilai int

### getDegradedPrinting {#getDegradedPrinting--}
```
public static DocumentPrivilege getDegradedPrinting()
```

Mengizinkan pencetakan terdegradasi.

**Returns:**
Elemen DocumentPrivilege

### getFillIn {#getFillIn--}
```
public static DocumentPrivilege getFillIn()
```

Mengizinkan pengisian formulir dalam file.

**Returns:**
Elemen DocumentPrivilege

### getForbidAll {#getForbidAll--}
```
public static DocumentPrivilege getForbidAll()
```

Semua Dilarang.

**Returns:**
Elemen DocumentPrivilege

### getModifyAnnotations {#getModifyAnnotations--}
```
public static DocumentPrivilege getModifyAnnotations()
```

Mengizinkan memodifikasi anotasi file.

**Returns:**
Elemen DocumentPrivilege

### getModifyContents {#getModifyContents--}
```
public static DocumentPrivilege getModifyContents()
```

Mengizinkan memodifikasi file.

**Returns:**
Elemen DocumentPrivilege

### getPrint {#getPrint--}
```
public static DocumentPrivilege getPrint()
```

Mengizinkan pencetakan file.

**Returns:**
Elemen DocumentPrivilege

### getPrintAllowLevel {#getPrintAllowLevel--}
```
public final int getPrintAllowLevel()
```

Mendapatkan dan mengatur tingkat pencetakan hak istimewa dokumen. Sama seperti pengaturan Printing Allowed pada Adobe Professional. 0: Tidak ada. 1: Resolusi Rendah (150 dpi). 2: Resolusi Tinggi. Jika properti memiliki nilai -1, maka tingkat tidak terdefinisi.

**Returns:**
nilai int

### getScreenReaders {#getScreenReaders--}
```
public static DocumentPrivilege getScreenReaders()
```

Mengizinkan hanya membaca di layar.

**Returns:**
Elemen DocumentPrivilege

### getValue {#getValue--}
```
public final int getValue()
```



### hashCode {#hashCode--}
```
public int hashCode()
```

Mengembalikan nilai kode hash untuk objek. Metode ini didukung untuk kepentingan tabel hash seperti yang disediakan oleh <code>java.util.Hashtable</code>. <p> Kontrak umum dari <code>hashCode</code> adalah: <ul> <li>Setiap kali dipanggil pada objek yang sama lebih dari satu kali selama eksekusi aplikasi Java, metode <tt>hashCode</tt> harus secara konsisten mengembalikan integer yang sama, dengan catatan tidak ada informasi yang digunakan dalam perbandingan <tt>equals</tt> pada objek yang diubah. Integer ini tidak harus tetap konsisten dari satu eksekusi aplikasi ke eksekusi lain dari aplikasi yang sama. <li>Jika dua objek sama menurut metode <tt>equals(Object)</tt>, maka memanggil metode <code>hashCode</code> pada masing‑masing dua objek harus menghasilkan hasil integer yang sama. <li>Itu <em>tidak</em> diwajibkan bahwa jika dua objek tidak sama menurut metode {@link java.lang.Object#equals(java.lang.Object)}, maka memanggil metode <tt>hashCode</tt> pada masing‑masing dua objek harus menghasilkan hasil integer yang berbeda. Namun, programmer harus menyadari bahwa menghasilkan hasil integer yang berbeda untuk objek yang tidak sama dapat meningkatkan kinerja tabel hash. </ul> <p> Selama memungkinkan secara praktis, metode hashCode yang didefinisikan oleh kelas <tt>Object</tt> memang mengembalikan integer yang berbeda untuk objek yang berbeda. (Ini biasanya diimplementasikan dengan mengonversi alamat internal objek menjadi sebuah integer, tetapi teknik implementasi ini tidak diwajibkan oleh bahasa pemrograman Java<span style=\"font-size:70%\"><sup>TM</sup></span>.)

**Returns:**
nilai kode hash untuk objek ini. @see java.lang.Object#equals(java.lang.Object) @see java.util.Hashtable

### isAllowAssembly {#isAllowAssembly--}
```
public boolean isAllowAssembly()
```

Mengatur izin yang memungkinkan perakitan atau tidak. true berarti mengizinkan dan false berarti dilarang.

**Returns:**
nilai boolean

### isAllowCopy {#isAllowCopy--}
```
public boolean isAllowCopy()
```

Mengatur izin yang memungkinkan penyalinan atau tidak. true berarti mengizinkan dan false berarti dilarang.

**Returns:**
nilai boolean

### isAllowDegradedPrinting {#isAllowDegradedPrinting--}
```
public boolean isAllowDegradedPrinting()
```

Mengatur izin yang memungkinkan pencetakan terdegradasi atau tidak. true berarti mengizinkan dan false berarti dilarang. Ketika diatur, pencetakan akan dibatasi pada representasi tingkat rendah dari tampilan, mungkin dengan kualitas yang terdegradasi.

**Returns:**
nilai boolean

### isAllowFillIn {#isAllowFillIn--}
```
public boolean isAllowFillIn()
```

Mengatur izin yang memungkinkan mengisi formulir atau tidak. true berarti mengizinkan dan false berarti dilarang.

**Returns:**
nilai boolean

### isAllowModifyAnnotations {#isAllowModifyAnnotations--}
```
public boolean isAllowModifyAnnotations()
```

Mengatur izin yang memungkinkan memodifikasi anotasi atau tidak. true berarti mengizinkan dan false berarti dilarang.

**Returns:**
nilai boolean

### isAllowModifyContents {#isAllowModifyContents--}
```
public boolean isAllowModifyContents()
```

Mengatur izin yang memungkinkan memodifikasi konten atau tidak. true berarti mengizinkan dan false berarti dilarang.

**Returns:**
nilai boolean

### isAllowPrint {#isAllowPrint--}
```
public boolean isAllowPrint()
```

Mengatur izin yang memungkinkan pencetakan atau tidak. true berarti mengizinkan dan false berarti dilarang.

**Returns:**
nilai boolean

### isAllowScreenReaders {#isAllowScreenReaders--}
```
public boolean isAllowScreenReaders()
```

Mengatur izin yang memungkinkan pembaca layar atau tidak. true berarti mengizinkan dan false berarti dilarang.

**Returns:**
nilai boolean

### setAllowAssembly {#setAllowAssembly-boolean-}
```
public void setAllowAssembly(boolean value)
```

Mengatur izin yang memungkinkan perakitan atau tidak. true berarti mengizinkan dan false berarti dilarang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setAllowCopy {#setAllowCopy-boolean-}
```
public void setAllowCopy(boolean value)
```

Mengatur izin yang memungkinkan penyalinan atau tidak. true berarti mengizinkan dan false berarti dilarang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setAllowDegradedPrinting {#setAllowDegradedPrinting-boolean-}
```
public void setAllowDegradedPrinting(boolean value)
```

Mengatur izin yang memungkinkan pencetakan terdegradasi atau tidak. true berarti mengizinkan dan false berarti dilarang. Ketika diatur, pencetakan akan dibatasi pada representasi tingkat rendah dari tampilan, mungkin dengan kualitas yang terdegradasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setAllowFillIn {#setAllowFillIn-boolean-}
```
public void setAllowFillIn(boolean value)
```

Mengatur izin yang memungkinkan mengisi formulir atau tidak. true berarti mengizinkan dan false berarti dilarang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setAllowModifyAnnotations {#setAllowModifyAnnotations-boolean-}
```
public void setAllowModifyAnnotations(boolean value)
```

Mengatur izin yang memungkinkan memodifikasi anotasi atau tidak. true berarti mengizinkan dan false berarti dilarang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setAllowModifyContents {#setAllowModifyContents-boolean-}
```
public void setAllowModifyContents(boolean value)
```

Mengatur izin yang memungkinkan memodifikasi konten atau tidak. true berarti mengizinkan dan false berarti dilarang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setAllowPrint {#setAllowPrint-boolean-}
```
public void setAllowPrint(boolean value)
```

Mengatur izin yang memungkinkan pencetakan atau tidak. true berarti mengizinkan dan false berarti dilarang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setAllowScreenReaders {#setAllowScreenReaders-boolean-}
```
public void setAllowScreenReaders(boolean value)
```

Mengatur izin yang memungkinkan pembaca layar atau tidak. true berarti mengizinkan dan false berarti dilarang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setChangeAllowLevel {#setChangeAllowLevel-int-}
```
public void setChangeAllowLevel(int value)
```

Mendapatkan dan mengatur tingkat perubahan hak istimewa dokumen. Sama seperti pengaturan Changes Allowed pada Adobe Professional. 0: Tidak ada. 1: Menyisipkan, Menghapus, dan Memutar halaman. 2: Mengisi bidang formulir dan menandatangani bidang tanda tangan yang ada. 3: Mengomentari, mengisi bidang formulir, dan menandatangani bidang tanda tangan yang ada. 4: Semua kecuali mengekstrak halaman. Jika properti memiliki nilai -1, maka tingkat tidak terdefinisi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setCopyAllowLevel {#setCopyAllowLevel-int-}
```
public void setCopyAllowLevel(int value)
```

Mendapatkan dan mengatur tingkat penyalinan hak istimewa dokumen. Sama seperti pengaturan izin pada Adobe Professional. 0: Tidak ada. 1: Mengaktifkan akses teks untuk perangkat pembaca layar bagi penyandang gangguan penglihatan. 2: Mengaktifkan penyalinan teks, gambar, dan konten lainnya. Jika properti memiliki nilai -1, maka tingkat tidak terdefinisi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setPrintAllowLevel {#setPrintAllowLevel-int-}
```
public void setPrintAllowLevel(int value)
```

Mendapatkan dan mengatur tingkat pencetakan hak istimewa dokumen. Sama seperti pengaturan Printing Allowed pada Adobe Professional. 0: Tidak ada. 1: Resolusi Rendah (150 dpi). 2: Resolusi Tinggi. Jika properti memiliki nilai -1, maka tingkat tidak terdefinisi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |
