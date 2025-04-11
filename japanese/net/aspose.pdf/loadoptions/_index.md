---
title: Class LoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LoadOptions クラス。LoadOptions タイプは個々のロードオプションの抽象レベルを保持します
type: docs
weight: 6120
url: /ja/net/aspose.pdf/loadoptions/
---
## LoadOptions クラス

LoadOptions タイプは個々のロードオプションの抽象レベルを保持します

```csharp
public abstract class LoadOptions
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | ファイルをロードする際にすべてのフォントに対するライセンス制限を無効にするフラグを取得または設定します。`true` の場合、このフォントのライセンスによって禁止されているフォントでの操作を実行できるようになります。たとえば、このフォントの埋め込みがライセンスルールによって無効にされている場合でも、PDF ドキュメントにフォントを埋め込むことができます。デフォルトは `false` です。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | `LoadOptions` が記述するファイル形式を表します。 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 生成された警告を処理するためのコールバックです。WarningHandler は、Continue または Abort のいずれかを指定する ReturnAction 列挙体の項目を返します。Continue はデフォルトのアクションで、ロード操作は続行されますが、ユーザーが Abort を返すこともでき、その場合はロード操作を中止する必要があります。 |

### 参照

* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)