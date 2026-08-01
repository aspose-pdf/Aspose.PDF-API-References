---
title: "OpenAIClient.WaitForAssistantMessageAsync"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "OpenAIClient メソッド。スレッド内でアシスタントからの最初のメッセージを非同期で待機します。"
type: docs
weight: 470
url: /ja/net/aspose.pdf.ai/openaiclient/waitforassistantmessageasync/
---
## OpenAIClient.WaitForAssistantMessageAsync method

スレッド内でアシスタントからの最初のメッセージを非同期で待機します。

```csharp
public Task<ThreadMessageResponse> WaitForAssistantMessageAsync(string threadId, 
    ThreadMessageListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| threadId | String | 最初のアシスタントメッセージを監視するスレッドの ID です。 |
| queryParameters | ThreadMessageListQueryParameters | メッセージ一覧をフィルタリングするためのオプションのクエリ パラメータです。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークンです。 |

### 戻り値

非同期操作を表すタスクです。タスクの結果にはスレッド内の最初のアシスタントメッセージが含まれます。

### 例外

| 例外 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | スレッドIDがnullまたは空の場合にスローされます。 |

### 関連項目

* class [ThreadMessageResponse](../../threadmessageresponse/)
* class [ThreadMessageListQueryParameters](../../threadmessagelistqueryparameters/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


