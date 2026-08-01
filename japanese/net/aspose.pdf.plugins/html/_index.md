---
title: "クラス Html"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Plugins.Html クラス。Html プラグインを表します。"
type: docs
weight: 8950
url: /ja/net/aspose.pdf.plugins/html/
---
## Html class

`Html` プラグインを表します。

```csharp
public sealed class Html : IDisposable, IPlugin
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Html](html/)() | デフォルトコンストラクタです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/html/dispose/)() | IDisposable の実装です。 |
| [Process](../../aspose.pdf.plugins/html/process/)(IPluginOptions) | 指定されたパラメータで `Html` 処理を開始します。 |

## 例

この例は PDF を HTML document に変換する方法を示しています。

```csharp
// Html を作成する
var converter = new Html();
// 埋め込みリソース付きのファイルとして出力データタイプを設定するために PdfToHtmlOptions オブジェクトを作成します。
var opt = new PdfToHtmlOptions(PdfToHtmlOptions.SaveDataType.FileWithEmbeddedResources);
// 入力ファイルパスを追加します
opt.AddInput(new FileDataSource(inputPath));
// 出力ファイル パスを設定する
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

この例は HTML を PDF document に変換する方法を示しています。

```csharp
// Html を作成する
var converter = new Html();
// HtmlToPdfOptions を作成する
var opt = new HtmlToPdfOptions();
// 入力ファイルパスを追加します
opt.AddInput(new FileDataSource(inputPath));
// 出力ファイル パスを設定する
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

### 関連項目

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


