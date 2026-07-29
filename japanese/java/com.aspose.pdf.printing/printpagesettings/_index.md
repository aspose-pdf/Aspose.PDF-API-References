---
title: "PrintPageSettings"
linktitle: "PrintPageSettings"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "単一の印刷ページに適用される設定を指定します。"
type: docs
weight: 90
url: /ja/java/com.aspose.pdf.printing/printpagesettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PrintPageSettings

```
public class PrintPageSettings extends Object
```

単一の印刷ページに適用される設定を指定します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PrintPageSettings](#PrintPageSettings--) | デフォルトのプリンターを使用して PageSettings クラスの新しいインスタンスを初期化します。 |
| [PrintPageSettings](#PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | デフォルトのプリンターを使用して PageSettings クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBounds](#getBounds--) | Landscape プロパティで指定されたページの向きを考慮して、ページのサイズを取得します。 |
| [getHardMarginX](#getHardMarginX--) | ページ左側のハードマージンの x 座標（インチの百分の一単位）を取得します。 |
| [getHardMarginY](#getHardMarginY--) | ページ上部のハードマージンの y 座標（インチの百分の一単位）を取得します。 |
| [getMargins](#getMargins--) | このページの余白を取得します。 |
| [getPageSettings](#getPageSettings--) | ページ設定を取得します |
| [getPaperSize](#getPaperSize--) | ページの用紙サイズを取得します。 |
| [getPaperSource](#getPaperSource--) | ページの用紙ソースを取得します。例: プリンターの上部トレイ。 |
| [getPrintableArea](#getPrintableArea--) | プリンター用のページの印刷可能領域の境界を取得します。 |
| [getPrinterResolution](#getPrinterResolution--) | ページのプリンター解像度を取得します。 |
| [getPrinterSettings](#getPrinterSettings--) | ページに関連付けられたプリンター設定を取得します。 |
| [isColor](#isColor--) | ページをカラーで印刷すべきかどうかを示す値を取得または設定します。 |
| [isLandscape](#isLandscape--) | ページが横向きか縦向きかを示す値を取得または設定します。 |
| [setColor](#setColor-boolean-) | ページをカラーで印刷すべきかどうかを示す値を取得または設定します。 |
| [setLandscape](#setLandscape-boolean-) | ページが横向きか縦向きかを示す値を取得または設定します。 |
| [setMargins](#setMargins-com.aspose.pdf.printing.PrinterMargins-) | このページの余白を設定します。 |
| [setPaperSize](#setPaperSize-com.aspose.pdf.printing.PrintPaperSize-) | ページの用紙サイズを設定します。 |
| [setPaperSource](#setPaperSource-com.aspose.pdf.printing.PrintPaperSource-) | ページの用紙ソースを設定します。例: プリンターの上部トレイ。 |
| [setPrinterResolution](#setPrinterResolution-com.aspose.pdf.printing.PdfPrinterResolution-) | ページのプリンター解像度を設定します。 |
| [setPrinterSettings](#setPrinterSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | ページに関連付けられたプリンター設定を設定します。 |

### PrintPageSettings {#PrintPageSettings--}
```
public PrintPageSettings()
```

デフォルトのプリンターを使用して PageSettings クラスの新しいインスタンスを初期化します。

### PrintPageSettings {#PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
デフォルトのプリンターを使用して PageSettings クラスの新しいインスタンスを初期化します。

### getBounds {#getBounds--}
```
public Rectangle getBounds()
```

Landscape プロパティで指定されたページの向きを考慮して、ページのサイズを取得します。

**Returns:**
Rectangle オブジェクト

### getHardMarginX {#getHardMarginX--}
```
public float getHardMarginX()
```

ページ左側のハードマージンの x 座標（インチの百分の一単位）を取得します。

**Returns:**
float 値

### getHardMarginY {#getHardMarginY--}
```
public float getHardMarginY()
```

ページ上部のハードマージンの y 座標（インチの百分の一単位）を取得します。

**Returns:**
float 値

### getMargins {#getMargins--}
```
public PrinterMargins getMargins()
```

このページの余白を取得します。

**Returns:**
PrinterMargins オブジェクト

### getPageSettings {#getPageSettings--}
```
public com.aspose.ms.System.Drawing.Printing.PageSettings getPageSettings()
```

ページ設定を取得します

**Returns:**
PageSettings オブジェクト

### getPaperSize {#getPaperSize--}
```
public PrintPaperSize getPaperSize()
```

ページの用紙サイズを取得します。

**Returns:**
PrintPaperSize オブジェクト

### getPaperSource {#getPaperSource--}
```
public PrintPaperSource getPaperSource()
```

ページの用紙ソースを取得します。例: プリンターの上部トレイ。

**Returns:**
PrintPaperSource オブジェクト

### getPrintableArea {#getPrintableArea--}
```
public Rectangle getPrintableArea()
```

プリンター用のページの印刷可能領域の境界を取得します。

**Returns:**
Rectangle オブジェクト

### getPrinterResolution {#getPrinterResolution--}
```
public PdfPrinterResolution getPrinterResolution()
```

ページのプリンター解像度を取得します。

**Returns:**
PdfPrinterResolution オブジェクト

### getPrinterSettings {#getPrinterSettings--}
```
public PdfPrinterSettings getPrinterSettings()
```

ページに関連付けられたプリンター設定を取得します。

**Returns:**
PdfPrinterSettings オブジェクト

### isColor {#isColor--}
```
public boolean isColor()
```

ページをカラーで印刷すべきかどうかを示す値を取得または設定します。

**Returns:**
ブール値

### isLandscape {#isLandscape--}
```
public boolean isLandscape()
```

ページが横向きか縦向きかを示す値を取得または設定します。

**Returns:**
ブール値

### setColor {#setColor-boolean-}
```
public void setColor(boolean value)
```

ページをカラーで印刷すべきかどうかを示す値を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setLandscape {#setLandscape-boolean-}
```
public void setLandscape(boolean value)
```

ページが横向きか縦向きかを示す値を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setMargins {#setMargins-com.aspose.pdf.printing.PrinterMargins-}
このページの余白を設定します。

### setPaperSize {#setPaperSize-com.aspose.pdf.printing.PrintPaperSize-}
ページの用紙サイズを設定します。

### setPaperSource {#setPaperSource-com.aspose.pdf.printing.PrintPaperSource-}
ページの用紙ソースを設定します。例: プリンターの上部トレイ。

### setPrinterResolution {#setPrinterResolution-com.aspose.pdf.printing.PdfPrinterResolution-}
ページのプリンター解像度を設定します。

### setPrinterSettings {#setPrinterSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
ページに関連付けられたプリンター設定を設定します。
