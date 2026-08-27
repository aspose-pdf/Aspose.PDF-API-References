---
title: "OpenAIClient.CreateThreadAndRunAsync"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "OpenAIClient メソッド。スレッドとその中のランを非同期に作成します。"
type: docs
weight: 60
url: /ja/net/aspose.pdf.ai/openaiclient/createthreadandrunasync/
---
## OpenAIClient.CreateThreadAndRunAsync method

スレッド内に新しいメッセージを非同期に作成します。

```csharp
public Task<RunResponse> CreateThreadAndRunAsync(RunThreadCreateRequest runCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| runCreateRequest | RunThreadCreateRequest | スレッドとランを作成するためのリクエスト詳細。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークンです。 |

### 戻り値

非同期操作を表すタスクです。タスクの結果にはスレッドとランの作成からのレスポンスが含まれます。

### 関連項目

* class [RunResponse](../../runresponse/)
* class [RunThreadCreateRequest](../../runthreadcreaterequest/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


