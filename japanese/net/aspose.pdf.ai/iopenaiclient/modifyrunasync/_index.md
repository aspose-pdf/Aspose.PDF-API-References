---
title: IOpenAIClient.ModifyRunAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient メソッド。スレッド内の既存の実行を非同期で修正します
type: docs
weight: 370
url: /ja/net/aspose.pdf.ai/iopenaiclient/modifyrunasync/
---
## IOpenAIClient.ModifyRunAsync メソッド

スレッド内の既存の実行を非同期で修正します。

```csharp
public Task<RunResponse> ModifyRunAsync(string threadId, string runId, 
    RunModifyRequest assistantModifyRequest, CancellationToken? cancellationToken = default)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| threadId | String | 実行を含むスレッドの ID。 |
| runId | String | 修正する実行の ID。 |
| assistantModifyRequest | RunModifyRequest | 実行を修正するためのリクエストの詳細。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークン。 |

### 戻り値

非同期操作を表すタスク。タスクの結果には、実行の修正からの応答が含まれます。

### 例外

| 例外 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | スレッド ID が null または空の場合にスローされます。 |
| [AIClientException](../../aiclientexception/) | 実行 ID が null または空の場合にスローされます。 |

### 参照

* クラス [RunResponse](../../runresponse/)
* クラス [RunModifyRequest](../../runmodifyrequest/)
* インターフェース [IOpenAIClient](../)
* 名前空間 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../../)