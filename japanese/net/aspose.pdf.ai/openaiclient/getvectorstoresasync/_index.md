---
title: "OpenAIClient.GetVectorStoresAsync"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "OpenAIClient メソッド。ベクトルストアの一覧を非同期で取得します"
type: docs
weight: 390
url: /ja/net/aspose.pdf.ai/openaiclient/getvectorstoresasync/
---
## OpenAIClient.GetVectorStoresAsync method

ベクトルストアの一覧を非同期で取得します。

```csharp
public Task<VectorStoreListResponse> GetVectorStoresAsync(
    VectorStoreListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| queryParameters | VectorStoreListQueryParameters | ベクトルストアの一覧をフィルタリングするためのオプションのクエリパラメータ。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークンです。 |

### 戻り値

非同期操作を表すタスク。タスクの結果にはベクトルストアの一覧が含まれます。

### 関連項目

* class [VectorStoreListResponse](../../vectorstorelistresponse/)
* class [VectorStoreListQueryParameters](../../vectorstorelistqueryparameters/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


