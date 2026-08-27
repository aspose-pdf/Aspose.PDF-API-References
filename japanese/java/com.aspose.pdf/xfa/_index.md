---
title: "XFA"
linktitle: "XFA"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "XML Forms Architecture (XFA) に関する XML フォームを表します。"
type: docs
weight: 5550
url: /ja/java/com.aspose.pdf/xfa/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XFA

```
public final class XFA extends Object
```

XML Forms Architecture (XFA) に関する XML フォームを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [appendToTemplate](#appendToTemplate-java.lang.String-java.lang.String-) | XPath式に一致するテンプレートのノードにXML値を追加します |
| [beginCachedUpdates](#beginCachedUpdates--) | キャッシュ更新モードを開始します。XFAへのすべての変更はキャッシュされ、EndCachedUpdates 呼び出し時にドキュメント構造に保存されます。これにより、XFAへの多数の変更が行われた際に、XML パケットをドキュメントに保存する際の冗長な操作を回避し、パフォーマンスを向上させることができます。 |
| [endCachedUpdates](#endCachedUpdates--) | キャッシュ更新を終了し、すべてのデータをドキュメント構造に保存します。 |
| [flattenXfaField](#flattenXfaField-com.aspose.ms.System.Xml.XmlNode-) | XFA フォームのフィールドをフラット化します。 |
| [get_Item](#get_Item-java.lang.String-) | {@code path} に従ってデータノードの値を取得します。 |
| [getConfig](#getConfig--) | XFA フォームの XFA Config コンポーネントです。 |
| [getDatasets](#getDatasets--) | XFA フォームの XFA Datasets コンポーネントです。 |
| [getFieldNames](#getFieldNames--) | フォームテンプレート内のフィールド名の一覧です。 |
| [getFieldsWithTextValuesMap](#getFieldsWithTextValuesMap--) | <p> すべてのフィールドに対して、短いフィールド名とその文字列値のマップを返します。 </p> |
| [getFieldTemplate](#getFieldTemplate-java.lang.String-) | XFA フィールドテンプレートの XML ノードを返します。 |
| [getFieldTemplates](#getFieldTemplates--) | XFA フォーム上のすべてのフィールドテンプレートの一覧を返します。 |
| [getForm](#getForm--) | XFA フォームの XFA Form Component を取得します。 |
| [getNamespaceManager_](#getNamespaceManager_--) | XFA フォームの名前空間を取得します。以下の名前空間が定義されています: "data" はフォームデータ用、"tpl" はフォームテンプレート用です。 |
| [getNamespaceManager](#getNamespaceManager--) | テンプレートとデータで使用される名前空間を持つ名前空間マネージャーを返します。 |
| [getTemplate](#getTemplate--) | XFA フォームの XFA Template コンポーネントです。 |
| [getXDP](#getXDP--) | XML データパッケージ（周囲の XML コンテナ内のすべての XFA フォームコンポーネント）。 |
| [getXfaField](#getXfaField-java.lang.String-) |  |
| [set_Item](#set_Item-java.lang.String-java.lang.String-) | {@code path} に従ってデータノードの値を取得します。 |
| [setFieldImage](#setFieldImage-java.lang.String-java.io.InputStream-) | XFA フィールドの画像を設定します。 |
| [setFieldImageInternal](#setFieldImageInternal-java.lang.String-com.aspose.ms.System.IO.Stream-) |  |
| [tryGetTemplateString](#tryGetTemplateString-java.lang.String-) | XFA フォームから計算スクリプトのエクスポートを試みます。失敗した場合は空文字列を返します。 |

### appendToTemplate {#appendToTemplate-java.lang.String-java.lang.String-}
XPath式に一致するテンプレートのノードにXML値を追加します

### beginCachedUpdates {#beginCachedUpdates--}
```
public void beginCachedUpdates()
```

キャッシュ更新モードを開始します。XFAへのすべての変更はキャッシュされ、EndCachedUpdates 呼び出し時にドキュメント構造に保存されます。これにより、XFAへの多数の変更が行われた際に、XML パケットをドキュメントに保存する際の冗長な操作を回避し、パフォーマンスを向上させることができます。

### endCachedUpdates {#endCachedUpdates--}
```
public void endCachedUpdates()
```

キャッシュ更新を終了し、すべてのデータをドキュメント構造に保存します。

### flattenXfaField {#flattenXfaField-com.aspose.ms.System.Xml.XmlNode-}
XFA フォームのフィールドをフラット化します。

### get_Item {#get_Item-java.lang.String-}
{@code path} に従ってデータノードの値を取得します。

### getConfig {#getConfig--}
```
public com.aspose.ms.System.Xml.XmlNode getConfig()
```

XFA フォームの XFA Config コンポーネントです。

**Returns:**
XmlNode オブジェクト

### getDatasets {#getDatasets--}
```
public com.aspose.ms.System.Xml.XmlNode getDatasets()
```

XFA フォームの XFA Datasets コンポーネントです。

**Returns:**
XmlNode オブジェクト

### getFieldNames {#getFieldNames--}
```
public String [] getFieldNames()
```

フォームテンプレート内のフィールド名の一覧です。

**Returns:**
String 値の配列

### getFieldsWithTextValuesMap {#getFieldsWithTextValuesMap--}
```
public HashMap < String , String > getFieldsWithTextValuesMap()
```

<p> すべてのフィールドに対して、短いフィールド名とその文字列値のマップを返します。 </p>

**Returns:**
{@code HashMap<String, String>} オブジェクト

### getFieldTemplate {#getFieldTemplate-java.lang.String-}
XFA フィールドテンプレートの XML ノードを返します。

### getFieldTemplates {#getFieldTemplates--}
```
public com.aspose.ms.System.Xml.XmlNodeList getFieldTemplates()
```

XFA フォーム上のすべてのフィールドテンプレートの一覧を返します。

**Returns:**
フィールドテンプレートのリスト。

### getForm {#getForm--}
```
public com.aspose.ms.System.Xml.XmlNode getForm()
```

XFA フォームの XFA Form Component を取得します。

**Returns:**
XmlNode オブジェクト

### getNamespaceManager_ {#getNamespaceManager_--}
```
public com.aspose.ms.System.Xml.XmlNamespaceManager getNamespaceManager_()
```

XFA フォームの名前空間を取得します。以下の名前空間が定義されています: "data" はフォームデータ用、"tpl" はフォームテンプレート用です。

**Returns:**
XmlNamespaceManager オブジェクト

### getNamespaceManager {#getNamespaceManager--}
```
public com.aspose.ms.System.Xml.XmlNamespaceManager getNamespaceManager()
```

テンプレートとデータで使用される名前空間を持つ名前空間マネージャーを返します。

**Returns:**
XmlNamespaceManager オブジェクト

### getTemplate {#getTemplate--}
```
public com.aspose.ms.System.Xml.XmlNode getTemplate()
```

XFA フォームの XFA Template コンポーネントです。

**Returns:**
XmlNode オブジェクト

### getXDP {#getXDP--}
```
public com.aspose.ms.System.Xml.XmlDocument getXDP()
```

XML データパッケージ（周囲の XML コンテナ内のすべての XFA フォームコンポーネント）。

**Returns:**
XmlDocument オブジェクト

### getXfaField {#getXfaField-java.lang.String-}


### set_Item {#set_Item-java.lang.String-java.lang.String-}
{@code path} に従ってデータノードの値を取得します。

### setFieldImage {#setFieldImage-java.lang.String-java.io.InputStream-}
XFA フィールドの画像を設定します。

### setFieldImageInternal {#setFieldImageInternal-java.lang.String-com.aspose.ms.System.IO.Stream-}


### tryGetTemplateString {#tryGetTemplateString-java.lang.String-}
XFA フォームから計算スクリプトのエクスポートを試みます。失敗した場合は空文字列を返します。
