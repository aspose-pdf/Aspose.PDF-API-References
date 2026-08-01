---
title: "IChatCopilot.SaveResponseAsync"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "IChatCopilot メソッド。指定されたメッセージのレスポンスを PDF ファイルに非同期で保存します。"
type: docs
weight: 40
url: /ja/net/aspose.pdf.ai/ichatcopilot/saveresponseasync/
---
## SaveResponseAsync(string, string, CancellationToken?) {#saveresponseasync_3}

指定されたメッセージの応答を PDF ファイルに非同期で保存します。

```csharp
public Task SaveResponseAsync(string message, string outputFileName, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| メッセージ | String | レスポンスが保存される入力メッセージです。 |
| outputFileName | String | レスポンスを保存する出力 PDF ファイルの名前です。 |
| cancellationToken | Nullable`1 | キャンセルトークン（オプション）。 |

### 戻り値

非同期操作を表すタスクです。

### 関連項目

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(string, string, SaveFormat, CancellationToken?) {#saveresponseasync_2}

指定されたメッセージの応答を指定フォーマットのファイルに非同期で保存します。

```csharp
public Task SaveResponseAsync(string message, string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| メッセージ | String | レスポンスが保存される入力メッセージです。 |
| outputFileName | String | レスポンスを保存する出力ファイルの名前です。 |
| saveFormat | SaveFormat | レスポンスを保存する形式（指定がない場合は PDF）。 |
| cancellationToken | Nullable`1 | キャンセルトークン（オプション）。 |

### 戻り値

非同期操作を表すタスクです。

### 関連項目

* enum [SaveFormat](../../../aspose.pdf/saveformat/)
* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(List&lt;string&gt;, string, CancellationToken?) {#saveresponseasync_1}

指定されたメッセージリストの応答を PDF ファイルに非同期で保存します。

```csharp
public Task SaveResponseAsync(List<string> messages, string outputFileName, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| messages | List`1 | レスポンスが保存される入力メッセージのリスト。 |
| outputFileName | String | レスポンスを保存する出力 PDF ファイルの名前。 |
| cancellationToken | Nullable`1 | キャンセルトークン（オプション）。 |

### 戻り値

非同期操作を表すタスクです。

### 関連項目

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(List&lt;string&gt;, string, SaveFormat, CancellationToken?) {#saveresponseasync}

指定されたメッセージリストの応答を指定フォーマットのファイルに非同期で保存します。

```csharp
public Task SaveResponseAsync(List<string> messages, string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| messages | List`1 | レスポンスが保存される入力メッセージのリスト。 |
| outputFileName | String | レスポンスを保存する出力ファイルの名前。 |
| saveFormat | SaveFormat | レスポンスを保存する形式（指定がない場合は PDF）。 |
| cancellationToken | Nullable`1 | キャンセルトークン（オプション）。 |

### 戻り値

非同期操作を表すタスクです。

### 関連項目

* enum [SaveFormat](../../../aspose.pdf/saveformat/)
* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


