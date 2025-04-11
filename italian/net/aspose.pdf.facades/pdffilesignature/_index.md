---
title: Class PdfFileSignature
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.PdfFileSignature. Rappresenta una classe per firmare un file pdf con un certificato
type: docs
weight: 4560
url: /it/net/aspose.pdf.facades/pdffilesignature/
---
## Classe PdfFileSignature

Rappresenta una classe per firmare un file pdf con un certificato.

```csharp
public sealed class PdfFileSignature : SaveableFacade
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PdfFileSignature](pdffilesignature/#constructor)() | Il costruttore della classe PdfFileSignature. |
| [PdfFileSignature](pdffilesignature/#constructor_1)(Document) | Inizializza un nuovo oggetto `PdfFileSignature` sulla base del *documento*. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Ottiene il documento su cui la facciata sta lavorando. |
| [IsCertified](../../aspose.pdf.facades/pdffilesignature/iscertified/) { get; } | Ottiene il flag che determina se un documento è certificato o meno. |
| [IsLtvEnabled](../../aspose.pdf.facades/pdffilesignature/isltvenabled/) { get; } | Ottiene il flag LTV abilitato. |
| [SignatureAppearance](../../aspose.pdf.facades/pdffilesignature/signatureappearance/) { get; set; } | Imposta o ottiene un aspetto grafico per la firma. Il valore della proprietà rappresenta il nome del file immagine. |
| [SignatureAppearanceStream](../../aspose.pdf.facades/pdffilesignature/signatureappearancestream/) { get; set; } | Imposta o ottiene un aspetto grafico per la firma. Il valore della proprietà rappresenta lo stream dell'immagine. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Inizializza la facciata. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_1)(Stream) | Collega uno stream Pdf per la modifica. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_2)(string) | Collega un file Pdf per la modifica. |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify_1)(string, DocMDPSignature) | Certifica il documento con la firma MDP che è posizionata nel campo di firma già presentato. Prima di firmare, il campo di firma deve essere vuoto, cioè il campo non deve contenere un dizionario di firma. Pertanto, il documento pdf ha già un campo di firma, non è necessario fornire il luogo per timbrare la firma, la pagina e il rettangolo corrispondenti sono presi dal campo di firma che si trova per nome della firma (vedi parametro sigName). |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify)(int, string, string, string, bool, Rectangle, DocMDPSignature) | Certifica il documento con la firma MDP. Dati come motivo della firma, contatto e posizione devono essere forniti dalle corrispondenti proprietà dell'oggetto Signature sig. |
| override [Close](../../aspose.pdf.facades/pdffilesignature/close/)() | Chiude la facciata. |
| [ContainsSignature](../../aspose.pdf.facades/pdffilesignature/containssignature/)() | Controlla se il pdf ha una firma digitale o meno. |
| [ContainsUsageRights](../../aspose.pdf.facades/pdffilesignature/containsusagerights/)() | Controlla se il pdf ha diritti d'uso o meno. |
| [CoversWholeDocument](../../aspose.pdf.facades/pdffilesignature/coverswholedocument/#coverswholedocument)(SignatureName) | Controlla se la firma copre l'intero documento. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Smaltisce la facciata. |
| [ExtractCertificate](../../aspose.pdf.facades/pdffilesignature/extractcertificate/#extractcertificate)(SignatureName) | Estrae il singolo certificato X.509 della firma come stream. |
| [ExtractImage](../../aspose.pdf.facades/pdffilesignature/extractimage/#extractimage)(SignatureName) | Estrae l'immagine della firma. |
| [GetAccessPermissions](../../aspose.pdf.facades/pdffilesignature/getaccesspermissions/)() | Restituisce il valore dei permessi di accesso del documento certificato dal tipo di firma MDP. |
| [GetBlankSignatureNames](../../aspose.pdf.facades/pdffilesignature/getblanksignaturenames/)() | Ottiene i nomi di tutti i campi di firma vuoti. |
| [GetContactInfo](../../aspose.pdf.facades/pdffilesignature/getcontactinfo/#getcontactinfo)(SignatureName) | Ottiene le informazioni di contatto di una firma. |
| [GetDateTime](../../aspose.pdf.facades/pdffilesignature/getdatetime/#getdatetime)(SignatureName) | Ottiene la data e l'ora della firma. |
| [GetLocation](../../aspose.pdf.facades/pdffilesignature/getlocation/#getlocation)(SignatureName) | Ottiene la posizione di una firma. |
| [GetReason](../../aspose.pdf.facades/pdffilesignature/getreason/#getreason)(SignatureName) | Ottiene il motivo di una firma. |
| [GetRevision](../../aspose.pdf.facades/pdffilesignature/getrevision/#getrevision)(SignatureName) | Ottiene la revisione di una firma. |
| [GetSignatureNames](../../aspose.pdf.facades/pdffilesignature/getsignaturenames/)(bool) | Ottiene i nomi di tutte le firme non vuote. |
| [GetSignaturesInfo](../../aspose.pdf.facades/pdffilesignature/getsignaturesinfo/)() | Recupera informazioni su tutti gli algoritmi di firma presenti nel documento PDF. |
| [GetSignerName](../../aspose.pdf.facades/pdffilesignature/getsignername/#getsignername)(SignatureName) | Ottiene il nome della persona o dell'organizzazione che firma il documento pdf. |
| [GetTotalRevision](../../aspose.pdf.facades/pdffilesignature/gettotalrevision/)() | Ottiene la revisione totale. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature)(SignatureName) | Rimuove la firma in base al nome della firma. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature_1)(SignatureName, bool) | Rimuove la firma in base al nome della firma. |
| [RemoveSignatures](../../aspose.pdf.facades/pdffilesignature/removesignatures/)() | Rimuove tutte le firme. |
| [RemoveUsageRights](../../aspose.pdf.facades/pdffilesignature/removeusagerights/)() | Rimuove l'entrata dei diritti d'uso. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_1)(Stream) | Salva il PDF risultante nello stream. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_2)(string) | Salva il PDF risultante nel file. |
| [SetCertificate](../../aspose.pdf.facades/pdffilesignature/setcertificate/)(string, string) | Imposta il file del certificato e la password per la routine di firma. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_4)(string, Signature) | Firma il documento con il tipo di firma dato che è posizionata nel campo di firma già presentato. Prima di firmare, il campo di firma deve essere vuoto, cioè il campo non deve contenere un dizionario di firma. Pertanto, il documento pdf ha già un campo di firma, non è necessario fornire il luogo per timbrare la firma, la pagina e il rettangolo corrispondenti sono presi dal campo di firma che si trova per nome della firma (vedi parametro SigName). Dati come motivo della firma, contatto e posizione devono essere forniti dalle corrispondenti proprietà dell'oggetto Signature sig. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign)(int, bool, Rectangle, Signature) | Firma il documento con il tipo di firma dato. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_5)(string, string, string, string, Signature) | Firma il documento con il tipo di firma dato che è posizionata nel campo di firma già presentato. Prima di firmare, il campo di firma deve essere vuoto, cioè il campo non deve contenere un dizionario di firma. Pertanto, il documento pdf ha già un campo di firma, non è necessario fornire il luogo per timbrare la firma, la pagina e il rettangolo corrispondenti sono presi dal campo di firma che si trova per nome della firma (vedi parametro SigName). |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_1)(int, string, string, string, bool, Rectangle) | Effettua una firma sul documento pdf. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_2)(int, string, string, string, bool, Rectangle, Signature) | Firma il documento con il tipo di firma dato. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_3)(int, string, string, string, string, bool, Rectangle, Signature) | Firma il documento con il tipo di firma dato che è posizionata nel campo di firma già presentato. Prima di firmare, il documento pdf deve già avere un campo di firma, la pagina e il rettangolo corrispondenti sono presi dal campo di firma che si trova per nome della firma (vedi parametro SigName). |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature)(SignatureName) | Controlla la validità di una firma. |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature_1)(SignatureName, ValidationOptions, out ValidationResult) | Controlla la validità di una firma. |

### Vedi Anche

* classe [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)