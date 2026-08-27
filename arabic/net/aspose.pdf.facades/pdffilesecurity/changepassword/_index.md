---
title: "PdfFileSecurity.ChangePassword"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfFileSecurity. تغير كلمة مرور المستخدم وكلمة مرور المالك باستخدام كلمة مرور المالك مع الحفاظ على إعدادات الأمان الأصلية. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغتين أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو null. تُلقي استثناءً إذا فشلت العملية"
type: docs
weight: 40
url: /ar/net/aspose.pdf.facades/pdffilesecurity/changepassword/
---
## ChangePassword(string, string, string) {#changepassword}

يغيّر كلمة مرور المستخدم وكلمة مرور المالك باستخدام كلمة مرور المالك، مع الحفاظ على إعدادات الأمان الأصلية. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغتين أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو null. يرمي استثناءً إذا فشلت العملية.

```csharp
public bool ChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| ownerPassword | String | كلمة مرور المالك الأصلية. |
| newUserPassword | String | كلمة مرور المستخدم الجديدة. |
| newOwnerPassword | String | كلمة مرور المالك الجديدة. |

### قيمة الإرجاع

صحيح للنجاح.

## أمثلة

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

### انظر أيضًا

* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ChangePassword(string, string, string, DocumentPrivilege, KeySize) {#changepassword_1}

يغيّر كلمة مرور المستخدم وكلمة المرور باستخدام كلمة مرور المالك، ويسمح بإعادة تعيين أمان مستند Pdf. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغتين أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو null. يرمي استثناءً إذا فشلت العملية.

```csharp
public bool ChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword, 
    DocumentPrivilege privilege, KeySize keySize)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| ownerPassword | String | كلمة مرور المالك الأصلية. |
| newUserPassword | String | كلمة مرور المستخدم الجديدة. |
| newOwnerPassword | String | كلمة مرور المالك الجديدة. |
| امتياز | DocumentPrivilege | إعادة تعيين الأمان. |
| keySize | KeySize | KeySize.x40 للتشفير 40 بت، KeySize.x128 للتشفير 128 بت وKeySize.x256 للتشفير 256 بت. |

### قيمة الإرجاع

صحيح للنجاح.

## أمثلة

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

### انظر أيضًا

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ChangePassword(string, string, string, DocumentPrivilege, KeySize, Algorithm) {#changepassword_2}

يغيّر كلمة مرور المستخدم وكلمة المرور باستخدام كلمة مرور المالك، ويسمح بإعادة تعيين أمان مستند Pdf. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغتين أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو null. هناك 6 تركيبات محتملة لقيم KeySize و Algorithm. ومع ذلك، التركيبة (KeySize.x40, Algorithm.AES) و (KeySize.x256, Algorithm.RC4) غير صالحة وسيتم رفع استثناء مناسب إذا واجهت الأداة هذه التركيبة. يرمي استثناءً إذا فشلت العملية.

```csharp
public bool ChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword, 
    DocumentPrivilege privilege, KeySize keySize, Algorithm cipher)
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

صحيح للنجاح.

## أمثلة

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

### انظر أيضًا

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* enum [Algorithm](../../algorithm/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


