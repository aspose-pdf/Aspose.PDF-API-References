---
title: PdfFileSecurity.EncryptFile
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSecurity metodu. Pdf dosyasını kullanıcı şifresi ve sahip şifresi ile şifreler ve belgelerin erişim ayrıcalıklarını ayarlar. Kullanıcı şifresi ve sahip şifresi null veya boş olabilir. Girdi sahip şifresi null veya boşsa, sahip şifresi rastgele bir dize ile değiştirilir. İşlem başarısız olursa istisna fırlatır.
type: docs
weight: 70
url: /tr/net/aspose.pdf.facades/pdffilesecurity/encryptfile/
---
## EncryptFile(string, string, DocumentPrivilege, KeySize) {#encryptfile}

Pdf dosyasını kullanıcı şifresi ve sahip şifresi ile şifreler ve belgenin erişim ayrıcalıklarını ayarlar. Kullanıcı şifresi ve sahip şifresi null veya boş olabilir. Girdi sahip şifresi null veya boşsa, sahip şifresi rastgele bir dize ile değiştirilir. İşlem başarısız olursa istisna fırlatır.

```csharp
public bool EncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| userPassword | String | Kullanıcı şifresi. |
| ownerPassword | String | Sahip şifresi. |
| privilege | DocumentPrivilege | Ayrıcalığı ayarla. |
| keySize | KeySize | 40 bit şifreleme için KeySize.x40, 128 bit şifreleme için KeySize.x128 ve 256 bit şifreleme için KeySize.x256. |

### Dönüş Değeri

Başarı için True.

## Örnekler

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256);	

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"   'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256)
```

### Ayrıca Bakınız

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## EncryptFile(string, string, DocumentPrivilege, KeySize, Algorithm) {#encryptfile_1}

Pdf dosyasını kullanıcı şifresi ve sahip şifresi ile şifreler ve belgenin erişim ayrıcalıklarını ayarlar. Kullanıcı şifresi ve sahip şifresi null veya boş olabilir. Girdi sahip şifresi null veya boşsa, sahip şifresi rastgele bir dize ile değiştirilir. KeySize ve Algorithm değerlerinin 6 olası kombinasyonu vardır. Ancak (KeySize.x40, Algorithm.AES) ve (KeySize.x256, Algorithm.RC4) geçersizdir ve bu kombinasyonla karşılaşılırsa ilgili istisna fırlatılacaktır. İşlem başarısız olursa istisna fırlatır.

```csharp
public bool EncryptFile(string userPassword, string ownerPassword, DocumentPrivilege privilege, 
    KeySize keySize, Algorithm cipher)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| userPassword | String | Kullanıcı şifresi. |
| ownerPassword | String | Sahip şifresi. |
| privilege | DocumentPrivilege | Ayrıcalığı ayarla. |
| keySize | KeySize | 40 bit şifreleme için KeySize.x40, 128 bit şifreleme için KeySize.x128 ve 256 bit şifreleme için KeySize.x256. |
| cipher | Algorithm | AES algoritması ile şifrelemek için Algorithm.AES veya RC4 şifrelemesi için Algorithm.RC4. |

### Dönüş Değeri

Başarı için True.

## Örnekler

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf"; //The TestPath may be re-assigned.	
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
fileSecurity.EncryptFile("userpass","ownerpass",DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);	

[Visual Basic]
Dim inFile As String = "D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String = "D:\\output.pdf"   'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
fileSecurity.EncryptFile("userpass","ownerpass",DocumentPrivilege.Print,KeySize.x256,Algorithm.AES)
```

### Ayrıca Bakınız

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* enum [Algorithm](../../algorithm/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)