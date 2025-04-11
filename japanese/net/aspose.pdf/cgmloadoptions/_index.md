---
title: Class CgmLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.CgmLoadOptions クラス。PDF ドキュメントに CGM ファイルを読み込む/インポートするためのオプションを含みます。
type: docs
weight: 3010
url: /ja/net/aspose.pdf/cgmloadoptions/
---
## CgmLoadOptions クラス

PDF ドキュメントに CGM ファイルを読み込む/インポートするためのオプションを含みます。

```csharp
public sealed class CgmLoadOptions : LoadOptions
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [CgmLoadOptions](cgmloadoptions/#constructor)() | CGM ファイルを PDF ドキュメントに変換するためのデフォルトの読み込みオプションを作成します。デフォルトの PDF ページサイズ - A4 300dpi 2480 X 3508。 |
| [CgmLoadOptions](cgmloadoptions/#constructor_1)(SizeF) | 定義された !:pageSize で読み込みオプションを作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | ファイルを読み込む際にすべてのフォントに対するライセンス制限を無効にするフラグを取得または設定します。`true` の場合、このフォントのライセンスによって禁止されているフォントでの操作を実行できるようになります。たとえば、このフォントの埋め込みを無効にするライセンスルールがある場合でも、PDF ドキュメントにフォントを埋め込むことができます。デフォルトは `false` です。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/) が説明するファイル形式を表します。 |
| [PageSize](../../aspose.pdf/cgmloadoptions/pagesize/) { get; } | インポートの出力ページサイズを取得または設定します。 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 生成された警告を処理するためのコールバック。WarningHandler は、Continue または Abort のいずれかを指定する ReturnAction 列挙型のアイテムを返します。Continue はデフォルトのアクションで、Load 操作は続行されますが、ユーザーが Abort を返すこともでき、その場合 Load 操作は停止する必要があります。 |

### 参照

* クラス [LoadOptions](../loadoptions/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)