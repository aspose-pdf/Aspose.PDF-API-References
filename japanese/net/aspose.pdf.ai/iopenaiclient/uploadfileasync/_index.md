---
title: "IOpenAIClient.UploadFileAsync"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "IOpenAIClient メソッド。ファイルを非同期で OpenAI サーバーにアップロードします"
type: docs
weight: 420
url: /ja/net/aspose.pdf.ai/iopenaiclient/uploadfileasync/
---
## IOpenAIClient.UploadFileAsync method

ファイルを非同期で OpenAI サーバーにアップロードします。

```csharp
public Task<FileResponse> UploadFileAsync(string purpose, string fileName, byte[] fileBytes, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| purpose | String | ファイルアップロードの目的で、通常はファイルの使用方法を説明します。 |
| fileName | String | アップロードするファイルの名前。 |
| fileBytes | Byte[] | ファイルデータを含むバイト配列。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークンです。 |

### 戻り値

非同期操作を表すタスクです。タスクの結果にはファイルアップロードのレスポンスが含まれます。

### 例外

| 例外 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | ファイルの目的が null または空の場合にスローされます。 |
| [AIClientException](../../aiclientexception/) | ファイル名が null または空の場合にスローされます。 |

### 関連項目

* class [FileResponse](../../fileresponse/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


