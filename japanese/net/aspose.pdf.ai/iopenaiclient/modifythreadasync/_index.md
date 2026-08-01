---
title: "IOpenAIClient.ModifyThreadAsync"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "IOpenAIClient メソッド。既存のスレッドを非同期で変更します。"
type: docs
weight: 380
url: /ja/net/aspose.pdf.ai/iopenaiclient/modifythreadasync/
---
## IOpenAIClient.ModifyThreadAsync method

既存のスレッドを非同期で変更します。

```csharp
public Task<ThreadResponse> ModifyThreadAsync(string threadId, 
    ThreadModifyRequest threadModifyRequest, CancellationToken? cancellationToken = default)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| threadId | String | 変更するスレッドの ID。 |
| threadModifyRequest | ThreadModifyRequest | 変更の詳細を含むリクエスト オブジェクトです。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークンです。 |

### 戻り値

非同期操作を表すタスクです。タスクの結果には、スレッドの変更からの応答が含まれます。

### 例外

| 例外 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | スレッドIDがnullまたは空の場合にスローされます。 |

### 関連項目

* class [ThreadResponse](../../threadresponse/)
* class [ThreadModifyRequest](../../threadmodifyrequest/)
* interface [IOpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


