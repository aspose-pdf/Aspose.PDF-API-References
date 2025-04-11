---
title: Class Stamp
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.Stamp クラス。スタンプを表すクラス
type: docs
weight: 4720
url: /ja/net/aspose.pdf.facades/stamp/
---
## スタンプ クラス

スタンプを表すクラス。

```csharp
public sealed class Stamp
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Stamp](stamp/)() | デフォルトのコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BlendingSpace](../../aspose.pdf.facades/stamp/blendingspace/) { get; set; } | ページ上で透明度とブレンド操作を実行するために使用されるカラースペースを定義する BlendingColorSpace 値を取得または設定します。 |
| [IsBackground](../../aspose.pdf.facades/stamp/isbackground/) { get; set; } | 背景ステータスを取得または設定します。true の場合、スタンプはスタンプされたページの背景として配置されます。デフォルトは false に設定されています。 |
| [Opacity](../../aspose.pdf.facades/stamp/opacity/) { get; set; } | スタンプの不透明度を取得または設定します。 |
| [PageNumber](../../aspose.pdf.facades/stamp/pagenumber/) { get; set; } | ページ番号を取得または設定します。 |
| [Pages](../../aspose.pdf.facades/stamp/pages/) { get; set; } | スタンプの影響を受けるページ番号の配列を取得または設定します。Pages が null の場合、ドキュメントのすべてのページが影響を受けます。 |
| [Quality](../../aspose.pdf.facades/stamp/quality/) { get; set; } | 画像スタンプの品質をパーセントで取得または設定します。有効な値は 0..100% です。 |
| [Rotation](../../aspose.pdf.facades/stamp/rotation/) { get; set; } | スタンプの回転を度単位で取得または設定します。 |
| [StampId](../../aspose.pdf.facades/stamp/stampid/) { get; set; } | スタンプの識別子を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/#bindimage)(Stream) | スタンプとして使用される画像を設定します。 |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/#bindimage_1)(string) | 画像をスタンプとして設定します。 |
| [BindLogo](../../aspose.pdf.facades/stamp/bindlogo/)(FormattedText) | テキストをスタンプとして設定します。 |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/#bindpdf)(Stream, int) | スタンプとして使用される PDF ファイルとページ番号を設定します。 |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/#bindpdf_1)(string, int) | スタンプとして使用される PDF ファイルとページ番号を設定します。 |
| [BindTextState](../../aspose.pdf.facades/stamp/bindtextstate/)(TextState) | スタンプテキストのテキスト状態を設定します。 |
| [SetImageSize](../../aspose.pdf.facades/stamp/setimagesize/)(float, float) | 画像スタンプのサイズを設定します。画像は指定された値に応じてスケーリングされます。 |
| [SetOrigin](../../aspose.pdf.facades/stamp/setorigin/)(float, float) | スタンプが配置されるページ上の位置を設定します。 |

### 参照

* 名前空間 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../)