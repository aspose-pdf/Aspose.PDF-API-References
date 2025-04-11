---
title: ExternalSignature.ExternalSignature
second_title: Aspose.PDF for .NET API Reference
description: Costruttore di ExternalSignature. Crea una firma PKCS7 staccata utilizzando un X509Certificate2. Supporta i token delle smartcard usb senza chiavi private esportabili
type: docs
weight: 10
url: /it/net/aspose.pdf.forms/externalsignature/externalsignature/
---
## ExternalSignature(X509Certificate2) {#constructor}

Crea una firma PKCS#7 `(detached)` staccata utilizzando un X509Certificate2. Supporta le smartcard usb, i token senza chiavi private esportabili.

```csharp
public ExternalSignature(X509Certificate2 certificate)
```

| Parameter | Type | Description |
| --- | --- | --- |
| certificate | X509Certificate2 | Il certificato con la chiave privata. |

## Remarks

L'algoritmo di digest sarà selezionato automaticamente in base ai dati della chiave del certificato.

### See Also

* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(X509Certificate2, DigestHashAlgorithm) {#constructor_1}

Crea una firma PKCS#7 `(detached)` staccata utilizzando un X509Certificate2. Supporta le smartcard usb, i token senza chiavi private esportabili.

```csharp
public ExternalSignature(X509Certificate2 certificate, DigestHashAlgorithm digestHashAlgorithm)
```

| Parameter | Type | Description |
| --- | --- | --- |
| certificate | X509Certificate2 | Il certificato con la chiave privata. |
| digestHashAlgorithm | DigestHashAlgorithm | L'algoritmo di digest per firmare un documento. |

### See Also

* enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(X509Certificate2, bool) {#constructor_2}

Crea una firma PKCS#7 staccata utilizzando un X509Certificate2. Supporta le smartcard usb, i token senza chiavi private esportabili.

```csharp
public ExternalSignature(X509Certificate2 certificate, bool detached)
```

| Parameter | Type | Description |
| --- | --- | --- |
| certificate | X509Certificate2 | Il certificato con la chiave privata. |
| detached | Boolean | Vero se la firma deve essere staccata, altrimenti falso. |

## Remarks

Per staccato impostato su falso, l'algoritmo di digest sarà sempre `SHA1`. Altrimenti, l'algoritmo di digest sarà selezionato automaticamente in base ai dati della chiave del certificato (vedi Auto).

### See Also

* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(string, bool) {#constructor_4}

Crea una firma PKCS#7 utilizzando un X509Certificate2 come stringa base64.

```csharp
public ExternalSignature(string base64, bool detached)
```

| Parameter | Type | Description |
| --- | --- | --- |
| base64 | String | X509Certificate2 come stringa base64. |
| detached | Boolean | Vero se la firma deve essere staccata, altrimenti falso. |

## Remarks

Per staccato impostato su falso, l'algoritmo di digest sarà sempre `SHA1`. Altrimenti, l'algoritmo di digest sarà selezionato automaticamente in base ai dati della chiave del certificato (vedi Auto).

### See Also

* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(string, DigestHashAlgorithm) {#constructor_3}

Crea una firma PKCS#7 `(detached)` utilizzando un X509Certificate2 come stringa base64.

```csharp
public ExternalSignature(string base64, DigestHashAlgorithm digestHashAlgorithm)
```

| Parameter | Type | Description |
| --- | --- | --- |
| base64 | String | X509Certificate2 come stringa base64. |
| digestHashAlgorithm | DigestHashAlgorithm | L'algoritmo di digest per firmare un documento. |

### See Also

* enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)