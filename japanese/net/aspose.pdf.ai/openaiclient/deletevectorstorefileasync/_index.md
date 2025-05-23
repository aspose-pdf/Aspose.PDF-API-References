---
title: OpenAIClient.DeleteVectorStoreFileAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient メソッド。ベクターストア内のファイルを非同期で削除します
type: docs
weight: 180
url: /ja/net/aspose.pdf.ai/openaiclient/deletevectorstorefileasync/
---
## OpenAIClient.DeleteVectorStoreFileAsync メソッド

ベクターストア内のファイルを非同期で削除します。

```csharp
public Task<DeleteStatusResponse> DeleteVectorStoreFileAsync(string vectorStoreId, string fileId, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| vectorStoreId | String | 削除するファイルを含むベクターストアの ID。 |
| fileId | String | 削除するファイルの ID。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークン。 |

### 戻り値

非同期操作を表すタスク。タスクの結果には削除操作のステータスが含まれます。

### 例外

| 例外 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | ベクターストア ID が null または空の場合にスローされます。 |
| [AIClientException](../../aiclientexception/) | ファイル ID が null または空の場合にスローされます。 |

### 参照

* クラス [DeleteStatusResponse](../../deletestatusresponse/)
* クラス [OpenAIClient](../)
* 名前空間 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../../)