---
title: "ExternalSignature.ExternalSignature"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "ExternalSignature constructor. Crea una firma PKCS7 detached separata utilizzando un X509Certificate2. Supporta token smartcard USB senza chiavi private esportabili"
type: docs
weight: 10
url: /it/net/aspose.pdf.forms/externalsignature/externalsignature/
---
## ExternalSignature(X509Certificate2) {#constructor}

Crea una firma PKCS#7 `(detached)` distaccata utilizzando un X509Certificate2. Supporta smartcard USB, token senza chiavi private esportabili.

```csharp
public ExternalSignature(X509Certificate2 certificate)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| certificato | X509Certificate2 | Il certificato con la chiave privata. |

## Osservazioni

L'algoritmo di digest verrà selezionato automaticamente in base ai dati della chiave del certificato.

### Vedi anche

* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(X509Certificate2, DigestHashAlgorithm) {#constructor_1}

Crea una firma PKCS#7 `(detached)` distaccata utilizzando un X509Certificate2. Supporta smartcard USB, token senza chiavi private esportabili.

```csharp
public ExternalSignature(X509Certificate2 certificate, DigestHashAlgorithm digestHashAlgorithm)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| certificato | X509Certificate2 | Il certificato con la chiave privata. |
| digestHashAlgorithm | DigestHashAlgorithm | L'algoritmo di digest per firmare un documento. |

### Vedi anche

* enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(X509Certificate2, bool) {#constructor_2}

Crea una firma PKCS#7 distaccata utilizzando un X509Certificate2. Supporta smartcard USB, token senza chiavi private esportabili.

```csharp
public ExternalSignature(X509Certificate2 certificate, bool detached)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| certificato | X509Certificate2 | Il certificato con la chiave privata. |
| separato | Boolean | True se la firma deve essere separata, altrimenti false. |

## Osservazioni

Se detached è impostato su false, l'algoritmo di digest sarà sempre `SHA1`. Altrimenti, l'algoritmo di digest sarà selezionato automaticamente in base ai dati della chiave del certificato (vedi Auto).

### Vedi anche

* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(string, bool) {#constructor_4}

Crea una firma PKCS#7 utilizzando un X509Certificate2 come stringa base64.

```csharp
public ExternalSignature(string base64, bool detached)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| base64 | String | X509Certificate2 come stringa base64. |
| separato | Boolean | True se la firma deve essere separata, altrimenti false. |

## Osservazioni

Se detached è impostato su false, l'algoritmo di digest sarà sempre `SHA1`. Altrimenti, l'algoritmo di digest sarà selezionato automaticamente in base ai dati della chiave del certificato (vedi Auto).

### Vedi anche

* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExternalSignature(string, DigestHashAlgorithm) {#constructor_3}

Crea una firma PKCS#7 `(detached)` utilizzando un X509Certificate2 come stringa base64.

```csharp
public ExternalSignature(string base64, DigestHashAlgorithm digestHashAlgorithm)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| base64 | String | X509Certificate2 come stringa base64. |
| digestHashAlgorithm | DigestHashAlgorithm | L'algoritmo di digest per firmare un documento. |

### Vedi anche

* enum [DigestHashAlgorithm](../../../aspose.pdf/digesthashalgorithm/)
* class [ExternalSignature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


