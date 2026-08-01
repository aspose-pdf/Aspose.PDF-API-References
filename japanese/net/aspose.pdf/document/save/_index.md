---
title: "Document.Save"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Document メソッド。保存オプションを使用してドキュメントをストリームに保存します。"
type: docs
weight: 850
url: /ja/net/aspose.pdf/document/save/
---
## Save(Stream, SaveOptions) {#save_4}

save options を使用して document をストリームに保存します。

```csharp
public void Save(Stream outputStream, SaveOptions options)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputStream | Stream | ドキュメントが保存されるストリーム。 |
| オプション | SaveOptions | 保存オプションです。 |

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

## Save(Stream) {#save_2}

document をストリームに保存します。

```csharp
public void Save(Stream output)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| output | Stream | ドキュメントが格納されるストリーム。 |

### 関連項目

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(string) {#save_5}

document を指定されたファイルに保存します。

```csharp
public void Save(string outputFileName)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputFileName | String | ドキュメントが保存されるファイルへのパス。 |

### 関連項目

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save() {#save}

document をインクリメンタルに保存します（すなわちインクリメンタル更新手法を使用）。

```csharp
public void Save()
```

## 備考

ドキュメントをインクリメンタルに保存するには、ドキュメントファイルを写し込みモードで開く必要があります。そのため、Document は次のコードスニペットのように書き込み可能なストリームで初期化しなければなりません: Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // 変更を加えてドキュメントをインクリメンタルに保存 doc.Save();

### 関連項目

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(SaveOptions) {#save_1}

save options を使用して document を保存します。

```csharp
public void Save(SaveOptions options)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| オプション | SaveOptions | 保存オプションです。 |

### 関連項目

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(string, SaveFormat) {#save_6}

document を新しい名前とファイル形式で保存します。

```csharp
public void Save(string outputFileName, SaveFormat format)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputFileName | String | ドキュメントが保存されるファイルへのパス。 |
| フォーマット | SaveFormat | フォーマットオプション。 |

### 関連項目

* enum [SaveFormat](../../saveformat/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Save(Stream, SaveFormat) {#save_3}

document を新しい名前とファイル形式で保存します。

```csharp
public void Save(Stream outputStream, SaveFormat format)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputStream | Stream | ドキュメントが保存されるストリーム。 |
| フォーマット | SaveFormat | フォーマットオプション。 |

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

## Save(string, SaveOptions) {#save_7}

新しい名前を設定し、save options を指定して document を保存します。

```csharp
public void Save(string outputFileName, SaveOptions options)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| outputFileName | String | ドキュメントが保存されるファイルへのパス。 |
| オプション | SaveOptions | 保存オプションです。 |

### 関連項目

* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


