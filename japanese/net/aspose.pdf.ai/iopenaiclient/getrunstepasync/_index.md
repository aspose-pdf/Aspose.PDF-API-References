---
title: "IOpenAIClient.GetRunStepAsync"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "IOpenAIClient メソッド。実行内の特定ステップの詳細を非同期で取得します"
type: docs
weight: 250
url: /ja/net/aspose.pdf.ai/iopenaiclient/getrunstepasync/
---
## IOpenAIClient.GetRunStepAsync method

実行内の特定のステップの詳細を非同期で取得します。

```csharp
public Task<RunStepResponse> GetRunStepAsync(string threadId, string runId, string runStepId, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| threadId | String | ランを含むスレッドのID。 |
| runId | String | ステップを含むランのID。 |
| runStepId | String | 取得するランステップのID。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークンです。 |

### 戻り値

非同期操作を表すタスクです。タスクの結果には実行ステップの詳細が含まれます。

### 例外

| 例外 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | スレッドIDがnullまたは空の場合にスローされます。 |
| [AIClientException](../../aiclientexception/) | run Id が null または空の場合にスローされます。 |
| [AIClientException](../../aiclientexception/) | run step Id が null または空の場合にスローされます。 |

### 関連項目

* class [RunStepResponse](../../runstepresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


