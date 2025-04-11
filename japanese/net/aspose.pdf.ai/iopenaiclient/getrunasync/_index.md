---
title: IOpenAIClient.GetRunAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient メソッド。スレッド内の特定の実行の詳細を非同期で取得します。
type: docs
weight: 230
url: /ja/net/aspose.pdf.ai/iopenaiclient/getrunasync/
---
## IOpenAIClient.GetRunAsync メソッド

スレッド内の特定の実行の詳細を非同期で取得します。

```csharp
public Task<RunResponse> GetRunAsync(string threadId, string runId, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| threadId | String | 実行を含むスレッドの ID。 |
| runId | String | 取得する実行の ID。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークン。 |

### 戻り値

非同期操作を表すタスク。タスクの結果には実行の詳細が含まれます。

### 例外

| 例外 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | スレッド ID が null または空の場合にスローされます。 |
| [AIClientException](../../aiclientexception/) | 実行 ID が null または空の場合にスローされます。 |

### 参照

* クラス [RunResponse](../../runresponse/)
* インターフェース [IOpenAIClient](../)
* 名前空間 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../../)