---
title: "OpenAIClient.ModifyThreadMessageAsync"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "OpenAIClient メソッド。スレッド内の既存メッセージを非同期に変更します。"
type: docs
weight: 430
url: /ja/net/aspose.pdf.ai/openaiclient/modifythreadmessageasync/
---
## OpenAIClient.ModifyThreadMessageAsync method

スレッド内の既存のメッセージを非同期で変更します。

```csharp
public Task<ThreadMessageResponse> ModifyThreadMessageAsync(string threadId, 
    string threadMessageId, ThreadMessageModifyRequest threadMessageModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| threadId | String | 変更するメッセージを含むスレッドの ID。 |
| threadMessageId | String | 変更するメッセージの ID。 |
| threadMessageModifyRequest | ThreadMessageModifyRequest | メッセージを変更するためのリクエスト詳細。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークンです。 |

### 戻り値

非同期操作を表すタスクです。タスクの結果には、メッセージの変更からの応答が含まれます。

### 例外

| 例外 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | スレッドIDがnullまたは空の場合にスローされます。 |
| [AIClientException](../../aiclientexception/) | thread message Id が null または空の場合にスローされます。 |

### 関連項目

* class [ThreadMessageResponse](../../threadmessageresponse/)
* class [ThreadMessageModifyRequest](../../threadmessagemodifyrequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


