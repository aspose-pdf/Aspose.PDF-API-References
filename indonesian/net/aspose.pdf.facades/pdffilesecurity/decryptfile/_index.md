---
title: PdfFileSecurity.DecryptFile
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfFileSecurity. Mendekripsi dokumen Pdf yang terenkripsi dengan kata sandi pemilik. Jika dokumen tidak memiliki kata sandi pemilik, diizinkan untuk menggunakan kata sandi pengguna. Menghasilkan pengecualian jika proses gagal
type: docs
weight: 60
url: /id/net/aspose.pdf.facades/pdffilesecurity/decryptfile/
---
## Metode PdfFileSecurity.DecryptFile

Mendekripsi dokumen Pdf yang terenkripsi dengan kata sandi pemilik. Jika dokumen tidak memiliki kata sandi pemilik, diizinkan untuk menggunakan kata sandi pengguna. Menghasilkan pengecualian jika proses gagal.

```csharp
public bool DecryptFile(string ownerPassword)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ownerPassword | String | Kata sandi pemilik. |

### Nilai Kembali

True untuk keberhasilan.

## Contoh

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.DecryptFile("ownerpass");

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.DecryptFile("ownerpass")
```

### Lihat Juga

* kelas [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)