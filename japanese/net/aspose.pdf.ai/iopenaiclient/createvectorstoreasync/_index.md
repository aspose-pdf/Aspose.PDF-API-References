---
title: IOpenAIClient.CreateVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient メソッド。新しいベクターストアを非同期で作成します。
type: docs
weight: 100
url: /ja/net/aspose.pdf.ai/iopenaiclient/createvectorstoreasync/
---
## IOpenAIClient.CreateVectorStoreAsync メソッド

新しいベクターストアを非同期で作成します。

```csharp
public Task<VectorStoreResponse> CreateVectorStoreAsync(
    VectorStoreCreateRequest vectorStoreCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| vectorStoreCreateRequest | VectorStoreCreateRequest | ベクターストアを作成するための詳細を含むリクエストオブジェクト。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークン。 |

### 戻り値

非同期操作を表すタスク。タスクの結果には、ベクターストア作成からの応答が含まれます。

### 参照

* クラス [VectorStoreResponse](../../vectorstoreresponse/)
* クラス [VectorStoreCreateRequest](../../vectorstorecreaterequest/)
* インターフェース [IOpenAIClient](../)
* 名前空間 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../../)