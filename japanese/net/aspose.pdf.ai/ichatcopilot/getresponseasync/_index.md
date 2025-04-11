---
title: IChatCopilot.GetResponseAsync
second_title: Aspose.PDF for .NET API Reference
description: IChatCopilot メソッド。指定されたメッセージに対する応答を非同期的に取得します
type: docs
weight: 20
url: /ja/net/aspose.pdf.ai/ichatcopilot/getresponseasync/
---
## GetResponseAsync(string, CancellationToken?) {#getresponseasync_1}

指定されたメッセージに対する応答を非同期的に取得します。

```csharp
public Task<string> GetResponseAsync(string message, CancellationToken? cancellationToken = default)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| message | String | 応答を要求する入力メッセージ。 |
| cancellationToken | Nullable`1 | キャンセルトークン（オプション）。 |

### 戻り値

応答文字列を持つ非同期操作を表すタスク。

### 参照

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## GetResponseAsync(List&lt;string&gt;, CancellationToken?) {#getresponseasync}

指定されたメッセージのリストに対する応答を非同期的に取得します。

```csharp
public Task<string> GetResponseAsync(List<string> messages, 
    CancellationToken? cancellationToken = default)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| messages | List`1 | 応答を要求する入力メッセージのリスト。 |
| cancellationToken | Nullable`1 | キャンセルトークン（オプション）。 |

### 戻り値

応答文字列を持つ非同期操作を表すタスク。

### 参照

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)