---
title: "IOpenAIClient.CancelRunAsync"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "IOpenAIClient メソッド。スレッド内の既存の実行を非同期でキャンセルします"
type: docs
weight: 10
url: /ja/net/aspose.pdf.ai/iopenaiclient/cancelrunasync/
---
## IOpenAIClient.CancelRunAsync method

新しいアシスタントを非同期に作成します。

```csharp
public Task<RunResponse> CancelRunAsync(string threadId, string runId, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| threadId | String | キャンセルする実行が含まれるスレッドの ID。 |
| runId | String | キャンセルする実行の ID。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークンです。 |

### 戻り値

非同期操作を表すタスクです。タスクの結果には実行キャンセルのレスポンスが含まれます。

### 例外

| 例外 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | スレッドIDがnullまたは空の場合にスローされます。 |
| [AIClientException](../../aiclientexception/) | run Id が null または空の場合にスローされます。 |

### 関連項目

* class [RunResponse](../../runresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


