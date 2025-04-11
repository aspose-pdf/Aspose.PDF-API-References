---
title: IOpenAIClient.ModifyThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient メソッド。スレッド内の既存のメッセージを非同期で修正します。
type: docs
weight: 390
url: /ja/net/aspose.pdf.ai/iopenaiclient/modifythreadmessageasync/
---
## IOpenAIClient.ModifyThreadMessageAsync メソッド

スレッド内の既存のメッセージを非同期で修正します。

```csharp
public Task<ThreadMessageResponse> ModifyThreadMessageAsync(string threadId, 
    string threadMessageId, ThreadMessageModifyRequest threadMessageModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| threadId | String | 修正するメッセージを含むスレッドの ID。 |
| threadMessageId | String | 修正するメッセージの ID。 |
| threadMessageModifyRequest | ThreadMessageModifyRequest | メッセージを修正するためのリクエストの詳細。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークン。 |

### 戻り値

非同期操作を表すタスク。タスクの結果には、メッセージ修正からの応答が含まれます。

### 例外

| 例外 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | スレッド ID が null または空の場合にスローされます。 |
| [AIClientException](../../aiclientexception/) | スレッドメッセージ ID が null または空の場合にスローされます。 |

### 参照

* クラス [ThreadMessageResponse](../../threadmessageresponse/)
* クラス [ThreadMessageModifyRequest](../../threadmessagemodifyrequest/)
* インターフェース [IOpenAIClient](../)
* 名前空間 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../../)