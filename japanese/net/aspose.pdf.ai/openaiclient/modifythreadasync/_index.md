---
title: OpenAIClient.ModifyThreadAsync
second_title: Aspose.PDF for .NET API Reference
description: OpenAIClient メソッド。既存のスレッドを非同期で修正します
type: docs
weight: 410
url: /ja/net/aspose.pdf.ai/openaiclient/modifythreadasync/
---
## OpenAIClient.ModifyThreadAsync メソッド

既存のスレッドを非同期で修正します。

```csharp
public Task<ThreadResponse> ModifyThreadAsync(string threadId, 
    ThreadModifyRequest threadModifyRequest, CancellationToken? cancellationToken = default)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| threadId | String | 修正するスレッドの ID。 |
| threadModifyRequest | ThreadModifyRequest | 修正の詳細を含むリクエストオブジェクト。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークン。 |

### 戻り値

非同期操作を表すタスク。タスクの結果には、スレッド修正からの応答が含まれます。

### 例外

| 例外 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | スレッド ID が null または空の場合にスローされます。 |

### 参照

* クラス [ThreadResponse](../../threadresponse/)
* クラス [ThreadModifyRequest](../../threadmodifyrequest/)
* クラス [OpenAIClient](../)
* 名前空間 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../../)