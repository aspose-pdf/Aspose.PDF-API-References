---
title: "IOpenAIClient.GetVectorStoreFileBatchFilesAsync"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "IOpenAIClient メソッド。特定のベクトルストアファイルバッチ内のファイル一覧を非同期で取得します"
type: docs
weight: 330
url: /ja/net/aspose.pdf.ai/iopenaiclient/getvectorstorefilebatchfilesasync/
---
## IOpenAIClient.GetVectorStoreFileBatchFilesAsync method

特定のベクトルストアファイルバッチ内のファイル一覧を非同期で取得します。

```csharp
public Task<VectorStoreFileListResponse> GetVectorStoreFileBatchFilesAsync(string vectorStoreId, 
    string fileBatchId, VectorStoreFileBatchFileListQueryParameters queryParameters = null, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| vectorStoreId | String | ファイルバッチを含むベクトルストアの ID。 |
| fileBatchId | String | ファイルを取得するファイルバッチのID。 |
| queryParameters | VectorStoreFileBatchFileListQueryParameters | ファイル一覧をフィルタリングするためのオプションのクエリ パラメータ。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークンです。 |

### 戻り値

非同期操作を表すタスクです。タスクの結果にはファイルバッチ内のファイル一覧が含まれます。

### 例外

| 例外 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | ベクトルストアの Id が null または空の場合にスローされます。 |
| [AIClientException](../../aiclientexception/) | ベクトルストア ファイルバッチ ID が null または空の場合にスローされます。 |

### 関連項目

* class [VectorStoreFileListResponse](../../vectorstorefilelistresponse/)
* class [VectorStoreFileBatchFileListQueryParameters](../../vectorstorefilebatchfilelistqueryparameters/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


