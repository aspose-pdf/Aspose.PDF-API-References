---
title: "Classe PdfFileSignature"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Facades.PdfFileSignature. Rappresenta una classe per firmare un file PDF con un certificato"
type: docs
weight: 4680
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
| [PdfFileSignature](pdffilesignature/#constructor)() | Il costruttore della classe PdfFileSignature. |
| [PdfFileSignature](pdffilesignature/#constructor_1)(Document) | Inizializza un nuovo oggetto `PdfFileSignature` sulla base del *documento*. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Ottiene il facade del documento su cui sta lavorando. |
| [IsCertified](../../aspose.pdf.facades/pdffilesignature/iscertified/) { get; } | Restituisce il flag che determina se un documento è certificato o meno. |
| [IsLtvEnabled](../../aspose.pdf.facades/pdffilesignature/isltvenabled/) { get; } | Restituisce il flag LTV abilitato. |
| [SignatureAppearance](../../aspose.pdf.facades/pdffilesignature/signatureappearance/) { get; set; } | Imposta o ottiene un aspetto grafico per la firma. Il valore della proprietà rappresenta il nome del file immagine. |
| [SignatureAppearanceStream](../../aspose.pdf.facades/pdffilesignature/signatureappearancestream/) { get; set; } | Imposta o ottiene un aspetto grafico per la firma. Il valore della proprietà rappresenta lo stream dell'immagine. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Inizializza il facade. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_1)(Stream) | Associa uno stream PDF per la modifica. |
| override [BindPdf](../../aspose.pdf.facades/pdffilesignature/bindpdf/#bindpdf_2)(string) | Associa un file PDF per la modifica. |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify_1)(string, DocMDPSignature) | Certifica il documento con la firma MDP che è posizionata in un campo firma già presente. Prima della firma il campo firma deve essere vuoto, cioè il campo non deve contenere il dizionario della firma. Pertanto il documento PDF ha già un campo firma; non è necessario fornire il luogo dove apporre la firma, la pagina corrispondente e Rectangle vengono presi dal campo firma trovato per nome della firma (vedi parametro sigName). |
| [Certify](../../aspose.pdf.facades/pdffilesignature/certify/#certify)(int, string, string, string, bool, Rectangle, DocMDPSignature) | Certifica il documento con la firma MDP. Dati come motivo della firma, contatto e posizione devono essere forniti tramite le proprietà corrispondenti dell'oggetto Signature sig. |
| override [Close](../../aspose.pdf.facades/pdffilesignature/close/)() | Chiude la facciata. |
| [ContainsSignature](../../aspose.pdf.facades/pdffilesignature/containssignature/)() | Verifica se il PDF ha una firma digitale o meno. |
| [ContainsUsageRights](../../aspose.pdf.facades/pdffilesignature/containsusagerights/)() | Verifica se il PDF ha diritti di utilizzo o meno. |
| [CoversWholeDocument](../../aspose.pdf.facades/pdffilesignature/coverswholedocument/#coverswholedocument)(SignatureName) | Verifica se la firma copre l'intero documento. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Rilascia la facciata. |
| [ExtractCertificate](../../aspose.pdf.facades/pdffilesignature/extractcertificate/#extractcertificate)(SignatureName) | Estrae il singolo certificato X.509 della firma come stream. |
| [ExtractImage](../../aspose.pdf.facades/pdffilesignature/extractimage/#extractimage)(SignatureName) | Estrae l'immagine della firma. |
| [GetAccessPermissions](../../aspose.pdf.facades/pdffilesignature/getaccesspermissions/)() | Restituisce il valore dei permessi di accesso del documento certificato tramite il tipo di firma MDP. |
| [GetBlankSignatureNames](../../aspose.pdf.facades/pdffilesignature/getblanksignaturenames/)() | Restituisce i nomi di tutti i campi firma vuoti. |
| [GetContactInfo](../../aspose.pdf.facades/pdffilesignature/getcontactinfo/#getcontactinfo)(SignatureName) | Restituisce le informazioni di contatto di una firma. |
| [GetDateTime](../../aspose.pdf.facades/pdffilesignature/getdatetime/#getdatetime)(SignatureName) | Restituisce la data e l'ora della firma. |
| [GetLocation](../../aspose.pdf.facades/pdffilesignature/getlocation/#getlocation)(SignatureName) | Restituisce la posizione di una firma. |
| [GetReason](../../aspose.pdf.facades/pdffilesignature/getreason/#getreason)(SignatureName) | Restituisce il motivo di una firma. |
| [GetRevision](../../aspose.pdf.facades/pdffilesignature/getrevision/#getrevision)(SignatureName) | Restituisce la revisione di una firma. |
| [GetSignatureNames](../../aspose.pdf.facades/pdffilesignature/getsignaturenames/)(bool) | Restituisce i nomi di tutte le firme non vuote. |
| [GetSignaturesInfo](../../aspose.pdf.facades/pdffilesignature/getsignaturesinfo/)() | Recupera informazioni su tutti gli algoritmi delle firme presenti nel documento PDF. |
| [GetSignerName](../../aspose.pdf.facades/pdffilesignature/getsignername/#getsignername)(SignatureName) | Restituisce il nome della persona o dell'organizzazione che firma il documento PDF. |
| [GetTotalRevision](../../aspose.pdf.facades/pdffilesignature/gettotalrevision/)() | Restituisce la revisione totale. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature)(SignatureName) | Rimuove la firma in base al nome della firma. |
| [RemoveSignature](../../aspose.pdf.facades/pdffilesignature/removesignature/#removesignature_1)(SignatureName, bool) | Rimuove la firma in base al nome della firma. |
| [RemoveSignatures](../../aspose.pdf.facades/pdffilesignature/removesignatures/)() | Rimuove tutte le firme. |
| [RemoveUsageRights](../../aspose.pdf.facades/pdffilesignature/removeusagerights/)() | Rimuove la voce dei diritti di utilizzo. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_1)(Stream) | Salva il PDF risultante nello stream. |
| override [Save](../../aspose.pdf.facades/pdffilesignature/save/#save_2)(string) | Salva il PDF risultante nel file. |
| [SetCertificate](../../aspose.pdf.facades/pdffilesignature/setcertificate/)(string, string) | Imposta il file del certificato e la password per la routine di firma. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_4)(string, Signature) | Firma il documento con la firma di tipo specificato che è posizionata in un campo firma già presente. Prima della firma il campo firma deve essere vuoto, cioè non deve contenere un dizionario firma. Pertanto il documento PDF ha già un campo firma; non è necessario fornire il luogo per apporre la firma, la pagina corrispondente e il rettangolo vengono presi dal campo firma trovato tramite il nome della firma (vedi parametro SigName). Dati come il motivo della firma, il contatto e la posizione devono essere forniti dalle proprietà corrispondenti dell'oggetto Signature sig. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign)(int, bool, Rectangle, Signature) | Firma il documento con la firma di tipo specificato. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_5)(string, string, string, string, Signature) | Firma il documento con la firma di tipo specificato che è posizionata in un campo firma già presente. Prima della firma il campo firma deve essere vuoto, cioè non deve contenere un dizionario firma. Pertanto il documento PDF ha già un campo firma; non è necessario fornire il luogo per apporre la firma, la pagina corrispondente e il rettangolo vengono presi dal campo firma trovato tramite il nome della firma (vedi parametro SigName). |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_1)(int, string, string, string, bool, Rectangle) | Crea una firma sul documento PDF. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_2)(int, string, string, string, bool, Rectangle, Signature) | Firma il documento con la firma di tipo specificato. |
| [Sign](../../aspose.pdf.facades/pdffilesignature/sign/#sign_3)(int, string, string, string, string, bool, Rectangle, Signature) | Firma il documento con la firma di tipo specificato che è posizionata in un campo firma già presente. Prima della firma il documento PDF dovrebbe già avere un campo firma; la pagina corrispondente e il rettangolo vengono presi dal campo firma trovato tramite il nome della firma (vedi parametro SigName). |
| [TryExtractCertificate](../../aspose.pdf.facades/pdffilesignature/tryextractcertificate/#tryextractcertificate)(SignatureName, out Stream) | Estrae il singolo certificato X.509 della firma come stream. |
| [TryExtractCertificate](../../aspose.pdf.facades/pdffilesignature/tryextractcertificate/#tryextractcertificate_1)(SignatureName, out X509Certificate2) | Estrae il singolo certificato X.509 della firma. |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature)(SignatureName) | Verifica la validità di una firma. |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature_2)(SignatureName, X509Certificate2) | Verifica la validità di una firma. La verifica è eseguita utilizzando il certificato della chiave pubblica esterna. |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature_1)(SignatureName, ValidationOptions, out ValidationResult) | Verifica la validità di una firma. |
| [VerifySignature](../../aspose.pdf.facades/pdffilesignature/verifysignature/#verifysignature_3)(SignatureName, X509Certificate2, ValidationOptions, out ValidationResult) | Verifica la validità di una firma. La verifica è eseguita utilizzando il certificato della chiave pubblica esterna. |

### Vedi anche

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


