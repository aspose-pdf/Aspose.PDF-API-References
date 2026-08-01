---
title: "OpenAIClient.CreateThreadMessageAsync"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "OpenAIClient メソッド。スレッド内に新しいメッセージを非同期に作成します"
type: docs
weight: 80
url: /ja/net/aspose.pdf.ai/openaiclient/createthreadmessageasync/
---
## OpenAIClient.CreateThreadMessageAsync method

新しいベクトルストアを非同期に作成します。

```csharp
public Task<ThreadMessageResponse> CreateThreadMessageAsync(string threadId, 
    ThreadMessageCreateRequest threadMessageRequest, CancellationToken? cancellationToken = default)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| threadId | String | メッセージが作成されるスレッドの ID。 |
| threadMessageRequest | ThreadMessageCreateRequest | メッセージ作成のリクエスト詳細。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークンです。 |

### 戻り値

非同期操作を表すタスクです。タスクの結果にはメッセージ作成に対するレスポンスが含まれます。

### 例外

| 例外 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | スレッドIDがnullまたは空の場合にスローされます。 |

### 関連項目

* class [ThreadMessageResponse](../../threadmessageresponse/)
* class [ThreadMessageCreateRequest](../../threadmessagecreaterequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


