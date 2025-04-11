---
title: Class Merger
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.Mergerクラス。マージャプラグインを表します
type: docs
weight: 8940
url: /ja/net/aspose.pdf.plugins/merger/
---
## マージャクラス

`Merger`プラグインを表します。

```csharp
public sealed class Merger : IPlugin
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Merger](merger/)() | デフォルトコンストラクタ。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Process](../../aspose.pdf.plugins/merger/process/)(IPluginOptions) | 指定されたパラメータで`Merger`処理を開始します。 |

## 例

この例は、2つのPDFドキュメントをマージする方法を示しています。

```csharp
// create Merger
var merger = new Merger();
// create MergeOptions object to set instructions
var opt = new MergeOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath1));
opt.AddInput(new FileDataSource(inputPath2));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
merger.Process(opt);
```

### 参照

* インターフェース [IPlugin](../iplugin/)
* 名前空間 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* アセンブリ [Aspose.PDF](../../)