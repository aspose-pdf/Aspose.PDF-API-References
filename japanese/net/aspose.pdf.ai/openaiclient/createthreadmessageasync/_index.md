---
title: OpenAIClient.CreateThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient メソッド。スレッド内に新しいメッセージを非同期で作成します。
type: docs
weight: 80
url: /ja/net/aspose.pdf.ai/openaiclient/createthreadmessageasync/
---
## OpenAIClient.CreateThreadMessageAsync メソッド

スレッド内に新しいメッセージを非同期で作成します。

```csharp
public Task<ThreadMessageResponse> CreateThreadMessageAsync(string threadId, 
    ThreadMessageCreateRequest threadMessageRequest, CancellationToken? cancellationToken = default)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| threadId | String | メッセージが作成されるスレッドの ID。 |
| threadMessageRequest | ThreadMessageCreateRequest | メッセージを作成するためのリクエストの詳細。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークン。 |

### 戻り値

非同期操作を表すタスク。タスクの結果にはメッセージ作成からの応答が含まれます。

### 例外

| 例外 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | スレッド ID が null または空の場合にスローされます。 |

### 参照

* クラス [ThreadMessageResponse](../../threadmessageresponse/)
* クラス [ThreadMessageCreateRequest](../../threadmessagecreaterequest/)
* クラス [OpenAIClient](../)
* 名前空間 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../../)