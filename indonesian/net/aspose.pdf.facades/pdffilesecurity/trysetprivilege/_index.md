---
title: PdfFileSecurity.TrySetPrivilege
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfFileSecurity. Mengatur keamanan file Pdf dengan kata sandi asli. Tidak melempar pengecualian jika proses gagal
type: docs
weight: 120
url: /id/net/aspose.pdf.facades/pdffilesecurity/trysetprivilege/
---
## Metode PdfFileSecurity.TrySetPrivilege

Mengatur keamanan file Pdf dengan kata sandi asli. Tidak melempar pengecualian jika proses gagal.

```csharp
public bool TrySetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| userPassword | String | Kata sandi pengguna asli. |
| ownerPassword | String | Kata sandi pemilik asli. |
| privilege | DocumentPrivilege | Mengatur hak istimewa. |

### Nilai Kembali

True untuk keberhasilan, atau false.

## Contoh

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
bool result = fileSecurity.TrySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);

[Visual Basic]
Dim inFile As String =  "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TrySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print)
```

### Lihat Juga

* kelas [DocumentPrivilege](../../documentprivilege/)
* kelas [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)