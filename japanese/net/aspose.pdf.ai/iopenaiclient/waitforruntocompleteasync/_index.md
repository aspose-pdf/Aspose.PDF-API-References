---
title: "IOpenAIClient.WaitForRunToCompleteAsync"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "IOpenAIClient メソッド。スレッド内の実行が完了するのを非同期で待機します"
type: docs
weight: 440
url: /ja/net/aspose.pdf.ai/iopenaiclient/waitforruntocompleteasync/
---
## IOpenAIClient.WaitForRunToCompleteAsync method

スレッド内で run が完了するのを非同期で待機します。

```csharp
public Task<RunResponse> WaitForRunToCompleteAsync(string threadId, string runId, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| threadId | String | ランを含むスレッドのID。 |
| runId | String | 完了まで監視する実行の ID。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークンです。 |

### 戻り値

非同期操作を表すタスクです。タスクの結果には実行の最終ステータスが含まれます。

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


