---
title: IOpenAIClient.ModifyVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient メソッド。既存のベクターストアを非同期で変更します
type: docs
weight: 400
url: /ja/net/aspose.pdf.ai/iopenaiclient/modifyvectorstoreasync/
---
## IOpenAIClient.ModifyVectorStoreAsync メソッド

既存のベクターストアを非同期で変更します。

```csharp
public Task<VectorStoreResponse> ModifyVectorStoreAsync(string vectorStoreId, 
    VectorStoreModifyRequest vectorStoreModifyRequest, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| vectorStoreId | String | 変更するベクターストアの ID。 |
| vectorStoreModifyRequest | VectorStoreModifyRequest | 変更の詳細を含むリクエストオブジェクト。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークン。 |

### 戻り値

非同期操作を表すタスク。タスクの結果には、ベクターストアの変更からの応答が含まれます。

### 例外

| 例外 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | ベクターストア ID が null または空の場合にスローされます。 |

### 参照

* クラス [VectorStoreResponse](../../vectorstoreresponse/)
* クラス [VectorStoreModifyRequest](../../vectorstoremodifyrequest/)
* インターフェース [IOpenAIClient](../)
* 名前空間 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../../)