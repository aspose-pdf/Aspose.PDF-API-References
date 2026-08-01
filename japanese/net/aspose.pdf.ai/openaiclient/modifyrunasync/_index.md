---
title: "OpenAIClient.ModifyRunAsync"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "OpenAIClient メソッド。スレッド内の既存の実行を非同期に変更します。"
type: docs
weight: 410
url: /ja/net/aspose.pdf.ai/openaiclient/modifyrunasync/
---
## OpenAIClient.ModifyRunAsync method

スレッド内の既存の実行を非同期で変更します。

```csharp
public Task<RunResponse> ModifyRunAsync(string threadId, string runId, 
    RunModifyRequest assistantModifyRequest, CancellationToken? cancellationToken = default)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| threadId | String | ランを含むスレッドのID。 |
| runId | String | 変更する実行の ID。 |
| assistantModifyRequest | RunModifyRequest | 実行を変更するためのリクエスト詳細。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークンです。 |

### 戻り値

非同期操作を表すタスクです。タスクの結果には実行の変更からのレスポンスが含まれます。

### 例外

| 例外 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | スレッドIDがnullまたは空の場合にスローされます。 |
| [AIClientException](../../aiclientexception/) | run Id が null または空の場合にスローされます。 |

### 関連項目

* class [RunResponse](../../runresponse/)
* class [RunModifyRequest](../../runmodifyrequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


