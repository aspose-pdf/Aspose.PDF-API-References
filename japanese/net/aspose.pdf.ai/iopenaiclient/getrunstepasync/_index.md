---
title: IOpenAIClient.GetRunStepAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient メソッド。実行内の特定のステップの詳細を非同期で取得します
type: docs
weight: 250
url: /ja/net/aspose.pdf.ai/iopenaiclient/getrunstepasync/
---
## IOpenAIClient.GetRunStepAsync メソッド

実行内の特定のステップの詳細を非同期で取得します。

```csharp
public Task<RunStepResponse> GetRunStepAsync(string threadId, string runId, string runStepId, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| threadId | String | 実行を含むスレッドの ID。 |
| runId | String | ステップを含む実行の ID。 |
| runStepId | String | 取得する実行ステップの ID。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークン。 |

### 戻り値

非同期操作を表すタスク。タスクの結果には、実行ステップの詳細が含まれます。

### 例外

| 例外 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | スレッド ID が null または空の場合にスローされます。 |
| [AIClientException](../../aiclientexception/) | 実行 ID が null または空の場合にスローされます。 |
| [AIClientException](../../aiclientexception/) | 実行ステップ ID が null または空の場合にスローされます。 |

### 参照

* クラス [RunStepResponse](../../runstepresponse/)
* インターフェース [IOpenAIClient](../)
* 名前空間 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../../)