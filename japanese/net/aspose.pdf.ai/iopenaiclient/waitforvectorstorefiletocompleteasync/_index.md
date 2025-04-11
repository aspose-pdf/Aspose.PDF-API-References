---
title: IOpenAIClient.WaitForVectorStoreFileToCompleteAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient メソッド。特定のベクターストアファイルが非同期で完了するのを待ちます。
type: docs
weight: 460
url: /ja/net/aspose.pdf.ai/iopenaiclient/waitforvectorstorefiletocompleteasync/
---
## IOpenAIClient.WaitForVectorStoreFileToCompleteAsync メソッド

特定のベクターストアファイルが非同期で完了するのを待ちます。

```csharp
public Task<VectorStoreFileResponse> WaitForVectorStoreFileToCompleteAsync(string vectorStoreId, 
    string fileId, CancellationToken? cancellationToken = default)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| vectorStoreId | String | ファイルを含むベクターストアの ID。 |
| fileId | String | 完了するまで監視するファイルの ID。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークン。 |

### 戻り値

非同期操作を表すタスク。タスクの結果にはファイルの最終ステータスが含まれます。

### 例外

| 例外 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | ベクターストア ID が null または空の場合にスローされます。 |
| [AIClientException](../../aiclientexception/) | ファイル ID が null または空の場合にスローされます。 |

### 参照

* クラス [VectorStoreFileResponse](../../vectorstorefileresponse/)
* インターフェース [IOpenAIClient](../)
* 名前空間 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../../)