---
title: "IChatCopilot.GetResponseAsync"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "IChatCopilot メソッド。指定されたメッセージに対して非同期にレスポンスを取得します。"
type: docs
weight: 20
url: /ja/net/aspose.pdf.ai/ichatcopilot/getresponseasync/
---
## GetResponseAsync(string, CancellationToken?) {#getresponseasync_1}

指定されたメッセージに対する応答を非同期に取得します。

```csharp
public Task<string> GetResponseAsync(string message, CancellationToken? cancellationToken = default)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| メッセージ | String | レスポンスが要求される入力メッセージです。 |
| cancellationToken | Nullable`1 | キャンセルトークン（オプション）。 |

### 戻り値

レスポンス文字列を伴う非同期操作を表すタスクです。

### 関連項目

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## GetResponseAsync(List&lt;string&gt;, CancellationToken?) {#getresponseasync}

指定されたメッセージリストに対する応答を非同期に取得します。

```csharp
public Task<string> GetResponseAsync(List<string> messages, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| messages | List`1 | レスポンスが要求される入力メッセージのリストです。 |
| cancellationToken | Nullable`1 | キャンセルトークン（オプション）。 |

### 戻り値

レスポンス文字列を伴う非同期操作を表すタスクです。

### 関連項目

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


