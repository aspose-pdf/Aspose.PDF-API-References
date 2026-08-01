---
title: "IOpenAIClient.GetVectorStoreFileAsync"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "IOpenAIClient メソッド。ベクトルストア内の特定ファイルの詳細を非同期で取得します。"
type: docs
weight: 310
url: /ja/net/aspose.pdf.ai/iopenaiclient/getvectorstorefileasync/
---
## IOpenAIClient.GetVectorStoreFileAsync method

ベクトルストア内の特定のファイルの詳細を非同期で取得します。

```csharp
public Task<VectorStoreFileResponse> GetVectorStoreFileAsync(string vectorStoreId, string fileId, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| vectorStoreId | String | ファイルを含むベクトルストアの ID。 |
| fileId | String | 取得するファイルの ID。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークンです。 |

### 戻り値

非同期操作を表すタスクです。タスクの結果にはファイルの詳細が含まれます。

### 例外

| 例外 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | ベクトルストアの Id が null または空の場合にスローされます。 |
| [AIClientException](../../aiclientexception/) | ファイル ID が null または空の場合にスローされます。 |

### 関連項目

* class [VectorStoreFileResponse](../../vectorstorefileresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


