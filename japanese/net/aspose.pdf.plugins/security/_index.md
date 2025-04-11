---
title: Class Security
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.Security クラス。セキュリティプラグインを表します
type: docs
weight: 9230
url: /ja/net/aspose.pdf.plugins/security/
---
## セキュリティクラス

`Security` プラグインを表します。

```csharp
public sealed class Security : IPlugin
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Security](security/)() | デフォルトコンストラクタ。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Process](../../aspose.pdf.plugins/security/process/)(IPluginOptions) | 指定されたパラメータで `Security` 処理を開始します。 |

## 例

この例は、PDF ドキュメントを暗号化する方法を示しています。

```csharp
// create Security 
var plugin = new Security();
// create EncryptionOptions object to set instructions
var opt = new EncryptionOptions("123456", "qwerty", DocumentPrivilege.ForbidAll));
// add input file path
opt.AddInput(new FileDataSource(inputPath));
// set output file path
opt.AddOutput(new FileDataSource(outputPath));
// perform the process
plugin.Process(opt);
```

この例は、PDF ドキュメントを復号化する方法を示しています。

```csharp
// create Security 
var plugin = new Security();
// create DecryptionOptions object to set instructions
var opt = new DecryptionOptions("123456"));
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