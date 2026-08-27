---
title: "Elemen"
linktitle: "Elemen"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang mewakili elemen dasar struktur logis."
type: docs
weight: 1180
url: /id/java/com.aspose.pdf/element/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Element

```
public abstract class Element extends Object
```

Kelas yang mewakili elemen dasar struktur logis.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getActualText](#getActualText--) | (Opsional; PDF 1.4) Teks yang merupakan pengganti tepat untuk elemen struktur dan anak‑anaknya. Teks pengganti ini (yang seharusnya berlaku pada bagian konten sekecil mungkin) berguna saat mengekstrak isi dokumen untuk mendukung aksesibilitas bagi pengguna dengan disabilitas atau untuk tujuan lain. |
| [getAlt](#getAlt--) | (Opsional) Deskripsi alternatif dari elemen struktur dan anak‑anaknya dalam bentuk yang dapat dibaca manusia, yang berguna saat mengekstrak isi dokumen untuk mendukung aksesibilitas bagi pengguna dengan disabilitas atau untuk tujuan lain. |
| [getChildren](#getChildren--) | Mendapatkan koleksi elemen anak. |
| [getE](#getE--) | (Opsional; PDF 1.5) Bentuk lengkap dari sebuah singkatan. |
| [getLang](#getLang--) | (Opsional; PDF 1.4) Bahasa yang menentukan bahasa alami untuk semua teks dalam elemen struktur kecuali jika ditimpa oleh spesifikasi bahasa untuk elemen struktur bersarang atau konten yang ditandai. |
| [remove](#remove--) | Hapus elemen. |
| [setActualText](#setActualText-java.lang.String-) | (Opsional; PDF 1.4) Teks yang merupakan pengganti tepat untuk elemen struktur dan anak‑anaknya. Teks pengganti ini (yang seharusnya berlaku pada bagian konten sekecil mungkin) berguna saat mengekstrak isi dokumen untuk mendukung aksesibilitas bagi pengguna dengan disabilitas atau untuk tujuan lain. |
| [setAlt](#setAlt-java.lang.String-) | (Opsional) Deskripsi alternatif dari elemen struktur dan anak‑anaknya dalam bentuk yang dapat dibaca manusia, yang berguna saat mengekstrak isi dokumen untuk mendukung aksesibilitas bagi pengguna dengan disabilitas atau untuk tujuan lain. |
| [setE](#setE-java.lang.String-) | (Opsional; PDF 1.5) Bentuk lengkap dari sebuah singkatan. |
| [setLang](#setLang-java.lang.String-) | (Opsional; PDF 1.4) Bahasa yang menentukan bahasa alami untuk semua teks dalam elemen struktur kecuali jika ditimpa oleh spesifikasi bahasa untuk elemen struktur bersarang atau konten yang ditandai. |

### getActualText {#getActualText--}
```
public String getActualText()
```

(Opsional; PDF 1.4) Teks yang merupakan pengganti tepat untuk elemen struktur dan anak‑anaknya. Teks pengganti ini (yang seharusnya berlaku pada bagian konten sekecil mungkin) berguna saat mengekstrak isi dokumen untuk mendukung aksesibilitas bagi pengguna dengan disabilitas atau untuk tujuan lain.

**Returns:**
Objek String

### getAlt {#getAlt--}
```
public String getAlt()
```

(Opsional) Deskripsi alternatif dari elemen struktur dan anak‑anaknya dalam bentuk yang dapat dibaca manusia, yang berguna saat mengekstrak isi dokumen untuk mendukung aksesibilitas bagi pengguna dengan disabilitas atau untuk tujuan lain.

**Returns:**
Objek String

### getChildren {#getChildren--}
```
public final ElementCollection getChildren()
```

Mendapatkan koleksi elemen anak.

**Returns:**
Instansi ElementCollection

### getE {#getE--}
```
public String getE()
```

(Opsional; PDF 1.5) Bentuk lengkap dari sebuah singkatan.

**Returns:**
Objek String

### getLang {#getLang--}
```
public String getLang()
```

(Opsional; PDF 1.4) Bahasa yang menentukan bahasa alami untuk semua teks dalam elemen struktur kecuali jika ditimpa oleh spesifikasi bahasa untuk elemen struktur bersarang atau konten yang ditandai.

**Returns:**
Objek String

### remove {#remove--}
```
public final void remove()
```

Hapus elemen.

### setActualText {#setActualText-java.lang.String-}
(Opsional; PDF 1.4) Teks yang merupakan pengganti tepat untuk elemen struktur dan anak‑anaknya. Teks pengganti ini (yang seharusnya berlaku pada bagian konten sekecil mungkin) berguna saat mengekstrak isi dokumen untuk mendukung aksesibilitas bagi pengguna dengan disabilitas atau untuk tujuan lain.

### setAlt {#setAlt-java.lang.String-}
(Opsional) Deskripsi alternatif dari elemen struktur dan anak‑anaknya dalam bentuk yang dapat dibaca manusia, yang berguna saat mengekstrak isi dokumen untuk mendukung aksesibilitas bagi pengguna dengan disabilitas atau untuk tujuan lain.

### setE {#setE-java.lang.String-}
(Opsional; PDF 1.5) Bentuk lengkap dari sebuah singkatan.

### setLang {#setLang-java.lang.String-}
(Opsional; PDF 1.4) Bahasa yang menentukan bahasa alami untuk semua teks dalam elemen struktur kecuali jika ditimpa oleh spesifikasi bahasa untuk elemen struktur bersarang atau konten yang ditandai.
