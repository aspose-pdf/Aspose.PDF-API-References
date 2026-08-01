---
title: "クラス PdfFormatConversionOptions"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.PdfFormatConversionOptions クラス。PDF ドキュメントの変換オプションのセットを表します。"
type: docs
weight: 8520
url: /ja/net/aspose.pdf/pdfformatconversionoptions/
---
## PdfFormatConversionOptions class

PDF Document を変換するためのオプションセットを表します。

```csharp
public class PdfFormatConversionOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor)(PdfFormat) | コンストラクタ |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_1)(PdfFormat, ConvertErrorAction) | コンストラクタ |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_3)(string, PdfFormat) | コンストラクタ |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_2)(Stream, PdfFormat, ConvertErrorAction) | コンストラクタ |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_4)(string, PdfFormat, ConvertErrorAction) | コンストラクタ |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_5)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | コンストラクタ |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [Default](../../aspose.pdf/pdfformatconversionoptions/default/) { get; } | デフォルト パラメータで PdfFormatConversionOptions オブジェクトを取得します。 |
| [AlignText](../../aspose.pdf/pdfformatconversionoptions/aligntext/) { get; set; } | このフラグは変換されたドキュメントのテキスト配置を制御します。デフォルトでは、ドキュメント変換はテキスト配置に影響せず、テキストはそのまま残ります。しかし、フォント置換によりテキストが重なったり、変換ドキュメントに余分なスペースが生じる場合があります。このフラグを設定すると、特別な配置操作が実行されます。このフラグは、テキストの重なりや余分なスペースの問題があるドキュメントにのみ設定すべきです。このフラグを使用するとパフォーマンスが低下し、場合によってはテキスト内容が破損する可能性があります。 |
| [AutoTaggingSettings](../../aspose.pdf/pdfformatconversionoptions/autotaggingsettings/) { get; set; } | PDF 形式変換中の自動タグ付け設定を取得または設定します。 |
| [ConvertSoftMaskAction](../../aspose.pdf/pdfformatconversionoptions/convertsoftmaskaction/) { get; set; } | ソフトマスク付き画像に対するアクション。 |
| [ErrorAction](../../aspose.pdf/pdfformatconversionoptions/erroraction/) { get; set; } | 変換できないオブジェクトに対するアクション |
| [ExcludeFontsStrategy](../../aspose.pdf/pdfformatconversionoptions/excludefontsstrategy/) { get; set; } | 不要なフォントを除外し、ドキュメントのファイルサイズを削減するための戦略です。このパラメータはフラグ [`OptimizeFileSize`](./optimizefilesize/) が true に設定されている場合にのみ意味があります。デフォルトでは SubsetFonts と RemoveDuplicatedFonts の組み合わせが使用されます。 |
| [FontEmbeddingOptions](../../aspose.pdf/pdfformatconversionoptions/fontembeddingoptions/) { get; } | 一部のフォントを PDF ドキュメントに埋め込めない場合のオプション。 |
| [Format](../../aspose.pdf/pdfformatconversionoptions/format/) { get; set; } | PDF 形式。 |
| [IccProfileFileName](../../aspose.pdf/pdfformatconversionoptions/iccprofilefilename/) { get; set; } | icc プロファイル名のファイル名を取得または設定します。null の場合はデフォルトの icc プロファイルが使用されます。 |
| [IsAsyncImageStreamsConversionMode](../../aspose.pdf/pdfformatconversionoptions/isasyncimagestreamsconversionmode/) { get; set; } | 非同期モードで画像ストリームの実行を取得/設定します。 |
| [IsLowMemoryMode](../../aspose.pdf/pdfformatconversionoptions/islowmemorymode/) { get; set; } | 低メモリ変換モードが有効かどうか |
| [IsTransferInfo](../../aspose.pdf/pdfformatconversionoptions/istransferinfo/) { get; set; } | PDF 2.0 に変換する際に Info から Metadata へデータを渡すかどうかを取得または設定します。デフォルトは true です。 |
| [LogFileName](../../aspose.pdf/pdfformatconversionoptions/logfilename/) { get; set; } | コメントが保存されるファイルへのパス。 |
| [LogStream](../../aspose.pdf/pdfformatconversionoptions/logstream/) { get; set; } | コメントが保存されるストリーム。 |
| [NonSpecificationCases](../../aspose.pdf/pdfformatconversionoptions/nonspecificationcases/) { get; } | ソースドキュメントが PDF/A 仕様に準拠していない場合の PDF/A 変換プロセスを制御するフラグを保持します。 |
| [NotAccessibleFonts](../../aspose.pdf/pdfformatconversionoptions/notaccessiblefonts/) { get; } | このプロパティは出力プロパティです。最後の PDF/A 変換時にコンピュータ上で見つからなかったすべてのフォント（フォント名）を保持します。 |
| [OptimizeFileSize](../../aspose.pdf/pdfformatconversionoptions/optimizefilesize/) { get; set; } | ファイルサイズが削減された PDF/A ドキュメントを取得するための特殊変換モードを有効化/無効化するフラグを取得または設定します。このフラグは現在、PDF ドキュメントで使用されるフォントの最適化に影響します。将来的には、グラフィックなどの他のデータ構造の最適化をオンにするためにも使用される可能性があります。このフラグとモードの組み合わせにより、ファイルサイズは大幅に削減できますが、同時に変換パフォーマンスが大幅に低下する可能性があります。 |
| [OutputIntent](../../aspose.pdf/pdfformatconversionoptions/outputintent/) { get; set; } | PDF 形式変換のための [`OutputIntent`](../outputintent/) を取得または設定します。 |
| [PuaTextProcessingStrategy](../../aspose.pdf/pdfformatconversionoptions/puatextprocessingstrategy/) { get; set; } | Unicode Private Use Area (PUA) のシンボルを処理する戦略。 |
| [SymbolicFontEncodingStrategy](../../aspose.pdf/pdfformatconversionoptions/symbolicfontencodingstrategy/) { get; set; } | シンボリック TrueType フォントに複数のエンコーディングサブテーブルがある場合に、シンボリックフォントのエンコーディングデータをコピーする戦略。 |
| [TransparencyAction](../../aspose.pdf/pdfformatconversionoptions/transparencyaction/) { get; set; } | 画像マスクオブジェクトに対するアクション。 |
| [UnicodeProcessingRules](../../aspose.pdf/pdfformatconversionoptions/unicodeprocessingrules/) { get; set; } | Unicode マッピングの問題を解決するためのルール。null にすることも可能です。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| [AlignStrategy](../../aspose.pdf/pdfformatconversionoptions/alignstrategy/) | テキストを整列させる戦略。このパラメータはフラグ [`AlignText`](./aligntext/) が true に設定されている場合にのみ意味があります。 |

### 関連項目

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


