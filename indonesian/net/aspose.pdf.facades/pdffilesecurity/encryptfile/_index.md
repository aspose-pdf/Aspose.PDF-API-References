---
title: "PdfFileSecurity.EncryptFile"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PdfFileSecurity. Mengenkripsi file Pdf dengan kata sandi pengguna dan kata sandi pemilik serta mengatur hak akses dokumen. Kata sandi pengguna dan kata sandi pemilik dapat bernilai null atau kosong. Kata sandi pemilik akan diganti dengan string acak jika kata sandi pemilik yang diberikan null atau kosong. Melemparkan pengecualian jika proses gagal"
type: docs
weight: 70
url: /id/net/aspose.pdf.facades/pdffilesecurity/encryptfile/
---
## EncryptFile(string, string, DocumentPrivilege, KeySize) {#encryptfile}

Mengenkripsi file Pdf dengan kata sandi pengguna dan kata sandi pemilik serta mengatur hak akses dokumen. Kata sandi pengguna dan kata sandi pemilik dapat bernilai null atau kosong. Kata sandi pemilik akan diganti dengan string acak jika kata sandi pemilik yang dimasukkan bernilai null atau kosong. Melempar pengecualian jika proses gagal.

```csharp
public bool EncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| userPassword | String | Kata sandi pengguna. |
| ownerPassword | String | Password pemilik. |
| hak | DocumentPrivilege | Atur hak. |
| keySize | KeySize | KeySize.x40 untuk enkripsi 40 bit, KeySize.x128 untuk enkripsi 128 bit, dan KeySize.x256 untuk enkripsi 256 bit. |

### Nilai Kembalian

True untuk keberhasilan.

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

Mengenkripsi file Pdf dengan kata sandi pengguna dan kata sandi pemilik serta mengatur hak akses dokumen. Kata sandi pengguna dan kata sandi pemilik dapat bernilai null atau kosong. Kata sandi pemilik akan diganti dengan string acak jika kata sandi pemilik yang dimasukkan bernilai null atau kosong. Terdapat 6 kombinasi kemungkinan nilai KeySize dan Algorithm. Namun (KeySize.x40, Algorithm.AES) dan (KeySize.x256, Algorithm.RC4) tidak valid dan pengecualian yang sesuai akan diangkat jika kit menemukan kombinasi ini. Melempar pengecualian jika proses gagal.

```csharp
public bool EncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize, Algorithm cipher)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| userPassword | String | Kata sandi pengguna. |
| ownerPassword | String | Password pemilik. |
| hak | DocumentPrivilege | Atur hak. |
| keySize | KeySize | KeySize.x40 untuk enkripsi 40 bit, KeySize.x128 untuk enkripsi 128 bit, dan KeySize.x256 untuk enkripsi 256 bit. |
| cipher | Algorithm | Algorithm.AES untuk mengenkripsi menggunakan algoritma AES atau Algorithm.RC4 untuk enkripsi RC4. |

### Nilai Kembalian

True untuk keberhasilan.

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


