---
title: ComHelper.OpenStream
second_title: Aspose.PDF for .NET API Reference
description: ComHelper メソッド。入力ストリームから新しい Document インスタンスを初期化して返します
type: docs
weight: 30
url: /ja/net/aspose.pdf/comhelper/openstream/
---
## OpenStream(Stream) {#openstream}

*入力* ストリームから新しい Document インスタンスを初期化して返します。

```csharp
public Document OpenStream(Stream input)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | Stream | PDF ドキュメントを含むストリーム。 |

### 戻り値

Document オブジェクト

### 参照

* クラス [Document](../../document/)
* クラス [ComHelper](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## OpenStream(Stream, string) {#openstream_3}

*入力* ストリームから新しい Document インスタンスを初期化して返します。

```csharp
public Document OpenStream(Stream input, string password)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | Stream | 入力ストリームオブジェクト、対応する PDF はパスワード保護されています。 |
| password | String | ユーザーまたはオーナーパスワード。 |

### 戻り値

Document オブジェクト

### 参照

* クラス [Document](../../document/)
* クラス [ComHelper](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## OpenStream(Stream, bool) {#openstream_2}

*入力* ストリームから新しい Document インスタンスを初期化して返します。

```csharp
public Document OpenStream(Stream input, bool isManagedStream)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | Stream | PDF ドキュメントを含むストリーム。 |
| isManagedStream | Boolean | `true` に設定されている場合、内部ストリームは終了前に閉じられます。そうでない場合は閉じられません。 |

### 戻り値

Document オブジェクト

### 参照

* クラス [Document](../../document/)
* クラス [ComHelper](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## OpenStream(Stream, string, bool) {#openstream_4}

*入力* ストリームから新しい Document インスタンスを初期化して返します。

```csharp
public Document OpenStream(Stream input, string password, bool isManagedStream)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | Stream | PDF ドキュメントを含むストリーム。 |
| password | String | ユーザーまたはオーナーパスワード。 |
| isManagedStream | Boolean | `true` に設定されている場合、内部ストリームは終了前に閉じられます。そうでない場合は閉じられません。 |

### 戻り値

Document オブジェクト

### 参照

* クラス [Document](../../document/)
* クラス [ComHelper](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)

---

## OpenStream(Stream, LoadOptions) {#openstream_1}

ストリームから既存のドキュメントを開いて返し、PDF ドキュメントを取得するために必要な変換を提供します。

```csharp
public Document OpenStream(Stream input, LoadOptions options)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | Stream | PDF ドキュメントに変換するための入力ストリーム。 |
| options | LoadOptions | *入力* を PDF ドキュメントに変換するためのプロパティを表します。 |

### 戻り値

Document オブジェクト

### 参照

* クラス [Document](../../document/)
* クラス [LoadOptions](../../loadoptions/)
* クラス [ComHelper](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)