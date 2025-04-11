---
title: OpenAIClient.GetVectorStoresAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient メソッド。ベクターストアのリストを非同期で取得します
type: docs
weight: 380
url: /ja/net/aspose.pdf.ai/openaiclient/getvectorstoresasync/
---
## OpenAIClient.GetVectorStoresAsync メソッド

ベクターストアのリストを非同期で取得します。

```csharp
public Task<VectorStoreListResponse> GetVectorStoresAsync(
    VectorStoreListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| queryParameters | VectorStoreListQueryParameters | ベクターストアのリストをフィルタリングするためのオプションのクエリパラメーター。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークン。 |

### 戻り値

非同期操作を表すタスク。タスクの結果にはベクターストアのリストが含まれます。

### 参照

* class [VectorStoreListResponse](../../vectorstorelistresponse/)
* class [VectorStoreListQueryParameters](../../vectorstorelistqueryparameters/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)