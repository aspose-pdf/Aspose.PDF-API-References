---
title: "PdfAOptionsBase.AlignText"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfAOptionsBase プロパティ。PDF/A 変換プロセス中にテキストの配置を保持するために追加の手段が必要かどうかを示す値を取得または設定します。"
type: docs
weight: 10
url: /ja/net/aspose.pdf.plugins/pdfaoptionsbase/aligntext/
---
## PdfAOptionsBase.AlignText property

PDF/A 変換プロセス中にテキストの配置を保持するために追加の手段が必要かどうかを示す値を取得または設定します。

```csharp
public bool AlignText { get; set; }
```

### Property Value

テキストの配置が変更され、復元のために追加の操作が必要な場合は `true`、それ以外の場合は `false`。

## 備考

`true` に設定すると、変換プロセスは元のテキスト セグメントの境界を復元しようとします。ほとんどの文書では、デフォルトの `false` のままでこのプロパティを変更する必要はありません。デフォルトの変換プロセスではテキストの配置は変わらないためです。

### 関連項目

* class [PdfAOptionsBase](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)


