---
title: PdfFileSecurity.EncryptFile
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfFileSecurity. Mengenkripsi file Pdf dengan userpassword dan ownerpassword dan mengatur hak akses dokumen. User password dan owner password dapat null atau kosong. Owner password akan diganti dengan string acak jika owner password input adalah null atau kosong. Menghasilkan pengecualian jika proses gagal
type: docs
weight: 70
url: /id/net/aspose.pdf.facades/pdffilesecurity/encryptfile/
---
## EncryptFile(string, string, DocumentPrivilege, KeySize) {#encryptfile}

Mengenkripsi file Pdf dengan userpassword dan ownerpassword dan mengatur hak akses dokumen. User password dan owner password dapat null atau kosong. Owner password akan diganti dengan string acak jika owner password input adalah null atau kosong. Menghasilkan pengecualian jika proses gagal.

```csharp
public bool EncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| userPassword | String | User password. |
| ownerPassword | String | Owner password. |
| privilege | DocumentPrivilege | Atur hak akses. |
| keySize | KeySize | KeySize.x40 untuk enkripsi 40 bit, KeySize.x128 untuk enkripsi 128 bit dan KeySize.x256 untuk enkripsi 256 bit. |

### Return Value

True untuk sukses.

## Contoh

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256);	

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"   'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256)
```

### Lihat Juga

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## EncryptFile(string, string, DocumentPrivilege, KeySize, Algorithm) {#encryptfile_1}

Mengenkripsi file Pdf dengan userpassword dan ownerpassword dan mengatur hak akses dokumen. User password dan owner password dapat null atau kosong. Owner password akan diganti dengan string acak jika owner password input adalah null atau kosong. Terdapat 6 kombinasi nilai KeySize dan Algorithm yang mungkin. Namun (KeySize.x40, Algorithm.AES) dan (KeySize.x256, Algorithm.RC4) tidak valid dan pengecualian yang sesuai akan diangkat jika kit menemui kombinasi ini. Menghasilkan pengecualian jika proses gagal.

```csharp
public bool EncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize, Algorithm cipher)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| userPassword | String | User password. |
| ownerPassword | String | Owner password. |
| privilege | DocumentPrivilege | Atur hak akses. |
| keySize | KeySize | KeySize.x40 untuk enkripsi 40 bit, KeySize.x128 untuk enkripsi 128 bit dan KeySize.x256 untuk enkripsi 256 bit. |
| cipher | Algorithm | Algorithm.AES untuk mengenkripsi menggunakan algoritma AES atau Algorithm.RC4 untuk enkripsi RC4. |

### Return Value

True untuk sukses.

## Contoh

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.EncryptFile("userpass","ownerpass",DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);	

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"   'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
fileSecurity.EncryptFile("userpass","ownerpass",DocumentPrivilege.Print,KeySize.x256,Algorithm.AES)
```

### Lihat Juga

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* enum [Algorithm](../../algorithm/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)