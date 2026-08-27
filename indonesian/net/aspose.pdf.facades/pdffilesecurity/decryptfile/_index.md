---
title: "PdfFileSecurity.DecryptFile"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "PdfFileSecurity method. Mendekripsi Pdf document yang terenkripsi dengan kata sandi pemilik. Jika document tidak memiliki kata sandi pemilik, diperbolehkan menggunakan kata sandi pengguna. Melempar pengecualian jika proses gagal"
type: docs
weight: 60
url: /id/net/aspose.pdf.facades/pdffilesecurity/decryptfile/
---
## PdfFileSecurity.DecryptFile method

Mendekripsi dokumen Pdf yang terenkripsi dengan kata sandi pemilik. Jika dokumen tidak memiliki kata sandi pemilik, diperbolehkan menggunakan kata sandi pengguna. Melempar pengecualian jika proses gagal.

```csharp
public bool DecryptFile(string ownerPassword)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ownerPassword | String | Password pemilik. |

### Nilai Kembalian

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

* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


