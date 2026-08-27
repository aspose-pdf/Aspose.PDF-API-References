---
title: "SignatureLengthMismatchException"
linktitle: "SignatureLengthMismatchException"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente les erreurs qui surviennent lors de la signature PDF. Se produit si {@code SignHash} est utilisé pour signer un document et que la longueur réelle de la signature est supérieure à celle spécifiée dans."
type: docs
weight: 310
url: /fr/java/com.aspose.pdf.exceptions/signaturelengthmismatchexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable java.lang.Exception java.lang.RuntimeException com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, java.lang.Throwable, java.lang.Exception java.lang.RuntimeException com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, java.lang.Exception, java.lang.RuntimeException com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, java.lang.RuntimeException, com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, com.aspose.ms.System.Exception, com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, com.aspose.ms.System.ApplicationException, com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, com.aspose.pdf.exceptions.PdfException, com.aspose.pdf.exceptions.SignatureLengthMismatchException

**All Implemented Interfaces:**
Serializable

```
public class SignatureLengthMismatchException extends PdfException
```

Représente les erreurs qui surviennent lors de la signature PDF. Se produit si {@code SignHash} est utilisé pour signer un document et que la longueur réelle de la signature est supérieure à celle spécifiée dans l'option {@code Signature.DefaultSignatureLength}({@code Signature#getDefaultSignatureLength}/{@code Signature#setDefaultSignatureLength(int)}).

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SignatureLengthMismatchException](#SignatureLengthMismatchException-int-) | Crée une instance de {@code SignatureLengthMismatchException} à partir d'une longueur de signature réelle. |

### SignatureLengthMismatchException {#SignatureLengthMismatchException-int-}
```
public SignatureLengthMismatchException(int actualSignatureLength)
```

Crée une instance de {@code SignatureLengthMismatchException} à partir d'une longueur de signature réelle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| actualSignatureLength |  | La longueur réelle de la signature en octets. |
