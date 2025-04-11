---
title: PdfFileSecurity.DecryptFile
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSecurity yöntemi. Sahip parolası ile şifrelenmiş bir Pdf belgesini çözer. Belgenin sahip parolası yoksa, kullanıcı parolasının kullanılmasına izin verilir. İşlem başarısız olursa bir istisna fırlatır.
type: docs
weight: 60
url: /tr/net/aspose.pdf.facades/pdffilesecurity/decryptfile/
---
## PdfFileSecurity.DecryptFile yöntemi

Sahip parolası ile şifrelenmiş bir Pdf belgesini çözer. Belgenin sahip parolası yoksa, kullanıcı parolasının kullanılmasına izin verilir. İşlem başarısız olursa bir istisna fırlatır.

```csharp
public bool DecryptFile(string ownerPassword)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ownerPassword | String | Sahip parolası. |

### Dönüş Değeri

Başarı için doğru.

## Örnekler

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

### Ayrıca Bakınız

* sınıf [PdfFileSecurity](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)