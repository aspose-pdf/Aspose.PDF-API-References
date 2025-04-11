---
title: PdfFileSecurity.TryEncryptFile
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSecurity metodu. Pdf dosyasını kullanıcı şifresi ve sahip şifresi ile şifreler ve belgelerin erişim ayrıcalıklarını ayarlar. Kullanıcı şifresi ve sahip şifresi null veya boş olabilir. Girdi sahip şifresi null veya boşsa, sahip şifresi rastgele bir dize ile değiştirilir. İşlem başarısız olursa bir istisna fırlatmaz.
type: docs
weight: 110
url: /tr/net/aspose.pdf.facades/pdffilesecurity/tryencryptfile/
---
## PdfFileSecurity.TryEncryptFile metodu

Pdf dosyasını kullanıcı şifresi ve sahip şifresi ile şifreler ve belgenin erişim ayrıcalıklarını ayarlar. Kullanıcı şifresi ve sahip şifresi null veya boş olabilir. Girdi sahip şifresi null veya boşsa, sahip şifresi rastgele bir dize ile değiştirilir. İşlem başarısız olursa bir istisna fırlatmaz.

```csharp
public bool TryEncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| userPassword | String | Kullanıcı şifresi. |
| ownerPassword | String | Sahip şifresi. |
| privilege | DocumentPrivilege | Ayrıcalığı ayarla. |
| keySize | KeySize | 40 bit şifreleme için KeySize.x40, 128 bit şifreleme için KeySize.x128 ve 256 bit şifreleme için KeySize.x256. |

### Dönüş Değeri

Başarı için true, ya da başarısızlık için false.

## Örnekler

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
bool result = fileSecurity.TryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256);	

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"   'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256)
```

### Ayrıca Bakınız

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)