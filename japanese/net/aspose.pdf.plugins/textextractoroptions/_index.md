---
title: "クラス TextExtractorOptions"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Plugins.TextExtractorOptions クラス。TextExtractor プラグインのテキスト抽出オプションを表します"
type: docs
weight: 9540
url: /ja/net/aspose.pdf.plugins/textextractoroptions/
---
## TextExtractorOptions class

TextExtractor プラグイン用のテキスト抽出オプションを表します。

```csharp
public sealed class TextExtractorOptions : PdfExtractorOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TextExtractorOptions](textextractoroptions/#constructor)() | `TextExtractorOptions` オブジェクトの新しいインスタンスを、'Raw'（デフォルト）のテキストフォーマットモードで初期化します。 |
| [TextExtractorOptions](textextractoroptions/#constructor_1)(TextFormattingMode) | 指定されたテキストフォーマットモードで `TextExtractorOptions` オブジェクトの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [FormattingMode](../../aspose.pdf.plugins/textextractoroptions/formattingmode/) { get; } | フォーマットモードを取得します。 |
| [Inputs](../../aspose.pdf.plugins/pdfextractoroptions/inputs/) { get; } | PdfExtractor プラグインのデータコレクションを返します。 |
| override [OperationName](../../aspose.pdf.plugins/textextractoroptions/operationname/) { get; } | 操作の名前を返します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/pdfextractoroptions/addinput/)(IDataSource) | PdfExtractor プラグインのデータコレクションに新しいデータソースを追加します。 |

## その他のメンバー

| 名前 | 説明 |
| --- | --- |
| enum [TextFormattingMode](../../aspose.pdf.plugins/textextractoroptions.textformattingmode) | PDF ドキュメントをテキストに変換する際に使用できるさまざまなモードを定義します。`TextExtractorOptions` クラスを参照してください。 |

## 備考

`TextExtractorOptions` オブジェクトは、[`TextFormattingMode`](../textextractoroptions.textformattingmode/) とテキスト抽出操作のその他のオプションを設定するために使用されます。また、入力 PDF ドキュメントを表すデータ（ファイル、ストリーム）を追加する機能を継承しています。

## 例

この例は、PDF ドキュメントのテキストコンテンツを抽出する方法を示しています。

```csharp
// PDF コンテンツを抽出するために TextExtractor オブジェクトを作成します
using (TextExtractor extractor = new TextExtractor())
{
    // TextFormattingMode（Pure、または Raw - デフォルト）を設定するために TextExtractorOptions オブジェクトを作成します
    extractorOptions = new TextExtractorOptions(TextExtractorOptions.TextFormattingMode.Pure);
    
    // 入力ファイルパスをデータソースに追加します
    extractorOptions.AddInput(new FileDataSource(inputPath));
    
    // 抽出プロセスを実行する
    ResultContainer resultContainer = extractor.Process(extractorOptions);
    
    // ResultContainer オブジェクトから抽出されたテキストを取得します
    string textExtracted = resultContainer.ResultCollection[0].ToString();
}
```

### 関連項目

* class [PdfExtractorOptions](../pdfextractoroptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


