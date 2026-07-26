---
title: "PdfFileSecurity"
linktitle: "PdfFileSecurity"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili enkripsi atau dekripsi file PDF dengan kata sandi pemilik atau pengguna, mengubah pengaturan keamanan dan kata sandi."
type: docs
weight: 520
url: /id/java/com.aspose.pdf.facades/pdffilesecurity/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSecurity, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSecurity, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileSecurity

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileSecurity extends SaveableFacade implements com.aspose.ms.System.IDisposable
```

Mewakili enkripsi atau dekripsi file PDF dengan kata sandi pemilik atau pengguna, mengubah pengaturan keamanan dan kata sandi.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PdfFileSecurity](#PdfFileSecurity--) | Inisialisasi objek PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-com.aspose.pdf.IDocument-) | Inisialisasi objek PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-com.aspose.pdf.IDocument-java.io.OutputStream-) | Inisialisasi objek PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-com.aspose.pdf.IDocument-java.lang.String-) | Inisialisasi objek PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-java.io.InputStream-java.io.OutputStream-) | Inisialisasi objek PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-java.lang.String-java.lang.String-) | Inisialisasi objek PdfFileSecurity. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-) | Menginisialisasi facade. |
| [bindPdf](#bindPdf-java.lang.String-) | Menginisialisasi facade. |
| [changePassword](#changePassword-java.lang.String-java.lang.String-java.lang.String-) | Mengubah kata sandi pengguna dan kata sandi pemilik menggunakan kata sandi pemilik, mempertahankan pengaturan keamanan asli. Kata sandi pengguna baru dan kata sandi pemilik baru dapat bernilai null atau kosong. Kata sandi pemilik akan diganti dengan string acak jika kata sandi pemilik baru bernilai null atau kosong. Melemparkan pengecualian jika proses gagal. string inFile = "D:\\\\input.pdf"; //The TestPath may be re-assigned. string outFile = "D:\\\\output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.changePassword("owner","newuser","newowner"); |
| [changePassword](#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | <p> Mengubah kata sandi pengguna dan kata sandi menggunakan kata sandi pemilik, memungkinkan mereset keamanan dokumen Pdf. Kata sandi pengguna baru dan kata sandi pemilik baru dapat bernilai null atau kosong. Kata sandi pemilik akan diganti dengan string acak jika kata sandi pemilik baru bernilai null atau kosong. </p> <p> Melemparkan pengecualian jika proses gagal. </p> <hr> <pre> string inFile = "input.pdf"; // The TestPath may be // re-assigned. string outFile = "output.pdf"; // The TestPath may be // re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword("owner", "newuser", "newowner", DocumentPrivilege.Print, KeySize.x256); </pre> |
| [changePassword](#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-) | <p> Mengubah kata sandi pengguna dan kata sandi menggunakan kata sandi pemilik, memungkinkan mereset keamanan dokumen Pdf. Kata sandi pengguna baru dan kata sandi pemilik baru dapat bernilai null atau kosong. Kata sandi pemilik akan diganti dengan string acak jika kata sandi pemilik baru bernilai null atau kosong. Ada 6 kombinasi nilai yang mungkin antara KeySize dan Algorithm. Namun (KeySize.x40, Algorithm.AES) dan (KeySize.x256, Algorithm.RC4) tidak valid dan pengecualian yang sesuai akan dilemparkan jika kit menemukan kombinasi ini. Melemparkan pengecualian jika proses gagal. </p> <hr> <pre> string inFile = "input.pdf"; // The TestPath may be // re-assigned. string outFile = "output.pdf"; // The TestPath may be // re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword("owner", "newuser", "newowner", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre> |
| [close](#close--) | Menutup facade. |
| [decryptFile](#decryptFile-java.lang.String-) | Mendekripsi dokumen Pdf yang terenkripsi menggunakan kata sandi pemilik. Jika dokumen tidak memiliki kata sandi pemilik, diperbolehkan menggunakan kata sandi pengguna. Melemparkan pengecualian jika proses gagal. string inFile = "input.pdf"; //The TestPath may be re-assigned. string outFile = "output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.decryptFile("ownerpass"); |
| [dispose](#dispose--) | Menutup facade. |
| [encryptFile](#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | <p> Mengenkripsi file Pdf dengan kata sandi pengguna dan kata sandi pemilik serta mengatur hak akses dokumen. Kata sandi pengguna dan kata sandi pemilik dapat bernilai null atau kosong. Kata sandi pemilik akan diganti dengan string acak jika kata sandi pemilik yang diberikan bernilai null atau kosong. Melemparkan pengecualian jika proses gagal. </p> <hr> <pre> String inFile = "input.pdf"; // The TestPath may be // re-assigned. String outFile = "output.pdf"; // The TestPath may be // re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256); </pre> |
| [encryptFile](#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-) | <p> Mengenkripsi file Pdf dengan userpassword dan ownerpassword serta mengatur hak istimewa dokumen untuk akses. Password pengguna dan password pemilik dapat bernilai null atau kosong. Password pemilik akan diganti dengan string acak jika password pemilik yang diberikan null atau kosong. Terdapat 6 kombinasi yang mungkin antara nilai KeySize dan Algorithm. Namun (KeySize.x40, Algorithm.AES) dan (KeySize.x256, Algorithm.RC4) tidak valid dan pengecualian yang sesuai akan dilempar jika kit menemukan kombinasi ini. Melempar pengecualian jika proses gagal. </p> <hr> <pre> String inFile = "input.pdf"; // TestPath dapat ditetapkan kembali. String outFile = "output.pdf"; // TestPath dapat ditetapkan kembali. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.encryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre> |
| [getAllowExceptions](#getAllowExceptions--) | Jika nilai ini diatur ke true, pengecualian akan dilempar saat operasi gagal. Jika tidak, metode mengembalikan false saat gagal dan pengecualian terakhir dapat diperiksa melalui properti LastException. |
| [getLastException](#getLastException--) | Mengembalikan pengecualian yang dilempar oleh operasi terakhir. |
| [setAllowExceptions](#setAllowExceptions-boolean-) | Jika nilai ini diatur ke true, pengecualian akan dilempar saat operasi gagal. Jika tidak, metode mengembalikan false saat gagal dan pengecualian terakhir dapat diperiksa melalui properti LastException. |
| [setInputFile](#setInputFile-java.lang.String-) | Mengatur file input. Obsolete("Use bindPdf(inputStream) method for facade initialization.") |
| [setInputStream](#setInputStream-java.io.InputStream-) | Mengatur aliran input. Obsolete("Use bindPdf(inputStream) method for facade initialization.") |
| [setOutputFile](#setOutputFile-java.lang.String-) | Mengatur file output. Obsolete("Use save(outputStream) method for getting facade results.") |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | Mengatur aliran output. Obsolete("Use save(outputStream) method for getting facade results.") |
| [setPrivilege](#setPrivilege-com.aspose.pdf.facades.DocumentPrivilege-) | <p> Mengatur keamanan file Pdf dengan password pengguna/pemilik kosong. Password pemilik akan ditambahkan dengan string acak. Melempar pengecualian jika proses gagal. </p> <hr> <pre> string inFile = "input.pdf"; // TestPath dapat ditetapkan kembali. string outFile = "output.pdf"; // TestPath dapat ditetapkan kembali. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(DocumentPrivilege.Print); </pre> |
| [setPrivilege](#setPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-) | <p> Mengatur keamanan file Pdf dengan password asli. Melempar pengecualian jika proses gagal. </p> <hr> <pre> string inFile = "input.pdf"; // TestPath dapat ditetapkan kembali. string outFile = "output.pdf"; // TestPath dapat ditetapkan kembali. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(userPassword, ownerPassword, DocumentPrivilege.getPrint()); </pre> |
| [tryChangePassword](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-) | Mengubah password pengguna dan password pemilik menggunakan password pemilik, mempertahankan pengaturan keamanan asli. Password pengguna baru dan password pemilik baru dapat bernilai null atau kosong. Password pemilik akan diganti dengan string acak jika password pemilik baru null atau kosong. Tidak melempar pengecualian jika proses gagal. string inFile = "D:\\\\input.pdf"; // TestPath dapat ditetapkan kembali. string outFile = "D:\\\\output.pdf"; // TestPath dapat ditetapkan kembali. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner"); |
| [tryChangePassword](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | Mengubah password pengguna dan password menggunakan password pemilik, memungkinkan mereset keamanan dokumen Pdf. Password pengguna baru dan password pemilik baru dapat bernilai null atau kosong. Password pemilik akan diganti dengan string acak jika password pemilik baru null atau kosong. Tidak melempar pengecualian jika proses gagal. string inFile = ".D:\\\\input.pdf"; // TestPath dapat ditetapkan kembali. string outFile = "D:\\\\output.pdf"; // TestPath dapat ditetapkan kembali. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256); |
| [tryChangePassword](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-) | Mengubah kata sandi pengguna dan kata sandi oleh kata sandi pemilik, memungkinkan untuk mereset keamanan dokumen Pdf. Kata sandi pengguna baru dan kata sandi pemilik baru dapat bernilai null atau kosong. Kata sandi pemilik akan diganti dengan string acak jika kata sandi pemilik baru bernilai null atau kosong. Ada 6 kombinasi kemungkinan nilai KeySize dan Algorithm. Namun (KeySize.x40, Algorithm.AES) dan (KeySize.x256, Algorithm.RC4) tidak valid dan pengecualian yang sesuai akan dilempar jika kit menemukan kombinasi ini. Tidak melempar pengecualian jika proses gagal. string inFile = "D:\\\\input.pdf"; //TestPath dapat ditetapkan kembali. string outFile = "D:\\\\output.pdf"; //TestPath dapat ditetapkan kembali. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.changePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES); |
| [tryDecryptFile](#tryDecryptFile-java.lang.String-) | Mendekripsi dokumen Pdf yang terenkripsi dengan kata sandi pemilik. Jika dokumen tidak memiliki kata sandi pemilik, diperbolehkan menggunakan kata sandi pengguna. Tidak melempar pengecualian jika proses gagal. string inFile = "input.pdf"; //TestPath dapat ditetapkan kembali. string outFile = "output.pdf"; //TestPath dapat ditetapkan kembali. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.TryDecryptFile("ownerpass"); |
| [tryEncryptFile](#tryEncryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | Mengenkripsi file Pdf dengan kata sandi pengguna dan kata sandi pemilik serta mengatur hak akses dokumen. Kata sandi pengguna dan kata sandi pemilik dapat bernilai null atau kosong. Kata sandi pemilik akan diganti dengan string acak jika kata sandi pemilik input bernilai null atau kosong. Tidak melempar pengecualian jika proses gagal. string inFile = "input.pdf"; //TestPath dapat ditetapkan kembali. string outFile = "output.pdf"; //TestPath dapat ditetapkan kembali. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256); |
| [trySetPrivilege](#trySetPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-) | Mengatur keamanan file Pdf dengan kata sandi asli. Tidak melempar pengecualian jika proses gagal. string inFile = "D:\\\\input.pdf"; //TestPath dapat ditetapkan kembali. string outFile = "D:\\\\output.pdf"; //TestPath dapat ditetapkan kembali. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.trySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print); |

### PdfFileSecurity {#PdfFileSecurity--}
```
public PdfFileSecurity()
```

Inisialisasi objek PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-com.aspose.pdf.IDocument-}
Inisialisasi objek PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-com.aspose.pdf.IDocument-java.io.OutputStream-}
Inisialisasi objek PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-com.aspose.pdf.IDocument-java.lang.String-}
Inisialisasi objek PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-java.io.InputStream-java.io.OutputStream-}
Inisialisasi objek PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-java.lang.String-java.lang.String-}
Inisialisasi objek PdfFileSecurity.

### bindPdf {#bindPdf-java.io.InputStream-}
Menginisialisasi facade.

### bindPdf {#bindPdf-java.lang.String-}
Menginisialisasi facade.

### changePassword {#changePassword-java.lang.String-java.lang.String-java.lang.String-}
Mengubah kata sandi pengguna dan kata sandi pemilik dengan kata sandi pemilik, mempertahankan pengaturan keamanan asli. Kata sandi pengguna baru dan kata sandi pemilik baru dapat bernilai null atau kosong. Kata sandi pemilik akan diganti dengan string acak jika kata sandi pemilik baru bernilai null atau kosong. Melempar pengecualian jika proses gagal. string inFile = "D:\\input.pdf"; //TestPath dapat ditetapkan kembali. string outFile = "D:\\output.pdf"; //TestPath dapat ditetapkan kembali. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.changePassword("owner","newuser","newowner");

### changePassword {#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
<p> Mengubah kata sandi pengguna dan kata sandi menggunakan kata sandi pemilik, memungkinkan mereset keamanan dokumen Pdf. Kata sandi pengguna baru dan kata sandi pemilik baru dapat bernilai null atau kosong. Kata sandi pemilik akan diganti dengan string acak jika kata sandi pemilik baru bernilai null atau kosong. </p> <p> Melemparkan pengecualian jika proses gagal. </p> <hr> <pre> string inFile = "input.pdf"; // The TestPath may be // re-assigned. string outFile = "output.pdf"; // The TestPath may be // re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword("owner", "newuser", "newowner", DocumentPrivilege.Print, KeySize.x256); </pre>

### changePassword {#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-}
<p> Mengubah kata sandi pengguna dan kata sandi menggunakan kata sandi pemilik, memungkinkan mereset keamanan dokumen Pdf. Kata sandi pengguna baru dan kata sandi pemilik baru dapat bernilai null atau kosong. Kata sandi pemilik akan diganti dengan string acak jika kata sandi pemilik baru bernilai null atau kosong. Ada 6 kombinasi nilai yang mungkin antara KeySize dan Algorithm. Namun (KeySize.x40, Algorithm.AES) dan (KeySize.x256, Algorithm.RC4) tidak valid dan pengecualian yang sesuai akan dilemparkan jika kit menemukan kombinasi ini. Melemparkan pengecualian jika proses gagal. </p> <hr> <pre> string inFile = "input.pdf"; // The TestPath may be // re-assigned. string outFile = "output.pdf"; // The TestPath may be // re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword("owner", "newuser", "newowner", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre>

### close {#close--}
```
public void close()
```

Menutup facade.

### decryptFile {#decryptFile-java.lang.String-}
Mendekripsi dokumen Pdf yang terenkripsi menggunakan kata sandi pemilik. Jika dokumen tidak memiliki kata sandi pemilik, diperbolehkan menggunakan kata sandi pengguna. Melemparkan pengecualian jika proses gagal. string inFile = "input.pdf"; //The TestPath may be re-assigned. string outFile = "output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.decryptFile("ownerpass");

### dispose {#dispose--}
```
public void dispose()
```

Menutup facade.

### encryptFile {#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
<p> Mengenkripsi file Pdf dengan kata sandi pengguna dan kata sandi pemilik serta mengatur hak akses dokumen. Kata sandi pengguna dan kata sandi pemilik dapat bernilai null atau kosong. Kata sandi pemilik akan diganti dengan string acak jika kata sandi pemilik yang diberikan bernilai null atau kosong. Melemparkan pengecualian jika proses gagal. </p> <hr> <pre> String inFile = "input.pdf"; // The TestPath may be // re-assigned. String outFile = "output.pdf"; // The TestPath may be // re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256); </pre>

### encryptFile {#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-}
<p> Mengenkripsi file Pdf dengan userpassword dan ownerpassword serta mengatur hak istimewa dokumen untuk akses. Password pengguna dan password pemilik dapat bernilai null atau kosong. Password pemilik akan diganti dengan string acak jika password pemilik yang diberikan null atau kosong. Terdapat 6 kombinasi yang mungkin antara nilai KeySize dan Algorithm. Namun (KeySize.x40, Algorithm.AES) dan (KeySize.x256, Algorithm.RC4) tidak valid dan pengecualian yang sesuai akan dilempar jika kit menemukan kombinasi ini. Melempar pengecualian jika proses gagal. </p> <hr> <pre> String inFile = "input.pdf"; // TestPath dapat ditetapkan kembali. String outFile = "output.pdf"; // TestPath dapat ditetapkan kembali. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.encryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre>

### getAllowExceptions {#getAllowExceptions--}
```
@Deprecated public final boolean getAllowExceptions()
```

Jika nilai ini diatur ke true, pengecualian akan dilempar saat operasi gagal. Jika tidak, metode mengembalikan false saat gagal dan pengecualian terakhir dapat diperiksa melalui properti LastException.

**Returns:**
nilai boolean @deprecated Properti ini sudah usang dan tidak dapat digunakan untuk mengizinkan melempar pengecualian.

### getLastException {#getLastException--}
```
public final RuntimeException getLastException()
```

Mengembalikan pengecualian yang dilempar oleh operasi terakhir.

**Returns:**
java.lang.RuntimeException

### setAllowExceptions {#setAllowExceptions-boolean-}
```
@Deprecated public final void setAllowExceptions(boolean value)
```

Jika nilai ini diatur ke true, pengecualian akan dilempar saat operasi gagal. Jika tidak, metode mengembalikan false saat gagal dan pengecualian terakhir dapat diperiksa melalui properti LastException.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean @deprecated Properti ini sudah usang dan tidak dapat digunakan untuk mengizinkan melempar pengecualian. |

### setInputFile {#setInputFile-java.lang.String-}
Mengatur file input. Obsolete("Use bindPdf(inputStream) method for facade initialization.")

### setInputStream {#setInputStream-java.io.InputStream-}
Mengatur aliran input. Obsolete("Use bindPdf(inputStream) method for facade initialization.")

### setOutputFile {#setOutputFile-java.lang.String-}
Mengatur file output. Obsolete("Use save(outputStream) method for getting facade results.")

### setOutputStream {#setOutputStream-java.io.OutputStream-}
Mengatur aliran output. Obsolete("Use save(outputStream) method for getting facade results.")

### setPrivilege {#setPrivilege-com.aspose.pdf.facades.DocumentPrivilege-}
<p> Mengatur keamanan file Pdf dengan password pengguna/pemilik kosong. Password pemilik akan ditambahkan dengan string acak. Melempar pengecualian jika proses gagal. </p> <hr> <pre> string inFile = "input.pdf"; // TestPath dapat ditetapkan kembali. string outFile = "output.pdf"; // TestPath dapat ditetapkan kembali. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(DocumentPrivilege.Print); </pre>

### setPrivilege {#setPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-}
<p> Mengatur keamanan file Pdf dengan password asli. Melempar pengecualian jika proses gagal. </p> <hr> <pre> string inFile = "input.pdf"; // TestPath dapat ditetapkan kembali. string outFile = "output.pdf"; // TestPath dapat ditetapkan kembali. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(userPassword, ownerPassword, DocumentPrivilege.getPrint()); </pre>

### tryChangePassword {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-}
Mengubah kata sandi pengguna dan kata sandi pemilik dengan kata sandi pemilik, mempertahankan pengaturan keamanan asli. Kata sandi pengguna baru dan kata sandi pemilik baru dapat bernilai null atau kosong. Kata sandi pemilik akan diganti dengan string acak jika kata sandi pemilik baru bernilai null atau kosong. Tidak melempar pengecualian jika proses gagal. string inFile = "D:\\input.pdf"; //TestPath dapat ditetapkan kembali. string outFile = "D:\\output.pdf"; //TestPath dapat ditetapkan kembali. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner");

### tryChangePassword {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
 Mengubah kata sandi pengguna dan kata sandi oleh kata sandi pemilik, memungkinkan mereset keamanan dokumen Pdf. Kata sandi pengguna baru dan kata sandi pemilik baru dapat bernilai null atau kosong. Kata sandi pemilik akan diganti dengan string acak jika kata sandi pemilik baru bernilai null atau kosong. Tidak melempar pengecualian jika proses gagal. string inFile = ".D:\\input.pdf"; //TestPath dapat ditetapkan kembali. string outFile = "D:\\output.pdf"; //TestPath dapat ditetapkan kembali. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256);

### tryChangePassword {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-}
 Mengubah kata sandi pengguna dan kata sandi oleh kata sandi pemilik, memungkinkan mereset keamanan dokumen Pdf. Kata sandi pengguna baru dan kata sandi pemilik baru dapat bernilai null atau kosong. Kata sandi pemilik akan diganti dengan string acak jika kata sandi pemilik baru bernilai null atau kosong. Ada 6 kombinasi kemungkinan nilai KeySize dan Algorithm. Namun (KeySize.x40, Algorithm.AES) dan (KeySize.x256, Algorithm.RC4) tidak valid dan pengecualian yang sesuai akan dilempar jika kit menemukan kombinasi ini. Tidak melempar pengecualian jika proses gagal. string inFile = "D:\\input.pdf"; //TestPath dapat ditetapkan kembali. string outFile = "D:\\output.pdf"; //TestPath dapat ditetapkan kembali. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.changePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);

### tryDecryptFile {#tryDecryptFile-java.lang.String-}
Mendekripsi dokumen Pdf yang terenkripsi dengan kata sandi pemilik. Jika dokumen tidak memiliki kata sandi pemilik, diperbolehkan menggunakan kata sandi pengguna. Tidak melempar pengecualian jika proses gagal. string inFile = "input.pdf"; //TestPath dapat ditetapkan kembali. string outFile = "output.pdf"; //TestPath dapat ditetapkan kembali. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.TryDecryptFile("ownerpass");

### tryEncryptFile {#tryEncryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
Mengenkripsi file Pdf dengan kata sandi pengguna dan kata sandi pemilik serta mengatur hak akses dokumen. Kata sandi pengguna dan kata sandi pemilik dapat bernilai null atau kosong. Kata sandi pemilik akan diganti dengan string acak jika kata sandi pemilik input bernilai null atau kosong. Tidak melempar pengecualian jika proses gagal. string inFile = "input.pdf"; //TestPath dapat ditetapkan kembali. string outFile = "output.pdf"; //TestPath dapat ditetapkan kembali. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256);

### trySetPrivilege {#trySetPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-}
 Mengatur keamanan file Pdf dengan kata sandi asli. Tidak melempar pengecualian jika proses gagal. string inFile = "D:\\input.pdf"; //TestPath dapat ditetapkan kembali. string outFile = "D:\\output.pdf"; //TestPath dapat ditetapkan kembali. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.trySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);
