---
title: PdfFileSecurity.SetPrivilege
second_title: Aspose.PDF for .NET API Reference
description: Metode PdfFileSecurity. Mengatur keamanan file Pdf dengan kata sandi pengguna/pemilik yang kosong. Kata sandi pemilik akan ditambahkan dengan string acak. Menghasilkan pengecualian jika proses gagal
type: docs
weight: 80
url: /id/net/aspose.pdf.facades/pdffilesecurity/setprivilege/
---
## SetPrivilege(DocumentPrivilege) {#setprivilege}

Mengatur keamanan file Pdf dengan kata sandi pengguna/pemilik yang kosong. Kata sandi pemilik akan ditambahkan dengan string acak. Menghasilkan pengecualian jika proses gagal.

```csharp
public bool SetPrivilege(DocumentPrivilege privilege)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| privilege | DocumentPrivilege | Atur hak istimewa. |

### Nilai Kembali

True untuk keberhasilan.

## Contoh

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.SetPrivilege(DocumentPrivilege.Print);

[Visual Basic]
Dim inFile As String =  "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.SetPrivilege(DocumentPrivilege.Print)
```

### Lihat Juga

* kelas [DocumentPrivilege](../../documentprivilege/)
* kelas [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SetPrivilege(string, string, DocumentPrivilege) {#setprivilege_1}

Mengatur keamanan file Pdf dengan kata sandi asli. Menghasilkan pengecualian jika proses gagal.

```csharp
public bool SetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| userPassword | String | Kata sandi pengguna asli. |
| ownerPassword | String | Kata sandi pemilik asli. |
| privilege | DocumentPrivilege | Atur hak istimewa. |

### Nilai Kembali

True untuk keberhasilan.

## Contoh

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.SetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);

[Visual Basic]
Dim inFile As String =  "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.SetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print)
```

### Lihat Juga

* kelas [DocumentPrivilege](../../documentprivilege/)
* kelas [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)