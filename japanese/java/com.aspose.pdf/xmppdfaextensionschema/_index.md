---
title: "XmpPdfAExtensionSchema"
linktitle: "XmpPdfAExtensionSchema"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF/A-1 が提供する XMP 拡張スキーマを記述します。"
type: docs
weight: 5720
url: /ja/java/com.aspose.pdf/xmppdfaextensionschema/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XmpPdfAExtensionSchema

```
public class XmpPdfAExtensionSchema extends Object
```

PDF/A-1 が提供する XMP 拡張スキーマを記述します。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [DEFAULT_EXTENSION_NAMESPACE_PREFIX](#DEFAULT_EXTENSION_NAMESPACE_PREFIX) | デフォルト拡張名前空間プレフィックス。 |
| [DEFAULT_EXTENSION_NAMESPACE_URI](#DEFAULT_EXTENSION_NAMESPACE_URI) | デフォルト拡張名前空間 URI。 |
| [DEFAULT_FIELD_NAMESPACE_PREFIX](#DEFAULT_FIELD_NAMESPACE_PREFIX) | デフォルトフィールド名前空間プレフィックス。 |
| [DEFAULT_FIELD_NAMESPACE_URI](#DEFAULT_FIELD_NAMESPACE_URI) | デフォルト拡張名前空間 URI。 |
| [DEFAULT_PROPERTY_NAMESPACE_PREFIX](#DEFAULT_PROPERTY_NAMESPACE_PREFIX) | デフォルトプロパティ名前空間プレフィックス。 |
| [DEFAULT_PROPERTY_NAMESPACE_URI](#DEFAULT_PROPERTY_NAMESPACE_URI) | デフォルトプロパティ名前空間 URI。 |
| [DEFAULT_SCHEMA_NAMESPACE_PREFIX](#DEFAULT_SCHEMA_NAMESPACE_PREFIX) | デフォルトのスキーマ名前空間プレフィックスです。 |
| [DEFAULT_SCHEMA_NAMESPACE_URI](#DEFAULT_SCHEMA_NAMESPACE_URI) | デフォルトのスキーマ名前空間 URIです。 |
| [DEFAULT_VALUE_NAMESPACE_URI](#DEFAULT_VALUE_NAMESPACE_URI) | デフォルトの値名前空間 URIです。 |
| [DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX](#DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX) | デフォルトの値タイプ名前空間プレフィックスです。 |
| [RDF_NAMESPACE_URI](#RDF_NAMESPACE_URI) | デフォルトの RDF 名前空間 URIです。 |
| [RDF_PREFIX](#RDF_PREFIX) | デフォルトの RDF 名前空間プレフィックスです。 |
| [XMLNS](#XMLNS) |  |

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [XmpPdfAExtensionSchema](#XmpPdfAExtensionSchema-com.aspose.pdf.XmpPdfAExtensionSchemaDescription-) | 新しいオブジェクトを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [add](#add-com.aspose.pdf.XmpPdfAExtensionObject-) | スキーマに新しいオブジェクトを追加します。 |
| [contains](#contains-com.aspose.pdf.XmpPdfAExtensionObject-) | オブジェクトがスキーマに存在するかどうかを判定します。 |
| [createDescriptionValueXml](#createDescriptionValueXml-com.aspose.ms.System.Xml.XmlDocument-) | プロパティ値ブロックの説明 XML 要素を作成します。 |
| [createDescriptionXml](#createDescriptionXml-com.aspose.ms.System.Xml.XmlDocument-) | すべてのスキーマの説明 XML 要素を作成します。 |
| [createSchemasElement](#createSchemasElement-com.aspose.ms.System.Xml.XmlNode-) | XML ツリーからスキーマ要素のリストを作成します。 |
| [getDescription](#getDescription--) | スキーマの説明を取得します。 |
| [getObjects1](#getObjects1--) | オブジェクト（プロパティ、値タイプ）のリストを取得します。 |
| [getObjectsInternal](#getObjectsInternal--) | オブジェクト（プロパティ、値タイプ）のリストを取得します。 |
| [getProperty](#getProperty-java.lang.String-) | 名前で PDF/A プロパティを返します。 |
| [getPropertyIndex](#getPropertyIndex-java.lang.String-) | 指定された名前のプロパティのインデックスを返します。 |
| [getSchemaXml](#getSchemaXml-com.aspose.ms.System.Xml.XmlDocument-) | XML ツリーでスキーマを表す XML 要素（タグ - li）を返します。 |
| [getValuesXml](#getValuesXml-com.aspose.ms.System.Xml.XmlDocument-com.aspose.ms.System.Xml.XmlElement-) | プロパティの値を XML ツリー表現として取得します。 |
| [initializeSchemaValue](#initializeSchemaValue-com.aspose.ms.System.Xml.XmlNode-com.aspose.pdf.XmpPdfAExtensionSchema-) | プロパティの値を初期化します。 |
| [isPdfAExtensionPrefix](#isPdfAExtensionPrefix-java.lang.String-) | プレフィックス値が PDF/A 拡張機能の一部かどうかを判定します。 |
| [remove](#remove-com.aspose.pdf.XmpPdfAExtensionObject-) | スキーマからオブジェクトを削除します。 |

### DEFAULT_EXTENSION_NAMESPACE_PREFIX {#DEFAULT_EXTENSION_NAMESPACE_PREFIX}
```
public static final String DEFAULT_EXTENSION_NAMESPACE_PREFIX
```

デフォルト拡張名前空間プレフィックス。

### DEFAULT_EXTENSION_NAMESPACE_URI {#DEFAULT_EXTENSION_NAMESPACE_URI}
```
public static final String DEFAULT_EXTENSION_NAMESPACE_URI
```

デフォルト拡張名前空間 URI。

### DEFAULT_FIELD_NAMESPACE_PREFIX {#DEFAULT_FIELD_NAMESPACE_PREFIX}
```
public static final String DEFAULT_FIELD_NAMESPACE_PREFIX
```

デフォルトフィールド名前空間プレフィックス。

### DEFAULT_FIELD_NAMESPACE_URI {#DEFAULT_FIELD_NAMESPACE_URI}
```
public static final String DEFAULT_FIELD_NAMESPACE_URI
```

デフォルト拡張名前空間 URI。

### DEFAULT_PROPERTY_NAMESPACE_PREFIX {#DEFAULT_PROPERTY_NAMESPACE_PREFIX}
```
public static final String DEFAULT_PROPERTY_NAMESPACE_PREFIX
```

デフォルトプロパティ名前空間プレフィックス。

### DEFAULT_PROPERTY_NAMESPACE_URI {#DEFAULT_PROPERTY_NAMESPACE_URI}
```
public static final String DEFAULT_PROPERTY_NAMESPACE_URI
```

デフォルトプロパティ名前空間 URI。

### DEFAULT_SCHEMA_NAMESPACE_PREFIX {#DEFAULT_SCHEMA_NAMESPACE_PREFIX}
```
public static final String DEFAULT_SCHEMA_NAMESPACE_PREFIX
```

デフォルトのスキーマ名前空間プレフィックスです。

### DEFAULT_SCHEMA_NAMESPACE_URI {#DEFAULT_SCHEMA_NAMESPACE_URI}
```
public static final String DEFAULT_SCHEMA_NAMESPACE_URI
```

デフォルトのスキーマ名前空間 URIです。

### DEFAULT_VALUE_NAMESPACE_URI {#DEFAULT_VALUE_NAMESPACE_URI}
```
public static final String DEFAULT_VALUE_NAMESPACE_URI
```

デフォルトの値名前空間 URIです。

### DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX {#DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX}
```
public static final String DEFAULT_VALUE_TYPE_NAMESPACE_PREFIX
```

デフォルトの値タイプ名前空間プレフィックスです。

### RDF_NAMESPACE_URI {#RDF_NAMESPACE_URI}
```
public static final String RDF_NAMESPACE_URI
```

デフォルトの RDF 名前空間 URIです。

### RDF_PREFIX {#RDF_PREFIX}
```
public static final String RDF_PREFIX
```

デフォルトの RDF 名前空間プレフィックスです。

### XMLNS {#XMLNS}
```
public static final String XMLNS
```



### XmpPdfAExtensionSchema {#XmpPdfAExtensionSchema-com.aspose.pdf.XmpPdfAExtensionSchemaDescription-}
新しいオブジェクトを初期化します。

### add {#add-com.aspose.pdf.XmpPdfAExtensionObject-}
スキーマに新しいオブジェクトを追加します。

### contains {#contains-com.aspose.pdf.XmpPdfAExtensionObject-}
オブジェクトがスキーマに存在するかどうかを判定します。

### createDescriptionValueXml {#createDescriptionValueXml-com.aspose.ms.System.Xml.XmlDocument-}
プロパティ値ブロックの説明 XML 要素を作成します。

### createDescriptionXml {#createDescriptionXml-com.aspose.ms.System.Xml.XmlDocument-}
すべてのスキーマの説明 XML 要素を作成します。

### createSchemasElement {#createSchemasElement-com.aspose.ms.System.Xml.XmlNode-}
XML ツリーからスキーマ要素のリストを作成します。

### getDescription {#getDescription--}
```
public XmpPdfAExtensionSchemaDescription getDescription()
```

スキーマの説明を取得します。

**Returns:**
XmpPdfAExtensionSchemaDescription

### getObjects1 {#getObjects1--}
```
public List getObjects1()
```

オブジェクト（プロパティ、値タイプ）のリストを取得します。

**Returns:**
ArrayList

### getObjectsInternal {#getObjectsInternal--}
```
public com.aspose.ms.System.Collections.Generic.List< XmpPdfAExtensionObject > getObjectsInternal()
```

オブジェクト（プロパティ、値タイプ）のリストを取得します。

**Returns:**
ArrayList

### getProperty {#getProperty-java.lang.String-}
名前で PDF/A プロパティを返します。

### getPropertyIndex {#getPropertyIndex-java.lang.String-}
指定された名前のプロパティのインデックスを返します。

### getSchemaXml {#getSchemaXml-com.aspose.ms.System.Xml.XmlDocument-}
XML ツリーでスキーマを表す XML 要素（タグ - li）を返します。

### getValuesXml {#getValuesXml-com.aspose.ms.System.Xml.XmlDocument-com.aspose.ms.System.Xml.XmlElement-}
プロパティの値を XML ツリー表現として取得します。

### initializeSchemaValue {#initializeSchemaValue-com.aspose.ms.System.Xml.XmlNode-com.aspose.pdf.XmpPdfAExtensionSchema-}
プロパティの値を初期化します。

### isPdfAExtensionPrefix {#isPdfAExtensionPrefix-java.lang.String-}
プレフィックス値が PDF/A 拡張機能の一部かどうかを判定します。

### remove {#remove-com.aspose.pdf.XmpPdfAExtensionObject-}
スキーマからオブジェクトを削除します。
