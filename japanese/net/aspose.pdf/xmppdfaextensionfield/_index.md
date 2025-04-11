---
title: Class XmpPdfAExtensionField
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XmpPdfAExtensionField クラス。このスキーマは構造化タイプのフィールドを説明します。これは PDF/A プロパティ値タイプスキーマに非常に似ていますが、プロパティの代わりに構造内のフィールドを定義します。スキーマ名前空間 URI http//www.aiim.org/pdfa/ns/field 必須スキーマ名前空間プレフィックス pdfaField
type: docs
weight: 11440
url: /ja/net/aspose.pdf/xmppdfaextensionfield/
---
## XmpPdfAExtensionField クラス

このスキーマは構造化タイプのフィールドを説明します。これは PDF/A プロパティ値タイプスキーマに非常に似ていますが、プロパティの代わりに構造内のフィールドを定義します。スキーマ名前空間 URI: http://www.aiim.org/pdfa/ns/field# 必須スキーマ名前空間プレフィックス: pdfaField。

```csharp
public class XmpPdfAExtensionField : XmpPdfAExtensionObject
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [XmpPdfAExtensionField](xmppdfaextensionfield/)(string, string, string, string) | オブジェクトを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Description](../../aspose.pdf/xmppdfaextensionobject/description/) { get; } | 説明を取得します。 |
| [Name](../../aspose.pdf/xmppdfaextensionfield/name/) { get; } | フィールド名。フィールド名は有効な XML 要素名でなければなりません。 |
| [Value](../../aspose.pdf/xmppdfaextensionobject/value/) { get; set; } | 値を取得または設定します。 |
| [ValueType](../../aspose.pdf/xmppdfaextensionfield/valuetype/) { get; } | フィールド値タイプ。XMP 仕様 2004 から取得された、または埋め込まれた PDF/A 値タイプ拡張スキーマ。事前定義された XMP タイプ名またはカスタムタイプの名前。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [GetXml](../../aspose.pdf/xmppdfaextensionfield/getxml/)(XmlDocument) | XML ツリー内のフィールドを表す XML 要素のリストを返します。 |

### 参照

* クラス [XmpPdfAExtensionObject](../xmppdfaextensionobject/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)