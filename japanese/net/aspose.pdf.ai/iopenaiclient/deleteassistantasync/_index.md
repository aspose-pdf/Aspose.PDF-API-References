---
title: IOpenAIClient.DeleteAssistantAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient メソッド。既存のアシスタントを非同期に削除します
type: docs
weight: 130
url: /ja/net/aspose.pdf.ai/iopenaiclient/deleteassistantasync/
---
## IOpenAIClient.DeleteAssistantAsync メソッド

既存のアシスタントを非同期に削除します。

```csharp
public Task<DeleteStatusResponse> DeleteAssistantAsync(string assistantId, 
    CancellationToken? cancellationToken = default)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| assistantId | String | 削除するアシスタントの ID。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークン。 |

### 戻り値

非同期操作を表すタスク。タスクの結果には削除操作のステータスが含まれます。

### 例外

| 例外 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | アシスタント ID が null または空の場合にスローされます。 |

### 参照

* クラス [DeleteStatusResponse](../../deletestatusresponse/)
* インターフェース [IOpenAIClient](../)
* 名前空間 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../../)