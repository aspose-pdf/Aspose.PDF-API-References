---
title: Document.SaveAsync
second_title: Aspose.PDF for .NET API Reference
description: ドキュメントメソッド。ドキュメントをストリームに保存します
type: docs
weight: 840
url: /ja/net/aspose.pdf/document/saveasync/
---
## SaveAsync(Stream, CancellationToken) {#saveasync_3}

ドキュメントをストリームに保存します。

```csharp
public Task SaveAsync(Stream output, CancellationToken cancellationToken)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| output | Stream | ドキュメントが保存されるストリーム。 |
| cancellationToken | CancellationToken | キャンセルトークン。 |

### 戻り値

非同期タスク。

### 参照

* クラス [Document](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## SaveAsync(string, CancellationToken) {#saveasync_6}

指定されたファイルにドキュメントを保存します。

```csharp
public Task SaveAsync(string outputFileName, CancellationToken cancellationToken)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputFileName | String | ドキュメントが保存されるファイルへのパス。 |
| cancellationToken | CancellationToken | キャンセルトークン。 |

### 戻り値

非同期タスク。

### 参照

* クラス [Document](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## SaveAsync(CancellationToken) {#saveasync_7}

ドキュメントをインクリメンタルに保存します（すなわち、インクリメンタル更新技術を使用）。

```csharp
public Task SaveAsync(CancellationToken cancellationToken)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| cancellationToken | CancellationToken | キャンセルトークン。 |

### 戻り値

非同期タスク。

## 備考

ドキュメントをインクリメンタルに保存するには、書き込み用にドキュメントファイルを開く必要があります。したがって、ドキュメントは次のコードスニペットのように書き込み可能なストリームで初期化する必要があります: Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // いくつかの変更を加えてドキュメントをインクリメンタルに保存します doc.Save();

### 参照

* クラス [Document](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## SaveAsync(SaveOptions, CancellationToken) {#saveasync}

保存オプションを使用してドキュメントを保存します。

```csharp
public Task SaveAsync(SaveOptions options, CancellationToken cancellationToken)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| options | SaveOptions | 保存オプション。 |
| cancellationToken | CancellationToken | キャンセルトークン。 |

### 戻り値

非同期タスク。

### 参照

* クラス [SaveOptions](../../saveoptions/)
* クラス [Document](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## SaveAsync(string, SaveFormat, CancellationToken) {#saveasync_4}

新しい名前とファイル形式でドキュメントを保存します。

```csharp
public Task SaveAsync(string outputFileName, SaveFormat format, CancellationToken cancellationToken)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputFileName | String | ドキュメントが保存されるファイルへのパス。 |
| format | SaveFormat | フォーマットオプション。 |
| cancellationToken | CancellationToken | キャンセルトークン。 |

### 戻り値

非同期タスク。

### 参照

* 列挙 [SaveFormat](../../saveformat/)
* クラス [Document](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## SaveAsync(Stream, SaveFormat, CancellationToken) {#saveasync_1}

新しい名前とファイル形式でドキュメントを保存します。

```csharp
public Task SaveAsync(Stream outputStream, SaveFormat format, CancellationToken cancellationToken)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputStream | Stream | ドキュメントが保存されるストリーム。 |
| format | SaveFormat | フォーマットオプション。 |
| cancellationToken | CancellationToken | キャンセルトークン。 |

### 戻り値

非同期タスク。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | [`HtmlSaveOptions`](../../htmlsaveoptions/) がメソッドに渡されたときの ArgumentException。HTMLストリームにドキュメントを保存することはサポートされていません。ファイルに保存するメソッドを使用してください。 |

### 参照

* 列挙 [SaveFormat](../../saveformat/)
* クラス [Document](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## SaveAsync(string, SaveOptions, CancellationToken) {#saveasync_5}

新しい名前を設定し、その保存オプションを設定してドキュメントを保存します。

```csharp
public Task SaveAsync(string outputFileName, SaveOptions options, 
    CancellationToken cancellationToken)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputFileName | String | ドキュメントが保存されるファイルへのパス。 |
| options | SaveOptions | 保存オプション。 |
| cancellationToken | CancellationToken | キャンセルトークン。 |

### 戻り値

非同期タスク。

### 参照

* クラス [SaveOptions](../../saveoptions/)
* クラス [Document](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## SaveAsync(Stream, SaveOptions, CancellationToken) {#saveasync_2}

保存オプションを使用してストリームにドキュメントを保存します。

```csharp
public Task SaveAsync(Stream outputStream, SaveOptions options, CancellationToken cancellationToken)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| outputStream | Stream | ドキュメントが保存されるストリーム。 |
| options | SaveOptions | 保存オプション。 |
| cancellationToken | CancellationToken | キャンセルトークン。 |

### 戻り値

非同期タスク。

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | [`HtmlSaveOptions`](../../htmlsaveoptions/) がメソッドに渡されたときの ArgumentException。HTMLストリームにドキュメントを保存することはサポートされていません。ファイルに保存するメソッドを使用してください。 |

### 参照

* クラス [SaveOptions](../../saveoptions/)
* クラス [Document](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)