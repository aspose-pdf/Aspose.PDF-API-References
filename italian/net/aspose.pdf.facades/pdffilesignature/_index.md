---
title: PdfFileSignature
second_title: Aspose.PDF per .NET API Reference
description: Rappresenta una classe per firmare un file pdf con un certificato.
type: docs
weight: 2570
url: /it/net/aspose.pdf.facades/pdffilesignature/
---
## PdfFileSignature class

Rappresenta una classe per firmare un file pdf con un certificato.

```csharp
public sealed class PdfFileSignature : SaveableFacade
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfFileSignature](pdffilesignature#constructor)() | Il costruttore della classe PdfFileSignature. |
| [PdfFileSignature](pdffilesignature#constructor_1)(Document) | Inizializza nuovo[`PdfFileSignature`](../pdffilesignature) oggetto sulla base del*document* . |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Ottiene la facciata del documento su cui sta lavorando. |
| [IsCertified](../../aspose.pdf.facades/pdffilesignature/iscertified) { get; } | Ottiene il flag che determina se un documento è certificato o meno. |
| [IsLtvEnabled](../../aspose.pdf.facades/pdffilesignature/isltvenabled) { get; } | Ottiene il flag abilitato LTV. |
| [SignatureAppearance](../../aspose.pdf.facades/pdffilesignature/signatureappearance) { get; set; } | Imposta o ottiene un aspetto grafico per la firma. Il valore della proprietà rappresenta il nome del file immagine. |
| [SignatureAppearanceStream](../../aspose.pdf.facades/pdffilesignature/signatureappearancestream) { get; set; } | Imposta o ottiene un aspetto grafico per la firma. Il valore della proprietà rappresenta il flusso di immagini. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Inizializza la facciata. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf#bindpdf_1)(Stream) | Associa un flusso Pdf per la modifica. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf#bindpdf_2)(string) | Associa un file Pdf per la modifica. |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify#certify_1)(string, DocMDPSignature) | Certificare il documento con la firma MDP che è apposto nel campo firma già presentato. Prima di firmare il campo firma deve essere vuoto, cioè il campo non deve contenere il dizionario delle firme. Quindi il documento pdf ha già il campo firma, non dovresti fornire il luogo per timbrare la firma, la pagina e il rettangolo corrispondenti sono presi dal campo della firma che si trova dal nome della firma (vedi parametro sigName). |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify#certify)(int, string, string, string, bool, Rectangle, DocMDPSignature) | Certificare il documento con la firma MDP. Tali dati come motivo firma, contatto e ubicazione devono essere forniti dalle corrispondenti proprietà dell'oggetto Firma sig. |
| override [Close](../../aspose.pdf.facades/pdffilesignature/close)() | Chiude la facciata. |
| [ContainsSignature](../../aspose.pdf.facades/pdffilesignature/containssignature)() | Verifica se il pdf ha una firma digitale o meno. |
| [ContainsUsageRights](../../aspose.pdf.facades/pdffilesignature/containsusagerights)() | Verifica se il pdf ha o meno diritti di utilizzo. |
| [CoversWholeDocument](../../aspose.pdf.facades/pdffilesignature/coverswholedocument)(string) | Verifica se la firma copre l'intero documento. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Elimina la facciata. |
| [ExtractCertificate](../../aspose.pdf.facades/pdffilesignature/extractcertificate)(string) | Estrae il singolo certificato X.509 della firma come flusso. |
| [ExtractImage](../../aspose.pdf.facades/pdffilesignature/extractimage)(string) | Estrae l'immagine della firma. |
| [GetAccessPermissions](../../aspose.pdf.facades/pdffilesignature/getaccesspermissions)() | Restituisce il valore delle autorizzazioni di accesso del documento certificato in base al tipo di firma MDP. |
| [GetBlankSignNames](../../aspose.pdf.facades/pdffilesignature/getblanksignnames)() | Ottiene i nomi di tutti i campi firma vuoti. |
| [GetContactInfo](../../aspose.pdf.facades/pdffilesignature/getcontactinfo)(string) | Ottiene le informazioni di contatto di una firma. |
| [GetDateTime](../../aspose.pdf.facades/pdffilesignature/getdatetime)(string) | Ottiene la data e l'ora della firma. |
| [GetLocation](../../aspose.pdf.facades/pdffilesignature/getlocation)(string) | Ottiene la posizione di una firma. |
| [GetReason](../../aspose.pdf.facades/pdffilesignature/getreason)(string) | Ottiene il motivo di una firma. |
| [GetRevision](../../aspose.pdf.facades/pdffilesignature/getrevision)(string) | Ottiene la revisione di una firma. |
| [GetSignerName](../../aspose.pdf.facades/pdffilesignature/getsignername)(string) | Ottiene il nome della persona o dell'organizzazione che ha firmato il documento pdf. |
| [GetSignNames](../../aspose.pdf.facades/pdffilesignature/getsignnames)(bool) | Ottiene i nomi di tutte le firme non vuote. |
| [GetTotalRevision](../../aspose.pdf.facades/pdffilesignature/gettotalrevision)() | Ottiene la revisione totale. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature#removesignature)(string) | Rimuovere la firma in base al nome della firma. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature#removesignature_1)(string, bool) | Rimuove la firma in base al nome della firma. |
| [RemoveUsageRights](../../aspose.pdf.facades/pdffilesignature/removeusagerights)() | Rimuove la voce dei diritti di utilizzo. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save#save_1)(Stream) | Salva il risultato PDF in streaming. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save#save_2)(string) | Salva il risultato PDF su file. |
| [SetCertificate](../../aspose.pdf.facades/pdffilesignature/setcertificate)(string, string) | Imposta il file del certificato e la password per la routine di firma. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_4)(string, Signature) | Firma il documento con il tipo specificato firma che è posto nel campo firma già presentato. Prima di firmare il campo firma deve essere vuoto, cioè il campo non deve contenere dizionario firme. Quindi il documento pdf ha già il campo firma, non dovresti fornire il luogo per apporre la firma, pagina e rettangolo corrispondenti sono presi dal campo firma che si trova per nome firma (vedi parametro SigName). Tali dati come motivo firma, contatto e posizione devono essere forniti dalle proprietà corrispondenti dell'oggetto Firma sig. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign)(int, bool, Rectangle, Signature) | Firma il documento con la firma di tipo specificata. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_5)(string, string, string, string, Signature) | Firma il documento con il tipo specificato firma che è posto nel campo firma già presentato. Prima di firmare il campo firma deve essere vuoto, cioè il campo non deve contenere dizionario firme. Quindi il documento pdf ha già il campo firma, non dovresti fornire il luogo per apporre la firma, la pagina e il rettangolo corrispondenti sono presi dal campo della firma che si trova per nome della firma (vedi parametro SigName). |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_1)(int, string, string, string, bool, Rectangle) | Apporta una firma sul documento pdf. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_2)(int, string, string, string, bool, Rectangle, Signature) | Firma il documento con la firma di tipo specificata. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign#sign_3)(int, string, string, string, string, bool, Rectangle, Signature) | Firma il documento con la firma del tipo specificata che è inserita nel campo della firma già presentato. Prima di firmare il documento pdf dovrebbe avere già il campo della firma, la pagina e il rettangolo corrispondenti sono presi dal campo della firma che si trova dal nome della firma (vedi parametro SigName) . |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature)(string) | Verifica la validità di una firma. |
| [VerifySigned](../../aspose.pdf.facades/pdffilesignature/verifysigned)(string) | Verifica la validità di una firma. |

### Guarda anche

* class [SaveableFacade](../saveablefacade)
* spazio dei nomi [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
