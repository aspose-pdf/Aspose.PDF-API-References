---
title: "OpenAIClient.GetFilesAsync"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "OpenAIClient メソッド。指定された目的に基づいてファイルのリストを非同期で取得します。"
type: docs
weight: 230
url: /ja/net/aspose.pdf.ai/openaiclient/getfilesasync/
---
## OpenAIClient.GetFilesAsync method

指定された目的に基づいてファイルの一覧を非同期で取得します。

```csharp
public Task<FileListResponse> GetFilesAsync(string purpose = null, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| purpose | String | オプション。取得するファイルの目的です。null の場合、すべての目的のファイルが取得されます。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークンです。 |

### 戻り値

非同期操作を表すタスクです。タスクの結果にはファイルのリストが含まれます。

### 関連項目

* class [FileListResponse](../../filelistresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


