---
title: "OpenAIClient.CreateCompletionAsync"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "OpenAIClient メソッド。新しい completion を非同期に作成します"
type: docs
weight: 40
url: /ja/net/aspose.pdf.ai/openaiclient/createcompletionasync/
---
## OpenAIClient.CreateCompletionAsync method

スレッドとその中の実行を非同期に作成します。

```csharp
public Task<CompletionResponse> CreateCompletionAsync(
    CompletionCreateRequest completionCreateRequest, CancellationToken? cancellationToken = default)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| completionCreateRequest | CompletionCreateRequest | completion 作成の詳細を含むリクエストオブジェクト。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークンです。 |

### 戻り値

非同期操作を表すタスクです。タスクの結果には completion 作成のレスポンスが含まれます。

### 関連項目

* class [CompletionResponse](../../completionresponse/)
* class [CompletionCreateRequest](../../completioncreaterequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


