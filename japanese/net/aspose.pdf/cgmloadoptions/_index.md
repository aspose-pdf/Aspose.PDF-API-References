---
title: "クラス CgmLoadOptions"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.CgmLoadOptions クラス。CGM ファイルを pdf Document にロード/インポートするためのオプションを含みます。"
type: docs
weight: 3120
url: /ja/net/aspose.pdf/cgmloadoptions/
---
## CgmLoadOptions class

CGM ファイルを pdf ドキュメントに読み込み/インポートするためのオプションを含みます。

```csharp
public sealed class CgmLoadOptions : LoadOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [CgmLoadOptions](cgmloadoptions/#constructor)() | CGM ファイルを pdf Document に変換するためのデフォルトのロードオプションを作成します。デフォルトの pdf ページサイズは A4 300dpi 2480 X 3508 です。 |
| [CgmLoadOptions](cgmloadoptions/#constructor_1)(SizeF) | 定義された !:pageSize を使用してロードオプションを作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | ファイルをロードする際に、すべてのフォントに対するライセンス制限を無効にするフラグを取得または設定します。`true` の場合、このフォントのライセンスで禁止されている操作（例として、ライセンス規則で埋め込みが禁止されているフォントでも PDF Document に埋め込むこと）が実行可能になります。デフォルトは `false` です。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/) が記述するファイル形式を表します。 |
| [PageSize](../../aspose.pdf/cgmloadoptions/pagesize/) { get; } | インポート用の出力ページサイズを取得または設定します。 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 生成された警告を処理するコールバックです。WarningHandler は ReturnAction 列挙型の項目を返し、Continue または Abort を指定します。Continue はデフォルトの動作で、Load 操作は継続しますが、ユーザーは Abort を返すこともでき、その場合 Load 操作は中止されます。 |

### 関連項目

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


