---
title: OpenAIClient.CreateVectorStoreAndWaitToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient メソッド。新しいベクターストアを作成し、非同期で完了するのを待ちます
type: docs
weight: 90
url: /ja/net/aspose.pdf.ai/openaiclient/createvectorstoreandwaittocompleteasync/
---
## OpenAIClient.CreateVectorStoreAndWaitToCompleteAsync メソッド

新しいベクターストアを作成し、非同期で完了するのを待ちます。

```csharp
public Task<VectorStoreResponse> CreateVectorStoreAndWaitToCompleteAsync(
    VectorStoreCreateRequest vectorStoreCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| vectorStoreCreateRequest | VectorStoreCreateRequest | ベクターストアを作成するための詳細を含むリクエストオブジェクト。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークン。 |

### 戻り値

非同期操作を表すタスク。タスクの結果には、完了後のベクターストア作成からの応答が含まれます。

### 参照

* クラス [VectorStoreResponse](../../vectorstoreresponse/)
* クラス [VectorStoreCreateRequest](../../vectorstorecreaterequest/)
* クラス [OpenAIClient](../)
* 名前空間 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../../)