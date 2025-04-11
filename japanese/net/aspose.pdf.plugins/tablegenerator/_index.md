---
title: Class TableGenerator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.TableGenerator クラス。Aspose.PDF TableGenerator プラグインを表します
type: docs
weight: 9350
url: /ja/net/aspose.pdf.plugins/tablegenerator/
---
## TableGenerator クラス

Aspose.PDF TableGenerator プラグインを表します。

```csharp
public sealed class TableGenerator : IDisposable, IPlugin
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TableGenerator](tablegenerator/)() | デフォルトコンストラクタ。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/tablegenerator/dispose/)() | IDisposable の実装。実際には、TableGenerator には必要ありません。 |
| [Process](../../aspose.pdf.plugins/tablegenerator/process/)(IPluginOptions) | 指定されたパラメータで PdfGenerator 処理を開始します。 |

## 例

この例は、PDF ファイルにテーブルを追加する方法を示しています。

```csharp
// create TableGenerator
var generator = new TableGenerator();
// create TableOptions object to set instructions
var opt = new TableOptions();
// add input file paths
opt.AddInput(new FileDataSource(inputPath1));
opt.AddInput(new FileDataSource(inputPath2));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform extraction process
generator.Process(opt);
```

### 参照

* インターフェース [IPlugin](../iplugin/)
* 名前空間 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* アセンブリ [Aspose.PDF](../../)