---
title: PKCS7
second_title: Aspose.PDF per .NET API Reference
description: Rappresenta loggetto PKCS7 conforme alla specifica PKCS7 in Internet RFC 2315 PKCS 7 Cryptographic Message Syntax Version 1.5. Il digest SHA1 dellintervallo di byte del documento è incapsulato nel campo PKCS7 SignedData .
type: docs
weight: 3130
url: /it/net/aspose.pdf.forms/pkcs7/
---
## PKCS7 class

Rappresenta l'oggetto PKCS#7 conforme alla specifica PKCS#7 in Internet RFC 2315, PKCS #7: Cryptographic Message Syntax, Version 1.5. Il digest SHA1 dell'intervallo di byte del documento è incapsulato nel campo PKCS#7 SignedData .

```csharp
public sealed class PKCS7 : Signature
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PKCS7](pkcs7#constructor)() | Inizializza la nuova istanza di[`PKCS7`](../pkcs7) classe. |
| [PKCS7](pkcs7#constructor_1)(Stream, string) | Inizializza la nuova istanza di[`PKCS7`](../pkcs7) classe. |
| [PKCS7](pkcs7#constructor_2)(string, string) | Inizializza la nuova istanza di[`PKCS7`](../pkcs7) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority) { get; set; } | Il nome della persona o dell'autorità che firma il documento. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange) { get; } | Un array di coppie di interi (offset di byte iniziale, lunghezza in byte) che deve descrivere l'esatto intervallo di byte per il calcolo del digest. |
| [ContactInfo](../../aspose.pdf.forms/signature/contactinfo) { get; set; } | Informazioni fornite dal firmatario per consentire a un destinatario di contattare il firmatario per verificare la firma, ad esempio un numero di telefono. |
| [CustomAppearance](../../aspose.pdf.forms/signature/customappearance) { get; set; } | Ottiene/imposta l'aspetto personalizzato. |
| [Date](../../aspose.pdf.forms/signature/date) { get; set; } | L'ora della firma. |
| [Location](../../aspose.pdf.forms/signature/location) { get; set; } | Il nome host della CPU o la posizione fisica della firma. |
| [OcspSettings](../../aspose.pdf.forms/signature/ocspsettings) { get; set; } | Ottiene/imposta le impostazioni ocsp. |
| [Reason](../../aspose.pdf.forms/signature/reason) { get; set; } | Il motivo della firma, ad esempio (AccettoРІР‚В¦). |
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties) { get; set; } | Forza per mostrare/nascondere le proprietà della firma. Nel caso in cui ShowProperties sia vero, il campo della firma ha un formato di aspetto predefinito (stringhe da rappresentare): --------------------- ---------------------- Firmato digitalmente da {soggetto del certificato} Data: {signature.Date} Motivo: {signature.Reason} Località: { firma.Posizione} ------------------------------------------- dove {X} è un segnaposto per il valore X. Anche la firma può avere un'immagine, in questo caso le stringhe elencate vengono posizionate sopra l'immagine. ShowProperties è true per impostazione predefinita. |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings) { get; set; } | Ottiene/imposta le impostazioni del timestamp. |
| [UseLtv](../../aspose.pdf.forms/signature/useltv) { get; set; } | Ottiene/imposta il flag di convalida ltv. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Verify](../../aspose.pdf.forms/signature/verify)() | Verifica il documento relativo a questa firma e restituisce true se il documento è valido o altrimenti false. |

### Guarda anche

* class [Signature](../signature)
* spazio dei nomi [Aspose.Pdf.Forms](../../aspose.pdf.forms)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->