---
title: PdfFileSecurity.TryChangePassword
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfFileSecurity. تغير كلمة مرور المستخدم وكلمة مرور المالك مع الحفاظ على إعدادات الأمان الأصلية. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغة أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو null. لا يتم إلقاء استثناء إذا فشل العملية.
type: docs
weight: 90
url: /ar/net/aspose.pdf.facades/pdffilesecurity/trychangepassword/
---
## TryChangePassword(string, string, string) {#trychangepassword}

تغير كلمة مرور المستخدم وكلمة مرور المالك مع الحفاظ على إعدادات الأمان الأصلية. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغة أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو null. لا يتم إلقاء استثناء إذا فشل العملية.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, string newOwnerPassword)
```

| Parameter | Type | Description |
| --- | --- | --- |
| ownerPassword | String | كلمة مرور المالك الأصلية. |
| newUserPassword | String | كلمة مرور المستخدم الجديدة. |
| newOwnerPassword | String | كلمة مرور المالك الجديدة. |

### Return Value

True للنجاح، أو false.

## Examples

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

### See Also

* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize) {#trychangepassword_1}

تغير كلمة مرور المستخدم وكلمة مرور المالك، ويسمح بإعادة تعيين أمان مستند Pdf. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغة أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو null. لا يتم إلقاء استثناء إذا فشل العملية.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, 
    string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| ownerPassword | String | كلمة مرور المالك الأصلية. |
| newUserPassword | String | كلمة مرور المستخدم الجديدة. |
| newOwnerPassword | String | كلمة مرور المالك الجديدة. |
| privilege | DocumentPrivilege | إعادة تعيين الأمان. |
| keySize | KeySize | KeySize.x40 لتشفير 40 بت، KeySize.x128 لتشفير 128 بت و KeySize.x256 لتشفير 256 بت. |

### Return Value

True للنجاح، أو false.

## Examples

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

### See Also

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## TryChangePassword(string, string, string, DocumentPrivilege, KeySize, Algorithm) {#trychangepassword_2}

تغير كلمة مرور المستخدم وكلمة مرور المالك، ويسمح بإعادة تعيين أمان مستند Pdf. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغة أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو null. هناك 6 تركيبات ممكنة من قيم KeySize و Algorithm. ومع ذلك، فإن (KeySize.x40، Algorithm.AES) و (KeySize.x256، Algorithm.RC4) غير صالحة وسيتم رفع استثناء مناسب إذا واجهت المجموعة. لا يتم إلقاء استثناء إذا فشل العملية.

```csharp
public bool TryChangePassword(string ownerPassword, string newUserPassword, 
    string newOwnerPassword, DocumentPrivilege privilege, KeySize keySize, Algorithm cipher)
```

| Parameter | Type | Description |
| --- | --- | --- |
| ownerPassword | String | كلمة مرور المالك الأصلية. |
| newUserPassword | String | كلمة مرور المستخدم الجديدة. |
| newOwnerPassword | String | كلمة مرور المالك الجديدة. |
| privilege | DocumentPrivilege | إعادة تعيين الأمان. |
| keySize | KeySize | KeySize.x40 لتشفير 40 بت، KeySize.x128 لتشفير 128 بت و KeySize.x256 لتشفير 256 بت. |
| cipher | Algorithm | Algorithm.AES للتشفير باستخدام خوارزمية AES أو Algorithm.RC4 لتشفير RC4. |

### Return Value

True للنجاح، أو false.

## Examples

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

### See Also

* class [DocumentPrivilege](../../documentprivilege/)
* enum [KeySize](../../keysize/)
* enum [Algorithm](../../algorithm/)
* class [PdfFileSecurity](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)