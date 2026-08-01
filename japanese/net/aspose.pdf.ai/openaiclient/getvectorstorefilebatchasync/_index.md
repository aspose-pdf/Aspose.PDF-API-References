---
title: "OpenAIClient.GetVectorStoreFileBatchAsync"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "OpenAIClient メソッド。特定のベクトルストア ファイルバッチの詳細を非同期で取得します"
type: docs
weight: 360
url: /ja/net/aspose.pdf.ai/openaiclient/getvectorstorefilebatchasync/
---
## OpenAIClient.GetVectorStoreFileBatchAsync method

特定のベクトルストアファイルバッチの詳細を非同期で取得します。

```csharp
public Task<VectorStoreFileBatchResponse> GetVectorStoreFileBatchAsync(string vectorStoreId, 
    string fileBatchId, CancellationToken? cancellationToken = default)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| vectorStoreId | String | ファイルバッチを含むベクトルストアの ID。 |
| fileBatchId | String | 取得するファイルバッチの ID。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークンです。 |

### 戻り値

非同期操作を表すタスク。タスクの結果にはファイルバッチの詳細が含まれます。

### 例外

| 例外 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | ベクトルストアの Id が null または空の場合にスローされます。 |
| [AIClientException](../../aiclientexception/) | ベクトルストア ファイルバッチ ID が null または空の場合にスローされます。 |

### 関連項目

* class [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


