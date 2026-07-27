---
title: "SignatureLengthMismatchException"
linktitle: "SignatureLengthMismatchException"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa erros que ocorrem durante a assinatura de PDF. Ocorre se {@code SignHash} for usado para assinar um documento e o comprimento real da assinatura for maior que o especificado em."
type: docs
weight: 310
url: /pt/java/com.aspose.pdf.exceptions/signaturelengthmismatchexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable java.lang.Exception java.lang.RuntimeException com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, java.lang.Throwable, java.lang.Exception java.lang.RuntimeException com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, java.lang.Exception, java.lang.RuntimeException com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, java.lang.RuntimeException, com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, com.aspose.ms.System.Exception, com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, com.aspose.ms.System.ApplicationException, com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, com.aspose.pdf.exceptions.PdfException, com.aspose.pdf.exceptions.SignatureLengthMismatchException

**All Implemented Interfaces:**
Serializable

```
public class SignatureLengthMismatchException extends PdfException
```

Representa erros que ocorrem durante a assinatura de PDF. Ocorre se {@code SignHash} for usado para assinar um documento e o comprimento real da assinatura for maior que o especificado na opção {@code Signature.DefaultSignatureLength}({@code Signature#getDefaultSignatureLength}/{@code Signature#setDefaultSignatureLength(int)}).

## Construtores

| Construtor | Descrição |
| --- | --- |
| [SignatureLengthMismatchException](#SignatureLengthMismatchException-int-) | Cria uma instância de {@code SignatureLengthMismatchException} a partir de um comprimento real da assinatura. |

### SignatureLengthMismatchException {#SignatureLengthMismatchException-int-}
```
public SignatureLengthMismatchException(int actualSignatureLength)
```

Cria uma instância de {@code SignatureLengthMismatchException} a partir de um comprimento real da assinatura.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| actualSignatureLength |  | O comprimento real da assinatura em bytes. |
