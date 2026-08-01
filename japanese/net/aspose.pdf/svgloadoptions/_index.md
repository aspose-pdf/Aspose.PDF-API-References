---
title: "クラス SvgLoadOptions"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.SvgLoadOptions クラス。SVG ファイルを PDF ドキュメントにロード/インポートするためのオプションを表します。"
type: docs
weight: 10390
url: /ja/net/aspose.pdf/svgloadoptions/
---
## SvgLoadOptions class

SVG ファイルを PDF ドキュメントにロード/インポートするオプションを表します。

```csharp
public sealed class SvgLoadOptions : LoadOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SvgLoadOptions](svgloadoptions/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AdjustPageSize](../../aspose.pdf/svgloadoptions/adjustpagesize/) { get; set; } | PDF ページサイズを SVG サイズに合わせて調整します。 |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | ファイルをロードする際に、すべてのフォントに対するライセンス制限を無効にするフラグを取得または設定します。`true` の場合、このフォントのライセンスで禁止されている操作（例として、ライセンス規則で埋め込みが禁止されているフォントでも PDF Document に埋め込むこと）が実行可能になります。デフォルトは `false` です。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/) が記述するファイル形式を表します。 |
| [PageInfo](../../aspose.pdf/svgloadoptions/pageinfo/) { get; set; } | ドキュメントのロード中に適用されるページ情報を取得または設定します。 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 生成された警告を処理するコールバックです。WarningHandler は ReturnAction 列挙型の項目を返し、Continue または Abort を指定します。Continue はデフォルトの動作で、Load 操作は継続しますが、ユーザーは Abort を返すこともでき、その場合 Load 操作は中止されます。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| [ConversionEngine](../../aspose.pdf/svgloadoptions/conversionengine/) | 変換時に使用される変換エンジンを選択できるようにします。現在、新しいエンジンはベータテスト段階にあるため、この値はデフォルトで ConversionEngines.LegacyEngine に設定されています。 |

### 関連項目

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


