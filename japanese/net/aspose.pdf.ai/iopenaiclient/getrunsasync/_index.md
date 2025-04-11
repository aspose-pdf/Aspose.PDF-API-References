---
title: IOpenAIClient.GetRunsAsync
second_title: Aspose.PDF for .NET API Reference
description: IOpenAIClient メソッド。指定されたスレッドの実行リストを非同期で取得します
type: docs
weight: 240
url: /ja/net/aspose.pdf.ai/iopenaiclient/getrunsasync/
---
## IOpenAIClient.GetRunsAsync メソッド

指定されたスレッドの実行リストを非同期で取得します。

```csharp
public Task<RunListResponse> GetRunsAsync(string threadId, 
    RunListQueryParameters queryParameters = null, CancellationToken? cancellationToken = default)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| threadId | String | 実行を取得するスレッドの ID。 |
| queryParameters | RunListQueryParameters | 実行リストをフィルタリングするためのオプションのクエリパラメータ。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークン。 |

### 戻り値

非同期操作を表すタスク。タスクの結果には実行のリストが含まれます。

### 例外

| 例外 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | スレッド ID が null または空の場合にスローされます。 |

### 参照

* クラス [RunListResponse](../../runlistresponse/)
* クラス [RunListQueryParameters](../../runlistqueryparameters/)
* インターフェース [IOpenAIClient](../)
* 名前空間 [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* アセンブリ [Aspose.PDF](../../../)