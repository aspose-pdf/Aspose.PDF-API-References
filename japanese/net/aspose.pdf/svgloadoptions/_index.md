---
title: Class SvgLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.SvgLoadOptions クラス。PDF ドキュメントに SVG ファイルを読み込む/インポートするためのオプションを表します。
type: docs
weight: 10210
url: /ja/net/aspose.pdf/svgloadoptions/
---
## SvgLoadOptions クラス

PDF ドキュメントに SVG ファイルを読み込む/インポートするためのオプションを表します。

```csharp
public sealed class SvgLoadOptions : LoadOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [SvgLoadOptions](svgloadoptions/)() | デフォルトのコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AdjustPageSize](../../aspose.pdf/svgloadoptions/adjustpagesize/) { get; set; } | PDF ページサイズを SVG サイズに調整します。 |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | ファイルを読み込む際にすべてのフォントに対するライセンス制限を無効にするフラグを取得または設定します。`true` の場合、このフォントのライセンスによって禁止されているフォントでの操作を実行できるようにします。たとえば、このフォントの埋め込みがライセンスルールによって無効にされている場合でも、PDF ドキュメントにフォントを埋め込むことを許可します。デフォルトは `false` です。 |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | [`LoadOptions`](../loadoptions/) が説明するファイル形式を表します。 |
| [PageInfo](../../aspose.pdf/svgloadoptions/pageinfo/) { get; set; } | ドキュメントの読み込み中に適用されるページ情報を取得または設定します。 |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | 生成された警告を処理するためのコールバック。WarningHandler は、Continue または Abort のいずれかを指定する ReturnAction 列挙型のアイテムを返します。Continue はデフォルトのアクションで、Load 操作は続行されますが、ユーザーが Abort を返すこともでき、その場合 Load 操作は中止されるべきです。 |

## フィールド

| 名前 | 説明 |
| --- | --- |
| [ConversionEngine](../../aspose.pdf/svgloadoptions/conversionengine/) | 変換中に使用される変換エンジンを選択できます。現在、新しいエンジンは B テスト段階にあるため、この値はデフォルトで ConversionEngines.LegacyEngine に設定されています。 |

### 関連項目

* クラス [LoadOptions](../loadoptions/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)