---
title: Class PdfAConvertOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.PdfAConvertOptions クラス。PdfAConverter プラグインを使用して PDF ドキュメントを PDF/A 形式に変換するためのオプションを表します。
type: docs
weight: 8990
url: /ja/net/aspose.pdf.plugins/pdfaconvertoptions/
---
## PdfAConvertOptions クラス

[`PdfAConverter`](../pdfaconverter/) プラグインを使用して PDF ドキュメントを PDF/A 形式に変換するためのオプションを表します。

```csharp
public sealed class PdfAConvertOptions : PdfAOptionsBase
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfAConvertOptions](pdfaconvertoptions/)() | デフォルトのコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AlignText](../../aspose.pdf.plugins/pdfaoptionsbase/aligntext/) { get; set; } | PDF/A 変換プロセス中にテキストの整列を維持するために追加の手段が必要かどうかを示す値を取得または設定します。 |
| [ErrorAction](../../aspose.pdf.plugins/pdfaoptionsbase/erroraction/) { get; set; } | 変換できないオブジェクトに対して取るべきアクションを取得または設定します。 |
| [ExcludeFontsStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/excludefontsstrategy/) { get; set; } | PDF/A 変換プロセス中に出力ファイルサイズを最小限に抑えるためにフォントを削除する戦略を取得または設定します。 |
| [FontEmbeddingOptions](../../aspose.pdf.plugins/pdfaoptionsbase/fontembeddingoptions/) { get; } | ドキュメントに埋め込むことができないフォントを処理するためのオプションを取得します。 |
| [IccProfileFileName](../../aspose.pdf.plugins/pdfaoptionsbase/iccprofilefilename/) { get; set; } | デフォルトの ICC (International Color Consortium) プロファイルの代わりに PDF/A 変換に使用する ICC プロファイルのファイル名を取得または設定します。 |
| [Inputs](../../aspose.pdf.plugins/pdfaoptionsbase/inputs/) { get; } | データソースのコレクションを取得します。 |
| [IsLowMemoryMode](../../aspose.pdf.plugins/pdfaoptionsbase/islowmemorymode/) { get; set; } | PDF/A 変換プロセス中に低メモリモードが有効かどうかを示す値を取得または設定します。 |
| [LogOutputSource](../../aspose.pdf.plugins/pdfaoptionsbase/logoutputsource/) { get; set; } | ログ出力のデータソースを取得または設定します。 |
| [NonSpecificationFlags](../../aspose.pdf.plugins/pdfaoptionsbase/nonspecificationflags/) { get; } | ソース PDF ドキュメントが PDF 仕様に対応していない場合の PDF/A 変換を制御するフラグを取得します。 |
| [OptimizeFileSize](../../aspose.pdf.plugins/pdfaoptionsbase/optimizefilesize/) { get; set; } | PDF/A 変換プロセス中にファイルサイズを削減しようとするかどうかを示す値を取得または設定します。 |
| [Outputs](../../aspose.pdf.plugins/pdfaconvertoptions/outputs/) { get; } | 保存操作結果のために追加されたターゲット (ファイルまたはストリームデータソース) のコレクションを取得します。 |
| [PdfAVersion](../../aspose.pdf.plugins/pdfaoptionsbase/pdfaversion/) { get; set; } | 検証または変換に使用する PDF/A 標準のバージョンを取得または設定します。 |
| [PuaSymbolsProcessingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/puasymbolsprocessingstrategy/) { get; set; } | PDF ドキュメント内のプライベートユースエリア (PUA) シンボルを処理するための戦略を取得または設定します。 |
| [SoftMaskAction](../../aspose.pdf.plugins/pdfaoptionsbase/softmaskaction/) { get; set; } | ソフトマスクを持つ画像の変換中に取るべきアクションを取得または設定します。 |
| [SymbolicFontEncodingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/symbolicfontencodingstrategy/) { get; set; } | PDF/A 形式に変換する際にシンボリックフォントをエンコードするための戦略を取得または設定します。 |
| [UnicodeProcessingRules](../../aspose.pdf.plugins/pdfaoptionsbase/unicodeprocessingrules/) { get; set; } | PDF/A 変換プロセス中に Unicode シンボルにリンクされていない ToUnicode CMap テーブルを処理するためのルールを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfaoptionsbase/addinput/)(IDataSource) | コレクションに新しいデータソースを追加します。 |
| [AddOutput](../../aspose.pdf.plugins/pdfaconvertoptions/addoutput/)(IDataSource) | 新しい結果保存ターゲットを追加します。 |

### 参照

* クラス [PdfAOptionsBase](../pdfaoptionsbase/)
* 名前空間 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* アセンブリ [Aspose.PDF](../../)