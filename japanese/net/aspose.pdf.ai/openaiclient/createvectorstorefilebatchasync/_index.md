---
title: OpenAIClient.CreateVectorStoreFileBatchAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient メソッド。新しいベクターストアファイルバッチを非同期で作成します
type: docs
weight: 120
url: /ja/net/aspose.pdf.ai/openaiclient/createvectorstorefilebatchasync/
---
## OpenAIClient.CreateVectorStoreFileBatchAsync メソッド

新しいベクターストアファイルバッチを非同期で作成します。

```csharp
public Task<VectorStoreFileBatchResponse> CreateVectorStoreFileBatchAsync(string vectorStoreId, 
    VectorStoreFileBatchCreateRequest vectorStoreFileCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| vectorStoreId | String | ファイルバッチが作成されるベクターストアの ID。 |
| vectorStoreFileCreateRequest | VectorStoreFileBatchCreateRequest | ファイルバッチを作成するための詳細を含むリクエストオブジェクト。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークン。 |

### 戻り値

非同期操作を表すタスク。タスクの結果には、ファイルバッチ作成からの応答が含まれます。

### 例外

| 例外 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | ベクターストア ID が null または空の場合にスローされます。 |

### 参照

* クラス [VectorStoreFileBatchResponse](../../vectorstorefilebatchresponse/)
* クラス [VectorStoreFileBatchCreateRequest](../../vectorstorefilebatchcreaterequest/)
* クラス [OpenAIClient](../)
* 名前空間 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../../)