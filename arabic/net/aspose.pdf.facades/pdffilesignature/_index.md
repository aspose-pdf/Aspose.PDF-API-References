---
title: PdfFileSignature
second_title: Aspose.PDF لمرجع .NET API
description: يمثل فئة لتوقيع ملف pdf بشهادة.
type: docs
weight: 2570
url: /ar/net/aspose.pdf.facades/pdffilesignature/
---
## PdfFileSignature class

يمثل فئة لتوقيع ملف pdf بشهادة.

```csharp
public sealed class PdfFileSignature : SaveableFacade
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [PdfFileSignature](pdffilesignature#constructor)() | مُنشئ فئة PdfFileSignature. |
| [PdfFileSignature](pdffilesignature#constructor_1)(Document) | تهيئة جديد[`PdfFileSignature`](../pdffilesignature) كائن على قاعدة*document* . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | الحصول على واجهة المستند التي تعمل عليها. |
| [IsCertified](../../aspose.pdf.facades/pdffilesignature/iscertified) { get; } | الحصول على العلامة التي تحدد ما إذا كان المستند معتمدًا أم لا. |
| [IsLtvEnabled](../../aspose.pdf.facades/pdffilesignature/isltvenabled) { get; } | الحصول على علامة تمكين LTV . |
| [SignatureAppearance](../../aspose.pdf.facades/pdffilesignature/signatureappearance) { get; set; } | لتعيين مظهر رسومي للتوقيع أو الحصول عليه. تمثل قيمة الخاصية اسم ملف الصورة. |
| [SignatureAppearanceStream](../../aspose.pdf.facades/pdffilesignature/signatureappearancestream) { get; set; } | لتعيين مظهر رسومي للتوقيع أو الحصول عليه. تمثل قيمة الخاصية تدفق الصورة. |

## طُرق

| اسم | وصف |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | تهيئة الواجهة . |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf#bindpdf_1)(Stream) | يربط دفق PDF للتحرير. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf#bindpdf_2)(string) | يربط ملف PDF للتحرير. |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify#certify_1)(string, DocMDPSignature) | قم بتوثيق المستند بتوقيع MDP الذي تم وضعه في حقل التوقيع المقدم بالفعل. قبل التوقيع يجب أن يكون حقل التوقيع فارغًا ، أي يجب ألا يحتوي الحقل على قاموس التوقيع. ختم التوقيع ، يتم أخذ الصفحة المقابلة والمستطيل من حقل التوقيع الموجود باسم التوقيع (انظر معلمة sigName) . |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify#certify)(int, string, string, string, bool, Rectangle, DocMDPSignature) | المصادقة على المستند بتوقيع MDP . يجب توفير بيانات مثل سبب التوقيع والاتصال والموقع من خلال الخصائص المقابلة لكائن التوقيع sig. |
| override [Close](../../aspose.pdf.facades/pdffilesignature/close)() | إغلاق الواجهة . |
| [ContainsSignature](../../aspose.pdf.facades/pdffilesignature/containssignature)() | للتحقق مما إذا كان ملف pdf يحتوي على توقيع رقمي أم لا. |
| [ContainsUsageRights](../../aspose.pdf.facades/pdffilesignature/containsusagerights)() | للتحقق مما إذا كان لقوات الدفاع الشعبي حقوق استخدام أم لا. |
| [CoversWholeDocument](../../aspose.pdf.facades/pdffilesignature/coverswholedocument)(string) | للتحقق مما إذا كان التوقيع يغطي المستند بأكمله. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | التخلص من الواجهة . |
| [ExtractCertificate](../../aspose.pdf.facades/pdffilesignature/extractcertificate)(string) | استخراج شهادة X.509 المفردة للتوقيع كتدفق. |
| [ExtractImage](../../aspose.pdf.facades/pdffilesignature/extractimage)(string) | استخراج صورة التوقيع. |
| [GetAccessPermissions](../../aspose.pdf.facades/pdffilesignature/getaccesspermissions)() | إرجاع قيمة أذونات الوصول للمستند المعتمد من خلال نوع توقيع MDP. |
| [GetBlankSignNames](../../aspose.pdf.facades/pdffilesignature/getblanksignnames)() | يحصل على أسماء جميع حقول التوقيع الفارغة. |
| [GetContactInfo](../../aspose.pdf.facades/pdffilesignature/getcontactinfo)(string) | يحصل على معلومات الاتصال للتوقيع. |
| [GetDateTime](../../aspose.pdf.facades/pdffilesignature/getdatetime)(string) | يحصل على تاريخ التوقيع. |
| [GetLocation](../../aspose.pdf.facades/pdffilesignature/getlocation)(string) | الحصول على موقع التوقيع. |
| [GetReason](../../aspose.pdf.facades/pdffilesignature/getreason)(string) | يحصل على سبب التوقيع. |
| [GetRevision](../../aspose.pdf.facades/pdffilesignature/getrevision)(string) | يحصل على مراجعة التوقيع. |
| [GetSignerName](../../aspose.pdf.facades/pdffilesignature/getsignername)(string) | يحصل على اسم الشخص أو المنظمة التي وقعت على وثيقة pdf. |
| [GetSignNames](../../aspose.pdf.facades/pdffilesignature/getsignnames)(bool) | يحصل على أسماء جميع التوقيعات غير الفارغة. |
| [GetTotalRevision](../../aspose.pdf.facades/pdffilesignature/gettotalrevision)() | يحصل على مراجعة toltal . |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature#removesignature)(string) | إزالة التوقيع حسب اسم التوقيع. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature#removesignature_1)(string, bool) | يزيل التوقيع حسب اسم التوقيع. |
| [RemoveUsageRights](../../aspose.pdf.facades/pdffilesignature/removeusagerights)() | يزيل إدخال حقوق الاستخدام . |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save#save_1)(Stream) | يحفظ نتيجة PDF للدفق . |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save#save_2)(string) | يحفظ نتيجة PDF في ملف . |
| [SetCertificate](../../aspose.pdf.facades/pdffilesignature/setcertificate)(string, string) | تعيين ملف الشهادة وكلمة المرور لإجراء التوقيع. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_4)(string, Signature) | قم بتوقيع المستند بتوقيع النوع المحدد والذي تم وضعه في حقل التوقيع المقدم بالفعل. قبل التوقيع يجب أن يكون حقل التوقيع فارغًا ، أي يجب ألا يحتوي الحقل على قاموس التوقيع. لختم التوقيع ، يتم أخذ الصفحة المقابلة والمستطيل من حقل التوقيع الذي تم العثور عليه بواسطة اسم التوقيع (انظر معلمة SigName) . يجب توفير البيانات مثل سبب التوقيع والاتصال والموقع من خلال الخصائص المقابلة لكائن التوقيع sig. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign)(int, bool, Rectangle, Signature) | وقّع على المستند باستخدام نوع التوقيع المحدد. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_5)(string, string, string, string, Signature) | قم بتوقيع المستند بتوقيع النوع المحدد والذي تم وضعه في حقل التوقيع المقدم بالفعل. قبل التوقيع يجب أن يكون حقل التوقيع فارغًا ، أي يجب ألا يحتوي الحقل على قاموس التوقيع. لختم التوقيع ، يتم أخذ الصفحة المقابلة والمستطيل من حقل التوقيع الموجود باسم التوقيع (انظر معلمة SigName) . |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_1)(int, string, string, string, bool, Rectangle) | قم بعمل توقيع على مستند pdf . |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_2)(int, string, string, string, bool, Rectangle, Signature) | وقّع على المستند باستخدام نوع التوقيع المحدد. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_3)(int, string, string, string, string, bool, Rectangle, Signature) | قم بتوقيع المستند بتوقيع النوع المحدد والذي تم وضعه في حقل التوقيع المقدم بالفعل. قبل التوقيع يجب أن يحتوي مستند pdf بالفعل على حقل توقيع ، يتم أخذ الصفحة المقابلة والمستطيل من حقل التوقيع الذي تم العثور عليه بواسطة اسم التوقيع (انظر معلمة SigName) . |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature)(string) | للتحقق من صلاحية التوقيع. |
| [VerifySigned](../../aspose.pdf.facades/pdffilesignature/verifysigned)(string) | للتحقق من صلاحية التوقيع. |

### أنظر أيضا

* class [SaveableFacade](../saveablefacade)
* مساحة الاسم [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* المجسم [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
