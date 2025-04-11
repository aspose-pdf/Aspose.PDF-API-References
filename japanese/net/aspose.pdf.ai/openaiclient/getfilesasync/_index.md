---
title: OpenAIClient.GetFilesAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient メソッド。指定された目的に基づいて非同期的にファイルのリストを取得します。
type: docs
weight: 230
url: /ja/net/aspose.pdf.ai/openaiclient/getfilesasync/
---
## OpenAIClient.GetFilesAsync メソッド

指定された目的に基づいて非同期的にファイルのリストを取得します。

```csharp
public Task<FileListResponse> GetFilesAsync(string purpose = null, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| purpose | String | オプション。取得するファイルの目的。null の場合、すべての目的のファイルが取得されます。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークン。 |

### 戻り値

非同期操作を表すタスク。タスクの結果にはファイルのリストが含まれます。

### 参照

* クラス [FileListResponse](../../filelistresponse/)
* クラス [OpenAIClient](../)
* 名前空間 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../../)