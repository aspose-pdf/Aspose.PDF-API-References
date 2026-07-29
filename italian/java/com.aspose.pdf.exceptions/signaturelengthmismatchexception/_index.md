---
title: "SignatureLengthMismatchException"
linktitle: "SignatureLengthMismatchException"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta gli errori che si verificano durante la firma PDF. Si verifica se {@code SignHash} viene utilizzato per firmare un documento e la lunghezza effettiva della firma è maggiore di quella specificata in."
type: docs
weight: 310
url: /it/java/com.aspose.pdf.exceptions/signaturelengthmismatchexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable java.lang.Exception java.lang.RuntimeException com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, java.lang.Throwable, java.lang.Exception java.lang.RuntimeException com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, java.lang.Exception, java.lang.RuntimeException com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, java.lang.RuntimeException, com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, com.aspose.ms.System.Exception, com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, com.aspose.ms.System.ApplicationException, com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, com.aspose.pdf.exceptions.PdfException, com.aspose.pdf.exceptions.SignatureLengthMismatchException

**All Implemented Interfaces:**
Serializable

```
public class SignatureLengthMismatchException extends PdfException
```

Rappresenta gli errori che si verificano durante la firma PDF. Si verifica se {@code SignHash} viene utilizzato per firmare un documento e la lunghezza effettiva della firma è maggiore di quella specificata nell'opzione {@code Signature.DefaultSignatureLength}({@code Signature#getDefaultSignatureLength}/{@code Signature#setDefaultSignatureLength(int)}).

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SignatureLengthMismatchException](#SignatureLengthMismatchException-int-) | Crea un'istanza di {@code SignatureLengthMismatchException} utilizzando la lunghezza effettiva della firma. |

### SignatureLengthMismatchException {#SignatureLengthMismatchException-int-}
```
public SignatureLengthMismatchException(int actualSignatureLength)
```

Crea un'istanza di {@code SignatureLengthMismatchException} utilizzando la lunghezza effettiva della firma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| actualSignatureLength |  | La lunghezza effettiva della firma in byte. |
