---
title: "SignatureLengthMismatchException"
linktitle: "SignatureLengthMismatchException"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل الأخطاء التي تحدث أثناء توقيع PDF. يحدث إذا تم استخدام {@code SignHash} لتوقيع مستند وكان الطول الفعلي للتوقيع أكبر من المحدد في."
type: docs
weight: 310
url: /ar/java/com.aspose.pdf.exceptions/signaturelengthmismatchexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable java.lang.Exception java.lang.RuntimeException com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, java.lang.Throwable, java.lang.Exception java.lang.RuntimeException com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, java.lang.Exception, java.lang.RuntimeException com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, java.lang.RuntimeException, com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, com.aspose.ms.System.Exception, com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, com.aspose.ms.System.ApplicationException, com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, com.aspose.pdf.exceptions.PdfException, com.aspose.pdf.exceptions.SignatureLengthMismatchException

**All Implemented Interfaces:**
Serializable

```
public class SignatureLengthMismatchException extends PdfException
```

يمثل الأخطاء التي تحدث أثناء توقيع PDF. يحدث إذا تم استخدام {@code SignHash} لتوقيع مستند وكان الطول الفعلي للتوقيع أكبر من ذلك المحدد في خيار {@code Signature.DefaultSignatureLength}({@code Signature#getDefaultSignatureLength}/{@code Signature#setDefaultSignatureLength(int)}).

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [SignatureLengthMismatchException](#SignatureLengthMismatchException-int-) | ينشئ مثيلًا من {@code SignatureLengthMismatchException} بطول توقيع فعلي. |

### SignatureLengthMismatchException {#SignatureLengthMismatchException-int-}
```
public SignatureLengthMismatchException(int actualSignatureLength)
```

ينشئ مثيلًا من {@code SignatureLengthMismatchException} بطول توقيع فعلي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| actualSignatureLength |  | الطول الفعلي للتوقيع بالبايت. |
