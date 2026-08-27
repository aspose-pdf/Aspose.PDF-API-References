---
title: "Document.Document"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Document コンストラクタ。入力ストリームから新しい Document インスタンスを初期化します。"
type: docs
weight: 10
url: /ja/net/aspose.pdf/document/document/
---
## Document(Stream) {#constructor_2}

*input* ストリームから新しい Document インスタンスを初期化します。

```csharp
public Document(Stream input)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| 入力 | Stream | PDF ドキュメントを含むストリーム。 |

### 関連項目

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, bool) {#constructor_6}

*input* ストリームから新しい Document インスタンスを初期化します。

```csharp
public Document(Stream input, bool isManagedStream)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| 入力 | Stream | PDF ドキュメントを含むストリーム。 |
| isManagedStream | Boolean | `true` に設定された場合、内部ストリームは終了前に閉じられます。設定されていない場合は閉じられません。 |

### 関連項目

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string) {#constructor_7}

*input* ストリームから新しい Document インスタンスを初期化します。

```csharp
public Document(Stream input, string password)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| 入力 | Stream | 入力ストリームオブジェクト、対応する PDF はパスワードで保護されています。 |
| password | String | ユーザーまたは所有者パスワード。 |

### 関連項目

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, CertificateEncryptionOptions) {#constructor_4}

*input* ストリームから新しい Document インスタンスを初期化します。

```csharp
public Document(Stream input, CertificateEncryptionOptions certOptions)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| 入力 | Stream | 入力ストリームオブジェクト、対応する PDF はパスワードで保護されています。 |
| certOptions | CertificateEncryptionOptions | 証明書暗号化オプションです。 |

### 関連項目

* class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, CertificateEncryptionOptions, bool) {#constructor_5}

*input* ストリームから新しい Document インスタンスを初期化します。

```csharp
public Document(Stream input, CertificateEncryptionOptions certOptions, bool isManagedStream)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| 入力 | Stream | PDF ドキュメントを含むストリーム。 |
| certOptions | CertificateEncryptionOptions | 証明書暗号化オプションです。 |
| isManagedStream | Boolean | `true` に設定すると、内部ストリームは終了前に閉じられます。そうでない場合は閉じられません。 |

### 関連項目

* class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, CertificateEncryptionOptions) {#constructor_13}

暗号化されたドキュメントを操作するための [`Document`](../) クラスの新しいインスタンスを初期化します。

```csharp
public Document(string filename, CertificateEncryptionOptions certOptions)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| filename | String | Document ファイル名。 |
| certOptions | CertificateEncryptionOptions | 証明書暗号化オプションです。 |

### 関連項目

* class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, CertificateEncryptionOptions, bool) {#constructor_14}

暗号化されたドキュメントを操作するための [`Document`](../) クラスの新しいインスタンスを初期化します。

```csharp
public Document(string filename, CertificateEncryptionOptions certOptions, bool isManagedStream)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| filename | String | Document ファイル名。 |
| certOptions | CertificateEncryptionOptions | 証明書暗号化オプションです。 |
| isManagedStream | Boolean | `true` に設定された場合、内部ストリームは終了前に閉じられます。設定されていない場合は閉じられません。 |

### 関連項目

* class [CertificateEncryptionOptions](../../../aspose.pdf.security/certificateencryptionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string, ICustomSecurityHandler) {#constructor_8}

*input* ストリームから新しい Document インスタンスを初期化します。

```csharp
public Document(Stream input, string password, ICustomSecurityHandler customSecurityHandler)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| 入力 | Stream | 入力ストリームオブジェクト、対応する PDF はパスワードで保護されています。 |
| password | String | ユーザーまたは所有者パスワード。 |
| customSecurityHandler | ICustomSecurityHandler | カスタム セキュリティ ハンドラ。 |

### 関連項目

* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string, bool) {#constructor_9}

*input* ストリームから新しい Document インスタンスを初期化します。

```csharp
public Document(Stream input, string password, bool isManagedStream)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| 入力 | Stream | PDF ドキュメントを含むストリーム。 |
| password | String | ユーザーまたは所有者パスワード。 |
| isManagedStream | Boolean | `true` に設定すると、内部ストリームは終了前に閉じられます。そうでない場合は閉じられません。 |

### 関連項目

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, string, bool, ICustomSecurityHandler) {#constructor_10}

*input* ストリームから新しい Document インスタンスを初期化します。

```csharp
public Document(Stream input, string password, bool isManagedStream, 
    ICustomSecurityHandler customSecurityHandler)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| 入力 | Stream | PDF ドキュメントを含むストリーム。 |
| password | String | ユーザーまたは所有者パスワード。 |
| isManagedStream | Boolean | `true` に設定すると、内部ストリームは終了前に閉じられます。そうでない場合は閉じられません。 |
| customSecurityHandler | ICustomSecurityHandler | カスタム セキュリティ ハンドラ。 |

### 関連項目

* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string) {#constructor_11}

*filename* を使用して Document を初期化するだけです。`Document` と同じです。

```csharp
public Document(string filename)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| filename | String | PDF ドキュメントファイルの名前。 |

### 関連項目

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, bool) {#constructor_15}

*filename* を使用して Document を初期化するだけです。`Document` と同じです。

```csharp
public Document(string filename, bool isManagedStream)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| filename | String | PDF ドキュメントファイルの名前。 |
| isManagedStream | Boolean | `true` に設定すると、内部ストリームは終了前に閉じられます。そうでない場合は閉じられません。 |

### 関連項目

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string, ICustomSecurityHandler) {#constructor_17}

暗号化されたドキュメントを操作するための [`Document`](../) クラスの新しいインスタンスを初期化します。

```csharp
public Document(string filename, string password, ICustomSecurityHandler customSecurityHandler)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| filename | String | Document ファイル名。 |
| password | String | ユーザーまたは所有者パスワード。 |
| customSecurityHandler | ICustomSecurityHandler | カスタム セキュリティ ハンドラ。 |

### 関連項目

* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string) {#constructor_16}

暗号化されたドキュメントを操作するための [`Document`](../) クラスの新しいインスタンスを初期化します。

```csharp
public Document(string filename, string password)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| filename | String | Document ファイル名。 |
| password | String | ユーザーまたは所有者パスワード。 |

### 関連項目

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string, bool) {#constructor_18}

暗号化されたドキュメントを操作するための [`Document`](../) クラスの新しいインスタンスを初期化します。

```csharp
public Document(string filename, string password, bool isManagedStream)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| filename | String | Document ファイル名。 |
| password | String | ユーザーまたは所有者パスワード。 |
| isManagedStream | Boolean | `true` に設定された場合、内部ストリームは終了前に閉じられます。設定されていない場合は閉じられません。 |

### 関連項目

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, string, bool, ICustomSecurityHandler) {#constructor_19}

暗号化されたドキュメントを操作するための [`Document`](../) クラスの新しいインスタンスを初期化します。

```csharp
public Document(string filename, string password, bool isManagedStream, 
    ICustomSecurityHandler customSecurityHandler)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| filename | String | Document ファイル名。 |
| password | String | ユーザーまたは所有者パスワード。 |
| isManagedStream | Boolean | `true` に設定された場合、内部ストリームは終了前に閉じられます。設定されていない場合は閉じられません。 |
| customSecurityHandler | ICustomSecurityHandler | カスタム セキュリティ ハンドラ。 |

### 関連項目

* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document() {#constructor}

空の Document を初期化します。

```csharp
public Document()
```

### 関連項目

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(PdfVersion) {#constructor_1}

バージョン指定で空の Document を初期化します。

```csharp
public Document(PdfVersion version)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| バージョン | PdfVersion | PDF バージョンです。 |

### 関連項目

* enum [PdfVersion](../../pdfversion/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(string, LoadOptions) {#constructor_12}

ファイルから既存の Document を開き、PDF Document を取得するために必要な変換オプションを提供します。

```csharp
public Document(string filename, LoadOptions options)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| filename | String | PDF ドキュメントに変換する入力ファイル。 |
| オプション | LoadOptions | *filename* を PDF ドキュメントに変換するためのプロパティを表します。 |

### 関連項目

* class [LoadOptions](../../loadoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Document(Stream, LoadOptions) {#constructor_3}

ストリームから既存の Document を開き、PDF Document を取得するために必要な変換を提供します。

```csharp
public Document(Stream input, LoadOptions options)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| 入力 | Stream | PDF ドキュメントに変換するための入力ストリーム。 |
| オプション | LoadOptions | *input* を PDF ドキュメントに変換するためのプロパティを表します。 |

### 関連項目

* class [LoadOptions](../../loadoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


