---
title: "OpenAIClient.CreateVectorStoreAndWaitToCompleteAsync"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "OpenAIClient メソッド。新しいベクトルストアを作成し、非同期で完了するのを待機します。"
type: docs
weight: 90
url: /ja/net/aspose.pdf.ai/openaiclient/createvectorstoreandwaittocompleteasync/
---
## OpenAIClient.CreateVectorStoreAndWaitToCompleteAsync method

新しいベクトルストアファイルを非同期に作成します。

```csharp
public Task<VectorStoreResponse> CreateVectorStoreAndWaitToCompleteAsync(
    VectorStoreCreateRequest vectorStoreCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| vectorStoreCreateRequest | VectorStoreCreateRequest | ベクトルストア作成の詳細を含むリクエストオブジェクト。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークンです。 |

### 戻り値

非同期操作を表すタスクです。タスクの結果には、完了後のベクトルストア作成からの応答が含まれます。

### 関連項目

* class [VectorStoreResponse](../../vectorstoreresponse/)
* class [VectorStoreCreateRequest](../../vectorstorecreaterequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


