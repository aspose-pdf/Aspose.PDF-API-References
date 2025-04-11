---
title: Class ExternalSignature
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Forms.ExternalSignature. Crea una firma PKCS7 staccata utilizzando un X509Certificate2. Supporta token di smartcard usb senza chiavi private esportabili
type: docs
weight: 5040
url: /it/net/aspose.pdf.forms/externalsignature/
---
## Classe ExternalSignature

Crea una firma PKCS#7 staccata utilizzando un X509Certificate2. Supporta smartcard usb, token senza chiavi private esportabili.

```csharp
public class ExternalSignature : Signature
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ExternalSignature](externalsignature/#constructor)(X509Certificate2) | Crea una firma PKCS#7 `(staccata)` utilizzando un X509Certificate2. Supporta smartcard usb, token senza chiavi private esportabili. |
| [ExternalSignature](externalsignature/#constructor_4)(string, bool) | Crea una firma PKCS#7 utilizzando un X509Certificate2 come stringa base64. |
| [ExternalSignature](externalsignature/#constructor_3)(string, DigestHashAlgorithm) | Crea una firma PKCS#7 `(staccata)` utilizzando un X509Certificate2 come stringa base64. |
| [ExternalSignature](externalsignature/#constructor_2)(X509Certificate2, bool) | Crea una firma PKCS#7 staccata utilizzando un X509Certificate2. Supporta smartcard usb, token senza chiavi private esportabili. |
| [ExternalSignature](externalsignature/#constructor_1)(X509Certificate2, DigestHashAlgorithm) | Crea una firma PKCS#7 `(staccata)` utilizzando un X509Certificate2. Supporta smartcard usb, token senza chiavi private esportabili. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | Il nome della persona o dell'autorità che firma il documento. |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | Ottiene e imposta un'opzione che indica se evitare di stimare la lunghezza di una firma. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | Un array di coppie di interi (offset di byte iniziale, lunghezza in byte) che descrivono l'esatto intervallo di byte per il calcolo del digest. |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | Informazioni fornite dal firmatario per consentire a un destinatario di contattare il firmatario per verificare la firma, ad esempio un numero di telefono. |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | Ottiene/imposta l'aspetto personalizzato. |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | Il delegato per firmare in modo personalizzato l'hash del documento. |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | Il momento della firma. |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | Ottiene o imposta la lunghezza predefinita per i dati della firma in byte. |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | Il nome host della CPU o la posizione fisica della firma. |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | Ottiene/imposta le impostazioni ocsp. |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | Il motivo della firma, come (Accetto, Pip B.). |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | Forza a mostrare/nascondere le proprietà della firma. Nel caso in cui ShowProperties sia true, il campo della firma ha un formato predefinito di apparizione (stringhe da rappresentare): ------------------------------------------- Firmato digitalmente da {certificate subject} Data: {signature.Date} Motivo: {signature.Reason} Luogo: {signature.Location} ------------------------------------------- dove {X} è un segnaposto per il valore X. Inoltre, la firma può avere un'immagine, in questo caso le stringhe elencate sono posizionate sopra l'immagine. ShowProperties è true per impostazione predefinita. |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings/) { get; set; } | Ottiene/imposta le impostazioni del timestamp. |
| [UseLtv](../../aspose.pdf.forms/signature/useltv/) { get; set; } | Ottiene/imposta il flag di validazione ltv. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [GetSignatureAlgorithmInfo](../../aspose.pdf.forms/signature/getsignaturealgorithminfo/)() | Recupera informazioni sull'algoritmo di firma utilizzato nella firma. |
| [Verify](../../aspose.pdf.forms/signature/verify/)() | Verifica il documento riguardo a questa firma e restituisce true se il documento è valido, altrimenti false. |
| [Verify](../../aspose.pdf.forms/signature/verify/)(ValidationOptions, out ValidationResult) | Verifica il documento riguardo a questa firma e restituisce true se il documento è valido, altrimenti false. |

## Campi

| Nome | Descrizione |
| --- | --- |
| readonly [Certificate](../../aspose.pdf.forms/externalsignature/certificate/) | Il certificato con la chiave privata. |

### Vedi Anche

* classe [Signature](../signature/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)