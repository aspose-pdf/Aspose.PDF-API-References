---
title: "SignatureLengthMismatchException"
linktitle: "SignatureLengthMismatchException"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar fel som uppstår under PDF‑signering. Uppstår om {@code SignHash} används för att signera ett dokument och den faktiska signaturens längd är större än den som specificerats i."
type: docs
weight: 310
url: /sv/java/com.aspose.pdf.exceptions/signaturelengthmismatchexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable java.lang.Exception java.lang.RuntimeException com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, java.lang.Throwable, java.lang.Exception java.lang.RuntimeException com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, java.lang.Exception, java.lang.RuntimeException com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, java.lang.RuntimeException, com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, com.aspose.ms.System.Exception, com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, com.aspose.ms.System.ApplicationException, com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, com.aspose.pdf.exceptions.PdfException, com.aspose.pdf.exceptions.SignatureLengthMismatchException

**All Implemented Interfaces:**
Serialiserbar

```
public class SignatureLengthMismatchException extends PdfException
```

Representerar fel som uppstår under PDF-signering. Uppstår om {@code SignHash} används för att signera ett dokument och den faktiska längden på signaturen är större än den som anges i alternativet {@code Signature.DefaultSignatureLength}({@code Signature#getDefaultSignatureLength}/{@code Signature#setDefaultSignatureLength(int)}).

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [SignatureLengthMismatchException](#SignatureLengthMismatchException-int-) | Skapar en instans av {@code SignatureLengthMismatchException} med en faktisk signaturlängd. |

### SignatureLengthMismatchException {#SignatureLengthMismatchException-int-}
```
public SignatureLengthMismatchException(int actualSignatureLength)
```

Skapar en instans av {@code SignatureLengthMismatchException} med en faktisk signaturlängd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| actualSignatureLength |  | Den faktiska längden på signaturen i byte. |
