---
title: "OpenAIClient.CreateVectorStoreFileAsync"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "OpenAIClient メソッド。新しいベクトルストアファイルを非同期に作成します"
type: docs
weight: 110
url: /ja/net/aspose.pdf.ai/openaiclient/createvectorstorefileasync/
---
## OpenAIClient.CreateVectorStoreFileAsync method

既存のアシスタントを非同期に削除します。

```csharp
public Task<VectorStoreFileResponse> CreateVectorStoreFileAsync(string vectorStoreId, 
    VectorStoreFileCreateRequest vectorStoreFileCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| vectorStoreId | String | ファイルが作成されるベクトルストアの ID。 |
| vectorStoreFileCreateRequest | VectorStoreFileCreateRequest | ファイル作成の詳細を含むリクエストオブジェクト。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークンです。 |

### 戻り値

非同期操作を表すタスクです。タスクの結果にはファイル作成のレスポンスが含まれます。

### 例外

| 例外 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | ベクトルストアの Id が null または空の場合にスローされます。 |

### 関連項目

* class [VectorStoreFileResponse](../../vectorstorefileresponse/)
* class [VectorStoreFileCreateRequest](../../vectorstorefilecreaterequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


