---
title: TryChangePassword
second_title: Aspose.PDF for .NET API Referansı
description: Kullanıcı parolasını ve sahip parolasını sahip parolasıyla değiştirir orijinal güvenlik ayarlarını korur. Yeni kullanıcı parolası ve yeni sahip parolası boş veya boş olabilir. Sahip parolası değiştirilecek İşlem başarısız olursa bir istisna oluşturmaz. Yeni sahip parolası boş veya boşsa rastgele bir dizeyle.
type: docs
weight: 90
url: /tr/net/aspose.pdf.facades/pdffilesecurity/trychangepassword/
---
## TryChangePassword(string, string, string) {#trychangepassword}

Kullanıcı parolasını ve sahip parolasını sahip parolasıyla değiştirir, orijinal güvenlik ayarlarını korur. Yeni kullanıcı parolası ve yeni sahip parolası boş veya boş olabilir. Sahip parolası değiştirilecek İşlem başarısız olursa bir istisna oluşturmaz. Yeni sahip parolası boş veya boşsa rastgele bir dizeyle.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| ownerPassword | String | Orijinal Sahip şifresi. |
| newUserPassword | String | Yeni Kullanıcı şifresi. |
| newOwnerPassword | String | Yeni Sahip şifresi. |

### Geri dönüş değeri

Başarı için doğru veya yanlış.

### Örnekler

```csharp
[C#]
 string inFile = "D:\\input.pdf"; // TestPath yeniden atanabilir.
 string outFile = "D:\\output.pdf";	// TestPath yeniden atanabilir.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
 bool result = fileSecurity.TryChangePassword("owner","newuser","newowner");

[Visual Basic]
 Dim inFile As String = ".D:\\input.pdf"  'The TestPath may be re-assigned.'
 Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
 Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
 Dim result As Boolean = fileSecurity.TryChangePassword("owner","newuser","newowner")	
```

### Ayrıca bakınız

* class [PdfFileSecurity](../../pdffilesecurity)
* ad alanı [Aspose.Pdf.Facades](../../pdffilesecurity)
* toplantı [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize) {#trychangepassword_1}

Kullanıcı parolasını ve parolayı sahip parolasıyla değiştirir, Pdf belge güvenliğinin sıfırlanmasına olanak tanır. Yeni kullanıcı parolası ve yeni sahip parolası boş veya boş olabilir. Yeni sahip parolası boşsa veya boşsa sahip parolası rastgele bir dizeyle değiştirilir. İşlem başarısız olursa bir istisna oluşturmaz.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, 
    string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| ownerPassword | String | Orijinal sahip şifresi. |
| newUserPassword | String | Yeni Kullanıcı şifresi. |
| newOwnerPassword | String | Yeni Sahip şifresi. |
| privilege | DocumentPrivilege | Güvenliği sıfırlayın. |
| keySize | KeySize | 40 bit şifreleme için KeySize.x40, 128 bit şifreleme için KeySize.x128 ve 256 bit şifreleme için KeySize.x256. |

### Geri dönüş değeri

Başarı için doğru veya yanlış.

### Örnekler

```csharp
[C#]
string inFile = ".D:\\input.pdf"; // TestPath yeniden atanabilir.
string outFile = "D:\\output.pdf";	// TestPath yeniden atanabilir.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
bool result = fileSecurity.TryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256)
```

### Ayrıca bakınız

* class [DocumentPrivilege](../../documentprivilege)
* enum [KeySize](../../keysize)
* class [PdfFileSecurity](../../pdffilesecurity)
* ad alanı [Aspose.Pdf.Facades](../../pdffilesecurity)
* toplantı [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize, Algorithm) {#trychangepassword_2}

Kullanıcı parolasını ve parolayı sahip parolasıyla değiştirir, Pdf belge güvenliğinin sıfırlanmasına olanak tanır. Yeni kullanıcı parolası ve yeni sahip parolası boş veya boş olabilir. Yeni sahip parolası boşsa veya boşsa, sahip parolası rastgele bir dizeyle değiştirilecektir. KeySize ve Algorithm değerlerinin 6 olası kombinasyonu vardır. Ancak (KeySize.x40, Algorithm.AES) ve (KeySize.x256, Algorithm.RC4) geçersizdir ve kit bu kombinasyonla karşılaşırsa ilgili istisnası ortaya çıkar. İşlem başarısız olursa bir istisna oluşturmaz.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, 
    string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize, Algorithm cipher)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| ownerPassword | String | Orijinal sahip şifresi. |
| newUserPassword | String | Yeni Kullanıcı şifresi. |
| newOwnerPassword | String | Yeni Sahip şifresi. |
| privilege | DocumentPrivilege | Güvenliği sıfırlayın. |
| keySize | KeySize | 40 bit şifreleme için KeySize.x40, 128 bit şifreleme için KeySize.x128 ve 256 bit şifreleme için KeySize.x256. |
| cipher | Algorithm | AES algoritmasını kullanarak şifrelemek için Algorithm.AES veya RC4 şifrelemesi için Algorithm.RC4. |

### Geri dönüş değeri

Başarı için doğru veya yanlış.

### Örnekler

```csharp
[C#]
string inFile = "D:\\input.pdf"; // TestPath yeniden atanabilir.
string outFile = "D:\\output.pdf";	// TestPath yeniden atanabilir.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
bool result = fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES)
```

### Ayrıca bakınız

* class [DocumentPrivilege](../../documentprivilege)
* enum [KeySize](../../keysize)
* enum [Algorithm](../../algorithm)
* class [PdfFileSecurity](../../pdffilesecurity)
* ad alanı [Aspose.Pdf.Facades](../../pdffilesecurity)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
