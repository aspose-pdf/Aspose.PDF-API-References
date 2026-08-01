---
title: "PdfAOptionsBase.ExcludeFontsStrategy"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfAOptionsBase プロパティ。PDF/A 変換プロセス中に出力ファイルサイズを最小化するためのフォント除去戦略を取得または設定します。"
type: docs
weight: 30
url: /ja/net/aspose.pdf.plugins/pdfaoptionsbase/excludefontsstrategy/
---
## PdfAOptionsBase.ExcludeFontsStrategy property

PDF/A 変換プロセス中に出力ファイルサイズを最小化するためのフォント削除戦略を取得または設定します。

```csharp
public RemoveFontsStrategy ExcludeFontsStrategy { get; set; }
```

### Property Value

フォント除去の戦略です。これは [`RemoveFontsStrategy`](../../../aspose.pdf/pdfformatconversionoptions.removefontsstrategy/) 列挙体の値のいずれかを指定できます。デフォルトは SubsetFonts と RemoveDuplicatedFonts の組み合わせです。

## 備考

このプロパティを使用すると、変換プロセス中のフォント処理方法を制御できます。重複フォントの除去、幅が異なる類似フォントの除去、またはフォントのサブセット化を選択できます。

### 関連項目

* enum [RemoveFontsStrategy](../../../aspose.pdf/pdfformatconversionoptions.removefontsstrategy/)
* class [PdfAOptionsBase](../)
* namespace [Aspose.Pdf.Plugins](../../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../../)


