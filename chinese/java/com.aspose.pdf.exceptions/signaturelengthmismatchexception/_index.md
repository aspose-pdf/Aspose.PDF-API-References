---
title: "SignatureLengthMismatchException"
linktitle: "SignatureLengthMismatchException"
second_title: "Aspose.PDF for Java API 参考"
description: "表示在 PDF 签名期间发生的错误。如果使用 {@code SignHash} 对文档进行签名，并且签名的实际长度大于指定的长度，则会发生此错误。"
type: docs
weight: 310
url: /zh/java/com.aspose.pdf.exceptions/signaturelengthmismatchexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable java.lang.Exception java.lang.RuntimeException com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, java.lang.Throwable, java.lang.Exception java.lang.RuntimeException com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, java.lang.Exception, java.lang.RuntimeException com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, java.lang.RuntimeException, com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, com.aspose.ms.System.Exception, com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, com.aspose.ms.System.ApplicationException, com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, com.aspose.pdf.exceptions.PdfException, com.aspose.pdf.exceptions.SignatureLengthMismatchException

**All Implemented Interfaces:**
可序列化

```
public class SignatureLengthMismatchException extends PdfException
```

表示在 PDF 签名期间出现的错误。如果使用 {@code SignHash} 对文档进行签名，并且签名的实际长度大于 {@code Signature.DefaultSignatureLength}（{@code Signature#getDefaultSignatureLength}/{@code Signature#setDefaultSignatureLength(int)}）选项中指定的长度，则会出现此错误。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SignatureLengthMismatchException](#SignatureLengthMismatchException-int-) | 通过实际签名长度创建 {@code SignatureLengthMismatchException} 的实例。 |

### SignatureLengthMismatchException {#SignatureLengthMismatchException-int-}
```
public SignatureLengthMismatchException(int actualSignatureLength)
```

通过实际签名长度创建 {@code SignatureLengthMismatchException} 的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| actualSignatureLength |  | 签名的实际长度（字节）。 |
