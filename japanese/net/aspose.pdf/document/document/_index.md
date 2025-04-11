---
title: Document.Document
second_title: Aspose.PDF for .NET API Reference
description: ドキュメントコンストラクタ。入力ストリームから新しいドキュメントインスタンスを初期化します
type: docs
weight: 10
url: /ja/net/aspose.pdf/document/document/
---
## Document(Stream) {#constructor_2}

*入力* ストリームから新しいドキュメントインスタンスを初期化します。

```csharp
public Document(Stream input)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | Stream | PDFドキュメントを含むストリーム。 |

### 参照

* クラス [Document](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## Document(Stream, bool) {#constructor_4}

*入力* ストリームから新しいドキュメントインスタンスを初期化します。

```csharp
public Document(Stream input, bool isManagedStream)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | Stream | PDFドキュメントを含むストリーム。 |
| isManagedStream | Boolean | `true` に設定されている場合、内部ストリームは終了前に閉じられます。そうでない場合は閉じられません。 |

### 参照

* クラス [Document](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## Document(Stream, string) {#constructor_5}

*入力* ストリームから新しいドキュメントインスタンスを初期化します。

```csharp
public Document(Stream input, string password)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | Stream | 入力ストリームオブジェクト、対応するPDFはパスワード保護されています。 |
| password | String | ユーザーまたはオーナーパスワード。 |

### 参照

* クラス [Document](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## Document(Stream, string, bool) {#constructor_6}

*入力* ストリームから新しいドキュメントインスタンスを初期化します。

```csharp
public Document(Stream input, string password, bool isManagedStream)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | Stream | PDFドキュメントを含むストリーム。 |
| password | String | ユーザーまたはオーナーパスワード。 |
| isManagedStream | Boolean | `true` に設定されている場合、内部ストリームは終了前に閉じられます。そうでない場合は閉じられません。 |

### 参照

* クラス [Document](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## Document(string) {#constructor_7}

*ファイル名* を使用してドキュメントを初期化します。`Document` と同じです。

```csharp
public Document(string filename)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filename | String | PDFドキュメントファイルの名前。 |

### 参照

* クラス [Document](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## Document(string, bool) {#constructor_9}

*ファイル名* を使用してドキュメントを初期化します。`Document` と同じです。

```csharp
public Document(string filename, bool isManagedStream)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filename | String | PDFドキュメントファイルの名前。 |
| isManagedStream | Boolean | `true` に設定されている場合、内部ストリームは終了前に閉じられます。そうでない場合は閉じられません。 |

### 参照

* クラス [Document](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## Document(string, string) {#constructor_10}

暗号化されたドキュメントで作業するための [`Document`](../) クラスの新しいインスタンスを初期化します。

```csharp
public Document(string filename, string password)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filename | String | ドキュメントファイル名。 |
| password | String | ユーザーまたはオーナーパスワード。 |

### 参照

* クラス [Document](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## Document(string, string, bool) {#constructor_11}

暗号化されたドキュメントで作業するための [`Document`](../) クラスの新しいインスタンスを初期化します。

```csharp
public Document(string filename, string password, bool isManagedStream)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filename | String | ドキュメントファイル名。 |
| password | String | ユーザーまたはオーナーパスワード。 |
| isManagedStream | Boolean | `true` に設定されている場合、内部ストリームは終了前に閉じられます。そうでない場合は閉じられません。 |

### 参照

* クラス [Document](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## Document() {#constructor}

空のドキュメントを初期化します。

```csharp
public Document()
```

### 参照

* クラス [Document](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## Document(PdfVersion) {#constructor_1}

バージョンによって空のドキュメントを初期化します。

```csharp
public Document(PdfVersion version)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| version | PdfVersion | PDFバージョン。 |

### 参照

* 列挙 [PdfVersion](../../pdfversion/)
* クラス [Document](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## Document(string, LoadOptions) {#constructor_8}

必要な変換オプションを提供してファイルから既存のドキュメントを開き、PDFドキュメントを取得します。

```csharp
public Document(string filename, LoadOptions options)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| filename | String | PDFドキュメントに変換するための入力ファイル。 |
| options | LoadOptions | *filename* をPDFドキュメントに変換するためのプロパティを表します。 |

### 参照

* クラス [LoadOptions](../../loadoptions/)
* クラス [Document](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## Document(Stream, LoadOptions) {#constructor_3}

必要な変換を提供してストリームから既存のドキュメントを開き、PDFドキュメントを取得します。

```csharp
public Document(Stream input, LoadOptions options)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | Stream | PDFドキュメントに変換するための入力ストリーム。 |
| options | LoadOptions | *input* をPDFドキュメントに変換するためのプロパティを表します。 |

### 参照

* クラス [LoadOptions](../../loadoptions/)
* クラス [Document](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)