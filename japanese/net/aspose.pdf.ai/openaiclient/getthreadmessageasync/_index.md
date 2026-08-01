---
title: "OpenAIClient.GetThreadMessageAsync"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "OpenAIClient メソッド。スレッド内の特定のメッセージの詳細を非同期で取得します"
type: docs
weight: 320
url: /ja/net/aspose.pdf.ai/openaiclient/getthreadmessageasync/
---
## OpenAIClient.GetThreadMessageAsync method

スレッド内の特定のメッセージの詳細を非同期で取得します。

```csharp
public Task<ThreadMessageResponse> GetThreadMessageAsync(string threadId, string threadMessageId, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| threadId | String | メッセージを含むスレッドの ID です。 |
| threadMessageId | String | 取得するメッセージのID。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークンです。 |

### 戻り値

非同期操作を表すタスクです。タスクの結果にはスレッドメッセージの詳細が含まれます。

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


