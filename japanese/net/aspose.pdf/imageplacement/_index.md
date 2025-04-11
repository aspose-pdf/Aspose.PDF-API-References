---
title: Class ImagePlacement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ImagePlacement クラス。Pdf ドキュメントページに配置された画像の特性を表します
type: docs
weight: 5900
url: /ja/net/aspose.pdf/imageplacement/
---
## ImagePlacement クラス

Pdf ドキュメントページに配置された画像の特性を表します。

```csharp
public sealed class ImagePlacement
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CompositingParameters](../../aspose.pdf/imageplacement/compositingparameters/) { get; } | ページに配置された画像のためにアクティブなグラフィックス状態の合成パラメータを取得します。 |
| [Image](../../aspose.pdf/imageplacement/image/) { get; } | 関連する XImage リソースオブジェクトを取得します。 |
| [Matrix](../../aspose.pdf/imageplacement/matrix/) { get; } | この画像の現在の変換行列。 |
| [Operator](../../aspose.pdf/imageplacement/operator/) { get; } | 画像を表示するために使用されるオペレーター。 |
| [Page](../../aspose.pdf/imageplacement/page/) { get; } | 画像を含むページを取得します。 |
| [Rectangle](../../aspose.pdf/imageplacement/rectangle/) { get; } | 画像の矩形を取得します。 |
| [Resolution](../../aspose.pdf/imageplacement/resolution/) { get; } | 画像の解像度を取得します。 |
| [Rotation](../../aspose.pdf/imageplacement/rotation/) { get; } | 画像の回転角度を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Hide](../../aspose.pdf/imageplacement/hide/)() | ページから画像を削除します。 |
| [Replace](../../aspose.pdf/imageplacement/replace/)(Stream) | コレクション内の画像を別の画像に置き換えます。 |
| [Save](../../aspose.pdf/imageplacement/save/#save)(Stream) | スケーリング、回転、解像度に対応する変換を伴って画像を保存します。 |
| [Save](../../aspose.pdf/imageplacement/save/#save_1)(Stream, ImageFormat) | スケーリング、回転、解像度に対応する変換を伴って画像を保存します。 |

## 備考

画像がページに配置されると、[`Resources`](../resources/) で定義された物理的寸法とは異なる寸法を持つ場合があります。オブジェクト `ImagePlacement` は、寸法、解像度などの情報を提供することを目的としています。

## 例

この例では、最初の PDF ドキュメントページ上の画像を見つけ、可視寸法を持つビットマップとして画像を取得する方法を示します。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create ImagePlacementAbsorber object to perform image placement search
ImagePlacementAbsorber abs = new ImagePlacementAbsorber();

// Accept the absorber for first page
doc.Pages[1].Accept(abs);

// Retrieve images with visible dimensions
foreach (ImagePlacement imagePlacement in abs.ImagePlacements)
{
    Bitmap scaledImage;
    using (MemoryStream imageStream = new MemoryStream())
    {
        // Retrieve image from resources
        imagePlacement.Image.Save(imageStream, ImageFormat.Png);
        Bitmap resourceImage = (Bitmap) Bitmap.FromStream(imageStream);
        // Create new bitmap with actual dimensions
        scaledImage = new Bitmap(resourceImage, (int)imagePlacement.Rectangle.Width, (int)imagePlacement.Rectangle.Height);
    }
} 
```

### 参照

* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)