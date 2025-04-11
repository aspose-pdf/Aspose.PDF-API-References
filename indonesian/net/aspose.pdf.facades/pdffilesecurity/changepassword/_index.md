---
title: PdfFileSecurity.ChangePassword
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfFileSecurity. Mengubah kata sandi pengguna dan kata sandi pemilik dengan kata sandi pemilik yang mempertahankan pengaturan keamanan asli. Kata sandi pengguna baru dan kata sandi pemilik baru dapat bernilai null atau kosong. Kata sandi pemilik akan diganti dengan string acak jika kata sandi pemilik baru bernilai null atau kosong. Menghasilkan pengecualian jika proses gagal
type: docs
weight: 40
url: /id/net/aspose.pdf.facades/pdffilesecurity/changepassword/
---
## ChangePassword(string, string, string) {#changepassword}

Mengubah kata sandi pengguna dan kata sandi pemilik dengan kata sandi pemilik, mempertahankan pengaturan keamanan asli. Kata sandi pengguna baru dan kata sandi pemilik baru dapat bernilai null atau kosong. Kata sandi pemilik akan diganti dengan string acak jika kata sandi pemilik baru bernilai null atau kosong. Menghasilkan pengecualian jika proses gagal.

```csharp
public bool ChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ownerPassword | String | Kata sandi Pemilik asli. |
| newUserPassword | String | Kata sandi Pengguna baru. |
| newOwnerPassword | String | Kata sandi Pemilik baru. |

### Return Value

True untuk sukses.

## Contoh

```csharp
[C#]
 string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
 string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
 fileSecurity.ChangePassword("owner","newuser","newowner");

[Visual Basic]
 Dim inFile As String = ".D:\\input.pdf"  'The TestPath may be re-assigned.'
 Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
 Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
 fileSecurity.ChangePassword("owner","newuser","newowner")	
```

### Lihat Juga

* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ChangePassword(string, string, string, DocumentPrivilege, KeySize) {#changepassword_1}

Mengubah kata sandi pengguna dan kata sandi dengan kata sandi pemilik, memungkinkan untuk mereset keamanan dokumen Pdf. Kata sandi pengguna baru dan kata sandi pemilik baru dapat bernilai null atau kosong. Kata sandi pemilik akan diganti dengan string acak jika kata sandi pemilik baru bernilai null atau kosong. Menghasilkan pengecualian jika proses gagal.

```csharp
public bool ChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword, 
    DocumentPrivilege privilege, KeySize keySize)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ownerPassword | String | Kata sandi pemilik asli. |
| newUserPassword | String | Kata sandi Pengguna baru. |
| newOwnerPassword | String | Kata sandi Pemilik baru. |
| privilege | DocumentPrivilege | Reset keamanan. |
| keySize | KeySize | KeySize.x40 untuk enkripsi 40 bit, KeySize.x128 untuk enkripsi 128 bit dan KeySize.x256 untuk enkripsi 256 bit. |

### Return Value

True untuk sukses.

## Contoh

```csharp
[C#]
string inFile = ".D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256)
```

### Lihat Juga

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ChangePassword(string, string, string, DocumentPrivilege, KeySize, Algorithm) {#changepassword_2}

Mengubah kata sandi pengguna dan kata sandi dengan kata sandi pemilik, memungkinkan untuk mereset keamanan dokumen Pdf. Kata sandi pengguna baru dan kata sandi pemilik baru dapat bernilai null atau kosong. Kata sandi pemilik akan diganti dengan string acak jika kata sandi pemilik baru bernilai null atau kosong. Ada 6 kombinasi nilai KeySize dan Algorithm yang mungkin. Namun (KeySize.x40, Algorithm.AES) dan (KeySize.x256, Algorithm.RC4) tidak valid dan pengecualian yang sesuai akan diangkat jika kit menemui kombinasi ini. Menghasilkan pengecualian jika proses gagal.

```csharp
public bool ChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword, 
    DocumentPrivilege privilege, KeySize keySize, Algorithm cipher)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ownerPassword | String | Kata sandi pemilik asli. |
| newUserPassword | String | Kata sandi Pengguna baru. |
| newOwnerPassword | String | Kata sandi Pemilik baru. |
| privilege | DocumentPrivilege | Reset keamanan. |
| keySize | KeySize | KeySize.x40 untuk enkripsi 40 bit, KeySize.x128 untuk enkripsi 128 bit dan KeySize.x256 untuk enkripsi 256 bit. |
| cipher | Algorithm | Algorithm.AES untuk mengenkripsi menggunakan algoritma AES atau Algorithm.RC4 untuk enkripsi RC4. |

### Return Value

True untuk sukses.

## Contoh

```csharp
[C#]
string inFile = ".D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES)
```

### Lihat Juga

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* enum [Algorithm](../../algorithm/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)