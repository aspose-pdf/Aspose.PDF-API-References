---
title: "CertificateEncryptionOptions.CertificateEncryptionOptions"
second_title: "Aspose.PDF for .NET API 参考"
description: "CertificateEncryptionOptions 构造函数。创建 CertificateEncryptionOptions 类的实例"
type: docs
weight: 10
url: /zh/net/aspose.pdf.security/certificateencryptionoptions/certificateencryptionoptions/
---
## CertificateEncryptionOptions(string, string, string) {#constructor_3}

创建 [`CertificateEncryptionOptions`](../) 类的实例。

```csharp
public CertificateEncryptionOptions(string publicCertificatePath, string pfxPath, 
    string pfxPassword)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| publicCertificatePath | String | 公共证书文件路径。 |
| pfxPath | String | p12 存档文件路径。 |
| pfxPassword | String | p12 存档文件密码。 |

### 另请参见

* class [CertificateEncryptionOptions](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)

---

## CertificateEncryptionOptions(string, StoreName, StoreLocation) {#constructor_2}

创建 [`CertificateEncryptionOptions`](../) 类的实例。

```csharp
public CertificateEncryptionOptions(string publicCertificatePath, 
    StoreName storeName = StoreName.My, StoreLocation storeLocation = StoreLocation.CurrentUser)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| publicCertificatePath | String | 公共证书文件路径。 |
| storeName | StoreName | 用于获取私钥证书的存储名称。 |
| storeLocation | StoreLocation | 用于获取私钥证书的存储位置。 |

### 另请参见

* class [CertificateEncryptionOptions](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)

---

## CertificateEncryptionOptions(X509Certificate2, StoreName, StoreLocation) {#constructor}

创建 [`CertificateEncryptionOptions`](../) 类的实例。

```csharp
public CertificateEncryptionOptions(X509Certificate2 publicCertificate, 
    StoreName storeName = StoreName.My, StoreLocation storeLocation = StoreLocation.CurrentUser)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| publicCertificate | X509Certificate2 | 公共证书。 |
| storeName | StoreName | 用于获取私钥证书的存储名称。 |
| storeLocation | StoreLocation | 用于获取私钥证书的存储位置。 |

### 另请参见

* class [CertificateEncryptionOptions](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)

---

## CertificateEncryptionOptions(X509Certificate2, string, string) {#constructor_1}

创建 [`CertificateEncryptionOptions`](../) 类的实例。

```csharp
public CertificateEncryptionOptions(X509Certificate2 publicCertificate, string pfxPath, 
    string pfxPassword)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| publicCertificate | X509Certificate2 | 公共证书。 |
| pfxPath | String | p12 存档文件路径。 |
| pfxPassword | String | p12 存档文件密码。 |

### 另请参见

* class [CertificateEncryptionOptions](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


