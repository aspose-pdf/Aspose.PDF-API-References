---
title: "ExternalSignature.ExternalSignature"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "ExternalSignature コンストラクタ。X509Certificate2 を使用して分離された PKCS7 署名を作成します。エクスポート可能なプライベートキーを持たない USB スマートカードトークンをサポートします。"
type: docs
weight: 10
url: /ja/net/aspose.pdf.forms/externalsignature/externalsignature/
---
## ExternalSignature(X509Certificate2) {#constructor}

X509Certificate2 を使用して分離型 PKCS#7 `(detached)` 署名を作成します。エクスポート可能なプライベートキーを持たない USB スマートカードやトークンをサポートします。

```csharp
public ExternalSignature(X509Certificate2 certificate)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| 証明書 | X509Certificate2 | プライベートキーを含む証明書。 |

## 備考

ダイジェストアルゴリズムは証明書の鍵データに基づいて自動的に選択されます。

### 関連項目

* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(X509Certificate2, DigestHashAlgorithm) {#constructor_1}

X509Certificate2 を使用して分離型 PKCS#7 `(detached)` 署名を作成します。エクスポート可能なプライベートキーを持たない USB スマートカードやトークンをサポートします。

```csharp
public ExternalSignature(X509Certificate2 certificate, DigestHashAlgorithm digestHashAlgorithm)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| 証明書 | X509Certificate2 | プライベートキーを含む証明書。 |
| digestHashAlgorithm | DigestHashAlgorithm | ドキュメントに署名するためのダイジェストアルゴリズム。 |

### 関連項目

* enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(X509Certificate2, bool) {#constructor_2}

X509Certificate2 を使用して分離型 PKCS#7 署名を作成します。エクスポート可能なプライベートキーを持たない USB スマートカードやトークンをサポートします。

```csharp
public ExternalSignature(X509Certificate2 certificate, bool detached)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| 証明書 | X509Certificate2 | プライベートキーを含む証明書。 |
| 分離 | Boolean | 署名を分離する場合は true、そうでない場合は false。 |

## 備考

分離が false に設定されている場合、ダイジェストアルゴリズムは常に `SHA1` になります。それ以外の場合、ダイジェストアルゴリズムは証明書の鍵データに基づいて自動的に選択されます（ Auto を参照）。

### 関連項目

* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(string, bool) {#constructor_4}

X509Certificate2 を base64 文字列として使用して PKCS#7 署名を作成します。

```csharp
public ExternalSignature(string base64, bool detached)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| base64 | String | X509Certificate2 を base64 文字列として表現します。 |
| 分離 | Boolean | 署名を分離する場合は true、そうでない場合は false。 |

## 備考

分離が false に設定されている場合、ダイジェストアルゴリズムは常に `SHA1` になります。それ以外の場合、ダイジェストアルゴリズムは証明書の鍵データに基づいて自動的に選択されます（ Auto を参照）。

### 関連項目

* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(string, DigestHashAlgorithm) {#constructor_3}

X509Certificate2 を base64 文字列として使用して PKCS#7 `(detached)` 署名を作成します。

```csharp
public ExternalSignature(string base64, DigestHashAlgorithm digestHashAlgorithm)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| base64 | String | X509Certificate2 を base64 文字列として表現します。 |
| digestHashAlgorithm | DigestHashAlgorithm | ドキュメントに署名するためのダイジェストアルゴリズム。 |

### 関連項目

* enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


