---
title: TryChangePassword
second_title: Aspose.PDF لمرجع .NET API
description: تغيير كلمة مرور المستخدم وكلمة مرور المالك بواسطة كلمة مرور المالك  مع الاحتفاظ بإعدادات الأمان الأصلية. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغة أو فارغة. سيتم استبدال كلمة مرور المالك لا يطرح استثناء إذا فشلت العملية. بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو فارغة.
type: docs
weight: 90
url: /ar/net/aspose.pdf.facades/pdffilesecurity/trychangepassword/
---
## TryChangePassword(string, string, string) {#trychangepassword}

تغيير كلمة مرور المستخدم وكلمة مرور المالك بواسطة كلمة مرور المالك ، مع الاحتفاظ بإعدادات الأمان الأصلية. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغة أو فارغة. سيتم استبدال كلمة مرور المالك لا يطرح استثناء إذا فشلت العملية. بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو فارغة.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| ownerPassword | String | كلمة مرور المالك الأصلية. |
| newUserPassword | String | كلمة مرور مستخدم جديدة. |
| newOwnerPassword | String | كلمة مرور المالك الجديدة. |

### قيمة الإرجاع

صحيح للنجاح أو خطأ.

### أمثلة

```csharp
[C#]
 string inFile = "D:\\input.pdf"; // قد يتم إعادة تعيين TestPath.
 string outFile = "D:\\output.pdf";	// قد يتم إعادة تعيين TestPath.
 PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);		
 bool result = fileSecurity.TryChangePassword("owner","newuser","newowner");

[Visual Basic]
 Dim inFile As String = ".D:\\input.pdf"  'The TestPath may be re-assigned.'
 Dim outFile As String = "D:\\output.pdf"  'The TestPath may be re-assigned.'
 Dim fileSecurity As PdfFileSecurity = New PdfFileSecurity(inFile,outFile) 
 Dim result As Boolean = fileSecurity.TryChangePassword("owner","newuser","newowner")	
```

### أنظر أيضا

* class [PdfFileSecurity](../../pdffilesecurity)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffilesecurity)
* المجسم [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize) {#trychangepassword_1}

يغير كلمة مرور المستخدم وكلمة المرور بواسطة كلمة مرور المالك ، ويسمح بإعادة تعيين Pdf Documentnent security. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغة أو فارغة. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو فارغة. لا يطرح استثناءً إذا فشلت العملية.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, 
    string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| ownerPassword | String | كلمة مرور المالك الأصلية. |
| newUserPassword | String | كلمة مرور مستخدم جديدة. |
| newOwnerPassword | String | كلمة مرور المالك الجديدة. |
| privilege | DocumentPrivilege | إعادة تعيين الأمان. |
| keySize | KeySize | KeySize.x40 لتشفير 40 بت و KeySize.x128 لتشفير 128 بت و KeySize.x256 لتشفير 256 بت. |

### قيمة الإرجاع

صحيح للنجاح أو خطأ.

### أمثلة

```csharp
[C#]
string inFile = ".D:\\input.pdf"; // قد يتم إعادة تعيين TestPath.
string outFile = "D:\\output.pdf";	// قد يتم إعادة تعيين TestPath.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
bool result = fileSecurity.TryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.TryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256)
```

### أنظر أيضا

* class [DocumentPrivilege](../../documentprivilege)
* enum [KeySize](../../keysize)
* class [PdfFileSecurity](../../pdffilesecurity)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffilesecurity)
* المجسم [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize, Algorithm) {#trychangepassword_2}

يغير كلمة مرور المستخدم وكلمة المرور بواسطة كلمة مرور المالك ، ويسمح بإعادة تعيين Pdf Documentnent security. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغة أو فارغة. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو فارغة . هناك 6 مجموعات محتملة من قيم KeySize والخوارزمية. ومع ذلك (KeySize.x40، Algorithm.AES) و (KeySize.x256، Algorithm.RC4) غير صالحين وسيتم تشغيل استثناء المقابل إذا واجهت المجموعة هذه المجموعة . لا تطرح استثناءً إذا فشلت العملية.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, 
    string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize, Algorithm cipher)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| ownerPassword | String | كلمة مرور المالك الأصلية. |
| newUserPassword | String | كلمة مرور مستخدم جديدة. |
| newOwnerPassword | String | كلمة مرور المالك الجديدة. |
| privilege | DocumentPrivilege | إعادة تعيين الأمان. |
| keySize | KeySize | KeySize.x40 لتشفير 40 بت و KeySize.x128 لتشفير 128 بت و KeySize.x256 لتشفير 256 بت. |
| cipher | Algorithm | الخوارزمية: AES للتشفير باستخدام خوارزمية AES أو الخوارزمية. RC4 لتشفير RC4. |

### قيمة الإرجاع

صحيح للنجاح أو خطأ.

### أمثلة

```csharp
[C#]
string inFile = "D:\\input.pdf"; // قد يتم إعادة تعيين TestPath.
string outFile = "D:\\output.pdf";	// قد يتم إعادة تعيين TestPath.
PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile);	
bool result = fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);

[Visual Basic] 
Dim inFile As String =  ".D:\\input.pdf"  'The TestPath may be re-assigned.'
Dim outFile As String =  "D:\\output.pdf"  'The TestPath may be re-assigned.'
Dim fileSecurity As PdfFileSecurity =  New PdfFileSecurity(inFile,outFile) 
Dim result As Boolean = fileSecurity.ChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES)
```

### أنظر أيضا

* class [DocumentPrivilege](../../documentprivilege)
* enum [KeySize](../../keysize)
* enum [Algorithm](../../algorithm)
* class [PdfFileSecurity](../../pdffilesecurity)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdffilesecurity)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
