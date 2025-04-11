---
title: Class Optimizer
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.Optimizer クラス。オプティマイザ プラグインを表します
type: docs
weight: 8970
url: /ja/net/aspose.pdf.plugins/optimizer/
---
## オプティマイザ クラス

`Optimizer` プラグインを表します。

```csharp
public sealed class Optimizer : IPlugin
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Optimizer](optimizer/)() | デフォルトのコンストラクタ。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Process](../../aspose.pdf.plugins/optimizer/process/)(IPluginOptions) | 指定されたパラメータで `Optimizer` 処理を開始します。 |

## 例

この例は、PDF ドキュメントを最適化する方法を示しています。

```csharp
// create Optimizer
var optimizer = new Optimizer();
// create OptimizeOptions object to set instructions
var opt = new OptimizeOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
optimizer.Process(opt);
```

### 関連項目

* インターフェース [IPlugin](../iplugin/)
* 名前空間 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* アセンブリ [Aspose.PDF](../../)