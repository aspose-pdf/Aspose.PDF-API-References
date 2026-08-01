---
title: "クラス Optimizer"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Plugins.Optimizer クラス。Optimizer プラグインを表します。"
type: docs
weight: 9120
url: /ja/net/aspose.pdf.plugins/optimizer/
---
## Optimizer class

`Optimizer` プラグインを表します。

```csharp
public sealed class Optimizer : IPlugin
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Optimizer](optimizer/)() | デフォルトコンストラクタです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Process](../../aspose.pdf.plugins/optimizer/process/)(IPluginOptions) | 指定されたパラメータで `Optimizer` の処理を開始します。 |

## 例

この例は PDF ドキュメントを最適化する方法を示しています。

```csharp
// Optimizer を作成する
var optimizer = new Optimizer();
// 指示を設定するために OptimizeOptions オブジェクトを作成する
var opt = new OptimizeOptions();
// 入力ファイル パスを追加する
opt.AddInput(new FileDataSource(inputPath));
// 出力ファイル パスを設定する
opt.AddOutput(new FileDataSource(outputPath));
// プロセスを実行する
optimizer.Process(opt);
```

### 関連項目

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


