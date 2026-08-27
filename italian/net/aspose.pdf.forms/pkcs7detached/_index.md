---
title: "Classe PKCS7Detached"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Forms.PKCS7Detached. Rappresenta l'oggetto PKCS7 conforme alla specifica PKCS7 nella RFC 2315 di Internet PKCS 7 Cryptographic Message Syntax Version 1.5. Il digest del messaggio firmato originale sull'intervallo di byte del documento è incorporato nel normale campo PKCS7 SignedData. Nessun dato è incapsulato nel campo PKCS7 SignedData."
type: docs
weight: 5310
url: /it/net/aspose.pdf.forms/pkcs7detached/
---
## PKCS7Detached class

Rappresenta l'oggetto PKCS#7 che conforma alla specifica PKCS#7 nell'Internet RFC 2315, PKCS #7: Cryptographic Message Syntax, Versione 1.5. Il digest originale del messaggio firmato sul byte range del Document è incorporato come campo SignedData normale di PKCS#7. Nessun dato deve essere incapsulato nel campo SignedData di PKCS#7.

```csharp
public sealed class PKCS7Detached : Signature
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PKCS7Detached](pkcs7detached/#constructor)() | Inizializza una nuova istanza della classe `PKCS7Detached`. |
| [PKCS7Detached](pkcs7detached/#constructor_1)(DigestHashAlgorithm) | Inizializza una nuova istanza della classe `PKCS7Detached`. |
| [PKCS7Detached](pkcs7detached/#constructor_2)(Stream) | Inizializza una nuova istanza della classe `PKCS7Detached`. |
| [PKCS7Detached](pkcs7detached/#constructor_3)(Stream, DigestHashAlgorithm) | Inizializza una nuova istanza della classe `PKCS7Detached`. |
| [PKCS7Detached](pkcs7detached/#constructor_4)(Stream, string) | Inizializza una nuova istanza della classe `PKCS7Detached`. |
| [PKCS7Detached](pkcs7detached/#constructor_6)(string, string) | Inizializza una nuova istanza della classe `PKCS7Detached`. |
| [PKCS7Detached](pkcs7detached/#constructor_5)(Stream, string, DigestHashAlgorithm) | Inizializza una nuova istanza della classe `PKCS7Detached`. |
| [PKCS7Detached](pkcs7detached/#constructor_7)(string, string, DigestHashAlgorithm) | Inizializza una nuova istanza della classe `PKCS7Detached`. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority/) { get; set; } | Il nome della persona o dell'autorità che firma il documento. |
| [AvoidEstimatingSignatureLength](../../aspose.pdf.forms/signature/avoidestimatingsignaturelength/) { get; set; } | Ottiene e imposta un'opzione che indica se evitare di stimare la lunghezza di una firma. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange/) { get; } | Un array di coppie di interi (offset iniziale in byte, lunghezza in byte) che descrive l'intervallo esatto di byte per il calcolo del digest. |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo/) { get; set; } | Informazioni fornite dal firmatario per consentire al destinatario di contattare il firmatario per verificare la firma, ad esempio un numero di telefono. |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance/) { get; set; } | Ottiene/imposta l'aspetto personalizzato. |
| [CustomSignHash](../../aspose.pdf.forms/signature/customsignhash/) { get; set; } | Il delegato per la firma personalizzata dell'hash del documento. |
| [Date](../../aspose.pdf.forms/signature/date/) { get; set; } | L'ora della firma. |
| [DefaultSignatureLength](../../aspose.pdf.forms/signature/defaultsignaturelength/) { get; set; } | Ottiene o imposta la lunghezza predefinita per i dati della firma in byte. |
| [Location](../../aspose.pdf.forms/signature/location/) { get; set; } | Il nome host della CPU o la posizione fisica della firma. |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings/) { get; set; } | Ottiene/imposta le impostazioni OCSP. |
| [Reason](../../aspose.pdf.forms/signature/reason/) { get; set; } | Il motivo della firma, ad esempio (I agree, Pip B.). |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | Obbliga a mostrare/nascondere le proprietà della firma. Nel caso in cui ShowProperties è true, il campo firma ha un formato di aspetto predefinito (stringhe da rappresentare): ------------------------------------------- Digitally signed by {certificate subject} Date: {signature.Date} Reason: {signature.Reason} Location: {signature.Location} ------------------------------------------- dove {X} è un segnaposto per il valore X. Inoltre la firma può avere un'immagine; in questo caso le stringhe elencate sono posizionate sull'immagine. ShowProperties è true per impostazione predefinita. |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings/) { get; set; } | Ottiene/imposta le impostazioni del timestamp. |
| [UseLtv](../../aspose.pdf.forms/signature/useltv/) { get; set; } | Ottiene/imposta il flag di convalida LTV. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [GetSignatureAlgorithmInfo](../../aspose.pdf.forms/signature/getsignaturealgorithminfo/)() | Recupera informazioni sull'algoritmo di firma utilizzato nella firma. |
| [Verify](../../aspose.pdf.forms/signature/verify/)() | Verifica il documento rispetto a questa firma e restituisce true se il documento è valido, altrimenti false. |
| [Verify](../../aspose.pdf.forms/signature/verify/)(ValidationOptions, out ValidationResult) | Verifica il documento rispetto a questa firma e restituisce true se il documento è valido, altrimenti false. |
| [Verify](../../aspose.pdf.forms/signature/verify/)(X509Certificate2, ValidationOptions, out ValidationResult) | Verifica il documento rispetto a questa firma e restituisce true se il documento è valido, altrimenti false. La verifica viene eseguita utilizzando il certificato della chiave pubblica esterna. |

### Vedi anche

* class [Signature](../signature/)
* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)


