---
title: OpenAIClient.RunAndGetAssistantResponseAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient メソッド。指定された threadId と runCreateRequest でアシスタントを実行し、非同期的にアシスタントの応答を取得します。
type: docs
weight: 440
url: /ja/net/aspose.pdf.ai/openaiclient/runandgetassistantresponseasync/
---
## OpenAIClient.RunAndGetAssistantResponseAsync メソッド

指定された threadId と runCreateRequest でアシスタントを実行し、非同期的にアシスタントの応答を取得します。

```csharp
public Task<string> RunAndGetAssistantResponseAsync(string threadId, 
    RunCreateRequest runCreateRequest, CancellationToken? cancellationToken)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| threadId | String | スレッドの ID。 |
| runCreateRequest | RunCreateRequest | 実行作成リクエスト。 |
| cancellationToken | Nullable`1 | キャンセルトークン（オプション）。 |

### 戻り値

アシスタントの応答文字列を持つ非同期操作を表すタスク。

### 参照

* クラス [RunCreateRequest](../../runcreaterequest/)
* クラス [OpenAIClient](../)
* 名前空間 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../../)