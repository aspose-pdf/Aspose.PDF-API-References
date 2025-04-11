---
title: PdfFileSecurity.TryEncryptFile
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfFileSecurity. Mengenkripsi file Pdf dengan userpassword dan ownerpassword dan mengatur hak akses dokumen. User password dan owner password dapat bernilai null atau kosong. Owner password akan diganti dengan string acak jika owner password input bernilai null atau kosong. Tidak melempar pengecualian jika proses gagal
type: docs
weight: 110
url: /id/net/aspose.pdf.facades/pdffilesecurity/tryencryptfile/
---
## Metode PdfFileSecurity.TryEncryptFile

Mengenkripsi file Pdf dengan userpassword dan ownerpassword dan mengatur hak akses dokumen. User password dan owner password dapat bernilai null atau kosong. Owner password akan diganti dengan string acak jika owner password input bernilai null atau kosong. Tidak melempar pengecualian jika proses gagal.

```csharp
public bool TryEncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| userPassword | String | User password. |
| ownerPassword | String | Owner password. |
| privilege | DocumentPrivilege | Atur hak akses. |
| keySize | KeySize | KeySize.x40 untuk enkripsi 40 bit, KeySize.x128 untuk enkripsi 128 bit dan KeySize.x256 untuk enkripsi 256 bit. |

### Nilai Kembali

True untuk sukses, atau false.

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

* kelas [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* kelas [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)