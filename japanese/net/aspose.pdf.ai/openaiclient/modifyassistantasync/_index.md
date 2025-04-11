---
title: OpenAIClient.ModifyAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient メソッド。既存のアシスタントを非同期で変更します
type: docs
weight: 390
url: /ja/net/aspose.pdf.ai/openaiclient/modifyassistantasync/
---
## OpenAIClient.ModifyAssistantAsync メソッド

既存のアシスタントを非同期で変更します。

```csharp
public Task<AssistantResponse> ModifyAssistantAsync(string assistantId, 
    AssistantModifyRequest assistantModifyRequest, CancellationToken? cancellationToken = default)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| assistantId | String | 変更するアシスタントの ID。 |
| assistantModifyRequest | AssistantModifyRequest | 変更の詳細を含むリクエストオブジェクト。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークン。 |

### 戻り値

非同期操作を表すタスク。タスクの結果にはアシスタント変更からの応答が含まれます。

### 例外

| 例外 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | アシスタント ID が null または空の場合にスローされます。 |

### 参照

* クラス [AssistantResponse](../../assistantresponse/)
* クラス [AssistantModifyRequest](../../assistantmodifyrequest/)
* クラス [OpenAIClient](../)
* 名前空間 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../../)