---
title: "クラス TocGenerator"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Plugins.TocGenerator クラス。Aspose.PDF TocGenerator プラグインを表します。"
type: docs
weight: 9580
url: /ja/net/aspose.pdf.plugins/tocgenerator/
---
## TocGenerator class

Aspose.PDF TocGenerator プラグインを表します。

```csharp
public sealed class TocGenerator : IDisposable, IPlugin
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TocGenerator](tocgenerator/)() | デフォルトコンストラクタです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/tocgenerator/dispose/)() | IDisposable の実装です。実際には TocGenerator には必要ありません。 |
| [Process](../../aspose.pdf.plugins/tocgenerator/process/)(IPluginOptions) | 指定されたパラメータで PdfGenerator の処理を開始します。 |

## 例

この例では PDF ファイルに TOC を追加する方法を示します。

```csharp
// TocGenerator を作成する
var generator = new TocGenerator();
// 指示を設定するために TocOptions オブジェクトを作成する
var opt = new TocOptions();
// 入力ファイル パスを追加する
opt.AddInput(new FileDataSource(inputPath1));
opt.AddInput(new FileDataSource(inputPath2));
// 出力ファイル パスを設定する
opt.AddOutput(new FileDataSource(outputPath));
// 抽出プロセスを実行する
generator.Process(opt);
```

### 関連項目

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


