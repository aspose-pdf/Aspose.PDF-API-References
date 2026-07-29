---
title: "الفئة PdfFileSignature"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Facades.PdfFileSignature. تمثل فئة لتوقيع ملف pdf باستخدام شهادة"
type: docs
weight: 4680
url: /ar/net/aspose.pdf.facades/pdffilesignature/
---
## PdfFileSignature class

يمثل فئة لتوقيع ملف pdf باستخدام شهادة.

```csharp
public sealed class PdfFileSignature : SaveableFacade
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [PdfFileSignature](pdffilesignature/#constructor)() | المُنشئ لفئة PdfFileSignature. |
| [PdfFileSignature](pdffilesignature/#constructor_1)(Document) | يُهيئ كائنًا جديدًا `PdfFileSignature` بناءً على *المستند*. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | يحصل على واجهة المستند التي يتم العمل عليها. |
| [IsCertified](../../aspose.pdf.facades/pdffilesignature/iscertified/) { get; } | يحصل على العلامة التي تحدد ما إذا كان المستند مُعتمدًا أم لا. |
| [IsLtvEnabled](../../aspose.pdf.facades/pdffilesignature/isltvenabled/) { get; } | يحصل على علامة تمكين LTV. |
| [SignatureAppearance](../../aspose.pdf.facades/pdffilesignature/signatureappearance/) { get; set; } | يضبط أو يحصل على المظهر الرسومي للتوقيع. قيمة الخاصية تمثل اسم ملف الصورة. |
| [SignatureAppearanceStream](../../aspose.pdf.facades/pdffilesignature/signatureappearancestream/) { get; set; } | يضبط أو يحصل على المظهر الرسومي للتوقيع. قيمة الخاصية تمثل تدفق الصورة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | يُهيئ الواجهة. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_1)(Stream) | يربط تدفق Pdf للتحرير. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_2)(string) | يربط ملف Pdf للتحرير. |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify_1)(string, DocMDPSignature) | صادق المستند باستخدام توقيع MDP الموجود في حقل التوقيع الموجود مسبقًا. قبل التوقيع يجب أن يكون حقل التوقيع فارغًا، أي لا يجب أن يحتوي الحقل على قاموس توقيع. وبالتالي فإن مستند pdf يحتوي بالفعل على حقل توقيع، لا يلزم توفير مكان لتخطيط التوقيع؛ يتم أخذ الصفحة والمستطيل المقابلين من حقل التوقيع الذي يُعثر عليه باسم التوقيع (انظر معلمة sigName). |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify)(int, string, string, string, bool, Rectangle, DocMDPSignature) | صادق المستند باستخدام توقيع MDP. يجب توفير بيانات مثل سبب التوقيع، جهة الاتصال والموقع عبر الخصائص المقابلة لكائن Signature sig. |
| override [Close](../../aspose.pdf.facades/pdffilesignature/close/)() | يغلق الواجهة. |
| [ContainsSignature](../../aspose.pdf.facades/pdffilesignature/containssignature/)() | يتحقق مما إذا كان ملف pdf يحتوي على توقيع رقمي أم لا. |
| [ContainsUsageRights](../../aspose.pdf.facades/pdffilesignature/containsusagerights/)() | يتحقق مما إذا كان ملف pdf يحتوي على حقوق استخدام أم لا. |
| [CoversWholeDocument](../../aspose.pdf.facades/pdffilesignature/coverswholedocument/#coverswholedocument)(SignatureName) | يتحقق مما إذا كان التوقيع يغطي المستند بالكامل. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | يتخلص من الواجهة. |
| [ExtractCertificate](../../aspose.pdf.facades/pdffilesignature/extractcertificate/#extractcertificate)(SignatureName) | يستخرج شهادة X.509 الفردية للتوقيع كتيار. |
| [ExtractImage](../../aspose.pdf.facades/pdffilesignature/extractimage/#extractimage)(SignatureName) | يستخرج صورة التوقيع. |
| [GetAccessPermissions](../../aspose.pdf.facades/pdffilesignature/getaccesspermissions/)() | يعيد قيمة أذونات الوصول للمستند المعتمد بواسطة نوع توقيع MDP. |
| [GetBlankSignatureNames](../../aspose.pdf.facades/pdffilesignature/getblanksignaturenames/)() | يحصل على أسماء جميع حقول التوقيع الفارغة. |
| [GetContactInfo](../../aspose.pdf.facades/pdffilesignature/getcontactinfo/#getcontactinfo)(SignatureName) | يحصل على معلومات الاتصال الخاصة بالتوقيع. |
| [GetDateTime](../../aspose.pdf.facades/pdffilesignature/getdatetime/#getdatetime)(SignatureName) | يحصل على تاريخ ووقت التوقيع. |
| [GetLocation](../../aspose.pdf.facades/pdffilesignature/getlocation/#getlocation)(SignatureName) | يحصل على موقع التوقيع. |
| [GetReason](../../aspose.pdf.facades/pdffilesignature/getreason/#getreason)(SignatureName) | يحصل على سبب التوقيع. |
| [GetRevision](../../aspose.pdf.facades/pdffilesignature/getrevision/#getrevision)(SignatureName) | يحصل على مراجعة التوقيع. |
| [GetSignatureNames](../../aspose.pdf.facades/pdffilesignature/getsignaturenames/)(bool) | يحصل على أسماء جميع التوقيعات غير الفارغة. |
| [GetSignaturesInfo](../../aspose.pdf.facades/pdffilesignature/getsignaturesinfo/)() | يسترجع معلومات حول جميع خوارزميات التوقيع الموجودة في مستند PDF. |
| [GetSignerName](../../aspose.pdf.facades/pdffilesignature/getsignername/#getsignername)(SignatureName) | يحصل على اسم الشخص أو المؤسسة التي توقّع مستند PDF. |
| [GetTotalRevision](../../aspose.pdf.facades/pdffilesignature/gettotalrevision/)() | يحصل على المراجعة الإجمالية. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature)(SignatureName) | إزالة التوقيع وفقًا لاسم التوقيع. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature_1)(SignatureName, bool) | يزيل التوقيع وفقًا لاسم التوقيع. |
| [RemoveSignatures](../../aspose.pdf.facades/pdffilesignature/removesignatures/)() | يزيل جميع التوقيعات. |
| [RemoveUsageRights](../../aspose.pdf.facades/pdffilesignature/removeusagerights/)() | يزيل إدخال حقوق الاستخدام. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_1)(Stream) | يحفظ ملف PDF الناتج إلى تدفق. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_2)(string) | يحفظ ملف PDF الناتج إلى ملف. |
| [SetCertificate](../../aspose.pdf.facades/pdffilesignature/setcertificate/)(string, string) | تعيين ملف الشهادة وكلمة المرور لإجراء التوقيع. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_4)(string, Signature) | وقّع المستند باستخدام نوع التوقيع المحدد والذي يتم وضعه في حقل توقيع موجود مسبقًا. قبل التوقيع يجب أن يكون حقل التوقيع فارغًا، أي لا يجب أن يحتوي الحقل على قاموس توقيع. وبالتالي يحتوي مستند PDF بالفعل على حقل توقيع، لا تحتاج إلى تحديد مكان وضع التوقيع، حيث يتم أخذ الصفحة والمستطيل المقابلين من حقل التوقيع الذي يتم العثور عليه باسم التوقيع (انظر معلمة SigName). يجب توفير بيانات مثل سبب التوقيع، ومعلومات الاتصال، والموقع عبر الخصائص المقابلة لكائن Signature المسمى sig. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign)(int, bool, Rectangle, Signature) | وقّع المستند باستخدام نوع التوقيع المحدد. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_5)(string, string, string, string, Signature) | وقّع المستند باستخدام نوع التوقيع المحدد والذي يتم وضعه في حقل توقيع موجود مسبقًا. قبل التوقيع يجب أن يكون حقل التوقيع فارغًا، أي لا يجب أن يحتوي الحقل على قاموس توقيع. وبالتالي يحتوي مستند PDF بالفعل على حقل توقيع، لا تحتاج إلى تحديد مكان وضع التوقيع، حيث يتم أخذ الصفحة والمستطيل المقابلين من حقل التوقيع الذي يتم العثور عليه باسم التوقيع (انظر معلمة SigName). |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_1)(int, string, string, string, bool, Rectangle) | أنشئ توقيعًا على مستند PDF. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_2)(int, string, string, string, bool, Rectangle, Signature) | وقّع المستند باستخدام نوع التوقيع المحدد. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_3)(int, string, string, string, string, bool, Rectangle, Signature) | وقّع المستند باستخدام نوع التوقيع المحدد والذي يتم وضعه في حقل توقيع موجود مسبقًا. قبل التوقيع يجب أن يحتوي مستند PDF بالفعل على حقل توقيع، حيث يتم أخذ الصفحة والمستطيل المقابلين من حقل التوقيع الذي يتم العثور عليه باسم التوقيع (انظر معلمة SigName). |
| [TryExtractCertificate](../../aspose.pdf.facades/pdffilesignature/tryextractcertificate/#tryextractcertificate)(SignatureName, out Stream) | يستخرج شهادة X.509 الفردية للتوقيع كتيار. |
| [TryExtractCertificate](../../aspose.pdf.facades/pdffilesignature/tryextractcertificate/#tryextractcertificate_1)(SignatureName, out X509Certificate2) | يستخرج شهادة X.509 الفردية للتوقيع. |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature)(SignatureName) | يفحص صلاحية التوقيع. |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature_2)(SignatureName, X509Certificate2) | يفحص صلاحية التوقيع. يتم إجراء التحقق باستخدام شهادة المفتاح العام الخارجية. |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature_1)(SignatureName, ValidationOptions, out ValidationResult) | يفحص صلاحية التوقيع. |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature_3)(SignatureName, X509Certificate2, ValidationOptions, out ValidationResult) | يفحص صلاحية التوقيع. يتم إجراء التحقق باستخدام شهادة المفتاح العام الخارجية. |

### انظر أيضًا

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


