---
title: "CertificateEncryptionOptions.CertificateEncryptionOptions"
second_title: "Aspose.PDF para .NET Referencia de API"
description: "CertificateEncryptionOptions constructor. Crea una instancia de la clase CertificateEncryptionOptions"
type: docs
weight: 10
url: /es/net/aspose.pdf.security/certificateencryptionoptions/certificateencryptionoptions/
---
## CertificateEncryptionOptions(string, string, string) {#constructor_3}

Crea una instancia de la clase [`CertificateEncryptionOptions`](../).

```csharp
public CertificateEncryptionOptions(string publicCertificatePath, string pfxPath, 
    string pfxPassword)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| publicCertificatePath | Cadena | La ruta del archivo del certificado público. |
| pfxPath | Cadena | La ruta del archivo p12. |
| pfxPassword | Cadena | La contraseña del archivo p12. |

### Ver también

* class [CertificateEncryptionOptions](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)

---

## CertificateEncryptionOptions(string, StoreName, StoreLocation) {#constructor_2}

Crea una instancia de la clase [`CertificateEncryptionOptions`](../).

```csharp
public CertificateEncryptionOptions(string publicCertificatePath, 
    StoreName storeName = StoreName.My, StoreLocation storeLocation = StoreLocation.CurrentUser)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| publicCertificatePath | Cadena | La ruta del archivo del certificado público. |
| storeName | StoreName | El nombre del almacén para obtener un certificado de clave privada. |
| storeLocation | StoreLocation | La ubicación del almacén para obtener un certificado de clave privada. |

### Ver también

* class [CertificateEncryptionOptions](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)

---

## CertificateEncryptionOptions(X509Certificate2, StoreName, StoreLocation) {#constructor}

Crea una instancia de la clase [`CertificateEncryptionOptions`](../).

```csharp
public CertificateEncryptionOptions(X509Certificate2 publicCertificate, 
    StoreName storeName = StoreName.My, StoreLocation storeLocation = StoreLocation.CurrentUser)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| publicCertificate | X509Certificate2 | El certificado público. |
| storeName | StoreName | El nombre del almacén para obtener un certificado de clave privada. |
| storeLocation | StoreLocation | La ubicación del almacén para obtener un certificado de clave privada. |

### Ver también

* class [CertificateEncryptionOptions](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)

---

## CertificateEncryptionOptions(X509Certificate2, string, string) {#constructor_1}

Crea una instancia de la clase [`CertificateEncryptionOptions`](../).

```csharp
public CertificateEncryptionOptions(X509Certificate2 publicCertificate, string pfxPath, 
    string pfxPassword)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| publicCertificate | X509Certificate2 | El certificado público. |
| pfxPath | Cadena | La ruta del archivo p12. |
| pfxPassword | Cadena | La contraseña del archivo p12. |

### Ver también

* class [CertificateEncryptionOptions](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


