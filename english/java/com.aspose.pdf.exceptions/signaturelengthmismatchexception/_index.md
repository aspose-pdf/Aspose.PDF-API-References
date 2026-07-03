---
title: SignatureLengthMismatchException
linktitle: SignatureLengthMismatchException
second_title: Aspose.PDF for Java API Reference
description: Represents errors that occur during PDF signing. Occurs if {@code SignHash} is used to sign a document and the actual length of the signature is greater than that specified in.
type: docs
weight: 310
url: /java/com.aspose.pdf.exceptions/signaturelengthmismatchexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable java.lang.Exception java.lang.RuntimeException com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, java.lang.Throwable, java.lang.Exception java.lang.RuntimeException com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, java.lang.Exception, java.lang.RuntimeException com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, java.lang.RuntimeException, com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, com.aspose.ms.System.Exception, com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, com.aspose.ms.System.ApplicationException, com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, com.aspose.pdf.exceptions.PdfException, com.aspose.pdf.exceptions.SignatureLengthMismatchException

**All Implemented Interfaces:**
Serializable

```
public class SignatureLengthMismatchException extends PdfException
```

Represents errors that occur during PDF signing. Occurs if {@code SignHash} is used to sign a document and the actual length of the signature is greater than that specified in the {@code Signature.DefaultSignatureLength}({@code Signature#getDefaultSignatureLength}/{@code Signature#setDefaultSignatureLength(int)}) option.

## Constructors

| Constructor | Description |
| --- | --- |
| [SignatureLengthMismatchException](#SignatureLengthMismatchException-int-) | Creates an instance of {@code SignatureLengthMismatchException} by an actual signature length. |

### SignatureLengthMismatchException {#SignatureLengthMismatchException-int-}
```
public SignatureLengthMismatchException(int actualSignatureLength)
```

Creates an instance of {@code SignatureLengthMismatchException} by an actual signature length.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| actualSignatureLength |  | The actual length of signature in bytes. |
