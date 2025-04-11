---
title: IOpenAIClient.GetAssistantsAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient メソッド。アシスタントのリストを非同期で取得します
type: docs
weight: 200
url: /ja/net/aspose.pdf.ai/iopenaiclient/getassistantsasync/
---
## IOpenAIClient.GetAssistantsAsync メソッド

アシスタントのリストを非同期で取得します。

```csharp
public Task<AssistantListResponse> GetAssistantsAsync(
    AssistantListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| queryParameters | AssistantListQueryParameters | アシスタントのリストをフィルタリングするためのオプションのクエリパラメーター。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークン。 |

### 戻り値

非同期操作を表すタスク。タスクの結果にはアシスタントのリストが含まれます。

### 参照

* クラス [AssistantListResponse](../../assistantlistresponse/)
* クラス [AssistantListQueryParameters](../../assistantlistqueryparameters/)
* インターフェース [IOpenAIClient](../)
* 名前空間 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../../)