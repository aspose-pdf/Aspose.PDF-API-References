---
title: Document.Encrypt
second_title: Aspose.PDF for .NET API Reference
description: Document method. Encrypts the document. Call then Save to get encrypted version of the document
type: docs
weight: 640
url: /net/aspose.pdf/document/encrypt/
---
## Encrypt(string, string, DocumentPrivilege, ICustomSecurityHandler) {#encrypt_1}

Encrypts the document. Call then Save to get encrypted version of the document.

```csharp
public void Encrypt(string userPassword, string ownerPassword, DocumentPrivilege privileges, 
    ICustomSecurityHandler customHandler)
```

| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | String | User password. |
| ownerPassword | String | Owner password. |
| privileges | DocumentPrivilege | Document permissions, see [`Permissions`](../permissions/) for details. |
| customHandler | ICustomSecurityHandler | The custom security handler. |

### See Also

* class [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, ICustomSecurityHandler) {#encrypt_4}

Encrypts the document. Call then Save to get encrypted version of the document.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    ICustomSecurityHandler customHandler)
```

| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | String | User password. |
| ownerPassword | String | Owner password. |
| permissions | Permissions | Document permissions, see [`Permissions`](../permissions/) for details. |
| customHandler | ICustomSecurityHandler | The custom security handler. |

### See Also

* enum [Permissions](../../permissions/)
* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, DocumentPrivilege, CryptoAlgorithm, bool) {#encrypt}

Encrypts the document. Call then Save to get encrypted version of the document.

```csharp
public void Encrypt(string userPassword, string ownerPassword, DocumentPrivilege privileges, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | String | User password. |
| ownerPassword | String | Owner password. |
| privileges | DocumentPrivilege | Document permissions, see [`Permissions`](../permissions/) for details. |
| cryptoAlgorithm | CryptoAlgorithm | Cryptographic algorithm, see [`CryptoAlgorithm`](../cryptoalgorithm/) for details. |
| usePdf20 | Boolean | Support for revision 6 (Extension 8). |

### See Also

* class [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm) {#encrypt_2}

Encrypts the document. Call then Save to get encrypted version of the document.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm)
```

| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | String | User password. |
| ownerPassword | String | Owner password. |
| permissions | Permissions | Document permissions, see [`Permissions`](../permissions/) for details. |
| cryptoAlgorithm | CryptoAlgorithm | Cryptographic algorithm, see [`CryptoAlgorithm`](../cryptoalgorithm/) for details. |

### See Also

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm, bool) {#encrypt_3}

Encrypts the document. Call then Save to get encrypted version of the document.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | String | User password. |
| ownerPassword | String | Owner password. |
| permissions | Permissions | Document permissions, see [`Permissions`](../permissions/) for details. |
| cryptoAlgorithm | CryptoAlgorithm | Cryptographic algorithm, see [`CryptoAlgorithm`](../cryptoalgorithm/) for details. |
| usePdf20 | Boolean | Support for revision 6 (Extension 8). |

### See Also

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


