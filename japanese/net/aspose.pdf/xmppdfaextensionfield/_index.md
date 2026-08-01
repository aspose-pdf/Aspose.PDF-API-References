---
title: "クラス XmpPdfAExtensionField"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.XmpPdfAExtensionField クラス。このスキーマは構造化タイプのフィールドを記述します。PDF/A プロパティ値タイプ スキーマと非常に類似していますが、プロパティの代わりに構造内のフィールドを定義します。スキーマ 名前空間 URI http//www.aiim.org/pdfa/ns/field 必須スキーマ 名前空間 プレフィックス pdfaField"
type: docs
weight: 11630
url: /ja/net/aspose.pdf/xmppdfaextensionfield/
---
## XmpPdfAExtensionField class

このスキーマは構造化型のフィールドを記述します。PDF/A プロパティ値タイプスキーマに非常に似ていますが、プロパティではなく構造体内のフィールドを定義します。スキーマ名前空間 URI: http://www.aiim.org/pdfa/ns/field# 必要なスキーマ名前空間プレフィックス: pdfaField。

```csharp
public class XmpPdfAExtensionField : XmpPdfAExtensionObject
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [XmpPdfAExtensionField](xmppdfaextensionfield/)(string, string, string, string) | オブジェクトを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Description](../../aspose.pdf/xmppdfaextensionobject/description/) { get; } | 説明を取得します。 |
| [Name](../../aspose.pdf/xmppdfaextensionfield/name/) { get; } | フィールド名。フィールド名は有効な XML 要素名である必要があります。 |
| [Value](../../aspose.pdf/xmppdfaextensionobject/value/) { get; set; } | 値を取得または設定します。 |
| [ValueType](../../aspose.pdf/xmppdfaextensionfield/valuetype/) { get; } | フィールド値タイプは XMP Specification 2004 から取得するか、埋め込み PDF/A 値タイプ拡張スキーマから取得します。事前定義された XMP タイプ名またはカスタムタイプの名前です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [GetXml](../../aspose.pdf/xmppdfaextensionfield/getxml/)(XmlDocument) | XMLツリーでフィールドを表すXML要素のリストを返します。 |

### 関連項目

* class [XmpPdfAExtensionObject](../xmppdfaextensionobject/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


