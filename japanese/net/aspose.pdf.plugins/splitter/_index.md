---
title: "クラス Splitter"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Plugins.Splitter クラス。Splitter プラグインを表します。"
type: docs
weight: 9430
url: /ja/net/aspose.pdf.plugins/splitter/
---
## Splitter class

`Splitter` プラグインを表します。

```csharp
public class Splitter : IPlugin
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Splitter](splitter/)() | デフォルトコンストラクタです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Process](../../aspose.pdf.plugins/splitter/process/)(IPluginOptions) | 指定されたパラメータで `Splitter` の処理を開始します。 |

## 例

この例は PDF ドキュメントの分割方法を示しています。

```csharp
// Splitter を作成する
var splitter = new Splitter();
// 指示を設定するために SplitOptions オブジェクトを作成する
var opt = new SplitOptions();
// 入力ファイル パスを追加する
opt.AddInput(new FileDataSource(inputPath));
// 出力ファイルパスを設定する
opt.AddOutput(new FileDataSource(outputPath1));
opt.AddOutput(new FileDataSource(outputPath2));
// プロセスを実行する
splitter.Process(opt);
```

### 関連項目

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


