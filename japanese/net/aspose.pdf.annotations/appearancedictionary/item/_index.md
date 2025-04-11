---
title: AppearanceDictionary.Item
second_title: Aspose.PDF for .NET API Reference
description: AppearanceDictionary プロパティ。外観ストリームを取得するための便利な形式を表します
type: docs
weight: 50
url: /ja/net/aspose.pdf.annotations/appearancedictionary/item/
---
## AppearanceDictionary インデクサ

外観ストリームを取得するための便利な形式を表します。

```csharp
public XForm this[string key] { get; set; }
```

| パラメータ | 説明 |
| --- | --- |
| key | 外観ストリームへのパスを表します。外観辞書にサブ辞書がある場合、パスは 2 つの部分を含む必要があります ([`Keys`](../keys/))。そうでない場合、パスは 1 つの部分のみを持ちます。 |

### 戻り値

指定されたキーに対応する XForm オブジェクト（外観ストリーム）。

### 参照

* クラス [XForm](../../../aspose.pdf/xform/)
* クラス [AppearanceDictionary](../)
* 名前空間 [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* アセンブリ [Aspose.PDF](../../../)