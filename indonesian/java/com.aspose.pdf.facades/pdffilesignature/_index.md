---
title: "PdfFileSignature"
linktitle: "PdfFileSignature"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili kelas untuk menandatangani file PDF dengan sertifikat."
type: docs
weight: 530
url: /id/java/com.aspose.pdf.facades/pdffilesignature/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSignature, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSignature, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileSignature

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileSignature extends SaveableFacade
```

Mewakili kelas untuk menandatangani file PDF dengan sertifikat.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PdfFileSignature](#PdfFileSignature--) | Konstruktor kelas PdfFileSignature. |
| [PdfFileSignature](#PdfFileSignature-com.aspose.pdf.IDocument-) | Konstruktor kelas PdfFileSignature. |
| [PdfFileSignature](#PdfFileSignature-com.aspose.pdf.IDocument-java.lang.String-) | Konstruktor kelas PdfFileSignature. |
| [PdfFileSignature](#PdfFileSignature-java.lang.String-) | Konstruktor kelas PdfFileSignature. |
| [PdfFileSignature](#PdfFileSignature-java.lang.String-java.lang.String-) | Konstruktor kelas PdfFileSignature. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-) | Mengikat aliran Pdf untuk penyuntingan. |
| [bindPdf](#bindPdf-java.lang.String-) | Mengikat file Pdf untuk penyuntingan. |
| [certify](#certify-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.DocMDPSignature-) | Menyertifikasi dokumen dengan tanda tangan MDP. |
| [certify](#certify-java.lang.String-com.aspose.pdf.DocMDPSignature-) | Menyertifikasi dokumen dengan tanda tangan MDP yang ditempatkan di bidang tanda tangan yang sudah ada. Sebelum menandatangani, bidang tanda tangan harus kosong, yaitu bidang tidak boleh berisi kamus tanda tangan. Jadi dokumen pdf sudah memiliki bidang tanda tangan, Anda tidak perlu menyediakan tempat untuk menempelkan tanda tangan, halaman dan persegi yang sesuai diambil dari bidang tanda tangan yang ditemukan berdasarkan nama tanda tangan (lihat parameter sigName). |
| [close](#close--) | Menutup facade. |
| [containsSignature](#containsSignature--) | Memeriksa apakah pdf memiliki tanda tangan digital atau tidak. |
| [containsUsageRights](#containsUsageRights--) | Memeriksa apakah pdf memiliki hak penggunaan atau tidak. |
| [coversWholeDocument](#coversWholeDocument-com.aspose.pdf.facades.SignatureName-) | Memeriksa apakah tanda tangan mencakup seluruh dokumen. |
| [coversWholeDocument](#coversWholeDocument-java.lang.String-) | Memeriksa apakah tanda tangan mencakup seluruh dokumen. |
| [dispose](#dispose--) | Menutup facade. Metode ini sudah usang, gunakan close() sebagai gantinya. |
| [extractCertificate](#extractCertificate-com.aspose.pdf.facades.SignatureName-) | Mengekstrak sertifikat X.509 tunggal tanda tangan sebagai aliran. |
| [extractCertificate](#extractCertificate-java.lang.String-) | Mengekstrak sertifikat X.509 tunggal tanda tangan sebagai aliran. |
| [extractImage](#extractImage-com.aspose.pdf.facades.SignatureName-) | Mengekstrak gambar tanda tangan. |
| [extractImage](#extractImage-java.lang.String-) | Mengekstrak gambar tanda tangan. |
| [getAccessPermissions](#getAccessPermissions--) | Mengembalikan nilai izin akses dokumen bersertifikat berdasarkan tipe tanda tangan MDP. |
| [getBlankSignNames](#getBlankSignNames--) | Mendapatkan nama semua bidang tanda tangan yang kosong. |
| [getContactInfo](#getContactInfo-com.aspose.pdf.facades.SignatureName-) | Mendapatkan informasi kontak dari sebuah tanda tangan. |
| [getContactInfo](#getContactInfo-java.lang.String-) | Mendapatkan informasi kontak dari sebuah tanda tangan. |
| [getDateTime](#getDateTime-com.aspose.pdf.facades.SignatureName-) | Mendapatkan tanggal dan waktu tanda tangan. |
| [getDateTime](#getDateTime-java.lang.String-) | Mendapatkan tanggal dan waktu tanda tangan. |
| [getLocation](#getLocation-com.aspose.pdf.facades.SignatureName-) | Mendapatkan lokasi tanda tangan. |
| [getLocation](#getLocation-java.lang.String-) | Mendapatkan lokasi tanda tangan. |
| [getReason](#getReason-com.aspose.pdf.facades.SignatureName-) | Mendapatkan alasan tanda tangan. |
| [getReason](#getReason-java.lang.String-) | Mendapatkan alasan tanda tangan. |
| [getRevision](#getRevision-com.aspose.pdf.facades.SignatureName-) | Mendapatkan revisi tanda tangan. |
| [getRevision](#getRevision-java.lang.String-) | Mendapatkan revisi tanda tangan. |
| [getSignatureAppearance](#getSignatureAppearance--) | Mendapatkan tampilan grafis untuk tanda tangan. Nilai properti mewakili nama file gambar. |
| [getSignatureAppearanceStream](#getSignatureAppearanceStream--) | Mendapatkan tampilan grafis untuk tanda tangan. Nilai properti mewakili aliran gambar. |
| [getSignatureNames](#getSignatureNames--) | / * <p> / * Mendapatkan nama semua tanda tangan yang tidak kosong. / * </p> / * <p> / * <pre> / * string inFile=TestPath + \"example1.pdf\"; / * PdfFileSignature pdfSign=new PdfFileSignature(); / * pdfSign.bindPdf(inFile); / * java.util.List<String> names=pdfSign.getSignatureNames(); / * for(int i=0;i<names.size();i++) / * { / * System.out.println(\"signature name:\" + names[i]); / * System.out.println(\"coverswholedocument:\" + pdfSign.coversWholeDocument(names[i])); / * System.out.println(\"revision:\" + pdfSign.getRevision(names[i])); / * System.out.println(\"verifysigned:\" + pdfSign.verifySignature(names[i])); / * System.out.println(\"reason:\" + pdfSign.getReason(names[i])); / * System.out.println(\"location:\" + pdfSign.getLocation(names[i])); / * System.out.println(\"datatime:\" + pdfSign.getDateTime(names[i])); / * } / * System.out.println(\"totalvision:\" + pdfSign.GetTotalRevision()); / * / * </pre> / * |
| [getSignatureNames](#getSignatureNames-boolean-) | Mendapatkan nama semua tanda tangan yang tidak kosong. string inFile=TestPath + \"example1.pdf\"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); java.util.List names=pdfSign.getSignatureNames(); for(int i=0;i<names.size();i++) { System.out.println(\"signature name:\" + names[i]); System.out.println(\"coverswholedocument:\" + pdfSign.coversWholeDocument(names[i])); System.out.println(\"revision:\" + pdfSign.getRevision(names[i])); System.out.println(\"verifysigned:\" + pdfSign.verifySignature(names[i])); System.out.println(\"reason:\" + pdfSign.getReason(names[i])); System.out.println(\"location:\" + pdfSign.getLocation(names[i])); System.out.println(\"datatime:\" + pdfSign.getDateTime(names[i])); } System.out.println(\"totalvision:\" + pdfSign.GetTotalRevision()); |
| [getSignaturesInfo](#getSignaturesInfo--) | Mengambil informasi tentang semua algoritma tanda tangan yang ada dalam dokumen PDF. |
| [getSignerName](#getSignerName-com.aspose.pdf.facades.SignatureName-) | Mendapatkan nama orang atau organisasi yang menandatangani dokumen pdf. |
| [getSignerName](#getSignerName-java.lang.String-) | Mendapatkan nama orang atau organisasi yang menandatangani dokumen pdf. |
| [getSignNames](#getSignNames--) | <p> Mendapatkan nama semua tanda tangan yang tidak kosong. </p> <hr> |
| [getSignNames](#getSignNames-boolean-) | <p> Mendapatkan nama semua tanda tangan yang tidak kosong. </p> <hr> <pre> String inFile=TestPath + \"example1.pdf\"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); ArrayList names=pdfSign.getSignNames(true); for(int i=0;i<names.Count;i++) { System.out.println(\"signature name:\"+(String)names[i]); System.out.println(\"coverswholedocument:\"+pdfSign.IsCoversWholeDocument((String)names[i])); System.out.println(\"revision:\"+pdfSign.GetRevision((String)names[i])); System.out.println(\"verifysigned:\"+pdfSign.VerifySigned((String)names[i])); System.out.println(\"reason:\"+pdfSign.GetReason((String)names[i])); System.out.println(\"location:\"+pdfSign.GetLocation((String)names[i])); System.out.println(\"datatime:\"+pdfSign.GetDateTime((String)names[i])); } System.out.println(\"totalvision:\"+pdfSign.GetTotalRevision()); </pre> |
| [getTotalRevision](#getTotalRevision--) | Mendapatkan total revisi. |
| [isCertified](#isCertified--) | Mendapatkan flag yang menentukan apakah dokumen bersertifikat atau tidak. |
| [isContainSignature](#isContainSignature--) | Memeriksa apakah pdf memiliki tanda tangan digital atau tidak. |
| [isCoversWholeDocument](#isCoversWholeDocument-java.lang.String-) | Memeriksa apakah tanda tangan mencakup seluruh dokumen. |
| [isLtvEnabled](#isLtvEnabled--) | Mendapatkan flag LTV yang diaktifkan. |
| [removeSignature](#removeSignature-com.aspose.pdf.facades.SignatureName-) | Menghapus tanda tangan berdasarkan nama tanda tangan. string inFile = TestPath + \"example1.pdf\"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i]); } pdfSign.save(TestPath + \"signed_removed.pdf\"); |
| [removeSignature](#removeSignature-com.aspose.pdf.facades.SignatureName-boolean-) | Menghapus tanda tangan sesuai dengan nama tanda tangan. string inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i], false); } pdfSign.save(TestPath + "signed_removed.pdf"); |
| [removeSignature](#removeSignature-java.lang.String-) | <p> Hapus tanda tangan sesuai dengan nama tanda tangan. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i)); } pdfSign.save(TestPath + "signed_removed.pdf"); </pre> |
| [removeSignature](#removeSignature-java.lang.String-boolean-) | <p> Menghapus tanda tangan sesuai dengan nama tanda tangan. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.BindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i), false); } pdfSign.save(TestPath + "signed_removed.pdf"); </pre> |
| [removeSignatures](#removeSignatures--) | Menghapus semua tanda tangan. string inFile = TestPath + "example1.pdf"; var pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); pdfSign.removeSignatures(); pdfSign.save(TestPath + "signed_removed.pdf"); |
| [removeUsageRights](#removeUsageRights--) | Menghapus entri hak penggunaan. |
| [save](#save--) | Simpan file pdf yang ditandatangani. Nama file output harus disediakan sebelumnya dengan bantuan konstruktor PdfFileSignature yang sesuai. |
| [save](#save-java.io.OutputStream-) | Simpan file pdf yang ditandatangani. Nama file output harus disediakan sebelumnya dengan bantuan konstruktor PdfFileSignature yang sesuai. |
| [save](#save-java.lang.String-) | Simpan file pdf yang ditandatangani. Nama file output harus disediakan sebelumnya dengan bantuan konstruktor PdfFileSignature yang sesuai. |
| [setCertificate](#setCertificate-java.lang.String-java.lang.String-) | Setel file sertifikat dan kata sandi untuk rutin penandatanganan. |
| [setSignatureAppearance](#setSignatureAppearance-java.lang.String-) | Menetapkan tampilan grafis untuk tanda tangan. Nilai properti mewakili nama file gambar. |
| [setSignatureAppearanceStream](#setSignatureAppearanceStream-java.io.InputStream-) | Menetapkan tampilan grafis untuk tanda tangan. Nilai properti mewakili aliran gambar. |
| [sign](#sign-int-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-) | Tandatangani dokumen dengan tanda tangan tipe yang diberikan. |
| [sign](#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-) | Buat tanda tangan pada dokumen pdf. |
| [sign](#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-) | Tandatangani dokumen dengan tanda tangan tipe yang diberikan. |
| [sign](#sign-int-java.lang.String-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-) | Tandatangani dokumen dengan tanda tangan tipe yang diberikan yang ditempatkan dalam bidang tanda tangan yang sudah ada. |
| [sign](#sign-java.lang.String-com.aspose.pdf.Signature-) | <p> Tandatangani dokumen dengan tanda tangan tipe yang diberikan yang ditempatkan dalam bidang tanda tangan yang sudah ada. Sebelum menandatangani, bidang tanda tangan harus kosong, yaitu bidang tidak boleh berisi kamus tanda tangan. Jadi dokumen pdf sudah memiliki bidang tanda tangan, Anda tidak perlu menyediakan tempat untuk menempelkan tanda tangan, halaman dan persegi yang sesuai diambil dari bidang tanda tangan yang ditemukan berdasarkan nama tanda tangan (lihat parameter SigName). Data seperti alasan tanda tangan, kontak, dan lokasi harus disediakan melalui properti yang sesuai dari objek Signature sig. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; String outFile = TestPath + "signature.pdf"; PKCS1 sig = new PKCS1("certificate.pfx", "password"); sig.setReason ( "Some reason"); sig.setContact ( "Smith"); sig.setLocation ( "New York"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg"); pdfSign.sign("Signature1", sig); pdfSign.save(); </pre> |
| [sign](#sign-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.Signature-) | <p> Tandatangani dokumen dengan tanda tangan tipe yang diberikan yang ditempatkan dalam bidang tanda tangan yang sudah ada. Sebelum menandatangani, bidang tanda tangan harus kosong, yaitu bidang tidak boleh berisi kamus tanda tangan. Jadi dokumen pdf sudah memiliki bidang tanda tangan, Anda tidak perlu menyediakan tempat untuk menempelkan tanda tangan, halaman dan persegi yang sesuai diambil dari bidang tanda tangan yang ditemukan berdasarkan nama tanda tangan (lihat parameter SigName). </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; String outFile = TestPath + "signature.pdf"; PKCS1 sig = new PKCS1("certificate.pfx", "password"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg"); pdfSign.sign("Signature1", "Allen", "success", "ChangSha", sig); pdfSign.save(); </pre> |
| [tryExtractCertificate](#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-java.io.OutputStream:A-) | Mengekstrak sertifikat X.509 tunggal tanda tangan sebagai aliran. |
| [tryExtractCertificate](#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2:A-) | Mengekstrak sertifikat X.509 tunggal dari tanda tangan. |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-) | Memeriksa keabsahan sebuah tanda tangan. |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Memeriksa keabsahan sebuah tanda tangan. |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-) | Memeriksa keabsahan sebuah tanda tangan. |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Memeriksa keabsahan sebuah tanda tangan. |
| [verifySignature](#verifySignature-java.lang.String-) | Memeriksa keabsahan sebuah tanda tangan. |
| [verifySignature](#verifySignature-java.lang.String-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Memeriksa keabsahan sebuah tanda tangan. |
| [verifySigned](#verifySigned-java.lang.String-) | Memeriksa keabsahan sebuah tanda tangan. Metode ini sudah usang dan akan dihapus pada versi 25.1. Gunakan metode VerifySignature sebagai gantinya. |

### PdfFileSignature {#PdfFileSignature--}
```
public PdfFileSignature()
```

Konstruktor kelas PdfFileSignature.

### PdfFileSignature {#PdfFileSignature-com.aspose.pdf.IDocument-}
Konstruktor kelas PdfFileSignature.

### PdfFileSignature {#PdfFileSignature-com.aspose.pdf.IDocument-java.lang.String-}
Konstruktor kelas PdfFileSignature.

### PdfFileSignature {#PdfFileSignature-java.lang.String-}
Konstruktor kelas PdfFileSignature.

### PdfFileSignature {#PdfFileSignature-java.lang.String-java.lang.String-}
Konstruktor kelas PdfFileSignature.

### bindPdf {#bindPdf-java.io.InputStream-}
Mengikat aliran Pdf untuk penyuntingan.

### bindPdf {#bindPdf-java.lang.String-}
Mengikat file Pdf untuk penyuntingan.

### certify {#certify-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.DocMDPSignature-}
Menyertifikasi dokumen dengan tanda tangan MDP.

### certify {#certify-java.lang.String-com.aspose.pdf.DocMDPSignature-}
Menyertifikasi dokumen dengan tanda tangan MDP yang ditempatkan di bidang tanda tangan yang sudah ada. Sebelum menandatangani, bidang tanda tangan harus kosong, yaitu bidang tidak boleh berisi kamus tanda tangan. Jadi dokumen pdf sudah memiliki bidang tanda tangan, Anda tidak perlu menyediakan tempat untuk menempelkan tanda tangan, halaman dan persegi yang sesuai diambil dari bidang tanda tangan yang ditemukan berdasarkan nama tanda tangan (lihat parameter sigName).

### close {#close--}
```
public void close()
```

Menutup facade.

### containsSignature {#containsSignature--}
```
public boolean containsSignature()
```

Memeriksa apakah pdf memiliki tanda tangan digital atau tidak.

**Returns:**
Mengembalikan hasil bertipe bool.

### containsUsageRights {#containsUsageRights--}
```
public boolean containsUsageRights()
```

Memeriksa apakah pdf memiliki hak penggunaan atau tidak.

**Returns:**
Mengembalikan hasil bertipe bool.

### coversWholeDocument {#coversWholeDocument-com.aspose.pdf.facades.SignatureName-}
Memeriksa apakah tanda tangan mencakup seluruh dokumen.

### coversWholeDocument {#coversWholeDocument-java.lang.String-}
Memeriksa apakah tanda tangan mencakup seluruh dokumen.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Menutup facade. Metode ini sudah usang, gunakan close() sebagai gantinya.

### extractCertificate {#extractCertificate-com.aspose.pdf.facades.SignatureName-}
Mengekstrak sertifikat X.509 tunggal tanda tangan sebagai aliran.

### extractCertificate {#extractCertificate-java.lang.String-}
Mengekstrak sertifikat X.509 tunggal tanda tangan sebagai aliran.

### extractImage {#extractImage-com.aspose.pdf.facades.SignatureName-}
Mengekstrak gambar tanda tangan.

### extractImage {#extractImage-java.lang.String-}
Mengekstrak gambar tanda tangan.

### getAccessPermissions {#getAccessPermissions--}
```
public DocMDPAccessPermissions getAccessPermissions()
```

Mengembalikan nilai izin akses dokumen bersertifikat berdasarkan tipe tanda tangan MDP.

**Returns:**
PdfException Jika dokumen sedang disertifikasi, maka mengembalikan nilai izin akses; jika tidak, dilemparkan. @see com.aspose.pdf.DocMDPAccessPermissions

### getBlankSignNames {#getBlankSignNames--}
```
@Deprecated public List < String > getBlankSignNames()
```

Mendapatkan nama semua bidang tanda tangan yang kosong.

**Returns:**
Kembalikan sebuah arrayList. @deprecated Gunakan GetBlankSignatureNames() sebagai gantinya.

### getContactInfo {#getContactInfo-com.aspose.pdf.facades.SignatureName-}
Mendapatkan informasi kontak dari sebuah tanda tangan.

### getContactInfo {#getContactInfo-java.lang.String-}
Mendapatkan informasi kontak dari sebuah tanda tangan.

### getDateTime {#getDateTime-com.aspose.pdf.facades.SignatureName-}
Mendapatkan tanggal dan waktu tanda tangan.

### getDateTime {#getDateTime-java.lang.String-}
Mendapatkan tanggal dan waktu tanda tangan.

### getLocation {#getLocation-com.aspose.pdf.facades.SignatureName-}
Mendapatkan lokasi tanda tangan.

### getLocation {#getLocation-java.lang.String-}
Mendapatkan lokasi tanda tangan.

### getReason {#getReason-com.aspose.pdf.facades.SignatureName-}
Mendapatkan alasan tanda tangan.

### getReason {#getReason-java.lang.String-}
Mendapatkan alasan tanda tangan.

### getRevision {#getRevision-com.aspose.pdf.facades.SignatureName-}
Mendapatkan revisi tanda tangan.

### getRevision {#getRevision-java.lang.String-}
Mendapatkan revisi tanda tangan.

### getSignatureAppearance {#getSignatureAppearance--}
```
public String getSignatureAppearance()
```

Mendapatkan tampilan grafis untuk tanda tangan. Nilai properti mewakili nama file gambar.

**Returns:**
nilai String

### getSignatureAppearanceStream {#getSignatureAppearanceStream--}
```
public InputStream getSignatureAppearanceStream()
```

Mendapatkan tampilan grafis untuk tanda tangan. Nilai properti mewakili aliran gambar.

**Returns:**
Elemen InputStream

### getSignatureNames {#getSignatureNames--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericList< SignatureName > getSignatureNames()
```

/ * <p> / * Mendapatkan nama semua tanda tangan yang tidak kosong. / * </p> / * <p> / * <pre> / * string inFile=TestPath + \"example1.pdf\"; / * PdfFileSignature pdfSign=new PdfFileSignature(); / * pdfSign.bindPdf(inFile); / * java.util.List<String> names=pdfSign.getSignatureNames(); / * for(int i=0;i<names.size();i++) / * { / * System.out.println(\"signature name:\" + names[i]); / * System.out.println(\"coverswholedocument:\" + pdfSign.coversWholeDocument(names[i])); / * System.out.println(\"revision:\" + pdfSign.getRevision(names[i])); / * System.out.println(\"verifysigned:\" + pdfSign.verifySignature(names[i])); / * System.out.println(\"reason:\" + pdfSign.getReason(names[i])); / * System.out.println(\"location:\" + pdfSign.getLocation(names[i])); / * System.out.println(\"datatime:\" + pdfSign.getDateTime(names[i])); / * } / * System.out.println(\"totalvision:\" + pdfSign.GetTotalRevision()); / * / * </pre> / *

**Returns:**
Kembalikan sebuah IList<SignatureName>. /

### getSignatureNames {#getSignatureNames-boolean-}
```
public final com.aspose.ms.System.Collections.Generic.IGenericList< SignatureName > getSignatureNames(boolean onlyActive)
```

Mendapatkan nama semua tanda tangan yang tidak kosong. string inFile=TestPath + \"example1.pdf\"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); java.util.List names=pdfSign.getSignatureNames(); for(int i=0;i<names.size();i++) { System.out.println(\"signature name:\" + names[i]); System.out.println(\"coverswholedocument:\" + pdfSign.coversWholeDocument(names[i])); System.out.println(\"revision:\" + pdfSign.getRevision(names[i])); System.out.println(\"verifysigned:\" + pdfSign.verifySignature(names[i])); System.out.println(\"reason:\" + pdfSign.getReason(names[i])); System.out.println(\"location:\" + pdfSign.getLocation(names[i])); System.out.println(\"datatime:\" + pdfSign.getDateTime(names[i])); } System.out.println(\"totalvision:\" + pdfSign.GetTotalRevision());

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| onlyActive |  | jika true, kembalikan hanya tanda tangan yang aktif; jika tidak, kembalikan semua tanda tangan. |

**Returns:**
Kembalikan sebuah IList<SignatureName>.

### getSignaturesInfo {#getSignaturesInfo--}
```
public final List <com.aspose.pdf.engine.security.SignatureAlgorithmInfo> getSignaturesInfo()
```

Mengambil informasi tentang semua algoritma tanda tangan yang ada dalam dokumen PDF.

**Returns:**
Daftar instance {@link SignatureAlgorithmInfo} yang berisi informasi tentang setiap tanda tangan.

### getSignerName {#getSignerName-com.aspose.pdf.facades.SignatureName-}
Mendapatkan nama orang atau organisasi yang menandatangani dokumen pdf.

### getSignerName {#getSignerName-java.lang.String-}
Mendapatkan nama orang atau organisasi yang menandatangani dokumen pdf.

### getSignNames {#getSignNames--}
```
public final List < String > getSignNames()
```

<p> Mendapatkan nama semua tanda tangan yang tidak kosong. </p> <hr>

**Returns:**
Kembalikan sebuah arrayList.

### getSignNames {#getSignNames-boolean-}
```
@Deprecated public List < String > getSignNames(boolean onlyActive)
```

<p> Mendapatkan nama semua tanda tangan yang tidak kosong. </p> <hr> <pre> String inFile=TestPath + \"example1.pdf\"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); ArrayList names=pdfSign.getSignNames(true); for(int i=0;i<names.Count;i++) { System.out.println(\"signature name:\"+(String)names[i]); System.out.println(\"coverswholedocument:\"+pdfSign.IsCoversWholeDocument((String)names[i])); System.out.println(\"revision:\"+pdfSign.GetRevision((String)names[i])); System.out.println(\"verifysigned:\"+pdfSign.VerifySigned((String)names[i])); System.out.println(\"reason:\"+pdfSign.GetReason((String)names[i])); System.out.println(\"location:\"+pdfSign.GetLocation((String)names[i])); System.out.println(\"datatime:\"+pdfSign.GetDateTime((String)names[i])); } System.out.println(\"totalvision:\"+pdfSign.GetTotalRevision()); </pre>

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| onlyActive |  | nilai boolean, jika true, kembalikan hanya tanda tangan yang aktif; jika tidak, kembalikan semua tanda tangan. |

**Returns:**
Kembalikan sebuah arrayList. @deprecated Metode ini dapat menghasilkan nama tanda tangan yang sama, yang tidak dapat dibedakan selama verifikasi. Gunakan getSignatureNames(boolean onlyActive) sebagai gantinya.

### getTotalRevision {#getTotalRevision--}
```
public int getTotalRevision()
```

Mendapatkan total revisi.

**Returns:**
Kembalikan total jumlah revisi tanda tangan.

### isCertified {#isCertified--}
```
public boolean isCertified()
```

Mendapatkan flag yang menentukan apakah dokumen bersertifikat atau tidak.

**Returns:**
nilai boolean

### isContainSignature {#isContainSignature--}
```
@Deprecated public boolean isContainSignature()
```

Memeriksa apakah pdf memiliki tanda tangan digital atau tidak.

**Returns:**
Mengembalikan hasil bertipe bool.

### isCoversWholeDocument {#isCoversWholeDocument-java.lang.String-}
Memeriksa apakah tanda tangan mencakup seluruh dokumen.

### isLtvEnabled {#isLtvEnabled--}
```
public final boolean isLtvEnabled()
```

Mendapatkan flag LTV yang diaktifkan.

**Returns:**
nilai boolean

### removeSignature {#removeSignature-com.aspose.pdf.facades.SignatureName-}
Menghapus tanda tangan berdasarkan nama tanda tangan. string inFile = TestPath + \"example1.pdf\"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i]); } pdfSign.save(TestPath + \"signed_removed.pdf\");

### removeSignature {#removeSignature-com.aspose.pdf.facades.SignatureName-boolean-}
Menghapus tanda tangan sesuai dengan nama tanda tangan. string inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i], false); } pdfSign.save(TestPath + "signed_removed.pdf");

### removeSignature {#removeSignature-java.lang.String-}
<p> Hapus tanda tangan sesuai dengan nama tanda tangan. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i)); } pdfSign.save(TestPath + "signed_removed.pdf"); </pre>

### removeSignature {#removeSignature-java.lang.String-boolean-}
<p> Menghapus tanda tangan sesuai dengan nama tanda tangan. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.BindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i), false); } pdfSign.save(TestPath + "signed_removed.pdf"); </pre>

### removeSignatures {#removeSignatures--}
```
public final void removeSignatures()
```

Menghapus semua tanda tangan. string inFile = TestPath + "example1.pdf"; var pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); pdfSign.removeSignatures(); pdfSign.save(TestPath + "signed_removed.pdf");

### removeUsageRights {#removeUsageRights--}
```
public void removeUsageRights()
```

Menghapus entri hak penggunaan.

### save {#save--}
```
@Deprecated public void save()
```

Simpan file pdf yang ditandatangani. Nama file output harus disediakan sebelumnya dengan bantuan konstruktor PdfFileSignature yang sesuai.

### save {#save-java.io.OutputStream-}
Simpan file pdf yang ditandatangani. Nama file output harus disediakan sebelumnya dengan bantuan konstruktor PdfFileSignature yang sesuai.

### save {#save-java.lang.String-}
Simpan file pdf yang ditandatangani. Nama file output harus disediakan sebelumnya dengan bantuan konstruktor PdfFileSignature yang sesuai.

### setCertificate {#setCertificate-java.lang.String-java.lang.String-}
Setel file sertifikat dan kata sandi untuk rutin penandatanganan.

### setSignatureAppearance {#setSignatureAppearance-java.lang.String-}
Menetapkan tampilan grafis untuk tanda tangan. Nilai properti mewakili nama file gambar.

### setSignatureAppearanceStream {#setSignatureAppearanceStream-java.io.InputStream-}
Menetapkan tampilan grafis untuk tanda tangan. Nilai properti mewakili aliran gambar.

### sign {#sign-int-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-}
Tandatangani dokumen dengan tanda tangan tipe yang diberikan.

### sign {#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-}
Buat tanda tangan pada dokumen pdf.

### sign {#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-}
Tandatangani dokumen dengan tanda tangan tipe yang diberikan.

### sign {#sign-int-java.lang.String-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-}
Tandatangani dokumen dengan tanda tangan tipe yang diberikan yang ditempatkan dalam bidang tanda tangan yang sudah ada.

### sign {#sign-java.lang.String-com.aspose.pdf.Signature-}
<p> Tandatangani dokumen dengan tanda tangan tipe yang diberikan yang ditempatkan dalam bidang tanda tangan yang sudah ada. Sebelum menandatangani, bidang tanda tangan harus kosong, yaitu bidang tidak boleh berisi kamus tanda tangan. Jadi dokumen pdf sudah memiliki bidang tanda tangan, Anda tidak perlu menyediakan tempat untuk menempelkan tanda tangan, halaman dan persegi yang sesuai diambil dari bidang tanda tangan yang ditemukan berdasarkan nama tanda tangan (lihat parameter SigName). Data seperti alasan tanda tangan, kontak, dan lokasi harus disediakan melalui properti yang sesuai dari objek Signature sig. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; String outFile = TestPath + "signature.pdf"; PKCS1 sig = new PKCS1("certificate.pfx", "password"); sig.setReason ( "Some reason"); sig.setContact ( "Smith"); sig.setLocation ( "New York"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg"); pdfSign.sign("Signature1", sig); pdfSign.save(); </pre>

### sign {#sign-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.Signature-}
<p> Tandatangani dokumen dengan tanda tangan tipe yang diberikan yang ditempatkan dalam bidang tanda tangan yang sudah ada. Sebelum menandatangani, bidang tanda tangan harus kosong, yaitu bidang tidak boleh berisi kamus tanda tangan. Jadi dokumen pdf sudah memiliki bidang tanda tangan, Anda tidak perlu menyediakan tempat untuk menempelkan tanda tangan, halaman dan persegi yang sesuai diambil dari bidang tanda tangan yang ditemukan berdasarkan nama tanda tangan (lihat parameter SigName). </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; String outFile = TestPath + "signature.pdf"; PKCS1 sig = new PKCS1("certificate.pfx", "password"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg"); pdfSign.sign("Signature1", "Allen", "success", "ChangSha", sig); pdfSign.save(); </pre>

### tryExtractCertificate {#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-java.io.OutputStream:A-}
Mengekstrak sertifikat X.509 tunggal tanda tangan sebagai aliran.

### tryExtractCertificate {#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2:A-}
Mengekstrak sertifikat X.509 tunggal dari tanda tangan.

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-}
Memeriksa keabsahan sebuah tanda tangan.

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Memeriksa keabsahan sebuah tanda tangan.

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-}
Memeriksa keabsahan sebuah tanda tangan.

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Memeriksa keabsahan sebuah tanda tangan.

### verifySignature {#verifySignature-java.lang.String-}
Memeriksa keabsahan sebuah tanda tangan.

### verifySignature {#verifySignature-java.lang.String-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Memeriksa keabsahan sebuah tanda tangan.

### verifySigned {#verifySigned-java.lang.String-}
Memeriksa keabsahan sebuah tanda tangan. Metode ini sudah usang dan akan dihapus pada versi 25.1. Gunakan metode VerifySignature sebagai gantinya.
