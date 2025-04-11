---
title: PdfFileSecurity.TryDecryptFile
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfFileSecurity. Mendekripsi dokumen Pdf yang terenkripsi dengan kata sandi pemilik. Jika dokumen tidak memiliki kata sandi pemilik, diperbolehkan untuk menggunakan kata sandi pengguna. Tidak melempar pengecualian jika proses gagal
type: docs
weight: 100
url: /id/net/aspose.pdf.facades/pdffilesecurity/trydecryptfile/
---
## Metode PdfFileSecurity.TryDecryptFile

Mendekripsi dokumen Pdf yang terenkripsi dengan kata sandi pemilik. Jika dokumen tidak memiliki kata sandi pemilik, diperbolehkan untuk menggunakan kata sandi pengguna. Tidak melempar pengecualian jika proses gagal.

```csharp
public bool TryDecryptFile(string ownerPassword)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ownerPassword | String | Kata sandi pemilik. |

### Nilai Kembali

True untuk sukses, atau false.

## Contoh

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
bool result = fileSecurity.TryDecryptFile("ownerpass");

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TryDecryptFile("ownerpass")
```

### Lihat Juga

* kelas [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)