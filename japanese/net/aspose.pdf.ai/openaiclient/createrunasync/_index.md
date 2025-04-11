---
title: OpenAIClient.CreateRunAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient メソッド。指定されたスレッド内で非同期に実行を作成します
type: docs
weight: 50
url: /ja/net/aspose.pdf.ai/openaiclient/createrunasync/
---
## OpenAIClient.CreateRunAsync メソッド

指定されたスレッド内で非同期に実行を作成します。

```csharp
public Task<RunResponse> CreateRunAsync(string threadId, RunCreateRequest runCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| threadId | String | 実行が作成されるスレッドの ID。 |
| runCreateRequest | RunCreateRequest | 実行を作成するためのリクエストの詳細。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークン。 |

### 戻り値

非同期操作を表すタスク。タスクの結果には、実行作成からの応答が含まれます。

### 例外

| 例外 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | スレッド ID が null または空の場合にスローされます。 |

### 参照

* クラス [RunResponse](../../runresponse/)
* クラス [RunCreateRequest](../../runcreaterequest/)
* クラス [OpenAIClient](../)
* 名前空間 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../../)