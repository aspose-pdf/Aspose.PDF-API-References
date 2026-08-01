---
title: "列挙型 LoadOptions.PageSizeAdjustmentModes"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.LoadOptionsPageSizeAdjustmentModes 列挙型。ATTENTION この機能は実装済みですが、サンプルドキュメントで OSHARED 層のブロッカー問題が判明したため、まだ公開 API には含まれていません。変換時のページサイズ使用モードを表します。HTML や EPUB などの形式は通常フロート設計で、必要なページサイズに合わせることができます。しかし、コンテンツが水平位置やサイズを指定していて、必要なページサイズに収められない場合があります。そのような場合、コンテンツのサイズが結果 PDF ドキュメントの初期ページサイズに合わないときに何をすべきかを定義できます。"
type: docs
weight: 6280
url: /ja/net/aspose.pdf/loadoptions.pagesizeadjustmentmodes/
---
## LoadOptions.PageSizeAdjustmentModes enumeration

ATTENTION! この機能は実装済みですが、サンプルドキュメントで OSHARED 層のブロッカー問題が判明したため、まだ公開 API には含まれていません。変換時のページサイズ使用モードを表します。HTML、EPUB などの形式は通常フロート設計で、必要なページサイズに合わせることができます。しかし、コンテンツが水平位置やサイズを指定していて、必要なページサイズに収められない場合があります。そのような場合、コンテンツのサイズが結果 PDF ドキュメントの初期ページサイズに合わないときに何をすべきかを定義できます（例：コンテンツのサイズが必要な初期ページサイズに合わない場合）。

```csharp
public enum PageSizeAdjustmentModes
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| NoAjustmentAllwaysUsePredefinedSize | `0` | このモードでは、変換後のコンテンツがページ境界を超えているかどうかに関わらず、結果ページは LoadOptions で定義された必要なページサイズになります。 |
| EnlargeRequiredViewportWidthAndDoConversionAgain | `1` | このモードは次の動作を定義します：変換結果を取得し、コンテンツの一部が切り捨てられたことを検出した場合、ポートビューの幅がコンテンツに合わせて拡大され、変換が再実行されます。このモードにより、結果のページ数を減らすことができますが、再レンダリングが必要になるため処理時間が増加します。 |

### 関連項目

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


