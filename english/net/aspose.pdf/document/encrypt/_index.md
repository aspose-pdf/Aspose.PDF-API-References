---
title: "Document.Encrypt"
linktitle: "Encrypt"
articleTitle: "Encrypt"
second_title: "Aspose.PDF for .NET"
description: "Encrypts the document."
type: docs
weight: 590
url: "/net/aspose.pdf/document/encrypt/"
product_version: "26.9.0"
---
## Encrypt([Permissions](../../../aspose.pdf/permissions/), [CryptoAlgorithm](../../../aspose.pdf/cryptoalgorithm/), IList<X509Certificate2>) {#encrypt}

Encrypts the document.

This method prepares for encryption. To encrypt a document, you need to call the Save method to save it.

```csharp
public void Encrypt(Permissions permissions, CryptoAlgorithm cryptoAlgorithm, IList<X509Certificate2> publicCertificates)
```

| Parameter | Type | Description |
| --- | --- | --- |
| permissions | Permissions | Document permissions, see <see cref="P:Aspose.Pdf.Document.Permissions" /> for details. |
| cryptoAlgorithm | CryptoAlgorithm | Cryptographic algorithm, see <see cref="P:Aspose.Pdf.Document.CryptoAlgorithm" /> for details. |
| publicCertificates | IList<X509Certificate2> | The public certificates used for encryption — one per recipient. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/), [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)) {#encrypt_1}

Encrypts the document.

This method prepares for encryption. To encrypt a document, you need to call the Save method to save it.

```csharp
public void Encrypt(string userPassword, string ownerPassword, DocumentPrivilege privileges, ICustomSecurityHandler customHandler)
```

| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | string | User password. |
| ownerPassword | string | Owner password. |
| privileges | DocumentPrivilege | Document permissions, see <see cref="P:Aspose.Pdf.Document.Permissions" /> for details. |
| customHandler | ICustomSecurityHandler | The custom security handler. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, [Permissions](../../../aspose.pdf/permissions/), [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)) {#encrypt_2}

Encrypts the document.

This method prepares for encryption. To encrypt a document, you need to call the Save method to save it.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, ICustomSecurityHandler customHandler)
```

| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | string | User password. |
| ownerPassword | string | Owner password. |
| permissions | Permissions | Document permissions, see <see cref="P:Aspose.Pdf.Document.Permissions" /> for details. |
| customHandler | ICustomSecurityHandler | The custom security handler. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/), [CryptoAlgorithm](../../../aspose.pdf/cryptoalgorithm/), bool) {#encrypt_3}

Encrypts the document.

This method prepares for encryption. To encrypt a document, you need to call the Save method to save it.

```csharp
public void Encrypt(string userPassword, string ownerPassword, DocumentPrivilege privileges, CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | string | User password. |
| ownerPassword | string | Owner password. |
| privileges | DocumentPrivilege | Document permissions, see <see cref="P:Aspose.Pdf.Document.Permissions" /> for details. |
| cryptoAlgorithm | CryptoAlgorithm | Cryptographic algorithm, see <see cref="P:Aspose.Pdf.Document.CryptoAlgorithm" /> for details. |
| usePdf20 | bool | Support for revision 6 (Extension 8). |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, [Permissions](../../../aspose.pdf/permissions/), [CryptoAlgorithm](../../../aspose.pdf/cryptoalgorithm/)) {#encrypt_4}

Encrypts the document.

This method prepares for encryption. To encrypt a document, you need to call the Save method to save it.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, CryptoAlgorithm cryptoAlgorithm)
```

| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | string | User password. |
| ownerPassword | string | Owner password. |
| permissions | Permissions | Document permissions, see <see cref="P:Aspose.Pdf.Document.Permissions" /> for details. |
| cryptoAlgorithm | CryptoAlgorithm | Cryptographic algorithm, see <see cref="P:Aspose.Pdf.Document.CryptoAlgorithm" /> for details. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, [Permissions](../../../aspose.pdf/permissions/), [CryptoAlgorithm](../../../aspose.pdf/cryptoalgorithm/), bool) {#encrypt_5}

Encrypts the document.

This method prepares for encryption. To encrypt a document, you need to call the Save method to save it.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| Parameter | Type | Description |
| --- | --- | --- |
| userPassword | string | User password. |
| ownerPassword | string | Owner password. |
| permissions | Permissions | Document permissions, see <see cref="P:Aspose.Pdf.Document.Permissions" /> for details. |
| cryptoAlgorithm | CryptoAlgorithm | Cryptographic algorithm, see <see cref="P:Aspose.Pdf.Document.CryptoAlgorithm" /> for details. |
| usePdf20 | bool | Support for revision 6 (Extension 8). |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

