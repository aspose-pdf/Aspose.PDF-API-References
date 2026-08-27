---
title: "PdfPrinterSettings"
linktitle: "PdfPrinterSettings"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ドキュメントがどのように印刷されるかに関する情報を指定します。これには印刷するプリンターも含まれます。"
type: docs
weight: 50
url: /ja/java/com.aspose.pdf.printing/pdfprintersettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PdfPrinterSettings

```
public class PdfPrinterSettings extends Object
```

ドキュメントがどのように印刷されるかに関する情報を指定します。これには印刷するプリンターも含まれます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PdfPrinterSettings](#PdfPrinterSettings--) | PrinterSettings クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [canDuplex](#canDuplex--) | プリンターが両面印刷をサポートしているかどうかを示す値を取得します。 |
| [createMeasurementGraphics](#createMeasurementGraphics--) | Graphics2D オブジェクトを取得します。 |
| [createMeasurementGraphics](#createMeasurementGraphics-boolean-) | Graphics2D オブジェクトを取得します。 |
| [createMeasurementGraphics](#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-) | Graphics2D オブジェクトを取得します。 |
| [createMeasurementGraphics](#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-boolean-) | Graphics2D オブジェクトを取得します。 |
| [deepClone](#deepClone--) | クローン化されたオブジェクトを取得します。 |
| [getCopies](#getCopies--) | 印刷する文書の部数を取得します。 |
| [getDefaultPageSettings](#getDefaultPageSettings--) | このプリンターのデフォルトページ設定を取得します。 |
| [getDuplex](#getDuplex--) | 両面印刷のプリンター設定を取得または設定します。 |
| [getFromPage](#getFromPage--) | 印刷する最初のページ番号を取得または設定します。 |
| [getInstalledPrinters](#getInstalledPrinters--) | コンピューターにインストールされているすべてのプリンター名を取得します。 |
| [getLandscapeAngle](#getLandscapeAngle--) | 縦向きが横向きになるように回転する角度（度）を取得します。 |
| [getMaximumCopies](#getMaximumCopies--) | プリンターが一度に印刷できる最大部数を取得します。 |
| [getMaximumPage](#getMaximumPage--) | PrintDialogで選択できる最大のFromPageまたはToPageを取得または設定します。 |
| [getMinimumPage](#getMinimumPage--) | PrintDialogで選択できる最小のFromPageまたはToPageを取得または設定します。 |
| [getPaperSizes](#getPaperSizes--) | このプリンターがサポートする用紙サイズを取得します。 |
| [getPaperSources](#getPaperSources--) | プリンターで利用可能な用紙供給トレイを取得します。 |
| [getPrinterName](#getPrinterName--) | 使用するプリンターの名前を取得または設定します。 |
| [getPrinterResolutions](#getPrinterResolutions--) | このプリンターがサポートするすべての解像度を取得します。 |
| [getPrinterSettings](#getPrinterSettings--) | PrinterSettings オブジェクトを返します。 |
| [getPrintFileName](#getPrintFileName--) | ファイルに印刷する際のファイル名を取得または設定します。 |
| [getPrintRange](#getPrintRange--) | ユーザーが指定した印刷ページ番号を取得または設定します。 |
| [getSelectedPages](#getSelectedPages--) | 印刷するために選択されたページ数を取得します。 |
| [getToPage](#getToPage--) | 印刷する最終ページ番号を取得または設定します。 |
| [isCollate](#isCollate--) | 印刷された文書が綴じられるかどうかを示す値を取得または設定します。 |
| [isDefaultPrinter](#isDefaultPrinter--) | ユーザーが明示的に PrinterName を設定した場合を除き、PrinterName プロパティが既定のプリンターを示すかどうかを示す値を取得します。 |
| [isDirectPrintingSupported](#isDirectPrintingSupported-com.aspose.pdf.ImageType-) | プリンターが DirectPrinting をサポートしているかどうかを示す値を取得します。 |
| [isDirectPrintingSupported](#isDirectPrintingSupported-java.lang.String-) | プリンターが DirectPrinting をサポートしているかどうかを示す値を取得します。 |
| [isPlotter](#isPlotter--) | プリンターがプロッタであるかどうかを示す値を取得します。 |
| [isPrintToFile](#isPrintToFile--) | 印刷出力がポートではなくファイルに送られるかどうかを示す値を取得します。 |
| [isSupportsColor](#isSupportsColor--) | このプリンターがカラー印刷をサポートしているかどうかを示す値を取得します。 |
| [isValid](#isValid--) | PrinterName プロパティが有効なプリンターを示すかどうかを示す値を取得します。 |
| [setCollate](#setCollate-boolean-) | 印刷された文書が綴じられるかどうかを示す値を取得または設定します。 |
| [setCopies](#setCopies-short-) | 印刷する文書のコピー数を設定します。 |
| [setDuplex](#setDuplex-int-) | 両面印刷のプリンター設定を取得または設定します。 |
| [setFromPage](#setFromPage-int-) | 印刷する最初のページ番号を取得または設定します。 |
| [setMaximumPage](#setMaximumPage-int-) | PrintDialogで選択できる最大のFromPageまたはToPageを取得または設定します。 |
| [setMinimumPage](#setMinimumPage-int-) | PrintDialogで選択できる最小のFromPageまたはToPageを取得または設定します。 |
| [setPrinterName](#setPrinterName-java.lang.String-) | 使用するプリンターの名前を設定します。 |
| [setPrintFileName](#setPrintFileName-java.lang.String-) | 印刷するファイル名を設定します。 |
| [setPrintRange](#setPrintRange-int-) | ユーザーが指定した印刷ページ番号を設定します。 |
| [setPrintToFile](#setPrintToFile-boolean-) | 印刷出力がポートではなくファイルに送られるかどうかを示す値を設定します。 |
| [setSelectedPages](#setSelectedPages-int:A-) | 印刷するために選択されたページ数を設定します。 |
| [setToPage](#setToPage-int-) | 印刷する最終ページ番号を設定します。 |

### PdfPrinterSettings {#PdfPrinterSettings--}
```
public PdfPrinterSettings()
```

PrinterSettings クラスの新しいインスタンスを初期化します。

### canDuplex {#canDuplex--}
```
public boolean canDuplex()
```

プリンターが両面印刷をサポートしているかどうかを示す値を取得します。

**Returns:**
ブール値

### createMeasurementGraphics {#createMeasurementGraphics--}
```
public Graphics2D createMeasurementGraphics()
```

Graphics2D オブジェクトを取得します。

**Returns:**
Graphics2D オブジェクト

### createMeasurementGraphics {#createMeasurementGraphics-boolean-}
```
public Graphics2D createMeasurementGraphics(boolean value)
```

Graphics2D オブジェクトを取得します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

**Returns:**
Graphics2D オブジェクト

### createMeasurementGraphics {#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-}
Graphics2D オブジェクトを取得します。

**Returns:**
Graphics2D オブジェクト

### createMeasurementGraphics {#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-boolean-}
Graphics2D オブジェクトを取得します。

**Returns:**
Graphics2D オブジェクト

### deepClone {#deepClone--}
```
public PdfPrinterSettings deepClone()
```

クローン化されたオブジェクトを取得します。

**Returns:**
PdfPrinterSettings オブジェクト

### getCopies {#getCopies--}
```
public short getCopies()
```

印刷する文書の部数を取得します。

**Returns:**
コピー数

### getDefaultPageSettings {#getDefaultPageSettings--}
```
public PrintPageSettings getDefaultPageSettings()
```

このプリンターのデフォルトページ設定を取得します。

**Returns:**
デフォルトページ設定

### getDuplex {#getDuplex--}
```
public int getDuplex()
```

両面印刷のプリンター設定を取得または設定します。

**Returns:**
int 値 @see DuplexKind

### getFromPage {#getFromPage--}
```
public int getFromPage()
```

印刷する最初のページ番号を取得または設定します。

**Returns:**
int 値です。

### getInstalledPrinters {#getInstalledPrinters--}
```
public static ArrayList < String > getInstalledPrinters()
```

コンピューターにインストールされているすべてのプリンター名を取得します。

**Returns:**
{@code ArrayList<String>} オブジェクト

### getLandscapeAngle {#getLandscapeAngle--}
```
public int getLandscapeAngle()
```

縦向きが横向きになるように回転する角度（度）を取得します。

**Returns:**
int 値です。

### getMaximumCopies {#getMaximumCopies--}
```
public int getMaximumCopies()
```

プリンターが一度に印刷できる最大部数を取得します。

**Returns:**
int 値です。

### getMaximumPage {#getMaximumPage--}
```
public int getMaximumPage()
```

PrintDialogで選択できる最大のFromPageまたはToPageを取得または設定します。

**Returns:**
int 値です。

### getMinimumPage {#getMinimumPage--}
```
public int getMinimumPage()
```

PrintDialogで選択できる最小のFromPageまたはToPageを取得または設定します。

**Returns:**
int 値です。

### getPaperSizes {#getPaperSizes--}
```
public ArrayList < PrintPaperSize > getPaperSizes()
```

このプリンターがサポートする用紙サイズを取得します。

**Returns:**
{@code ArrayList<PrintPaperSize> } オブジェクト

### getPaperSources {#getPaperSources--}
```
public ArrayList < PrintPaperSource > getPaperSources()
```

プリンターで利用可能な用紙供給トレイを取得します。

**Returns:**
{@code ArrayList<PrintPaperSource> } オブジェクト

### getPrinterName {#getPrinterName--}
```
public String getPrinterName()
```

使用するプリンターの名前を取得または設定します。

**Returns:**
string オブジェクト

### getPrinterResolutions {#getPrinterResolutions--}
```
public com.aspose.ms.System.Drawing.Printing.PrinterSettings.PrinterResolutionCollection getPrinterResolutions()
```

このプリンターがサポートするすべての解像度を取得します。

**Returns:**
PrinterResolutionCollection オブジェクト

### getPrinterSettings {#getPrinterSettings--}
```
public com.aspose.ms.System.Drawing.Printing.PrinterSettings getPrinterSettings()
```

PrinterSettings オブジェクトを返します。

**Returns:**
PrinterSettings オブジェクト

### getPrintFileName {#getPrintFileName--}
```
public String getPrintFileName()
```

ファイルに印刷する際のファイル名を取得または設定します。

**Returns:**
string オブジェクト

### getPrintRange {#getPrintRange--}
```
public int getPrintRange()
```

ユーザーが指定した印刷ページ番号を取得または設定します。

**Returns:**
int 値 @see PdfPrintRange

### getSelectedPages {#getSelectedPages--}
```
public int[] getSelectedPages()
```

印刷するために選択されたページ数を取得します。

**Returns:**
pagesList int 配列 @see PdfPrintRange

### getToPage {#getToPage--}
```
public int getToPage()
```

印刷する最終ページ番号を取得または設定します。

**Returns:**
int 値です。

### isCollate {#isCollate--}
```
public boolean isCollate()
```

印刷された文書が綴じられるかどうかを示す値を取得または設定します。

**Returns:**
ブール値

### isDefaultPrinter {#isDefaultPrinter--}
```
public boolean isDefaultPrinter()
```

ユーザーが明示的に PrinterName を設定した場合を除き、PrinterName プロパティが既定のプリンターを示すかどうかを示す値を取得します。

**Returns:**
ブール値

### isDirectPrintingSupported {#isDirectPrintingSupported-com.aspose.pdf.ImageType-}
プリンターが DirectPrinting をサポートしているかどうかを示す値を取得します。

### isDirectPrintingSupported {#isDirectPrintingSupported-java.lang.String-}
プリンターが DirectPrinting をサポートしているかどうかを示す値を取得します。

### isPlotter {#isPlotter--}
```
public boolean isPlotter()
```

プリンターがプロッタであるかどうかを示す値を取得します。

**Returns:**
ブール値

### isPrintToFile {#isPrintToFile--}
```
public boolean isPrintToFile()
```

印刷出力がポートではなくファイルに送られるかどうかを示す値を取得します。

**Returns:**
ブール値

### isSupportsColor {#isSupportsColor--}
```
public boolean isSupportsColor()
```

このプリンターがカラー印刷をサポートしているかどうかを示す値を取得します。

**Returns:**
ブール値

### isValid {#isValid--}
```
public boolean isValid()
```

PrinterName プロパティが有効なプリンターを示すかどうかを示す値を取得します。

**Returns:**
ブール値

### setCollate {#setCollate-boolean-}
```
public void setCollate(boolean value)
```

印刷された文書が綴じられるかどうかを示す値を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setCopies {#setCopies-short-}
```
public void setCopies(short value)
```

印刷する文書のコピー数を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | コピー数 |

### setDuplex {#setDuplex-int-}
```
public void setDuplex(int value)
```

両面印刷のプリンター設定を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値 @see DuplexKind |

### setFromPage {#setFromPage-int-}
```
public void setFromPage(int value)
```

印刷する最初のページ番号を取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setMaximumPage {#setMaximumPage-int-}
```
public void setMaximumPage(int value)
```

PrintDialogで選択できる最大のFromPageまたはToPageを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setMinimumPage {#setMinimumPage-int-}
```
public void setMinimumPage(int value)
```

PrintDialogで選択できる最小のFromPageまたはToPageを取得または設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setPrinterName {#setPrinterName-java.lang.String-}
使用するプリンターの名前を設定します。

### setPrintFileName {#setPrintFileName-java.lang.String-}
印刷するファイル名を設定します。

### setPrintRange {#setPrintRange-int-}
```
public void setPrintRange(int value)
```

ユーザーが指定した印刷ページ番号を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | PdfPrintRange 要素 @see PdfPrintRange |

### setPrintToFile {#setPrintToFile-boolean-}
```
public void setPrintToFile(boolean value)
```

印刷出力がポートではなくファイルに送られるかどうかを示す値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setSelectedPages {#setSelectedPages-int:A-}
```
public void setSelectedPages(int[] pagesList)
```

印刷するために選択されたページ数を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pagesList |  | int 配列 @see PdfPrintRange |

### setToPage {#setToPage-int-}
```
public void setToPage(int value)
```

印刷する最終ページ番号を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | PdfPrintRange 要素 @see PdfPrintRange |
