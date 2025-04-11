---
title: PdfFileSecurity.TrySetPrivilege
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSecurity metodu. Pdf dosyası güvenliğini orijinal şifre ile ayarlar. İşlem başarısız olursa bir istisna fırlatmaz
type: docs
weight: 120
url: /tr/net/aspose.pdf.facades/pdffilesecurity/trysetprivilege/
---
## PdfFileSecurity.TrySetPrivilege metodu

Pdf dosyası güvenliğini orijinal şifre ile ayarlar. İşlem başarısız olursa bir istisna fırlatmaz.

```csharp
public bool TrySetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| userPassword | String | Orijinal kullanıcı şifresi. |
| ownerPassword | String | Orijinal sahip şifresi. |
| privilege | DocumentPrivilege | Ayrıcalığı ayarla. |

### Dönüş Değeri

Başarı için true, ya da false.

## Örnekler

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

### Ayrıca Bakınız

* class [DocumentPrivilege](../../documentprivilege/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)