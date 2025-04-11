---
title: ExternalSignature.ExternalSignature
second_title: Aspose.PDF for .NET API Reference
description: Constructor de ExternalSignature. Crea una firma PKCS7 separada utilizando un X509Certificate2. Soporta tokens de tarjetas inteligentes USB sin claves privadas exportables.
type: docs
weight: 10
url: /es/net/aspose.pdf.forms/externalsignature/externalsignature/
---
## ExternalSignature(X509Certificate2) {#constructor}

Crea una firma PKCS#7 `(detached)` separada utilizando un X509Certificate2. Soporta tarjetas inteligentes USB, tokens sin claves privadas exportables.

```csharp
public ExternalSignature(X509Certificate2 certificate)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| certificate | X509Certificate2 | El certificado con la clave privada. |

## Observaciones

El algoritmo de resumen se seleccionará automáticamente en función de los datos de la clave del certificado.

### Véase También

* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(X509Certificate2, DigestHashAlgorithm) {#constructor_1}

Crea una firma PKCS#7 `(detached)` separada utilizando un X509Certificate2. Soporta tarjetas inteligentes USB, tokens sin claves privadas exportables.

```csharp
public ExternalSignature(X509Certificate2 certificate, DigestHashAlgorithm digestHashAlgorithm)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| certificate | X509Certificate2 | El certificado con la clave privada. |
| digestHashAlgorithm | DigestHashAlgorithm | El algoritmo de resumen para firmar un documento. |

### Véase También

* enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(X509Certificate2, bool) {#constructor_2}

Crea una firma PKCS#7 separada utilizando un X509Certificate2. Soporta tarjetas inteligentes USB, tokens sin claves privadas exportables.

```csharp
public ExternalSignature(X509Certificate2 certificate, bool detached)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| certificate | X509Certificate2 | El certificado con la clave privada. |
| detached | Boolean | Verdadero si la firma debe ser separada, de lo contrario falso. |

## Observaciones

Para detached establecido en falso, el algoritmo de resumen siempre será `SHA1`. De lo contrario, el algoritmo de resumen se seleccionará automáticamente en función de los datos de la clave del certificado (ver Auto).

### Véase También

* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(string, bool) {#constructor_4}

Crea una firma PKCS#7 utilizando un X509Certificate2 como cadena base64.

```csharp
public ExternalSignature(string base64, bool detached)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| base64 | String | X509Certificate2 como cadena base64. |
| detached | Boolean | Verdadero si la firma debe ser separada, de lo contrario falso. |

## Observaciones

Para detached establecido en falso, el algoritmo de resumen siempre será `SHA1`. De lo contrario, el algoritmo de resumen se seleccionará automáticamente en función de los datos de la clave del certificado (ver Auto).

### Véase También

* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(string, DigestHashAlgorithm) {#constructor_3}

Crea una firma PKCS#7 `(detached)` utilizando un X509Certificate2 como cadena base64.

```csharp
public ExternalSignature(string base64, DigestHashAlgorithm digestHashAlgorithm)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| base64 | String | X509Certificate2 como cadena base64. |
| digestHashAlgorithm | DigestHashAlgorithm | El algoritmo de resumen para firmar un documento. |

### Véase También

* enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)