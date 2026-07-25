---
title: "PdfFileSecurity"
linktitle: "PdfFileSecurity"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل تشفير أو فك تشفير ملف Pdf باستخدام كلمة مرور المالك أو المستخدم، وتغيير إعدادات الأمان وكلمة المرور."
type: docs
weight: 520
url: /ar/java/com.aspose.pdf.facades/pdffilesecurity/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSecurity, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSecurity, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileSecurity

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileSecurity extends SaveableFacade implements com.aspose.ms.System.IDisposable
```

يمثل تشفير أو فك تشفير ملف Pdf باستخدام كلمة مرور المالك أو المستخدم، وتغيير إعدادات الأمان وكلمة المرور.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PdfFileSecurity](#PdfFileSecurity--) | تهيئة كائن PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-com.aspose.pdf.IDocument-) | تهيئة كائن PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-com.aspose.pdf.IDocument-java.io.OutputStream-) | تهيئة كائن PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-com.aspose.pdf.IDocument-java.lang.String-) | تهيئة كائن PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-java.io.InputStream-java.io.OutputStream-) | تهيئة كائن PdfFileSecurity. |
| [PdfFileSecurity](#PdfFileSecurity-java.lang.String-java.lang.String-) | تهيئة كائن PdfFileSecurity. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-) | ينشئ الواجهة. |
| [bindPdf](#bindPdf-java.lang.String-) | ينشئ الواجهة. |
| [changePassword](#changePassword-java.lang.String-java.lang.String-java.lang.String-) | يغيّر كلمة مرور المستخدم وكلمة مرور المالك باستخدام كلمة مرور المالك، ويحافظ على إعدادات الأمان الأصلية. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغتين أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو null. يرمي استثناءً إذا فشلت العملية. string inFile = "D:\\\\input.pdf"; // قد يتم إعادة تعيين TestPath. string outFile = "D:\\\\output.pdf"; // قد يتم إعادة تعيين TestPath. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.changePassword("owner","newuser","newowner"); |
| [changePassword](#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | <p> يغيّر كلمة مرور المستخدم وكلمة المرور باستخدام كلمة مرور المالك، ويسمح بإعادة ضبط أمان مستند Pdf. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغتين أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو null. </p> <p> يرمي استثناءً إذا فشلت العملية. </p> <hr> <pre> string inFile = "input.pdf"; // قد يتم إعادة تعيين TestPath. string outFile = "output.pdf"; // قد يتم إعادة تعيين TestPath. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword("owner", "newuser", "newowner", DocumentPrivilege.Print, KeySize.x256); </pre> |
| [changePassword](#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-) | <p> يغيّر كلمة مرور المستخدم وكلمة المرور باستخدام كلمة مرور المالك، ويسمح بإعادة ضبط أمان مستند Pdf. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغتين أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو null. هناك 6 تركيبات ممكنة لقيم KeySize و Algorithm. ومع ذلك، التركيبان (KeySize.x40, Algorithm.AES) و (KeySize.x256, Algorithm.RC4) غير صالحين وسيتم رفع استثناء مناسب إذا واجه البرنامج هذا التركيب. يرمي استثناءً إذا فشلت العملية. </p> <hr> <pre> string inFile = "input.pdf"; // قد يتم إعادة تعيين TestPath. string outFile = "output.pdf"; // قد يتم إعادة تعيين TestPath. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword("owner", "newuser", "newowner", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre> |
| [close](#close--) | يغلق الواجهة. |
| [decryptFile](#decryptFile-java.lang.String-) | يفك تشفير مستند Pdf مشفر باستخدام كلمة مرور المالك. إذا لم يكن للمستند كلمة مرور مالك، يُسمح باستخدام كلمة مرور المستخدم. يرمي استثناءً إذا فشلت العملية. string inFile = "input.pdf"; // قد يتم إعادة تعيين TestPath. string outFile = "output.pdf"; // قد يتم إعادة تعيين TestPath. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.decryptFile("ownerpass"); |
| [dispose](#dispose--) | يغلق الواجهة. |
| [encryptFile](#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | <p> يشفر ملف Pdf باستخدام كلمة مرور المستخدم وكلمة مرور المالك ويحدد صلاحيات المستند للوصول. يمكن أن تكون كلمة مرور المستخدم وكلمة مرور المالك فارغتين أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك المدخلة فارغة أو null. يرمي استثناءً إذا فشلت العملية. </p> <hr> <pre> String inFile = "input.pdf"; // قد يتم إعادة تعيين TestPath. String outFile = "output.pdf"; // قد يتم إعادة تعيين TestPath. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256); </pre> |
| [encryptFile](#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-) | <p> يقوم بتشفير ملف Pdf باستخدام userpassword و ownerpassword ويضبط امتيازات المستند للوصول. يمكن أن تكون كلمة مرور المستخدم وكلمة مرور المالك null أو فارغة. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك المدخلة null أو فارغة. هناك 6 تركيبات ممكنة لقيم KeySize و Algorithm. ومع ذلك (KeySize.x40, Algorithm.AES) و (KeySize.x256, Algorithm.RC4) غير صالحة وسيتم رفع الاستثناء المناسب إذا صادف kit هذه التركيبة. يرفع استثناء إذا فشل العملية. </p> <hr> <pre> String inFile = "input.pdf"; // The TestPath may be // re-assigned. String outFile = "output.pdf"; // The TestPath may be // re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.encryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre> |
| [getAllowExceptions](#getAllowExceptions--) | إذا تم تعيين هذه القيمة إلى true، سيتم رفع استثناء عند فشل العملية. وإلا، تُعيد الطريقة false عند الفشل ويمكن التحقق من الاستثناء الأخير باستخدام الخاصية LastException. |
| [getLastException](#getLastException--) | يعيد الاستثناء الذي تم رفعه بواسطة العملية الأخيرة. |
| [setAllowExceptions](#setAllowExceptions-boolean-) | إذا تم تعيين هذه القيمة إلى true، سيتم رفع استثناء عند فشل العملية. وإلا، تُعيد الطريقة false عند الفشل ويمكن التحقق من الاستثناء الأخير باستخدام الخاصية LastException. |
| [setInputFile](#setInputFile-java.lang.String-) | يضبط ملف الإدخال. Obsolete("Use bindPdf(inputStream) method for facade initialization.") |
| [setInputStream](#setInputStream-java.io.InputStream-) | يضبط تدفق الإدخال. Obsolete("Use bindPdf(inputStream) method for facade initialization.") |
| [setOutputFile](#setOutputFile-java.lang.String-) | يضبط ملف الإخراج. Obsolete("Use save(outputStream) method for getting facade results.") |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | يضبط تدفق الإخراج. Obsolete("Use save(outputStream) method for getting facade results.") |
| [setPrivilege](#setPrivilege-com.aspose.pdf.facades.DocumentPrivilege-) | <p> يضبط أمان ملف Pdf باستخدام كلمات مرور المستخدم/المالك فارغة. سيتم إضافة كلمة مرور المالك بسلسلة عشوائية. يرفع استثناء إذا فشلت العملية. </p> <hr> <pre> string inFile = "input.pdf"; // The TestPath may be re-assigned. string outFile = "output.pdf"; // The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(DocumentPrivilege.Print); </pre> |
| [setPrivilege](#setPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-) | <p> يضبط أمان ملف Pdf باستخدام كلمة المرور الأصلية. يرفع استثناء إذا فشلت العملية. </p> <hr> <pre> string inFile = "input.pdf"; // The TestPath may be re-assigned. string outFile = "output.pdf"; // The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(userPassword, ownerPassword, DocumentPrivilege.getPrint()); </pre> |
| [tryChangePassword](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-) | يغيّر كلمة مرور المستخدم وكلمة مرور المالك باستخدام كلمة مرور المالك، ويحافظ على إعدادات الأمان الأصلية. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة null أو فارغة. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة null أو فارغة. لا يتم رفع استثناء إذا فشلت العملية. string inFile = "D:\\\\input.pdf"; //The TestPath may be re-assigned. string outFile = "D:\\\\output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner"); |
| [tryChangePassword](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | يغيّر كلمة مرور المستخدم وكلمة المرور باستخدام كلمة مرور المالك، ويسمح بإعادة تعيين أمان مستند Pdf. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة null أو فارغة. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة null أو فارغة. لا يتم رفع استثناء إذا فشلت العملية. string inFile = ".D:\\\\input.pdf"; //The TestPath may be re-assigned. string outFile = "D:\\\\output.pdf"; //The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256); |
| [tryChangePassword](#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-) | يغيّر كلمة مرور المستخدم وكلمة مرور المالك بواسطة كلمة مرور المالك، يسمح بإعادة تعيين أمان مستند Pdf. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغتين أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو null. هناك 6 تركيبات محتملة لقيم KeySize و Algorithm. ومع ذلك، (KeySize.x40, Algorithm.AES) و (KeySize.x256, Algorithm.RC4) غير صالحة وسيتم رفع الاستثناء المقابل إذا واجهت الأداة هذه التركيبة. لا يرفع استثناء إذا فشلت العملية. string inFile = "D:\\\\input.pdf"; //قد يتم إعادة تعيين TestPath. string outFile = "D:\\\\output.pdf"; //قد يتم إعادة تعيين TestPath. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.changePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES); |
| [tryDecryptFile](#tryDecryptFile-java.lang.String-) | يفك تشفير مستند Pdf مشفر بواسطة كلمة مرور المالك. إذا لم يكن للمستند كلمة مرور مالك، يُسمح باستخدام كلمة مرور المستخدم. لا يرفع استثناء إذا فشلت العملية. string inFile = "input.pdf"; //قد يتم إعادة تعيين TestPath. string outFile = "output.pdf"; //قد يتم إعادة تعيين TestPath. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.TryDecryptFile("ownerpass"); |
| [tryEncryptFile](#tryEncryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-) | يقوم بتشفير ملف Pdf باستخدام كلمة مرور المستخدم وكلمة مرور المالك ويضبط امتيازات المستند للوصول. يمكن أن تكون كلمة مرور المستخدم وكلمة مرور المالك فارغتين أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك المدخلة فارغة أو null. لا يرفع استثناء إذا فشلت العملية. string inFile = "input.pdf"; //قد يتم إعادة تعيين TestPath. string outFile = "output.pdf"; //قد يتم إعادة تعيين TestPath. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256); |
| [trySetPrivilege](#trySetPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-) | يضبط أمان ملف Pdf باستخدام كلمة المرور الأصلية. لا يرفع استثناء إذا فشلت العملية. string inFile = "D:\\\\input.pdf"; //قد يتم إعادة تعيين TestPath. string outFile = "D:\\\\output.pdf"; //قد يتم إعادة تعيين TestPath. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.trySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print); |

### PdfFileSecurity {#PdfFileSecurity--}
```
public PdfFileSecurity()
```

تهيئة كائن PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-com.aspose.pdf.IDocument-}
تهيئة كائن PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-com.aspose.pdf.IDocument-java.io.OutputStream-}
تهيئة كائن PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-com.aspose.pdf.IDocument-java.lang.String-}
تهيئة كائن PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-java.io.InputStream-java.io.OutputStream-}
تهيئة كائن PdfFileSecurity.

### PdfFileSecurity {#PdfFileSecurity-java.lang.String-java.lang.String-}
تهيئة كائن PdfFileSecurity.

### bindPdf {#bindPdf-java.io.InputStream-}
ينشئ الواجهة.

### bindPdf {#bindPdf-java.lang.String-}
ينشئ الواجهة.

### changePassword {#changePassword-java.lang.String-java.lang.String-java.lang.String-}
يغيّر كلمة مرور المستخدم وكلمة مرور المالك باستخدام كلمة مرور المالك، ويحافظ على إعدادات الأمان الأصلية. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغتين أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو null. يرفع استثناء إذا فشلت العملية. string inFile = "D:\\input.pdf"; //قد يتم إعادة تعيين TestPath. string outFile = "D:\\output.pdf"; //قد يتم إعادة تعيين TestPath. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.changePassword("owner","newuser","newowner");

### changePassword {#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
<p> يغيّر كلمة مرور المستخدم وكلمة المرور باستخدام كلمة مرور المالك، ويسمح بإعادة ضبط أمان مستند Pdf. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغتين أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو null. </p> <p> يرمي استثناءً إذا فشلت العملية. </p> <hr> <pre> string inFile = "input.pdf"; // قد يتم إعادة تعيين TestPath. string outFile = "output.pdf"; // قد يتم إعادة تعيين TestPath. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword("owner", "newuser", "newowner", DocumentPrivilege.Print, KeySize.x256); </pre>

### changePassword {#changePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-}
<p> يغيّر كلمة مرور المستخدم وكلمة المرور باستخدام كلمة مرور المالك، ويسمح بإعادة ضبط أمان مستند Pdf. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغتين أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو null. هناك 6 تركيبات ممكنة لقيم KeySize و Algorithm. ومع ذلك، التركيبان (KeySize.x40, Algorithm.AES) و (KeySize.x256, Algorithm.RC4) غير صالحين وسيتم رفع استثناء مناسب إذا واجه البرنامج هذا التركيب. يرمي استثناءً إذا فشلت العملية. </p> <hr> <pre> string inFile = "input.pdf"; // قد يتم إعادة تعيين TestPath. string outFile = "output.pdf"; // قد يتم إعادة تعيين TestPath. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.changePassword("owner", "newuser", "newowner", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre>

### close {#close--}
```
public void close()
```

يغلق الواجهة.

### decryptFile {#decryptFile-java.lang.String-}
يفك تشفير مستند Pdf مشفر باستخدام كلمة مرور المالك. إذا لم يكن للمستند كلمة مرور مالك، يُسمح باستخدام كلمة مرور المستخدم. يرمي استثناءً إذا فشلت العملية. string inFile = "input.pdf"; // قد يتم إعادة تعيين TestPath. string outFile = "output.pdf"; // قد يتم إعادة تعيين TestPath. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); fileSecurity.decryptFile("ownerpass");

### dispose {#dispose--}
```
public void dispose()
```

يغلق الواجهة.

### encryptFile {#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
<p> يشفر ملف Pdf باستخدام كلمة مرور المستخدم وكلمة مرور المالك ويحدد صلاحيات المستند للوصول. يمكن أن تكون كلمة مرور المستخدم وكلمة مرور المالك فارغتين أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك المدخلة فارغة أو null. يرمي استثناءً إذا فشلت العملية. </p> <hr> <pre> String inFile = "input.pdf"; // قد يتم إعادة تعيين TestPath. String outFile = "output.pdf"; // قد يتم إعادة تعيين TestPath. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.EncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256); </pre>

### encryptFile {#encryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-}
<p> يقوم بتشفير ملف Pdf باستخدام userpassword و ownerpassword ويضبط امتيازات المستند للوصول. يمكن أن تكون كلمة مرور المستخدم وكلمة مرور المالك null أو فارغة. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك المدخلة null أو فارغة. هناك 6 تركيبات ممكنة لقيم KeySize و Algorithm. ومع ذلك (KeySize.x40, Algorithm.AES) و (KeySize.x256, Algorithm.RC4) غير صالحة وسيتم رفع الاستثناء المناسب إذا صادف kit هذه التركيبة. يرفع استثناء إذا فشل العملية. </p> <hr> <pre> String inFile = "input.pdf"; // The TestPath may be // re-assigned. String outFile = "output.pdf"; // The TestPath may be // re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.encryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256, Algorithm.AES); </pre>

### getAllowExceptions {#getAllowExceptions--}
```
@Deprecated public final boolean getAllowExceptions()
```

إذا تم تعيين هذه القيمة إلى true، سيتم رفع استثناء عند فشل العملية. وإلا، تُعيد الطريقة false عند الفشل ويمكن التحقق من الاستثناء الأخير باستخدام الخاصية LastException.

**Returns:**
قيمة منطقية @deprecated هذه الخاصية مهجورة ولا يمكن استخدامها للسماح برمي الاستثناءات.

### getLastException {#getLastException--}
```
public final RuntimeException getLastException()
```

يعيد الاستثناء الذي تم رفعه بواسطة العملية الأخيرة.

**Returns:**
java.lang.RuntimeException

### setAllowExceptions {#setAllowExceptions-boolean-}
```
@Deprecated public final void setAllowExceptions(boolean value)
```

إذا تم تعيين هذه القيمة إلى true، سيتم رفع استثناء عند فشل العملية. وإلا، تُعيد الطريقة false عند الفشل ويمكن التحقق من الاستثناء الأخير باستخدام الخاصية LastException.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية @deprecated هذه الخاصية مهجورة ولا يمكن استخدامها للسماح برمي الاستثناءات. |

### setInputFile {#setInputFile-java.lang.String-}
يضبط ملف الإدخال. Obsolete("Use bindPdf(inputStream) method for facade initialization.")

### setInputStream {#setInputStream-java.io.InputStream-}
يضبط تدفق الإدخال. Obsolete("Use bindPdf(inputStream) method for facade initialization.")

### setOutputFile {#setOutputFile-java.lang.String-}
يضبط ملف الإخراج. Obsolete("Use save(outputStream) method for getting facade results.")

### setOutputStream {#setOutputStream-java.io.OutputStream-}
يضبط تدفق الإخراج. Obsolete("Use save(outputStream) method for getting facade results.")

### setPrivilege {#setPrivilege-com.aspose.pdf.facades.DocumentPrivilege-}
<p> يضبط أمان ملف Pdf باستخدام كلمات مرور المستخدم/المالك فارغة. سيتم إضافة كلمة مرور المالك بسلسلة عشوائية. يرفع استثناء إذا فشلت العملية. </p> <hr> <pre> string inFile = "input.pdf"; // The TestPath may be re-assigned. string outFile = "output.pdf"; // The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(DocumentPrivilege.Print); </pre>

### setPrivilege {#setPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-}
<p> يضبط أمان ملف Pdf باستخدام كلمة المرور الأصلية. يرفع استثناء إذا فشلت العملية. </p> <hr> <pre> string inFile = "input.pdf"; // The TestPath may be re-assigned. string outFile = "output.pdf"; // The TestPath may be re-assigned. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile, outFile); fileSecurity.setPrivilege(userPassword, ownerPassword, DocumentPrivilege.getPrint()); </pre>

### tryChangePassword {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-}
يغيّر كلمة مرور المستخدم وكلمة مرور المالك باستخدام كلمة مرور المالك، ويحافظ على إعدادات الأمان الأصلية. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغتين أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو null. لا يرفع استثناء إذا فشلت العملية. string inFile = "D:\\input.pdf"; //قد يتم إعادة تعيين TestPath. string outFile = "D:\\output.pdf"; //قد يتم إعادة تعيين TestPath. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner");

### tryChangePassword {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
يغيّر كلمة مرور المستخدم وكلمة مرور المالك، ويسمح بإعادة تعيين أمان مستند Pdf. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغتين أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو null. لا يرمي استثناءً إذا فشل العملية. string inFile = ".D:\\input.pdf"; // قد يتم إعادة تعيين TestPath. string outFile = "D:\\output.pdf"; // قد يتم إعادة تعيين TestPath. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryChangePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256);

### tryChangePassword {#tryChangePassword-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-com.aspose.pdf.facades.Algorithm-}
يغيّر كلمة مرور المستخدم وكلمة مرور المالك، ويسمح بإعادة تعيين أمان مستند Pdf. يمكن أن تكون كلمة مرور المستخدم الجديدة وكلمة مرور المالك الجديدة فارغتين أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك الجديدة فارغة أو null. هناك 6 تركيبات ممكنة لقيم KeySize و Algorithm. ومع ذلك (KeySize.x40, Algorithm.AES) و (KeySize.x256, Algorithm.RC4) غير صالحة وسيتم رفع استثناء مناسب إذا واجه البرنامج هذه التركيبة. لا يرمي استثناءً إذا فشل العملية. string inFile = "D:\\input.pdf"; // قد يتم إعادة تعيين TestPath. string outFile = "D:\\output.pdf"; // قد يتم إعادة تعيين TestPath. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.changePassword("owner","newuser","newowner", DocumentPrivilege.Print,KeySize.x256,Algorithm.AES);

### tryDecryptFile {#tryDecryptFile-java.lang.String-}
يفك تشفير مستند Pdf مشفر بواسطة كلمة مرور المالك. إذا لم يكن للمستند كلمة مرور مالك، يُسمح باستخدام كلمة مرور المستخدم. لا يرفع استثناء إذا فشلت العملية. string inFile = "input.pdf"; //قد يتم إعادة تعيين TestPath. string outFile = "output.pdf"; //قد يتم إعادة تعيين TestPath. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.TryDecryptFile("ownerpass");

### tryEncryptFile {#tryEncryptFile-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.facades.KeySize-}
يقوم بتشفير ملف Pdf باستخدام كلمة مرور المستخدم وكلمة مرور المالك ويضبط امتيازات المستند للوصول. يمكن أن تكون كلمة مرور المستخدم وكلمة مرور المالك فارغتين أو null. سيتم استبدال كلمة مرور المالك بسلسلة عشوائية إذا كانت كلمة مرور المالك المدخلة فارغة أو null. لا يرفع استثناء إذا فشلت العملية. string inFile = "input.pdf"; //قد يتم إعادة تعيين TestPath. string outFile = "output.pdf"; //قد يتم إعادة تعيين TestPath. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.tryEncryptFile("userpass", "ownerpass", DocumentPrivilege.Print, KeySize.x256);

### trySetPrivilege {#trySetPrivilege-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-}
يضبط أمان ملف Pdf باستخدام كلمة المرور الأصلية. لا يرمي استثناءً إذا فشل العملية. string inFile = "D:\\input.pdf"; // قد يتم إعادة تعيين TestPath. string outFile = "D:\\output.pdf"; // قد يتم إعادة تعيين TestPath. PdfFileSecurity fileSecurity = new PdfFileSecurity(inFile,outFile); bool result = fileSecurity.trySetPrivilege(userPassword, ownerPassword, DocumentPrivilege.Print);
