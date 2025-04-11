---
title: ISummaryCopilot.SaveSummaryAsync
second_title: Aspose.PDF for .NET API Reference
description: ISummaryCopilot メソッド。要約を PDF ファイルに非同期で保存します
type: docs
weight: 30
url: /ja/net/aspose.pdf.ai/isummarycopilot/savesummaryasync/
---
## SaveSummaryAsync(string, CancellationToken?) {#savesummaryasync_1}

要約を PDF ファイルに非同期で保存します。

```csharp
public Task SaveSummaryAsync(string outputFileName, CancellationToken? cancellationToken = default)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| outputFileName | String | 要約を保存する出力ファイルの名前。 |
| cancellationToken | Nullable`1 | キャンセルトークン（オプション）。 |

### 戻り値

非同期操作を表すタスク。

### 参照

* interface [ISummaryCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveSummaryAsync(string, SaveFormat, CancellationToken?) {#savesummaryasync}

指定された形式でファイルに要約を非同期で保存します。

```csharp
public Task SaveSummaryAsync(string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| outputFileName | String | 要約を保存する出力ファイルの名前。 |
| saveFormat | SaveFormat | 要約を保存する形式。 |
| cancellationToken | Nullable`1 | キャンセルトークン（オプション）。 |

### 戻り値

非同期操作を表すタスク。

### 参照

* enum [SaveFormat](../../../aspose.pdf/saveformat/)
* interface [ISummaryCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)