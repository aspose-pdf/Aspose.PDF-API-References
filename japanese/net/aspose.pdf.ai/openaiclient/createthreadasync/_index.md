---
title: OpenAIClient.CreateThreadAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient メソッド。新しいスレッドを非同期に作成します
type: docs
weight: 70
url: /ja/net/aspose.pdf.ai/openaiclient/createthreadasync/
---
## OpenAIClient.CreateThreadAsync メソッド

新しいスレッドを非同期に作成します。

```csharp
public Task<ThreadResponse> CreateThreadAsync(ThreadCreateRequest threadCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| threadCreateRequest | ThreadCreateRequest | スレッドを作成するための詳細を含むリクエストオブジェクト。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークン。 |

### 戻り値

非同期操作を表すタスク。タスクの結果には、スレッド作成からの応答が含まれます。

### 参照

* クラス [ThreadResponse](../../threadresponse/)
* クラス [ThreadCreateRequest](../../threadcreaterequest/)
* クラス [OpenAIClient](../)
* 名前空間 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../../)