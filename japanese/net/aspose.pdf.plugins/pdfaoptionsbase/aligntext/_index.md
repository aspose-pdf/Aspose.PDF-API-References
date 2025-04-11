---
title: PdfAOptionsBase.AlignText
second_title: Aspose.PDF for .NET API Reference
description: PdfAOptionsBase プロパティ。PDF/A 変換プロセス中にテキストの整列を維持するために追加の手段が必要かどうかを示す値を取得または設定します。
type: docs
weight: 10
url: /ja/net/aspose.pdf.plugins/pdfaoptionsbase/aligntext/
---
## PdfAOptionsBase.AlignText プロパティ

PDF/A 変換プロセス中にテキストの整列を維持するために追加の手段が必要かどうかを示す値を取得または設定します。

```csharp
public bool AlignText { get; set; }
```

### プロパティ値

テキストの整列が変更され、元に戻すために追加のアクションが必要な場合は `true`、そうでない場合は `false`。

## 備考

`true` に設定すると、変換プロセスは元のテキストセグメントの境界を復元しようとします。ほとんどのドキュメントでは、デフォルトの `false` 値からこのプロパティを変更する必要はありません。デフォルトの変換プロセス中にテキストの整列は変更されないためです。

### 関連項目

* クラス [PdfAOptionsBase](../)
* 名前空間 [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* アセンブリ [Aspose.PDF](../../../)