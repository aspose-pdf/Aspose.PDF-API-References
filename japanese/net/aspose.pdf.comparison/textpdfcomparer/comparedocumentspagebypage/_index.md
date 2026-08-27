---
title: "TextPdfComparer.CompareDocumentsPageByPage"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "TextPdfComparer メソッド。2つのドキュメントをページ単位で比較します"
type: docs
weight: 40
url: /ja/net/aspose.pdf.comparison/textpdfcomparer/comparedocumentspagebypage/
---
## CompareDocumentsPageByPage(Document, Document, ComparisonOptions) {#comparedocumentspagebypage}

2つのドキュメントをページ単位で比較します。

```csharp
public static List<List<DiffOperation>> CompareDocumentsPageByPage(Document document1, 
    Document document2, ComparisonOptions options)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| document1 | Document | 最初のドキュメント.. |
| document2 | Document | 2番目のドキュメント。 |
| オプション | ComparisonOptions | 比較オプション。 |

### 戻り値

ページごとの変更リスト。

### 関連項目

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## CompareDocumentsPageByPage(Document, Document, ComparisonOptions, string) {#comparedocumentspagebypage_1}

2つのドキュメントをページ単位で比較します。結果は PDF ファイルに保存されます。

```csharp
public static List<List<DiffOperation>> CompareDocumentsPageByPage(Document document1, 
    Document document2, ComparisonOptions options, string resultPdfDocumentPath)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| document1 | Document | 最初のドキュメント.. |
| document2 | Document | 2番目のドキュメント。 |
| オプション | ComparisonOptions | 比較オプション。 |
| resultPdfDocumentPath | String | 比較結果を保存する PDF ファイルへのパス。 |

### 戻り値

ページごとの変更リスト。

### 関連項目

* class [DiffOperation](../../diffoperation/)
* class [Document](../../../aspose.pdf/document/)
* class [ComparisonOptions](../../comparisonoptions/)
* class [TextPdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)


