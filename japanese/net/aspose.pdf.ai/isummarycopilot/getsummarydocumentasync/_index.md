---
title: "ISummaryCopilot.GetSummaryDocumentAsync"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "ISummaryCopilot メソッド。非同期で要約 PDF ドキュメントを取得します。"
type: docs
weight: 20
url: /ja/net/aspose.pdf.ai/isummarycopilot/getsummarydocumentasync/
---
## GetSummaryDocumentAsync(CancellationToken?) {#getsummarydocumentasync_1}

非同期で要約 PDF ドキュメントを取得します。

```csharp
public Task<Document> GetSummaryDocumentAsync(CancellationToken? cancellationToken = default)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| cancellationToken | Nullable`1 | キャンセルトークン（オプション）。 |

### 戻り値

要約ドキュメントを伴う非同期操作を表す Task です。

### 関連項目

* class [Document](../../../aspose.pdf/document/)
* interface [ISummaryCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## GetSummaryDocumentAsync(PageInfo, CancellationToken?) {#getsummarydocumentasync}

指定されたページ情報に対する要約 PDF ドキュメントを非同期で取得します。

```csharp
public Task<Document> GetSummaryDocumentAsync(PageInfo pageInfo, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| pageInfo | PageInfo | 要約ドキュメントを生成する対象ページの情報です。 |
| cancellationToken | Nullable`1 | キャンセルトークン（オプション）。 |

### 戻り値

要約ドキュメントを伴う非同期操作を表す Task です。

### 関連項目

* class [Document](../../../aspose.pdf/document/)
* class [PageInfo](../../../aspose.pdf/pageinfo/)
* interface [ISummaryCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


