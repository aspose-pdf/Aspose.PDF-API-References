---
title: Class Splitter
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.Splitter クラス。スプリッタープラグインを表します
type: docs
weight: 9280
url: /ja/net/aspose.pdf.plugins/splitter/
---
## スプリッター クラス

`Splitter` プラグインを表します。

```csharp
public class Splitter : IPlugin
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Splitter](splitter/)() | デフォルトのコンストラクター。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Process](../../aspose.pdf.plugins/splitter/process/)(IPluginOptions) | 指定されたパラメーターで `Splitter` 処理を開始します。 |

## 例

この例は、PDF ドキュメントを分割する方法を示しています。

```csharp
// create Splitter
var splitter = new Splitter();
// create SplitOptions object to set instructions
var opt = new SplitOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath));
// set output file paths
opt.AddOutput(new FileDataSource(outputPath1));
opt.AddOutput(new FileDataSource(outputPath2));
// perform the process
splitter.Process(opt);
```

### 参照

* インターフェース [IPlugin](../iplugin/)
* 名前空間 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* アセンブリ [Aspose.PDF](../../)