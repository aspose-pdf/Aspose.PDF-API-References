---
title: "الفئة PdfFileSecurity"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Facades.PdfFileSecurity. تمثّل تشفير أو فك تشفير ملف Pdf باستخدام كلمة مرور المالك أو المستخدم مع تغيير إعدادات الأمان وكلمة المرور."
type: docs
weight: 4670
url: /ar/net/aspose.pdf.facades/pdffilesecurity/
---
## PdfFileSecurity class

يمثل تشفير أو فك تشفير ملف Pdf باستخدام كلمة مرور المالك أو المستخدم، وتغيير إعدادات الأمان وكلمة المرور.

```csharp
public sealed class PdfFileSecurity : SaveableFacade
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PdfFileSecurity](pdffilesecurity/#constructor)() | تهيئة كائن PdfFileSecurity. |
| [PdfFileSecurity](pdffilesecurity/#constructor_1)(Document) | يُنشئ كائن `PdfFileSecurity` جديد استنادًا إلى *document*. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | يحصل على واجهة المستند التي يتم العمل عليها. |
| [LastException](../../aspose.pdf.facades/pdffilesecurity/lastexception/) { get; } | يرجع الاستثناء الذي تم إلقاؤه بواسطة العملية الأخيرة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | يُهيئ الواجهة. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf/#bindpdf_1)(Stream) | يُهيئ الواجهة. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesecurity/bindpdf/#bindpdf_2)(string) | يُهيئ الواجهة. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword)(string, string, string) | يغيّر كلمة مرور المستخدم وكلمة مرور المالك باستخدام كلمة مرور المالك، مع الحفاظ على إعدادات الأمان الأصلية. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغتين أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو null. يرمي استثناءً إذا فشلت العملية. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword_1)(string, string, string, DocumentPrivilege, KeySize) | يغيّر كلمة مرور المستخدم وكلمة المرور باستخدام كلمة مرور المالك، ويسمح بإعادة تعيين أمان مستند Pdf. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغتين أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو null. يرمي استثناءً إذا فشلت العملية. |
| [ChangePassword](../../aspose.pdf.facades/pdffilesecurity/changepassword/#changepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | يغيّر كلمة مرور المستخدم وكلمة المرور باستخدام كلمة مرور المالك، ويسمح بإعادة تعيين أمان مستند Pdf. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغتين أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو null. هناك 6 تركيبات محتملة لقيم KeySize و Algorithm. ومع ذلك، التركيبة (KeySize.x40, Algorithm.AES) و (KeySize.x256, Algorithm.RC4) غير صالحة وسيتم رفع استثناء مناسب إذا واجهت الأداة هذه التركيبة. يرمي استثناءً إذا فشلت العملية. |
| override [Close](../../aspose.pdf.facades/pdffilesecurity/close/)() | يغلق الواجهة. |
| [DecryptFile](../../aspose.pdf.facades/pdffilesecurity/decryptfile/)(string) | يفك تشفير مستند Pdf مشفر باستخدام كلمة مرور المالك. إذا لم يكن للمستند كلمة مرور مالك، يُسمح باستخدام كلمة مرور المستخدم. يرمي استثناءً إذا فشلت العملية. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | يتخلص من الواجهة. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile/#encryptfile)(string, string, DocumentPrivilege, KeySize) | يشفّر ملف Pdf باستخدام كلمة مرور المستخدم وكلمة مرور المالك ويضبط صلاحيات الوصول للمستند. يمكن أن تكون كلمة مرور المستخدم وكلمة مرور المالك فارغتين أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك المدخلة فارغة أو null. يرمي استثناءً إذا فشلت العملية. |
| [EncryptFile](../../aspose.pdf.facades/pdffilesecurity/encryptfile/#encryptfile_1)(string, string, DocumentPrivilege, KeySize, Algorithm) | يشفّر ملف Pdf باستخدام كلمة مرور المستخدم وكلمة مرور المالك ويضبط صلاحيات الوصول للمستند. يمكن أن تكون كلمة مرور المستخدم وكلمة مرور المالك فارغتين أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك المدخلة فارغة أو null. هناك 6 تركيبات محتملة لقيم KeySize و Algorithm. ومع ذلك، التركيبة (KeySize.x40, Algorithm.AES) و (KeySize.x256, Algorithm.RC4) غير صالحة وسيتم رفع استثناء مناسب إذا واجهت الأداة هذه التركيبة. يرمي استثناءً إذا فشلت العملية. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | يحفظ مستند PDF إلى الدفق المحدد. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | يحفظ مستند PDF إلى الملف المحدد. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege/#setprivilege)(DocumentPrivilege) | يضبط أمان ملف Pdf باستخدام كلمات مرور المستخدم/المالك فارغة. سيتم إضافة كلمة مرور المالك بسلسلة عشوائية. يرمي استثناءً إذا فشلت العملية. |
| [SetPrivilege](../../aspose.pdf.facades/pdffilesecurity/setprivilege/#setprivilege_1)(string, string, DocumentPrivilege) | يضبط أمان ملف Pdf باستخدام كلمة المرور الأصلية. يرمي استثناءً إذا فشلت العملية. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword)(string, string, string) | يغيّر كلمة مرور المستخدم وكلمة مرور المالك باستخدام كلمة مرور المالك، مع الحفاظ على إعدادات الأمان الأصلية. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغتين أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو null. لا يرمي استثناءً إذا فشلت العملية. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword_1)(string, string, string, DocumentPrivilege, KeySize) | يغيّر كلمة مرور المستخدم وكلمة المرور باستخدام كلمة مرور المالك، ويسمح بإعادة تعيين أمان مستند Pdf. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغتين أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو null. لا يرمي استثناءً إذا فشلت العملية. |
| [TryChangePassword](../../aspose.pdf.facades/pdffilesecurity/trychangepassword/#trychangepassword_2)(string, string, string, DocumentPrivilege, KeySize, Algorithm) | يغيّر كلمة مرور المستخدم وكلمة مرور المالك، ويسمح بإعادة تعيين أمان مستند Pdf. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغتين أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو null. هناك 6 تركيبات محتملة لقيم KeySize و Algorithm. ومع ذلك، فإن (KeySize.x40, Algorithm.AES) و (KeySize.x256, Algorithm.RC4) غير صالحة وسيتم رفع الاستثناء المناسب إذا صادف التطبيق هذه التركيبة. لا يُطلق استثناءً إذا فشلت العملية. |
| [TryDecryptFile](../../aspose.pdf.facades/pdffilesecurity/trydecryptfile/)(string) | يفك تشفير مستند Pdf مشفر باستخدام كلمة مرور المالك. إذا لم يكن للمستند كلمة مرور مالك، يُسمح باستخدام كلمة مرور المستخدم. لا يُطلق استثناءً إذا فشلت العملية. |
| [TryEncryptFile](../../aspose.pdf.facades/pdffilesecurity/tryencryptfile/)(string, string, DocumentPrivilege, KeySize) | يشفّر ملف Pdf باستخدام كلمة مرور المستخدم وكلمة مرور المالك ويضبط صلاحيات المستند للوصول. يمكن أن تكون كلمة مرور المستخدم وكلمة مرور المالك فارغتين أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك المدخلة فارغة أو null. لا يُطلق استثناءً إذا فشلت العملية. |
| [TrySetPrivilege](../../aspose.pdf.facades/pdffilesecurity/trysetprivilege/)(string, string, DocumentPrivilege) | يضبط أمان ملف Pdf باستخدام كلمة المرور الأصلية. لا يُطلق استثناءً إذا فشلت العملية. |

### انظر أيضًا

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


