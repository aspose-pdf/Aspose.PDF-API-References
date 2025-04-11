---
title: TextPdfComparer.CompareFlatDocuments
second_title: Aspose.PDF for .NET API Reference
description: TextPdfComparer メソッド。2つのドキュメントをページごとに比較します。ドキュメントは全体として比較されます。テキストを比較する前に、ドキュメントページのテキストが1つのテキストに結合されます。
type: docs
weight: 50
url: /ja/net/aspose.pdf.comparison/textpdfcomparer/compareflatdocuments/
---
## CompareFlatDocuments(Document, Document, ComparisonOptions) {#compareflatdocuments}

2つのドキュメントをページごとに比較します。ドキュメントは全体として比較されます。テキストを比較する前に、ドキュメントページのテキストが1つのテキストに結合されます。

```csharp
public static List<DiffOperation> CompareFlatDocuments(Document document1, Document document2, 
    ComparisonOptions options)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| document1 | Document | 最初のドキュメント。 |
| document2 | Document | 2番目のドキュメント。 |
| options | ComparisonOptions | 比較オプション。 |

### 戻り値

変更のリスト。

### 参照

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## CompareFlatDocuments(Document, Document, ComparisonOptions, string) {#compareflatdocuments_1}

2つのドキュメントをページごとに比較します。結果はPDFファイルに保存されます。ドキュメントは全体として比較されます。テキストを比較する前に、ドキュメントページのテキストが1つのテキストに結合されます。

```csharp
public static List<DiffOperation> CompareFlatDocuments(Document document1, Document document2, 
    ComparisonOptions options, string resultPdfDocumentPath)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| document1 | Document | 最初のドキュメント。 |
| document2 | Document | 2番目のドキュメント。 |
| options | ComparisonOptions | 比較オプション。 |
| resultPdfDocumentPath | String | 比較結果を保存するPDFファイルへのパス。 |

### 戻り値

変更のリスト。

### 参照

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)