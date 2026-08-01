---
title: "クラス PdfViewer"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Facades.PdfViewer クラス。PDF を表示または印刷するためのクラスを表します。"
type: docs
weight: 4750
url: /ja/net/aspose.pdf.facades/pdfviewer/
---
## PdfViewer class

pdf を表示または印刷するクラスを表します。

```csharp
public sealed class PdfViewer : IFacade
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfViewer](pdfviewer/#constructor)() | `PdfViewer` オブジェクトを新規に初期化します。 |
| [PdfViewer](pdfviewer/#constructor_1)(Document) | `PdfViewer` オブジェクトを新規に初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AutoResize](../../aspose.pdf.facades/pdfviewer/autoresize/) { get; set; } | ファイルが最適化サイズで印刷されるかどうかを示す bool 値を取得または設定します。false の場合、ページをスケーリングせずに印刷します。true の場合、印刷可能領域に合わせてスケーリングしてページを印刷します。 |
| [AutoRotate](../../aspose.pdf.facades/pdfviewer/autorotate/) { get; set; } | ファイルが自動回転で印刷されるかどうかを示す bool 値を取得または設定します。 |
| [AutoRotateMode](../../aspose.pdf.facades/pdfviewer/autorotatemode/) { get; set; } | 回転方向を示す AutoRotateMode 値を取得または設定します。 |
| [CoordinateType](../../aspose.pdf.facades/pdfviewer/coordinatetype/) { get; set; } | ページ座標タイプ（Media/Crop ボックス）を取得または設定します。デフォルトでは CropBox の値が使用されます。 |
| [FormPresentationMode](../../aspose.pdf.facades/pdfviewer/formpresentationmode/) { get; set; } | フォームの表示モードを取得または設定します。 |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfviewer/horizontalalignment/) { get; set; } | 水平揃えを示す値を取得または設定します |
| [PageCount](../../aspose.pdf.facades/pdfviewer/pagecount/) { get; } | 現在のPdfファイルのページ数を取得します。 |
| [Password](../../aspose.pdf.facades/pdfviewer/password/) { get; set; } | 入力ドキュメントのパスワードを取得または設定します。 |
| [PrintAsGrayscale](../../aspose.pdf.facades/pdfviewer/printasgrayscale/) { get; set; } | ページがグレースケールで印刷されるかどうかを示すブール値を取得または設定します。既定値は false です。 |
| [PrintAsImage](../../aspose.pdf.facades/pdfviewer/printasimage/) { get; set; } | PdfViewer が画像として印刷するモードを設定または取得します。 |
| [PrinterJobName](../../aspose.pdf.facades/pdfviewer/printerjobname/) { get; set; } | ドキュメントが印刷される際のプリンターキュー内のドキュメント名を取得または設定します。既定値はファイル名です。 |
| [PrintPageDialog](../../aspose.pdf.facades/pdfviewer/printpagedialog/) { get; set; } | 印刷時にページ番号ダイアログを表示するかどうかを示すブール値を取得または設定します。 |
| [PrintStatus](../../aspose.pdf.facades/pdfviewer/printstatus/) { get; } | 印刷ジョブの結果を取得します。成功した場合は null、そうでない場合は例外オブジェクトです。 |
| [RenderingOptions](../../aspose.pdf.facades/pdfviewer/renderingoptions/) { get; set; } | レンダリングオプションを取得または設定します。 |
| [Resolution](../../aspose.pdf.facades/pdfviewer/resolution/) { get; set; } | 表示および印刷時の解像度を取得または設定します。解像度が高いほど速度が遅くなります。既定値は 150 です。 |
| [ScaleFactor](../../aspose.pdf.facades/pdfviewer/scalefactor/) { get; set; } | 拡大縮小率を示す浮動小数点値を取得または設定します。既定値は 1.0 です。 |
| [UseIntermidiateImage](../../aspose.pdf.facades/pdfviewer/useintermidiateimage/) { get; set; } | ファイルモードで印刷中に pdf ページを中間の png ファイルに変換するかどうかを取得/設定します。出力ファイルのサイズが重要な場合に使用してください。 |
| [VerticalAlignment](../../aspose.pdf.facades/pdfviewer/verticalalignment/) { get; set; } | 垂直揃えを示す値を取得または設定します |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf)(Document) | ファサードを初期化します。 |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf_1)(Stream) | ファサードを初期化します。 |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf_2)(string) | ファサードを初期化します。 |
| [Close](../../aspose.pdf.facades/pdfviewer/close/)() | ファサードを閉じます。 |
| [DecodeAllPages](../../aspose.pdf.facades/pdfviewer/decodeallpages/)() | 現在の pdf ファイルのページを取得します。 |
| [DecodePage](../../aspose.pdf.facades/pdfviewer/decodepage/)(int) | 1つの Pdf ファイルのページをデコードします。 |
| [Dispose](../../aspose.pdf.facades/pdfviewer/dispose/)() | ファサードリソースを解放します。 |
| [GetDefaultPageSettings](../../aspose.pdf.facades/pdfviewer/getdefaultpagesettings/)() | 既定のページ設定を取得します。 |
| [GetDefaultPrinterSettings](../../aspose.pdf.facades/pdfviewer/getdefaultprintersettings/)() | 既定のプリンター設定を取得します。 |
| [PrintDocument](../../aspose.pdf.facades/pdfviewer/printdocument/)() | 既定のプリンターを使用して Pdf ドキュメントを印刷します。 |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings/#printdocumentwithsettings_1)(PrinterSettings) | プリンター設定で Pdf ドキュメントを印刷します。出力ページサイズはドキュメントの最初のページサイズに合わせられます。 |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings/#printdocumentwithsettings)(PageSettings, PrinterSettings) | 設定で Pdf ドキュメントを印刷します。ドキュメントサイズがページサイズと合わない場合、ページサイズに合わせて拡張されます。 |
| [PrintDocumentWithSetup](../../aspose.pdf.facades/pdfviewer/printdocumentwithsetup/)() | 設定ダイアログで Pdf ドキュメントを印刷します。ダイアログを使用してプリンターを選択してください。 |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf)(Stream) | 大きな Pdf ストリームを開いて印刷します。Pdf ファイルが数百ページ以上、またはサイズが 3 MB を超える場合、このメソッドの使用を推奨します。 |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_3)(string) | 大きな Pdf ファイルを開いて印刷します。Pdf ファイルが数百ページ以上、またはサイズが 3 MB を超える場合、このメソッドの使用を推奨します。 |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_2)(Stream, PrinterSettings) | 指定されたプリンター設定で大きなPdfストリームを開き、印刷します。Pdfファイルが数百ページ以上、またはサイズが3 MBを超える場合、このメソッドはより高いパフォーマンスを得るために推奨されます。 |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_5)(string, PrinterSettings) | 指定されたプリンター設定で大きなPdfファイルを開き、印刷します。Pdfファイルが数百ページ以上、またはサイズが3 MBを超える場合、このメソッドはより高いパフォーマンスを得るために推奨されます。 |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_1)(Stream, PageSettings, PrinterSettings) | 指定されたページ設定とプリンター設定で大きなPdfストリームを開き、印刷します。Pdfファイルが数百ページ以上、またはサイズが3 MBを超える場合、このメソッドはより高いパフォーマンスを得るために推奨されます。 |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_4)(string, PageSettings, PrinterSettings) | 指定されたページ設定とプリンター設定で大きなPdfファイルを開き、印刷します。Pdfファイルが数百ページ以上、またはサイズが3 MBを超える場合、このメソッドはより高いパフォーマンスを得るために推奨されます。 |
| [Save](../../aspose.pdf.facades/pdfviewer/save/#save)(Stream) | 結果のPDFドキュメントをストリームに保存します。 |
| [Save](../../aspose.pdf.facades/pdfviewer/save/#save_1)(string) | 結果のPDFドキュメントをファイルに保存します。 |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments)(params Document[]) | デフォルトのプリンターとページ設定を使用して複数のPDFドキュメントを印刷します。 |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments_7)(params Stream[]) | 提供されたストリームからデフォルトのプリンターとページ設定を使用して複数のPDFドキュメントを印刷します。 |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments_8)(params string[]) | デフォルトのプリンターとページ設定を使用して複数のPDFドキュメントを印刷します。 |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments_1)(PrinterSettings, params Document[]) | 指定されたプリンター設定を使用して複数のPDFドキュメントを印刷します。 |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments_5)(PrinterSettings, params Stream[]) | 提供されたストリームから指定されたプリンター設定を使用して複数のPDFドキュメントを印刷します。 |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments_6)(PrinterSettings, params string[]) | 指定されたプリンター設定を使用して複数のPDFドキュメントを印刷します。 |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments_2)(PrinterSettings, PageSettings, params Document[]) | 指定されたプリンターとページ設定を使用して複数のPDFドキュメントを印刷します。 |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments_3)(PrinterSettings, PageSettings, params Stream[]) | 提供されたストリームから指定されたプリンターとページ設定を使用して複数のPDFドキュメントを印刷します。 |
| static [PrintDocuments](../../aspose.pdf.facades/pdfviewer/printdocuments/#printdocuments_4)(PrinterSettings, PageSettings, params string[]) | 指定されたプリンターとページ設定を使用して複数のPDFドキュメントを印刷します。 |

## イベント

| 名前 | 説明 |
| --- | --- |
| event [CustomPrint](../../aspose.pdf.facades/pdfviewer/customprint/) | 印刷が開始される前に発生し、デフォルトのハンドラの代わりにカスタム印刷ハンドラを提供できるようにします。 |
| event [EndPage](../../aspose.pdf.facades/pdfviewer/endpage/) | PdfViewerでページの印刷が終了したときに発生します。 |
| event [EndPrint](../../aspose.pdf.facades/pdfviewer/endprint/) | 最後のページ印刷イベントへのサブスクリプションを追加/削除します。 |
| event [PdfQueryPageSettings](../../aspose.pdf.facades/pdfviewer/pdfquerypagesettings/) | 最後のページ印刷イベントへのサブスクリプションを追加/削除します。 |
| event [StartPage](../../aspose.pdf.facades/pdfviewer/startpage/) | ページの印刷が開始される前に発生します。 |

### 関連項目

* interface [IFacade](../ifacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


