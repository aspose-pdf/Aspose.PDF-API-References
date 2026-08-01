---
title: "GraphicalPdfComparer.ComparePagesToImage"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "GraphicalPdfComparer メソッド。ページをグラフィカルに比較します。比較結果は画像に配置されます。"
type: docs
weight: 70
url: /ja/net/aspose.pdf.comparison/graphicalpdfcomparer/comparepagestoimage/
---
## GraphicalPdfComparer.ComparePagesToImage method

ページをグラフィカルに比較します。比較結果は画像として配置されます。

```csharp
public void ComparePagesToImage(Page page1, Page page2, string resultImagePath)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| page1 | ページ | 比較対象の最初のページです。 |
| page2 | ページ | 比較対象の2番目のページです。 |
| resultImagePath | String | 対象画像ファイルへのパスです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | 比較対象のページのサイズが異なる場合。resultImagePath が null または空文字列の場合。保存画像形式が不明です。 |

### 関連項目

* class [Page](../../../aspose.pdf/page/)
* class [GraphicalPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)


