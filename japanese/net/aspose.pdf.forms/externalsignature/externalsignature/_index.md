---
title: ExternalSignature.ExternalSignature
second_title: Aspose.PDF for .NET API Reference
description: ExternalSignature コンストラクタ。X509Certificate2 を使用して、分離された PKCS7 分離署名を作成します。エクスポート可能な秘密鍵を持たない USB スマートカードトークンをサポートしています。
type: docs
weight: 10
url: /ja/net/aspose.pdf.forms/externalsignature/externalsignature/
---
## ExternalSignature(X509Certificate2) {#constructor}

X509Certificate2 を使用して、分離された PKCS#7 `(detached)` 署名を作成します。エクスポート可能な秘密鍵を持たない USB スマートカード、トークンをサポートしています。

```csharp
public ExternalSignature(X509Certificate2 certificate)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| certificate | X509Certificate2 | 秘密鍵を持つ証明書。 |

## 備考

ダイジェストアルゴリズムは、証明書の鍵データに基づいて自動的に選択されます。

### 参照

* クラス [ExternalSignature](../)
* 名前空間 [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* アセンブリ [Aspose.PDF](../../../)

---

## ExternalSignature(X509Certificate2, DigestHashAlgorithm) {#constructor_1}

X509Certificate2 を使用して、分離された PKCS#7 `(detached)` 署名を作成します。エクスポート可能な秘密鍵を持たない USB スマートカード、トークンをサポートしています。

```csharp
public ExternalSignature(X509Certificate2 certificate, DigestHashAlgorithm digestHashAlgorithm)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| certificate | X509Certificate2 | 秘密鍵を持つ証明書。 |
| digestHashAlgorithm | DigestHashAlgorithm | ドキュメントに署名するためのダイジェストアルゴリズム。 |

### 参照

* 列挙 [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* クラス [ExternalSignature](../)
* 名前空間 [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* アセンブリ [Aspose.PDF](../../../)

---

## ExternalSignature(X509Certificate2, bool) {#constructor_2}

X509Certificate2 を使用して、分離された PKCS#7 署名を作成します。エクスポート可能な秘密鍵を持たない USB スマートカード、トークンをサポートしています。

```csharp
public ExternalSignature(X509Certificate2 certificate, bool detached)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| certificate | X509Certificate2 | 秘密鍵を持つ証明書。 |
| detached | Boolean | 署名が分離されるべき場合は true、そうでない場合は false。 |

## 備考

detached が false に設定されている場合、ダイジェストアルゴリズムは常に `SHA1` になります。それ以外の場合、ダイジェストアルゴリズムは証明書の鍵データに基づいて自動的に選択されます（自動参照）。

### 参照

* クラス [ExternalSignature](../)
* 名前空間 [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* アセンブリ [Aspose.PDF](../../../)

---

## ExternalSignature(string, bool) {#constructor_4}

X509Certificate2 を base64 文字列として使用して、PKCS#7 署名を作成します。

```csharp
public ExternalSignature(string base64, bool detached)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| base64 | String | base64 文字列としての X509Certificate2。 |
| detached | Boolean | 署名が分離されるべき場合は true、そうでない場合は false。 |

## 備考

detached が false に設定されている場合、ダイジェストアルゴリズムは常に `SHA1` になります。それ以外の場合、ダイジェストアルゴリズムは証明書の鍵データに基づいて自動的に選択されます（自動参照）。

### 参照

* クラス [ExternalSignature](../)
* 名前空間 [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* アセンブリ [Aspose.PDF](../../../)

---

## ExternalSignature(string, DigestHashAlgorithm) {#constructor_3}

X509Certificate2 を base64 文字列として使用して、PKCS#7 `(detached)` 署名を作成します。

```csharp
public ExternalSignature(string base64, DigestHashAlgorithm digestHashAlgorithm)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| base64 | String | base64 文字列としての X509Certificate2。 |
| digestHashAlgorithm | DigestHashAlgorithm | ドキュメントに署名するためのダイジェストアルゴリズム。 |

### 参照

* 列挙 [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* クラス [ExternalSignature](../)
* 名前空間 [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* アセンブリ [Aspose.PDF](../../../)