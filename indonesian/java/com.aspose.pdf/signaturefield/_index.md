---
title: "SignatureField"
linktitle: "SignatureField"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili bidang formulir tanda tangan."
type: docs
weight: 4510
url: /id/java/com.aspose.pdf/signaturefield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.Field, com.aspose.pdf.SignatureField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public final class SignatureField extends Field
```

Mewakili bidang formulir tanda tangan.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [SignatureField](#SignatureField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Menginisialisasi instance baru dari kelas {@code SignatureField}. |
| [SignatureField](#SignatureField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Menginisialisasi instance baru dari kelas {@code SignatureField}. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [clear](#clear--) | Menghapus objek tanda tangan dari bidang. |
| [extractCertificate](#extractCertificate--) | Mengekstrak sertifikat X.509 tunggal dalam format DER sebagai aliran. |
| [extractCertificateObject](#extractCertificateObject--) | Mengekstrak objek sertifikat X.509 tunggal. |
| [extractImage](#extractImage--) | Mengekstrak gambar tanda tangan sebagai aliran yang dikodekan jpeg. |
| [extractImage](#extractImage-com.aspose.pdf.ImageType-) | Mengekstrak gambar tanda tangan sebagai aliran yang dikodekan jpeg. |
| [getSignature](#getSignature--) | Mendapatkan objek tanda tangan. Objek ini berisi data tanda tangan terkait standar kriptografi kunci publik. Kelas {@code PKCS1}, {@code PKCS7}, dan {@code PKCS7Detached} mewakili semua tipe objek tanda tangan yang didukung. |
| [sign](#sign-com.aspose.pdf.Signature-) | Tandatangani dokumen menggunakan bidang tanda tangan ini. |
| [sign](#sign-com.aspose.pdf.Signature-java.io.InputStream-java.lang.String-) | Menandatangani dokumen menggunakan bidang tanda tangan ini. |

### SignatureField {#SignatureField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Menginisialisasi instance baru dari kelas {@code SignatureField}.

### SignatureField {#SignatureField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Menginisialisasi instance baru dari kelas {@code SignatureField}.

### clear {#clear--}
```
public void clear()
```

Menghapus objek tanda tangan dari bidang.

### extractCertificate {#extractCertificate--}
```
public InputStream extractCertificate()
```

Mengekstrak sertifikat X.509 tunggal dalam format DER sebagai aliran.

**Returns:**
Jika sertifikat ditemukan, mengembalikan sertifikat X.509 tunggal; jika tidak, null.

### extractCertificateObject {#extractCertificateObject--}
```
public final com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 extractCertificateObject()
```

Mengekstrak objek sertifikat X.509 tunggal.

**Returns:**
Jika sertifikat ditemukan, mengembalikan sertifikat X.509 tunggal; jika tidak, null.

### extractImage {#extractImage--}
```
public InputStream extractImage()
```

Mengekstrak gambar tanda tangan sebagai aliran yang dikodekan jpeg.

**Returns:**
Jika gambar berhasil ditemukan, mengembalikan objek aliran yang dikodekan jpeg; jika tidak, null.

### extractImage {#extractImage-com.aspose.pdf.ImageType-}
Mengekstrak gambar tanda tangan sebagai aliran yang dikodekan jpeg.

**Returns:**
Jika gambar berhasil ditemukan, mengembalikan objek aliran yang dikodekan jpeg; jika tidak, null.

### getSignature {#getSignature--}
```
public final Signature getSignature()
```

Mendapatkan objek tanda tangan. Objek ini berisi data tanda tangan terkait standar kriptografi kunci publik. Kelas {@code PKCS1}, {@code PKCS7}, dan {@code PKCS7Detached} mewakili semua tipe objek tanda tangan yang didukung.

**Returns:**
Objek tanda tangan

### sign {#sign-com.aspose.pdf.Signature-}
Tandatangani dokumen menggunakan bidang tanda tangan ini.

### sign {#sign-com.aspose.pdf.Signature-java.io.InputStream-java.lang.String-}
Menandatangani dokumen menggunakan bidang tanda tangan ini.
