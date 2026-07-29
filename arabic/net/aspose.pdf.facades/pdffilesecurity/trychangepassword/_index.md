---
title: "PdfFileSecurity.TryChangePassword"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfFileSecurity. تغير كلمة مرور المستخدم وكلمة مرور المالك باستخدام كلمة مرور المالك مع الحفاظ على إعدادات الأمان الأصلية. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغتين أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو null. لا يطرح استثناءً إذا فشلت العملية."
type: docs
weight: 90
url: /ar/net/aspose.pdf.facades/pdffilesecurity/trychangepassword/
---
## TryChangePassword(string, string, string) {#trychangepassword}

يغيّر كلمة مرور المستخدم وكلمة مرور المالك باستخدام كلمة مرور المالك، مع الحفاظ على إعدادات الأمان الأصلية. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغتين أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو null. لا يرمي استثناءً إذا فشلت العملية.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| ownerPassword | String | كلمة مرور المالك الأصلية. |
| newUserPassword | String | كلمة مرور المستخدم الجديدة. |
| newOwnerPassword | String | كلمة مرور المالك الجديدة. |

### قيمة الإرجاع

صحيح للنجاح، أو خطأ.

## أمثلة

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

### انظر أيضًا

* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize) {#trychangepassword_1}

يغيّر كلمة مرور المستخدم وكلمة المرور باستخدام كلمة مرور المالك، ويسمح بإعادة تعيين أمان مستند Pdf. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغتين أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو null. لا يرمي استثناءً إذا فشلت العملية.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, 
    string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| ownerPassword | String | كلمة مرور المالك الأصلية. |
| newUserPassword | String | كلمة مرور المستخدم الجديدة. |
| newOwnerPassword | String | كلمة مرور المالك الجديدة. |
| امتياز | DocumentPrivilege | إعادة تعيين الأمان. |
| keySize | KeySize | KeySize.x40 للتشفير 40 بت، KeySize.x128 للتشفير 128 بت وKeySize.x256 للتشفير 256 بت. |

### قيمة الإرجاع

صحيح إذا نجح، أو خطأ.

## أمثلة

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

### انظر أيضًا

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize, Algorithm) {#trychangepassword_2}

يغيّر كلمة مرور المستخدم وكلمة مرور المالك، ويسمح بإعادة تعيين أمان مستند Pdf. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغتين أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو null. هناك 6 تركيبات محتملة لقيم KeySize و Algorithm. ومع ذلك، فإن (KeySize.x40, Algorithm.AES) و (KeySize.x256, Algorithm.RC4) غير صالحة وسيتم رفع الاستثناء المناسب إذا صادف التطبيق هذه التركيبة. لا يُطلق استثناءً إذا فشلت العملية.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, 
    string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize, Algorithm cipher)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| ownerPassword | String | كلمة مرور المالك الأصلية. |
| newUserPassword | String | كلمة مرور المستخدم الجديدة. |
| newOwnerPassword | String | كلمة مرور المالك الجديدة. |
| امتياز | DocumentPrivilege | إعادة تعيين الأمان. |
| keySize | KeySize | KeySize.x40 للتشفير 40 بت، KeySize.x128 للتشفير 128 بت وKeySize.x256 للتشفير 256 بت. |
| شفرة | خوارزمية | Algorithm.AES للتشفير باستخدام خوارزمية AES أو Algorithm.RC4 لتشفير RC4. |

### قيمة الإرجاع

صحيح إذا نجح، أو خطأ.

## أمثلة

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

### انظر أيضًا

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* enum [Algorithm](../../algorithm/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


