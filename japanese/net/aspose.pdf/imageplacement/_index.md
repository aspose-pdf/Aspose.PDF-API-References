---
title: "クラス ImagePlacement"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.ImagePlacement クラス。PDF ドキュメントページに配置された画像の特性を表します"
type: docs
weight: 6030
url: /ja/net/aspose.pdf/imageplacement/
---
## ImagePlacement class

Pdf document page に配置された画像の特性を表します。

```csharp
public sealed class ImagePlacement
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CompositingParameters](../../aspose.pdf/imageplacement/compositingparameters/) { get; } | ページに配置された画像に対して有効なグラフィックス状態の合成パラメータを取得します。 |
| [Image](../../aspose.pdf/imageplacement/image/) { get; } | 関連する XImage リソースオブジェクトを取得します。 |
| [Matrix](../../aspose.pdf/imageplacement/matrix/) { get; } | この画像の現在の変換行列です。 |
| [Operator](../../aspose.pdf/imageplacement/operator/) { get; } | 画像の表示に使用されるオペレーターです。 |
| [Page](../../aspose.pdf/imageplacement/page/) { get; } | 画像を含むページを取得します。 |
| [Rectangle](../../aspose.pdf/imageplacement/rectangle/) { get; } | 画像の矩形を取得します。 |
| [Resolution](../../aspose.pdf/imageplacement/resolution/) { get; } | 画像の解像度を取得します。 |
| [Rotation](../../aspose.pdf/imageplacement/rotation/) { get; } | 画像の回転角度を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Hide](../../aspose.pdf/imageplacement/hide/)() | ページから画像を削除します。 |
| [Replace](../../aspose.pdf/imageplacement/replace/)(Stream) | コレクション内の画像を別の画像に置き換えます。 |
| [Save](../../aspose.pdf/imageplacement/save/#save)(Stream) | 画像を対応する変換（拡大縮小、回転、解像度）とともに保存します。 |
| [Save](../../aspose.pdf/imageplacement/save/#save_1)(Stream, ImageFormat) | 画像を対応する変換（拡大縮小、回転、解像度）とともに保存します。 |

## 備考

画像がページに配置されると、[`Resources`](../resources/)で定義された物理的寸法とは異なる寸法を持つことがあります。オブジェクト `ImagePlacement` は、寸法や解像度などの情報を提供することを目的としています。

## 例

この例では、最初の PDF ドキュメントページで画像を検索し、可視寸法を持つビットマップとして画像を取得する方法を示しています。

```csharp
// 開く document
Document doc = new Document(@"D:\Tests\input.pdf");

// 画像配置検索を実行するために ImagePlacementAbsorber オブジェクトを作成します。
ImagePlacementAbsorber abs = new ImagePlacementAbsorber();

// 最初のページに対してアブソーバーを受け入れます
doc.Pages[1].Accept(abs);

// 可視寸法を持つ画像を取得する
foreach (ImagePlacement imagePlacement in abs.ImagePlacements)
{
    Bitmap scaledImage;
    using (MemoryStream imageStream = new MemoryStream())
    {
        // リソースから画像を取得する
        imagePlacement.Image.Save(imageStream, ImageFormat.Png);
        Bitmap resourceImage = (Bitmap) Bitmap.FromStream(imageStream);
        // 実際の寸法で新しいビットマップを作成する
        scaledImage = new Bitmap(resourceImage, (int)imagePlacement.Rectangle.Width, (int)imagePlacement.Rectangle.Height);
    }
} 
```

### 関連項目

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


