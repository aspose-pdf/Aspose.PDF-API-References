---
title: "クラス PdfAOptionsBase"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Plugins.PdfAOptionsBase クラス。PdfAConverter プラグインオプションの基底クラスを表します。このクラスは PDF/A 変換および検証プロセスを構成するためのプロパティとメソッドを提供します。"
type: docs
weight: 9160
url: /ja/net/aspose.pdf.plugins/pdfaoptionsbase/
---
## PdfAOptionsBase class

`[`PdfAConverter`](../pdfaconverter/)` プラグインオプションの基底クラスを表します。このクラスは PDF/A 変換および検証プロセスを構成するためのプロパティとメソッドを提供します。

```csharp
public abstract class PdfAOptionsBase : IPluginOptions
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AlignText](../../aspose.pdf.plugins/pdfaoptionsbase/aligntext/) { get; set; } | PDF/A 変換プロセス中にテキストの配置を保持するために追加の手段が必要かどうかを示す値を取得または設定します。 |
| [ErrorAction](../../aspose.pdf.plugins/pdfaoptionsbase/erroraction/) { get; set; } | 変換できないオブジェクトに対して実行するアクションを取得または設定します。 |
| [ExcludeFontsStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/excludefontsstrategy/) { get; set; } | PDF/A 変換プロセス中に出力ファイルサイズを最小化するためのフォント削除戦略を取得または設定します。 |
| [FontEmbeddingOptions](../../aspose.pdf.plugins/pdfaoptionsbase/fontembeddingoptions/) { get; } | 文書に埋め込めないフォントを処理するためのオプションを取得します。 |
| [IccProfileFileName](../../aspose.pdf.plugins/pdfaoptionsbase/iccprofilefilename/) { get; set; } | デフォルトの代わりに PDF/A 変換で使用する ICC (International Color Consortium) プロファイルのファイル名を取得または設定します。 |
| [Inputs](../../aspose.pdf.plugins/pdfaoptionsbase/inputs/) { get; } | データ ソースのコレクションを取得します。 |
| [IsLowMemoryMode](../../aspose.pdf.plugins/pdfaoptionsbase/islowmemorymode/) { get; set; } | PDF/A 変換プロセス中に低メモリ モードが有効かどうかを示す値を取得または設定します。 |
| [LogOutputSource](../../aspose.pdf.plugins/pdfaoptionsbase/logoutputsource/) { get; set; } | ログ出力用のデータ ソースを取得または設定します。 |
| [NonSpecificationFlags](../../aspose.pdf.plugins/pdfaoptionsbase/nonspecificationflags/) { get; } | ソース PDF 文書が PDF 仕様に準拠していない場合の PDF/A 変換を制御するフラグを取得します。 |
| [OptimizeFileSize](../../aspose.pdf.plugins/pdfaoptionsbase/optimizefilesize/) { get; set; } | PDF/A 変換プロセス中にファイルサイズを削減しようとするかどうかを示す値を取得または設定します。 |
| [PdfAVersion](../../aspose.pdf.plugins/pdfaoptionsbase/pdfaversion/) { get; set; } | 検証または変換に使用する PDF/A 標準のバージョンを取得または設定します。 |
| [PuaSymbolsProcessingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/puasymbolsprocessingstrategy/) { get; set; } | PDF 文書内の Private Use Area (PUA) シンボルを処理する戦略を取得または設定します。 |
| [SoftMaskAction](../../aspose.pdf.plugins/pdfaoptionsbase/softmaskaction/) { get; set; } | ソフトマスク付き画像の変換中に実行するアクションを取得または設定します。 |
| [SymbolicFontEncodingStrategy](../../aspose.pdf.plugins/pdfaoptionsbase/symbolicfontencodingstrategy/) { get; set; } | PDF/A 形式に変換する際のシンボリック フォントのエンコード戦略を取得または設定します。 |
| [UnicodeProcessingRules](../../aspose.pdf.plugins/pdfaoptionsbase/unicodeprocessingrules/) { get; set; } | PDF/A 変換プロセス中に ToUnicode CMap テーブルを処理し、Unicode シンボルにリンクしないためのルールを取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfaoptionsbase/addinput/)(IDataSource) | コレクションに新しいデータ ソースを追加します。 |

### 関連項目

* interface [IPluginOptions](../ipluginoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


