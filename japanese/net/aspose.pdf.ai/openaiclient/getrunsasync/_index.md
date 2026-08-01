---
title: "OpenAIClient.GetRunsAsync"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "OpenAIClient メソッド。指定されたスレッドの実行リストを非同期に取得します。"
type: docs
weight: 270
url: /ja/net/aspose.pdf.ai/openaiclient/getrunsasync/
---
## OpenAIClient.GetRunsAsync method

指定されたスレッドの実行一覧を非同期で取得します。

```csharp
public Task<RunListResponse> GetRunsAsync(string threadId, 
    RunListQueryParameters queryParameters = null, CancellationToken? cancellationToken = default)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| threadId | String | 実行を取得するスレッドの ID。 |
| queryParameters | RunListQueryParameters | 実行リストをフィルタリングするためのオプションのクエリ パラメータです。 |
| cancellationToken | Nullable`1 | 操作をキャンセルするためのトークンです。 |

### 戻り値

非同期操作を表すタスクです。タスクの結果には実行のリストが含まれます。

### 例外

| 例外 | 条件 |
| --- | --- |
| [AIClientException](../../aiclientexception/) | スレッドIDがnullまたは空の場合にスローされます。 |

### 関連項目

* class [RunListResponse](../../runlistresponse/)
* class [RunListQueryParameters](../../runlistqueryparameters/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


