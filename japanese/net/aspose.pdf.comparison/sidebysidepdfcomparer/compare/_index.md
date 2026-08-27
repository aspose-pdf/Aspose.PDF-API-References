---
title: "SideBySidePdfComparer.Compare"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "SideBySidePdfComparer メソッド。2 つのページを比較します。結果は PDF ドキュメントに保存され、最初のページが先に、次に2ページ目が書き込まれます。Adobe Acrobat の 2 ページ表示で開くと、変更点を左右に並べて確認できます。削除は左側のページに、挿入は右側のページに示されます"
type: docs
weight: 10
url: /ja/net/aspose.pdf.comparison/sidebysidepdfcomparer/compare/
---
## Compare(Page, Page, string, SideBySideComparisonOptions) {#compare_1}

2つのページを比較します。結果は PDF ドキュメントに保存され、最初に1ページ目が書き込まれ、次に2ページ目が続きます。Adobe Acrobat の「2ページ表示」で開くと、変更点を左右に並べて確認できます。削除は左側のページに、挿入は右側のページに示されます。

```csharp
public static void Compare(Page page1, Page page2, string targetPdfPath, 
    SideBySideComparisonOptions options)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| page1 | ページ | 比較対象の最初のページです。 |
| page2 | ページ | 比較対象の最初のページです。 |
| targetPdfPath | String | 比較結果を保存する PDF ファイルへのパスです。 |
| オプション | SideBySideComparisonOptions | 比較オプションです。 |

### 関連項目

* class [Page](../../../aspose.pdf/page/)
* class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* class [SideBySidePdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)

---

## Compare(Document, Document, string, SideBySideComparisonOptions) {#compare}

2つのドキュメントを比較します。ページは1つずつ比較されます。比較されたドキュメントのページは、結果のドキュメントに1つずつ順にコピーされます。最初に最初のドキュメントの1ページ目、次に2番目のドキュメントの1ページ目が配置されます。その後、最初のドキュメントの2ページ目、次に2番目のドキュメントの2ページ目というように続きます。Adobe Acrobat の「2ページ表示」で開くと、変更点を左右に並べて確認できます。削除は左側のページに、挿入は右側のページに示されます。

```csharp
public static void Compare(Document document1, Document document2, string targetPdfPath, 
    SideBySideComparisonOptions options)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| document1 | Document | 比較する最初のドキュメントです。 |
| document2 | Document | 比較する2番目のドキュメントです。 |
| targetPdfPath | String | 比較結果を保存する PDF ファイルへのパスです。 |
| オプション | SideBySideComparisonOptions | 比較オプションです。 |

### 関連項目

* class [Document](../../../aspose.pdf/document/)
* class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* class [SideBySidePdfComparer](../)
* namespace [Aspose.Pdf.Comparison](../../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../../)


