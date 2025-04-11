---
title: ILlamaClient.CreateCompletionAsync
second_title: Aspose.PDF for .NET API Reference
description: ILlamaClient メソッド。Llama サービスでチャット完了リクエストを作成します。
type: docs
weight: 10
url: /ja/net/aspose.pdf.ai/illamaclient/createcompletionasync/
---
## ILlamaClient.CreateCompletionAsync メソッド

Llama サービスでチャット完了リクエストを作成します。

```csharp
public Task<LlamaChatCompletionResponse> CreateCompletionAsync(
    LlamaChatCompletionRequest chatCompletionRequest, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| chatCompletionRequest | LlamaChatCompletionRequest | チャット完了リクエスト。 |
| cancellationToken | Nullable`1 | キャンセルトークン。 |

### 戻り値

チャット完了レスポンス。

### 参照

* クラス [LlamaChatCompletionResponse](../../llamachatcompletionresponse/)
* クラス [LlamaChatCompletionRequest](../../llamachatcompletionrequest/)
* インターフェース [ILlamaClient](../)
* 名前空間 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../../)