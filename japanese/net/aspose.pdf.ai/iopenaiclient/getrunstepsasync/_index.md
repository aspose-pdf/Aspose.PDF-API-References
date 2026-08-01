---
title: "IOpenAIClient.GetRunStepsAsync"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "IOpenAIClient メソッド。スレッド内の特定の実行のステップ一覧を非同期で取得します"
type: docs
weight: 260
url: /ja/net/aspose.pdf.ai/iopenaiclient/getrunstepsasync/
---
## IOpenAIClient.GetRunStepsAsync method

スレッド内の特定の実行のステップ一覧を非同期で取得します。

```csharp
public Task<RunStepListResponse> GetRunStepsAsync(string threadId, string runId, 
    RunStepListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| threadId | String | ランを含むスレッドのID。 |
| runId | String | ステップを取得する実行の ID。 |
| queryParameters | RunStepListQueryParameters | 実行ステップの一覧をフィルタリングするためのオプションのクエリ パラメータ。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークンです。 |

### 戻り値

非同期操作を表すタスク。タスクの結果には実行ステップの一覧が含まれます。

### 例外

| 例外 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | スレッドIDがnullまたは空の場合にスローされます。 |
| [AIClientException](../../aiclientexception/) | run Id が null または空の場合にスローされます。 |

### 関連項目

* class [RunStepListResponse](../../runsteplistresponse/)
* class [RunStepListQueryParameters](../../runsteplistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


