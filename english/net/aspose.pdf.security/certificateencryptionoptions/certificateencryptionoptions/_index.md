---
title: CertificateEncryptionOptions.CertificateEncryptionOptions
second_title: Aspose.PDF for .NET API Reference
description: CertificateEncryptionOptions constructor. Creates an instance of CertificateEncryptionOptions class
type: docs
weight: 10
url: /net/aspose.pdf.security/certificateencryptionoptions/certificateencryptionoptions/
---
## CertificateEncryptionOptions(string, string, string) {#constructor_3}

Creates an instance of [`CertificateEncryptionOptions`](../) class.

```csharp
public CertificateEncryptionOptions(string publicCertificatePath, string pfxPath, 
    string pfxPassword)
```

| Parameter | Type | Description |
| --- | --- | --- |
| publicCertificatePath | String | The public certificate file path. |
| pfxPath | String | The p12 archive file path. |
| pfxPassword | String | The p12 archive file password. |

### See Also

* class [CertificateEncryptionOptions](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)

---

## CertificateEncryptionOptions(string, StoreName, StoreLocation) {#constructor_2}

Creates an instance of [`CertificateEncryptionOptions`](../) class.

```csharp
public CertificateEncryptionOptions(string publicCertificatePath, 
    StoreName storeName = StoreName.My, StoreLocation storeLocation = StoreLocation.CurrentUser)
```

| Parameter | Type | Description |
| --- | --- | --- |
| publicCertificatePath | String | The public certificate file path. |
| storeName | StoreName | The store name to get a private key certificate. |
| storeLocation | StoreLocation | The store location to get a private key certificate. |

### See Also

* class [CertificateEncryptionOptions](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)

---

## CertificateEncryptionOptions(X509Certificate2, StoreName, StoreLocation) {#constructor}

Creates an instance of [`CertificateEncryptionOptions`](../) class.

```csharp
public CertificateEncryptionOptions(X509Certificate2 publicCertificate, 
    StoreName storeName = StoreName.My, StoreLocation storeLocation = StoreLocation.CurrentUser)
```

| Parameter | Type | Description |
| --- | --- | --- |
| publicCertificate | X509Certificate2 | The public certificate. |
| storeName | StoreName | The store name to get a private key certificate. |
| storeLocation | StoreLocation | The store location to get a private key certificate. |

### See Also

* class [CertificateEncryptionOptions](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)

---

## CertificateEncryptionOptions(X509Certificate2, string, string) {#constructor_1}

Creates an instance of [`CertificateEncryptionOptions`](../) class.

```csharp
public CertificateEncryptionOptions(X509Certificate2 publicCertificate, string pfxPath, 
    string pfxPassword)
```

| Parameter | Type | Description |
| --- | --- | --- |
| publicCertificate | X509Certificate2 | The public certificate. |
| pfxPath | String | The p12 archive file path. |
| pfxPassword | String | The p12 archive file password. |

### See Also

* class [CertificateEncryptionOptions](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


