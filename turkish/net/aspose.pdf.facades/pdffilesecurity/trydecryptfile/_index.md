---
title: PdfFileSecurity.TryDecryptFile
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSecurity metodu. Sahip parolası ile şifrelenmiş bir Pdf belgesini çözer. Belge sahip parolasına sahip değilse, kullanıcı parolasının kullanılmasına izin verilir. İşlem başarısız olursa bir istisna fırlatmaz.
type: docs
weight: 100
url: /tr/net/aspose.pdf.facades/pdffilesecurity/trydecryptfile/
---
## PdfFileSecurity.TryDecryptFile metodu

Sahip parolası ile şifrelenmiş bir Pdf belgesini çözer. Belge sahip parolasına sahip değilse, kullanıcı parolasının kullanılmasına izin verilir. İşlem başarısız olursa bir istisna fırlatmaz.

```csharp
public bool TryDecryptFile(string ownerPassword)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ownerPassword | String | Sahip parolası. |

### Dönüş Değeri

Başarı için true, ya da false.

## Örnekler

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

### Ayrıca Bakınız

* sınıf [PdfFileSecurity](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)