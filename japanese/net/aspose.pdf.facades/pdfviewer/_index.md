---
title: Class PdfViewer
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfViewer クラス。PDF を表示または印刷するためのクラスを表します。
type: docs
weight: 4630
url: /ja/net/aspose.pdf.facades/pdfviewer/
---
## PdfViewer クラス

PDF を表示または印刷するためのクラスを表します。

```csharp
public sealed class PdfViewer : IFacade
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfViewer](pdfviewer/#constructor)() | 新しい `PdfViewer` オブジェクトを初期化します。 |
| [PdfViewer](pdfviewer/#constructor_1)(Document) | 新しい `PdfViewer` オブジェクトを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AutoResize](../../aspose.pdf.facades/pdfviewer/autoresize/) { get; set; } | ファイルが最適化されたサイズで印刷されるかどうかを示す bool 値を取得または設定します。 false の場合はページスケーリングなしで印刷します。 true の場合は印刷可能領域に合わせてスケーリングして印刷します。 |
| [AutoRotate](../../aspose.pdf.facades/pdfviewer/autorotate/) { get; set; } | ファイルが自動回転で印刷されるかどうかを示す bool 値を取得または設定します。 |
| [AutoRotateMode](../../aspose.pdf.facades/pdfviewer/autorotatemode/) { get; set; } | 回転の方向を示す AutoRotateMode 値を取得または設定します。 |
| [CoordinateType](../../aspose.pdf.facades/pdfviewer/coordinatetype/) { get; set; } | ページの座標タイプ (メディア/クロップボックス) を取得または設定します。デフォルトでは CropBox 値が使用されます。 |
| [FormPresentationMode](../../aspose.pdf.facades/pdfviewer/formpresentationmode/) { get; set; } | フォームのプレゼンテーションモードを取得または設定します。 |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfviewer/horizontalalignment/) { get; set; } | 水平配置を示す値を取得または設定します。 |
| [PageCount](../../aspose.pdf.facades/pdfviewer/pagecount/) { get; } | 現在の PDF ファイルのページ数を取得します。 |
| [Password](../../aspose.pdf.facades/pdfviewer/password/) { get; set; } | 入力ドキュメントのパスワードを取得または設定します。 |
| [PrintAsGrayscale](../../aspose.pdf.facades/pdfviewer/printasgrayscale/) { get; set; } | ページがグレースケールで印刷されるかどうかを示す bool 値を取得または設定します。デフォルトは false です。 |
| [PrintAsImage](../../aspose.pdf.facades/pdfviewer/printasimage/) { get; set; } | PdfViewer が画像として印刷するモードを設定または取得します。 |
| [PrinterJobName](../../aspose.pdf.facades/pdfviewer/printerjobname/) { get; set; } | ドキュメントが印刷されるときにプリンタキュー内のドキュメント名を取得または設定します。デフォルト値はファイル名です。 |
| [PrintPageDialog](../../aspose.pdf.facades/pdfviewer/printpagedialog/) { get; set; } | 印刷時にページ番号ダイアログを生成するかどうかを示す bool 値を取得または設定します。 |
| [PrintStatus](../../aspose.pdf.facades/pdfviewer/printstatus/) { get; } | 印刷ジョブの結果を取得します。成功した場合は null; それ以外の場合は例外オブジェクト。 |
| [RenderingOptions](../../aspose.pdf.facades/pdfviewer/renderingoptions/) { get; set; } | レンダリングオプションを取得または設定します。 |
| [Resolution](../../aspose.pdf.facades/pdfviewer/resolution/) { get; set; } | 表示および印刷中の解像度を取得または設定します。解像度が高いほど速度が遅くなります。デフォルト値は 150 です。 |
| [ScaleFactor](../../aspose.pdf.facades/pdfviewer/scalefactor/) { get; set; } | スケールファクターを示す浮動小数点値を取得または設定します。デフォルト値は 1.0 です。 |
| [UseIntermidiateImage](../../aspose.pdf.facades/pdfviewer/useintermidiateimage/) { get; set; } | ファイルモードで印刷中に PDF ページを中間 PNG ファイルに変換するかどうかを取得または設定します。出力ファイルのサイズが重要な場合に使用します。 |
| [VerticalAlignment](../../aspose.pdf.facades/pdfviewer/verticalalignment/) { get; set; } | 垂直配置を示す値を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf)(Document) | ファサードを初期化します。 |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf_1)(Stream) | ファサードを初期化します。 |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf_2)(string) | ファサードを初期化します。 |
| [Close](../../aspose.pdf.facades/pdfviewer/close/)() | ファサードを閉じます。 |
| [DecodeAllPages](../../aspose.pdf.facades/pdfviewer/decodeallpages/)() | 現在の PDF ファイルのページを取得します。 |
| [DecodePage](../../aspose.pdf.facades/pdfviewer/decodepage/)(int) | 1 つの PDF ファイルのページをデコードします。 |
| [Dispose](../../aspose.pdf.facades/pdfviewer/dispose/)() | ファサードリソースを破棄します。 |
| [GetDefaultPageSettings](../../aspose.pdf.facades/pdfviewer/getdefaultpagesettings/)() | デフォルトのページ設定を取得します。 |
| [GetDefaultPrinterSettings](../../aspose.pdf.facades/pdfviewer/getdefaultprintersettings/)() | デフォルトのプリンタ設定を取得します。 |
| [PrintDocument](../../aspose.pdf.facades/pdfviewer/printdocument/)() | デフォルトのプリンタを使用して PDF ドキュメントを印刷します。 |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings/#printdocumentwithsettings_1)(PrinterSettings) | プリンタ設定で PDF ドキュメントを印刷します。出力ページサイズはドキュメントの最初のページサイズに合わせて調整されます。 |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings/#printdocumentwithsettings)(PageSettings, PrinterSettings) | 設定で PDF ドキュメントを印刷します。ドキュメントサイズがページサイズに一致しない場合、ページサイズに合わせて拡張されます。 |
| [PrintDocumentWithSetup](../../aspose.pdf.facades/pdfviewer/printdocumentwithsetup/)() | セットアップダイアログで PDF ドキュメントを印刷します。ダイアログを使用してプリンタを選択します。 |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf)(Stream) | 大きな PDF ストリームを開いて印刷します。PDF ファイルが数百ページ以上またはサイズが 3 MB を超える場合、このメソッドを使用するとパフォーマンスが向上します。 |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_3)(string) | 大きな PDF ファイルを開いて印刷します。PDF ファイルが数百ページ以上またはサイズが 3 MB を超える場合、このメソッドを使用するとパフォーマンスが向上します。 |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_2)(Stream, PrinterSettings) | 指定されたプリンタ設定で大きな PDF ストリームを開いて印刷します。PDF ファイルが数百ページ以上またはサイズが 3 MB を超える場合、このメソッドを使用するとパフォーマンスが向上します。 |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_5)(string, PrinterSettings) | 指定されたプリンタ設定で大きな PDF ファイルを開いて印刷します。PDF ファイルが数百ページ以上またはサイズが 3 MB を超える場合、このメソッドを使用するとパフォーマンスが向上します。 |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_1)(Stream, PageSettings, PrinterSettings) | 指定されたページ設定とプリンタ設定で大きな PDF ストリームを開いて印刷します。PDF ファイルが数百ページ以上またはサイズが 3 MB を超える場合、このメソッドを使用するとパフォーマンスが向上します。 |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_4)(string, PageSettings, PrinterSettings) | 指定されたページ設定とプリンタ設定で大きな PDF ファイルを開いて印刷します。PDF ファイルが数百ページ以上またはサイズが 3 MB を超える場合、このメソッドを使用するとパフォーマンスが向上します。 |
| [Save](../../aspose.pdf.facades/pdfviewer/save/#save)(Stream) | 結果の PDF ドキュメントをストリームに保存します。 |
| [Save](../../aspose.pdf.facades/pdfviewer/save/#save_1)(string) | 結果の PDF ドキュメントをファイルに保存します。 |

## イベント

| 名前 | 説明 |
| --- | --- |
| event [CustomPrint](../../aspose.pdf.facades/pdfviewer/customprint/) | 印刷が開始される前に発生し、デフォルトの印刷ハンドラの代わりにカスタム印刷ハンドラを提供することを許可します。 |
| event [EndPage](../../aspose.pdf.facades/pdfviewer/endpage/) | PdfViewer でページの印刷が終了したときに発生します。 |
| event [EndPrint](../../aspose.pdf.facades/pdfviewer/endprint/) | 最後のページ印刷イベントのサブスクリプションを追加/削除します。 |
| event [PdfQueryPageSettings](../../aspose.pdf.facades/pdfviewer/pdfquerypagesettings/) | 最後のページ印刷イベントのサブスクリプションを追加/削除します。 |
| event [StartPage](../../aspose.pdf.facades/pdfviewer/startpage/) | ページの印刷が開始される前に発生します。 |

### 参照

* interface [IFacade](../ifacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)