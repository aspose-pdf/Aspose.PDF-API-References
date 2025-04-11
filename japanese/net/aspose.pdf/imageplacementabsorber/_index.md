---
title: Class ImagePlacementAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ImagePlacementAbsorber クラス。画像配置オブジェクトのアブソーバーオブジェクトを表します。画像の使用状況を検索し、`ImagePlacements` コレクションを介して検索結果にアクセスします。
type: docs
weight: 5910
url: /ja/net/aspose.pdf/imageplacementabsorber/
---
## ImagePlacementAbsorber クラス

画像配置オブジェクトのアブソーバーオブジェクトを表します。画像の使用状況を検索し、[`ImagePlacements`](./imageplacements/) コレクションを介して検索結果にアクセスします。

```csharp
public sealed class ImagePlacementAbsorber
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ImagePlacementAbsorber](imageplacementabsorber/)() | デフォルトコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ImagePlacements](../../aspose.pdf/imageplacementabsorber/imageplacements/) { get; } | [`ImagePlacement`](../imageplacement/) オブジェクトで表される画像配置の発生のコレクションを取得します。 |
| [IsReadOnlyMode](../../aspose.pdf/imageplacementabsorber/isreadonlymode/) { get; set; } | 解析操作コレクションの読み取り専用モードを取得/設定します。メモリ不足の例外を防ぐのに役立つ場合があります。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit)(Document) | 指定されたドキュメントで検索を実行します。 |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit_1)(Page) | 指定されたページで検索を実行します。 |

## 備考

`ImagePlacementAbsorber` オブジェクトは基本的に画像検索シナリオで使用されます。検索が完了すると、発生は [`ImagePlacement`](../imageplacement/) オブジェクトで表され、[`ImagePlacements`](./imageplacements/) コレクションに含まれます。[`ImagePlacement`](../imageplacement/) オブジェクトは、画像配置プロパティ（寸法、解像度など）へのアクセスを提供します。画像の正の回転は反時計回りであり、ページの場合は時計回りです。ここでは、画像の回転角度を表す必要があるため、ページの角度を画像の角度から引きます。

## 例

この例では、最初の PDF ドキュメントページで画像を見つけ、画像配置プロパティを取得する方法を示します。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create ImagePlacementAbsorber object to perform image placement search
ImagePlacementAbsorber abs = new ImagePlacementAbsorber();

// Accept the absorber for first page
doc.Pages[1].Accept(abs);

// Display image placement properties for all placements
foreach (ImagePlacement imagePlacement in abs.ImagePlacements)
{     
    Console.Out.WriteLine("image width:" + imagePlacement.Rectangle.Width);
    Console.Out.WriteLine("image height:" + imagePlacement.Rectangle.Height);
    Console.Out.WriteLine("image LLX:" + imagePlacement.Rectangle.LLX);
    Console.Out.WriteLine("image LLY:" + imagePlacement.Rectangle.LLY);
    Console.Out.WriteLine("image horizontal resolution:" + imagePlacement.Resolution.X);
    Console.Out.WriteLine("image vertical resolution:" + imagePlacement.Resolution.Y);
}
```

### 関連項目

* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)