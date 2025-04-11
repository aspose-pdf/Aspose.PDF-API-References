---
title: OpenAIClient.DeleteThreadMessageAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient メソッド。スレッド内のメッセージを非同期で削除します
type: docs
weight: 160
url: /ja/net/aspose.pdf.ai/openaiclient/deletethreadmessageasync/
---
## OpenAIClient.DeleteThreadMessageAsync メソッド

スレッド内のメッセージを非同期で削除します。

```csharp
public Task<DeleteStatusResponse> DeleteThreadMessageAsync(string threadId, string threadMessageId, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| threadId | String | 削除するメッセージを含むスレッドの ID。 |
| threadMessageId | String | 削除するメッセージの ID。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークン。 |

### 戻り値

非同期操作を表すタスク。タスクの結果には削除操作のステータスが含まれます。

### 例外

| 例外 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | スレッド ID が null または空の場合にスローされます。 |
| [AIClientException](../../aiclientexception/) | スレッドメッセージ ID が null または空の場合にスローされます。 |

### 参照

* クラス [DeleteStatusResponse](../../deletestatusresponse/)
* クラス [OpenAIClient](../)
* 名前空間 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../../)