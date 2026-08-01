---
title: "クラス Security"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Plugins.Security クラス。Security プラグインを表します。"
type: docs
weight: 9380
url: /ja/net/aspose.pdf.plugins/security/
---
## Security class

`Security` プラグインを表します。

```csharp
public sealed class Security : IPlugin
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Security](security/)() | デフォルトコンストラクタです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Process](../../aspose.pdf.plugins/security/process/)(IPluginOptions) | 指定されたパラメータで `Security` の処理を開始します。 |

## 例

この例は PDF ドキュメントを暗号化する方法を示しています。

```csharp
// Security を作成
var plugin = new Security();
// 指示を設定するために EncryptionOptions オブジェクトを作成する
var opt = new EncryptionOptions("123456", "qwerty", DocumentPrivilege.ForbidAll));
// 入力ファイルパスを追加します
opt.AddInput(new FileDataSource(inputPath));
// 出力ファイル パスを設定する
opt.AddOutput(new FileDataSource(outputPath));
// プロセスを実行する
plugin.Process(opt);
```

この例は PDF ドキュメントを復号化する方法を示しています。

```csharp
// Security を作成
var plugin = new Security();
// 指示を設定するために DecryptionOptions オブジェクトを作成する
var opt = new DecryptionOptions("123456"));
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


