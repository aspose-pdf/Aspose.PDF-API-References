---
title: "IPdfFileEditor.ContentsResizeParameters"
linktitle: "IPdfFileEditor.ContentsResizeParameters"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ページリサイズパラメータを指定するクラスです。次のパラメータを設定できます：結果ページのサイズ（幅、高さ）をデフォルトの空間単位または初期ページのパーセントで指定します。"
type: docs
weight: 300
url: /ja/java/com.aspose.pdf.facades/ipdffileeditor.contentsresizeparameters/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters

```
public static class IPdfFileEditor.ContentsResizeParameters extends Object
```

ページリサイズパラメータを指定するクラス。次のパラメータを設定できます: 結果ページのサイズ（幅、高さ）をデフォルトの空間単位または元ページサイズのパーセンテージで指定; 左、上、下、右の余白をデフォルトの空間単位または元ページサイズのパーセンテージで指定; 一部の値は自動計算のために null のままにできます。これらの値は、明示的に指定された値を除いた残りのページサイズから計算されます。例: ページ幅 = 100、 新しいページ幅を 60 単位と指定した場合、左と右の余白は自動的に計算されます: (100 - 60) / 2 = 15。このクラスは ResizeContents メソッドで使用されます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ContentsResizeParameters](#ContentsResizeParameters--) | すべての値が "auto" に設定されたリサイズパラメータを作成します。必要に応じて、後で余白やコンテンツサイズを指定できます。 |
| [ContentsResizeParameters](#ContentsResizeParameters-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | すべての値が "auto" に設定されたリサイズパラメータを作成します。必要に応じて、後で余白やコンテンツサイズを指定できます。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [contentSize](#contentSize-double-double-) | 指定されたコンテンツサイズでリサイズパラメータを作成します。 |
| [contentSizePercent](#contentSizePercent-double-double-) | 初期ページサイズのパーセントで指定されたコンテンツサイズでリサイズパラメータを作成します。余白は自動的に計算されます。 |
| [getBottomMargin](#getBottomMargin--) | 結果ページの下余白を取得または設定します。 |
| [getContentsHeight](#getContentsHeight--) | 結果ページ上のソースページのコンテンツの高さを取得または設定します。 |
| [getContentsWidth](#getContentsWidth--) | 結果ページ上のソースページのコンテンツの幅を取得または設定します。 |
| [getLeftMargin](#getLeftMargin--) | 結果ページの左余白を取得または設定します。 |
| [getRightMargin](#getRightMargin--) | 結果ページの右余白を取得または設定します。 |
| [getTopMargin](#getTopMargin--) | 結果ページの上余白を取得または設定します。 |
| [isChangeMediaBox](#isChangeMediaBox--) | リサイズ操作中にPDFページの MediaBox を調整するかどうかを取得します。デフォルト値は {@code false} です。このパラメータを設定すると、リサイズ中に MediaBox を CropBox の値に合わせて調整できるようになります。 |
| [margins](#margins-double-double-double-double-) | 指定された余白値でリサイズパラメータを作成します。コンテンツサイズは自動的に計算されます。 |
| [marginsPercent](#marginsPercent-double-double-double-double-) | リサイズパラメータを作成します。余白は初期ページサイズのパーセントで指定されます。 |
| [pageResize](#pageResize-double-double-) | ページリサイズ用のリサイズパラメータを作成します。 |
| [pageResizePct](#pageResizePct-double-double-) | ページリサイズ用のリサイズパラメータを作成します。新しいサイズはパーセントで指定されます。 |
| [setBottomMargin](#setBottomMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | 結果ページの下余白を取得または設定します。 |
| [setChangeMediaBox](#setChangeMediaBox-boolean-) | リサイズ操作中にPDFページの MediaBox を調整するかどうかを設定します。デフォルト値は {@code false} です。このパラメータを設定すると、リサイズ中に MediaBox を CropBox の値に合わせて調整できるようになります。 |
| [setContentsHeight](#setContentsHeight-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | 結果ページ上のソースページのコンテンツの高さを取得または設定します。 |
| [setContentsWidth](#setContentsWidth-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | 結果ページ上のソースページのコンテンツの幅を取得または設定します。 |
| [setLeftMargin](#setLeftMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | 結果ページの左余白を取得または設定します。 |
| [setRightMargin](#setRightMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | 結果ページの右余白を取得または設定します。 |
| [setTopMargin](#setTopMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-) | 結果ページの上余白を取得または設定します。 |

### ContentsResizeParameters {#ContentsResizeParameters--}
```
public ContentsResizeParameters()
```

すべての値が "auto" に設定されたリサイズパラメータを作成します。必要に応じて、後で余白やコンテンツサイズを指定できます。

### ContentsResizeParameters {#ContentsResizeParameters-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
すべての値が "auto" に設定されたリサイズパラメータを作成します。必要に応じて、後で余白やコンテンツサイズを指定できます。

### contentSize {#contentSize-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters contentSize(double width, double height)
```

指定されたコンテンツサイズでリサイズパラメータを作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 幅 |  | コンテンツの新しい幅。 |
| 高さ |  | コンテンツの新しい高さ。 |

**Returns:**
新しいリサイズパラメータを返します。

### contentSizePercent {#contentSizePercent-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters contentSizePercent(double width, double height)
```

初期ページサイズのパーセントで指定されたコンテンツサイズでリサイズパラメータを作成します。余白は自動的に計算されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 幅 |  | 新しいコンテンツ幅（パーセント）。 |
| 高さ |  | 新しいコンテンツの高さ（パーセント）。 |

**Returns:**
新しいリサイズ パラメータ。

### getBottomMargin {#getBottomMargin--}
```
public IPdfFileEditor.ContentsResizeValue getBottomMargin()
```

結果ページの下余白を取得または設定します。

**Returns:**
ContentsResizeValue オブジェクト

### getContentsHeight {#getContentsHeight--}
```
public IPdfFileEditor.ContentsResizeValue getContentsHeight()
```

結果ページ上のソースページのコンテンツの高さを取得または設定します。

**Returns:**
ContentsResizeValue オブジェクト

### getContentsWidth {#getContentsWidth--}
```
public IPdfFileEditor.ContentsResizeValue getContentsWidth()
```

結果ページ上のソースページのコンテンツの幅を取得または設定します。

**Returns:**
ContentsResizeValue オブジェクト

### getLeftMargin {#getLeftMargin--}
```
public IPdfFileEditor.ContentsResizeValue getLeftMargin()
```

結果ページの左余白を取得または設定します。

**Returns:**
ContentsResizeValue オブジェクト

### getRightMargin {#getRightMargin--}
```
public IPdfFileEditor.ContentsResizeValue getRightMargin()
```

結果ページの右余白を取得または設定します。

**Returns:**
ContentsResizeValue オブジェクト

### getTopMargin {#getTopMargin--}
```
public IPdfFileEditor.ContentsResizeValue getTopMargin()
```

結果ページの上余白を取得または設定します。

**Returns:**
ContentsResizeValue オブジェクト

### isChangeMediaBox {#isChangeMediaBox--}
```
public final boolean isChangeMediaBox()
```

リサイズ操作中にPDFページの MediaBox を調整するかどうかを取得します。デフォルト値は {@code false} です。このパラメータを設定すると、リサイズ中に MediaBox を CropBox の値に合わせて調整できるようになります。

**Returns:**
リサイズ操作中に PDF ページの MediaBox を調整するかどうか。

### margins {#margins-double-double-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters margins(double left, double right, double top, double bottom)
```

指定された余白値でリサイズパラメータを作成します。コンテンツサイズは自動的に計算されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| left |  | 左余白。 |
| 右 |  | 右余白。 |
| 上部 |  | 上余白。 |
| bottom |  | 下余白。 |

**Returns:**
作成されたリサイズパラメータ。

### marginsPercent {#marginsPercent-double-double-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters marginsPercent(double left, double right, double top, double bottom)
```

リサイズパラメータを作成します。余白は初期ページサイズのパーセントで指定されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| left |  | 左余白（ページ幅のパーセント）。 |
| 右 |  | 右余白（ページ高さのパーセント）。 |
| 上部 |  | 上余白（ページ高さのパーセント）。 |
| bottom |  | 下余白（ページ高さのパーセント）。 |

**Returns:**
新しいリサイズパラメータを返します。

### pageResize {#pageResize-double-double-}
```
public static IPdfFileEditor.ContentsResizeParameters pageResize(double width, double height)
```

ページリサイズ用のリサイズパラメータを作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 幅 |  | 新しいページ幅（単位）。 |
| 高さ |  | 新しいページ高さ（単位）。 |

**Returns:**
新しいリサイズ パラメータ。

### pageResizePct {#pageResizePct-double-double-}
```
public IPdfFileEditor.ContentsResizeParameters pageResizePct(double widthPct, double heightPct)
```

ページリサイズ用のリサイズパラメータを作成します。新しいサイズはパーセントで指定されます。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| widthPct |  | 新しいページ幅（パーセント）。 |
| heightPct |  | 新しいページ高さ（パーセント）。 |

**Returns:**
新しいリサイズ パラメータ。

### setBottomMargin {#setBottomMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
結果ページの下余白を取得または設定します。

### setChangeMediaBox {#setChangeMediaBox-boolean-}
```
public final void setChangeMediaBox(boolean value)
```

リサイズ操作中にPDFページの MediaBox を調整するかどうかを設定します。デフォルト値は {@code false} です。このパラメータを設定すると、リサイズ中に MediaBox を CropBox の値に合わせて調整できるようになります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | リサイズ操作中に PDF ページの MediaBox を調整するかどうか。 |

### setContentsHeight {#setContentsHeight-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
結果ページ上のソースページのコンテンツの高さを取得または設定します。

### setContentsWidth {#setContentsWidth-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
結果ページ上のソースページのコンテンツの幅を取得または設定します。

### setLeftMargin {#setLeftMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
結果ページの左余白を取得または設定します。

### setRightMargin {#setRightMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
結果ページの右余白を取得または設定します。

### setTopMargin {#setTopMargin-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue-}
結果ページの上余白を取得または設定します。
