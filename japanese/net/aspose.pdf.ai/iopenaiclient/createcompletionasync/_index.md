---
title: IOpenAIClient.CreateCompletionAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient メソッド。非同期で新しい補完を作成します
type: docs
weight: 40
url: /ja/net/aspose.pdf.ai/iopenaiclient/createcompletionasync/
---
## IOpenAIClient.CreateCompletionAsync メソッド

非同期で新しい補完を作成します。

```csharp
public Task<CompletionResponse> CreateCompletionAsync(
    CompletionCreateRequest completionCreateRequest, CancellationToken? cancellationToken = default)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| completionCreateRequest | CompletionCreateRequest | 補完を作成するための詳細を含むリクエストオブジェクト。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークン。 |

### 戻り値

非同期操作を表すタスク。タスクの結果には、補完作成からの応答が含まれます。

### 参照

* クラス [CompletionResponse](../../completionresponse/)
* クラス [CompletionCreateRequest](../../completioncreaterequest/)
* インターフェース [IOpenAIClient](../)
* 名前空間 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../../)