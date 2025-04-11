---
title: Document.Save
second_title: Aspose.PDF for .NET API Reference
description: Document メソッド。ドキュメントをストリームに保存します
type: docs
weight: 830
url: /ja/net/aspose.pdf/document/save/
---
## Save(Stream) {#save_2}

ドキュメントをストリームに保存します。

```csharp
public void Save(Stream output)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| output | Stream | ドキュメントが保存されるストリーム。 |

### 参照

* クラス [Document](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## Save(string) {#save_5}

指定されたファイルにドキュメントを保存します。

```csharp
public void Save(string outputFileName)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| outputFileName | String | ドキュメントが保存されるファイルのパス。 |

### 参照

* クラス [Document](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## Save() {#save}

ドキュメントをインクリメンタルに保存します（すなわち、インクリメンタル更新技術を使用します）。

```csharp
public void Save()
```

## 備考

ドキュメントをインクリメンタルに保存するには、書き込み用にドキュメントファイルを開く必要があります。したがって、Document は次のコードスニペットのように書き込み可能なストリームで初期化する必要があります: Document doc = new Document(new FileStream("document.pdf", FileMode.Open, FileAccess.ReadWrite)); // いくつかの変更を加え、ドキュメントをインクリメンタルに保存します doc.Save();

### 参照

* クラス [Document](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## Save(SaveOptions) {#save_1}

保存オプションを使用してドキュメントを保存します。

```csharp
public void Save(SaveOptions options)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| options | SaveOptions | 保存オプション。 |

### 参照

* クラス [SaveOptions](../../saveoptions/)
* クラス [Document](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## Save(string, SaveFormat) {#save_6}

新しい名前とファイル形式でドキュメントを保存します。

```csharp
public void Save(string outputFileName, SaveFormat format)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| outputFileName | String | ドキュメントが保存されるファイルのパス。 |
| format | SaveFormat | 形式オプション。 |

### 参照

* 列挙 [SaveFormat](../../saveformat/)
* クラス [Document](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## Save(Stream, SaveFormat) {#save_3}

新しい名前とファイル形式でドキュメントを保存します。

```csharp
public void Save(Stream outputStream, SaveFormat format)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| outputStream | Stream | ドキュメントが保存されるストリーム。 |
| format | SaveFormat | 形式オプション。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | [`HtmlSaveOptions`](../../htmlsaveoptions/) がメソッドに渡されたときの ArgumentException。HTML ストリームにドキュメントを保存することはサポートされていません。ファイルに保存するメソッドを使用してください。 |

### 参照

* 列挙 [SaveFormat](../../saveformat/)
* クラス [Document](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## Save(string, SaveOptions) {#save_7}

新しい名前を設定し、その保存オプションを設定してドキュメントを保存します。

```csharp
public void Save(string outputFileName, SaveOptions options)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| outputFileName | String | ドキュメントが保存されるファイルのパス。 |
| options | SaveOptions | 保存オプション。 |

### 参照

* クラス [SaveOptions](../../saveoptions/)
* クラス [Document](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## Save(Stream, SaveOptions) {#save_4}

保存オプションを使用してストリームにドキュメントを保存します。

```csharp
public void Save(Stream outputStream, SaveOptions options)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| outputStream | Stream | ドキュメントが保存されるストリーム。 |
| options | SaveOptions | 保存オプション。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| ArgumentException | [`HtmlSaveOptions`](../../htmlsaveoptions/) がメソッドに渡されたときの ArgumentException。HTML ストリームにドキュメントを保存することはサポートされていません。ファイルに保存するメソッドを使用してください。 |

### 参照

* クラス [SaveOptions](../../saveoptions/)
* クラス [Document](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)