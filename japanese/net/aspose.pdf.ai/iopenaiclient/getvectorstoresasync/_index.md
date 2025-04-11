---
title: IOpenAIClient.GetVectorStoresAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient メソッド。ベクターストアのリストを非同期で取得します
type: docs
weight: 350
url: /ja/net/aspose.pdf.ai/iopenaiclient/getvectorstoresasync/
---
## IOpenAIClient.GetVectorStoresAsync メソッド

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

* クラス [VectorStoreListResponse](../../vectorstorelistresponse/)
* クラス [VectorStoreListQueryParameters](../../vectorstorelistqueryparameters/)
* インターフェース [IOpenAIClient](../)
* 名前空間 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../../)