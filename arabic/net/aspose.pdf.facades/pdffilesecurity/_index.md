---
title: PdfFileSecurity
second_title: Aspose.PDF لمرجع .NET API
description: يمثل تشفير أو فك تشفير ملف Pdf مع المالك أو كلمة مرور المستخدم  وتغيير إعداد الأمان وكلمة المرور.
type: docs
weight: 2560
url: /ar/net/aspose.pdf.facades/pdffilesecurity/
---
## PdfFileSecurity class

يمثل تشفير أو فك تشفير ملف Pdf مع المالك أو كلمة مرور المستخدم ، وتغيير إعداد الأمان وكلمة المرور.

```csharp
public sealed class PdfFileSecurity : SaveableFacade
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [PdfFileSecurity](pdffilesecurity#constructor)() | تهيئة كائن PdfFileSecurity. |
| [PdfFileSecurity](pdffilesecurity#constructor_1)(Document) | تهيئة جديد[`PdfFileSecurity`](../pdffilesecurity) كائن على قاعدة*document* . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | الحصول على واجهة المستند التي تعمل عليها. |
| [LastException](../../aspose.pdf.facades/pdffilesecurity/lastexception) { get; } | إرجاع الاستثناء الذي تم طرحه بواسطة العملية الأخيرة. |

## طُرق

| اسم | وصف |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | تهيئة الواجهة . |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf#bindpdf_1)(Stream) | تهيئة الواجهة . |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf#bindpdf_2)(string) | تهيئة الواجهة . |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword#changepassword)(string, string, string) | تغيير كلمة مرور المستخدم وكلمة مرور المالك بواسطة كلمة مرور المالك ، مع الاحتفاظ بإعدادات الأمان الأصلية. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغة أو فارغة. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو فارغة. يطرح استثناءً إذا فشلت العملية. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword#changepassword_1)(string, string, string, DocumentPrivilege, KeySize) | يغير كلمة مرور المستخدم وكلمة المرور بواسطة كلمة مرور المالك ، ويسمح بإعادة تعيين Pdf Documentnent security. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغة أو فارغة. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو فارغة. يطرح استثناءً إذا فشلت العملية. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword#changepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | يغير كلمة مرور المستخدم وكلمة المرور بواسطة كلمة مرور المالك ، ويسمح بإعادة تعيين Pdf Documentnent security. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغة أو فارغة. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو فارغة . هناك 6 مجموعات محتملة من قيم KeySize والخوارزمية. ومع ذلك (KeySize.x40، Algorithm.AES) و (KeySize.x256، Algorithm.RC4) غير صالحين وسيتم تشغيل استثناء المقابل إذا واجهت المجموعة هذه المجموعة . يطرح استثناءً إذا فشلت العملية. |
| override [Close](../../aspose.pdf.facades/pdffilesecurity/close)() | إغلاق الواجهة . |
| [DecryptFile](../../aspose.pdf.facades/pdffilesecurity/decryptfile)(string) | يفك تشفير مستند Pdf المشفر بواسطة كلمة مرور المالك. إذا لم يكن المستند يحتوي على كلمة مرور المالك ، فيُسمح باستخدام كلمة مرور المستخدم. يطرح استثناءً إذا فشلت العملية . |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | التخلص من الواجهة . |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile#encryptfile)(string, string, DocumentPrivilege, KeySize) | تشفير ملف Pdf باستخدام كلمة مرور المستخدم وكلمة مرور المالك وتعيين امتيازات المستند للوصول . يمكن أن تكون كلمة مرور المستخدم وكلمة مرور المالك فارغة أو فارغة. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور مالك الإدخال فارغة أو فارغة . يتم استثناء إذا فشلت العملية. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile#encryptfile_1)(string, string, DocumentPrivilege, KeySize, Algorithm) | تشفير ملف Pdf باستخدام كلمة مرور المستخدم وكلمة مرور المالك وتعيين امتيازات المستند للوصول . يمكن أن تكون كلمة مرور المستخدم وكلمة مرور المالك فارغة أو فارغة. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور مالك الإدخال فارغة أو فارغة . هناك 6 مجموعات محتملة من قيم KeySize والخوارزمية. ومع ذلك (KeySize.x40، Algorithm.AES) و (KeySize.x256، Algorithm.RC4) غير صالحين وسيتم تشغيل استثناء المقابل إذا واجهت المجموعة هذه المجموعة . يطرح استثناءً إذا فشلت العملية. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(Stream) | يحفظ مستند PDF في التدفق المحدد. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(string) | يحفظ مستند PDF في الملف المحدد. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege#setprivilege)(DocumentPrivilege) | تعيين أمان ملف Pdf مع كلمات مرور فارغة للمستخدم / المالك. ستتم إضافة كلمة مرور المالك بسلسلة عشوائية. يطرح استثناءً إذا فشلت العملية. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege#setprivilege_1)(string, string, DocumentPrivilege) | يعين أمان ملف Pdf بكلمة المرور الأصلية. يطرح استثناءً إذا فشلت العملية. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword#trychangepassword)(string, string, string) | تغيير كلمة مرور المستخدم وكلمة مرور المالك بواسطة كلمة مرور المالك ، مع الاحتفاظ بإعدادات الأمان الأصلية. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغة أو فارغة. سيتم استبدال كلمة مرور المالك لا يطرح استثناء إذا فشلت العملية. بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو فارغة. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword#trychangepassword_1)(string, string, string, DocumentPrivilege, KeySize) | يغير كلمة مرور المستخدم وكلمة المرور بواسطة كلمة مرور المالك ، ويسمح بإعادة تعيين Pdf Documentnent security. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغة أو فارغة. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو فارغة. لا يطرح استثناءً إذا فشلت العملية. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword#trychangepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | يغير كلمة مرور المستخدم وكلمة المرور بواسطة كلمة مرور المالك ، ويسمح بإعادة تعيين Pdf Documentnent security. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغة أو فارغة. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو فارغة . هناك 6 مجموعات محتملة من قيم KeySize والخوارزمية. ومع ذلك (KeySize.x40، Algorithm.AES) و (KeySize.x256، Algorithm.RC4) غير صالحين وسيتم تشغيل استثناء المقابل إذا واجهت المجموعة هذه المجموعة . لا تطرح استثناءً إذا فشلت العملية. |
| [TryDecryptFile](../../aspose.pdf.facades/pdffilesecurity/trydecryptfile)(string) | يفك تشفير مستند Pdf المشفر بواسطة كلمة مرور المالك. إذا كان المستند لا يحتوي على كلمة مرور للمالك ، يُسمح باستخدام كلمة مرور المستخدم. لا يطرح استثناءً إذا فشلت العملية. |
| [TryEncryptFile](../../aspose.pdf.facades/pdffilesecurity/tryencryptfile)(string, string, DocumentPrivilege, KeySize) | تشفير ملف Pdf باستخدام كلمة مرور المستخدم وكلمة مرور المالك وتعيين امتيازات المستند للوصول . يمكن أن تكون كلمة مرور المستخدم وكلمة مرور المالك فارغة أو فارغة. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور مالك الإدخال فارغة أو فارغة. لا يطرح استثناء إذا فشلت العملية. |
| [TrySetPrivilege](../../aspose.pdf.facades/pdffilesecurity/trysetprivilege)(string, string, DocumentPrivilege) | يعين أمان ملف Pdf بكلمة المرور الأصلية. لا يطرح استثناء إذا فشلت العملية. |

### أنظر أيضا

* class [SaveableFacade](../saveablefacade)
* مساحة الاسم [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
