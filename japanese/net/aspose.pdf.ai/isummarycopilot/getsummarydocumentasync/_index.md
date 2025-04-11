---
title: ISummaryCopilot.GetSummaryDocumentAsync
second_title: Aspose.PDF for .NET API Reference
description: ISummaryCopilot メソッド。非同期で要約 PDF ドキュメントを取得します
type: docs
weight: 20
url: /ja/net/aspose.pdf.ai/isummarycopilot/getsummarydocumentasync/
---
## GetSummaryDocumentAsync(CancellationToken?) {#getsummarydocumentasync_1}

非同期で要約 PDF ドキュメントを取得します。

```csharp
public Task<Document> GetSummaryDocumentAsync(CancellationToken? cancellationToken = default)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| cancellationToken | Nullable`1 | キャンセルトークン（オプション）。 |

### 戻り値

要約ドキュメントを持つ非同期操作を表すタスク。

### 参照

* クラス [Document](../../../aspose.pdf/document/)
* インターフェース [ISummaryCopilot](../)
* 名前空間 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../../)

---

## GetSummaryDocumentAsync(PageInfo, CancellationToken?) {#getsummarydocumentasync}

指定されたページ情報の要約 PDF ドキュメントを非同期で取得します。

```csharp
public Task<Document> GetSummaryDocumentAsync(PageInfo pageInfo, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| pageInfo | PageInfo | 要約ドキュメントを生成するためのページ情報。 |
| cancellationToken | Nullable`1 | キャンセルトークン（オプション）。 |

### 戻り値

要約ドキュメントを持つ非同期操作を表すタスク。

### 参照

* クラス [Document](../../../aspose.pdf/document/)
* クラス [PageInfo](../../../aspose.pdf/pageinfo/)
* インターフェース [ISummaryCopilot](../)
* 名前空間 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../../)