---
title: "CertificateEncryptionOptions.CertificateEncryptionOptions"
second_title: "Aspose.PDF för .NET API‑referens"
description: "CertificateEncryptionOptions-konstruktor. Skapar en instans av CertificateEncryptionOptions-klassen"
type: docs
weight: 10
url: /sv/net/aspose.pdf.security/certificateencryptionoptions/certificateencryptionoptions/
---
## CertificateEncryptionOptions(string, string, string) {#constructor_3}

Skapar en instans av [`CertificateEncryptionOptions`](../)-klassen.

```csharp
public CertificateEncryptionOptions(string publicCertificatePath, string pfxPath, 
    string pfxPassword)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| publicCertificatePath | String | Den offentliga certifikatfilens sökväg. |
| pfxPath | String | Sökvägen till p12‑arkivfilen. |
| pfxPassword | String | Lösenordet för p12‑arkivfilen. |

### Se även

* class [CertificateEncryptionOptions](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)

---

## CertificateEncryptionOptions(string, StoreName, StoreLocation) {#constructor_2}

Skapar en instans av [`CertificateEncryptionOptions`](../)-klassen.

```csharp
public CertificateEncryptionOptions(string publicCertificatePath, 
    StoreName storeName = StoreName.My, StoreLocation storeLocation = StoreLocation.CurrentUser)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| publicCertificatePath | String | Den offentliga certifikatfilens sökväg. |
| storeName | StoreName | Namnet på lagret för att hämta ett privatnyckelcertifikat. |
| storeLocation | StoreLocation | Platsen för lagret för att hämta ett privatnyckelcertifikat. |

### Se även

* class [CertificateEncryptionOptions](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)

---

## CertificateEncryptionOptions(X509Certificate2, StoreName, StoreLocation) {#constructor}

Skapar en instans av [`CertificateEncryptionOptions`](../)-klassen.

```csharp
public CertificateEncryptionOptions(X509Certificate2 publicCertificate, 
    StoreName storeName = StoreName.My, StoreLocation storeLocation = StoreLocation.CurrentUser)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| publicCertificate | X509Certificate2 | Det offentliga certifikatet. |
| storeName | StoreName | Namnet på lagret för att hämta ett privatnyckelcertifikat. |
| storeLocation | StoreLocation | Platsen för lagret för att hämta ett privatnyckelcertifikat. |

### Se även

* class [CertificateEncryptionOptions](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)

---

## CertificateEncryptionOptions(X509Certificate2, string, string) {#constructor_1}

Skapar en instans av [`CertificateEncryptionOptions`](../)-klassen.

```csharp
public CertificateEncryptionOptions(X509Certificate2 publicCertificate, string pfxPath, 
    string pfxPassword)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| publicCertificate | X509Certificate2 | Det offentliga certifikatet. |
| pfxPath | String | Sökvägen till p12‑arkivfilen. |
| pfxPassword | String | Lösenordet för p12‑arkivfilen. |

### Se även

* class [CertificateEncryptionOptions](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


