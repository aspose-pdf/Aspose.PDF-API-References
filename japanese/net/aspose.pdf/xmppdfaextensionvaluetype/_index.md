---
title: "クラス XmpPdfAExtensionValueType"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.XmpPdfAExtensionValueType クラス。PDF/A ValueType スキーマは、XMP 2004 仕様で定義されていないすべてのプロパティ値タイプ、すなわち以下のリストに含まれない値タイプに必要です。Array types は、1 つ以上のフィールドを含む可能性があるコンテナタイプです。Alt、Bag、Seq。Basic value types は Boolean、open and closed、Choice、Date、Dimensions、Integer、Lang、Alt、Locale、MIMEType、ProperName、Real、Text、Thumbnail、URI、URL、XPath。Media Management value types は AgentName、RenditionClass、ResourceEvent、ResourceRef、Version。Basic Job/Workflow value type は Job。EXIF schema value types は Flash、CFAPattern、DeviceSettings、GPSCoordinate、OECF/SFR、Rational。Schema namespace URI は http//www.aiim.org/pdfa/ns/type。必要なスキーマ名前空間プレフィックスは pdfaType。"
type: docs
weight: 11680
url: /ja/net/aspose.pdf/xmppdfaextensionvaluetype/
---
## XmpPdfAExtensionValueType class

PDF/A ValueType スキーマは、XMP 2004 仕様で定義されていないすべてのプロパティ値タイプに必須です。つまり、以下のリストに含まれない値タイプに対して必要です： - 配列タイプ (これらは 1 つ以上のフィールドを含むコンテナタイプ): Alt, Bag, Seq - 基本的な値タイプ: Boolean, (open and closed) Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - メディア管理値タイプ: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - 基本的なジョブ/ワークフロー値タイプ: Job - EXIF スキーマ値タイプ: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational スキーマ名前空間 URI: http://www.aiim.org/pdfa/ns/type# 必要なスキーマ名前空間プレフィックス: pdfaType

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
| [Fields](../../aspose.pdf/xmppdfaextensionvaluetype/fields/) { get; } | フィールドの一覧を取得します。 |
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
| override [GetXml](../../aspose.pdf/xmppdfaextensionvaluetype/getxml/)(XmlDocument) | XML ツリー内で値タイプを表す XML 要素の一覧を返します。 |
| [Remove](../../aspose.pdf/xmppdfaextensionvaluetype/remove/)(XmpPdfAExtensionField) | フィールドの一覧からフィールドを削除します。 |

### 関連項目

* class [XmpPdfAExtensionObject](../xmppdfaextensionobject/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


