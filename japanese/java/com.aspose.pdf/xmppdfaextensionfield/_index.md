---
title: "XmpPdfAExtensionField"
linktitle: "XmpPdfAExtensionField"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "このスキーマは構造化型のフィールドを記述します。PDF/A プロパティ値タイプスキーマと非常に似ていますが、プロパティではなく構造内のフィールドを定義します。スキーマ。"
type: docs
weight: 5690
url: /ja/java/com.aspose.pdf/xmppdfaextensionfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XmpPdfAExtensionObject com.aspose.pdf.XmpPdfAExtensionField, com.aspose.pdf.XmpPdfAExtensionObject, com.aspose.pdf.XmpPdfAExtensionField

```
public class XmpPdfAExtensionField extends XmpPdfAExtensionObject
```

このスキーマは構造化タイプのフィールドを記述します。PDF/A プロパティ値タイプスキーマと非常に似ていますが、プロパティの代わりに構造内のフィールドを定義します。スキーマ名前空間 URI: http://www.aiim.org/pdfa/ns/field# 必要なスキーマ名前空間プレフィックス: pdfaField。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [XmpPdfAExtensionField](#XmpPdfAExtensionField-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | オブジェクトを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getName](#getName--) | フィールド名。フィールド名は有効な XML 要素名でなければなりません。 |
| [getValueType](#getValueType--) | フィールド値タイプは XMP Specification 2004 から取得するか、埋め込み PDF/A 値タイプ拡張スキーマから取得します。事前定義された XMP タイプ名またはカスタムタイプ名です。 |
| [getXml_](#getXml_-com.aspose.ms.System.Xml.XmlDocument-) | XML ツリー内でフィールドを表す XML 要素のリストを返します。 |
| [getXmlInternal](#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-) | XML ツリー内でフィールドを表す XML 要素のリストを返します。 |

### XmpPdfAExtensionField {#XmpPdfAExtensionField-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
オブジェクトを初期化します。

### getName {#getName--}
```
public String getName()
```

フィールド名。フィールド名は有効な XML 要素名でなければなりません。

**Returns:**
文字列

### getValueType {#getValueType--}
```
public String getValueType()
```

フィールド値タイプは XMP Specification 2004 から取得するか、埋め込み PDF/A 値タイプ拡張スキーマから取得します。事前定義された XMP タイプ名またはカスタムタイプ名です。

**Returns:**
文字列

### getXml_ {#getXml_-com.aspose.ms.System.Xml.XmlDocument-}
XML ツリー内でフィールドを表す XML 要素のリストを返します。

### getXmlInternal {#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-}
XML ツリー内でフィールドを表す XML 要素のリストを返します。
