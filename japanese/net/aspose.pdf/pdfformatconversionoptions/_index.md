---
title: Class PdfFormatConversionOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.PdfFormatConversionOptions クラス。PDF ドキュメントを変換するためのオプションのセットを表します
type: docs
weight: 8380
url: /ja/net/aspose.pdf/pdfformatconversionoptions/
---
## PdfFormatConversionOptions クラス

PDF ドキュメントを変換するためのオプションのセットを表します

```csharp
public class PdfFormatConversionOptions
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor)(PdfFormat) | コンストラクター |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_1)(PdfFormat, ConvertErrorAction) | コンストラクター |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_3)(string, PdfFormat) | コンストラクター |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_2)(Stream, PdfFormat, ConvertErrorAction) | コンストラクター |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_4)(string, PdfFormat, ConvertErrorAction) | コンストラクター |
| [PdfFormatConversionOptions](pdfformatconversionoptions/#constructor_5)(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | コンストラクター |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| static [Default](../../aspose.pdf/pdfformatconversionoptions/default/) { get; } | デフォルトのパラメーターを持つ PdfFormatConversionOptions オブジェクトを取得します |
| [AlignText](../../aspose.pdf/pdfformatconversionoptions/aligntext/) { get; set; } | このフラグは、変換されたドキュメントのテキストの整列を制御します。デフォルトでは、ドキュメントの変換はテキストの整列に影響を与えず、テキストをそのままにします。しかし、フォントの置き換えが原因で、変換されたドキュメントでテキストが重なったり、余分なスペースが発生する場合があります。このフラグが設定されている場合、特別な整列操作が実行されます。このフラグは、重なったテキストや余分なテキストスペースに問題があるドキュメントに対してのみ設定する必要があります。このフラグを使用すると、パフォーマンスが低下し、場合によってはテキストコンテンツが破損する可能性があります。 |
| [ConvertSoftMaskAction](../../aspose.pdf/pdfformatconversionoptions/convertsoftmaskaction/) { get; set; } | ソフトマスク付き画像のアクション。 |
| [ErrorAction](../../aspose.pdf/pdfformatconversionoptions/erroraction/) { get; set; } | 変換できないオブジェクトのアクション |
| [ExcludeFontsStrategy](../../aspose.pdf/pdfformatconversionoptions/excludefontsstrategy/) { get; set; } | 不要なフォントを除外し、ドキュメントファイルサイズを削減するための戦略。このパラメーターは、フラグ [`OptimizeFileSize`](./optimizefilesize/) が true に設定されている場合にのみ意味があります。デフォルトでは、SubsetFonts と RemoveDuplicatedFonts の戦略の組み合わせが使用されます。 |
| [FontEmbeddingOptions](../../aspose.pdf/pdfformatconversionoptions/fontembeddingoptions/) { get; } | PDF ドキュメントに一部のフォントを埋め込むことができない場合のオプション。 |
| [Format](../../aspose.pdf/pdfformatconversionoptions/format/) { get; set; } | PDF 形式。 |
| [IccProfileFileName](../../aspose.pdf/pdfformatconversionoptions/iccprofilefilename/) { get; set; } | ICC プロファイル名のファイル名を取得または設定します。null の場合、デフォルトの ICC プロファイルが使用されます。 |
| [IsAsyncImageStreamsConversionMode](../../aspose.pdf/pdfformatconversionoptions/isasyncimagestreamsconversionmode/) { get; set; } | 非同期モードでの画像ストリームの実行を取得または設定します。 |
| [IsLowMemoryMode](../../aspose.pdf/pdfformatconversionoptions/islowmemorymode/) { get; set; } | 低メモリ変換モードが有効になっているかどうか |
| [IsTransferInfo](../../aspose.pdf/pdfformatconversionoptions/istransferinfo/) { get; set; } | PDF 2.0 に変換する際に、Info から Metadata にデータを渡すかどうかを取得または設定します。デフォルトは true です。 |
| [LogFileName](../../aspose.pdf/pdfformatconversionoptions/logfilename/) { get; set; } | コメントが保存されるファイルへのパス。 |
| [LogStream](../../aspose.pdf/pdfformatconversionoptions/logstream/) { get; set; } | コメントが保存されるストリーム。 |
| [NonSpecificationCases](../../aspose.pdf/pdfformatconversionoptions/nonspecificationcases/) { get; } | ソースドキュメントが PDF/A 仕様に準拠していない場合の PDF/A 変換プロセスを制御するフラグを保持します。 |
| [NotAccessibleFonts](../../aspose.pdf/pdfformatconversionoptions/notaccessiblefonts/) { get; } | このプロパティはアウトプロパティです。最後の PDF/A 変換でコンピュータ上で見つからなかったすべてのフォント（フォント名）を保持します。 |
| [OptimizeFileSize](../../aspose.pdf/pdfformatconversionoptions/optimizefilesize/) { get; set; } | PDF/A ドキュメントのファイルサイズを削減する特別な変換モードを有効または無効にするフラグを取得または設定します。このフラグは、PDF ドキュメントで使用されるフォントの最適化に影響を与えます。将来的には、このフラグがグラフィックなどの他のデータ構造の最適化を切り替えるためにも使用される可能性があります。このフラグとモードのセットは、ファイルサイズを大幅に削減できますが、同時に変換のパフォーマンスを大幅に低下させる可能性があります。 |
| [OutputIntent](../../aspose.pdf/pdfformatconversionoptions/outputintent/) { get; set; } | PDF 形式の変換のための [`OutputIntent`](../outputintent/) を取得または設定します。 |
| [PuaTextProcessingStrategy](../../aspose.pdf/pdfformatconversionoptions/puatextprocessingstrategy/) { get; set; } | Unicode プライベートユースエリア (PUA) からのシンボルを処理するための戦略。 |
| [SymbolicFontEncodingStrategy](../../aspose.pdf/pdfformatconversionoptions/symbolicfontencodingstrategy/) { get; set; } | シンボリック TrueType フォントが 1 つ以上のエンコーディングサブテーブルを持つ場合に、シンボリックフォントのエンコーディングデータをコピーするための戦略。 |
| [TransparencyAction](../../aspose.pdf/pdfformatconversionoptions/transparencyaction/) { get; set; } | マスク付き画像オブジェクトのアクション |
| [UnicodeProcessingRules](../../aspose.pdf/pdfformatconversionoptions/unicodeprocessingrules/) { get; set; } | Unicode マッピングの問題を解決するためのルール。null である可能性があります。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| [AlignStrategy](../../aspose.pdf/pdfformatconversionoptions/alignstrategy/) | テキストを整列させるための戦略。このパラメーターは、フラグ [`AlignText`](./aligntext/) が true に設定されている場合にのみ意味があります。 |

### 参照

* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)