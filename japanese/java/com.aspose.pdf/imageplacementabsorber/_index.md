---
title: "ImagePlacementAbsorber"
linktitle: "ImagePlacementAbsorber"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "<p> 画像配置オブジェクトの吸収オブジェクトを表します。画像の使用状況を検索し、検索結果へのアクセスを {@code} を介して提供します。</p>"
type: docs
weight: 2340
url: /ja/java/com.aspose.pdf/imageplacementabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ImagePlacementAbsorber

```
public final class ImagePlacementAbsorber extends Object
```

<p> 画像配置オブジェクトの吸収オブジェクトを表します。画像の使用状況を検索し、検索結果へのアクセスを {@code ImagePlacementAbsorber.ImagePlacements} コレクションを介して提供します。 </p> <hr> <pre> この例は、最初の PDF ドキュメントページで画像を見つけ、画像配置プロパティを取得する方法を示しています。 // Open document Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Create ImagePlacementAbsorber object to perform image placement search ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Accept the absorber for first page doc.getPages().get_Item(1).accept(abs); // Display image placement properties for all placements for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { System.out.println(\"image width:\" + imagePlacement.getRectangle().getWidth()); System.out.println(\"image height:\" + imagePlacement.getRectangle().getHeight()); System.out.println(\"image LLX:\" + imagePlacement.getRectangle(0).getX()); System.out.println(\"image LLY:\" + imagePlacement.getRectangle.getY()); System.out.println(\"image horizontal resolution:\" + imagePlacement.getResolution().getX()); System.out.println(\"image vertical resolution:\" + imagePlacement.getResolution().getY()); } </pre> <hr> <p> {@code ImagePlacementAbsorber} オブジェクトは主に画像検索シナリオで使用されます。検索が完了すると、出現箇所は {@code ImagePlacement} オブジェクトとして表され、これらは {@code ImagePlacementAbsorber.ImagePlacements} コレクションに含まれます。{@code ImagePlacement} オブジェクトは画像配置プロパティ（寸法、解像度など）へのアクセスを提供します。 </p> 画像の正の回転は反時計回りで、ページに対しては時計回りです。ここでは、画像の回転角度を表すために、ページの角度を画像の角度から差し引きます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ImagePlacementAbsorber](#ImagePlacementAbsorber--) | 新しい {@code ImagePlacementAbsorber} オブジェクトのインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getImagePlacements](#getImagePlacements--) |  {@code ImagePlacement} オブジェクトで表される画像配置の出現コレクションを取得します。 |
| [isReadOnlyMode](#isReadOnlyMode--) | 解析操作コレクションの読み取り専用モードを取得/設定します。メモリ不足例外を防ぐのに役立つ場合があります。 |
| [setReadOnlyMode](#setReadOnlyMode-boolean-) | 解析操作コレクションの読み取り専用モードを取得/設定します。メモリ不足例外を防ぐのに役立つ場合があります。 |
| [visit](#visit-com.aspose.pdf.IDocument-) | 指定されたドキュメントで検索を実行します。 |
| [visit](#visit-com.aspose.pdf.Page-) | 指定されたページで検索を実行します。 |

### ImagePlacementAbsorber {#ImagePlacementAbsorber--}
```
public ImagePlacementAbsorber()
```

新しい {@code ImagePlacementAbsorber} オブジェクトのインスタンスを初期化します。

### getImagePlacements {#getImagePlacements--}
```
public ImagePlacementCollection getImagePlacements()
```

 {@code ImagePlacement} オブジェクトで表される画像配置の出現コレクションを取得します。

**Returns:**
ImagePlacementCollection オブジェクト

### isReadOnlyMode {#isReadOnlyMode--}
```
public final boolean isReadOnlyMode()
```

解析操作コレクションの読み取り専用モードを取得/設定します。メモリ不足例外を防ぐのに役立つ場合があります。

**Returns:**
ブール値

### setReadOnlyMode {#setReadOnlyMode-boolean-}
```
public final void setReadOnlyMode(boolean value)
```

解析操作コレクションの読み取り専用モードを取得/設定します。メモリ不足例外を防ぐのに役立つ場合があります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### visit {#visit-com.aspose.pdf.IDocument-}
指定されたドキュメントで検索を実行します。

### visit {#visit-com.aspose.pdf.Page-}
指定されたページで検索を実行します。
