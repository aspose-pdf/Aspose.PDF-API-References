---
title: Class DjvuLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.DjvuLoadOptions クラス。クラスは DJVU ロードオプションを説明します
type: docs
weight: 3740
url: /ja/net/aspose.pdf/djvuloadoptions/
---
## DjvuLoadOptions クラス

クラスは DJVU ロードオプションを説明します。

```csharp
public class DjvuLoadOptions : LoadOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [DjvuLoadOptions](djvuloadoptions/)() | デフォルトのコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | ファイルをロードする際にすべてのフォントに対するライセンス制限を無効にするフラグを取得または設定します。`true` の場合、このフォントのライセンスによって禁止されているフォントでの操作を実行できるようになります。たとえば、このフォントの埋め込みがライセンスルールによって無効になっている場合でも、PDF ドキュメントにフォントを埋め込むことができます。デフォルトは `false` です。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/) が説明するファイル形式を表します。 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 生成された警告を処理するためのコールバック。WarningHandler は、Continue または Abort のいずれかを指定する ReturnAction 列挙項目を返します。Continue はデフォルトのアクションで、ロード操作は続行されますが、ユーザーが Abort を返すこともでき、その場合はロード操作を中止する必要があります。 |

### 関連項目

* クラス [LoadOptions](../loadoptions/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)