---
title: PdfFileSecurity.SetPrivilege
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSecurity metodu. Pdf dosyası güvenliğini boş kullanıcı/sahip şifreleri ile ayarlar. Sahip şifresi rastgele bir dize ile eklenecektir. İşlem başarısız olursa bir istisna fırlatır.
type: docs
weight: 80
url: /tr/net/aspose.pdf.facades/pdffilesecurity/setprivilege/
---
## SetPrivilege(DocumentPrivilege) {#setprivilege}

Pdf dosyası güvenliğini boş kullanıcı/sahip şifreleri ile ayarlar. Sahip şifresi rastgele bir dize ile eklenecektir. İşlem başarısız olursa bir istisna fırlatır.

```csharp
public bool SetPrivilege(DocumentPrivilege privilege)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| privilege | DocumentPrivilege | Ayrıcalığı ayarla. |

### Dönüş Değeri

Başarı için doğru (True).

## Örnekler

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

### Ayrıca Bakınız

* sınıf [DocumentPrivilege](../../documentprivilege/)
* sınıf [PdfFileSecurity](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## SetPrivilege(string, string, DocumentPrivilege) {#setprivilege_1}

Orijinal şifre ile Pdf dosyası güvenliğini ayarlar. İşlem başarısız olursa bir istisna fırlatır.

```csharp
public bool SetPrivilege(string userPassword, string ownerPassword, DocumentPrivilege privilege)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| userPassword | String | Orijinal kullanıcı şifresi. |
| ownerPassword | String | Orijinal sahip şifresi. |
| privilege | DocumentPrivilege | Ayrıcalığı ayarla. |

### Dönüş Değeri

Başarı için doğru (True).

## Örnekler

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

### Ayrıca Bakınız

* sınıf [DocumentPrivilege](../../documentprivilege/)
* sınıf [PdfFileSecurity](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)