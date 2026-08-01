---
title: "CertificateEncryptionOptions.CertificateEncryptionOptions"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "CertificateEncryptionOptions コンストラクタ。CertificateEncryptionOptions クラスのインスタンスを作成します。"
type: docs
weight: 10
url: /ja/net/aspose.pdf.security/certificateencryptionoptions/certificateencryptionoptions/
---
## CertificateEncryptionOptions(string, string, string) {#constructor_3}

[`CertificateEncryptionOptions`](../) クラスのインスタンスを作成します。

```csharp
public CertificateEncryptionOptions(string publicCertificatePath, string pfxPath, 
    string pfxPassword)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| publicCertificatePath | String | 公開証明書ファイルのパスです。 |
| pfxPath | String | p12 アーカイブファイルのパスです。 |
| pfxPassword | String | p12 アーカイブファイルのパスワードです。 |

### 関連項目

* class [CertificateEncryptionOptions](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)

---

## CertificateEncryptionOptions(string, StoreName, StoreLocation) {#constructor_2}

[`CertificateEncryptionOptions`](../) クラスのインスタンスを作成します。

```csharp
public CertificateEncryptionOptions(string publicCertificatePath, 
    StoreName storeName = StoreName.My, StoreLocation storeLocation = StoreLocation.CurrentUser)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| publicCertificatePath | String | 公開証明書ファイルのパスです。 |
| storeName | StoreName | プライベートキー証明書を取得するためのストア名です。 |
| storeLocation | StoreLocation | プライベートキー証明書を取得するためのストアの場所です。 |

### 関連項目

* class [CertificateEncryptionOptions](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)

---

## CertificateEncryptionOptions(X509Certificate2, StoreName, StoreLocation) {#constructor}

[`CertificateEncryptionOptions`](../) クラスのインスタンスを作成します。

```csharp
public CertificateEncryptionOptions(X509Certificate2 publicCertificate, 
    StoreName storeName = StoreName.My, StoreLocation storeLocation = StoreLocation.CurrentUser)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| publicCertificate | X509Certificate2 | 公開証明書です。 |
| storeName | StoreName | プライベートキー証明書を取得するためのストア名です。 |
| storeLocation | StoreLocation | プライベートキー証明書を取得するためのストアの場所です。 |

### 関連項目

* class [CertificateEncryptionOptions](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)

---

## CertificateEncryptionOptions(X509Certificate2, string, string) {#constructor_1}

[`CertificateEncryptionOptions`](../) クラスのインスタンスを作成します。

```csharp
public CertificateEncryptionOptions(X509Certificate2 publicCertificate, string pfxPath, 
    string pfxPassword)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| publicCertificate | X509Certificate2 | 公開証明書です。 |
| pfxPath | String | p12 アーカイブファイルのパスです。 |
| pfxPassword | String | p12 アーカイブファイルのパスワードです。 |

### 関連項目

* class [CertificateEncryptionOptions](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


