---
title: Class TocGenerator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.TocGenerator クラス。Aspose.PDF TocGenerator プラグインを表します
type: docs
weight: 9430
url: /ja/net/aspose.pdf.plugins/tocgenerator/
---
## TocGenerator クラス

Aspose.PDF TocGenerator プラグインを表します。

```csharp
public sealed class TocGenerator : IDisposable, IPlugin
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TocGenerator](tocgenerator/)() | デフォルトコンストラクタ。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/tocgenerator/dispose/)() | IDisposable の実装。実際には、TocGenerator には必要ありません。 |
| [Process](../../aspose.pdf.plugins/tocgenerator/process/)(IPluginOptions) | 指定されたパラメータで PdfGenerator 処理を開始します。 |

## 例

この例は、PDF ファイルに TOC を追加する方法を示しています。

```csharp
// create TocGenerator
var generator = new TocGenerator();
// create TocOptions object to set instructions
var opt = new TocOptions();
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