---
title: SideBySidePdfComparer.Compare
second_title: Aspose.PDF for .NET API Reference
description: SideBySidePdfComparer メソッド。2つのページを比較します。結果は、最初のページが最初に書き込まれ、その後に2番目のページが書き込まれるPDFドキュメントに保存されます。Adobe Acrobatの2ページ表示で開くと、変更を並べて見ることができます。削除は左側のページに、挿入は右側のページに記載されます。
type: docs
weight: 10
url: /ja/net/aspose.pdf.comparison/sidebysidepdfcomparer/compare/
---
## Compare(Page, Page, string, SideBySideComparisonOptions) {#compare_1}

2つのページを比較します。結果は、最初のページが最初に書き込まれ、その後に2番目のページが書き込まれるPDFドキュメントに保存されます。Adobe Acrobatの2ページ表示で開くと、変更を並べて見ることができます。削除は左側のページに、挿入は右側のページに記載されます。

```csharp
public static void Compare(Page page1, Page page2, string targetPdfPath, 
    SideBySideComparisonOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| page1 | Page | 比較する最初のページ。 |
| page2 | Page | 比較する2番目のページ。 |
| targetPdfPath | String | 比較結果を保存するPDFファイルのパス。 |
| options | SideBySideComparisonOptions | 比較オプション。 |

### See Also

* class [Page](../../../aspose.pdf/page/)
* class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* class [SideBySidePdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## Compare(Document, Document, string, SideBySideComparisonOptions) {#compare}

2つのドキュメントを比較します。ページは1つずつ比較されます。比較されたドキュメントのページは、結果のドキュメントに1つずつコピーされます。最初に最初のドキュメントの最初のページ、その後に2番目のドキュメントの最初のページが続きます。次に、最初のドキュメントの2番目のページ、その後に2番目のドキュメントの2番目のページが続きます。Adobe Acrobatの2ページ表示で開くと、変更を並べて見ることができます。削除は左側のページに、挿入は右側のページに記載されます。

```csharp
public static void Compare(Document document1, Document document2, string targetPdfPath, 
    SideBySideComparisonOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| document1 | Document | 比較する最初のドキュメント。 |
| document2 | Document | 比較する2番目のドキュメント。 |
| targetPdfPath | String | 比較結果を保存するPDFファイルのパス。 |
| options | SideBySideComparisonOptions | 比較オプション。 |

### See Also

* class [Document](../../../aspose.pdf/document/)
* class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* class [SideBySidePdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)