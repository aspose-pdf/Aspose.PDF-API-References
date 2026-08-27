---
title: "IOpenAIClient.RunAndGetAssistantResponseAsync"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "IOpenAIClient メソッド。指定された threadId と runCreateRequest を使用してアシスタントを実行し、非同期でアシスタントの応答を取得します"
type: docs
weight: 410
url: /ja/net/aspose.pdf.ai/iopenaiclient/runandgetassistantresponseasync/
---
## IOpenAIClient.RunAndGetAssistantResponseAsync method

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
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


