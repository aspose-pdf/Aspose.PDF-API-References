---
title: "クラス PsLoadOptions"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.PsLoadOptions クラス。.mht ファイルを PDF ドキュメントに読み込み/インポートするためのオプションを表します。"
type: docs
weight: 9880
url: /ja/net/aspose.pdf/psloadoptions/
---
## PsLoadOptions class

.mht ファイルを pdf document にロード/インポートするオプションを表します。

```csharp
public sealed class PsLoadOptions : LoadOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PsLoadOptions](psloadoptions/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ConvertFontsToTTF](../../aspose.pdf/psloadoptions/convertfontstottf/) { get; set; } | 非 TrueType フォントを TTF に保存するかどうかを指定します。これにより、PS から PDF への変換時に生成されるドキュメントの容量が大幅に減少し、非 TrueType フォントで大量のテキストを含む PS ファイルの任意の出力形式への変換速度が向上します。ただし、PostSctipt ファイルを画像に変換する際にテキストがわずかに垂直方向にずれることがあります。 |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | ファイルをロードする際に、すべてのフォントに対するライセンス制限を無効にするフラグを取得または設定します。`true` の場合、このフォントのライセンスで禁止されている操作（例として、ライセンス規則で埋め込みが禁止されているフォントでも PDF Document に埋め込むこと）が実行可能になります。デフォルトは `false` です。 |
| [FontsFolders](../../aspose.pdf/psloadoptions/fontsfolders/) { get; set; } | フォントフォルダーのパスを取得または設定します。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/) が記述するファイル形式を表します。 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 生成された警告を処理するコールバックです。WarningHandler は ReturnAction 列挙型の項目を返し、Continue または Abort を指定します。Continue はデフォルトの動作で、Load 操作は継続しますが、ユーザーは Abort を返すこともでき、その場合 Load 操作は中止されます。 |

### 関連項目

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


