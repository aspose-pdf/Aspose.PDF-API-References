---
title: IOpenAIClient.CreateAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient メソッド。新しいアシスタントを非同期に作成します
type: docs
weight: 30
url: /ja/net/aspose.pdf.ai/iopenaiclient/createassistantasync/
---
## IOpenAIClient.CreateAssistantAsync メソッド

新しいアシスタントを非同期に作成します。

```csharp
public Task<AssistantResponse> CreateAssistantAsync(AssistantCreateRequest assistantCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| assistantCreateRequest | AssistantCreateRequest | アシスタントを作成するための詳細を含むリクエストオブジェクト。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークン。 |

### 戻り値

非同期操作を表すタスク。タスクの結果にはアシスタント作成からの応答が含まれます。

### 参照

* class [AssistantResponse](../../assistantresponse/)
* class [AssistantCreateRequest](../../assistantcreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)