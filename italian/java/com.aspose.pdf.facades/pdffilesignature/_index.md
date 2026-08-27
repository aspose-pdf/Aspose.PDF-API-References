---
title: "PdfFileSignature"
linktitle: "PdfFileSignature"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una classe per firmare un file pdf con un certificato."
type: docs
weight: 530
url: /it/java/com.aspose.pdf.facades/pdffilesignature/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSignature, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSignature, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileSignature

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileSignature extends SaveableFacade
```

Rappresenta una classe per firmare un file pdf con un certificato.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PdfFileSignature](#PdfFileSignature--) | Il costruttore della classe PdfFileSignature. |
| [PdfFileSignature](#PdfFileSignature-com.aspose.pdf.IDocument-) | Il costruttore della classe PdfFileSignature. |
| [PdfFileSignature](#PdfFileSignature-com.aspose.pdf.IDocument-java.lang.String-) | Il costruttore della classe PdfFileSignature. |
| [PdfFileSignature](#PdfFileSignature-java.lang.String-) | Il costruttore della classe PdfFileSignature. |
| [PdfFileSignature](#PdfFileSignature-java.lang.String-java.lang.String-) | Il costruttore della classe PdfFileSignature. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-) | Associa un flusso Pdf per la modifica. |
| [bindPdf](#bindPdf-java.lang.String-) | Associa un file Pdf per la modifica. |
| [certify](#certify-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.DocMDPSignature-) | Certifica il documento con la firma MDP. |
| [certify](#certify-java.lang.String-com.aspose.pdf.DocMDPSignature-) | Certifica il documento con la firma MDP che è posizionata in un campo firma già presente. Prima della firma il campo firma deve essere vuoto, cioè il campo non deve contenere un dizionario di firma. Pertanto il documento pdf ha già un campo firma; non è necessario fornire il luogo per apporre la firma, la pagina corrispondente e il rettangolo vengono presi dal campo firma trovato tramite il nome della firma (vedi parametro sigName). |
| [close](#close--) | Chiude la facciata. |
| [containsSignature](#containsSignature--) | Verifica se il pdf ha una firma digitale o meno. |
| [containsUsageRights](#containsUsageRights--) | Verifica se il pdf ha diritti di utilizzo o meno. |
| [coversWholeDocument](#coversWholeDocument-com.aspose.pdf.facades.SignatureName-) | Verifica se la firma copre l'intero documento. |
| [coversWholeDocument](#coversWholeDocument-java.lang.String-) | Verifica se la firma copre l'intero documento. |
| [dispose](#dispose--) | Chiude il facade. Questo metodo è obsoleto, usa close() al suo posto. |
| [extractCertificate](#extractCertificate-com.aspose.pdf.facades.SignatureName-) | Estrae il singolo certificato X.509 della firma come flusso. |
| [extractCertificate](#extractCertificate-java.lang.String-) | Estrae il singolo certificato X.509 della firma come flusso. |
| [extractImage](#extractImage-com.aspose.pdf.facades.SignatureName-) | Estrae l'immagine della firma. |
| [extractImage](#extractImage-java.lang.String-) | Estrae l'immagine della firma. |
| [getAccessPermissions](#getAccessPermissions--) | Restituisce il valore dei permessi di accesso del documento certificato per il tipo di firma MDP. |
| [getBlankSignNames](#getBlankSignNames--) | Ottiene i nomi di tutti i campi firma vuoti. |
| [getContactInfo](#getContactInfo-com.aspose.pdf.facades.SignatureName-) | Ottiene le informazioni di contatto di una firma. |
| [getContactInfo](#getContactInfo-java.lang.String-) | Ottiene le informazioni di contatto di una firma. |
| [getDateTime](#getDateTime-com.aspose.pdf.facades.SignatureName-) | Ottiene la data e ora della firma. |
| [getDateTime](#getDateTime-java.lang.String-) | Ottiene la data e ora della firma. |
| [getLocation](#getLocation-com.aspose.pdf.facades.SignatureName-) | Ottiene la posizione di una firma. |
| [getLocation](#getLocation-java.lang.String-) | Ottiene la posizione di una firma. |
| [getReason](#getReason-com.aspose.pdf.facades.SignatureName-) | Ottiene il motivo di una firma. |
| [getReason](#getReason-java.lang.String-) | Ottiene il motivo di una firma. |
| [getRevision](#getRevision-com.aspose.pdf.facades.SignatureName-) | Ottiene la revisione di una firma. |
| [getRevision](#getRevision-java.lang.String-) | Ottiene la revisione di una firma. |
| [getSignatureAppearance](#getSignatureAppearance--) | Ottiene un aspetto grafico per la firma. Il valore della proprietà rappresenta il nome del file immagine. |
| [getSignatureAppearanceStream](#getSignatureAppearanceStream--) | Ottiene un aspetto grafico per la firma. Il valore della proprietà rappresenta lo stream dell'immagine. |
| [getSignatureNames](#getSignatureNames--) | / * <p> / * Ottiene i nomi di tutte le firme non vuote. / * </p> / * <p> / * <pre> / * string inFile=TestPath + "example1.pdf"; / * PdfFileSignature pdfSign=new PdfFileSignature(); / * pdfSign.bindPdf(inFile); / * java.util.List<String> names=pdfSign.getSignatureNames(); / * for(int i=0;i<names.size();i++) / * { / * System.out.println("signature name:" + names[i]); / * System.out.println("coverswholeddocument:" + pdfSign.coversWholeDocument(names[i])); / * System.out.println("revision:" + pdfSign.getRevision(names[i])); / * System.out.println("verifysigned:" + pdfSign.verifySignature(names[i])); / * System.out.println("reason:" + pdfSign.getReason(names[i])); / * System.out.println("location:" + pdfSign.getLocation(names[i])); / * System.out.println("datatime:" + pdfSign.getDateTime(names[i])); / * } / * System.out.println("totalvision:" + pdfSign.GetTotalRevision()); / * / * </pre> / * |
| [getSignatureNames](#getSignatureNames-boolean-) | Ottiene i nomi di tutte le firme non vuote. string inFile=TestPath + "example1.pdf"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); java.util.List names=pdfSign.getSignatureNames(); for(int i=0;i<names.size();i++) { System.out.println("signature name:" + names[i]); System.out.println("coverswholeddocument:" + pdfSign.coversWholeDocument(names[i])); System.out.println("revision:" + pdfSign.getRevision(names[i])); System.out.println("verifysigned:" + pdfSign.verifySignature(names[i])); System.out.println("reason:" + pdfSign.getReason(names[i])); System.out.println("location:" + pdfSign.getLocation(names[i])); System.out.println("datatime:" + pdfSign.getDateTime(names[i])); } System.out.println("totalvision:" + pdfSign.GetTotalRevision()); |
| [getSignaturesInfo](#getSignaturesInfo--) | Recupera le informazioni su tutti gli algoritmi delle firme presenti nel documento PDF. |
| [getSignerName](#getSignerName-com.aspose.pdf.facades.SignatureName-) | Ottiene il nome della persona o dell'organizzazione che firma il documento PDF. |
| [getSignerName](#getSignerName-java.lang.String-) | Ottiene il nome della persona o dell'organizzazione che firma il documento PDF. |
| [getSignNames](#getSignNames--) | <p> Ottiene i nomi di tutte le firme non vuote. </p> <hr> |
| [getSignNames](#getSignNames-boolean-) | <p> Ottiene i nomi di tutte le firme non vuote. </p> <hr> <pre> String inFile=TestPath + "example1.pdf"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); ArrayList names=pdfSign.getSignNames(true); for(int i=0;i<names.Count;i++) { System.out.println("signature name:"+(String)names[i]); System.out.println("coverswholeddocument:"+pdfSign.IsCoversWholeDocument((String)names[i])); System.out.println("revision:"+pdfSign.GetRevision((String)names[i])); System.out.println("verifysigned:"+pdfSign.VerifySigned((String)names[i])); System.out.println("reason:"+pdfSign.GetReason((String)names[i])); System.out.println("location:"+pdfSign.GetLocation((String)names[i])); System.out.println("datatime:"+pdfSign.GetDateTime((String)names[i])); } System.out.println("totalvision:"+pdfSign.GetTotalRevision()); </pre> |
| [getTotalRevision](#getTotalRevision--) | Ottiene la revisione totale. |
| [isCertified](#isCertified--) | Ottiene il flag che determina se un documento è certificato o meno. |
| [isContainSignature](#isContainSignature--) | Verifica se il pdf ha una firma digitale o meno. |
| [isCoversWholeDocument](#isCoversWholeDocument-java.lang.String-) | Verifica se la firma copre l'intero documento. |
| [isLtvEnabled](#isLtvEnabled--) | Ottiene il flag LTV abilitato. |
| [removeSignature](#removeSignature-com.aspose.pdf.facades.SignatureName-) | Rimuove la firma in base al nome della firma. string inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i]); } pdfSign.save(TestPath + "signed_removed.pdf"); |
| [removeSignature](#removeSignature-com.aspose.pdf.facades.SignatureName-boolean-) | Rimuove la firma in base al nome della firma. string inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i], false); } pdfSign.save(TestPath + "signed_removed.pdf"); |
| [removeSignature](#removeSignature-java.lang.String-) | <p> Rimuovi la firma in base al nome della firma. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i)); } pdfSign.save(TestPath + "signed_removed.pdf"); </pre> |
| [removeSignature](#removeSignature-java.lang.String-boolean-) | <p> Rimuove la firma in base al nome della firma. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.BindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i), false); } pdfSign.save(TestPath + "signed_removed.pdf"); </pre> |
| [removeSignatures](#removeSignatures--) | Rimuove tutte le firme. string inFile = TestPath + "example1.pdf"; var pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); pdfSign.removeSignatures(); pdfSign.save(TestPath + "signed_removed.pdf"); |
| [removeUsageRights](#removeUsageRights--) | Rimuove la voce dei diritti di utilizzo. |
| [save](#save--) | Salva il file PDF firmato. Il nome del file di output deve essere fornito in precedenza con l'aiuto del costruttore corrispondente di PdfFileSignature. |
| [save](#save-java.io.OutputStream-) | Salva il file PDF firmato. Il nome del file di output deve essere fornito in precedenza con l'aiuto del costruttore corrispondente di PdfFileSignature. |
| [save](#save-java.lang.String-) | Salva il file PDF firmato. Il nome del file di output deve essere fornito in precedenza con l'aiuto del costruttore corrispondente di PdfFileSignature. |
| [setCertificate](#setCertificate-java.lang.String-java.lang.String-) | Imposta il file del certificato e la password per la routine di firma. |
| [setSignatureAppearance](#setSignatureAppearance-java.lang.String-) | Imposta un aspetto grafico per la firma. Il valore della proprietà rappresenta il nome del file immagine. |
| [setSignatureAppearanceStream](#setSignatureAppearanceStream-java.io.InputStream-) | Imposta un aspetto grafico per la firma. Il valore della proprietà rappresenta lo stream dell'immagine. |
| [sign](#sign-int-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-) | Firma il documento con la firma di tipo specificato. |
| [sign](#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-) | Crea una firma sul documento PDF. |
| [sign](#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-) | Firma il documento con la firma di tipo specificato. |
| [sign](#sign-int-java.lang.String-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-) | Firma il documento con la firma di tipo specificato che è posizionata in un campo firma già presente. |
| [sign](#sign-java.lang.String-com.aspose.pdf.Signature-) | <p> Firma il documento con la firma di tipo specificato che è posizionata in un campo firma già presente. Prima della firma il campo firma deve essere vuoto, cioè il campo non deve contenere un dizionario della firma. Pertanto il documento PDF ha già un campo firma; non è necessario fornire il luogo dove apporre la firma, la pagina e il rettangolo corrispondenti sono presi dal campo firma trovato tramite il nome della firma (vedi parametro SigName). Dati come il motivo della firma, il contatto e la posizione devono essere forniti dalle proprietà corrispondenti dell'oggetto Signature sig. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; String outFile = TestPath + "signature.pdf"; PKCS1 sig = new PKCS1("certificate.pfx", "password"); sig.setReason ( "Some reason"); sig.setContact ( "Smith"); sig.setLocation ( "New York"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg"); pdfSign.sign("Signature1", sig); pdfSign.save(); </pre> |
| [sign](#sign-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.Signature-) | <p> Firma il documento con la firma di tipo specificato che è posizionata in un campo firma già presente. Prima della firma il campo firma deve essere vuoto, cioè il campo non deve contenere un dizionario della firma. Pertanto il documento PDF ha già un campo firma; non è necessario fornire il luogo dove apporre la firma, la pagina e il rettangolo corrispondenti sono presi dal campo firma trovato tramite il nome della firma (vedi parametro SigName). </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; String outFile = TestPath + "signature.pdf"; PKCS1 sig = new PKCS1("certificate.pfx", "password"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg"); pdfSign.sign("Signature1", "Allen", "success", "ChangSha", sig); pdfSign.save(); </pre> |
| [tryExtractCertificate](#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-java.io.OutputStream:A-) | Estrae il singolo certificato X.509 della firma come flusso. |
| [tryExtractCertificate](#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2:A-) | Estrae il singolo certificato X.509 della firma. |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-) | Verifica la validità di una firma. |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Verifica la validità di una firma. |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-) | Verifica la validità di una firma. |
| [verifySignature](#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Verifica la validità di una firma. |
| [verifySignature](#verifySignature-java.lang.String-) | Verifica la validità di una firma. |
| [verifySignature](#verifySignature-java.lang.String-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-) | Verifica la validità di una firma. |
| [verifySigned](#verifySigned-java.lang.String-) | Verifica la validità di una firma. Il metodo è deprecato e sarà rimosso nella versione 25.1. Usa il metodo VerifySignature al suo posto. |

### PdfFileSignature {#PdfFileSignature--}
```
public PdfFileSignature()
```

Il costruttore della classe PdfFileSignature.

### PdfFileSignature {#PdfFileSignature-com.aspose.pdf.IDocument-}
Il costruttore della classe PdfFileSignature.

### PdfFileSignature {#PdfFileSignature-com.aspose.pdf.IDocument-java.lang.String-}
Il costruttore della classe PdfFileSignature.

### PdfFileSignature {#PdfFileSignature-java.lang.String-}
Il costruttore della classe PdfFileSignature.

### PdfFileSignature {#PdfFileSignature-java.lang.String-java.lang.String-}
Il costruttore della classe PdfFileSignature.

### bindPdf {#bindPdf-java.io.InputStream-}
Associa un flusso Pdf per la modifica.

### bindPdf {#bindPdf-java.lang.String-}
Associa un file Pdf per la modifica.

### certify {#certify-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.DocMDPSignature-}
Certifica il documento con la firma MDP.

### certify {#certify-java.lang.String-com.aspose.pdf.DocMDPSignature-}
Certifica il documento con la firma MDP che è posizionata in un campo firma già presente. Prima della firma il campo firma deve essere vuoto, cioè il campo non deve contenere un dizionario di firma. Pertanto il documento pdf ha già un campo firma; non è necessario fornire il luogo per apporre la firma, la pagina corrispondente e il rettangolo vengono presi dal campo firma trovato tramite il nome della firma (vedi parametro sigName).

### close {#close--}
```
public void close()
```

Chiude la facciata.

### containsSignature {#containsSignature--}
```
public boolean containsSignature()
```

Verifica se il pdf ha una firma digitale o meno.

**Returns:**
Restituisce un risultato di tipo bool.

### containsUsageRights {#containsUsageRights--}
```
public boolean containsUsageRights()
```

Verifica se il pdf ha diritti di utilizzo o meno.

**Returns:**
Restituisce un risultato di tipo bool.

### coversWholeDocument {#coversWholeDocument-com.aspose.pdf.facades.SignatureName-}
Verifica se la firma copre l'intero documento.

### coversWholeDocument {#coversWholeDocument-java.lang.String-}
Verifica se la firma copre l'intero documento.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Chiude il facade. Questo metodo è obsoleto, usa close() al suo posto.

### extractCertificate {#extractCertificate-com.aspose.pdf.facades.SignatureName-}
Estrae il singolo certificato X.509 della firma come flusso.

### extractCertificate {#extractCertificate-java.lang.String-}
Estrae il singolo certificato X.509 della firma come flusso.

### extractImage {#extractImage-com.aspose.pdf.facades.SignatureName-}
Estrae l'immagine della firma.

### extractImage {#extractImage-java.lang.String-}
Estrae l'immagine della firma.

### getAccessPermissions {#getAccessPermissions--}
```
public DocMDPAccessPermissions getAccessPermissions()
```

Restituisce il valore dei permessi di accesso del documento certificato per il tipo di firma MDP.

**Returns:**
PdfException Se il documento è in fase di certificazione, restituisce il valore delle autorizzazioni di accesso; altrimenti, viene lanciata. @see com.aspose.pdf.DocMDPAccessPermissions

### getBlankSignNames {#getBlankSignNames--}
```
@Deprecated public List < String > getBlankSignNames()
```

Ottiene i nomi di tutti i campi firma vuoti.

**Returns:**
Restituisce una arrayList. @deprecated Usa GetBlankSignatureNames() invece.

### getContactInfo {#getContactInfo-com.aspose.pdf.facades.SignatureName-}
Ottiene le informazioni di contatto di una firma.

### getContactInfo {#getContactInfo-java.lang.String-}
Ottiene le informazioni di contatto di una firma.

### getDateTime {#getDateTime-com.aspose.pdf.facades.SignatureName-}
Ottiene la data e ora della firma.

### getDateTime {#getDateTime-java.lang.String-}
Ottiene la data e ora della firma.

### getLocation {#getLocation-com.aspose.pdf.facades.SignatureName-}
Ottiene la posizione di una firma.

### getLocation {#getLocation-java.lang.String-}
Ottiene la posizione di una firma.

### getReason {#getReason-com.aspose.pdf.facades.SignatureName-}
Ottiene il motivo di una firma.

### getReason {#getReason-java.lang.String-}
Ottiene il motivo di una firma.

### getRevision {#getRevision-com.aspose.pdf.facades.SignatureName-}
Ottiene la revisione di una firma.

### getRevision {#getRevision-java.lang.String-}
Ottiene la revisione di una firma.

### getSignatureAppearance {#getSignatureAppearance--}
```
public String getSignatureAppearance()
```

Ottiene un aspetto grafico per la firma. Il valore della proprietà rappresenta il nome del file immagine.

**Returns:**
valore String

### getSignatureAppearanceStream {#getSignatureAppearanceStream--}
```
public InputStream getSignatureAppearanceStream()
```

Ottiene un aspetto grafico per la firma. Il valore della proprietà rappresenta lo stream dell'immagine.

**Returns:**
Elemento InputStream

### getSignatureNames {#getSignatureNames--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericList< SignatureName > getSignatureNames()
```

/ * <p> / * Ottiene i nomi di tutte le firme non vuote. / * </p> / * <p> / * <pre> / * string inFile=TestPath + "example1.pdf"; / * PdfFileSignature pdfSign=new PdfFileSignature(); / * pdfSign.bindPdf(inFile); / * java.util.List<String> names=pdfSign.getSignatureNames(); / * for(int i=0;i<names.size();i++) / * { / * System.out.println("signature name:" + names[i]); / * System.out.println("coverswholeddocument:" + pdfSign.coversWholeDocument(names[i])); / * System.out.println("revision:" + pdfSign.getRevision(names[i])); / * System.out.println("verifysigned:" + pdfSign.verifySignature(names[i])); / * System.out.println("reason:" + pdfSign.getReason(names[i])); / * System.out.println("location:" + pdfSign.getLocation(names[i])); / * System.out.println("datatime:" + pdfSign.getDateTime(names[i])); / * } / * System.out.println("totalvision:" + pdfSign.GetTotalRevision()); / * / * </pre> / *

**Returns:**
Restituisce un IList<SignatureName>. /

### getSignatureNames {#getSignatureNames-boolean-}
```
public final com.aspose.ms.System.Collections.Generic.IGenericList< SignatureName > getSignatureNames(boolean onlyActive)
```

Ottiene i nomi di tutte le firme non vuote. string inFile=TestPath + "example1.pdf"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); java.util.List names=pdfSign.getSignatureNames(); for(int i=0;i<names.size();i++) { System.out.println("signature name:" + names[i]); System.out.println("coverswholeddocument:" + pdfSign.coversWholeDocument(names[i])); System.out.println("revision:" + pdfSign.getRevision(names[i])); System.out.println("verifysigned:" + pdfSign.verifySignature(names[i])); System.out.println("reason:" + pdfSign.getReason(names[i])); System.out.println("location:" + pdfSign.getLocation(names[i])); System.out.println("datatime:" + pdfSign.getDateTime(names[i])); } System.out.println("totalvision:" + pdfSign.GetTotalRevision());

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| onlyActive |  | se true, restituisce solo le firme attive; altrimenti, restituisce tutte le firme. |

**Returns:**
Restituisce un IList<SignatureName>.

### getSignaturesInfo {#getSignaturesInfo--}
```
public final List <com.aspose.pdf.engine.security.SignatureAlgorithmInfo> getSignaturesInfo()
```

Recupera le informazioni su tutti gli algoritmi delle firme presenti nel documento PDF.

**Returns:**
Un elenco di istanze {@link SignatureAlgorithmInfo} contenente informazioni su ogni firma.

### getSignerName {#getSignerName-com.aspose.pdf.facades.SignatureName-}
Ottiene il nome della persona o dell'organizzazione che firma il documento PDF.

### getSignerName {#getSignerName-java.lang.String-}
Ottiene il nome della persona o dell'organizzazione che firma il documento PDF.

### getSignNames {#getSignNames--}
```
public final List < String > getSignNames()
```

<p> Ottiene i nomi di tutte le firme non vuote. </p> <hr>

**Returns:**
Restituisce una arrayList.

### getSignNames {#getSignNames-boolean-}
```
@Deprecated public List < String > getSignNames(boolean onlyActive)
```

<p> Ottiene i nomi di tutte le firme non vuote. </p> <hr> <pre> String inFile=TestPath + "example1.pdf"; PdfFileSignature pdfSign=new PdfFileSignature(); pdfSign.bindPdf(inFile); ArrayList names=pdfSign.getSignNames(true); for(int i=0;i<names.Count;i++) { System.out.println("signature name:"+(String)names[i]); System.out.println("coverswholeddocument:"+pdfSign.IsCoversWholeDocument((String)names[i])); System.out.println("revision:"+pdfSign.GetRevision((String)names[i])); System.out.println("verifysigned:"+pdfSign.VerifySigned((String)names[i])); System.out.println("reason:"+pdfSign.GetReason((String)names[i])); System.out.println("location:"+pdfSign.GetLocation((String)names[i])); System.out.println("datatime:"+pdfSign.GetDateTime((String)names[i])); } System.out.println("totalvision:"+pdfSign.GetTotalRevision()); </pre>

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| onlyActive |  | Valore booleano, se true, restituisce solo le firme attive; altrimenti, restituisce tutte le firme. |

**Returns:**
Restituisce una arrayList. @deprecated Il metodo può produrre gli stessi nomi di firma, che non possono essere distinti durante la verifica. Usa getSignatureNames(boolean onlyActive) invece.

### getTotalRevision {#getTotalRevision--}
```
public int getTotalRevision()
```

Ottiene la revisione totale.

**Returns:**
Restituisce il numero totale di revisioni della firma.

### isCertified {#isCertified--}
```
public boolean isCertified()
```

Ottiene il flag che determina se un documento è certificato o meno.

**Returns:**
valore booleano

### isContainSignature {#isContainSignature--}
```
@Deprecated public boolean isContainSignature()
```

Verifica se il pdf ha una firma digitale o meno.

**Returns:**
Restituisce un risultato di tipo bool.

### isCoversWholeDocument {#isCoversWholeDocument-java.lang.String-}
Verifica se la firma copre l'intero documento.

### isLtvEnabled {#isLtvEnabled--}
```
public final boolean isLtvEnabled()
```

Ottiene il flag LTV abilitato.

**Returns:**
valore booleano

### removeSignature {#removeSignature-com.aspose.pdf.facades.SignatureName-}
Rimuove la firma in base al nome della firma. string inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i]); } pdfSign.save(TestPath + "signed_removed.pdf");

### removeSignature {#removeSignature-com.aspose.pdf.facades.SignatureName-boolean-}
Rimuove la firma in base al nome della firma. string inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); IList<SignatureName> names = pdfSign.getSignatureNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature(names[i], false); } pdfSign.save(TestPath + "signed_removed.pdf");

### removeSignature {#removeSignature-java.lang.String-}
<p> Rimuovi la firma in base al nome della firma. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i)); } pdfSign.save(TestPath + "signed_removed.pdf"); </pre>

### removeSignature {#removeSignature-java.lang.String-boolean-}
<p> Rimuove la firma in base al nome della firma. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; PdfFileSignature pdfSign = new PdfFileSignature(); pdfSign.BindPdf(inFile); List names = pdfSign.getSignNames(); for(int i = 0; i < names.size(); i++) { pdfSign.removeSignature((String)names.get(i), false); } pdfSign.save(TestPath + "signed_removed.pdf"); </pre>

### removeSignatures {#removeSignatures--}
```
public final void removeSignatures()
```

Rimuove tutte le firme. string inFile = TestPath + "example1.pdf"; var pdfSign = new PdfFileSignature(); pdfSign.bindPdf(inFile); pdfSign.removeSignatures(); pdfSign.save(TestPath + "signed_removed.pdf");

### removeUsageRights {#removeUsageRights--}
```
public void removeUsageRights()
```

Rimuove la voce dei diritti di utilizzo.

### save {#save--}
```
@Deprecated public void save()
```

Salva il file PDF firmato. Il nome del file di output deve essere fornito in precedenza con l'aiuto del costruttore corrispondente di PdfFileSignature.

### save {#save-java.io.OutputStream-}
Salva il file PDF firmato. Il nome del file di output deve essere fornito in precedenza con l'aiuto del costruttore corrispondente di PdfFileSignature.

### save {#save-java.lang.String-}
Salva il file PDF firmato. Il nome del file di output deve essere fornito in precedenza con l'aiuto del costruttore corrispondente di PdfFileSignature.

### setCertificate {#setCertificate-java.lang.String-java.lang.String-}
Imposta il file del certificato e la password per la routine di firma.

### setSignatureAppearance {#setSignatureAppearance-java.lang.String-}
Imposta un aspetto grafico per la firma. Il valore della proprietà rappresenta il nome del file immagine.

### setSignatureAppearanceStream {#setSignatureAppearanceStream-java.io.InputStream-}
Imposta un aspetto grafico per la firma. Il valore della proprietà rappresenta lo stream dell'immagine.

### sign {#sign-int-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-}
Firma il documento con la firma di tipo specificato.

### sign {#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-}
Crea una firma sul documento PDF.

### sign {#sign-int-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-}
Firma il documento con la firma di tipo specificato.

### sign {#sign-int-java.lang.String-java.lang.String-java.lang.String-java.lang.String-boolean-java.awt.Rectangle-com.aspose.pdf.Signature-}
Firma il documento con la firma di tipo specificato che è posizionata in un campo firma già presente.

### sign {#sign-java.lang.String-com.aspose.pdf.Signature-}
<p> Firma il documento con la firma di tipo specificato che è posizionata in un campo firma già presente. Prima della firma il campo firma deve essere vuoto, cioè il campo non deve contenere un dizionario della firma. Pertanto il documento PDF ha già un campo firma; non è necessario fornire il luogo dove apporre la firma, la pagina e il rettangolo corrispondenti sono presi dal campo firma trovato tramite il nome della firma (vedi parametro SigName). Dati come il motivo della firma, il contatto e la posizione devono essere forniti dalle proprietà corrispondenti dell'oggetto Signature sig. </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; String outFile = TestPath + "signature.pdf"; PKCS1 sig = new PKCS1("certificate.pfx", "password"); sig.setReason ( "Some reason"); sig.setContact ( "Smith"); sig.setLocation ( "New York"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg"); pdfSign.sign("Signature1", sig); pdfSign.save(); </pre>

### sign {#sign-java.lang.String-java.lang.String-java.lang.String-java.lang.String-com.aspose.pdf.Signature-}
<p> Firma il documento con la firma di tipo specificato che è posizionata in un campo firma già presente. Prima della firma il campo firma deve essere vuoto, cioè il campo non deve contenere un dizionario della firma. Pertanto il documento PDF ha già un campo firma; non è necessario fornire il luogo dove apporre la firma, la pagina e il rettangolo corrispondenti sono presi dal campo firma trovato tramite il nome della firma (vedi parametro SigName). </p> <hr> <pre> String inFile = TestPath + "example1.pdf"; String outFile = TestPath + "signature.pdf"; PKCS1 sig = new PKCS1("certificate.pfx", "password"); PdfFileSignature pdfSign = new PdfFileSignature(inFile, outFile); pdfSign.setSignatureAppearance ( TestPath + "butterfly.jpg"); pdfSign.sign("Signature1", "Allen", "success", "ChangSha", sig); pdfSign.save(); </pre>

### tryExtractCertificate {#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-java.io.OutputStream:A-}
Estrae il singolo certificato X.509 della firma come flusso.

### tryExtractCertificate {#tryExtractCertificate-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2:A-}
Estrae il singolo certificato X.509 della firma.

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-}
Verifica la validità di una firma.

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Verifica la validità di una firma.

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-}
Verifica la validità di una firma.

### verifySignature {#verifySignature-com.aspose.pdf.facades.SignatureName-com.aspose.ms.System.Security.Cryptography.X509Certificates.X509Certificate2-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Verifica la validità di una firma.

### verifySignature {#verifySignature-java.lang.String-}
Verifica la validità di una firma.

### verifySignature {#verifySignature-java.lang.String-com.aspose.pdf.security.certificatevalidation.ValidationOptions-com.aspose.pdf.security.certificatevalidation.ValidationResult:A-}
Verifica la validità di una firma.

### verifySigned {#verifySigned-java.lang.String-}
Verifica la validità di una firma. Il metodo è deprecato e sarà rimosso nella versione 25.1. Usa il metodo VerifySignature al suo posto.
