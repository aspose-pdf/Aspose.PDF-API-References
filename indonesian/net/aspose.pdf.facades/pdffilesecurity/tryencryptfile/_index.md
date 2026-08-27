---
title: "PdfFileSecurity.TryEncryptFile"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "PdfFileSecurity method. Mengenkripsi file Pdf dengan kata sandi pengguna dan kata sandi pemilik serta mengatur hak akses documents. Kata sandi pengguna dan kata sandi pemilik dapat bernilai null atau kosong. Kata sandi pemilik akan diganti dengan string acak jika kata sandi pemilik masukan bernilai null atau kosong. Tidak melempar pengecualian jika proses gagal"
type: docs
weight: 110
url: /id/net/aspose.pdf.facades/pdffilesecurity/tryencryptfile/
---
## PdfFileSecurity.TryEncryptFile method

Mengenkripsi file Pdf dengan userpassword dan ownerpassword serta mengatur hak istimewa dokumen untuk akses. Kata sandi pengguna dan kata sandi pemilik dapat bernilai null atau kosong. Kata sandi pemilik akan diganti dengan string acak jika kata sandi pemilik masukan bernilai null atau kosong. Tidak melempar pengecualian jika proses gagal.

```csharp
public bool TryEncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| userPassword | String | Kata sandi pengguna. |
| ownerPassword | String | Password pemilik. |
| hak | DocumentPrivilege | Atur hak. |
| keySize | KeySize | KeySize.x40 untuk enkripsi 40 bit, KeySize.x128 untuk enkripsi 128 bit, dan KeySize.x256 untuk enkripsi 256 bit. |

### Nilai Kembalian

True untuk berhasil, atau false.

## Contoh

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
bool result = fileSecurity.TryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256);	

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"   'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256)
```

### Lihat Juga

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


