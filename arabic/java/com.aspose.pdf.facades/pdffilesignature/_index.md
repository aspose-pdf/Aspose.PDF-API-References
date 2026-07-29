---
title: "PdfFileSignature"
linktitle: "PdfFileSignature"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل فئة لتوقيع ملف pdf باستخدام شهادة."
type: docs
weight: 530
url: /ar/java/com.aspose.pdf.facades/pdffilesignature/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSignature, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSignature, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileSignature

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileSignature extends SaveableFacade
```

يمثل فئة لتوقيع ملف pdf باستخدام شهادة.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PdfFileSignature](#PdfFileSignature--) | منشئ فئة PdfFileSignature. |
| [PdfFileSignature](#PdfFileSignature-com.aspose.pdf.IDocument-) | منشئ فئة PdfFileSignature. |
| [PdfFileSignature](#PdfFileSignature-com.aspose.pdf.IDocument-java.lang.String-) | منشئ فئة PdfFileSignature. |
| [PdfFileSignature](#PdfFileSignature-java.lang.String-) | منشئ فئة PdfFileSignature. |
| [PdfFileSignature](#PdfFileSignature-java.lang.String-java.lang.String-) | منشئ فئة PdfFileSignature. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-) | يربط تدفق PDF للتحرير. |
| [bindPdf](#bindPdf-java.lang.String-) | يربط ملف PDF للتحرير. |
| [certify](#certify-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.DocMDPSignature-) | اعتماد المستند بتوقيع MDP. |
| [certify](#certify-java.lang.String-com.aspose.pdf.DocMDPSignature-) | اعتماد المستند بتوقيع MDP الذي يُوضع في حقل توقيع موجود مسبقًا. قبل التوقيع يجب أن يكون حقل التوقيع فارغًا، أي لا يجب أن يحتوي الحقل على قاموس توقيع. وبالتالي فإن مستند PDF يحتوي بالفعل على حقل توقيع، لا يجب عليك تحديد مكان وضع التوقيع، حيث يتم أخذ الصفحة والمستطيل المقابلين من حقل التوقيع الذي يُعثر عليه باسم التوقيع (انظر معلمة sigName). |
| [close](#close--) | يغلق الواجهة. |
| [containsSignature](#containsSignature--) | يتحقق مما إذا كان ملف PDF يحتوي على توقيع رقمي أم لا. |
| [containsUsageRights](#containsUsageRights--) | يتحقق مما إذا كان ملف PDF يحتوي على حقوق استخدام أم لا. |
| [coversWholeDocument](#coversWholeDocument-com.aspose.pdf.facades.SignatureName-) | يتحقق مما إذا كان التوقيع يغطي المستند بالكامل. |
| [coversWholeDocument](#coversWholeDocument-java.lang.String-) | يتحقق مما إذا كان التوقيع يغطي المستند بالكامل. |
| [dispose](#dispose--) | يغلق الواجهة. هذه الطريقة قديمة، استخدم close() بدلاً من ذلك. |
| [extractCertificate](#extractCertificate-com.aspose.pdf.facades.SignatureName-) | يستخرج شهادة X.509 الفردية للتوقيع كتيار. |
| [extractCertificate](#extractCertificate-java.lang.String-) | يستخرج شهادة X.509 الفردية للتوقيع كتيار. |
| [extractImage](#extractImage-com.aspose.pdf.facades.SignatureName-) | يستخرج صورة التوقيع. |
| [extractImage](#extractImage-java.lang.String-) | يستخرج صورة التوقيع. |
| [getAccessPermissions](#getAccessPermissions--) | يعيد قيمة أذونات الوصول للمستند المعتمد بنوع توقيع MDP. |
| [getBlankSignNames](#getBlankSignNames--) | يحصل على أسماء جميع حقول التوقيع الفارغة. |
| [getContactInfo](#getContactInfo-com.aspose.pdf.facades.SignatureName-) | يحصل على معلومات الاتصال لتوقيع. |
| [getContactInfo](#getContactInfo-java.lang.String-) | يحصل على معلومات الاتصال لتوقيع. |
| [getDateTime](#getDateTime-com.aspose.pdf.facades.SignatureName-) | يحصل على تاريخ ووقت التوقيع. |
| [getDateTime](#getDateTime-java.lang.String-) | يحصل على تاريخ ووقت التوقيع. |
| [getLocation](#getLocation-com.aspose.pdf.facades.SignatureName-) | يحصل على موقع التوقيع. |
| [getLocation](#getLocation-java.lang.String-) | يحصل على موقع التوقيع. |
| [getReason](#getReason-com.aspose.pdf.facades.SignatureName-) | يحصل على سبب التوقيع. |
| [getReason](#getReason-java.lang.String-) | يحصل على سبب التوقيع. |
| [getRevision](#getRevision-com.aspose.pdf.facades.SignatureName-) | يحصل على نسخة التوقيع. |
| [getRevision](#getRevision-java.lang.String-) | يحصل على نسخة التوقيع. |
| [getSignatureAppearance](#getSignatureAppearance--) | يحصل على مظهر رسومي للتوقيع. تمثل قيمة الخاصية اسم ملف الصورة. |
| [getSignatureAppearanceStream](#getSignatureAppearanceStream--) | يحصل على مظهر رسومي للتوقيع. تمثل قيمة الخاصية تدفق الصورة. |
| [getSignatureNames](#getSignatureNames--) | / * <p> / * يحصل على أسماء جميع التوقيعات غير الفارغة. / * </p> / * <p> / * <pre> / * string inFile=TestPath + "example1.pdf"; / * PdfFileSignature pdfSign=new PdfFileSignature(); / * pdfSign.bindPdf(inFile); / * java.util.List<String> names=pdfSign.getSignatureNames(); / * for(int i=0;i<names.size();i++) / * { / * System.out.println("signature name:" + names[i]); / * System.out.println("coverswholeddocument:" + pdfSign.coversWholeDocument(names[i])); / * System.out.println("revision:" + pdfSign.getRevision(names[i])); / * System.out.println("verifysigned:" + pdfSign.verifySignature(names[i])); / * System.out.println("reason:" + pdfSign.getReason(names[i])); / * System.out.println("location:" + pdfSign.getLocation(names[i])); / * System.out.println("datatime:" + pdfSign.getDateTime(names[i])); / * } / * System.out.println("totalvision:" + pdfSign.GetTotalRevision()); / * / * </pre> / * |
| [getSignatureNames](#getSignatureNames-boolean-) | يحصل على أسماء جميع التوقيعات غير الفارغة. string inFile=TestPath + "example1.pdf"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); java.util.List names=pdfSign.getSignatureNames(); for(int i=0;i<names.size();i++) { System.out.println("signature name:" + names[i]); System.out.println("coverswholeddocument:" + pdfSign.coversWholeDocument(names[i])); System.out.println("revision:" + pdfSign.getRevision(names[i])); System.out.println("verifysigned:" + pdfSign.verifySignature(names[i])); System.out.println("reason:" + pdfSign.getReason(names[i])); System.out.println("location:" + pdfSign.getLocation(names[i])); System.out.println("datatime:" + pdfSign.getDateTime(names[i])); } System.out.println("totalvision:" + pdfSign.GetTotalRevision()); |
| [getSignaturesInfo](#getSignaturesInfo--) | يسترجع معلومات حول جميع خوارزميات التوقيعات الموجودة في مستند PDF. |
| [getSignerName](#getSignerName-com.aspose.pdf.facades.SignatureName-) | يحصل على اسم الشخص أو المؤسسة التي توقّع مستند PDF. |
| [getSignerName](#getSignerName-java.lang.String-) | يحصل على اسم الشخص أو المؤسسة التي توقّع مستند PDF. |
| [getSignNames](#getSignNames--) | <p> يحصل على أسماء جميع التوقيعات غير الفارغة. </p> <hr> |
| [getSignNames](#getSignNames-boolean-) | <p> يحصل على أسماء جميع التوقيعات غير الفارغة. </p> <hr> <pre> String inFile=TestPath + "example1.pdf"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); ArrayList names=pdfSign.getSignNames(true); for(int i=0;i<names.Count;i++) { System.out.println("signature name:"+(String)names[i]); System.out.println("coverswholeddocument:"+pdfSign.IsCoversWholeDocument((String)names[i])); System.out.println("revision:"+pdfSign.GetRevision((String)names[i])); System.out.println("verifysigned:"+pdfSign.VerifySigned((String)names[i])); System.out.println("reason:"+pdfSign.GetReason((String)names[i])); System.out.println("location:"+pdfSign.GetLocation((String)names[i])); System.out.println("datatime:"+pdfSign.GetDateTime((String)names[i])); } System.out.println("totalvision:"+pdfSign.GetTotalRevision()); </pre> |
| [getTotalRevision](#getTotalRevision--) | يحصل على إجمالي النسخة. |
| [isCertified](#isCertified--) | يحصل على العلم الذي يحدد ما إذا كان المستند معتمدًا أم لا. |
| [isContainSignature](#isContainSignature--) | يتحقق مما إذا كان ملف PDF يحتوي على توقيع رقمي أم لا. |
| [isCoversWholeDocument](#isCoversWholeDocument-java.lang.String-) | يتحقق مما إذا كان التوقيع يغطي المستند بالكامل. |
| [isLtvEnabled](#isLtvEnabled--) | يحصل على علم تمكين LTV. |
| [removeSignature](#removeSignature-com.aspose.pdf.facades.SignatureName-) | إزالة التوقيع وفقًا لاسم التوقيع. string inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i]); } pdfSign.save(TestPath + "signed_removed.pdf"); |
| [removeSignature](#removeSignature-com.aspose.pdf.facades.SignatureName-boolean-) | يزيل التوقيع وفقًا لاسم التوقيع. string inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i], false); } pdfSign.save(TestPath + "signed_removed.pdf"); |
| [removeSignature](#removeSignature-java.lang.String-) | <p> إزالة التوقيع وفقًا لاسم التوقيع. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i)); } pdfSign.save(TestPath + "signed_removed.pdf"); </pre> |
| [removeSignature](#removeSignature-java.lang.String-boolean-) | <p> يزيل التوقيع وفقًا لاسم التوقيع. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.BindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i), false); } pdfSign.save(TestPath + "signed_removed.pdf"); </pre> |
| [removeSignatures](#removeSignatures--) | يزيل جميع التوقيعات. string inFile = TestPath + "example1.pdf"; var pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); pdfSign.removeSignatures(); pdfSign.save(TestPath + "signed_removed.pdf"); |
| [removeUsageRights](#removeUsageRights--) | يزيل إدخال حقوق الاستخدام. |
| [save](#save--) | احفظ ملف PDF الموقع. يجب توفير اسم ملف الإخراج مسبقًا بمساعدة مُنشئ PdfFileSignature المقابل. |
| [save](#save-java.io.OutputStream-) | احفظ ملف PDF الموقع. يجب توفير اسم ملف الإخراج مسبقًا بمساعدة مُنشئ PdfFileSignature المقابل. |
| [save](#save-java.lang.String-) | احفظ ملف PDF الموقع. يجب توفير اسم ملف الإخراج مسبقًا بمساعدة مُنشئ PdfFileSignature المقابل. |
| [setCertificate](#setCertificate-java.lang.String-java.lang.String-) | حدد ملف الشهادة وكلمة المرور لإجراء التوقيع. |
| [setSignatureAppearance](#setSignatureAppearance-java.lang.String-) | يضبط مظهرًا رسوميًا للتوقيع. قيمة الخاصية تمثل اسم ملف الصورة. |
| [setSignatureAppearanceStream](#setSignatureAppearanceStream-java.io.InputStream-) | يضبط مظهرًا رسوميًا للتوقيع. قيمة الخاصية تمثل تدفق الصورة. |
| [sign](#sign-int-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-) | وقع المستند باستخدام توقيع من النوع المحدد. |
| [sign](#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-) | أنشئ توقيعًا على مستند PDF. |
| [sign](#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-) | وقع المستند باستخدام توقيع من النوع المحدد. |
| [sign](#sign-int-java.lang.String-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-) | وقع المستند باستخدام توقيع من النوع المحدد الموجود في حقل توقيع موجود مسبقًا. |
| [sign](#sign-java.lang.String-com.aspose.pdf.Signature-) | <p> وقع المستند باستخدام توقيع من النوع المحدد الموجود في حقل توقيع موجود مسبقًا. قبل التوقيع يجب أن يكون حقل التوقيع فارغًا، أي لا يجب أن يحتوي على قاموس توقيع. وبالتالي يحتوي مستند PDF بالفعل على حقل توقيع، لا يلزم توفير مكان لختم التوقيع، حيث يتم أخذ الصفحة والمستطيل المقابلين من حقل التوقيع الذي يتم العثور عليه باسم التوقيع (انظر معلمة SigName). يجب توفير بيانات مثل سبب التوقيع، جهة الاتصال والموقع من خلال الخصائص المقابلة لكائن Signature المسمى sig. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; String outFile = TestPath + "signature.pdf"; PKCS1 sig = new PKCS1("certificate.pfx", "password"); sig.setReason ( "Some reason"); sig.setContact ( "Smith"); sig.setLocation ( "New York"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg"); pdfSign.sign("Signature1", sig); pdfSign.save(); </pre> |
| [sign](#sign-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.Signature-) | <p> وقع المستند باستخدام توقيع من النوع المحدد الموجود في حقل توقيع موجود مسبقًا. قبل التوقيع يجب أن يكون حقل التوقيع فارغًا، أي لا يجب أن يحتوي على قاموس توقيع. وبالتالي يحتوي مستند PDF بالفعل على حقل توقيع، لا يلزم توفير مكان لختم التوقيع، حيث يتم أخذ الصفحة والمستطيل المقابلين من حقل التوقيع الذي يتم العثور عليه باسم التوقيع (انظر معلمة SigName). </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; String outFile = TestPath + "signature.pdf"; PKCS1 sig = new PKCS1("certificate.pfx", "password"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg"); pdfSign.sign("Signature1", "Allen", "success", "ChangSha", sig); pdfSign.save(); </pre> |
| [tryExtractCertificate](#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-java.io.OutputStream:A-) | يستخرج شهادة X.509 الفردية للتوقيع كتيار. |
| [tryExtractCertificate](#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2:A-) | يستخرج شهادة X.509 الفردية للتوقيع. |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-) | يتحقق من صحة التوقيع. |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | يتحقق من صحة التوقيع. |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-) | يتحقق من صحة التوقيع. |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | يتحقق من صحة التوقيع. |
| [verifySignature](#verifySignature-java.lang.String-) | يتحقق من صحة التوقيع. |
| [verifySignature](#verifySignature-java.lang.String-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | يتحقق من صحة التوقيع. |
| [verifySigned](#verifySigned-java.lang.String-) | يتحقق من صحة التوقيع. الطريقة مهجورة وسيتم حذفها في الإصدار 25.1. استخدم طريقة VerifySignature بدلاً من ذلك. |

### PdfFileSignature {#PdfFileSignature--}
```
public PdfFileSignature()
```

منشئ فئة PdfFileSignature.

### PdfFileSignature {#PdfFileSignature-com.aspose.pdf.IDocument-}
منشئ فئة PdfFileSignature.

### PdfFileSignature {#PdfFileSignature-com.aspose.pdf.IDocument-java.lang.String-}
منشئ فئة PdfFileSignature.

### PdfFileSignature {#PdfFileSignature-java.lang.String-}
منشئ فئة PdfFileSignature.

### PdfFileSignature {#PdfFileSignature-java.lang.String-java.lang.String-}
منشئ فئة PdfFileSignature.

### bindPdf {#bindPdf-java.io.InputStream-}
يربط تدفق PDF للتحرير.

### bindPdf {#bindPdf-java.lang.String-}
يربط ملف PDF للتحرير.

### certify {#certify-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.DocMDPSignature-}
اعتماد المستند بتوقيع MDP.

### certify {#certify-java.lang.String-com.aspose.pdf.DocMDPSignature-}
اعتماد المستند بتوقيع MDP الذي يُوضع في حقل توقيع موجود مسبقًا. قبل التوقيع يجب أن يكون حقل التوقيع فارغًا، أي لا يجب أن يحتوي الحقل على قاموس توقيع. وبالتالي فإن مستند PDF يحتوي بالفعل على حقل توقيع، لا يجب عليك تحديد مكان وضع التوقيع، حيث يتم أخذ الصفحة والمستطيل المقابلين من حقل التوقيع الذي يُعثر عليه باسم التوقيع (انظر معلمة sigName).

### close {#close--}
```
public void close()
```

يغلق الواجهة.

### containsSignature {#containsSignature--}
```
public boolean containsSignature()
```

يتحقق مما إذا كان ملف PDF يحتوي على توقيع رقمي أم لا.

**Returns:**
إرجاع نتيجة من نوع bool.

### containsUsageRights {#containsUsageRights--}
```
public boolean containsUsageRights()
```

يتحقق مما إذا كان ملف PDF يحتوي على حقوق استخدام أم لا.

**Returns:**
يرجع نتيجة من نوع bool.

### coversWholeDocument {#coversWholeDocument-com.aspose.pdf.facades.SignatureName-}
يتحقق مما إذا كان التوقيع يغطي المستند بالكامل.

### coversWholeDocument {#coversWholeDocument-java.lang.String-}
يتحقق مما إذا كان التوقيع يغطي المستند بالكامل.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

يغلق الواجهة. هذه الطريقة قديمة، استخدم close() بدلاً من ذلك.

### extractCertificate {#extractCertificate-com.aspose.pdf.facades.SignatureName-}
يستخرج شهادة X.509 الفردية للتوقيع كتيار.

### extractCertificate {#extractCertificate-java.lang.String-}
يستخرج شهادة X.509 الفردية للتوقيع كتيار.

### extractImage {#extractImage-com.aspose.pdf.facades.SignatureName-}
يستخرج صورة التوقيع.

### extractImage {#extractImage-java.lang.String-}
يستخرج صورة التوقيع.

### getAccessPermissions {#getAccessPermissions--}
```
public DocMDPAccessPermissions getAccessPermissions()
```

يعيد قيمة أذونات الوصول للمستند المعتمد بنوع توقيع MDP.

**Returns:**
PdfException إذا كان المستند قيد التصديق، فإنها تُعيد قيمة أذونات الوصول؛ وإلا، يتم رمي الاستثناء. @see com.aspose.pdf.DocMDPAccessPermissions

### getBlankSignNames {#getBlankSignNames--}
```
@Deprecated public List < String > getBlankSignNames()
```

يحصل على أسماء جميع حقول التوقيع الفارغة.

**Returns:**
أعد arrayList. @deprecated استخدم GetBlankSignatureNames() بدلاً من ذلك.

### getContactInfo {#getContactInfo-com.aspose.pdf.facades.SignatureName-}
يحصل على معلومات الاتصال لتوقيع.

### getContactInfo {#getContactInfo-java.lang.String-}
يحصل على معلومات الاتصال لتوقيع.

### getDateTime {#getDateTime-com.aspose.pdf.facades.SignatureName-}
يحصل على تاريخ ووقت التوقيع.

### getDateTime {#getDateTime-java.lang.String-}
يحصل على تاريخ ووقت التوقيع.

### getLocation {#getLocation-com.aspose.pdf.facades.SignatureName-}
يحصل على موقع التوقيع.

### getLocation {#getLocation-java.lang.String-}
يحصل على موقع التوقيع.

### getReason {#getReason-com.aspose.pdf.facades.SignatureName-}
يحصل على سبب التوقيع.

### getReason {#getReason-java.lang.String-}
يحصل على سبب التوقيع.

### getRevision {#getRevision-com.aspose.pdf.facades.SignatureName-}
يحصل على نسخة التوقيع.

### getRevision {#getRevision-java.lang.String-}
يحصل على نسخة التوقيع.

### getSignatureAppearance {#getSignatureAppearance--}
```
public String getSignatureAppearance()
```

يحصل على مظهر رسومي للتوقيع. تمثل قيمة الخاصية اسم ملف الصورة.

**Returns:**
قيمة سلسلة

### getSignatureAppearanceStream {#getSignatureAppearanceStream--}
```
public InputStream getSignatureAppearanceStream()
```

يحصل على مظهر رسومي للتوقيع. تمثل قيمة الخاصية تدفق الصورة.

**Returns:**
عنصر InputStream

### getSignatureNames {#getSignatureNames--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericList< SignatureName > getSignatureNames()
```

/ * <p> / * يحصل على أسماء جميع التوقيعات غير الفارغة. / * </p> / * <p> / * <pre> / * string inFile=TestPath + "example1.pdf"; / * PdfFileSignature pdfSign=new PdfFileSignature(); / * pdfSign.bindPdf(inFile); / * java.util.List<String> names=pdfSign.getSignatureNames(); / * for(int i=0;i<names.size();i++) / * { / * System.out.println("signature name:" + names[i]); / * System.out.println("coverswholeddocument:" + pdfSign.coversWholeDocument(names[i])); / * System.out.println("revision:" + pdfSign.getRevision(names[i])); / * System.out.println("verifysigned:" + pdfSign.verifySignature(names[i])); / * System.out.println("reason:" + pdfSign.getReason(names[i])); / * System.out.println("location:" + pdfSign.getLocation(names[i])); / * System.out.println("datatime:" + pdfSign.getDateTime(names[i])); / * } / * System.out.println("totalvision:" + pdfSign.GetTotalRevision()); / * / * </pre> / *

**Returns:**
أعد IList<SignatureName>. /

### getSignatureNames {#getSignatureNames-boolean-}
```
public final com.aspose.ms.System.Collections.Generic.IGenericList< SignatureName > getSignatureNames(boolean onlyActive)
```

يحصل على أسماء جميع التوقيعات غير الفارغة. string inFile=TestPath + "example1.pdf"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); java.util.List names=pdfSign.getSignatureNames(); for(int i=0;i<names.size();i++) { System.out.println("signature name:" + names[i]); System.out.println("coverswholeddocument:" + pdfSign.coversWholeDocument(names[i])); System.out.println("revision:" + pdfSign.getRevision(names[i])); System.out.println("verifysigned:" + pdfSign.verifySignature(names[i])); System.out.println("reason:" + pdfSign.getReason(names[i])); System.out.println("location:" + pdfSign.getLocation(names[i])); System.out.println("datatime:" + pdfSign.getDateTime(names[i])); } System.out.println("totalvision:" + pdfSign.GetTotalRevision());

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| onlyActive |  | إذا كان true، أعد التواقيع النشطة فقط؛ وإلا، أعد جميع التواقيع. |

**Returns:**
أعد IList<SignatureName>.

### getSignaturesInfo {#getSignaturesInfo--}
```
public final List <com.aspose.pdf.engine.security.SignatureAlgorithmInfo> getSignaturesInfo()
```

يسترجع معلومات حول جميع خوارزميات التوقيعات الموجودة في مستند PDF.

**Returns:**
قائمة من كائنات {@link SignatureAlgorithmInfo} التي تحتوي على معلومات حول كل توقيع.

### getSignerName {#getSignerName-com.aspose.pdf.facades.SignatureName-}
يحصل على اسم الشخص أو المؤسسة التي توقّع مستند PDF.

### getSignerName {#getSignerName-java.lang.String-}
يحصل على اسم الشخص أو المؤسسة التي توقّع مستند PDF.

### getSignNames {#getSignNames--}
```
public final List < String > getSignNames()
```

<p> يحصل على أسماء جميع التوقيعات غير الفارغة. </p> <hr>

**Returns:**
أعد arrayList.

### getSignNames {#getSignNames-boolean-}
```
@Deprecated public List < String > getSignNames(boolean onlyActive)
```

<p> يحصل على أسماء جميع التوقيعات غير الفارغة. </p> <hr> <pre> String inFile=TestPath + "example1.pdf"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); ArrayList names=pdfSign.getSignNames(true); for(int i=0;i<names.Count;i++) { System.out.println("signature name:"+(String)names[i]); System.out.println("coverswholeddocument:"+pdfSign.IsCoversWholeDocument((String)names[i])); System.out.println("revision:"+pdfSign.GetRevision((String)names[i])); System.out.println("verifysigned:"+pdfSign.VerifySigned((String)names[i])); System.out.println("reason:"+pdfSign.GetReason((String)names[i])); System.out.println("location:"+pdfSign.GetLocation((String)names[i])); System.out.println("datatime:"+pdfSign.GetDateTime((String)names[i])); } System.out.println("totalvision:"+pdfSign.GetTotalRevision()); </pre>

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| onlyActive |  | قيمة منطقية، إذا كانت true، أعد التواقيع النشطة فقط؛ وإلا، أعد جميع التواقيع. |

**Returns:**
أعد arrayList. @deprecated يمكن للطريقة إنتاج نفس أسماء التواقيع، والتي لا يمكن تمييزها أثناء التحقق. استخدم getSignatureNames(boolean onlyActive) بدلاً من ذلك.

### getTotalRevision {#getTotalRevision--}
```
public int getTotalRevision()
```

يحصل على إجمالي النسخة.

**Returns:**
أعد العدد الإجمالي لإصدارات التوقيع.

### isCertified {#isCertified--}
```
public boolean isCertified()
```

يحصل على العلم الذي يحدد ما إذا كان المستند معتمدًا أم لا.

**Returns:**
قيمة منطقية

### isContainSignature {#isContainSignature--}
```
@Deprecated public boolean isContainSignature()
```

يتحقق مما إذا كان ملف PDF يحتوي على توقيع رقمي أم لا.

**Returns:**
إرجاع نتيجة من نوع bool.

### isCoversWholeDocument {#isCoversWholeDocument-java.lang.String-}
يتحقق مما إذا كان التوقيع يغطي المستند بالكامل.

### isLtvEnabled {#isLtvEnabled--}
```
public final boolean isLtvEnabled()
```

يحصل على علم تمكين LTV.

**Returns:**
قيمة منطقية

### removeSignature {#removeSignature-com.aspose.pdf.facades.SignatureName-}
إزالة التوقيع وفقًا لاسم التوقيع. string inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i]); } pdfSign.save(TestPath + "signed_removed.pdf");

### removeSignature {#removeSignature-com.aspose.pdf.facades.SignatureName-boolean-}
يزيل التوقيع وفقًا لاسم التوقيع. string inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i], false); } pdfSign.save(TestPath + "signed_removed.pdf");

### removeSignature {#removeSignature-java.lang.String-}
<p> إزالة التوقيع وفقًا لاسم التوقيع. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i)); } pdfSign.save(TestPath + "signed_removed.pdf"); </pre>

### removeSignature {#removeSignature-java.lang.String-boolean-}
<p> يزيل التوقيع وفقًا لاسم التوقيع. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.BindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i), false); } pdfSign.save(TestPath + "signed_removed.pdf"); </pre>

### removeSignatures {#removeSignatures--}
```
public final void removeSignatures()
```

يزيل جميع التوقيعات. string inFile = TestPath + "example1.pdf"; var pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); pdfSign.removeSignatures(); pdfSign.save(TestPath + "signed_removed.pdf");

### removeUsageRights {#removeUsageRights--}
```
public void removeUsageRights()
```

يزيل إدخال حقوق الاستخدام.

### save {#save--}
```
@Deprecated public void save()
```

احفظ ملف PDF الموقع. يجب توفير اسم ملف الإخراج مسبقًا بمساعدة مُنشئ PdfFileSignature المقابل.

### save {#save-java.io.OutputStream-}
احفظ ملف PDF الموقع. يجب توفير اسم ملف الإخراج مسبقًا بمساعدة مُنشئ PdfFileSignature المقابل.

### save {#save-java.lang.String-}
احفظ ملف PDF الموقع. يجب توفير اسم ملف الإخراج مسبقًا بمساعدة مُنشئ PdfFileSignature المقابل.

### setCertificate {#setCertificate-java.lang.String-java.lang.String-}
حدد ملف الشهادة وكلمة المرور لإجراء التوقيع.

### setSignatureAppearance {#setSignatureAppearance-java.lang.String-}
يضبط مظهرًا رسوميًا للتوقيع. قيمة الخاصية تمثل اسم ملف الصورة.

### setSignatureAppearanceStream {#setSignatureAppearanceStream-java.io.InputStream-}
يضبط مظهرًا رسوميًا للتوقيع. قيمة الخاصية تمثل تدفق الصورة.

### sign {#sign-int-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-}
وقع المستند باستخدام توقيع من النوع المحدد.

### sign {#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-}
أنشئ توقيعًا على مستند PDF.

### sign {#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-}
وقع المستند باستخدام توقيع من النوع المحدد.

### sign {#sign-int-java.lang.String-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-}
وقع المستند باستخدام توقيع من النوع المحدد الموجود في حقل توقيع موجود مسبقًا.

### sign {#sign-java.lang.String-com.aspose.pdf.Signature-}
<p> وقع المستند باستخدام توقيع من النوع المحدد الموجود في حقل توقيع موجود مسبقًا. قبل التوقيع يجب أن يكون حقل التوقيع فارغًا، أي لا يجب أن يحتوي على قاموس توقيع. وبالتالي يحتوي مستند PDF بالفعل على حقل توقيع، لا يلزم توفير مكان لختم التوقيع، حيث يتم أخذ الصفحة والمستطيل المقابلين من حقل التوقيع الذي يتم العثور عليه باسم التوقيع (انظر معلمة SigName). يجب توفير بيانات مثل سبب التوقيع، جهة الاتصال والموقع من خلال الخصائص المقابلة لكائن Signature المسمى sig. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; String outFile = TestPath + "signature.pdf"; PKCS1 sig = new PKCS1("certificate.pfx", "password"); sig.setReason ( "Some reason"); sig.setContact ( "Smith"); sig.setLocation ( "New York"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg"); pdfSign.sign("Signature1", sig); pdfSign.save(); </pre>

### sign {#sign-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.Signature-}
<p> وقع المستند باستخدام توقيع من النوع المحدد الموجود في حقل توقيع موجود مسبقًا. قبل التوقيع يجب أن يكون حقل التوقيع فارغًا، أي لا يجب أن يحتوي على قاموس توقيع. وبالتالي يحتوي مستند PDF بالفعل على حقل توقيع، لا يلزم توفير مكان لختم التوقيع، حيث يتم أخذ الصفحة والمستطيل المقابلين من حقل التوقيع الذي يتم العثور عليه باسم التوقيع (انظر معلمة SigName). </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; String outFile = TestPath + "signature.pdf"; PKCS1 sig = new PKCS1("certificate.pfx", "password"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg"); pdfSign.sign("Signature1", "Allen", "success", "ChangSha", sig); pdfSign.save(); </pre>

### tryExtractCertificate {#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-java.io.OutputStream:A-}
يستخرج شهادة X.509 الفردية للتوقيع كتيار.

### tryExtractCertificate {#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2:A-}
يستخرج شهادة X.509 الفردية للتوقيع.

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-}
يتحقق من صحة التوقيع.

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
يتحقق من صحة التوقيع.

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-}
يتحقق من صحة التوقيع.

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
يتحقق من صحة التوقيع.

### verifySignature {#verifySignature-java.lang.String-}
يتحقق من صحة التوقيع.

### verifySignature {#verifySignature-java.lang.String-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
يتحقق من صحة التوقيع.

### verifySigned {#verifySigned-java.lang.String-}
يتحقق من صحة التوقيع. الطريقة مهجورة وسيتم حذفها في الإصدار 25.1. استخدم طريقة VerifySignature بدلاً من ذلك.
