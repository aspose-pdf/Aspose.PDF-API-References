---
title: GraphicalPdfComparer.CompareDocumentsToImages
second_title: Aspose.PDF for .NET API Reference
description: GraphicalPdfComparer メソッド。文書をグラフィカルに比較します。比較結果は画像に配置されます。
type: docs
weight: 50
url: /ja/net/aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstoimages/
---
## GraphicalPdfComparer.CompareDocumentsToImages メソッド

文書をグラフィカルに比較します。比較結果は画像に配置されます。

```csharp
public void CompareDocumentsToImages(Document document1, Document document2, 
    string targetDirectory, string fileNamePrefix, ImageFormat imageFormat)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| document1 | Document | 比較する最初の文書。 |
| document2 | Document | 比較する2番目の文書。 |
| targetDirectory | String | 比較結果を保存するディレクトリ。 |
| fileNamePrefix | String | 画像の名前のプレフィックス。 |
| imageFormat | ImageFormat | 保存する画像の形式。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | 比較されるページのサイズが異なる場合。targetDirectory が null または空の文字列の場合。fileNamePrefix が null または空の文字列の場合。 |

### 参照

* クラス [Document](../../../aspose.pdf/document/)
* クラス [GraphicalPdfComparer](../)
* 名前空間 [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* アセンブリ [Aspose.PDF](../../../)