---
title: "XmpPdfAExtensionValueType"
linktitle: "XmpPdfAExtensionValueType"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF/A ValueType スキーマは、XMP 2004 仕様で定義されていないすべてのプロパティ値タイプ、すなわち以下のリストに含まれない値タイプに対して必須です：-。"
type: docs
weight: 5740
url: /ja/java/com.aspose.pdf/xmppdfaextensionvaluetype/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XmpPdfAExtensionObject com.aspose.pdf.XmpPdfAExtensionValueType, com.aspose.pdf.XmpPdfAExtensionObject, com.aspose.pdf.XmpPdfAExtensionValueType

```
public final class XmpPdfAExtensionValueType extends XmpPdfAExtensionObject
```

PDF/A ValueType スキーマは、XMP 2004 仕様で定義されていないすべてのプロパティ値タイプに必要です。つまり、以下のリストに含まれない値タイプです: - Array types (these are container types which may contain one or more fields): Alt, Bag, Seq - Basic value types: Boolean, (open and closed) Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - Media Management value types: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - Basic Job/Workflow value type: Job - EXIF schema value types: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational スキーマ名前空間 URI: http://www.aiim.org/pdfa/ns/type# 必要なスキーマ名前空間プレフィックス: pdfaType

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [XmpPdfAExtensionValueType](#XmpPdfAExtensionValueType-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | 新しいオブジェクトを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [add](#add-com.aspose.pdf.XmpPdfAExtensionField-) | 新しいフィールドを追加します。 |
| [addRange](#addRange-com.aspose.pdf.XmpPdfAExtensionField:A-) | フィールドの範囲を追加します。 |
| [clear](#clear--) | すべてのフィールドをクリアします。 |
| [getFields](#getFields--) | フィールドのリストを取得します。 |
| [getNamespaceUri](#getNamespaceUri--) | 名前空間 URI を取得します。 |
| [getPrefix](#getPrefix--) | プレフィックスを取得します。 |
| [getType](#getType--) | 値タイプを取得します。 |
| [getXml_](#getXml_-com.aspose.ms.System.Xml.XmlDocument-) | XML ツリー内でフィールドを表す XML 要素のリストを返します。 |
| [getXmlInternal](#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-) | XML ツリー内で値タイプを表す XML 要素のリストを返します。 |
| [remove](#remove-com.aspose.pdf.XmpPdfAExtensionField-) | フィールドのリストからフィールドを削除します。 |

### XmpPdfAExtensionValueType {#XmpPdfAExtensionValueType-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
新しいオブジェクトを初期化します。

### add {#add-com.aspose.pdf.XmpPdfAExtensionField-}
新しいフィールドを追加します。

### addRange {#addRange-com.aspose.pdf.XmpPdfAExtensionField:A-}
フィールドの範囲を追加します。

### clear {#clear--}
```
public void clear()
```

すべてのフィールドをクリアします。

### getFields {#getFields--}
```
public com.aspose.ms.System.Collections.Generic.List< XmpPdfAExtensionField > getFields()
```

フィールドのリストを取得します。

**Returns:**
IList

### getNamespaceUri {#getNamespaceUri--}
```
public String getNamespaceUri()
```

名前空間 URI を取得します。

**Returns:**
文字列

### getPrefix {#getPrefix--}
```
public String getPrefix()
```

プレフィックスを取得します。

**Returns:**
文字列

### getType {#getType--}
```
public String getType()
```

値タイプを取得します。

**Returns:**
文字列

### getXml_ {#getXml_-com.aspose.ms.System.Xml.XmlDocument-}
XML ツリー内でフィールドを表す XML 要素のリストを返します。

### getXmlInternal {#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-}
XML ツリー内で値タイプを表す XML 要素のリストを返します。

### remove {#remove-com.aspose.pdf.XmpPdfAExtensionField-}
フィールドのリストからフィールドを削除します。
