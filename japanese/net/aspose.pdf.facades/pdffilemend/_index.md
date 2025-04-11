---
title: Class PdfFileMend
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileMend クラス。既存の PDF ドキュメントのページにテキストや画像を追加するためのクラスを表します。
type: docs
weight: 4530
url: /ja/net/aspose.pdf.facades/pdffilemend/
---
## PdfFileMend クラス

既存の PDF ドキュメントのページにテキストや画像を追加するためのクラスを表します。

```csharp
public sealed class PdfFileMend : SaveableFacade
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfFileMend](pdffilemend/#constructor)() | コンストラクタ。 |
| [PdfFileMend](pdffilemend/#constructor_1)(Document) | *document* に基づいて新しい `PdfFileMend` オブジェクトを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | 作業中のドキュメントファサードを取得します。 |
| [IsWordWrap](../../aspose.pdf.facades/pdffilemend/iswordwrap/) { set; } | AddText メソッドでのワードラップを示す bool 値を設定します。値が true の場合、FormattedText のテキストはワードラップされます。デフォルトでは、値は false です。 |
| [TextPositioningMode](../../aspose.pdf.facades/pdffilemend/textpositioningmode/) { get; set; } | テキストの配置戦略を設定または取得します。[`PositioningMode`](../positioningmode/) デフォルトモードはレガシーです。 |
| [WrapMode](../../aspose.pdf.facades/pdffilemend/wrapmode/) { get; set; } | ワードラッピングアルゴリズムを設定または取得します。WordWrapMode と IsWordWrap を参照してください。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage)(Stream, int, float, float, float, float) | 指定された座標で PDF ドキュメントの指定されたページに画像を追加します。 |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_2)(Stream, int[], float, float, float, float) | 指定された座標で PDF ドキュメントの指定されたページに画像を追加します。 |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_4)(string, int, float, float, float, float) | 指定された座標で PDF ドキュメントの指定されたページに画像を追加します。 |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_6)(string, int[], float, float, float, float) | 指定された座標で PDF ドキュメントの指定されたページに画像を追加します。 |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_1)(Stream, int, float, float, float, float, CompositingParameters) | 指定された座標で PDF ドキュメントの指定されたページに画像を追加します。 |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_3)(Stream, int[], float, float, float, float, CompositingParameters) | 指定された座標で PDF ドキュメントの指定されたページに画像を追加します。 |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_5)(string, int, float, float, float, float, CompositingParameters) | 指定された座標で PDF ドキュメントの指定されたページに画像を追加します。 |
| [AddImage](../../aspose.pdf.facades/pdffilemend/addimage/#addimage_7)(string, int[], float, float, float, float, CompositingParameters) | 指定された座標で PDF ドキュメントの指定されたページに画像を追加します。 |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext)(FormattedText, int, float, float) | 実装されていません。 |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext_1)(FormattedText, int, float, float, float, float) | 実装されていません。 |
| [AddText](../../aspose.pdf.facades/pdffilemend/addtext/#addtext_2)(FormattedText, int[], float, float, float, float) | 実装されていません。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | ファサードを初期化します。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | ファサードを初期化します。 |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | ファサードを初期化します。 |
| override [Close](../../aspose.pdf.facades/pdffilemend/close/)() | PdfFileMend オブジェクトを閉じます。 |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | ファサードを破棄します。 |
| override [Save](../../aspose.pdf.facades/pdffilemend/save/#save)(Stream) | PDF ドキュメントを指定されたストリームに保存します。 |
| override [Save](../../aspose.pdf.facades/pdffilemend/save/#save_1)(string) | PDF ドキュメントを指定されたファイルに保存します。 |

### 参照

* クラス [SaveableFacade](../saveablefacade/)
* 名前空間 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../)