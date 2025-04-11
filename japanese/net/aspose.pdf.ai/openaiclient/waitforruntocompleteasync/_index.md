---
title: OpenAIClient.WaitForRunToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient メソッド。スレッド内で非同期に実行が完了するのを待ちます
type: docs
weight: 470
url: /ja/net/aspose.pdf.ai/openaiclient/waitforruntocompleteasync/
---
## OpenAIClient.WaitForRunToCompleteAsync メソッド

スレッド内で非同期に実行が完了するのを待ちます。

```csharp
public Task<RunResponse> WaitForRunToCompleteAsync(string threadId, string runId, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| threadId | String | 実行を含むスレッドの ID。 |
| runId | String | 完了まで監視する実行の ID。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークン。 |

### 戻り値

非同期操作を表すタスク。タスクの結果には、実行の最終ステータスが含まれます。

### 例外

| 例外 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | スレッド ID が null または空の場合にスローされます。 |
| [AIClientException](../../aiclientexception/) | 実行 ID が null または空の場合にスローされます。 |

### 参照

* クラス [RunResponse](../../runresponse/)
* クラス [OpenAIClient](../)
* 名前空間 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../../)