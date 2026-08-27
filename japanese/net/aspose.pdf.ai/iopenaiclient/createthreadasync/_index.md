---
title: "IOpenAIClient.CreateThreadAsync"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "IOpenAIClient メソッド。新しいスレッドを非同期で作成します"
type: docs
weight: 70
url: /ja/net/aspose.pdf.ai/iopenaiclient/createthreadasync/
---
## IOpenAIClient.CreateThreadAsync method

新しいベクトルストアを作成し、完了するまで非同期で待機します。

```csharp
public Task<ThreadResponse> CreateThreadAsync(ThreadCreateRequest threadCreateRequest, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| threadCreateRequest | ThreadCreateRequest | スレッド作成の詳細を含むリクエストオブジェクトです。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークンです。 |

### 戻り値

非同期操作を表すタスクです。タスクの結果にはスレッド作成のレスポンスが含まれます。

### 関連項目

* class [ThreadResponse](../../threadresponse/)
* class [ThreadCreateRequest](../../threadcreaterequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


