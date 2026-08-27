---
title: "CustomFontSubstitutionBase.OriginalFontSpecification"
linktitle: "CustomFontSubstitutionBase.OriginalFontSpecification"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "<p> Mewakili spesifikasi font asli. </p> <hr> <p> Menyediakan info terkait font asli seperti , flag. Juga menyediakan flag yang membantu memeriksa apakah substitusi akan.</p>"
type: docs
weight: 20
url: /id/java/com.aspose.pdf.text/customfontsubstitutionbase.originalfontspecification/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.CustomFontSubstitutionBase.OriginalFontSpecification

```
public static final class CustomFontSubstitutionBase.OriginalFontSpecification extends Object
```

<p> Mewakili spesifikasi font asli. </p> <hr> <p> Menyediakan informasi terkait font asli seperti , flag. Juga menyediakan flag yang membantu memeriksa apakah substitusi akan tetap terjadi dengan font tersebut dan pengguna dapat mengganti logika substitusi default. </p>

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [OriginalFontSpecification](#OriginalFontSpecification-java.lang.String-boolean-boolean-) | Menginisialisasi objek OriginalFontSpecification baru. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getOriginalFontName](#getOriginalFontName--) | Mendapatkan nama font asli. |
| [isEmbedded](#isEmbedded--) | Mendapatkan nilai yang menunjukkan apakah font tersebut tertanam. |
| [isSubstitutionUnavoidable](#isSubstitutionUnavoidable--) | <p> Mendapatkan nilai yang menunjukkan bahwa substitusi tidak dapat dihindari. </p> |

### OriginalFontSpecification {#OriginalFontSpecification-java.lang.String-boolean-boolean-}
Menginisialisasi objek OriginalFontSpecification baru.

### getOriginalFontName {#getOriginalFontName--}
```
public String getOriginalFontName()
```

Mendapatkan nama font asli.

**Returns:**
nilai String

### isEmbedded {#isEmbedded--}
```
public boolean isEmbedded()
```

Mendapatkan nilai yang menunjukkan apakah font tersebut tertanam.

**Returns:**
nilai boolean

### isSubstitutionUnavoidable {#isSubstitutionUnavoidable--}
```
public boolean isSubstitutionUnavoidable()
```

<p> Mendapatkan nilai yang menunjukkan bahwa substitusi tidak dapat dihindari. </p>

**Returns:**
boolean value <hr> <p> Mengembalikan true jika substitusi diminta karena tidak adanya font asli atau jika font asli tidak dapat digunakan dalam konteks suatu tugas. Jika pengguna mengabaikan flag dan tidak mengganti font - prosedur substitusi font default akan dijalankan. Namun hal ini memberikan kesempatan bagi pengguna untuk mengubah prosedur substitusi standar dan menetapkan font yang lebih baik ke sistem. Mengembalikan false jika font asli ada, valid, tetapi pengguna diizinkan untuk menggantinya. </p>
