---
title: IChatCopilot.SaveResponseAsync
second_title: Aspose.PDF for .NET API Reference
description: IChatCopilot メソッド。指定されたメッセージの応答を PDF ファイルに非同期で保存します。
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

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| message | String | 応答が保存される入力メッセージ。 |
| outputFileName | String | 応答を保存する出力 PDF ファイルの名前。 |
| cancellationToken | Nullable`1 | キャンセルトークン（オプション）。 |

### 戻り値

非同期操作を表すタスク。

### 参照

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(string, string, SaveFormat, CancellationToken?) {#saveresponseasync_2}

指定されたメッセージの応答を指定された形式のファイルに非同期で保存します。

```csharp
public Task SaveResponseAsync(string message, string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| message | String | 応答が保存される入力メッセージ。 |
| outputFileName | String | 応答を保存する出力ファイルの名前。 |
| saveFormat | SaveFormat | 応答を保存する形式（指定しない場合は PDF）。 |
| cancellationToken | Nullable`1 | キャンセルトークン（オプション）。 |

### 戻り値

非同期操作を表すタスク。

### 参照

* enum [SaveFormat](../../../aspose.pdf/saveformat/)
* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(List&lt;string&gt;, string, CancellationToken?) {#saveresponseasync_1}

指定されたメッセージのリストの応答を PDF ファイルに非同期で保存します。

```csharp
public Task SaveResponseAsync(List<string> messages, string outputFileName, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| messages | List`1 | 応答が保存される入力メッセージのリスト。 |
| outputFileName | String | 応答を保存する出力 PDF ファイルの名前。 |
| cancellationToken | Nullable`1 | キャンセルトークン（オプション）。 |

### 戻り値

非同期操作を表すタスク。

### 参照

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(List&lt;string&gt;, string, SaveFormat, CancellationToken?) {#saveresponseasync}

指定されたメッセージのリストの応答を指定された形式のファイルに非同期で保存します。

```csharp
public Task SaveResponseAsync(List<string> messages, string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| messages | List`1 | 応答が保存される入力メッセージのリスト。 |
| outputFileName | String | 応答を保存する出力ファイルの名前。 |
| saveFormat | SaveFormat | 応答を保存する形式（指定しない場合は PDF）。 |
| cancellationToken | Nullable`1 | キャンセルトークン（オプション）。 |

### 戻り値

非同期操作を表すタスク。

### 参照

* enum [SaveFormat](../../../aspose.pdf/saveformat/)
* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)