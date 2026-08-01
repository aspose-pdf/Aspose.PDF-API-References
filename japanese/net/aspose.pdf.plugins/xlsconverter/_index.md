---
title: "クラス XlsConverter"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Plugins.XlsConverter クラス。XlsConverter プラグインを表します"
type: docs
weight: 9600
url: /ja/net/aspose.pdf.plugins/xlsconverter/
---
## XlsConverter class

`XlsConverter` プラグインを表します。

```csharp
public sealed class XlsConverter : IDisposable, IPlugin
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [XlsConverter](xlsconverter/)() | デフォルトコンストラクタです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/xlsconverter/dispose/)() | IDisposable の実装です。 |
| [Process](../../aspose.pdf.plugins/xlsconverter/process/)(IPluginOptions) | 指定されたパラメータで PdfToExcel の処理を開始します。 |

## 例

この例は PDF を XLSX ドキュメントに変換する方法を示しています。

```csharp
// XlsConverter コンバータを作成します
var converter = new XlsConverter();
// PdfToXLSOptions を作成します
var opt = new PdfToXLSOptions();
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


