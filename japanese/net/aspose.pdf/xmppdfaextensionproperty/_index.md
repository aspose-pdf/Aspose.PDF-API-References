---
title: Class XmpPdfAExtensionProperty
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XmpPdfAExtensionProperty クラス。単一のプロパティを説明します。スキーマ名前空間 URI http//www.aiim.org/pdfa/ns/property 必須スキーマ名前空間プレフィックス pdfaProperty
type: docs
weight: 11460
url: /ja/net/aspose.pdf/xmppdfaextensionproperty/
---
## XmpPdfAExtensionProperty クラス

単一のプロパティを説明します。スキーマ名前空間 URI: http://www.aiim.org/pdfa/ns/property# 必須スキーマ名前空間プレフィックス: pdfaProperty

```csharp
public sealed class XmpPdfAExtensionProperty : XmpPdfAExtensionField
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [XmpPdfAExtensionProperty](xmppdfaextensionproperty/)(string, string, string, XmpPdfAExtensionCategoryType, string) | 新しいオブジェクトを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Category](../../aspose.pdf/xmppdfaextensionproperty/category/) { get; } | プロパティカテゴリを取得します。 |
| [Description](../../aspose.pdf/xmppdfaextensionobject/description/) { get; } | 説明を取得します。 |
| [Name](../../aspose.pdf/xmppdfaextensionfield/name/) { get; } | フィールド名。フィールド名は有効な XML 要素名でなければなりません。 |
| [Value](../../aspose.pdf/xmppdfaextensionobject/value/) { get; set; } | 値を取得または設定します。 |
| [ValueType](../../aspose.pdf/xmppdfaextensionfield/valuetype/) { get; } | フィールド値の型。XMP 仕様 2004 から取得されるか、埋め込まれた PDF/A 値型拡張スキーマ。事前定義された XMP 型名またはカスタム型の名前。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [GetXml](../../aspose.pdf/xmppdfaextensionproperty/getxml/)(XmlDocument) | XML ツリー内のプロパティを表す XML 要素のリストを返します。 |

### 参照

* クラス [XmpPdfAExtensionField](../xmppdfaextensionfield/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)