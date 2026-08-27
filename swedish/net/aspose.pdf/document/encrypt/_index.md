---
title: "Document.Encrypt"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Document‑metod. Krypterar dokumentet"
type: docs
weight: 640
url: /sv/net/aspose.pdf/document/encrypt/
---
## Encrypt(Permissions, CryptoAlgorithm, IList&lt;X509Certificate2&gt;) {#encrypt}

Krypterar document.

```csharp
public void Encrypt(Permissions permissions, CryptoAlgorithm cryptoAlgorithm, 
    IList<X509Certificate2> publicCertificates)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| permissions | Permissions | Dokumentbehörigheter, se [`Permissions`](../permissions/) för detaljer. |
| cryptoAlgorithm | CryptoAlgorithm | Kryptografisk algoritm, se [`CryptoAlgorithm`](../cryptoalgorithm/) för detaljer. |
| publicCertificates | IList`1 | De offentliga certifikaten som används för kryptering — ett per mottagare. |

## Anmärkningar

Denna metod förbereder kryptering. För att kryptera ett dokument måste du anropa Save‑metoden för att spara det.

### Se även

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, DocumentPrivilege, ICustomSecurityHandler) {#encrypt_2}

Krypterar document.

```csharp
public void Encrypt(string userPassword, string ownerPassword, DocumentPrivilege privileges, 
    ICustomSecurityHandler customHandler)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| userPassword | String | Användarlösenord. |
| ownerPassword | String | Ägarlösenord. |
| privileges | DocumentPrivilege | Dokumentbehörigheter, se [`Permissions`](../permissions/) för detaljer. |
| customHandler | ICustomSecurityHandler | Den anpassade säkerhetshanteraren. |

## Anmärkningar

Denna metod förbereder kryptering. För att kryptera ett dokument måste du anropa Save‑metoden för att spara det.

### Se även

* class [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, ICustomSecurityHandler) {#encrypt_5}

Krypterar document.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    ICustomSecurityHandler customHandler)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| userPassword | String | Användarlösenord. |
| ownerPassword | String | Ägarlösenord. |
| permissions | Permissions | Dokumentbehörigheter, se [`Permissions`](../permissions/) för detaljer. |
| customHandler | ICustomSecurityHandler | Den anpassade säkerhetshanteraren. |

## Anmärkningar

Denna metod förbereder kryptering. För att kryptera ett dokument måste du anropa Save‑metoden för att spara det.

### Se även

* enum [Permissions](../../permissions/)
* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, DocumentPrivilege, CryptoAlgorithm, bool) {#encrypt_1}

Krypterar document.

```csharp
public void Encrypt(string userPassword, string ownerPassword, DocumentPrivilege privileges, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| userPassword | String | Användarlösenord. |
| ownerPassword | String | Ägarlösenord. |
| privileges | DocumentPrivilege | Dokumentbehörigheter, se [`Permissions`](../permissions/) för detaljer. |
| cryptoAlgorithm | CryptoAlgorithm | Kryptografisk algoritm, se [`CryptoAlgorithm`](../cryptoalgorithm/) för detaljer. |
| usePdf20 | Boolean | Stöd för revision 6 (Extension 8). |

## Anmärkningar

Denna metod förbereder kryptering. För att kryptera ett dokument måste du anropa Save‑metoden för att spara det.

### Se även

* class [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm) {#encrypt_3}

Krypterar document.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| userPassword | String | Användarlösenord. |
| ownerPassword | String | Ägarlösenord. |
| permissions | Permissions | Dokumentbehörigheter, se [`Permissions`](../permissions/) för detaljer. |
| cryptoAlgorithm | CryptoAlgorithm | Kryptografisk algoritm, se [`CryptoAlgorithm`](../cryptoalgorithm/) för detaljer. |

## Anmärkningar

Denna metod förbereder kryptering. För att kryptera ett dokument måste du anropa Save‑metoden för att spara det.

### Se även

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm, bool) {#encrypt_4}

Krypterar document.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| userPassword | String | Användarlösenord. |
| ownerPassword | String | Ägarlösenord. |
| permissions | Permissions | Dokumentbehörigheter, se [`Permissions`](../permissions/) för detaljer. |
| cryptoAlgorithm | CryptoAlgorithm | Kryptografisk algoritm, se [`CryptoAlgorithm`](../cryptoalgorithm/) för detaljer. |
| usePdf20 | Boolean | Stöd för revision 6 (Extension 8). |

## Anmärkningar

Denna metod förbereder kryptering. För att kryptera ett dokument måste du anropa Save‑metoden för att spara det.

### Se även

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


