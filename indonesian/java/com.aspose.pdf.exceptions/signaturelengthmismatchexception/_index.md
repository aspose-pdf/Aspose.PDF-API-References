---
title: "SignatureLengthMismatchException"
linktitle: "SignatureLengthMismatchException"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili kesalahan yang terjadi selama penandatanganan PDF. Terjadi jika {@code SignHash} digunakan untuk menandatangani dokumen dan panjang sebenarnya dari tanda tangan lebih besar daripada yang ditentukan dalam."
type: docs
weight: 310
url: /id/java/com.aspose.pdf.exceptions/signaturelengthmismatchexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable java.lang.Exception java.lang.RuntimeException com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, java.lang.Throwable, java.lang.Exception java.lang.RuntimeException com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, java.lang.Exception, java.lang.RuntimeException com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, java.lang.RuntimeException, com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, com.aspose.ms.System.Exception, com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, com.aspose.ms.System.ApplicationException, com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, com.aspose.pdf.exceptions.PdfException, com.aspose.pdf.exceptions.SignatureLengthMismatchException

**All Implemented Interfaces:**
Serializable

```
public class SignatureLengthMismatchException extends PdfException
```

Mewakili kesalahan yang terjadi selama penandatanganan PDF. Terjadi jika {@code SignHash} digunakan untuk menandatangani dokumen dan panjang sebenarnya dari tanda tangan lebih besar daripada yang ditentukan dalam opsi {@code Signature.DefaultSignatureLength}({@code Signature#getDefaultSignatureLength}/{@code Signature#setDefaultSignatureLength(int)}).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [SignatureLengthMismatchException](#SignatureLengthMismatchException-int-) | Membuat sebuah instance dari {@code SignatureLengthMismatchException} berdasarkan panjang tanda tangan yang sebenarnya. |

### SignatureLengthMismatchException {#SignatureLengthMismatchException-int-}
```
public SignatureLengthMismatchException(int actualSignatureLength)
```

Membuat sebuah instance dari {@code SignatureLengthMismatchException} berdasarkan panjang tanda tangan yang sebenarnya.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| actualSignatureLength |  | Panjang sebenarnya dari tanda tangan dalam byte. |
