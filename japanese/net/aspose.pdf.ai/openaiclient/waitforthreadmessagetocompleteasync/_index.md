---
title: "OpenAIClient.WaitForThreadMessageToCompleteAsync"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "OpenAIClient メソッド。特定のスレッドメッセージが非同期に完了するのを待機します。"
type: docs
weight: 490
url: /ja/net/aspose.pdf.ai/openaiclient/waitforthreadmessagetocompleteasync/
---
## OpenAIClient.WaitForThreadMessageToCompleteAsync method

特定のスレッドメッセージが完了するのを非同期で待機します。

```csharp
public Task<ThreadMessageResponse> WaitForThreadMessageToCompleteAsync(string threadId, 
    string threadMessageId, CancellationToken? cancellationToken = default)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| threadId | String | メッセージを含むスレッドの ID です。 |
| threadMessageId | String | 完了まで監視するメッセージの ID です。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークンです。 |

### 戻り値

非同期操作を表すタスクです。タスクの結果にはメッセージの最終ステータスが含まれます。

### 例外

| 例外 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | スレッドIDがnullまたは空の場合にスローされます。 |
| [AIClientException](../../aiclientexception/) | thread message Id が null または空の場合にスローされます。 |

### 関連項目

* class [ThreadMessageResponse](../../threadmessageresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


