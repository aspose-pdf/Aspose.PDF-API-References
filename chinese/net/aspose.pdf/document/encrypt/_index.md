---
title: "Document.Encrypt"
second_title: "Aspose.PDF for .NET API 参考"
description: "Document 方法。加密文档"
type: docs
weight: 640
url: /zh/net/aspose.pdf/document/encrypt/
---
## Encrypt(Permissions, CryptoAlgorithm, IList&lt;X509Certificate2&gt;) {#encrypt}

加密文档。

```csharp
public void Encrypt(Permissions permissions, CryptoAlgorithm cryptoAlgorithm, 
    IList<X509Certificate2> publicCertificates)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| permissions | Permissions | Document 权限，详见 [`Permissions`](../permissions/) 获取详细信息。 |
| cryptoAlgorithm | CryptoAlgorithm | 加密算法，详见 [`CryptoAlgorithm`](../cryptoalgorithm/) 获取详细信息。 |
| publicCertificates | IList`1 | 用于加密的公共证书——每个收件人一个。 |

## 备注

此方法为加密做准备。要加密文档，需要调用 Save 方法来保存它。

### 另请参见

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, DocumentPrivilege, ICustomSecurityHandler) {#encrypt_2}

加密文档。

```csharp
public void Encrypt(string userPassword, string ownerPassword, DocumentPrivilege privileges, 
    ICustomSecurityHandler customHandler)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| userPassword | String | 用户密码。 |
| ownerPassword | String | 所有者密码。 |
| privileges | DocumentPrivilege | Document 权限，详见 [`Permissions`](../permissions/) 获取详细信息。 |
| customHandler | ICustomSecurityHandler | 自定义安全处理程序。 |

## 备注

此方法为加密做准备。要加密文档，需要调用 Save 方法来保存它。

### 另请参见

* class [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, ICustomSecurityHandler) {#encrypt_5}

加密文档。

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    ICustomSecurityHandler customHandler)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| userPassword | String | 用户密码。 |
| ownerPassword | String | 所有者密码。 |
| permissions | Permissions | Document 权限，详见 [`Permissions`](../permissions/) 获取详细信息。 |
| customHandler | ICustomSecurityHandler | 自定义安全处理程序。 |

## 备注

此方法为加密做准备。要加密文档，需要调用 Save 方法来保存它。

### 另请参见

* enum [Permissions](../../permissions/)
* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, DocumentPrivilege, CryptoAlgorithm, bool) {#encrypt_1}

加密文档。

```csharp
public void Encrypt(string userPassword, string ownerPassword, DocumentPrivilege privileges, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| userPassword | String | 用户密码。 |
| ownerPassword | String | 所有者密码。 |
| privileges | DocumentPrivilege | Document 权限，详见 [`Permissions`](../permissions/) 获取详细信息。 |
| cryptoAlgorithm | CryptoAlgorithm | 加密算法，详见 [`CryptoAlgorithm`](../cryptoalgorithm/) 获取详细信息。 |
| usePdf20 | Boolean | 支持第 6 版（扩展 8）。 |

## 备注

此方法为加密做准备。要加密文档，需要调用 Save 方法来保存它。

### 另请参见

* class [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm) {#encrypt_3}

加密文档。

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| userPassword | String | 用户密码。 |
| ownerPassword | String | 所有者密码。 |
| permissions | Permissions | Document 权限，详见 [`Permissions`](../permissions/) 获取详细信息。 |
| cryptoAlgorithm | CryptoAlgorithm | 加密算法，详见 [`CryptoAlgorithm`](../cryptoalgorithm/) 获取详细信息。 |

## 备注

此方法为加密做准备。要加密文档，需要调用 Save 方法来保存它。

### 另请参见

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm, bool) {#encrypt_4}

加密文档。

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| userPassword | String | 用户密码。 |
| ownerPassword | String | 所有者密码。 |
| permissions | Permissions | Document 权限，详见 [`Permissions`](../permissions/) 获取详细信息。 |
| cryptoAlgorithm | CryptoAlgorithm | 加密算法，详见 [`CryptoAlgorithm`](../cryptoalgorithm/) 获取详细信息。 |
| usePdf20 | Boolean | 支持第 6 版（扩展 8）。 |

## 备注

此方法为加密做准备。要加密文档，需要调用 Save 方法来保存它。

### 另请参见

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


