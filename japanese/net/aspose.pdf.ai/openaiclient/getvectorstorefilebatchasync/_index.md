---
title: OpenAIClient.GetVectorStoreFileBatchAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient メソッド。特定のベクターストアファイルバッチの詳細を非同期で取得します。
type: docs
weight: 350
url: /ja/net/aspose.pdf.ai/openaiclient/getvectorstorefilebatchasync/
---
## OpenAIClient.GetVectorStoreFileBatchAsync メソッド

特定のベクターストアファイルバッチの詳細を非同期で取得します。

```csharp
public Task<VectorStoreFileBatchResponse> GetVectorStoreFileBatchAsync(string vectorStoreId, 
    string fileBatchId, CancellationToken? cancellationToken = default)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| vectorStoreId | String | ファイルバッチを含むベクターストアの ID。 |
| fileBatchId | String | 取得するファイルバッチの ID。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークン。 |

### 戻り値

非同期操作を表すタスク。タスクの結果にはファイルバッチの詳細が含まれます。

### 例外

| 例外 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | ベクターストア ID が null または空の場合にスローされます。 |
| [AIClientException](../../aiclientexception/) | ベクターストアファイルバッチ ID が null または空の場合にスローされます。 |

### 参照

* クラス [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* クラス [OpenAIClient](../)
* 名前空間 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../../)