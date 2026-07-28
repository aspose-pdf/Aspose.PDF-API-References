---
title: "SignatureLengthMismatchException"
linktitle: "SignatureLengthMismatchException"
second_title: "Aspose.PDF for Java API Referansı"
description: "PDF imzalama sırasında oluşan hataları temsil eder. {@code SignHash} bir belgeyi imzalamak için kullanılırsa ve imzanın gerçek uzunluğu belirtilen değerden daha büyükse ortaya çıkar."
type: docs
weight: 310
url: /tr/java/com.aspose.pdf.exceptions/signaturelengthmismatchexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable java.lang.Exception java.lang.RuntimeException com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, java.lang.Throwable, java.lang.Exception java.lang.RuntimeException com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, java.lang.Exception, java.lang.RuntimeException com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, java.lang.RuntimeException, com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, com.aspose.ms.System.Exception, com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, com.aspose.ms.System.ApplicationException, com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, com.aspose.pdf.exceptions.PdfException, com.aspose.pdf.exceptions.SignatureLengthMismatchException

**All Implemented Interfaces:**
Serializable

```
public class SignatureLengthMismatchException extends PdfException
```

PDF imzalaması sırasında oluşan hataları temsil eder. {@code SignHash} bir belgeyi imzalamak için kullanılırsa ve imzanın gerçek uzunluğu {@code Signature.DefaultSignatureLength}({@code Signature#getDefaultSignatureLength}/{@code Signature#setDefaultSignatureLength(int)}) seçeneğinde belirtilenden daha büyükse ortaya çıkar.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SignatureLengthMismatchException](#SignatureLengthMismatchException-int-) | Gerçek bir imza uzunluğuna göre {@code SignatureLengthMismatchException} sınıfının bir örneğini oluşturur. |

### SignatureLengthMismatchException {#SignatureLengthMismatchException-int-}
```
public SignatureLengthMismatchException(int actualSignatureLength)
```

Gerçek bir imza uzunluğuna göre {@code SignatureLengthMismatchException} sınıfının bir örneğini oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| actualSignatureLength |  | İmzanın bayt cinsinden gerçek uzunluğu. |
