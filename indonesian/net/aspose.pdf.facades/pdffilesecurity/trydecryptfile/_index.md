---
title: "PdfFileSecurity.TryDecryptFile"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "PdfFileSecurity method. Mendekripsi Pdf document yang terenkripsi dengan kata sandi pemilik. Jika document tidak memiliki kata sandi pemilik, diperbolehkan menggunakan kata sandi pengguna. Tidak melempar pengecualian jika proses gagal"
type: docs
weight: 100
url: /id/net/aspose.pdf.facades/pdffilesecurity/trydecryptfile/
---
## PdfFileSecurity.TryDecryptFile method

Mendekripsi dokumen Pdf yang terenkripsi dengan kata sandi pemilik. Jika dokumen tidak memiliki kata sandi pemilik, diperbolehkan menggunakan kata sandi pengguna. Tidak melempar pengecualian jika proses gagal.

```csharp
public bool TryDecryptFile(string ownerPassword)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ownerPassword | String | Password pemilik. |

### Nilai Kembalian

Benar untuk keberhasilan,atau salah.

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

* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


