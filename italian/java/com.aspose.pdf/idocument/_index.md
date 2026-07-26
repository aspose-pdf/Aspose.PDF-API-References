---
title: "IDocument"
linktitle: "IDocument"
second_title: "Riferimento API Aspose.PDF per Java"
description: "interfaccia che rappresenta un documento PDF"
type: docs
weight: 2230
url: /it/java/com.aspose.pdf/idocument/
---
```
public interface IDocument extends com.aspose.ms.System.IDisposable, Closeable
```

interfaccia che rappresenta un documento PDF

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [afterImport](#afterImport--) | Enumera tutte le annotazioni registrate e chiama AfterImport per ciascuna di esse. |
| [bindXml](#bindXml-java.io.InputStream-) | Associa xml al documento |
| [bindXml](#bindXml-java.lang.String-) | Associa xml al documento |
| [bindXml](#bindXml-java.lang.String-java.lang.String-) | Associa xml/xsl al documento |
| [changePasswords](#changePasswords-java.lang.String-java.lang.String-java.lang.String-) | Modifica le password del documento. |
| [check](#check-boolean-) | Convalida il documento. |
| [close](#close--) | Chiude tutte le risorse utilizzate da questo documento. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-) | Converti il documento in un documento ricercabile. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-) | Converti il documento in un documento ricercabile e ignora gli errori di hochr che non possono essere convertiti. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-) | Converti il documento e salva gli errori nel file specificato. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-) | Converti il documento e salva gli errori nel file specificato. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-) | Converti il documento e salva gli errori nel file specificato. <p> Questo consente di mostrare/nascondere il testo ricercabile nella pagina. Il valore predefinito è FALSE. Questo consente di ottenere l'immagine originale dal pdf. Il valore predefinito è FALSE. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-) | Converti il documento e salva gli errori nel file specificato. <p> Questo consente di mostrare/nascondere il testo ricercabile nella pagina. Il valore predefinito è FALSE. Questo consente di ottenere l'immagine originale dal pdf. Il valore predefinito è FALSE. |
| [convert](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) |  |
| [convert](#convert-com.aspose.pdf.PdfFormatConversionOptions-) | Converti il documento usando le opzioni di conversione specificate |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Converti il documento e salva gli errori nel file specificato. |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | Converti il documento e salva gli errori nel file specificato. |
| [convertInternal](#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Metodo interno |
| [convertWithFlatten](#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-) | Converti il documento in un documento ricercabile e ignora gli errori di hochr che non possono essere convertiti. |
| [convertWithSkippingErrors](#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-) | Converti il documento in un documento ricercabile e ignora gli errori di hochr che non possono essere convertiti. |
| [decrypt](#decrypt--) | Decripta il documento. |
| [dispose](#dispose--) | Obsoleto. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-) | Cripta il documento. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-) | Cripta il documento. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-) | Cripta il documento. |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.lang.String-) | Esporta tutte le annotazioni del documento in un file XFDF |
| [flatten](#flatten--) | Rimuove tutti i campi (e le annotazioni) dal documento e ne inserisce i valori al loro posto. |
| [flatten](#flatten-com.aspose.pdf.Form.FlattenSettings-) | Rimuove tutti i campi dal documento e ne inserisce i valori al loro posto. |
| [flattenTransparency](#flattenTransparency--) | Sostituisce il contenuto trasparente con grafica raster e vettoriale non trasparente. |
| [freeMemory](#freeMemory--) | Cancella la memoria |
| [getActions](#getActions--) | Ottiene le azioni del documento. |
| [getBackground](#getBackground--) | Ottiene il colore di sfondo del documento. |
| [getCatalogValue](#getCatalogValue-java.lang.String-) | Restituisce il valore dell'elemento dal dizionario del catalogo. |
| [getCollection](#getCollection--) | Ottiene la collezione del documento. |
| [getCryptoAlgorithm](#getCryptoAlgorithm--) | Ottiene le impostazioni di sicurezza se il documento è crittografato. |
| [getCustomSecurityHandler](#getCustomSecurityHandler--) | Ottiene un gestore di sicurezza personalizzato. |
| [getDefaultCopier](#getDefaultCopier--) | Restituisce il copiatore usato per copiare le pagine in questo documento. |
| [getDestinations](#getDestinations--) | Ottiene la collezione delle destinazioni. |
| [getDirection](#getDirection--) | Ottiene l'ordine di lettura del testo: L2R (da sinistra a destra) o R2L (da destra a sinistra). |
| [getDuplex](#getDuplex--) | Ottiene o imposta l'opzione di gestione della stampa duplex da utilizzare quando si stampa il file dalla finestra di stampa. |
| [getEmbeddedFiles](#getEmbeddedFiles--) | Ottiene la collezione dei file incorporati nel documento. |
| [getEmbedStandardFonts](#getEmbedStandardFonts--) | Proprietà che dichiara che il documento deve incorporare tutti i font Type1 standard il cui flag IsEmbedded è impostato su true. |
| [getEnableSignatureSanitization](#getEnableSignatureSanitization--) | Ottiene o imposta il flag per gestire la sanificazione dei campi firma. |
| [getEngineDoc](#getEngineDoc--) | Istanza di **IPdfDocument** usata per accedere alla struttura interna del documento. |
| [getFileName](#getFileName--) | Nome del file PDF che ha generato questo documento |
| [getForm](#getForm--) | Ottiene il modulo Acro Form del documento. |
| [getId](#getId--) | Ottiene l'ID. |
| [getIgnoreCorruptedObjects](#getIgnoreCorruptedObjects--) | Ottiene o imposta il flag per ignorare gli errori nei file sorgente. |
| [getInfo](#getInfo--) | Ottiene le informazioni del documento. |
| [getLogicalStructure](#getLogicalStructure--) | Ottiene la struttura logica del documento. |
| [getMetadata](#getMetadata--) | Metadati del documento. |
| [getMetadataStream](#getMetadataStream--) | Restituisce il flusso grezzo dei metadati |
| [getNamedDestinations](#getNamedDestinations--) | Raccolta di Destinazioni Nominative nel documento. |
| [getNonFullScreenPageMode](#getNonFullScreenPageMode--) | Ottiene la modalità pagina, specificando come visualizzare il documento uscendo dalla modalità a schermo intero. |
| [getObjectById](#getObjectById-java.lang.String-) | Ottiene un oggetto con ID specificato nel documento. |
| [getOpenAction](#getOpenAction--) | Ottiene l'azione eseguita all'apertura del documento. |
| [getOptimizeSize](#getOptimizeSize--) | Ottiene il flag di ottimizzazione. |
| [getOutlines](#getOutlines--) | Ottiene la struttura del documento. |
| [getPageInfo](#getPageInfo--) | Ottiene le informazioni della pagina (solo per il generatore, non compilate durante la lettura del documento) |
| [getPageLabels](#getPageLabels--) | Ottiene le etichette delle pagine nel documento. |
| [getPageLayout](#getPageLayout--) | Ottiene il layout della pagina da utilizzare quando il documento viene aperto. |
| [getPageMode](#getPageMode--) | Ottiene la modalità pagina, specificando come il documento dovrebbe essere visualizzato all'apertura. |
| [getPages](#getPages--) | Ottiene la raccolta delle pagine del documento. |
| [getPdfFormat](#getPdfFormat--) |  |
| [getPermissions](#getPermissions--) | Ottiene i permessi del documento. |
| [getPrintScaling](#getPrintScaling--) | Ottiene l'opzione di gestione della scala di stampa da utilizzare quando si stampa il file dalla finestra di stampa. |
| [getTaggedContent](#getTaggedContent--) | Ottiene l'accesso al contenuto TaggedPdf. |
| [getVersion](#getVersion--) | Ottiene una versione di Pdf dall'intestazione del file Pdf. |
| [getXmpMetadata](#getXmpMetadata-java.io.OutputStream-) | Ottieni i metadati XMP dal documento. |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.lang.String-) | Importa le annotazioni dal file XFDF al documento. |
| [isAbsentFontTryToSubstitute](#isAbsentFontTryToSubstitute--) | Notifica dei font mancanti durante l'elaborazione dei documenti |
| [isCenterWindow](#isCenterWindow--) | Ottiene il flag che specifica se la posizione della finestra del documento sarà centrata sullo schermo. |
| [isDisableFontLicenseVerifications](#isDisableFontLicenseVerifications--) | Molte operazioni con il font non possono essere eseguite se queste operazioni sono vietate dalla licenza di questo font. |
| [isDisplayDocTitle](#isDisplayDocTitle--) | Ottiene il flag che specifica se la barra del titolo della finestra del documento deve visualizzare il titolo del documento. |
| [isEncrypted](#isEncrypted--) | Ottiene lo stato di crittografia del documento. |
| [isFitWindow](#isFitWindow--) | Ottiene il flag che specifica se la finestra del documento deve essere ridimensionata per adattarsi alla prima pagina visualizzata. |
| [isHideMenubar](#isHideMenubar--) | Ottiene il flag che specifica se la barra dei menu deve essere nascosta quando il documento è attivo. |
| [isHideToolBar](#isHideToolBar--) | Ottiene il flag che specifica se la barra degli strumenti deve essere nascosta quando il documento è attivo. |
| [isHideWindowUI](#isHideWindowUI--) | Ottiene o imposta il flag che specifica se gli elementi dell'interfaccia utente devono essere nascosti quando il documento è attivo. |
| [isLinearized](#isLinearized--) | Ottiene o imposta un valore che indica se il documento è linearizzato. |
| [isManualDisposeEnabled](#isManualDisposeEnabled--) | Per impostazione predefinita il metodo save chiude i flussi interni e rilascia le risorse di memoria. Possiamo eseguire alcune operazioni e continuare a lavorare con il documento dopo il metodo save se questo parametro ManualDispose è abilitato. |
| [isPdfaCompliant](#isPdfaCompliant--) | Ottiene se il documento è conforme a PDF/A. |
| [isPdfUaCompliant](#isPdfUaCompliant--) | Ottiene se il documento è conforme a PDF/UA. |
| [isPickTrayByPdfSize](#isPickTrayByPdfSize--) | Ottiene un flag che specifica se la dimensione della pagina PDF deve essere usata per selezionare il vassoio di ingresso della carta. |
| [isXrefGapsAllowed](#isXrefGapsAllowed--) | Ottiene o imposta se il documento è conforme a PDF/A. |
| [optimize](#optimize--) | Linearizza il documento al fine di - aprire la prima pagina il più rapidamente possibile; - visualizzare la pagina successiva o seguire un collegamento alla pagina successiva il più rapidamente possibile; - visualizzare la pagina in modo incrementale man mano che arriva, quando i dati per una pagina vengono trasmessi su un canale lento (visualizzare prima i dati più utili); - consentire l'interazione dell'utente, come seguire un collegamento, anche prima che l'intera pagina sia stata ricevuta e visualizzata. |
| [optimizeResources](#optimizeResources--) | Ottimizza le risorse nel documento: 1. |
| [optimizeResources](#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-) | Ottimizza le risorse nel documento secondo la strategia di ottimizzazione definita. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree--) | Organizza i nodi dell'albero delle pagine in un documento in un albero bilanciato. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree-byte-) | Organizza i nodi dell'albero delle pagine in un documento in un albero bilanciato. |
| [processParagraphs](#processParagraphs--) | Memorizza il documento in un flusso. |
| [removeMetadata](#removeMetadata--) | Rimuove i metadati dal documento. |
| [removePdfaCompliance](#removePdfaCompliance--) | Rimuove la conformità PDF/A dal documento |
| [removePdfUaCompliance](#removePdfUaCompliance--) | Rimuove la conformità PDF/UA dal documento |
| [repair](#repair--) | Ripara il documento danneggiato. |
| [resumeUpdate](#resumeUpdate--) | resumeUpdate |
| [save](#save--) | Salva il documento in modo incrementale (ad es. |
| [save](#save-java.io.OutputStream-) | Memorizza il documento in un flusso. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-) | Salva il documento |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | Salva il documento con un nuovo nome impostando le sue opzioni di salvataggio. |
| [save](#save-java.lang.String-) | Salva il documento nel file specificato. |
| [save](#save-java.lang.String-com.aspose.pdf.SaveOptions-) | Salva il documento con un nuovo nome impostando le sue opzioni di salvataggio. |
| [saveIncrementally](#saveIncrementally-java.io.OutputStream-) | Salva in modo incrementale il documento PDF nello stream specificato. |
| [saveIncrementally](#saveIncrementally-com.aspose.ms.System.IO.Stream-) | Salva in modo incrementale il documento PDF nello stream specificato. |
| [saveIncrementally](#saveIncrementally-java.lang.String-) | Salva in modo incrementale il documento PDF nello stream specificato. |
| [saveXml](#saveXml-java.lang.String-) | Salva il documento in XML. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-) | Invia le pagine specifiche del documento al dispositivo del documento per l'elaborazione. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-) | Invia l'intero documento al dispositivo del documento per l'elaborazione. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-) | Invia l'intero documento al dispositivo del documento per l'elaborazione. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-) | Invia l'intero documento al dispositivo del documento per l'elaborazione. |
| [setAbsentFontTryToSubstitute](#setAbsentFontTryToSubstitute-boolean-) | Imposta il flag per impostare il carattere determinato dal programma in caso di assenza del carattere. |
| [setBackground](#setBackground-java.awt.Color-) | Imposta il colore di sfondo del documento. |
| [setCenterWindow](#setCenterWindow-boolean-) | Imposta il flag che specifica se la posizione della finestra del documento sarà centrata sullo schermo. |
| [setCollection](#setCollection-com.aspose.pdf.Collection-) | Imposta la raccolta del documento. |
| [setConvertMetadataAndCatalogOnly](#setConvertMetadataAndCatalogOnly-boolean-) | Ottiene il parametro di conversione per il convertitore pdf/ua (Converti solo i Metadati e il Catalogo del Documento se impostato su true). |
| [setDirection](#setDirection-com.aspose.pdf.Direction-) | Imposta l'ordine di lettura del testo: L2R (da sinistra a destra) o R2L (da destra a sinistra). |
| [setDisableFontLicenseVerifications](#setDisableFontLicenseVerifications-boolean-) | Molte operazioni con il font non possono essere eseguite se queste operazioni sono vietate dalla licenza di questo font. |
| [setDisplayDocTitle](#setDisplayDocTitle-boolean-) | Imposta il flag che specifica se la barra del titolo della finestra del documento deve visualizzare il titolo del documento. |
| [setDuplex](#setDuplex-int-) | Ottiene o imposta l'opzione di gestione della stampa duplex da utilizzare quando si stampa il file dalla finestra di stampa. |
| [setEmbedStandardFonts](#setEmbedStandardFonts-boolean-) | Proprietà che dichiara che il documento deve incorporare tutti i font Type1 standard il cui flag IsEmbedded è impostato su true. |
| [setEnableSignatureSanitization](#setEnableSignatureSanitization-boolean-) | Ottiene o imposta il flag per gestire la sanificazione dei campi firma. |
| [setFitWindow](#setFitWindow-boolean-) | Imposta il flag che specifica se la finestra del documento deve essere ridimensionata per adattarsi alla prima pagina visualizzata. |
| [setHideMenubar](#setHideMenubar-boolean-) | Imposta il flag che specifica se la barra dei menu deve essere nascosta quando il documento è attivo. |
| [setHideToolBar](#setHideToolBar-boolean-) | Imposta il flag che specifica se la barra degli strumenti deve essere nascosta quando il documento è attivo. |
| [setHideWindowUI](#setHideWindowUI-boolean-) | Imposta il flag che specifica se gli elementi dell'interfaccia utente devono essere nascosti quando il documento è attivo. |
| [setIgnoreCorruptedObjects](#setIgnoreCorruptedObjects-boolean-) |  |
| [setLinearized](#setLinearized-boolean-) | Imposta un valore che indica se il documento è linearizzato. |
| [setManualDisposeEnabled](#setManualDisposeEnabled-boolean-) | Per impostazione predefinita, il metodo save chiude i flussi interni e rilascia le risorse di memoria. Possiamo eseguire alcune operazioni e continuare a lavorare con il documento dopo che il metodo save è stato chiamato se questo parametro ManualDispose è abilitato. Tuttavia è fortemente consigliato chiamare il metodo dispose quando l'istanza Document non è più necessaria. |
| [setNonFullScreenPageMode](#setNonFullScreenPageMode-com.aspose.pdf.PageMode-) | Imposta la modalità pagina, specificando come visualizzare il documento uscendo dalla modalità a schermo intero. |
| [setOpenAction](#setOpenAction-com.aspose.pdf.IAppointment-) | Imposta l'azione eseguita all'apertura del documento. |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Imposta il flag di ottimizzazione. |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Imposta le informazioni della pagina (solo per il generatore, non compilate durante la lettura del documento). |
| [setPageLayout](#setPageLayout-com.aspose.pdf.PageLayout-) | Imposta il layout della pagina da utilizzare quando il documento viene aperto. |
| [setPageMode](#setPageMode-com.aspose.pdf.PageMode-) | Imposta la modalità pagina, specificando come il documento deve essere visualizzato quando aperto. |
| [setPickTrayByPdfSize](#setPickTrayByPdfSize-boolean-) | Imposta un flag che specifica se la dimensione della pagina PDF deve essere usata per selezionare il vassoio di ingresso della carta. |
| [setPrintScaling](#setPrintScaling-int-) | Imposta l'opzione di gestione della scala di stampa da utilizzare quando si stampa il file dalla finestra di dialogo di stampa. |
| [setTitle](#setTitle-java.lang.String-) | Imposta il titolo per il documento PDF. |
| [setXmpMetadata](#setXmpMetadata-java.io.InputStream-) | Imposta i metadati XMP del documento. |
| [setXrefGapsAllowed](#setXrefGapsAllowed-boolean-) | Ottiene o imposta se il documento è conforme a PDF/A. |
| [suppressUpdate](#suppressUpdate--) | suppressUpdate |
| [updatePages](#updatePages--) | updatePages |
| [validate](#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-) | Convalida il documento nel file specificato. |
| [validate](#validate-java.lang.String-com.aspose.pdf.PdfFormat-) | Convalida il documento nel file specificato. |

### afterImport {#afterImport--}
```
void afterImport()
```

Enumera tutte le annotazioni registrate e chiama AfterImport per ciascuna di esse.

### bindXml {#bindXml-java.io.InputStream-}
Associa xml al documento

### bindXml {#bindXml-java.lang.String-}
Associa xml al documento

### bindXml {#bindXml-java.lang.String-java.lang.String-}
Associa xml/xsl al documento

### changePasswords {#changePasswords-java.lang.String-java.lang.String-java.lang.String-}
Modifica le password del documento.

### check {#check-boolean-}
```
boolean check(boolean doRepair)
```

Convalida il documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| doRepair |  | Se vero, i problemi trovati saranno riparati. |

**Returns:**
valore booleano

### close {#close--}
```
void close()
```

Chiude tutte le risorse utilizzate da questo documento.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-}
Converti il documento in un documento ricercabile.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-}
Converti il documento in un documento ricercabile e ignora gli errori di hochr che non possono essere convertiti.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-}
Converti il documento e salva gli errori nel file specificato.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-}
Converti il documento e salva gli errori nel file specificato.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-}
Converti il documento e salva gli errori nel file specificato. <p> Questo consente di mostrare/nascondere il testo ricercabile nella pagina. Il valore predefinito è FALSE. Questo consente di ottenere l'immagine originale dal pdf. Il valore predefinito è FALSE.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-}
Converti il documento e salva gli errori nel file specificato. <p> Questo consente di mostrare/nascondere il testo ricercabile nella pagina. Il valore predefinito è FALSE. Questo consente di ottenere l'immagine originale dal pdf. Il valore predefinito è FALSE.

### convert {#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}


### convert {#convert-com.aspose.pdf.PdfFormatConversionOptions-}
Converti il documento usando le opzioni di conversione specificate

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Converti il documento e salva gli errori nel file specificato.

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
Converti il documento e salva gli errori nel file specificato.

### convertInternal {#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Metodo interno

### convertWithFlatten {#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-}
Converti il documento in un documento ricercabile e ignora gli errori di hochr che non possono essere convertiti.

### convertWithSkippingErrors {#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-}
Converti il documento in un documento ricercabile e ignora gli errori di hochr che non possono essere convertiti.

### decrypt {#decrypt--}
```
void decrypt()
```

Decripta il documento.

### dispose {#dispose--}
```
@Deprecated void dispose()
```

Obsoleto.

### encrypt {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-}
Cripta il documento.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-}
Cripta il documento.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-}
Cripta il documento.

### exportAnnotationsToXfdf {#exportAnnotationsToXfdf-java.lang.String-}
Esporta tutte le annotazioni del documento in un file XFDF

### flatten {#flatten--}
```
void flatten()
```

Rimuove tutti i campi (e le annotazioni) dal documento e ne inserisce i valori al loro posto.

### flatten {#flatten-com.aspose.pdf.Form.FlattenSettings-}
Rimuove tutti i campi dal documento e ne inserisce i valori al loro posto.

### flattenTransparency {#flattenTransparency--}
```
void flattenTransparency()
```

Sostituisce il contenuto trasparente con grafica raster e vettoriale non trasparente.

### freeMemory {#freeMemory--}
```
void freeMemory()
```

Cancella la memoria

### getActions {#getActions--}
```
DocumentActionCollection getActions()
```

Ottiene le azioni del documento.

**Returns:**
DocumentActionCollection oggetto

### getBackground {#getBackground--}
```
Color getBackground()
```

Ottiene il colore di sfondo del documento.

**Returns:**
java.awt.Color oggetto

### getCatalogValue {#getCatalogValue-java.lang.String-}
Restituisce il valore dell'elemento dal dizionario del catalogo.

### getCollection {#getCollection--}
```
Collection getCollection()
```

Ottiene la collezione del documento.

**Returns:**
Collection oggetto

### getCryptoAlgorithm {#getCryptoAlgorithm--}
```
CryptoAlgorithm getCryptoAlgorithm()
```

Ottiene le impostazioni di sicurezza se il documento è crittografato.

**Returns:**
CryptoAlgorithm elemento oppure null

### getCustomSecurityHandler {#getCustomSecurityHandler--}
```
com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler getCustomSecurityHandler()
```

Ottiene un gestore di sicurezza personalizzato.

**Returns:**
ICustomSecurityHandler istanza

### getDefaultCopier {#getDefaultCopier--}
```
Copier getDefaultCopier()
```

Restituisce il copiatore usato per copiare le pagine in questo documento.

**Returns:**
Copier oggetto

### getDestinations {#getDestinations--}
```
DestinationCollection getDestinations()
```

Ottiene la collezione delle destinazioni.

**Returns:**
DestinationCollection oggetto

### getDirection {#getDirection--}
```
Direction getDirection()
```

Ottiene l'ordine di lettura del testo: L2R (da sinistra a destra) o R2L (da destra a sinistra).

**Returns:**
Direction elemento

### getDuplex {#getDuplex--}
```
int getDuplex()
```

Ottiene o imposta l'opzione di gestione della stampa duplex da utilizzare quando si stampa il file dalla finestra di stampa.

**Returns:**
PrintDuplex elemento

### getEmbeddedFiles {#getEmbeddedFiles--}
```
EmbeddedFileCollection getEmbeddedFiles()
```

Ottiene la collezione dei file incorporati nel documento.

**Returns:**
EmbeddedFileCollection oggetto

### getEmbedStandardFonts {#getEmbedStandardFonts--}
```
boolean getEmbedStandardFonts()
```

Proprietà che dichiara che il documento deve incorporare tutti i font Type1 standard il cui flag IsEmbedded è impostato su true.

**Returns:**
valore booleano

### getEnableSignatureSanitization {#getEnableSignatureSanitization--}
```
boolean getEnableSignatureSanitization()
```

Ottiene o imposta il flag per gestire la sanificazione dei campi firma.

**Returns:**
valore booleano

### getEngineDoc {#getEngineDoc--}
```
com.aspose.pdf.engine.IPdfDocument getEngineDoc()
```

Istanza di **IPdfDocument** usata per accedere alla struttura interna del documento.

**Returns:**
IPdfDocument oggetto

### getFileName {#getFileName--}
```
String getFileName()
```

Nome del file PDF che ha generato questo documento

**Returns:**
Oggetto stringa

### getForm {#getForm--}
```
Form getForm()
```

Ottiene il modulo Acro Form del documento.

**Returns:**
Form oggetto

### getId {#getId--}
```
Id getId()
```

Ottiene l'ID.

**Returns:**
Id oggetto

### getIgnoreCorruptedObjects {#getIgnoreCorruptedObjects--}
```
boolean getIgnoreCorruptedObjects()
```

Ottiene o imposta il flag per ignorare gli errori nei file sorgente.

**Returns:**
valore booleano

### getInfo {#getInfo--}
```
DocumentInfo getInfo()
```

Ottiene le informazioni del documento.

**Returns:**
DocumentInfo oggetto

### getLogicalStructure {#getLogicalStructure--}
```
RootElement getLogicalStructure()
```

Ottiene la struttura logica del documento.

**Returns:**
RootElement oggetto

### getMetadata {#getMetadata--}
```
Metadata getMetadata()
```

Metadati del documento.

**Returns:**
Metadata oggetto

### getMetadataStream {#getMetadataStream--}
```
com.aspose.pdf.engine.data.types.IPdfStreamAccessor getMetadataStream()
```

Restituisce il flusso grezzo dei metadati

**Returns:**
IPdfStreamAccessor oggetto

### getNamedDestinations {#getNamedDestinations--}
```
NamedDestinationCollection getNamedDestinations()
```

Raccolta di Destinazioni Nominative nel documento.

**Returns:**
NamedDestinationCollection istanza

### getNonFullScreenPageMode {#getNonFullScreenPageMode--}
```
PageMode getNonFullScreenPageMode()
```

Ottiene la modalità pagina, specificando come visualizzare il documento uscendo dalla modalità a schermo intero.

**Returns:**
PageMode elemento

### getObjectById {#getObjectById-java.lang.String-}
Ottiene un oggetto con ID specificato nel documento.

### getOpenAction {#getOpenAction--}
```
IAppointment getOpenAction()
```

Ottiene l'azione eseguita all'apertura del documento.

**Returns:**
IAppointment oggetto

### getOptimizeSize {#getOptimizeSize--}
```
boolean getOptimizeSize()
```

Ottiene il flag di ottimizzazione.

**Returns:**
valore booleano

### getOutlines {#getOutlines--}
```
OutlineCollection getOutlines()
```

Ottiene la struttura del documento.

**Returns:**
Oggetto OutlineCollection

### getPageInfo {#getPageInfo--}
```
PageInfo getPageInfo()
```

Ottiene le informazioni della pagina (solo per il generatore, non compilate durante la lettura del documento)

**Returns:**
Le informazioni della pagina.

### getPageLabels {#getPageLabels--}
```
PageLabelCollection getPageLabels()
```

Ottiene le etichette delle pagine nel documento.

**Returns:**
Oggetto PageLabelCollection

### getPageLayout {#getPageLayout--}
```
PageLayout getPageLayout()
```

Ottiene il layout della pagina da utilizzare quando il documento viene aperto.

**Returns:**
Elemento PageLayout

### getPageMode {#getPageMode--}
```
PageMode getPageMode()
```

Ottiene la modalità pagina, specificando come il documento dovrebbe essere visualizzato all'apertura.

**Returns:**
PageMode elemento

### getPages {#getPages--}
```
PageCollection getPages()
```

Ottiene la raccolta delle pagine del documento.

**Returns:**
valore booleano

### getPdfFormat {#getPdfFormat--}
```
PdfFormat getPdfFormat()
```



**Returns:**
Elemento PdfFormat

### getPermissions {#getPermissions--}
```
int getPermissions()
```

Ottiene i permessi del documento.

**Returns:**
valore int

### getPrintScaling {#getPrintScaling--}
```
int getPrintScaling()
```

Ottiene l'opzione di gestione della scala di stampa da utilizzare quando si stampa il file dalla finestra di stampa.

**Returns:**
Elemento PrintScaling

### getTaggedContent {#getTaggedContent--}
```
ITaggedContent getTaggedContent()
```

Ottiene l'accesso al contenuto TaggedPdf.

**Returns:**
Istanza ITaggedContent

### getVersion {#getVersion--}
```
String getVersion()
```

Ottiene una versione di Pdf dall'intestazione del file Pdf.

**Returns:**
Oggetto stringa

### getXmpMetadata {#getXmpMetadata-java.io.OutputStream-}
Ottieni i metadati XMP dal documento.

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.lang.String-}
Importa le annotazioni dal file XFDF al documento.

### isAbsentFontTryToSubstitute {#isAbsentFontTryToSubstitute--}
```
boolean isAbsentFontTryToSubstitute()
```

Notifica dei font mancanti durante l'elaborazione dei documenti

**Returns:**
valore booleano

### isCenterWindow {#isCenterWindow--}
```
boolean isCenterWindow()
```

Ottiene il flag che specifica se la posizione della finestra del documento sarà centrata sullo schermo.

**Returns:**
valore booleano

### isDisableFontLicenseVerifications {#isDisableFontLicenseVerifications--}
```
boolean isDisableFontLicenseVerifications()
```

Molte operazioni con il font non possono essere eseguite se queste operazioni sono vietate dalla licenza di questo font.

**Returns:**
Valore booleano, per impostazione predefinita false.

### isDisplayDocTitle {#isDisplayDocTitle--}
```
boolean isDisplayDocTitle()
```

Ottiene il flag che specifica se la barra del titolo della finestra del documento deve visualizzare il titolo del documento.

**Returns:**
valore booleano

### isEncrypted {#isEncrypted--}
```
boolean isEncrypted()
```

Ottiene lo stato di crittografia del documento.

**Returns:**
valore booleano

### isFitWindow {#isFitWindow--}
```
boolean isFitWindow()
```

Ottiene il flag che specifica se la finestra del documento deve essere ridimensionata per adattarsi alla prima pagina visualizzata.

**Returns:**
valore booleano

### isHideMenubar {#isHideMenubar--}
```
boolean isHideMenubar()
```

Ottiene il flag che specifica se la barra dei menu deve essere nascosta quando il documento è attivo.

**Returns:**
valore booleano

### isHideToolBar {#isHideToolBar--}
```
boolean isHideToolBar()
```

Ottiene il flag che specifica se la barra degli strumenti deve essere nascosta quando il documento è attivo.

**Returns:**
valore booleano

### isHideWindowUI {#isHideWindowUI--}
```
boolean isHideWindowUI()
```

Ottiene o imposta il flag che specifica se gli elementi dell'interfaccia utente devono essere nascosti quando il documento è attivo.

**Returns:**
valore booleano

### isLinearized {#isLinearized--}
```
boolean isLinearized()
```

Ottiene o imposta un valore che indica se il documento è linearizzato.

**Returns:**
valore booleano

### isManualDisposeEnabled {#isManualDisposeEnabled--}
```
boolean isManualDisposeEnabled()
```

Per impostazione predefinita il metodo save chiude i flussi interni e rilascia le risorse di memoria. Possiamo eseguire alcune operazioni e continuare a lavorare con il documento dopo il metodo save se questo parametro ManualDispose è abilitato.

**Returns:**
Valore booleano. (Valore predefinito == false)

### isPdfaCompliant {#isPdfaCompliant--}
```
boolean isPdfaCompliant()
```

Ottiene se il documento è conforme a PDF/A.

**Returns:**
valore booleano

### isPdfUaCompliant {#isPdfUaCompliant--}
```
boolean isPdfUaCompliant()
```

Ottiene se il documento è conforme a PDF/UA.

**Returns:**
valore booleano

### isPickTrayByPdfSize {#isPickTrayByPdfSize--}
```
boolean isPickTrayByPdfSize()
```

Ottiene un flag che specifica se la dimensione della pagina PDF deve essere usata per selezionare il vassoio di ingresso della carta.

**Returns:**
valore booleano

### isXrefGapsAllowed {#isXrefGapsAllowed--}
```
boolean isXrefGapsAllowed()
```

Ottiene o imposta se il documento è conforme a PDF/A.

**Returns:**
valore booleano

### optimize {#optimize--}
```
void optimize()
```

Linearizza il documento al fine di - aprire la prima pagina il più rapidamente possibile; - visualizzare la pagina successiva o seguire un collegamento alla pagina successiva il più rapidamente possibile; - visualizzare la pagina in modo incrementale man mano che arriva, quando i dati per una pagina vengono trasmessi su un canale lento (visualizzare prima i dati più utili); - consentire l'interazione dell'utente, come seguire un collegamento, anche prima che l'intera pagina sia stata ricevuta e visualizzata.

### optimizeResources {#optimizeResources--}
```
void optimizeResources()
```

Ottimizza le risorse nel documento: 1.

### optimizeResources {#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-}
Ottimizza le risorse nel documento secondo la strategia di ottimizzazione definita.

### pageNodesToBalancedTree {#pageNodesToBalancedTree--}
```
void pageNodesToBalancedTree()
```

Organizza i nodi dell'albero delle pagine in un documento in un albero bilanciato.

### pageNodesToBalancedTree {#pageNodesToBalancedTree-byte-}
```
void pageNodesToBalancedTree(byte nodesNumInSubtrees)
```

Organizza i nodi dell'albero delle pagine in un documento in un albero bilanciato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nodesNumInSubtrees |  | Numero desiderato di sotto-nodi. Valore predefinito è dieci. |

### processParagraphs {#processParagraphs--}
```
void processParagraphs()
```

Memorizza il documento in un flusso.

### removeMetadata {#removeMetadata--}
```
void removeMetadata()
```

Rimuove i metadati dal documento.

### removePdfaCompliance {#removePdfaCompliance--}
```
void removePdfaCompliance()
```

Rimuove la conformità PDF/A dal documento

### removePdfUaCompliance {#removePdfUaCompliance--}
```
void removePdfUaCompliance()
```

Rimuove la conformità PDF/UA dal documento

### repair {#repair--}
```
void repair()
```

Ripara il documento danneggiato.

### resumeUpdate {#resumeUpdate--}
```
void resumeUpdate()
```

resumeUpdate

### save {#save--}
```
void save()
```

Salva il documento in modo incrementale (ad es.

### save {#save-java.io.OutputStream-}
Memorizza il documento in un flusso.

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-}
Salva il documento

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
Salva il documento con un nuovo nome impostando le sue opzioni di salvataggio.

### save {#save-java.lang.String-}
Salva il documento nel file specificato.

### save {#save-java.lang.String-com.aspose.pdf.SaveOptions-}
Salva il documento con un nuovo nome impostando le sue opzioni di salvataggio.

### saveIncrementally {#saveIncrementally-java.io.OutputStream-}
Salva in modo incrementale il documento PDF nello stream specificato.

### saveIncrementally {#saveIncrementally-com.aspose.ms.System.IO.Stream-}
Salva in modo incrementale il documento PDF nello stream specificato.

### saveIncrementally {#saveIncrementally-java.lang.String-}
Salva in modo incrementale il documento PDF nello stream specificato.

### saveXml {#saveXml-java.lang.String-}
Salva il documento in XML.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-}
Invia le pagine specifiche del documento al dispositivo del documento per l'elaborazione.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-}
Invia l'intero documento al dispositivo del documento per l'elaborazione.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-}
Invia l'intero documento al dispositivo del documento per l'elaborazione.

### sendTo {#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-}
Invia l'intero documento al dispositivo del documento per l'elaborazione.

### setAbsentFontTryToSubstitute {#setAbsentFontTryToSubstitute-boolean-}
```
void setAbsentFontTryToSubstitute(boolean setAbsentFontTryToSubstitute)
```

Imposta il flag per impostare il carattere determinato dal programma in caso di assenza del carattere.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| setAbsentFontTryToSubstitute |  | valore booleano |

### setBackground {#setBackground-java.awt.Color-}
Imposta il colore di sfondo del documento.

### setCenterWindow {#setCenterWindow-boolean-}
```
void setCenterWindow(boolean value)
```

Imposta il flag che specifica se la posizione della finestra del documento sarà centrata sullo schermo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setCollection {#setCollection-com.aspose.pdf.Collection-}
Imposta la raccolta del documento.

### setConvertMetadataAndCatalogOnly {#setConvertMetadataAndCatalogOnly-boolean-}
```
void setConvertMetadataAndCatalogOnly(boolean value)
```

Ottiene il parametro di conversione per il convertitore pdf/ua (Converti solo i Metadati e il Catalogo del Documento se impostato su true).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setDirection {#setDirection-com.aspose.pdf.Direction-}
Imposta l'ordine di lettura del testo: L2R (da sinistra a destra) o R2L (da destra a sinistra).

### setDisableFontLicenseVerifications {#setDisableFontLicenseVerifications-boolean-}
```
void setDisableFontLicenseVerifications(boolean value)
```

Molte operazioni con il font non possono essere eseguite se queste operazioni sono vietate dalla licenza di questo font.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Valore booleano, per impostazione predefinita false. |

### setDisplayDocTitle {#setDisplayDocTitle-boolean-}
```
void setDisplayDocTitle(boolean value)
```

Imposta il flag che specifica se la barra del titolo della finestra del documento deve visualizzare il titolo del documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setDuplex {#setDuplex-int-}
```
void setDuplex(int value)
```

Ottiene o imposta l'opzione di gestione della stampa duplex da utilizzare quando si stampa il file dalla finestra di stampa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | PrintDuplex elemento |

### setEmbedStandardFonts {#setEmbedStandardFonts-boolean-}
```
void setEmbedStandardFonts(boolean value)
```

Proprietà che dichiara che il documento deve incorporare tutti i font Type1 standard il cui flag IsEmbedded è impostato su true.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setEnableSignatureSanitization {#setEnableSignatureSanitization-boolean-}
```
void setEnableSignatureSanitization(boolean value)
```

Ottiene o imposta il flag per gestire la sanificazione dei campi firma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setFitWindow {#setFitWindow-boolean-}
```
void setFitWindow(boolean value)
```

Imposta il flag che specifica se la finestra del documento deve essere ridimensionata per adattarsi alla prima pagina visualizzata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setHideMenubar {#setHideMenubar-boolean-}
```
void setHideMenubar(boolean value)
```

Imposta il flag che specifica se la barra dei menu deve essere nascosta quando il documento è attivo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setHideToolBar {#setHideToolBar-boolean-}
```
void setHideToolBar(boolean value)
```

Imposta il flag che specifica se la barra degli strumenti deve essere nascosta quando il documento è attivo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setHideWindowUI {#setHideWindowUI-boolean-}
```
void setHideWindowUI(boolean value)
```

Imposta il flag che specifica se gli elementi dell'interfaccia utente devono essere nascosti quando il documento è attivo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setIgnoreCorruptedObjects {#setIgnoreCorruptedObjects-boolean-}
```
void setIgnoreCorruptedObjects(boolean value)
```



### setLinearized {#setLinearized-boolean-}
```
void setLinearized(boolean value)
```

Imposta un valore che indica se il documento è linearizzato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setManualDisposeEnabled {#setManualDisposeEnabled-boolean-}
```
void setManualDisposeEnabled(boolean manualDisposeEnabled)
```

Per impostazione predefinita, il metodo save chiude i flussi interni e rilascia le risorse di memoria. Possiamo eseguire alcune operazioni e continuare a lavorare con il documento dopo che il metodo save è stato chiamato se questo parametro ManualDispose è abilitato. Tuttavia è fortemente consigliato chiamare il metodo dispose quando l'istanza Document non è più necessaria.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| manualDisposeEnabled |  | Valore booleano. (Valore predefinito == false) |

### setNonFullScreenPageMode {#setNonFullScreenPageMode-com.aspose.pdf.PageMode-}
Imposta la modalità pagina, specificando come visualizzare il documento uscendo dalla modalità a schermo intero.

### setOpenAction {#setOpenAction-com.aspose.pdf.IAppointment-}
Imposta l'azione eseguita all'apertura del documento.

### setOptimizeSize {#setOptimizeSize-boolean-}
```
void setOptimizeSize(boolean value)
```

Imposta il flag di ottimizzazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
Imposta le informazioni della pagina (solo per il generatore, non compilate durante la lettura del documento).

### setPageLayout {#setPageLayout-com.aspose.pdf.PageLayout-}
Imposta il layout della pagina da utilizzare quando il documento viene aperto.

### setPageMode {#setPageMode-com.aspose.pdf.PageMode-}
Imposta la modalità pagina, specificando come il documento deve essere visualizzato quando aperto.

### setPickTrayByPdfSize {#setPickTrayByPdfSize-boolean-}
```
void setPickTrayByPdfSize(boolean value)
```

Imposta un flag che specifica se la dimensione della pagina PDF deve essere usata per selezionare il vassoio di ingresso della carta.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setPrintScaling {#setPrintScaling-int-}
```
void setPrintScaling(int value)
```

Imposta l'opzione di gestione della scala di stampa da utilizzare quando si stampa il file dalla finestra di dialogo di stampa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | PrintDuplex elemento |

### setTitle {#setTitle-java.lang.String-}
Imposta il titolo per il documento PDF.

### setXmpMetadata {#setXmpMetadata-java.io.InputStream-}
Imposta i metadati XMP del documento.

### setXrefGapsAllowed {#setXrefGapsAllowed-boolean-}
```
void setXrefGapsAllowed(boolean value)
```

Ottiene o imposta se il documento è conforme a PDF/A.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### suppressUpdate {#suppressUpdate--}
```
void suppressUpdate()
```

suppressUpdate

### updatePages {#updatePages--}
```
void updatePages()
```

updatePages

### validate {#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-}
Convalida il documento nel file specificato.

### validate {#validate-java.lang.String-com.aspose.pdf.PdfFormat-}
Convalida il documento nel file specificato.
