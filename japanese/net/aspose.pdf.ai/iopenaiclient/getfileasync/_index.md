---
title: IOpenAIClient.GetFileAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient メソッド。特定のファイルの詳細を非同期で取得します
type: docs
weight: 210
url: /ja/net/aspose.pdf.ai/iopenaiclient/getfileasync/
---
## IOpenAIClient.GetFileAsync メソッド

特定のファイルの詳細を非同期で取得します。

```csharp
public Task<FileResponse> GetFileAsync(string fileId, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileId | String | 取得するファイルの ID。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークン。 |

### 戻り値

非同期操作を表すタスク。タスクの結果にはファイルの詳細が含まれます。

### 例外

| 例外 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | ファイル ID が null または空の場合にスローされます。 |

### 参照

* クラス [FileResponse](../../fileresponse/)
* インターフェース [IOpenAIClient](../)
* 名前空間 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../../)