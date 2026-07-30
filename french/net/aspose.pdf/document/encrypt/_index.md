---
title: "Document.Encrypt"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode Document. Crypte le document"
type: docs
weight: 640
url: /fr/net/aspose.pdf/document/encrypt/
---
## Encrypt(Permissions, CryptoAlgorithm, IList&lt;X509Certificate2&gt;) {#encrypt}

Chiffre le document.

```csharp
public void Encrypt(Permissions permissions, CryptoAlgorithm cryptoAlgorithm, 
    IList<X509Certificate2> publicCertificates)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| permissions | Permissions | Permissions du document, voir [`Permissions`](../permissions/) pour plus de détails. |
| cryptoAlgorithm | CryptoAlgorithm | Algorithme cryptographique, voir [`CryptoAlgorithm`](../cryptoalgorithm/) pour plus de détails. |
| publicCertificates | IList`1 | Les certificats publics utilisés pour le chiffrement — un par destinataire. |

## Remarques

Cette méthode prépare le chiffrement. Pour chiffrer un document, vous devez appeler la méthode Save pour l’enregistrer.

### Voir aussi

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, DocumentPrivilege, ICustomSecurityHandler) {#encrypt_2}

Chiffre le document.

```csharp
public void Encrypt(string userPassword, string ownerPassword, DocumentPrivilege privileges, 
    ICustomSecurityHandler customHandler)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| userPassword | String | Mot de passe de l'utilisateur. |
| ownerPassword | String | Mot de passe du propriétaire. |
| privileges | DocumentPrivilege | Permissions du document, voir [`Permissions`](../permissions/) pour plus de détails. |
| customHandler | ICustomSecurityHandler | Le gestionnaire de sécurité personnalisé. |

## Remarques

Cette méthode prépare le chiffrement. Pour chiffrer un document, vous devez appeler la méthode Save pour l’enregistrer.

### Voir aussi

* class [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, ICustomSecurityHandler) {#encrypt_5}

Chiffre le document.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    ICustomSecurityHandler customHandler)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| userPassword | String | Mot de passe de l'utilisateur. |
| ownerPassword | String | Mot de passe du propriétaire. |
| permissions | Permissions | Permissions du document, voir [`Permissions`](../permissions/) pour plus de détails. |
| customHandler | ICustomSecurityHandler | Le gestionnaire de sécurité personnalisé. |

## Remarques

Cette méthode prépare le chiffrement. Pour chiffrer un document, vous devez appeler la méthode Save pour l’enregistrer.

### Voir aussi

* enum [Permissions](../../permissions/)
* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, DocumentPrivilege, CryptoAlgorithm, bool) {#encrypt_1}

Chiffre le document.

```csharp
public void Encrypt(string userPassword, string ownerPassword, DocumentPrivilege privileges, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| userPassword | String | Mot de passe de l'utilisateur. |
| ownerPassword | String | Mot de passe du propriétaire. |
| privileges | DocumentPrivilege | Permissions du document, voir [`Permissions`](../permissions/) pour plus de détails. |
| cryptoAlgorithm | CryptoAlgorithm | Algorithme cryptographique, voir [`CryptoAlgorithm`](../cryptoalgorithm/) pour plus de détails. |
| usePdf20 | Boolean | Prise en charge de la révision 6 (Extension 8). |

## Remarques

Cette méthode prépare le chiffrement. Pour chiffrer un document, vous devez appeler la méthode Save pour l’enregistrer.

### Voir aussi

* class [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm) {#encrypt_3}

Chiffre le document.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| userPassword | String | Mot de passe de l'utilisateur. |
| ownerPassword | String | Mot de passe du propriétaire. |
| permissions | Permissions | Permissions du document, voir [`Permissions`](../permissions/) pour plus de détails. |
| cryptoAlgorithm | CryptoAlgorithm | Algorithme cryptographique, voir [`CryptoAlgorithm`](../cryptoalgorithm/) pour plus de détails. |

## Remarques

Cette méthode prépare le chiffrement. Pour chiffrer un document, vous devez appeler la méthode Save pour l’enregistrer.

### Voir aussi

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm, bool) {#encrypt_4}

Chiffre le document.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| userPassword | String | Mot de passe de l'utilisateur. |
| ownerPassword | String | Mot de passe du propriétaire. |
| permissions | Permissions | Permissions du document, voir [`Permissions`](../permissions/) pour plus de détails. |
| cryptoAlgorithm | CryptoAlgorithm | Algorithme cryptographique, voir [`CryptoAlgorithm`](../cryptoalgorithm/) pour plus de détails. |
| usePdf20 | Boolean | Prise en charge de la révision 6 (Extension 8). |

## Remarques

Cette méthode prépare le chiffrement. Pour chiffrer un document, vous devez appeler la méthode Save pour l’enregistrer.

### Voir aussi

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


