---
title: "TextPdfComparer.CompareFlatDocuments"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "TextPdfComparer メソッド。2つのドキュメントをページ単位で比較します。ドキュメントは全体として比較されます。テキストを比較する前に、ドキュメントページのテキストを1つのテキストに結合します"
type: docs
weight: 50
url: /ja/net/aspose.pdf.comparison/textpdfcomparer/compareflatdocuments/
---
## CompareFlatDocuments(Document, Document, ComparisonOptions) {#compareflatdocuments}

2つのドキュメントをページ単位で比較します。ドキュメント全体として比較されます。テキストを比較する前に、ドキュメントページのテキストが1つのテキストに結合されます。

```csharp
public static List<DiffOperation> CompareFlatDocuments(Document document1, Document document2, 
    ComparisonOptions options)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| document1 | Document | 最初のドキュメント。 |
| document2 | Document | 2番目のドキュメント。 |
| オプション | ComparisonOptions | 比較オプション。 |

### 戻り値

変更リスト。

### 関連項目

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## CompareFlatDocuments(Document, Document, ComparisonOptions, string) {#compareflatdocuments_1}

2つのドキュメントをページ単位で比較します。結果は PDF ファイルに保存されます。ドキュメント全体として比較されます。テキストを比較する前に、ドキュメントページのテキストが1つのテキストに結合されます。

```csharp
public static List<DiffOperation> CompareFlatDocuments(Document document1, Document document2, 
    ComparisonOptions options, string resultPdfDocumentPath)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| document1 | Document | 最初のドキュメント。 |
| document2 | Document | 2番目のドキュメント。 |
| オプション | ComparisonOptions | 比較オプション。 |
| resultPdfDocumentPath | String | 比較結果を保存する PDF ファイルへのパス。 |

### 戻り値

変更リスト。

### 関連項目

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)


