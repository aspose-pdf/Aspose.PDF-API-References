---
title: "クラス Stamp"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Facades.Stamp クラス。スタンプを表すクラスです。"
type: docs
weight: 4840
url: /ja/net/aspose.pdf.facades/stamp/
---
## Stamp class

スタンプを表すクラスです。

```csharp
public sealed class Stamp
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Stamp](stamp/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BlendingSpace](../../aspose.pdf.facades/stamp/blendingspace/) { get; set; } | ページ上で透過およびブレンド操作を実行するために使用されるカラースペースを定義する BlendingColorSpace 値を取得または設定します。 |
| [IsBackground](../../aspose.pdf.facades/stamp/isbackground/) { get; set; } | 背景ステータスを取得または設定します。true の場合、スタンプはページの背景として配置されます。デフォルトは false に設定されています。 |
| [Opacity](../../aspose.pdf.facades/stamp/opacity/) { get; set; } | スタンプの不透明度を取得または設定します。 |
| [PageNumber](../../aspose.pdf.facades/stamp/pagenumber/) { get; set; } | ページ番号を取得または設定します。 |
| [Pages](../../aspose.pdf.facades/stamp/pages/) { get; set; } | スタンプの影響を受けるページ番号の配列を取得または設定します。Pages が null の場合、ドキュメントのすべてのページが対象になります。 |
| [Quality](../../aspose.pdf.facades/stamp/quality/) { get; set; } | 画像スタンプの品質をパーセンテージで取得または設定します。許容値は 0..100%。 |
| [Rotation](../../aspose.pdf.facades/stamp/rotation/) { get; set; } | スタンプの回転角度（度）を取得または設定します。 |
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
| [SetImageSize](../../aspose.pdf.facades/stamp/setimagesize/)(float, float) | 画像スタンプのサイズを設定します。画像は指定された値に従ってスケーリングされます。 |
| [SetOrigin](../../aspose.pdf.facades/stamp/setorigin/)(float, float) | スタンプが配置されるページ上の位置を設定します。 |

### 関連項目

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


