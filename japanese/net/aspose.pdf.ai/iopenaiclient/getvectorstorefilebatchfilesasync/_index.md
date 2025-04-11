---
title: IOpenAIClient.GetVectorStoreFileBatchFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient メソッド。特定のベクターストアファイルバッチ内のファイルのリストを非同期で取得します
type: docs
weight: 330
url: /ja/net/aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchfilesasync/
---
## IOpenAIClient.GetVectorStoreFileBatchFilesAsync メソッド

特定のベクターストアファイルバッチ内のファイルのリストを非同期で取得します。

```csharp
public Task<VectorStoreFileListResponse> GetVectorStoreFileBatchFilesAsync(string vectorStoreId, 
    string fileBatchId, VectorStoreFileBatchFileListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| vectorStoreId | String | ファイルバッチを含むベクターストアの ID。 |
| fileBatchId | String | ファイルを取得するためのファイルバッチの ID。 |
| queryParameters | VectorStoreFileBatchFileListQueryParameters | ファイルのリストをフィルタリングするためのオプションのクエリパラメーター。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークン。 |

### 戻り値

非同期操作を表すタスク。タスクの結果には、ファイルバッチ内のファイルのリストが含まれます。

### 例外

| 例外 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | ベクターストア ID が null または空の場合にスローされます。 |
| [AIClientException](../../aiclientexception/) | ベクターストアファイルバッチ ID が null または空の場合にスローされます。 |

### 参照

* クラス [VectorStoreFileListResponse](../../vectorstorefilelistresponse/)
* クラス [VectorStoreFileBatchFileListQueryParameters](../../vectorstorefilebatchfilelistqueryparameters/)
* インターフェース [IOpenAIClient](../)
* 名前空間 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../../)