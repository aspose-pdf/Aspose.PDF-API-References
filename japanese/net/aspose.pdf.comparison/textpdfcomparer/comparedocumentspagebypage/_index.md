---
title: TextPdfComparer.CompareDocumentsPageByPage
second_title: Aspose.PDF for .NET API Reference
description: TextPdfComparer メソッド。2つのドキュメントをページごとに比較します。
type: docs
weight: 40
url: /ja/net/aspose.pdf.comparison/textpdfcomparer/comparedocumentspagebypage/
---
## CompareDocumentsPageByPage(Document, Document, ComparisonOptions) {#comparedocumentspagebypage}

2つのドキュメントをページごとに比較します。

```csharp
public static List<List<DiffOperation>> CompareDocumentsPageByPage(Document document1, 
    Document document2, ComparisonOptions options)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| document1 | Document | 最初のドキュメント.. |
| document2 | Document | 2番目のドキュメント。 |
| options | ComparisonOptions | 比較オプション。 |

### 戻り値

ページごとの変更のリスト。

### 参照

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## CompareDocumentsPageByPage(Document, Document, ComparisonOptions, string) {#comparedocumentspagebypage_1}

2つのドキュメントをページごとに比較します。結果はPDFファイルに保存されます。

```csharp
public static List<List<DiffOperation>> CompareDocumentsPageByPage(Document document1, 
    Document document2, ComparisonOptions options, string resultPdfDocumentPath)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| document1 | Document | 最初のドキュメント.. |
| document2 | Document | 2番目のドキュメント。 |
| options | ComparisonOptions | 比較オプション。 |
| resultPdfDocumentPath | String | 比較結果を保存するPDFファイルのパス。 |

### 戻り値

ページごとの変更のリスト。

### 参照

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)