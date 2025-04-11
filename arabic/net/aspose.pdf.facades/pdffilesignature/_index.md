---
title: Class PdfFileSignature
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileSignature class. تمثل فئة لتوقيع ملف PDF باستخدام شهادة
type: docs
weight: 4560
url: /ar/net/aspose.pdf.facades/pdffilesignature/
---
## PdfFileSignature class

تمثل فئة لتوقيع ملف PDF باستخدام شهادة.

```csharp
public sealed class PdfFileSignature : SaveableFacade
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfFileSignature](pdffilesignature/#constructor)() | مُنشئ فئة PdfFileSignature. |
| [PdfFileSignature](pdffilesignature/#constructor_1)(Document) | يقوم بتهيئة كائن `PdfFileSignature` جديد بناءً على *المستند*. |

## Properties

| Name | Description |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | يحصل على واجهة المستند التي يعمل عليها. |
| [IsCertified](../../aspose.pdf.facades/pdffilesignature/iscertified/) { get; } | يحصل على العلم الذي يحدد ما إذا كان المستند معتمدًا أم لا. |
| [IsLtvEnabled](../../aspose.pdf.facades/pdffilesignature/isltvenabled/) { get; } | يحصل على علم تمكين LTV. |
| [SignatureAppearance](../../aspose.pdf.facades/pdffilesignature/signatureappearance/) { get; set; } | يحدد أو يحصل على مظهر رسومي للتوقيع. تمثل قيمة الخاصية اسم ملف الصورة. |
| [SignatureAppearanceStream](../../aspose.pdf.facades/pdffilesignature/signatureappearancestream/) { get; set; } | يحدد أو يحصل على مظهر رسومي للتوقيع. تمثل قيمة الخاصية تدفق الصورة. |

## Methods

| Name | Description |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | يقوم بتهيئة الواجهة. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_1)(Stream) | يربط تدفق PDF للتحرير. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_2)(string) | يربط ملف PDF للتحرير. |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify_1)(string, DocMDPSignature) | يعتمد المستند باستخدام توقيع MDP الذي تم وضعه في حقل التوقيع المقدم بالفعل. قبل التوقيع، يجب أن يكون حقل التوقيع فارغًا، أي يجب ألا يحتوي الحقل على قاموس التوقيع. وبالتالي، إذا كان مستند PDF يحتوي بالفعل على حقل توقيع، يجب ألا تزود المكان لطباعة التوقيع، حيث يتم أخذ الصفحة والمستطيل المقابلين من حقل التوقيع الذي يتم العثور عليه بواسطة اسم التوقيع (انظر معلمة sigName). |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify)(int, string, string, string, bool, Rectangle, DocMDPSignature) | يعتمد المستند باستخدام توقيع MDP. يجب توفير بيانات مثل سبب التوقيع، ووسيلة الاتصال، والموقع من خلال الخصائص المقابلة لكائن التوقيع sig. |
| override [Close](../../aspose.pdf.facades/pdffilesignature/close/)() | يغلق الواجهة. |
| [ContainsSignature](../../aspose.pdf.facades/pdffilesignature/containssignature/)() | يتحقق مما إذا كان PDF يحتوي على توقيع رقمي أم لا. |
| [ContainsUsageRights](../../aspose.pdf.facades/pdffilesignature/containsusagerights/)() | يتحقق مما إذا كان PDF يحتوي على حقوق استخدام أم لا. |
| [CoversWholeDocument](../../aspose.pdf.facades/pdffilesignature/coverswholedocument/#coverswholedocument)(SignatureName) | يتحقق مما إذا كان التوقيع يغطي المستند بالكامل. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | يتخلص من الواجهة. |
| [ExtractCertificate](../../aspose.pdf.facades/pdffilesignature/extractcertificate/#extractcertificate)(SignatureName) | يستخرج شهادة X.509 الفردية للتوقيع كتيار. |
| [ExtractImage](../../aspose.pdf.facades/pdffilesignature/extractimage/#extractimage)(SignatureName) | يستخرج صورة التوقيع. |
| [GetAccessPermissions](../../aspose.pdf.facades/pdffilesignature/getaccesspermissions/)() | يعيد قيمة أذونات الوصول للمستند المعتمد بواسطة نوع توقيع MDP. |
| [GetBlankSignatureNames](../../aspose.pdf.facades/pdffilesignature/getblanksignaturenames/)() | يحصل على أسماء جميع حقول التوقيع الفارغة. |
| [GetContactInfo](../../aspose.pdf.facades/pdffilesignature/getcontactinfo/#getcontactinfo)(SignatureName) | يحصل على معلومات الاتصال لتوقيع. |
| [GetDateTime](../../aspose.pdf.facades/pdffilesignature/getdatetime/#getdatetime)(SignatureName) | يحصل على تاريخ ووقت التوقيع. |
| [GetLocation](../../aspose.pdf.facades/pdffilesignature/getlocation/#getlocation)(SignatureName) | يحصل على موقع التوقيع. |
| [GetReason](../../aspose.pdf.facades/pdffilesignature/getreason/#getreason)(SignatureName) | يحصل على سبب التوقيع. |
| [GetRevision](../../aspose.pdf.facades/pdffilesignature/getrevision/#getrevision)(SignatureName) | يحصل على مراجعة التوقيع. |
| [GetSignatureNames](../../aspose.pdf.facades/pdffilesignature/getsignaturenames/)(bool) | يحصل على أسماء جميع التوقيعات غير الفارغة. |
| [GetSignaturesInfo](../../aspose.pdf.facades/pdffilesignature/getsignaturesinfo/)() | يسترجع معلومات حول جميع خوارزميات التوقيع الموجودة في مستند PDF. |
| [GetSignerName](../../aspose.pdf.facades/pdffilesignature/getsignername/#getsignername)(SignatureName) | يحصل على اسم الشخص أو المنظمة التي تقوم بتوقيع مستند PDF. |
| [GetTotalRevision](../../aspose.pdf.facades/pdffilesignature/gettotalrevision/)() | يحصل على المراجعة الإجمالية. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature)(SignatureName) | يزيل التوقيع وفقًا لاسم التوقيع. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature_1)(SignatureName, bool) | يزيل التوقيع وفقًا لاسم التوقيع. |
| [RemoveSignatures](../../aspose.pdf.facades/pdffilesignature/removesignatures/)() | يزيل جميع التوقيعات. |
| [RemoveUsageRights](../../aspose.pdf.facades/pdffilesignature/removeusagerights/)() | يزيل إدخال حقوق الاستخدام. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_1)(Stream) | يحفظ ملف PDF الناتج إلى تيار. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_2)(string) | يحفظ ملف PDF الناتج إلى ملف. |
| [SetCertificate](../../aspose.pdf.facades/pdffilesignature/setcertificate/)(string, string) | تعيين ملف الشهادة وكلمة المرور لعملية التوقيع. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_4)(string, Signature) | يوقع المستند باستخدام نوع التوقيع المحدد الذي تم وضعه في حقل التوقيع المقدم بالفعل. قبل التوقيع، يجب أن يكون حقل التوقيع فارغًا، أي يجب ألا يحتوي الحقل على قاموس التوقيع. وبالتالي، إذا كان مستند PDF يحتوي بالفعل على حقل توقيع، يجب ألا تزود المكان لطباعة التوقيع، حيث يتم أخذ الصفحة والمستطيل المقابلين من حقل التوقيع الذي يتم العثور عليه بواسطة اسم التوقيع (انظر معلمة SigName). يجب توفير بيانات مثل سبب التوقيع، ووسيلة الاتصال، والموقع من خلال الخصائص المقابلة لكائن التوقيع sig. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign)(int, bool, Rectangle, Signature) | يوقع المستند باستخدام نوع التوقيع المحدد. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_5)(string, string, string, string, Signature) | يوقع المستند باستخدام نوع التوقيع المحدد الذي تم وضعه في حقل التوقيع المقدم بالفعل. قبل التوقيع، يجب أن يكون حقل التوقيع فارغًا، أي يجب ألا يحتوي الحقل على قاموس التوقيع. وبالتالي، إذا كان مستند PDF يحتوي بالفعل على حقل توقيع، يجب ألا تزود المكان لطباعة التوقيع، حيث يتم أخذ الصفحة والمستطيل المقابلين من حقل التوقيع الذي يتم العثور عليه بواسطة اسم التوقيع (انظر معلمة SigName). |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_1)(int, string, string, string, bool, Rectangle) | يقوم بعمل توقيع على مستند PDF. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_2)(int, string, string, string, bool, Rectangle, Signature) | يوقع المستند باستخدام نوع التوقيع المحدد. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_3)(int, string, string, string, string, bool, Rectangle, Signature) | يوقع المستند باستخدام نوع التوقيع المحدد الذي تم وضعه في حقل التوقيع المقدم بالفعل. قبل التوقيع، يجب أن يحتوي مستند PDF بالفعل على حقل توقيع، حيث يتم أخذ الصفحة والمستطيل المقابلين من حقل التوقيع الذي يتم العثور عليه بواسطة اسم التوقيع (انظر معلمة SigName). |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature)(SignatureName) | يتحقق من صحة التوقيع. |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature_1)(SignatureName, ValidationOptions, out ValidationResult) | يتحقق من صحة التوقيع. |

### See Also

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)