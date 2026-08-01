---
title: "クラス ImagePlacementAbsorber"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.ImagePlacementAbsorber クラス。画像配置オブジェクトの吸収オブジェクトを表します。画像の使用状況を検索し、検索結果へは ImagePlacements コレクションを介してアクセスできます。"
type: docs
weight: 6040
url: /ja/net/aspose.pdf/imageplacementabsorber/
---
## ImagePlacementAbsorber class

画像配置オブジェクトの吸収オブジェクトを表します。画像の使用状況を検索し、検索結果へは [`ImagePlacements`](./imageplacements/) コレクションを介してアクセスできます。

```csharp
public sealed class ImagePlacementAbsorber
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ImagePlacementAbsorber](imageplacementabsorber/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [ImagePlacements](../../aspose.pdf/imageplacementabsorber/imageplacements/) { get; } | [`ImagePlacement`](../imageplacement/) オブジェクトで表される画像配置の出現のコレクションを取得します。 |
| [IsReadOnlyMode](../../aspose.pdf/imageplacementabsorber/isreadonlymode/) { get; set; } | 解析操作コレクションの読み取り専用モードを取得/設定します。メモリ不足例外の回避に役立つ可能性があります。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit)(Document) | 指定された Document で検索を実行します。 |
| [Visit](../../aspose.pdf/imageplacementabsorber/visit/#visit_1)(Page) | 指定された Page で検索を実行します。 |

## 備考

`ImagePlacementAbsorber` オブジェクトは主に画像検索シナリオで使用されます。検索が完了すると、出現は [`ImagePlacement`](../imageplacement/) オブジェクトで表され、これらは [`ImagePlacements`](./imageplacements/) コレクションに含まれます。[`ImagePlacement`](../imageplacement/) オブジェクトは画像配置プロパティ（寸法、解像度など）へのアクセスを提供します。画像の正の回転は反時計回りで、ページに対しては時計回りです。ここでは、画像の回転角度を表すために、ページの角度を画像の角度から差し引きます。

## 例

この例では、最初の PDF Document の Page で画像を検索し、画像配置プロパティを取得する方法を示しています。

```csharp
// 開く document
Document doc = new Document(@"D:\Tests\input.pdf");

// 画像配置検索を実行するために ImagePlacementAbsorber オブジェクトを作成します。
ImagePlacementAbsorber abs = new ImagePlacementAbsorber();

// 最初のページに対してアブソーバーを受け入れます
doc.Pages[1].Accept(abs);

// すべての配置に対する画像配置プロパティを表示します。
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

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


