---
title: OpenAIClient.GetThreadMessagesAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient メソッド。特定のスレッドのメッセージのリストを非同期で取得します。
type: docs
weight: 320
url: /ja/net/aspose.pdf.ai/openaiclient/getthreadmessagesasync/
---
## OpenAIClient.GetThreadMessagesAsync メソッド

特定のスレッドのメッセージのリストを非同期で取得します。

```csharp
public Task<ThreadMessageListResponse> GetThreadMessagesAsync(string threadId, 
    ThreadMessageListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| threadId | String | メッセージを取得するスレッドの ID。 |
| queryParameters | ThreadMessageListQueryParameters | メッセージのリストをフィルタリングするためのオプションのクエリパラメーター。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークン。 |

### 戻り値

非同期操作を表すタスク。タスクの結果にはスレッドメッセージのリストが含まれます。

### 例外

| 例外 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | スレッド ID が null または空の場合にスローされます。 |

### 参照

* クラス [ThreadMessageListResponse](../../threadmessagelistresponse/)
* クラス [ThreadMessageListQueryParameters](../../threadmessagelistqueryparameters/)
* クラス [OpenAIClient](../)
* 名前空間 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../../)