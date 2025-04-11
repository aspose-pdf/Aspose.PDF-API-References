---
title: PdfFileSecurity.ChangePassword
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSecurity yöntemi. Kullanıcı şifresini ve sahip şifresini değiştirir, sahip şifresi orijinal güvenlik ayarlarını korur. Yeni kullanıcı şifresi ve yeni sahip şifresi null veya boş olabilir. Yeni sahip şifresi null veya boşsa, sahip şifresi rastgele bir dize ile değiştirilir. İşlem başarısız olursa bir istisna fırlatır.
type: docs
weight: 40
url: /tr/net/aspose.pdf.facades/pdffilesecurity/changepassword/
---
## ChangePassword(string, string, string) {#changepassword}

Kullanıcı şifresini ve sahip şifresini değiştirir, orijinal güvenlik ayarlarını korur. Yeni kullanıcı şifresi ve yeni sahip şifresi null veya boş olabilir. Yeni sahip şifresi null veya boşsa, sahip şifresi rastgele bir dize ile değiştirilir. İşlem başarısız olursa bir istisna fırlatır.

```csharp
public bool ChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ownerPassword | String | Orijinal sahip şifresi. |
| newUserPassword | String | Yeni kullanıcı şifresi. |
| newOwnerPassword | String | Yeni sahip şifresi. |

### Dönüş Değeri

Başarı için True.

## Örnekler

```csharp
[C#]
 string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
 string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
 fileSecurity.ChangePassword("owner","newuser","newowner");

[Visual Basic]
 Dim inFile As String = ".D:\\input.pdf"  'The TestPath may be re-assigned.'
 Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
 Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
 fileSecurity.ChangePassword("owner","newuser","newowner")	
```

### Ayrıca Bakınız

* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ChangePassword(string, string, string, DocumentPrivilege, KeySize) {#changepassword_1}

Kullanıcı şifresini ve sahip şifresini değiştirir, Pdf belgesi güvenliğini sıfırlamaya izin verir. Yeni kullanıcı şifresi ve yeni sahip şifresi null veya boş olabilir. Yeni sahip şifresi null veya boşsa, sahip şifresi rastgele bir dize ile değiştirilir. İşlem başarısız olursa bir istisna fırlatır.

```csharp
public bool ChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword, 
    DocumentPrivilege privilege, KeySize keySize)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ownerPassword | String | Orijinal sahip şifresi. |
| newUserPassword | String | Yeni kullanıcı şifresi. |
| newOwnerPassword | String | Yeni sahip şifresi. |
| privilege | DocumentPrivilege | Güvenliği sıfırlama. |
| keySize | KeySize | 40 bit şifreleme için KeySize.x40, 128 bit şifreleme için KeySize.x128 ve 256 bit şifreleme için KeySize.x256. |

### Dönüş Değeri

Başarı için True.

## Örnekler

```csharp
[C#]
string inFile = ".D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256)
```

### Ayrıca Bakınız

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ChangePassword(string, string, string, DocumentPrivilege, KeySize, Algorithm) {#changepassword_2}

Kullanıcı şifresini ve sahip şifresini değiştirir, Pdf belgesi güvenliğini sıfırlamaya izin verir. Yeni kullanıcı şifresi ve yeni sahip şifresi null veya boş olabilir. Yeni sahip şifresi null veya boşsa, sahip şifresi rastgele bir dize ile değiştirilir. KeySize ve Algorithm değerlerinin 6 olası kombinasyonu vardır. Ancak (KeySize.x40, Algorithm.AES) ve (KeySize.x256, Algorithm.RC4) geçersizdir ve bu kombinasyonla karşılaşılırsa ilgili bir istisna fırlatılacaktır. İşlem başarısız olursa bir istisna fırlatır.

```csharp
public bool ChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword, 
    DocumentPrivilege privilege, KeySize keySize, Algorithm cipher)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ownerPassword | String | Orijinal sahip şifresi. |
| newUserPassword | String | Yeni kullanıcı şifresi. |
| newOwnerPassword | String | Yeni sahip şifresi. |
| privilege | DocumentPrivilege | Güvenliği sıfırlama. |
| keySize | KeySize | 40 bit şifreleme için KeySize.x40, 128 bit şifreleme için KeySize.x128 ve 256 bit şifreleme için KeySize.x256. |
| cipher | Algorithm | AES algoritmasını kullanarak şifrelemek için Algorithm.AES veya RC4 şifrelemesi için Algorithm.RC4. |

### Dönüş Değeri

Başarı için True.

## Örnekler

```csharp
[C#]
string inFile = ".D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES)
```

### Ayrıca Bakınız

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* enum [Algorithm](../../algorithm/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)