---
title: IOpenAIClient.UploadFileAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient メソッド。ファイルを非同期で OpenAI サーバーにアップロードします
type: docs
weight: 420
url: /ja/net/aspose.pdf.ai/iopenaiclient/uploadfileasync/
---
## IOpenAIClient.UploadFileAsync メソッド

ファイルを非同期で OpenAI サーバーにアップロードします。

```csharp
public Task<FileResponse> UploadFileAsync(string purpose, string fileName, byte[] fileBytes, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| purpose | String | ファイルアップロードの目的。通常、ファイルの使用方法を説明します。 |
| fileName | String | アップロードするファイルの名前。 |
| fileBytes | Byte[] | ファイルデータを含むバイト配列。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークン。 |

### 戻り値

非同期操作を表すタスク。タスクの結果にはファイルアップロードからの応答が含まれます。

### 例外

| 例外 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | ファイルの目的が null または空の場合にスローされます。 |
| [AIClientException](../../aiclientexception/) | ファイル名が null または空の場合にスローされます。 |

### 参照

* クラス [FileResponse](../../fileresponse/)
* インターフェース [IOpenAIClient](../)
* 名前空間 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../../)