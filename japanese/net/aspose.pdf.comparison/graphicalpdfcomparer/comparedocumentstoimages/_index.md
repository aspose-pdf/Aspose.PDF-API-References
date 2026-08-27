---
title: "GraphicalPdfComparer.CompareDocumentsToImages"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "GraphicalPdfComparer メソッド。ドキュメントをグラフィカルに比較します。比較結果は画像に配置されます。"
type: docs
weight: 50
url: /ja/net/aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstoimages/
---
## GraphicalPdfComparer.CompareDocumentsToImages method

ドキュメントをグラフィカルに比較します。比較結果は画像として配置されます。

```csharp
public void CompareDocumentsToImages(Document document1, Document document2, 
    string targetDirectory, string fileNamePrefix, ImageFormat imageFormat)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| document1 | Document | 比較する最初のドキュメントです。 |
| document2 | Document | 比較する2番目のドキュメントです。 |
| targetDirectory | String | 比較結果を保存するディレクトリです。 |
| fileNamePrefix | String | 画像名のプレフィックスです。 |
| imageFormat | ImageFormat | 保存する画像形式です。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | 比較対象のページのサイズが異なる場合。targetDirectory が null または空文字列の場合。fileNamePrefix が null または空文字列の場合。 |

### 関連項目

* class [Document](../../../aspose.pdf/document/)
* class [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)


