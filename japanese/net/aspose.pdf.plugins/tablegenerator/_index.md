---
title: "クラス TableGenerator"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Plugins.TableGenerator クラス。Aspose.PDF TableGenerator プラグインを表します。"
type: docs
weight: 9500
url: /ja/net/aspose.pdf.plugins/tablegenerator/
---
## TableGenerator class

Aspose.PDF TableGenerator プラグインを表します。

```csharp
public sealed class TableGenerator : IDisposable, IPlugin
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TableGenerator](tablegenerator/)() | デフォルトコンストラクタです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Dispose](../../aspose.pdf.plugins/tablegenerator/dispose/)() | IDisposable の実装です。実際には TableGenerator には必要ありません。 |
| [Process](../../aspose.pdf.plugins/tablegenerator/process/)(IPluginOptions) | 指定されたパラメータで PdfGenerator の処理を開始します。 |

## 例

この例は PDF ファイルにテーブルを追加する方法を示しています。

```csharp
// TableGenerator を作成する
var generator = new TableGenerator();
// 指示を設定するために TableOptions オブジェクトを作成する
var opt = new TableOptions();
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


