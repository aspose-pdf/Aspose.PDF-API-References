---
title: "OpenAIClient.CreateVectorStoreFileBatchAsync"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "OpenAIClient メソッド。ベクトルストアのファイルバッチを新規に非同期で作成します"
type: docs
weight: 120
url: /ja/net/aspose.pdf.ai/openaiclient/createvectorstorefilebatchasync/
---
## OpenAIClient.CreateVectorStoreFileBatchAsync method

特定のファイルを非同期に削除します。

```csharp
public Task<VectorStoreFileBatchResponse> CreateVectorStoreFileBatchAsync(string vectorStoreId, 
    VectorStoreFileBatchCreateRequest vectorStoreFileCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| vectorStoreId | String | ファイルバッチが作成されるベクトルストアの ID。 |
| vectorStoreFileCreateRequest | VectorStoreFileBatchCreateRequest | ファイルバッチ作成の詳細を含むリクエストオブジェクト。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークンです。 |

### 戻り値

非同期操作を表すタスク。タスクの結果にはファイルバッチ作成のレスポンスが含まれます。

### 例外

| 例外 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | ベクトルストアの Id が null または空の場合にスローされます。 |

### 関連項目

* class [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* class [VectorStoreFileBatchCreateRequest](../../vectorstorefilebatchcreaterequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


