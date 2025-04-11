---
title: SvgExtractionOptions.MinStrokeWidth
second_title: Aspose.PDF for .NET API Reference
description: SvgExtractionOptions プロパティ。結果の SVG で使用される最小ストローク幅を取得または設定します。PDF がより細いストローク幅を使用している場合は、この幅に置き換えられます。デフォルト値は 0.5 です。
type: docs
weight: 60
url: /ja/net/aspose.pdf.vector/svgextractionoptions/minstrokewidth/
---
## SvgExtractionOptions.MinStrokeWidth プロパティ

結果の SVG で使用される最小ストローク幅を取得または設定します。PDF がより細いストローク幅を使用している場合は、この幅に置き換えられます。デフォルト値は 0.5 です。

```csharp
public double MinStrokeWidth { get; set; }
```

## 備考

値は変換された PDF ページの変換されたユーザー空間単位で表されます。デフォルトでは、1 ユーザー空間単位は 1/72 インチ (0.35 mm) ですが、これは PDF ドキュメントによって上書きされる可能性があります。変換は生成された SVG の実際の最小幅に影響を与える可能性があります。

### 参照

* クラス [SvgExtractionOptions](../)
* 名前空間 [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* アセンブリ [Aspose.PDF](../../../)