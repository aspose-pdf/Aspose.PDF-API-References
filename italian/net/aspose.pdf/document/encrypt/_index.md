---
title: "Document.Encrypt"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Document metodo. Cifra il documento"
type: docs
weight: 640
url: /it/net/aspose.pdf/document/encrypt/
---
## Encrypt(Permissions, CryptoAlgorithm, IList&lt;X509Certificate2&gt;) {#encrypt}

Cripta il documento.

```csharp
public void Encrypt(Permissions permissions, CryptoAlgorithm cryptoAlgorithm, 
    IList<X509Certificate2> publicCertificates)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| permissions | Permissions | Permessi del Document, vedi [`Permissions`](../permissions/) per i dettagli. |
| cryptoAlgorithm | CryptoAlgorithm | Algoritmo crittografico, vedi [`CryptoAlgorithm`](../cryptoalgorithm/) per i dettagli. |
| publicCertificates | IList`1 | I certificati pubblici utilizzati per la crittografia — uno per destinatario. |

## Osservazioni

Questo metodo prepara la crittografia. Per crittografare un documento, è necessario chiamare il metodo Save per salvarlo.

### Vedi anche

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, DocumentPrivilege, ICustomSecurityHandler) {#encrypt_2}

Cripta il documento.

```csharp
public void Encrypt(string userPassword, string ownerPassword, DocumentPrivilege privileges, 
    ICustomSecurityHandler customHandler)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| userPassword | String | Password utente. |
| ownerPassword | String | Password del proprietario. |
| privileges | DocumentPrivilege | Permessi del Document, vedi [`Permissions`](../permissions/) per i dettagli. |
| customHandler | ICustomSecurityHandler | Il gestore di sicurezza personalizzato. |

## Osservazioni

Questo metodo prepara la crittografia. Per crittografare un documento, è necessario chiamare il metodo Save per salvarlo.

### Vedi anche

* class [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, ICustomSecurityHandler) {#encrypt_5}

Cripta il documento.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    ICustomSecurityHandler customHandler)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| userPassword | String | Password utente. |
| ownerPassword | String | Password del proprietario. |
| permissions | Permissions | Permessi del Document, vedi [`Permissions`](../permissions/) per i dettagli. |
| customHandler | ICustomSecurityHandler | Il gestore di sicurezza personalizzato. |

## Osservazioni

Questo metodo prepara la crittografia. Per crittografare un documento, è necessario chiamare il metodo Save per salvarlo.

### Vedi anche

* enum [Permissions](../../permissions/)
* interface [ICustomSecurityHandler](../../../aspose.pdf.security/icustomsecurityhandler/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, DocumentPrivilege, CryptoAlgorithm, bool) {#encrypt_1}

Cripta il documento.

```csharp
public void Encrypt(string userPassword, string ownerPassword, DocumentPrivilege privileges, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| userPassword | String | Password utente. |
| ownerPassword | String | Password del proprietario. |
| privileges | DocumentPrivilege | Permessi del Document, vedi [`Permissions`](../permissions/) per i dettagli. |
| cryptoAlgorithm | CryptoAlgorithm | Algoritmo crittografico, vedi [`CryptoAlgorithm`](../cryptoalgorithm/) per i dettagli. |
| usePdf20 | Boolean | Supporto per la revisione 6 (Estensione 8). |

## Osservazioni

Questo metodo prepara la crittografia. Per crittografare un documento, è necessario chiamare il metodo Save per salvarlo.

### Vedi anche

* class [DocumentPrivilege](../../../aspose.pdf.facades/documentprivilege/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm) {#encrypt_3}

Cripta il documento.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| userPassword | String | Password utente. |
| ownerPassword | String | Password del proprietario. |
| permissions | Permissions | Permessi del Document, vedi [`Permissions`](../permissions/) per i dettagli. |
| cryptoAlgorithm | CryptoAlgorithm | Algoritmo crittografico, vedi [`CryptoAlgorithm`](../cryptoalgorithm/) per i dettagli. |

## Osservazioni

Questo metodo prepara la crittografia. Per crittografare un documento, è necessario chiamare il metodo Save per salvarlo.

### Vedi anche

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Encrypt(string, string, Permissions, CryptoAlgorithm, bool) {#encrypt_4}

Cripta il documento.

```csharp
public void Encrypt(string userPassword, string ownerPassword, Permissions permissions, 
    CryptoAlgorithm cryptoAlgorithm, bool usePdf20)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| userPassword | String | Password utente. |
| ownerPassword | String | Password del proprietario. |
| permissions | Permissions | Permessi del Document, vedi [`Permissions`](../permissions/) per i dettagli. |
| cryptoAlgorithm | CryptoAlgorithm | Algoritmo crittografico, vedi [`CryptoAlgorithm`](../cryptoalgorithm/) per i dettagli. |
| usePdf20 | Boolean | Supporto per la revisione 6 (Estensione 8). |

## Osservazioni

Questo metodo prepara la crittografia. Per crittografare un documento, è necessario chiamare il metodo Save per salvarlo.

### Vedi anche

* enum [Permissions](../../permissions/)
* enum [CryptoAlgorithm](../../cryptoalgorithm/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


