---
title: "SignatureLengthMismatchException"
linktitle: "SignatureLengthMismatchException"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt Fehler dar, die beim PDF-Signieren auftreten. Tritt auf, wenn {@code SignHash} verwendet wird, um ein Dokument zu signieren, und die tatsächliche Länge der Signatur größer ist als die angegebene."
type: docs
weight: 310
url: /de/java/com.aspose.pdf.exceptions/signaturelengthmismatchexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable java.lang.Exception java.lang.RuntimeException com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, java.lang.Throwable, java.lang.Exception java.lang.RuntimeException com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, java.lang.Exception, java.lang.RuntimeException com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, java.lang.RuntimeException, com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, com.aspose.ms.System.Exception, com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, com.aspose.ms.System.ApplicationException, com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, com.aspose.pdf.exceptions.PdfException, com.aspose.pdf.exceptions.SignatureLengthMismatchException

**All Implemented Interfaces:**
Serializable

```
public class SignatureLengthMismatchException extends PdfException
```

Stellt Fehler dar, die beim PDF-Signieren auftreten. Tritt auf, wenn {@code SignHash} verwendet wird, um ein Dokument zu signieren, und die tatsächliche Länge der Signatur größer ist als die in der {@code Signature.DefaultSignatureLength}({@code Signature#getDefaultSignatureLength}/{@code Signature#setDefaultSignatureLength(int)})‑Option angegebene.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SignatureLengthMismatchException](#SignatureLengthMismatchException-int-) | Erstellt eine Instanz von {@code SignatureLengthMismatchException} anhand einer tatsächlichen Signaturlänge. |

### SignatureLengthMismatchException {#SignatureLengthMismatchException-int-}
```
public SignatureLengthMismatchException(int actualSignatureLength)
```

Erstellt eine Instanz von {@code SignatureLengthMismatchException} anhand einer tatsächlichen Signaturlänge.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| actualSignatureLength |  | Die tatsächliche Länge der Signatur in Bytes. |
