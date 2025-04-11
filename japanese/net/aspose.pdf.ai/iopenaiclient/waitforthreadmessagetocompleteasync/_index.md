---
title: IOpenAIClient.WaitForThreadMessageToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient メソッド。特定のスレッドメッセージが非同期に完了するのを待ちます
type: docs
weight: 450
url: /ja/net/aspose.pdf.ai/iopenaiclient/waitforthreadmessagetocompleteasync/
---
## IOpenAIClient.WaitForThreadMessageToCompleteAsync メソッド

特定のスレッドメッセージが非同期に完了するのを待ちます。

```csharp
public Task<ThreadMessageResponse> WaitForThreadMessageToCompleteAsync(string threadId, 
    string threadMessageId, CancellationToken? cancellationToken = default)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| threadId | String | メッセージを含むスレッドの ID。 |
| threadMessageId | String | 完了するまで監視するメッセージの ID。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークン。 |

### 戻り値

非同期操作を表すタスク。タスクの結果にはメッセージの最終状態が含まれます。

### 例外

| 例外 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | スレッド ID が null または空の場合にスローされます。 |
| [AIClientException](../../aiclientexception/) | スレッドメッセージ ID が null または空の場合にスローされます。 |

### 参照

* クラス [ThreadMessageResponse](../../threadmessageresponse/)
* インターフェース [IOpenAIClient](../)
* 名前空間 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../../)