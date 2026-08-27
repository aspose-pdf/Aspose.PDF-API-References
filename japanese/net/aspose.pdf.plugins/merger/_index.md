---
title: "クラス Merger"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Plugins.Merger クラス。Merger プラグインを表します"
type: docs
weight: 9070
url: /ja/net/aspose.pdf.plugins/merger/
---
## Merger class

`Merger` プラグインを表します。

```csharp
public sealed class Merger : IPlugin
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Merger](merger/)() | デフォルトコンストラクタです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Process](../../aspose.pdf.plugins/merger/process/)(IPluginOptions) | 指定されたパラメータで `Merger` の処理を開始します。 |

## 例

この例は、2 つの PDF ドキュメントをマージする方法を示しています。

```csharp
// Merger を作成する
var merger = new Merger();
// 指示を設定するために MergeOptions オブジェクトを作成する
var opt = new MergeOptions();
// 入力ファイル パスを追加する
opt.AddInput(new FileDataSource(inputPath1));
opt.AddInput(new FileDataSource(inputPath2));
// 出力ファイル パスを設定する
opt.AddOutput(new FileDataSource(outputPath));
// プロセスを実行する
merger.Process(opt);
```

### 関連項目

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


