---
title: Class OfdLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.OfdLoadOptions クラス。OFD 形式の読み込みオプション
type: docs
weight: 7060
url: /ja/net/aspose.pdf/ofdloadoptions/
---
## OfdLoadOptions クラス

OFD 形式の読み込みオプション。

```csharp
public class OfdLoadOptions : LoadOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [OfdLoadOptions](ofdloadoptions/)() | デフォルトコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | ファイルを読み込む際にすべてのフォントに対するライセンス制限を無効にするフラグを取得または設定します。`true` の場合、このフォントのライセンスによって禁止されているフォントでの操作を実行できるようになります。たとえば、このフォントの埋め込みがライセンスルールによって無効にされている場合でも、PDF ドキュメントにフォントを埋め込むことができます。デフォルトは `false` です。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/) が説明するファイル形式を表します。 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 生成された警告を処理するためのコールバック。WarningHandler は、Continue または Abort のいずれかを指定する ReturnAction 列挙項目を返します。Continue はデフォルトのアクションで、読み込み操作は続行されますが、ユーザーが Abort を返すこともでき、その場合は読み込み操作を中止する必要があります。 |

### 関連項目

* クラス [LoadOptions](../loadoptions/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)