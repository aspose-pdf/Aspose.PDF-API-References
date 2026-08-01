---
title: "OpenAIClient.RunAndGetAssistantResponseAsync"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "OpenAIClient メソッド。指定された threadId と runCreateRequest でアシスタントを実行し、アシスタントの応答を非同期で取得します"
type: docs
weight: 450
url: /ja/net/aspose.pdf.ai/openaiclient/runandgetassistantresponseasync/
---
## OpenAIClient.RunAndGetAssistantResponseAsync method

指定された threadId と runCreateRequest を使用してアシスタントを実行し、非同期でアシスタントの応答を取得します。

```csharp
public Task<string> RunAndGetAssistantResponseAsync(string threadId, 
    RunCreateRequest runCreateRequest, CancellationToken? cancellationToken)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| threadId | String | スレッドのID。 |
| runCreateRequest | RunCreateRequest | 実行作成リクエスト。 |
| cancellationToken | Nullable`1 | キャンセルトークン（オプション）。 |

### 戻り値

アシスタント応答文字列を伴う非同期操作を表すタスクです。

### 関連項目

* class [RunCreateRequest](../../runcreaterequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


