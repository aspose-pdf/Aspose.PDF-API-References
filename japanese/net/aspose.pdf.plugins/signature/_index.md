---
title: Class Signature
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.Signatureクラス。Signatureプラグインを表します
type: docs
weight: 9260
url: /ja/net/aspose.pdf.plugins/signature/
---
## Signatureクラス

`Signature`プラグインを表します。

```csharp
public sealed class Signature : IPlugin
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Signature](signature/)() | デフォルトコンストラクタ。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Process](../../aspose.pdf.plugins/signature/process/)(IPluginOptions) | 指定されたパラメータで`Signature`処理を開始します。 |

## 例

この例はPDFドキュメントに署名する方法を示しています。

```csharp
// create Signature
var plugin = new Signature();
// create SignOptions object to set instructions
var opt = new SignOptions(inputPfx, inputPfxPassword);
// add input file path
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
plugin.Process(opt);
```

### 参照

* インターフェース [IPlugin](../iplugin/)
* 名前空間 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* アセンブリ [Aspose.PDF](../../)