---
title: PdfFileSecurity.TryChangePassword
second_title: Aspose.PDF for .NET API Reference
description: PdfFileSecurity metodu. Kullanıcı şifresini ve sahibi şifresini değiştirir, sahibi şifresi orijinal güvenlik ayarlarını korur. Yeni kullanıcı şifresi ve yeni sahibi şifresi null veya boş olabilir. Yeni sahibi şifresi null veya boşsa, sahibi şifresi rastgele bir dize ile değiştirilir. İşlem başarısız olursa bir istisna fırlatmaz.
type: docs
weight: 90
url: /tr/net/aspose.pdf.facades/pdffilesecurity/trychangepassword/
---
## TryChangePassword(string, string, string) {#trychangepassword}

Kullanıcı şifresini ve sahibi şifresini değiştirir, sahibi şifresi orijinal güvenlik ayarlarını korur. Yeni kullanıcı şifresi ve yeni sahibi şifresi null veya boş olabilir. Yeni sahibi şifresi null veya boşsa, sahibi şifresi rastgele bir dize ile değiştirilir. İşlem başarısız olursa bir istisna fırlatmaz.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ownerPassword | String | Orijinal sahibi şifresi. |
| newUserPassword | String | Yeni kullanıcı şifresi. |
| newOwnerPassword | String | Yeni sahibi şifresi. |

### Dönüş Değeri

Başarı için true, ya da false.

## Örnekler

```csharp
[C#]
 string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
 string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
 bool result = fileSecurity.TryChangePassword("owner","newuser","newowner");

[Visual Basic]
 Dim inFile As String = ".D:\\input.pdf"  'The TestPath may be re-assigned.'
 Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
 Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
 Dim result As Boolean = fileSecurity.TryChangePassword("owner","newuser","newowner")	
```

### Ayrıca Bakınız

* sınıf [PdfFileSecurity](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize) {#trychangepassword_1}

Kullanıcı şifresini ve sahibi şifresini değiştirir, Pdf belgesi güvenliğini sıfırlamaya izin verir. Yeni kullanıcı şifresi ve yeni sahibi şifresi null veya boş olabilir. Yeni sahibi şifresi null veya boşsa, sahibi şifresi rastgele bir dize ile değiştirilir. İşlem başarısız olursa bir istisna fırlatmaz.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, 
    string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ownerPassword | String | Orijinal sahibi şifresi. |
| newUserPassword | String | Yeni kullanıcı şifresi. |
| newOwnerPassword | String | Yeni sahibi şifresi. |
| privilege | DocumentPrivilege | Güvenliği sıfırlama. |
| keySize | KeySize | 40 bit şifreleme için KeySize.x40, 128 bit şifreleme için KeySize.x128 ve 256 bit şifreleme için KeySize.x256. |

### Dönüş Değeri

Başarı için true, ya da false.

## Örnekler

```csharp
[C#]
string inFile = ".D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
bool result = fileSecurity.TryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256)
```

### Ayrıca Bakınız

* sınıf [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* sınıf [PdfFileSecurity](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize, Algorithm) {#trychangepassword_2}

Kullanıcı şifresini ve sahibi şifresini değiştirir, Pdf belgesi güvenliğini sıfırlamaya izin verir. Yeni kullanıcı şifresi ve yeni sahibi şifresi null veya boş olabilir. Yeni sahibi şifresi null veya boşsa, sahibi şifresi rastgele bir dize ile değiştirilir. KeySize ve Algorithm değerlerinin 6 olası kombinasyonu vardır. Ancak (KeySize.x40, Algorithm.AES) ve (KeySize.x256, Algorithm.RC4) geçersizdir ve bu kombinasyonla karşılaşılırsa ilgili istisna fırlatılacaktır. İşlem başarısız olursa bir istisna fırlatmaz.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, 
    string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize, Algorithm cipher)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ownerPassword | String | Orijinal sahibi şifresi. |
| newUserPassword | String | Yeni kullanıcı şifresi. |
| newOwnerPassword | String | Yeni sahibi şifresi. |
| privilege | DocumentPrivilege | Güvenliği sıfırlama. |
| keySize | KeySize | 40 bit şifreleme için KeySize.x40, 128 bit şifreleme için KeySize.x128 ve 256 bit şifreleme için KeySize.x256. |
| cipher | Algorithm | AES algoritmasını kullanarak şifrelemek için Algorithm.AES veya RC4 şifrelemesi için Algorithm.RC4. |

### Dönüş Değeri

Başarı için true, ya da false.

## Örnekler

```csharp
[C#]
string inFile = "D:\\input.pdf"; //The TestPath may be re-assigned.
string outFile = "D:\\output.pdf";	//The TestPath may be re-assigned.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
bool result = fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES)
```

### Ayrıca Bakınız

* sınıf [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* enum [Algorithm](../../algorithm/)
* sınıf [PdfFileSecurity](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)