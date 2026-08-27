---
title: "PdfFileSecurity.TrySetPrivilege"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "PdfFileSecurity method. Mengatur keamanan file Pdf dengan kata sandi asli. Tidak melempar pengecualian jika proses gagal"
type: docs
weight: 120
url: /id/net/aspose.pdf.facades/pdffilesecurity/trysetprivilege/
---
## PdfFileSecurity.TrySetPrivilege method

Mengatur keamanan file Pdf dengan kata sandi asli. Tidak melempar pengecualian jika proses gagal.

```csharp
public bool TrySetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| userPassword | String | Kata sandi pengguna asli. |
| ownerPassword | String | Kata sandi pemilik asli. |
| hak | DocumentPrivilege | Atur hak. |

### Nilai Kembalian

True untuk berhasil, atau false.

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

* class [DocumentPrivilege](../../documentprivilege/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


