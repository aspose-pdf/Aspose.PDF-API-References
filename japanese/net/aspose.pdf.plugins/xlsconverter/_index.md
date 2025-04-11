---
title: Class XlsConverter
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.XlsConverter クラス。XlsConverter プラグインを表します
type: docs
weight: 9450
url: /ja/net/aspose.pdf.plugins/xlsconverter/
---
## XlsConverter クラス

`XlsConverter` プラグインを表します。

```csharp
public sealed class XlsConverter : IDisposable, IPlugin
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [XlsConverter](xlsconverter/)() | デフォルトコンストラクター。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/xlsconverter/dispose/)() | IDisposable の実装。 |
| [Process](../../aspose.pdf.plugins/xlsconverter/process/)(IPluginOptions) | 指定されたパラメーターで PdfToExcel 処理を開始します。 |

## 例

この例は、PDF を XLSX ドキュメントに変換する方法を示しています。

```csharp
// create XlsConverter converter
var converter = new XlsConverter();
// create PdfToXLSOptions 
var opt = new PdfToXLSOptions();
// add input file path
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
converter.Process(opt);
```

### 参照

* インターフェース [IPlugin](../iplugin/)
* 名前空間 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* アセンブリ [Aspose.PDF](../../)