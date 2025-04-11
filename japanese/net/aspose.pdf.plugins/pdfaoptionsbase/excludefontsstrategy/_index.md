---
title: PdfAOptionsBase.ExcludeFontsStrategy
second_title: Aspose.PDF for .NET API Reference
description: PdfAOptionsBase プロパティ。PDF/A 変換プロセス中に出力ファイルサイズを最小限に抑えるためにフォントを削除する戦略を取得または設定します。
type: docs
weight: 30
url: /ja/net/aspose.pdf.plugins/pdfaoptionsbase/excludefontsstrategy/
---
## PdfAOptionsBase.ExcludeFontsStrategy プロパティ

PDF/A 変換プロセス中に出力ファイルサイズを最小限に抑えるためにフォントを削除する戦略を取得または設定します。

```csharp
public RemoveFontsStrategy ExcludeFontsStrategy { get; set; }
```

### プロパティ値

フォントを削除するための戦略。これは [`RemoveFontsStrategy`](../../../aspose.pdf/pdfformatconversionoptions.removefontsstrategy/) 列挙型の値のいずれかです。デフォルトは SubsetFonts と RemoveDuplicatedFonts の組み合わせです。

## 備考

このプロパティを使用すると、変換プロセス中にフォントの扱いを制御できます。重複したフォントを削除したり、異なる幅の類似フォントを削除したり、フォントをサブセット化したりすることができます。

### 関連項目

* enum [RemoveFontsStrategy](../../../aspose.pdf/pdfformatconversionoptions.removefontsstrategy/)
* class [PdfAOptionsBase](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)