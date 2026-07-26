---
title: "SignatureField"
linktitle: "SignatureField"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "署名フォームフィールドを表します。"
type: docs
weight: 4510
url: /ja/java/com.aspose.pdf/signaturefield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.SignatureField, com.aspose.pdf.Field, com.aspose.pdf.SignatureField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public final class SignatureField extends Field
```

署名フォームフィールドを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SignatureField](#SignatureField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | 新しい {@code SignatureField} クラスのインスタンスを初期化します。 |
| [SignatureField](#SignatureField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | 新しい {@code SignatureField} クラスのインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [clear](#clear--) | フィールドから署名オブジェクトを削除します。 |
| [extractCertificate](#extractCertificate--) | 単一の X.509 証明書を DER 形式のストリームとして抽出します。 |
| [extractCertificateObject](#extractCertificateObject--) | 単一の X.509 証明書オブジェクトを抽出します。 |
| [extractImage](#extractImage--) | 署名の画像を JPEG エンコードされたストリームとして抽出します。 |
| [extractImage](#extractImage-com.aspose.pdf.ImageType-) | 署名の画像を JPEG エンコードされたストリームとして抽出します。 |
| [getSignature](#getSignature--) | 署名オブジェクトを取得します。このオブジェクトは公開鍵暗号標準に関する署名データを含みます。クラス {@code PKCS1}、{@code PKCS7}、{@code PKCS7Detached} は、サポートされているすべての署名オブジェクトタイプを表します。 |
| [sign](#sign-com.aspose.pdf.Signature-) | この署名フィールドを使用してドキュメントに署名します。 |
| [sign](#sign-com.aspose.pdf.Signature-java.io.InputStream-java.lang.String-) | この署名フィールドを使用してドキュメントに署名します。 |

### SignatureField {#SignatureField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
新しい {@code SignatureField} クラスのインスタンスを初期化します。

### SignatureField {#SignatureField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
新しい {@code SignatureField} クラスのインスタンスを初期化します。

### clear {#clear--}
```
public void clear()
```

フィールドから署名オブジェクトを削除します。

### extractCertificate {#extractCertificate--}
```
public InputStream extractCertificate()
```

単一の X.509 証明書を DER 形式のストリームとして抽出します。

**Returns:**
証明書が見つかった場合は単一の X.509 証明書を返し、そうでない場合は null を返します。

### extractCertificateObject {#extractCertificateObject--}
```
public final com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2 extractCertificateObject()
```

単一の X.509 証明書オブジェクトを抽出します。

**Returns:**
証明書が見つかった場合は単一の X.509 証明書を返し、そうでない場合は null を返します。

### extractImage {#extractImage--}
```
public InputStream extractImage()
```

署名の画像を JPEG エンコードされたストリームとして抽出します。

**Returns:**
画像が正常に見つかった場合は JPEG エンコードされたストリームオブジェクトを返し、そうでない場合は null を返します。

### extractImage {#extractImage-com.aspose.pdf.ImageType-}
署名の画像を JPEG エンコードされたストリームとして抽出します。

**Returns:**
画像が正常に見つかった場合は JPEG エンコードされたストリームオブジェクトを返し、そうでない場合は null を返します。

### getSignature {#getSignature--}
```
public final Signature getSignature()
```

署名オブジェクトを取得します。このオブジェクトは公開鍵暗号標準に関する署名データを含みます。クラス {@code PKCS1}、{@code PKCS7}、{@code PKCS7Detached} は、サポートされているすべての署名オブジェクトタイプを表します。

**Returns:**
署名オブジェクト

### sign {#sign-com.aspose.pdf.Signature-}
この署名フィールドを使用してドキュメントに署名します。

### sign {#sign-com.aspose.pdf.Signature-java.io.InputStream-java.lang.String-}
この署名フィールドを使用してドキュメントに署名します。
