---
title: "IOpenAIClient.GetAssistantsAsync"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "IOpenAIClient メソッド。アシスタントの一覧を非同期で取得します"
type: docs
weight: 200
url: /ja/net/aspose.pdf.ai/iopenaiclient/getassistantsasync/
---
## IOpenAIClient.GetAssistantsAsync method

アシスタントの一覧を非同期で取得します。

```csharp
public Task<AssistantListResponse> GetAssistantsAsync(
    AssistantListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| queryParameters | AssistantListQueryParameters | アシスタントのリストをフィルタリングするためのオプションのクエリパラメータ。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークンです。 |

### 戻り値

非同期操作を表すタスクです。タスクの結果にはアシスタントのリストが含まれます。

### 関連項目

* class [AssistantListResponse](../../assistantlistresponse/)
* class [AssistantListQueryParameters](../../assistantlistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


