---
title: ExternalSignature
second_title: Aspose.PDF per .NET API Reference
description: Crea una firma separata PKCS7Detached utilizzando un certificato X5092. Supporta smartcard usb token senza chiavi private esportabili.
type: docs
weight: 2990
url: /it/net/aspose.pdf.forms/externalsignature/
---
## ExternalSignature class

Crea una firma separata PKCS#7Detached utilizzando un certificato X5092. Supporta smartcard usb, token senza chiavi private esportabili.

```csharp
public class ExternalSignature : Signature
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ExternalSignature](externalsignature)(X509Certificate2) | Crea una firma separata PKCS#7Detached utilizzando un certificato X5092. Supporta smartcard usb, token senza chiavi private esportabili. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Authority](../../aspose.pdf.forms/signature/authority) { get; set; } | Il nome della persona o dell'autorità che firma il documento. |
| [ByteRange](../../aspose.pdf.forms/signature/byterange) { get; } | Un array di coppie di interi (offset di byte iniziale, lunghezza in byte) che deve descrivere l'esatto intervallo di byte per il calcolo del digest. |
| [Certificate](../../aspose.pdf.forms/externalsignature/certificate) { get; } | Il certificato con la chiave privata. |
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