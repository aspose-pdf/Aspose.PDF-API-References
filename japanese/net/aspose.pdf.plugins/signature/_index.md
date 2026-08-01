---
title: "クラス Signature"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Plugins.Signature クラス。Signature プラグインを表します。"
type: docs
weight: 9410
url: /ja/net/aspose.pdf.plugins/signature/
---
## Signature class

`Signature` プラグインを表します。

```csharp
public sealed class Signature : IPlugin
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Signature](signature/)() | デフォルトコンストラクタです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Process](../../aspose.pdf.plugins/signature/process/)(IPluginOptions) | 指定されたパラメーターで `Signature` の処理を開始します。 |

## 例

この例は PDF ドキュメントに署名する方法を示しています。

```csharp
// Signature を作成する
var plugin = new Signature();
// 指示を設定するために SignOptions オブジェクトを作成する
var opt = new SignOptions(inputPfx, inputPfxPassword);
// 入力ファイルパスを追加します
opt.AddInput(new FileDataSource(inputPath));
// 出力ファイル パスを設定する
opt.AddOutput(new FileDataSource(outputPath));
// プロセスを実行する
plugin.Process(opt);
```

### 関連項目

* interface [IPlugin](../iplugin/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)


