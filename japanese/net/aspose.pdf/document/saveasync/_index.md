---
title: "Document.SaveAsync"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Document メソッド。保存オプションを使用してドキュメントをストリームに保存します。"
type: docs
weight: 860
url: /ja/net/aspose.pdf/document/saveasync/
---
## SaveAsync(Stream, SaveOptions, CancellationToken) {#saveasync_2}

save options を使用して document をストリームに保存します。

```csharp
public Task SaveAsync(Stream outputStream, SaveOptions options, CancellationToken cancellationToken)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputStream | Stream | ドキュメントが保存されるストリーム。 |
| オプション | SaveOptions | 保存オプションです。 |
| cancellationToken | CancellationToken | キャンセル トークン。 |

### 戻り値

非同期タスク。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | メソッドに [`HtmlSaveOptions`](../../htmlsaveoptions/) が渡されたときに ArgumentException がスローされます。ドキュメントを HTML ストリームに保存することはサポートされていません。ファイルに保存するメソッドを使用してください。 |

### 関連項目

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(Stream, CancellationToken) {#saveasync_3}

document をストリームに保存します。

```csharp
public Task SaveAsync(Stream output, CancellationToken cancellationToken)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| output | Stream | ドキュメントが格納されるストリーム。 |
| cancellationToken | CancellationToken | キャンセル トークン。 |

### 戻り値

非同期タスク。

### 関連項目

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, CancellationToken) {#saveasync_6}

document を指定されたファイルに保存します。

```csharp
public Task SaveAsync(string outputFileName, CancellationToken cancellationToken)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputFileName | String | ドキュメントが保存されるファイルへのパス。 |
| cancellationToken | CancellationToken | キャンセル トークン。 |

### 戻り値

非同期タスク。

### 関連項目

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(CancellationToken) {#saveasync_7}

document をインクリメンタルに保存します（すなわちインクリメンタル更新手法を使用）。

```csharp
public Task SaveAsync(CancellationToken cancellationToken)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| cancellationToken | CancellationToken | キャンセル トークン。 |

### 戻り値

非同期タスク。

## 備考

ドキュメントをインクリメンタルに保存するには、ドキュメントファイルを写し込みモードで開く必要があります。そのため、Document は次のコードスニペットのように書き込み可能なストリームで初期化しなければなりません: Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // 変更を加えてドキュメントをインクリメンタルに保存 doc.Save();

### 関連項目

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(SaveOptions, CancellationToken) {#saveasync}

save options を使用して document を保存します。

```csharp
public Task SaveAsync(SaveOptions options, CancellationToken cancellationToken)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| オプション | SaveOptions | 保存オプションです。 |
| cancellationToken | CancellationToken | キャンセル トークン。 |

### 戻り値

非同期タスク。

### 関連項目

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, SaveFormat, CancellationToken) {#saveasync_4}

document を新しい名前とファイル形式で保存します。

```csharp
public Task SaveAsync(string outputFileName, SaveFormat format, CancellationToken cancellationToken)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputFileName | String | ドキュメントが保存されるファイルへのパス。 |
| フォーマット | SaveFormat | フォーマットオプション。 |
| cancellationToken | CancellationToken | キャンセル トークン。 |

### 戻り値

非同期タスク。

### 関連項目

* enum [SaveFormat](../../saveformat/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(Stream, SaveFormat, CancellationToken) {#saveasync_1}

document を新しい名前とファイル形式で保存します。

```csharp
public Task SaveAsync(Stream outputStream, SaveFormat format, CancellationToken cancellationToken)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputStream | Stream | ドキュメントが保存されるストリーム。 |
| フォーマット | SaveFormat | フォーマットオプション。 |
| cancellationToken | CancellationToken | キャンセル トークン |

### 戻り値

非同期タスク。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | メソッドに [`HtmlSaveOptions`](../../htmlsaveoptions/) が渡されたときに ArgumentException がスローされます。ドキュメントを HTML ストリームに保存することはサポートされていません。ファイルに保存するメソッドを使用してください。 |

### 関連項目

* enum [SaveFormat](../../saveformat/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsync(string, SaveOptions, CancellationToken) {#saveasync_5}

新しい名前を設定し、save options を指定して document を保存します。

```csharp
public Task SaveAsync(string outputFileName, SaveOptions options, 
    CancellationToken cancellationToken)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputFileName | String | ドキュメントが保存されるファイルへのパス。 |
| オプション | SaveOptions | 保存オプションです。 |
| cancellationToken | CancellationToken | キャンセル トークン。 |

### 戻り値

非同期タスク。

### 関連項目

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


