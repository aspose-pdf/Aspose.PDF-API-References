---
title: "CertificateEncryptionOptions.CertificateEncryptionOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Constructeur CertificateEncryptionOptions. Crée une instance de la classe CertificateEncryptionOptions"
type: docs
weight: 10
url: /fr/net/aspose.pdf.security/certificateencryptionoptions/certificateencryptionoptions/
---
## CertificateEncryptionOptions(string, string, string) {#constructor_3}

Crée une instance de la classe [`CertificateEncryptionOptions`](../).

```csharp
public CertificateEncryptionOptions(string publicCertificatePath, string pfxPath, 
    string pfxPassword)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| publicCertificatePath | String | Le chemin du fichier du certificat public. |
| pfxPath | String | Le chemin du fichier d'archive p12. |
| pfxPassword | String | Le mot de passe du fichier d'archive p12. |

### Voir aussi

* class [CertificateEncryptionOptions](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)

---

## CertificateEncryptionOptions(string, StoreName, StoreLocation) {#constructor_2}

Crée une instance de la classe [`CertificateEncryptionOptions`](../).

```csharp
public CertificateEncryptionOptions(string publicCertificatePath, 
    StoreName storeName = StoreName.My, StoreLocation storeLocation = StoreLocation.CurrentUser)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| publicCertificatePath | String | Le chemin du fichier du certificat public. |
| storeName | StoreName | Le nom du magasin pour obtenir un certificat de clé privée. |
| storeLocation | StoreLocation | L'emplacement du magasin pour obtenir un certificat de clé privée. |

### Voir aussi

* class [CertificateEncryptionOptions](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)

---

## CertificateEncryptionOptions(X509Certificate2, StoreName, StoreLocation) {#constructor}

Crée une instance de la classe [`CertificateEncryptionOptions`](../).

```csharp
public CertificateEncryptionOptions(X509Certificate2 publicCertificate, 
    StoreName storeName = StoreName.My, StoreLocation storeLocation = StoreLocation.CurrentUser)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| publicCertificate | X509Certificate2 | Le certificat public. |
| storeName | StoreName | Le nom du magasin pour obtenir un certificat de clé privée. |
| storeLocation | StoreLocation | L'emplacement du magasin pour obtenir un certificat de clé privée. |

### Voir aussi

* class [CertificateEncryptionOptions](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)

---

## CertificateEncryptionOptions(X509Certificate2, string, string) {#constructor_1}

Crée une instance de la classe [`CertificateEncryptionOptions`](../).

```csharp
public CertificateEncryptionOptions(X509Certificate2 publicCertificate, string pfxPath, 
    string pfxPassword)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| publicCertificate | X509Certificate2 | Le certificat public. |
| pfxPath | String | Le chemin du fichier d'archive p12. |
| pfxPassword | String | Le mot de passe du fichier d'archive p12. |

### Voir aussi

* class [CertificateEncryptionOptions](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


