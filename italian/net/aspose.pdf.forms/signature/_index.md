---
title: Class Signature
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Forms.Signature. Una classe astratta che rappresenta un oggetto firma nel documento pdf. Le firme sono campi con valori di oggetti firma, questi ultimi contengono dati utilizzati per verificare la validità del documento.
type: docs
weight: 5270
url: /it/net/aspose.pdf.forms/signature/
---
## Classe Firma

Una classe astratta che rappresenta un oggetto firma nel documento pdf. Le firme sono campi con valori di oggetti firma, questi ultimi contengono dati utilizzati per verificare la validità del documento.

```csharp
public abstract class Signature
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Signature](signature/#constructor)() | Inizializza una nuova istanza della classe `Signature`. |
| [Signature](signature/#constructor_1)(Stream, string) | Inizializza una nuova istanza della classe `Signature`. |
| [Signature](signature/#constructor_2)(string, string) | Inizializza una nuova istanza della classe `Signature`. |

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
| [ShowProperties](../../aspose.pdf.forms/signature/showproperties/) { get; set; } | Forza a mostrare/nascondere le proprietà della firma. Nel caso in cui ShowProperties sia true, il campo firma ha un formato predefinito di apparizione (stringhe da rappresentare): ------------------------------------------- Firmato digitalmente da {certificate subject} Data: {signature.Date} Motivo: {signature.Reason} Luogo: {signature.Location} ------------------------------------------- dove {X} è un segnaposto per il valore X. Inoltre, la firma può avere un'immagine, in questo caso le stringhe elencate sono posizionate sopra l'immagine. ShowProperties è true per impostazione predefinita. |
| [TimestampSettings](../../aspose.pdf.forms/signature/timestampsettings/) { get; set; } | Ottiene/imposta le impostazioni del timestamp. |
| [UseLtv](../../aspose.pdf.forms/signature/useltv/) { get; set; } | Ottiene/imposta il flag di validazione ltv. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [GetSignatureAlgorithmInfo](../../aspose.pdf.forms/signature/getsignaturealgorithminfo/)() | Recupera informazioni sull'algoritmo di firma utilizzato nella firma. |
| [Verify](../../aspose.pdf.forms/signature/verify/#verify)() | Verifica il documento riguardo a questa firma e restituisce true se il documento è valido, altrimenti false. |
| [Verify](../../aspose.pdf.forms/signature/verify/#verify_1)(ValidationOptions, out ValidationResult) | Verifica il documento riguardo a questa firma e restituisce true se il documento è valido, altrimenti false. |

### Vedi Anche

* namespace [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../)