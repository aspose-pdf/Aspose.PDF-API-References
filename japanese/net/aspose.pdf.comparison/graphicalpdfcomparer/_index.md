---
title: "クラス GraphicalPdfComparer"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Comparison.GraphicalPdfComparer クラス。PDF ドキュメントをグラフィカルに比較するためのクラスを表します。主にグラフィカルな性質の小さな変更を検索するために使用すべきです。テキスト内容の変更を比較するには、他の PDF 比較クラスを使用してください。"
type: docs
weight: 3300
url: /ja/net/aspose.pdf.comparison/graphicalpdfcomparer/
---
## GraphicalPdfComparer class

PDF ドキュメントをグラフィカルに比較するクラスを表します。主にグラフィック上の小さな変更を検索するために使用すべきです。テキスト内容の変更を比較する場合は、他の PDF 比較クラスを使用してください。

```csharp
public class GraphicalPdfComparer
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [GraphicalPdfComparer](graphicalpdfcomparer/)() | デフォルトコンストラクタです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Color](../../aspose.pdf.comparison/graphicalpdfcomparer/color/) { get; set; } | 変更フラグの色を取得および設定します。デフォルトの色は赤です。 |
| [Resolution](../../aspose.pdf.comparison/graphicalpdfcomparer/resolution/) { get; set; } | 生成される画像の解像度を取得および設定します。デフォルト値は 150dpi です。 |
| [Threshold](../../aspose.pdf.comparison/graphicalpdfcomparer/threshold/) { get; set; } | しきい値（パーセンテージ）を取得および設定します。この値により、重要でない小さな変更を無視できます。デフォルト値は 0% です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [CompareDocumentsToImages](../../aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstoimages/)(Document, Document, string, string, ImageFormat) | ドキュメントをグラフィカルに比較します。比較結果は画像として配置されます。 |
| [CompareDocumentsToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparedocumentstopdf/)(Document, Document, string) | ドキュメントをグラフィカルに比較します。比較結果は PDF ドキュメントに配置されます。 |
| [ComparePagesToImage](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestoimage/)(Page, Page, string) | ページをグラフィカルに比較します。比較結果は画像として配置されます。 |
| [ComparePagesToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/#comparepagestopdf)(Page, Page, Document) | ページをグラフィカルに比較します。比較結果は PDF ドキュメントに配置されます。 |
| [ComparePagesToPdf](../../aspose.pdf.comparison/graphicalpdfcomparer/comparepagestopdf/#comparepagestopdf_1)(Page, Page, string) | ページをグラフィカルに比較します。比較結果は PDF ドキュメントに配置されます。 |
| [GetDifference](../../aspose.pdf.comparison/graphicalpdfcomparer/getdifference/)(Page, Page) | ページ画像間の差分を取得します。結果には比較された最初のページの画像と差分の配列が含まれます。 |

### 関連項目

* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


