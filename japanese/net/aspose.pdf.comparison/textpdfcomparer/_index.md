---
title: Class TextPdfComparer
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.TextPdfComparer クラス。2つの PDF ページまたは PDF ドキュメントを比較するクラスを表します。
type: docs
weight: 3320
url: /ja/net/aspose.pdf.comparison/textpdfcomparer/
---
## TextPdfComparer クラス

2つの PDF ページまたは PDF ドキュメントを比較するクラスを表します。

```csharp
public class TextPdfComparer
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TextPdfComparer](textpdfcomparer/)() | デフォルトのコンストラクタ。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [AssemblyDestinationPageText](../../aspose.pdf.comparison/textpdfcomparer/assemblydestinationpagetext/)(List&lt;DiffOperation&gt;) | 変更されたテキストを変更リストから復元します。 |
| static [AssemblySourcePageText](../../aspose.pdf.comparison/textpdfcomparer/assemblysourcepagetext/)(List&lt;DiffOperation&gt;) | 変更リストから元のテキストを復元します。 |
| static [CompareDocumentsPageByPage](../../aspose.pdf.comparison/textpdfcomparer/comparedocumentspagebypage/#comparedocumentspagebypage)(Document, Document, ComparisonOptions) | 2つのドキュメントをページごとに比較します。 |
| static [CompareDocumentsPageByPage](../../aspose.pdf.comparison/textpdfcomparer/comparedocumentspagebypage/#comparedocumentspagebypage_1)(Document, Document, ComparisonOptions, string) | 2つのドキュメントをページごとに比較します。結果は PDF ファイルに保存されます。 |
| static [CompareFlatDocuments](../../aspose.pdf.comparison/textpdfcomparer/compareflatdocuments/#compareflatdocuments)(Document, Document, ComparisonOptions) | 2つのドキュメントをページごとに比較します。ドキュメントは全体として比較されます。テキストを比較する前に、ドキュメントページのテキストが1つのテキストに結合されます。 |
| static [CompareFlatDocuments](../../aspose.pdf.comparison/textpdfcomparer/compareflatdocuments/#compareflatdocuments_1)(Document, Document, ComparisonOptions, string) | 2つのドキュメントをページごとに比較します。結果は PDF ファイルに保存されます。ドキュメントは全体として比較されます。テキストを比較する前に、ドキュメントページのテキストが1つのテキストに結合されます。 |
| static [ComparePages](../../aspose.pdf.comparison/textpdfcomparer/comparepages/)(Page, Page, ComparisonOptions) | ドキュメントページを比較します。 |
| static [CreateComparisonStatistics](../../aspose.pdf.comparison/textpdfcomparer/createcomparisonstatistics/#createcomparisonstatistics_1)(List&lt;DiffOperation&gt;) | 比較統計を取得します。 |
| static [CreateComparisonStatistics](../../aspose.pdf.comparison/textpdfcomparer/createcomparisonstatistics/#createcomparisonstatistics)(List&lt;List&lt;DiffOperation&gt;&gt;) | ドキュメントの比較統計を取得します。 |

### 参照

* 名前空間 [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* アセンブリ [Aspose.PDF](../../)