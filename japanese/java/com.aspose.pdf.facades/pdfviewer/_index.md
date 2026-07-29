---
title: "PdfViewer"
linktitle: "PdfViewer"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF を表示または印刷するクラスを表します。"
type: docs
weight: 610
url: /ja/java/com.aspose.pdf.facades/pdfviewer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfViewer

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public final class PdfViewer extends Object implements IFacade
```

PDF を表示または印刷するクラスを表します。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [CustomPrint](#CustomPrint) |  |
| [EndPrint](#EndPrint) | 最終ページ印刷イベントのサブスクリプションを追加/削除します。 |
| [PdfQueryPageSettings](#PdfQueryPageSettings) | 最終ページ印刷イベントのサブスクリプションを追加/削除します。 |

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PdfViewer](#PdfViewer--) | 新しい {@code PdfViewer} オブジェクトを初期化します。 |
| [PdfViewer](#PdfViewer-com.aspose.pdf.IDocument-) | 新しい {@code PdfViewer} オブジェクトを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.IDocument-) | ファサードを初期化します。 |
| [bindPdf](#bindPdf-java.io.InputStream-) | ファサードを初期化します。 |
| [bindPdf](#bindPdf-java.lang.String-) | ファサードを初期化します。 |
| [close](#close--) | 現在の PDF ファイルを閉じます。 |
| [closePdfFile](#closePdfFile--) | 現在の PDF ファイルを閉じます。 |
| [decodeAllPages](#decodeAllPages--) | 現在の PDF ファイルのページを取得します。 |
| [decodePage](#decodePage-int-) | 1つの Pdf ファイルのページをデコードします。 |
| [decodePageToImage](#decodePageToImage-int-com.aspose.pdf.ImageType-) | ページを BufferedImage にデコードします |
| [dispose](#dispose--) | ファサードリソースを破棄します。このメソッドは廃止予定です。代わりに close() を使用してください。 |
| [getAutoResize](#getAutoResize--) | ファイルが最適化サイズで印刷されるかどうかを示す bool 値を設定します。 |
| [getAutoRotate](#getAutoRotate--) | ファイルが自動回転で印刷されるかどうかを示す bool 値を取得します |
| [getAutoRotateMode](#getAutoRotateMode--) | 回転方向を示す AutoRotateMode 値を取得します |
| [getCoordinateType](#getCoordinateType--) | ページ座標タイプ (Media/Crop ボックス) を取得します。デフォルトでは CropBox の値が使用されます。 |
| [getCopiesPrinted](#getCopiesPrinted--) | 印刷された部数を取得します |
| [getDefaultPageSettings](#getDefaultPageSettings--) | デフォルトのページ設定を取得します。 |
| [getDefaultPrinterSettings](#getDefaultPrinterSettings--) | デフォルトのプリンター設定を取得します。 |
| [getFormPresentationMode](#getFormPresentationMode--) | フォームの表示モードを取得します。 |
| [getHorizontalAlignment](#getHorizontalAlignment--) | 水平揃えを示す値を取得します |
| [getPageCount](#getPageCount--) | 現在の Pdf ファイルのページ数を取得します。 |
| [getPassword](#getPassword--) | 入力ドキュメントのパスワードを取得します。 |
| [getPrintAsGrayscale](#getPrintAsGrayscale--) | <p> ページがグレースケールで印刷されるかどうかを示す bool 値を取得または設定します。デフォルトは false です。 </p> <hr> デフォルトの false は false です. |
| [getPrintAsImage](#getPrintAsImage--) | <p> PdfViewer が画像として印刷するモードを取得します。 </p> |
| [getPrinterJobName](#getPrinterJobName--) | ドキュメントが印刷されるときのプリンターキュー内のドキュメント名を取得します。デフォルト値はファイル名です。 |
| [getPrintPageDialog](#getPrintPageDialog--) | 印刷時にページ番号ダイアログを生成するかどうかを示す bool 値を取得します。 |
| [getPrintStatus](#getPrintStatus--) | 印刷ジョブの結果を取得します。成功した場合は null、そうでない場合は例外オブジェクトです。 |
| [getRenderingOptions](#getRenderingOptions--) | レンダリング オプションを取得します。 |
| [getResolution](#getResolution--) | 表示および印刷時の解像度を取得または設定します。解像度が高いほど速度は遅くなります。デフォルト値は 150 です。このプロパティはページから画像への変換フローで画像解像度を変更します：{@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) が {@code } に設定されている場合、または {@link #decodePage(int)} や {@link #decodeAllPages} メソッドが呼び出された場合。プリンターへの直接印刷用にプリンター解像度を設定するには、{@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) プロパティを {@code PageSettings} クラスで使用してください。 |
| [getScaleFactor](#getScaleFactor--) | スケール係数を示す浮動小数点値を取得します。デフォルト値は 1.0 です。 |
| [getUseIntermidiateImage](#getUseIntermidiateImage--) | ファイルモードで印刷中に pdf ページを中間 PNG ファイルに変換する使用状況を取得します。出力ファイルのサイズが重要な場合に使用してください。 |
| [getVerticalAlignment](#getVerticalAlignment--) | 垂直揃えを示す値を取得します |
| [isShowHiddenAreas](#isShowHiddenAreas--) | このメソッドは非推奨です。ページ上の非表示領域の可視性を制御するフラグを取得します。 |
| [openPdfFile](#openPdfFile-java.io.InputStream-) | <p> Pdf ファイルストリームを開きます。ただし、Pdf ファイルのページは実際にはデコードされません。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile(new FileInputStream("d:\\\\test.pdf"))); viewer.closePdfFile(); </pre> |
| [openPdfFile](#openPdfFile-java.lang.String-) | <p> Pdf ファイルを開きますが、Pdf ファイルのページは実際にはデコードされません。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.closePdfFile(); </pre> |
| [printDocument](#printDocument--) | <p> デフォルトプリンターを使用して Pdf ドキュメントを印刷します。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false); //do not produce the page number dialog when printing viewer.printDocument(ps); viewer.closePdfFile(); </pre> |
| [printDocumentWithSettings](#printDocumentWithSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> プリンター設定で Pdf ドキュメントを印刷します。 出力ページサイズはドキュメントの最初のページサイズに合わせられます。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false); //do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().PrinterName()); viewer.printDocumentWithSettings(ps); viewer.closePdfFile(); </pre> |
| [printDocumentWithSettings](#printDocumentWithSettings-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> 設定で Pdf ドキュメントを印刷します。 ドキュメントサイズがページサイズに合わない場合、pdf.kit がページサイズに合わせて拡張します。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings.getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize("A4", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printDocumentWithSettings(pgs, ps); viewer.closePdfFile(); </pre> |
| [printLargePdf](#printLargePdf-java.io.InputStream-) | <p> 大きな Pdf ストリームを開いて印刷します。 Pdf ファイルが数百ページ以上、またはサイズが 3 MB を超える場合、このメソッドはより高いパフォーマンスを得るために推奨されます。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.printPageDialog=false;//do not produce the page number dialog when printing viewer.printLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\\test.pdf"))); viewer.closePdfFile(); </pre> <hr> このメソッドはファイルのオープンと印刷を統合しており、OpenPdfFile() を明示的に呼び出す必要はありません。 |
| [printLargePdf](#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> 指定されたプリンター設定で大きな Pdf ストリームを開いて印刷します。 Pdf ファイルが数百ページ以上、またはサイズが 3 MB を超える場合、このメソッドはより高いパフォーマンスを得るために推奨されます。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false); // do not produce the page number dialog when // printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf(new FileInputStream("d:\\\\middleware.pdf"), ps); viewer.closePdfFile(); </pre> <hr> このメソッドはファイルのオープンと印刷を統合しており、OpenPdfFile() を明示的に呼び出す必要はありません。 |
| [printLargePdf](#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> 指定されたページ設定とプリンター設定で大きな Pdf ストリームを開いて印刷します。 Pdf ファイルが数百ページ以上、またはサイズが 3 MB を超える場合、このメソッドはより高いパフォーマンスを得るために推奨されます。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize("A4", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printLargePdf(new FileInputStream("d:\\\\middleware.pdf"),pgs,ps); viewer.closePdfFile(); </pre> <hr> このメソッドはファイルのオープンと印刷を統合しており、OpenPdfFile() を明示的に呼び出す必要はありません。 |
| [printLargePdf](#printLargePdf-java.lang.String-) | <p> 大きな Pdf ファイルを開いて印刷します。 Pdf ファイルが数百ページ以上、またはサイズが 3 MB を超える場合、このメソッドはより高いパフォーマンスを得るために推奨されます。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false);// do not produce the page number dialog when // printing viewer.setPrintLargePdf("d:\\test.pdf"); </pre> |
| [printLargePdf](#printLargePdf-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> 指定されたプリンター設定で大きな Pdf ファイルを開いて印刷します。 Pdf ファイルが数百ページ以上、またはサイズが 3 MB を超える場合、このメソッドはより高いパフォーマンスを得るために推奨されます。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf("d:\\\\test.pdf",ps); viewer.closePdfFile(); </pre> <hr> このメソッドはファイルのオープンと印刷を統合しており、OpenPdfFile() を明示的に呼び出す必要はありません。 |
| [printLargePdf](#printLargePdf-java.lang.String-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> 指定されたページ設定とプリンター設定で大きな Pdf ファイルを開き、印刷します。もし Pdf ファイルが数百ページ以上、またはサイズが 3 MB を超える場合は、より高いパフォーマンスを得るためにこのメソッドの使用が推奨されます。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false); // do not produce the page number dialog when // printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize(new PaperSize("A4", 827, 1169)); pgs.setMargins(new Margins(0, 0, 0, 0)); viewer.printLargePdf("d:\\\\test.pdf", pgs, ps); viewer.closePdfFile(); </pre> <hr> このメソッドはファイルのオープンと印刷を統合しているため、OpenPdfFile() を明示的に呼び出す必要はありません。 |
| [save](#save-java.io.InputStream-) | 結果の PDF ドキュメントをストリームに保存します。 |
| [save](#save-java.lang.String-) | 結果の PDF ドキュメントをファイルに保存します。 |
| [setAutoResize](#setAutoResize-boolean-) | ファイルが最適化サイズで印刷されるかどうかを示す bool 値を設定します。 |
| [setAutoRotate](#setAutoRotate-boolean-) | ファイルが自動回転で印刷されるかどうかを示す bool 値を設定します。 |
| [setAutoRotateMode](#setAutoRotateMode-int-) | 回転方向を示す AutoRotateMode 値を設定します。 |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | ページ座標タイプ (Media/Crop ボックス) を設定します。デフォルトでは CropBox の値が使用されます。 |
| [setFormPresentationMode](#setFormPresentationMode-int-) | フォームの表示モードを設定します。 |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | 水平揃えを示す値を設定します。 |
| [setPassword](#setPassword-java.lang.String-) | 入力ドキュメントのパスワードを設定します。 |
| [setPrintAsGrayscale](#setPrintAsGrayscale-boolean-) | <p> ページがグレースケールで印刷されるかどうかを示す bool 値を取得または設定します。デフォルトは false です。 </p> <hr> デフォルトの false は false です. |
| [setPrintAsImage](#setPrintAsImage-boolean-) | <p> PdfViewer が画像として印刷するモードを設定します。 </p> |
| [setPrinterJobName](#setPrinterJobName-java.lang.String-) | ドキュメントが印刷される際のプリンターキュー内のドキュメント名を設定します。デフォルト値はファイル名です。 |
| [setPrintPageDialog](#setPrintPageDialog-boolean-) | 印刷時にページ番号ダイアログを生成するかどうかを示す boolean 値を設定します。 |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | レンダリング オプションを設定します。 |
| [setResolution](#setResolution-int-) | 表示および印刷時の解像度を設定します。解像度が高いほど速度は遅くなります。デフォルト値は 150 です。このプロパティはページから画像への変換フローで画像解像度を変更します：{@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) が {@code } に設定されている場合、または {@link #decodePage(int)} や {@link #decodeAllPages} メソッドが呼び出された場合。プリンターへの直接印刷用にプリンター解像度を設定するには、{@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) プロパティを {@code PageSettings} クラスで使用してください。 |
| [setScaleFactor](#setScaleFactor-float-) | スケール係数を示す浮動小数点値を設定します。デフォルト値は 1.0 です。 |
| [setShowHiddenAreas](#setShowHiddenAreas-boolean-) | 非推奨です。 |
| [setUseIntermidiateImage](#setUseIntermidiateImage-boolean-) | ファイルモードで印刷中に PDF ページを中間 PNG ファイルに変換して使用するかを設定します。出力ファイルのサイズが重要な場合に使用してください。 |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | 垂直揃えを示す値を設定します。 |

### CustomPrint {#CustomPrint}
```
public final com.aspose.ms.lang.Event<com.aspose.ms.System.EventHandler< CustomPrintEventArgs >> CustomPrint
```



### EndPrint {#EndPrint}
```
public final PdfEvent <com.aspose.ms.System.Drawing.Printing.PrintEventHandler> EndPrint
```

最終ページ印刷イベントのサブスクリプションを追加/削除します。

### PdfQueryPageSettings {#PdfQueryPageSettings}
```
public final PdfEvent < PdfQueryPageSettingsEventHandler > PdfQueryPageSettings
```

最終ページ印刷イベントのサブスクリプションを追加/削除します。

### PdfViewer {#PdfViewer--}
```
public PdfViewer()
```

新しい {@code PdfViewer} オブジェクトを初期化します。

### PdfViewer {#PdfViewer-com.aspose.pdf.IDocument-}
新しい {@code PdfViewer} オブジェクトを初期化します。

### bindPdf {#bindPdf-com.aspose.pdf.IDocument-}
ファサードを初期化します。

### bindPdf {#bindPdf-java.io.InputStream-}
ファサードを初期化します。

### bindPdf {#bindPdf-java.lang.String-}
ファサードを初期化します。

### close {#close--}
```
public void close()
```

現在の PDF ファイルを閉じます。

### closePdfFile {#closePdfFile--}
```
public void closePdfFile()
```

現在の PDF ファイルを閉じます。

### decodeAllPages {#decodeAllPages--}
```
public BufferedImage [] decodeAllPages()
```

現在の PDF ファイルのページを取得します。

**Returns:**
Pdf ページ画像の配列を返します。

### decodePage {#decodePage-int-}
```
public BufferedImage decodePage(int pageNumber)
```

1つの Pdf ファイルのページをデコードします。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageNumber |  | 1 から PageCount の間でなければならない、1 つの Pdf ファイルのページ番号です。 |

**Returns:**
Pdf ページ画像を返します。

### decodePageToImage {#decodePageToImage-int-com.aspose.pdf.ImageType-}
ページを BufferedImage にデコードします

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

ファサードリソースを破棄します。このメソッドは廃止予定です。代わりに close() を使用してください。

### getAutoResize {#getAutoResize--}
```
public boolean getAutoResize()
```

ファイルが最適化サイズで印刷されるかどうかを示す bool 値を設定します。

**Returns:**
boolean 値: false の場合はページをスケーリングせずに印刷します。true の場合は印刷可能領域に合わせてスケーリングして印刷します。

### getAutoRotate {#getAutoRotate--}
```
public boolean getAutoRotate()
```

ファイルが自動回転で印刷されるかどうかを示す bool 値を取得します

**Returns:**
ブール値

### getAutoRotateMode {#getAutoRotateMode--}
```
public int getAutoRotateMode()
```

回転方向を示す AutoRotateMode 値を取得します

**Returns:**
AutoRotateMode 要素 @see AutoRotateMode

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

ページ座標タイプ (Media/Crop ボックス) を取得します。デフォルトでは CropBox の値が使用されます。

**Returns:**
PageCoordinateType 要素 @see PageCoordinateType

### getCopiesPrinted {#getCopiesPrinted--}
```
public int getCopiesPrinted()
```

印刷された部数を取得します

**Returns:**
int 値です。

### getDefaultPageSettings {#getDefaultPageSettings--}
```
public PrintPageSettings getDefaultPageSettings()
```

デフォルトのページ設定を取得します。

**Returns:**
ページ設定オブジェクト。

### getDefaultPrinterSettings {#getDefaultPrinterSettings--}
```
public PdfPrinterSettings getDefaultPrinterSettings()
```

デフォルトのプリンター設定を取得します。

**Returns:**
ページ設定オブジェクト。

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

フォームの表示モードを取得します。

**Returns:**
FormPresentationMode 要素 @see FormPresentationMode

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

水平揃えを示す値を取得します

**Returns:**
HorizontalAlignment 要素 @see HorizontalAlignment

### getPageCount {#getPageCount--}
```
public int getPageCount()
```

現在の Pdf ファイルのページ数を取得します。

**Returns:**
ページ数を返します。

### getPassword {#getPassword--}
```
public String getPassword()
```

入力ドキュメントのパスワードを取得します。

**Returns:**
文字列値

### getPrintAsGrayscale {#getPrintAsGrayscale--}
```
public boolean getPrintAsGrayscale()
```

<p> ページがグレースケールで印刷されるかどうかを示す bool 値を取得または設定します。デフォルトは false です。 </p> <hr> デフォルトの false は false です.

**Returns:**
ブール値

### getPrintAsImage {#getPrintAsImage--}
```
public boolean getPrintAsImage()
```

<p> PdfViewer が画像として印刷するモードを取得します。 </p>

**Returns:**
boolean 値 <hr> true の場合は常に画像として印刷します（印刷される画像を生成）。false の場合は、すべての機能がサポートされていればデバイスに直接印刷します。ドキュメントにサポートされていない機能が含まれる場合、システムは自動的に画像として印刷することを決定する場合があります。デフォルト値は false です。

### getPrinterJobName {#getPrinterJobName--}
```
public String getPrinterJobName()
```

ドキュメントが印刷されるときのプリンターキュー内のドキュメント名を取得します。デフォルト値はファイル名です。

**Returns:**
文字列値

### getPrintPageDialog {#getPrintPageDialog--}
```
public boolean getPrintPageDialog()
```

印刷時にページ番号ダイアログを生成するかどうかを示す bool 値を取得します。

**Returns:**
ブール値

### getPrintStatus {#getPrintStatus--}
```
public Object getPrintStatus()
```

印刷ジョブの結果を取得します。成功した場合は null、そうでない場合は例外オブジェクトです。

**Returns:**
例外オブジェクトまたは null

### getRenderingOptions {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```

レンダリング オプションを取得します。

**Returns:**
RenderingOptions オブジェクト

### getResolution {#getResolution--}
```
public int getResolution()
```

表示および印刷時の解像度を取得または設定します。解像度が高いほど速度は遅くなります。デフォルト値は 150 です。このプロパティはページから画像への変換フローで画像解像度を変更します：{@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) が {@code } に設定されている場合、または {@link #decodePage(int)} や {@link #decodeAllPages} メソッドが呼び出された場合。プリンターへの直接印刷用にプリンター解像度を設定するには、{@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) プロパティを {@code PageSettings} クラスで使用してください。

**Returns:**
int 値です。

### getScaleFactor {#getScaleFactor--}
```
public float getScaleFactor()
```

スケール係数を示す浮動小数点値を取得します。デフォルト値は 1.0 です。

**Returns:**
浮動小数点値。

### getUseIntermidiateImage {#getUseIntermidiateImage--}
```
public boolean getUseIntermidiateImage()
```

ファイルモードで印刷中に pdf ページを中間 PNG ファイルに変換する使用状況を取得します。出力ファイルのサイズが重要な場合に使用してください。

**Returns:**
ブール値。

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

垂直揃えを示す値を取得します

**Returns:**
VerticalAlignment 要素 @see VerticalAlignment

### isShowHiddenAreas {#isShowHiddenAreas--}
```
@Deprecated public boolean isShowHiddenAreas()
```

このメソッドは非推奨です。ページ上の非表示領域の可視性を制御するフラグを取得します。

**Returns:**
ブール値

### openPdfFile {#openPdfFile-java.io.InputStream-}
<p> Pdf ファイルストリームを開きます。ただし、Pdf ファイルのページは実際にはデコードされません。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile(new FileInputStream("d:\\test.pdf"))); viewer.closePdfFile(); </pre>

### openPdfFile {#openPdfFile-java.lang.String-}
<p> Pdf ファイルを開きますが、Pdf ファイルのページは実際にはデコードされません。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\test.pdf"); viewer.closePdfFile(); </pre>

### printDocument {#printDocument--}
```
public void printDocument()
```

<p> デフォルトプリンターを使用して Pdf ドキュメントを印刷します。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\test.pdf"); viewer.setAutoResize ( true); //調整されたサイズでファイルを印刷 viewer.setAutoRotate ( true); //調整された回転でファイルを印刷 viewer.setPrintPageDialog ( false); //印刷時にページ番号ダイアログを表示しない viewer.printDocument(ps); viewer.closePdfFile(); </pre>

### printDocumentWithSettings {#printDocumentWithSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> プリンター設定を使用して Pdf ドキュメントを印刷します。出力ページサイズは文書の最初のページサイズに合わせます。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\test.pdf"); viewer.setAutoResize ( true); //調整されたサイズでファイルを印刷 viewer.setAutoRotate ( true); //調整された回転でファイルを印刷 viewer.setPrintPageDialog ( false); //印刷時にページ番号ダイアログを表示しない PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().PrinterName()); viewer.printDocumentWithSettings(ps); viewer.closePdfFile(); </pre>

### printDocumentWithSettings {#printDocumentWithSettings-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> 設定を使用して Pdf ドキュメントを印刷します。文書サイズがページサイズに合わない場合、pdf.kit はページサイズに合わせて拡張します。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\test.pdf"); viewer.setAutoResize ( true); //調整されたサイズでファイルを印刷 viewer.setAutoRotate ( true); //調整された回転でファイルを印刷 viewer.setPrintPageDialog ( false);//印刷時にページ番号ダイアログを表示しない PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings.getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize("A4", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printDocumentWithSettings(pgs, ps); viewer.closePdfFile(); </pre>

### printLargePdf {#printLargePdf-java.io.InputStream-}
<p> 大きな Pdf ストリームを開いて印刷します。Pdf ファイルが数百ページ以上、またはサイズが 3 MB を超える場合、このメソッドを使用するとパフォーマンスが向上します。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //調整されたサイズでファイルを印刷 viewer.setAutoRotate ( true); //調整された回転でファイルを印刷 viewer.printPageDialog=false;//印刷時にページ番号ダイアログを表示しない viewer.printLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\test.pdf"))); viewer.closePdfFile(); </pre> <hr> このメソッドはファイルのオープンと印刷を統合しており、OpenPdfFile() を明示的に呼び出す必要はありません.

### printLargePdf {#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> 指定されたプリンター設定で大きな Pdf ストリームを開いて印刷します。Pdf ファイルが数百ページ以上、またはサイズが 3 MB を超える場合、このメソッドを使用するとパフォーマンスが向上します。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // 調整されたサイズでファイルを印刷 viewer.setAutoRotate(true); // 調整された回転でファイルを印刷 viewer.setPrintPageDialog(false); // 印刷時にページ番号ダイアログを表示しない PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf(new FileInputStream("d:\\middleware.pdf"), ps); viewer.closePdfFile(); </pre> <hr> このメソッドはファイルのオープンと印刷を統合しており、OpenPdfFile() を明示的に呼び出す必要はありません.

### printLargePdf {#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> 指定されたページ設定とプリンター設定で大きな Pdf ストリームを開いて印刷します。Pdf ファイルが数百ページ以上、またはサイズが 3 MB を超える場合、このメソッドを使用するとパフォーマンスが向上します。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //調整されたサイズでファイルを印刷 viewer.setAutoRotate ( true); //調整された回転でファイルを印刷 viewer.setPrintPageDialog ( false);//印刷時にページ番号ダイアログを表示しない PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize("A4", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printLargePdf(new FileInputStream("d:\\middleware.pdf"),pgs,ps); viewer.closePdfFile(); </pre> <hr> このメソッドはファイルのオープンと印刷を統合しており、OpenPdfFile() を明示的に呼び出す必要はありません.

### printLargePdf {#printLargePdf-java.lang.String-}
<p> 大きな Pdf ファイルを開いて印刷します。Pdf ファイルが数百ページ以上、またはサイズが 3 MB を超える場合、このメソッドを使用するとパフォーマンスが向上します。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // 調整されたサイズでファイルを印刷 viewer.setAutoRotate(true); // 調整された回転でファイルを印刷 viewer.setPrintPageDialog(false);// 印刷時にページ番号ダイアログを表示しない viewer.setPrintLargePdf("d:\test.pdf"); </pre>

### printLargePdf {#printLargePdf-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> 指定されたプリンター設定で大きな Pdf ファイルを開き、印刷します。もし Pdf ファイルが数百ページ以上、またはサイズが 3 MB を超える場合は、より良いパフォーマンスを得るためにこのメソッドの使用が推奨されます。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf("d:\\test.pdf",ps); viewer.closePdfFile(); </pre> <hr> このメソッドはファイルのオープンと印刷を統合しており、OpenPdfFile() を明示的に呼び出す必要はありません。

### printLargePdf {#printLargePdf-java.lang.String-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> 指定されたページ設定とプリンター設定で大きな Pdf ファイルを開き、印刷します。もし Pdf ファイルが数百ページ以上、またはサイズが 3 MB を超える場合は、より良いパフォーマンスを得るためにこのメソッドの使用が推奨されます。 </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false); // do not produce the page number dialog when // printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize(new PaperSize("A4", 827, 1169)); pgs.setMargins(new Margins(0, 0, 0, 0)); viewer.printLargePdf("d:\\test.pdf", pgs, ps); viewer.closePdfFile(); </pre> <hr> このメソッドはファイルのオープンと印刷を統合しており、OpenPdfFile() を明示的に呼び出す必要はありません。

### save {#save-java.io.InputStream-}
結果の PDF ドキュメントをストリームに保存します。

### save {#save-java.lang.String-}
結果の PDF ドキュメントをファイルに保存します。

### setAutoResize {#setAutoResize-boolean-}
```
public void setAutoResize(boolean value)
```

ファイルが最適化サイズで印刷されるかどうかを示す bool 値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | boolean 値: false の場合はページをスケーリングせずに印刷します。true の場合は印刷可能領域に合わせてスケーリングして印刷します。 |

### setAutoRotate {#setAutoRotate-boolean-}
```
public void setAutoRotate(boolean value)
```

ファイルが自動回転で印刷されるかどうかを示す bool 値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setAutoRotateMode {#setAutoRotateMode-int-}
```
public void setAutoRotateMode(int value)
```

回転方向を示す AutoRotateMode 値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | AutoRotateMode 要素 @see AutoRotateMode |

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
ページ座標タイプ (Media/Crop ボックス) を設定します。デフォルトでは CropBox の値が使用されます。

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

フォームの表示モードを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | FormPresentationMode 要素 |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
水平揃えを示す値を設定します。

### setPassword {#setPassword-java.lang.String-}
入力ドキュメントのパスワードを設定します。

### setPrintAsGrayscale {#setPrintAsGrayscale-boolean-}
```
public void setPrintAsGrayscale(boolean value)
```

<p> ページがグレースケールで印刷されるかどうかを示す bool 値を取得または設定します。デフォルトは false です。 </p> <hr> デフォルトの false は false です.

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setPrintAsImage {#setPrintAsImage-boolean-}
```
public void setPrintAsImage(boolean value)
```

<p> PdfViewer が画像として印刷するモードを設定します。 </p>

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | boolean 値 <hr> true の場合は常に画像として印刷します（印刷される画像を生成）。false の場合は、すべての機能がサポートされていればデバイスに直接印刷します。ドキュメントにサポートされていない機能が含まれる場合、システムは自動的に画像として印刷することを決定する場合があります。デフォルト値は false です。 |

### setPrinterJobName {#setPrinterJobName-java.lang.String-}
ドキュメントが印刷される際のプリンターキュー内のドキュメント名を設定します。デフォルト値はファイル名です。

### setPrintPageDialog {#setPrintPageDialog-boolean-}
```
public void setPrintPageDialog(boolean value)
```

印刷時にページ番号ダイアログを生成するかどうかを示す boolean 値を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
レンダリング オプションを設定します。

### setResolution {#setResolution-int-}
```
public void setResolution(int value)
```

表示および印刷時の解像度を設定します。解像度が高いほど速度は遅くなります。デフォルト値は 150 です。このプロパティはページから画像への変換フローで画像解像度を変更します：{@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) が {@code } に設定されている場合、または {@link #decodePage(int)} や {@link #decodeAllPages} メソッドが呼び出された場合。プリンターへの直接印刷用にプリンター解像度を設定するには、{@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) プロパティを {@code PageSettings} クラスで使用してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | int 値です。 |

### setScaleFactor {#setScaleFactor-float-}
```
public void setScaleFactor(float value)
```

スケール係数を示す浮動小数点値を設定します。デフォルト値は 1.0 です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 浮動小数点値。 |

### setShowHiddenAreas {#setShowHiddenAreas-boolean-}
```
@Deprecated public void setShowHiddenAreas(boolean value)
```

非推奨です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  |  |

### setUseIntermidiateImage {#setUseIntermidiateImage-boolean-}
```
public void setUseIntermidiateImage(boolean value)
```

ファイルモードで印刷中に PDF ページを中間 PNG ファイルに変換して使用するかを設定します。出力ファイルのサイズが重要な場合に使用してください。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値。 |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
垂直揃えを示す値を設定します。
