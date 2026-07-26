---
title: "SignatureLengthMismatchException"
linktitle: "SignatureLengthMismatchException"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF 署名中に発生するエラーを表します。{@code SignHash} を使用して文書に署名し、実際の署名長が指定された長さを超える場合に発生します。"
type: docs
weight: 310
url: /ja/java/com.aspose.pdf.exceptions/signaturelengthmismatchexception/
---
**Inheritance:**
java.lang.Object, java.lang.Throwable java.lang.Exception java.lang.RuntimeException com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, java.lang.Throwable, java.lang.Exception java.lang.RuntimeException com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, java.lang.Exception, java.lang.RuntimeException com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, java.lang.RuntimeException, com.aspose.ms.System.Exception com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, com.aspose.ms.System.Exception, com.aspose.ms.System.ApplicationException com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, com.aspose.ms.System.ApplicationException, com.aspose.pdf.exceptions.PdfException com.aspose.pdf.exceptions.SignatureLengthMismatchException, com.aspose.pdf.exceptions.PdfException, com.aspose.pdf.exceptions.SignatureLengthMismatchException

**All Implemented Interfaces:**
Serializable

```
public class SignatureLengthMismatchException extends PdfException
```

PDF 署名中に発生するエラーを表します。{@code SignHash} を使用してドキュメントに署名し、署名の実際の長さが {@code Signature.DefaultSignatureLength}（{@code Signature#getDefaultSignatureLength}/{@code Signature#setDefaultSignatureLength(int)}）オプションで指定された長さを超える場合に発生します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SignatureLengthMismatchException](#SignatureLengthMismatchException-int-) | 実際の署名長さで {@code SignatureLengthMismatchException} のインスタンスを作成します。 |

### SignatureLengthMismatchException {#SignatureLengthMismatchException-int-}
```
public SignatureLengthMismatchException(int actualSignatureLength)
```

実際の署名長さで {@code SignatureLengthMismatchException} のインスタンスを作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| actualSignatureLength |  | 署名の実際の長さ（バイト単位）。 |
