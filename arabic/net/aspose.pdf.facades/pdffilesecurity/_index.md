---
title: Class PdfFileSecurity
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Facades.PdfFileSecurity. تمثل تشفير أو فك تشفير ملف Pdf باستخدام كلمة مرور المالك أو المستخدم وتغيير إعدادات الأمان وكلمة المرور
type: docs
weight: 4550
url: /ar/net/aspose.pdf.facades/pdffilesecurity/
---
## PdfFileSecurity class

تمثل تشفير أو فك تشفير ملف Pdf باستخدام كلمة مرور المالك أو المستخدم، وتغيير إعدادات الأمان وكلمة المرور.

```csharp
public sealed class PdfFileSecurity : SaveableFacade
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfFileSecurity](pdffilesecurity/#constructor)() | تهيئة كائن PdfFileSecurity. |
| [PdfFileSecurity](pdffilesecurity/#constructor_1)(Document) | تهيئة كائن `PdfFileSecurity` جديد بناءً على *المستند*. |

## Properties

| Name | Description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | يحصل على واجهة المستند التي يعمل عليها. |
| [LastException](../../aspose.pdf.facades/pdffilesecurity/lastexception/) { get; } | يعيد الاستثناء الذي تم طرحه بواسطة العملية الأخيرة. |

## Methods

| Name | Description |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | يهيئ الواجهة. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf/#bindpdf_1)(Stream) | يهيئ الواجهة. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf/#bindpdf_2)(string) | يهيئ الواجهة. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword)(string, string, string) | يغير كلمة مرور المستخدم وكلمة مرور المالك بواسطة كلمة مرور المالك، ويحافظ على إعدادات الأمان الأصلية. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغة أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو null. يطرح استثناء إذا فشلت العملية. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword_1)(string, string, string, DocumentPrivilege, KeySize) | يغير كلمة مرور المستخدم وكلمة المرور بواسطة كلمة مرور المالك، ويسمح بإعادة تعيين أمان مستند Pdf. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغة أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو null. يطرح استثناء إذا فشلت العملية. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | يغير كلمة مرور المستخدم وكلمة المرور بواسطة كلمة مرور المالك، ويسمح بإعادة تعيين أمان مستند Pdf. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغة أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو null. هناك 6 تركيبات ممكنة من قيم KeySize و Algorithm. ومع ذلك، فإن (KeySize.x40، Algorithm.AES) و (KeySize.x256، Algorithm.RC4) غير صالحة وسيتم رفع استثناء إذا واجهت المجموعة. يطرح استثناء إذا فشلت العملية. |
| override [Close](../../aspose.pdf.facades/pdffilesecurity/close/)() | يغلق الواجهة. |
| [DecryptFile](../../aspose.pdf.facades/pdffilesecurity/decryptfile/)(string) | يفك تشفير مستند Pdf مشفر بواسطة كلمة مرور المالك. إذا لم يكن لدى المستند كلمة مرور المالك، يُسمح باستخدام كلمة مرور المستخدم. يطرح استثناء إذا فشلت العملية. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | يتخلص من الواجهة. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile/#encryptfile)(string, string, DocumentPrivilege, KeySize) | يشفر ملف Pdf باستخدام كلمة مرور المستخدم وكلمة مرور المالك ويحدد صلاحيات الوصول للمستند. يمكن أن تكون كلمة مرور المستخدم وكلمة مرور المالك فارغة أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك المدخلة فارغة أو null. يطرح استثناء إذا فشلت العملية. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile/#encryptfile_1)(string, string, DocumentPrivilege, KeySize, Algorithm) | يشفر ملف Pdf باستخدام كلمة مرور المستخدم وكلمة مرور المالك ويحدد صلاحيات الوصول للمستند. يمكن أن تكون كلمة مرور المستخدم وكلمة مرور المالك فارغة أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك المدخلة فارغة أو null. هناك 6 تركيبات ممكنة من قيم KeySize و Algorithm. ومع ذلك، فإن (KeySize.x40، Algorithm.AES) و (KeySize.x256، Algorithm.RC4) غير صالحة وسيتم رفع استثناء إذا واجهت المجموعة. يطرح استثناء إذا فشلت العملية. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | يحفظ مستند PDF إلى التدفق المحدد. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | يحفظ مستند PDF إلى الملف المحدد. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege/#setprivilege)(DocumentPrivilege) | يحدد أمان ملف Pdf بكلمات مرور مستخدم/مالك فارغة. سيتم إضافة كلمة مرور المالك بواسطة سلسلة عشوائية. يطرح استثناء إذا فشلت العملية. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege/#setprivilege_1)(string, string, DocumentPrivilege) | يحدد أمان ملف Pdf بكلمة المرور الأصلية. يطرح استثناء إذا فشلت العملية. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword)(string, string, string) | يغير كلمة مرور المستخدم وكلمة مرور المالك بواسطة كلمة مرور المالك، ويحافظ على إعدادات الأمان الأصلية. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغة أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو null. لا يطرح استثناء إذا فشلت العملية. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword_1)(string, string, string, DocumentPrivilege, KeySize) | يغير كلمة مرور المستخدم وكلمة المرور بواسطة كلمة مرور المالك، ويسمح بإعادة تعيين أمان مستند Pdf. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغة أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو null. لا يطرح استثناء إذا فشلت العملية. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | يغير كلمة مرور المستخدم وكلمة المرور بواسطة كلمة مرور المالك، ويسمح بإعادة تعيين أمان مستند Pdf. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغة أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو null. هناك 6 تركيبات ممكنة من قيم KeySize و Algorithm. ومع ذلك، فإن (KeySize.x40، Algorithm.AES) و (KeySize.x256، Algorithm.RC4) غير صالحة وسيتم رفع استثناء إذا واجهت المجموعة. لا يطرح استثناء إذا فشلت العملية. |
| [TryDecryptFile](../../aspose.pdf.facades/pdffilesecurity/trydecryptfile/)(string) | يفك تشفير مستند Pdf مشفر بواسطة كلمة مرور المالك. إذا لم يكن لدى المستند كلمة مرور المالك، يُسمح باستخدام كلمة مرور المستخدم. لا يطرح استثناء إذا فشلت العملية. |
| [TryEncryptFile](../../aspose.pdf.facades/pdffilesecurity/tryencryptfile/)(string, string, DocumentPrivilege, KeySize) | يشفر ملف Pdf باستخدام كلمة مرور المستخدم وكلمة مرور المالك ويحدد صلاحيات الوصول للمستند. يمكن أن تكون كلمة مرور المستخدم وكلمة مرور المالك فارغة أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك المدخلة فارغة أو null. لا يطرح استثناء إذا فشلت العملية. |
| [TrySetPrivilege](../../aspose.pdf.facades/pdffilesecurity/trysetprivilege/)(string, string, DocumentPrivilege) | يحدد أمان ملف Pdf بكلمة المرور الأصلية. لا يطرح استثناء إذا فشلت العملية. |

### See Also

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)