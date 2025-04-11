---
title: Enum LoadOptions.PageSizeAdjustmentModes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LoadOptionsPageSizeAdjustmentModes 列挙型。注意：機能は実装されていますが、サンプルドキュメントに対して OSHARED レイヤーでブロッカー問題が明らかになったため、まだ公開 API に追加されていません。変換中のページサイズの使用モードを表します。HTML、EPUB などの形式は通常フロートデザインを持っているため、必要なページサイズに合わせることができます。しかし、コンテンツが特定の水平位置やサイズを指定している場合、必要なページサイズにコンテンツを配置できないことがあります。その場合、コンテンツのサイズが結果の PDF ドキュメントの初期ページサイズに合わない場合に何をすべきかを定義できます。
type: docs
weight: 6140
url: /ja/net/aspose.pdf/loadoptions.pagesizeadjustmentmodes/
---
## LoadOptions.PageSizeAdjustmentModes 列挙型

注意！機能は実装されていますが、サンプルドキュメントに対して OSHARED レイヤーでブロッカー問題が明らかになったため、まだ公開 API に追加されていません。変換中のページサイズの使用モードを表します。形式（HTML、EPUB など）は通常フロートデザインを持っているため、必要なページサイズに合わせることができます。しかし、コンテンツが特定の水平位置やサイズを指定している場合、必要なページサイズにコンテンツを配置できないことがあります。その場合、コンテンツのサイズが結果の PDF ドキュメントの初期ページサイズに合わない場合に何をすべきかを定義できます。

```csharp
public enum PageSizeAdjustmentModes
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| NoAjustmentAllwaysUsePredefinedSize | `0` | このモードでは、結果のページは LoadOptions で定義された必要なページサイズを持ち、変換後にコンテンツがページの境界を超えているかどうかに関係なく、必要なページサイズが適用されます。 |
| EnlargeRequiredViewportWidthAndDoConversionAgain | `1` | このモードは次のような動作を定義します：変換結果を取得し、一部のコンテンツが切り取られていることを検出した後、ポートビューの幅がコンテンツに合わせて拡大され、変換が再実行されます。このモードでは、結果として得られるページ数が少なくなる可能性がありますが、再レンダリング（したがって、より多くの処理時間）が必要です。 |

### 参照

* クラス [LoadOptions](../loadoptions/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)