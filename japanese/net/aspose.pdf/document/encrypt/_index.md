---
title: "Document.Encrypt"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Document メソッド。ドキュメントを暗号化します"
type: docs
weight: 640
url: /ja/net/aspose.pdf/document/encrypt/
---
## Encrypt(Permissions, CryptoAlgorithm, IList&lt;X509Certificate2&gt;) {#encrypt}

Document を暗号化します。

```csharp
public void Encrypt(Permissions permissions, CryptoAlgorithm cryptoAlgorithm, 
    IList<X509Certificate2> publicCertificates)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| permissions | Permissions | Document の権限、詳細は [`Permissions`](../permissions/) を参照してください。 |
| cryptoAlgorithm | CryptoAlgorithm | 暗号アルゴリズム、詳細は [`CryptoAlgorithm`](../cryptoalgorithm/) を参照してください。 |
| publicCertificates | IList`1 | 暗号化に使用される公開証明書です — 受信者ごとに1つ。 |

## 備考

このメソッドは暗号化の準備を行います。ドキュメントを暗号化するには、Save メソッドを呼び出して保存する必要があります。

### 関連項目

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, DocumentPrivilege, ICustomSecurityHandler) {#encrypt_2}

Document を暗号化します。

```csharp
public void Encrypt(string userPassword, string ownerPassword, DocumentPrivilege privileges, 
    ICustomSecurityHandler customHandler)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| userPassword | String | ユーザーパスワード。 |
| ownerPassword | String | 所有者パスワード。 |
| privileges | DocumentPrivilege | Document の権限、詳細は [`Permissions`](../permissions/) を参照してください。 |
| customHandler | ICustomSecurityHandler | カスタム セキュリティ ハンドラ。 |

## 備考

このメソッドは暗号化の準備を行います。ドキュメントを暗号化するには、Save メソッドを呼び出して保存する必要があります。

### 関連項目

* class [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, ICustomSecurityHandler) {#encrypt_5}

Document を暗号化します。

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    ICustomSecurityHandler customHandler)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| userPassword | String | ユーザーパスワード。 |
| ownerPassword | String | 所有者パスワード。 |
| permissions | Permissions | Document の権限、詳細は [`Permissions`](../permissions/) を参照してください。 |
| customHandler | ICustomSecurityHandler | カスタム セキュリティ ハンドラ。 |

## 備考

このメソッドは暗号化の準備を行います。ドキュメントを暗号化するには、Save メソッドを呼び出して保存する必要があります。

### 関連項目

* enum [Permissions](../../permissions/)
* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, DocumentPrivilege, CryptoAlgorithm, bool) {#encrypt_1}

Document を暗号化します。

```csharp
public void Encrypt(string userPassword, string ownerPassword, DocumentPrivilege privileges, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| userPassword | String | ユーザーパスワード。 |
| ownerPassword | String | 所有者パスワード。 |
| privileges | DocumentPrivilege | Document の権限、詳細は [`Permissions`](../permissions/) を参照してください。 |
| cryptoAlgorithm | CryptoAlgorithm | 暗号アルゴリズム、詳細は [`CryptoAlgorithm`](../cryptoalgorithm/) を参照してください。 |
| usePdf20 | Boolean | リビジョン 6（拡張 8）をサポートします。 |

## 備考

このメソッドは暗号化の準備を行います。ドキュメントを暗号化するには、Save メソッドを呼び出して保存する必要があります。

### 関連項目

* class [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm) {#encrypt_3}

Document を暗号化します。

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| userPassword | String | ユーザーパスワード。 |
| ownerPassword | String | 所有者パスワード。 |
| permissions | Permissions | Document の権限、詳細は [`Permissions`](../permissions/) を参照してください。 |
| cryptoAlgorithm | CryptoAlgorithm | 暗号アルゴリズム、詳細は [`CryptoAlgorithm`](../cryptoalgorithm/) を参照してください。 |

## 備考

このメソッドは暗号化の準備を行います。ドキュメントを暗号化するには、Save メソッドを呼び出して保存する必要があります。

### 関連項目

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm, bool) {#encrypt_4}

Document を暗号化します。

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| userPassword | String | ユーザーパスワード。 |
| ownerPassword | String | 所有者パスワード。 |
| permissions | Permissions | Document の権限、詳細は [`Permissions`](../permissions/) を参照してください。 |
| cryptoAlgorithm | CryptoAlgorithm | 暗号アルゴリズム、詳細は [`CryptoAlgorithm`](../cryptoalgorithm/) を参照してください。 |
| usePdf20 | Boolean | リビジョン 6（拡張 8）をサポートします。 |

## 備考

このメソッドは暗号化の準備を行います。ドキュメントを暗号化するには、Save メソッドを呼び出して保存する必要があります。

### 関連項目

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


