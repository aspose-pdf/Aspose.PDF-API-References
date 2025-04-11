---
title: OpenAIClient.GetRunStepsAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClientメソッド。スレッド内の特定の実行のステップのリストを非同期で取得します。
type: docs
weight: 280
url: /ja/net/aspose.pdf.ai/openaiclient/getrunstepsasync/
---
## OpenAIClient.GetRunStepsAsyncメソッド

スレッド内の特定の実行のステップのリストを非同期で取得します。

```csharp
public Task<RunStepListResponse> GetRunStepsAsync(string threadId, string runId, 
    RunStepListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| threadId | String | 実行を含むスレッドのID。 |
| runId | String | ステップを取得する実行のID。 |
| queryParameters | RunStepListQueryParameters | 実行ステップのリストをフィルタリングするためのオプションのクエリパラメーター。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークン。 |

### 戻り値

非同期操作を表すタスク。タスクの結果には実行ステップのリストが含まれます。

### 例外

| 例外 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | スレッドIDがnullまたは空の場合にスローされます。 |
| [AIClientException](../../aiclientexception/) | 実行IDがnullまたは空の場合にスローされます。 |

### 参照

* クラス [RunStepListResponse](../../runsteplistresponse/)
* クラス [RunStepListQueryParameters](../../runsteplistqueryparameters/)
* クラス [OpenAIClient](../)
* 名前空間 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../../)