---
title: "LoadOptions.PageSizeAdjustmentModes"
linktitle: "LoadOptions.PageSizeAdjustmentModes"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "注意！この機能は実装済みですが、サンプルドキュメントでOSHARED層のブロッカー問題が判明したため、まだパブリックAPIに公開されていません。ページサイズの使用モードを表します。"
type: docs
weight: 2810
url: /ja/java/com.aspose.pdf/loadoptions.pagesizeadjustmentmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.PageSizeAdjustmentModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.PageSizeAdjustmentModes, com.aspose.ms.System.Enum, com.aspose.pdf.LoadOptions.PageSizeAdjustmentModes

```
public static final class LoadOptions.PageSizeAdjustmentModes extends com.aspose.ms.System.Enum
```

注意！この機能は実装済みですが、サンプルドキュメントで OSHARED 層のブロッカー問題が判明したため、まだパブリック API に公開されていません。変換時のページサイズ使用モードを表します。HTML、EPUB などのフォーマットは通常フロート設計で、必要なページサイズに合わせることができます。しかし、コンテンツが水平位置やサイズを指定していて、必要なページサイズに収められない場合があります。そのような場合、（たとえばコンテンツのサイズが結果 PDF 文書の初期ページサイズに合わないとき）何をすべきかを定義できます。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [EnlargeRequiredViewportWidthAndDoConversionAgain](#EnlargeRequiredViewportWidthAndDoConversionAgain) | このモードは次の動作を定義します：変換結果を取得し、コンテンツが切り捨てられたことを検出した場合、ポートビューの幅がコンテンツに合わせて拡大され、変換が再実行されます。このモードを使用すると、そのような場合に結果のページ数を減らすことができますが、再描画が必要になるため（その分処理時間が増加します）。 |
| [NoAjustmentAllwaysUsePredefinedSize](#NoAjustmentAllwaysUsePredefinedSize) | このモードでは、変換後のコンテンツがページ境界を超えているかどうかに関係なく、結果ページは LoadOptions で定義された必要なページサイズになります。 |

### EnlargeRequiredViewportWidthAndDoConversionAgain {#EnlargeRequiredViewportWidthAndDoConversionAgain}
```
public static final int EnlargeRequiredViewportWidthAndDoConversionAgain
```

このモードは次の動作を定義します：変換結果を取得し、コンテンツが切り捨てられたことを検出した場合、ポートビューの幅がコンテンツに合わせて拡大され、変換が再実行されます。このモードを使用すると、そのような場合に結果のページ数を減らすことができますが、再描画が必要になるため（その分処理時間が増加します）。

### NoAjustmentAllwaysUsePredefinedSize {#NoAjustmentAllwaysUsePredefinedSize}
```
public static final int NoAjustmentAllwaysUsePredefinedSize
```

このモードでは、変換後のコンテンツがページ境界を超えているかどうかに関係なく、結果ページは LoadOptions で定義された必要なページサイズになります。
