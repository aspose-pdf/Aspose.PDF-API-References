---
title: OpenAIClient.CreateAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient メソッド。非同期で新しいアシスタントを作成します。
type: docs
weight: 30
url: /ja/net/aspose.pdf.ai/openaiclient/createassistantasync/
---
## OpenAIClient.CreateAssistantAsync メソッド

非同期で新しいアシスタントを作成します。

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

* クラス [AssistantResponse](../../assistantresponse/)
* クラス [AssistantCreateRequest](../../assistantcreaterequest/)
* クラス [OpenAIClient](../)
* 名前空間 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../../)