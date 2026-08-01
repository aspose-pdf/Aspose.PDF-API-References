---
title: "IOpenAIClient.CreateVectorStoreAsync"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "IOpenAIClient メソッド。新しいベクトルストアを非同期で作成します"
type: docs
weight: 100
url: /ja/net/aspose.pdf.ai/iopenaiclient/createvectorstoreasync/
---
## IOpenAIClient.CreateVectorStoreAsync method

新しいベクトルストアファイルバッチを非同期に作成します。

```csharp
public Task<VectorStoreResponse> CreateVectorStoreAsync(
    VectorStoreCreateRequest vectorStoreCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| vectorStoreCreateRequest | VectorStoreCreateRequest | ベクトルストア作成の詳細を含むリクエストオブジェクト。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークンです。 |

### 戻り値

非同期操作を表すタスクです。タスクの結果にはベクトルストア作成からのレスポンスが含まれます。

### 関連項目

* class [VectorStoreResponse](../../vectorstoreresponse/)
* class [VectorStoreCreateRequest](../../vectorstorecreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


