---
title: IOpenAIClient.DeleteVectorStoreAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient メソッド。ベクトルストアを非同期で削除します
type: docs
weight: 170
url: /ja/net/aspose.pdf.ai/iopenaiclient/deletevectorstoreasync/
---
## IOpenAIClient.DeleteVectorStoreAsync メソッド

ベクトルストアを非同期で削除します。

```csharp
public Task<DeleteStatusResponse> DeleteVectorStoreAsync(string vectorStoreId, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| vectorStoreId | String | 削除するベクトルストアの ID。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークン。 |

### 戻り値

非同期操作を表すタスク。タスクの結果には削除操作のステータスが含まれます。

### 例外

| 例外 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | ベクトルストア ID が null または空の場合にスローされます。 |

### 参照

* クラス [DeleteStatusResponse](../../deletestatusresponse/)
* インターフェース [IOpenAIClient](../)
* 名前空間 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../../)