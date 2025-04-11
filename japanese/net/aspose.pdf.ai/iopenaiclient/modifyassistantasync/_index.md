---
title: IOpenAIClient.ModifyAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient メソッド。既存のアシスタントを非同期で修正します
type: docs
weight: 360
url: /ja/net/aspose.pdf.ai/iopenaiclient/modifyassistantasync/
---
## IOpenAIClient.ModifyAssistantAsync メソッド

既存のアシスタントを非同期で修正します。

```csharp
public Task<AssistantResponse> ModifyAssistantAsync(string assistantId, 
    AssistantModifyRequest assistantModifyRequest, CancellationToken? cancellationToken = default)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| assistantId | String | 修正するアシスタントの ID。 |
| assistantModifyRequest | AssistantModifyRequest | 修正の詳細を含むリクエストオブジェクト。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークン。 |

### 戻り値

非同期操作を表すタスク。タスクの結果にはアシスタント修正からの応答が含まれます。

### 例外

| 例外 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | アシスタント ID が null または空の場合にスローされます。 |

### 参照

* クラス [AssistantResponse](../../assistantresponse/)
* クラス [AssistantModifyRequest](../../assistantmodifyrequest/)
* インターフェース [IOpenAIClient](../)
* 名前空間 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../../)