---
title: OpenAIClient.CancelRunAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient メソッド。スレッド内の既存の実行を非同期にキャンセルします
type: docs
weight: 10
url: /ja/net/aspose.pdf.ai/openaiclient/cancelrunasync/
---
## OpenAIClient.CancelRunAsync メソッド

スレッド内の既存の実行を非同期にキャンセルします。

```csharp
public Task<RunResponse> CancelRunAsync(string threadId, string runId, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| threadId | String | キャンセルする実行を含むスレッドの ID。 |
| runId | String | キャンセルする実行の ID。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークン。 |

### 戻り値

非同期操作を表すタスク。タスクの結果には、実行キャンセルからの応答が含まれます。

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