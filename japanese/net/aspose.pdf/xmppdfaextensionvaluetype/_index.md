---
title: Class XmpPdfAExtensionValueType
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XmpPdfAExtensionValueType クラス。PDF/A ValueType スキーマは、XMP 2004 仕様で定義されていないすべてのプロパティ値タイプに必要です。つまり、以下のリストに含まれない値タイプに対して必要です： - 配列タイプ（これらは1つ以上のフィールドを含む可能性のあるコンテナタイプです）：Alt、Bag、Seq - 基本値タイプ：Boolean、（オープンおよびクローズド）Choice、Date、Dimensions、Integer、Lang Alt、Locale、MIMEType、ProperName、Real、Text、Thumbnail、URI、URL、XPath - メディア管理値タイプ：AgentName、RenditionClass、ResourceEvent、ResourceRef、Version - 基本ジョブ/ワークフロー値タイプ：Job - EXIF スキーマ値タイプ：Flash、CFAPattern、DeviceSettings、GPSCoordinate、OECF/SFR、Rational スキーマ名前空間 URI：http//www.aiim.org/pdfa/ns/type 必須スキーマ名前空間プレフィックス：pdfaType
type: docs
weight: 11490
url: /ja/net/aspose.pdf/xmppdfaextensionvaluetype/
---
## XmpPdfAExtensionValueType クラス

PDF/A ValueType スキーマは、XMP 2004 仕様で定義されていないすべてのプロパティ値タイプに必要です。つまり、以下のリストに含まれない値タイプに対して必要です： - 配列タイプ（これらは1つ以上のフィールドを含む可能性のあるコンテナタイプです）：Alt、Bag、Seq - 基本値タイプ：Boolean、（オープンおよびクローズド）Choice、Date、Dimensions、Integer、Lang Alt、Locale、MIMEType、ProperName、Real、Text、Thumbnail、URI、URL、XPath - メディア管理値タイプ：AgentName、RenditionClass、ResourceEvent、ResourceRef、Version - 基本ジョブ/ワークフロー値タイプ：Job - EXIF スキーマ値タイプ：Flash、CFAPattern、DeviceSettings、GPSCoordinate、OECF/SFR、Rational スキーマ名前空間 URI：http://www.aiim.org/pdfa/ns/type# 必須スキーマ名前空間プレフィックス：pdfaType

```csharp
public sealed class XmpPdfAExtensionValueType : XmpPdfAExtensionObject
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [XmpPdfAExtensionValueType](xmppdfaextensionvaluetype/)(string, string, string, string) | 新しいオブジェクトを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Description](../../aspose.pdf/xmppdfaextensionobject/description/) { get; } | 説明を取得します。 |
| [Fields](../../aspose.pdf/xmppdfaextensionvaluetype/fields/) { get; } | フィールドのリストを取得します。 |
| [NamespaceUri](../../aspose.pdf/xmppdfaextensionvaluetype/namespaceuri/) { get; } | 名前空間 URI を取得します。 |
| [Prefix](../../aspose.pdf/xmppdfaextensionvaluetype/prefix/) { get; } | プレフィックスを取得します。 |
| [Type](../../aspose.pdf/xmppdfaextensionvaluetype/type/) { get; } | 値タイプを取得します。 |
| [Value](../../aspose.pdf/xmppdfaextensionobject/value/) { get; set; } | 値を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Add](../../aspose.pdf/xmppdfaextensionvaluetype/add/)(XmpPdfAExtensionField) | 新しいフィールドを追加します。 |
| [AddRange](../../aspose.pdf/xmppdfaextensionvaluetype/addrange/)(XmpPdfAExtensionField[]) | フィールドの範囲を追加します。 |
| [Clear](../../aspose.pdf/xmppdfaextensionvaluetype/clear/)() | すべてのフィールドをクリアします。 |
| override [GetXml](../../aspose.pdf/xmppdfaextensionvaluetype/getxml/)(XmlDocument) | XML ツリー内の値タイプを表す XML 要素のリストを返します。 |
| [Remove](../../aspose.pdf/xmppdfaextensionvaluetype/remove/)(XmpPdfAExtensionField) | フィールドのリストからフィールドを削除します。 |

### 参照

* クラス [XmpPdfAExtensionObject](../xmppdfaextensionobject/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)