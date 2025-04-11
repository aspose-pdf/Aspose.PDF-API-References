---
title: OpenAIClient.CreateThreadAndRunAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient メソッド。スレッドを作成し、その中で非同期に実行します。
type: docs
weight: 60
url: /ja/net/aspose.pdf.ai/openaiclient/createthreadandrunasync/
---
## OpenAIClient.CreateThreadAndRunAsync メソッド

スレッドを作成し、その中で非同期に実行します。

```csharp
public Task<RunResponse> CreateThreadAndRunAsync(RunThreadCreateRequest runCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| runCreateRequest | RunThreadCreateRequest | スレッドと実行を作成するためのリクエストの詳細。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークン。 |

### 戻り値

非同期操作を表すタスク。タスクの結果には、スレッドと実行の作成からの応答が含まれます。

### 参照

* クラス [RunResponse](../../runresponse/)
* クラス [RunThreadCreateRequest](../../runthreadcreaterequest/)
* クラス [OpenAIClient](../)
* 名前空間 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../../)