---
title: "DocumentWeb"
linktitle: "DocumentWeb"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta la classe DocumentWeb"
type: docs
weight: 1170
url: /it/java/com.aspose.pdf/documentweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.DocumentWeb

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IDocument, Closeable, AutoCloseable

```
public final class DocumentWeb extends Object implements IDocument
```

Rappresenta la classe DocumentWeb

## Campi

| Campo | Descrizione |
| --- | --- |
| [DefaultNodesNumInSubtrees](#DefaultNodesNumInSubtrees) |  |
| [FontSubstitution](#FontSubstitution) | Si verifica quando il font sostituisce un altro font nel documento. |

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [DocumentWeb](#DocumentWeb--) | Inizializza un DocumentWeb vuoto. |
| [DocumentWeb](#DocumentWeb-java.io.InputStream-) | Inizializza un DocumentWeb vuoto. |
| [DocumentWeb](#DocumentWeb-java.io.InputStream-com.aspose.pdf.LoadOptions-) | Inizializza un DocumentWeb vuoto. |
| [DocumentWeb](#DocumentWeb-java.io.InputStream-java.lang.String-) | Inizializza un DocumentWeb vuoto. |
| [DocumentWeb](#DocumentWeb-java.lang.String-) | Inizializza un DocumentWeb vuoto. |
| [DocumentWeb](#DocumentWeb-java.lang.String-com.aspose.pdf.LoadOptions-) | Inizializza un DocumentWeb vuoto. |
| [DocumentWeb](#DocumentWeb-java.lang.String-java.lang.String-) | Inizializza un DocumentWeb vuoto. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [afterImport](#afterImport--) | Enumera tutte le annotazioni registrate e chiama AfterImport per ciascuna di esse. |
| [bindXml](#bindXml-java.io.InputStream-) | Associa xml al documento |
| [bindXml](#bindXml-java.io.InputStream-java.io.InputStream-) | Associa xml/xsl al documento |
| [bindXml](#bindXml-java.io.InputStream-java.io.InputStream-com.aspose.ms.System.Xml.XmlReaderSettings-) | Associa xml/xsl al documento |
| [bindXml](#bindXml-java.lang.String-) | Associa xml al documento |
| [bindXml](#bindXml-java.lang.String-java.lang.String-) | Associa xml/xsl al documento |
| [changePasswords](#changePasswords-java.lang.String-java.lang.String-java.lang.String-) | Modifica le password del documento. |
| [check](#check-boolean-) | Convalida il documento. |
| [close](#close--) | Chiude tutte le risorse utilizzate da questo documento. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-) | Converti il documento in un documento ricercabile. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-) | Converti il documento e salva gli errori nel file specificato. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-) | Converti il documento e salva gli errori nel file specificato. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-) | Converti il documento e salva gli errori nel file specificato. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-) | Converti il documento e salva gli errori nel file specificato. |
| [convert](#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-) | Converti il documento e salva gli errori nel file specificato. |
| [convert](#convert-com.aspose.pdf.Fixup-java.io.OutputStream-) | Converti il documento applicando il Fixup. |
| [convert](#convert-com.aspose.pdf.Fixup-java.io.OutputStream-boolean-java.lang.Object:A-) | Converti il documento applicando il Fixup. |
| [convert](#convert-com.aspose.pdf.Fixup-java.lang.String-) | Converti il documento applicando il Fixup. |
| [convert](#convert-com.aspose.pdf.Fixup-java.lang.String-boolean-java.lang.Object:A-) | Converti il documento applicando il Fixup. |
| [convert](#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | Converte lo stream nel formato di origine in uno stream nel formato di destinazione. |
| [convert](#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-) | Converte lo stream nel formato di origine in un file di destinazione nel formato di destinazione. |
| [convert](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Converti il documento e salva gli errori nello stream specificato. |
| [convert](#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | Converti il documento e salva gli errori nel file specificato. |
| [convert](#convert-com.aspose.pdf.PdfFormatConversionOptions-) | Converti il documento usando le opzioni di conversione specificate |
| [convert](#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | Converte il file di origine nel formato di origine in uno stream nel formato di destinazione. |
| [convert](#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-) | Converte il file di origine nel formato di origine in un file di destinazione nel formato di destinazione. |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Converti il documento e salva gli errori nel file specificato. |
| [convert](#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | Converti il documento e salva gli errori nel file specificato. |
| [convertInternal](#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Converti il documento e salva gli errori nello stream specificato. |
| [convertPageToPNGMemoryStream](#convertPageToPNGMemoryStream-com.aspose.pdf.Page-) | Converti la pagina in PNG per lo stream di immagine DSR, OMR, OCR. |
| [convertWithFlatten](#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-) | Converti il documento in un documento ricercabile e ignora gli errori di hochr che non possono essere convertiti. |
| [convertWithSkippingErrors](#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-) | Converti il documento in un documento ricercabile e ignora gli errori di hochr che non possono essere convertiti. |
| [decrypt](#decrypt--) | Decripta il documento. |
| [dispose](#dispose--) | Obsoleto. |
| [encrypt](#encrypt-int-com.aspose.pdf.CryptoAlgorithm-com.aspose.ms.System.Collections.Generic.IGenericList-) | Cripta il documento. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-) | Cripta il documento. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Cripta il documento. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-) | Cripta il documento. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-) | Cripta il documento. |
| [encrypt](#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | Cripta il documento. |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.io.OutputStream-) | Esporta tutte le annotazioni del documento nello stream. |
| [exportAnnotationsToXfdf](#exportAnnotationsToXfdf-java.lang.String-) | Esporta tutte le annotazioni del documento in un file XFDF |
| [flatten](#flatten--) | Rimuove tutti i campi (e le annotazioni) dal documento e ne inserisce i valori al loro posto. |
| [flatten](#flatten-com.aspose.pdf.Form.FlattenSettings-) | Rimuove tutti i campi dal documento e ne inserisce i valori al loro posto. |
| [flattenTransparency](#flattenTransparency--) | Sostituisce il contenuto trasparente con grafica raster e vettoriale non trasparente. |
| [freeMemory](#freeMemory--) | Cancella la memoria |
| [getAbsentFontHandler](#getAbsentFontHandler--) | Notifica dei font mancanti durante l'elaborazione dei documenti. |
| [getActions](#getActions--) | Ottiene le azioni del documento. |
| [getAllowReusePageContent](#getAllowReusePageContent--) | Consente di unire i contenuti delle pagine per ottimizzare le dimensioni del documento. |
| [getBackground](#getBackground--) | Ottiene il colore di sfondo del documento. |
| [getCatalogValue](#getCatalogValue-java.lang.String-) | Restituisce il valore dell'elemento dal dizionario del catalogo. |
| [getCollection](#getCollection--) | Ottiene la collezione del documento. |
| [getCryptoAlgorithm](#getCryptoAlgorithm--) | Ottiene le impostazioni di sicurezza se il documento è crittografato. |
| [getCustomSecurityHandler](#getCustomSecurityHandler--) | Ottiene un gestore di sicurezza personalizzato. |
| [getDefaultCopier](#getDefaultCopier--) | Restituisce il copiatore usato per copiare le pagine in questo documento. |
| [getDestinations](#getDestinations--) | Obsoleto. |
| [getDirection](#getDirection--) | Ottiene l'ordine di lettura del testo: L2R (da sinistra a destra) o R2L (da destra a sinistra). |
| [getDuplex](#getDuplex--) | Ottiene o imposta l'opzione di gestione della stampa duplex da utilizzare quando si stampa il file dalla finestra di stampa. |
| [getEmbeddedFiles](#getEmbeddedFiles--) | Ottiene la collezione dei file incorporati nel documento. |
| [getEmbedStandardFonts](#getEmbedStandardFonts--) | Proprietà che dichiara che il documento deve incorporare tutti i font Type1 standard il cui flag IsEmbedded è impostato su true. |
| [getEnableSignatureSanitization](#getEnableSignatureSanitization--) | Ottiene o imposta il flag per gestire la sanificazione dei campi firma. |
| [getEngineDoc](#getEngineDoc--) | Istanza di **IPdfDocument** usata per accedere alla struttura interna del documento. |
| [getFileName](#getFileName--) | Nome del file PDF che ha generato questo documento |
| [getFileSizeLimitToMemoryLoading](#getFileSizeLimitToMemoryLoading--) | Ottieni e imposta il limite di dimensione del file per caricare un intero file in memoria. |
| [getForm](#getForm--) | Ottiene il modulo Acro Form del documento. |
| [getId](#getId--) | Ottiene l'ID. |
| [getIgnoreCorruptedObjects](#getIgnoreCorruptedObjects--) | Ottiene o imposta il flag per ignorare gli errori nei file sorgente. |
| [getInfo](#getInfo--) | Ottiene le informazioni del documento. |
| [getJavaScript](#getJavaScript--) | Raccolta di JavaScript a livello di documento. |
| [getLogicalStructure](#getLogicalStructure--) | Ottiene la struttura logica del documento. |
| [getMetadata](#getMetadata--) | Metadati del documento. |
| [getMetadataStream](#getMetadataStream--) | Solo per uso interno! |
| [getNamedDestinations](#getNamedDestinations--) | Raccolta di Destinazioni Nominative nel documento. |
| [getNonFullScreenPageMode](#getNonFullScreenPageMode--) | Ottiene la modalità pagina, specificando come visualizzare il documento uscendo dalla modalità a schermo intero. |
| [getObjectById](#getObjectById-java.lang.String-) | Ottiene un oggetto con ID specificato nel documento. |
| [getOpenAction](#getOpenAction--) | Ottiene l'azione eseguita all'apertura del documento. |
| [getOptimizeSize](#getOptimizeSize--) | Ottiene il flag di ottimizzazione. |
| [getOutlines](#getOutlines--) | Ottiene la struttura del documento. |
| [getOutputIntents](#getOutputIntents--) | Ottiene la raccolta di Intenti di Output nel documento. |
| [getPageInfo](#getPageInfo--) | Ottiene le informazioni della pagina (solo per il generatore, non compilate durante la lettura del documento) |
| [getPageLabels](#getPageLabels--) | Ottiene le etichette delle pagine nel documento. |
| [getPageLayout](#getPageLayout--) | Ottiene il layout della pagina da utilizzare quando il documento viene aperto. |
| [getPageMode](#getPageMode--) | Ottiene la modalità pagina, specificando come il documento dovrebbe essere visualizzato all'apertura. |
| [getPages](#getPages--) | Ottiene la raccolta delle pagine del documento. |
| [getPdfFormat](#getPdfFormat--) | Ottiene il formato PDF. |
| [getPermissions](#getPermissions--) | Ottiene i permessi del documento. |
| [getPrintScaling](#getPrintScaling--) | Ottiene l'opzione di gestione della scala di stampa da utilizzare quando si stampa il file dalla finestra di stampa. |
| [getTaggedContent](#getTaggedContent--) | Ottiene l'accesso al contenuto TaggedPdf. |
| [getVersion](#getVersion--) | Ottiene una versione di Pdf dall'intestazione del file Pdf. |
| [getXmpMetadata](#getXmpMetadata-java.io.OutputStream-) | Ottieni i metadati XMP dal documento. |
| [hasIncrementalUpdate](#hasIncrementalUpdate--) | Verifica se il PDF corrente è stato salvato con aggiornamenti incrementali. |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.io.InputStream-) | Importa le annotazioni dallo stream al documento. |
| [importAnnotationsFromXfdf](#importAnnotationsFromXfdf-java.lang.String-) | Importa le annotazioni dal file XFDF al documento. |
| [isAbsentFontTryToSubstitute](#isAbsentFontTryToSubstitute--) | Flag che indica la sostituzione del font mancante. |
| [isCenterWindow](#isCenterWindow--) | Ottiene il flag che specifica se la posizione della finestra del documento sarà centrata sullo schermo. |
| [isDisableFontLicenseVerifications](#isDisableFontLicenseVerifications--) | Molte operazioni con il font non possono essere eseguite se queste operazioni sono vietate dalla licenza di questo font. |
| [isDisplayDocTitle](#isDisplayDocTitle--) | Ottiene il flag che specifica se la barra del titolo della finestra del documento deve visualizzare il titolo del documento. |
| [isEnableNotificationLogging](#isEnableNotificationLogging--) | Ottiene o imposta un valore che indica se abilitare la registrazione delle notifiche. |
| [isEnableObjectUnload](#isEnableObjectUnload--) | Ottiene o imposta il flag che consente al documento di essere parzialmente scaricato dalla memoria. |
| [isEncrypted](#isEncrypted--) | Ottiene lo stato di crittografia del documento. |
| [isFitWindow](#isFitWindow--) | Ottiene il flag che specifica se la finestra del documento deve essere ridimensionata per adattarsi alla prima pagina visualizzata. |
| [isHandleSignatureChange](#isHandleSignatureChange--) | Lancia un'eccezione se il documento viene salvato con modifiche e contiene una firma |
| [isHideMenubar](#isHideMenubar--) | Ottiene il flag che specifica se la barra dei menu deve essere nascosta quando il documento è attivo. |
| [isHideToolBar](#isHideToolBar--) | Ottiene il flag che specifica se la barra degli strumenti deve essere nascosta quando il documento è attivo. |
| [isHideWindowUI](#isHideWindowUI--) | Ottiene o imposta il flag che specifica se gli elementi dell'interfaccia utente devono essere nascosti quando il documento è attivo. |
| [isLicensed](#isLicensed--) | Ottiene lo stato di licenza del sistema. |
| [isLinearized](#isLinearized--) | Ottiene o imposta un valore che indica se il documento è linearizzato. |
| [isManualDisposeEnabled](#isManualDisposeEnabled--) | Per impostazione predefinita il metodo save chiude i flussi interni e rilascia le risorse di memoria. |
| [isPdfaCompliant](#isPdfaCompliant--) | Restituisce se il documento è conforme a pdfa. |
| [isPdfUaCompliant](#isPdfUaCompliant--) | Ottiene se il documento è conforme a PDF/UA. |
| [isPickTrayByPdfSize](#isPickTrayByPdfSize--) | Ottiene un flag che specifica se la dimensione della pagina PDF deve essere usata per selezionare il vassoio di ingresso della carta. |
| [isRepairNeeded](#isRepairNeeded-com.aspose.pdf.Document.RepairOptions:A-) | Verifica se il documento richiede la chiamata al metodo Repair. |
| [isSkippedPdfaCompliantValidationBeforeSave](#isSkippedPdfaCompliantValidationBeforeSave--) | Per impostazione predefinita, il processo di convalida pdfa è necessario per aggiornare o rimuovere i dati conformi a pdfa se alcune regole sono state violate. |
| [isXrefGapsAllowed](#isXrefGapsAllowed--) | Ottiene o imposta se il documento è conforme a PDF/A. |
| [loadFrom](#loadFrom-java.lang.String-com.aspose.pdf.LoadOptions-) | Carica un file, convertendolo in PDF. |
| [merge](#merge-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-) | Unisce i documenti. |
| [merge](#merge-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-) | Unisce i documenti. |
| [merge](#merge-com.aspose.pdf.Document...-) | Unisce i documenti. |
| [merge](#merge-java.lang.String...-) | Unisce i file pdf. |
| [mergeDocuments](#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-) | Unisce i documenti. |
| [mergeDocuments](#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-) | Unisce i documenti. |
| [mergeDocuments](#mergeDocuments-com.aspose.pdf.Document...-) | Unisce i documenti. |
| [mergeDocuments](#mergeDocuments-java.lang.String...-) | Unisce i file pdf. |
| [optimize](#optimize--) | Linearizzare il documento al fine di - aprire la prima pagina il più rapidamente possibile; - visualizzare la pagina successiva o seguirne il collegamento il più rapidamente possibile; - visualizzare la pagina in modo incrementale man mano che arriva, quando i dati per una pagina vengono trasmessi su un canale lento (visualizzare prima i dati più utili); - consentire l'interazione dell'utente, come seguire un collegamento, anche prima che l'intera pagina sia stata ricevuta e visualizzata. |
| [optimizeResources](#optimizeResources--) | Ottimizza le risorse nel documento: 1. |
| [optimizeResources](#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-) | Ottimizza le risorse nel documento secondo la strategia di ottimizzazione definita. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree--) | Organizza i nodi dell'albero delle pagine in un documento in un albero bilanciato. |
| [pageNodesToBalancedTree](#pageNodesToBalancedTree-byte-) | Organizza i nodi dell'albero delle pagine in un documento in un albero bilanciato. |
| [preSave](#preSave-com.aspose.pdf.PageCollection-com.aspose.pdf.SaveOptions-) | Metodo interno |
| [processParagraphs](#processParagraphs--) | Memorizza il documento nel generatore. |
| [removeMetadata](#removeMetadata--) | Rimuove i metadati dal documento. |
| [removePdfaCompliance](#removePdfaCompliance--) | Rimuove la conformità PDF/A dal documento |
| [removePdfUaCompliance](#removePdfUaCompliance--) | Rimuove la conformità PDF/UA dal documento |
| [repair](#repair--) | Ripara il documento danneggiato. |
| [repair](#repair-com.aspose.pdf.Document.RepairOptions-) | Ripara il documento danneggiato. |
| [resumeUpdate](#resumeUpdate--) | riprende l'aggiornamento del documento |
| [save](#save--) | Salva il documento in modo incrementale (ad es. |
| [save](#save-javax.servlet.http.HttpServletResponse-java.lang.String-com.aspose.pdf.ContentDisposition-com.aspose.pdf.SaveOptions-) | Salva il documento in un flusso di risposta con le opzioni di salvataggio. |
| [save](#save-java.io.OutputStream-) | Memorizza il documento in un flusso. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-) | Salva il documento con un nuovo nome insieme a un formato file. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-) | Salva il documento con un nuovo nome impostando le sue opzioni di salvataggio. |
| [save](#save-com.aspose.pdf.SaveOptions-) | Salva il documento con le opzioni di salvataggio. |
| [save](#save-com.aspose.ms.System.IO.Stream-) | Solo per uso interno |
| [save](#save-java.lang.String-) | Salva il documento nel file specificato. |
| [save](#save-java.lang.String-com.aspose.pdf.SaveFormat-) | Salva il documento con un nuovo nome insieme a un formato file. |
| [save](#save-java.lang.String-com.aspose.pdf.SaveOptions-) | Salva il documento con un nuovo nome impostando le sue opzioni di salvataggio. |
| [saveIncrementally](#saveIncrementally-java.io.OutputStream-) | Salva in modo incrementale il documento PDF nello stream specificato. |
| [saveIncrementally](#saveIncrementally-com.aspose.ms.System.IO.Stream-) | Salva in modo incrementale il documento PDF nello stream specificato. |
| [saveIncrementally](#saveIncrementally-java.lang.String-) | Salva in modo incrementale il documento PDF nello stream specificato. |
| [saveXml](#saveXml-java.lang.String-) | Salva il documento in XML. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.io.OutputStream-) | Invia le pagine specifiche del documento al dispositivo del documento per l'elaborazione. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-int-int-java.lang.String-) | Invia l'intero documento al dispositivo del documento per l'elaborazione. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.io.OutputStream-) | Invia l'intero documento al dispositivo del documento per l'elaborazione. |
| [sendTo](#sendTo-com.aspose.pdf.devices.DocumentDevice-java.lang.String-) | Invia l'intero documento al dispositivo del documento per l'elaborazione. |
| [setAbsentFontHandler](#setAbsentFontHandler-com.aspose.pdf.ADocument.AbsentFontHandler-) | Notifica dei font mancanti durante l'elaborazione dei documenti. |
| [setAbsentFontTryToSubstitute](#setAbsentFontTryToSubstitute-boolean-) | Impostazione del flag per sostituire il font mancante. |
| [setAllowReusePageContent](#setAllowReusePageContent-boolean-) | Consente di unire i contenuti delle pagine per ottimizzare le dimensioni del documento. |
| [setBackground](#setBackground-java.awt.Color-) | Imposta il colore di sfondo del documento. |
| [setCenterWindow](#setCenterWindow-boolean-) | Imposta il flag che specifica se la posizione della finestra del documento sarà centrata sullo schermo. |
| [setCollection](#setCollection-com.aspose.pdf.Collection-) | Imposta la raccolta del documento. |
| [setConvertMetadataAndCatalogOnly](#setConvertMetadataAndCatalogOnly-boolean-) | Ottiene il parametro di conversione per il convertitore pdf/ua (Converti solo i Metadati e il Catalogo del Documento se impostato su true). |
| [setDefaultFileSizeLimitToMemoryLoading](#setDefaultFileSizeLimitToMemoryLoading--) | Imposta il limite di dimensione del file per caricare un intero file in memoria al valore predefinito pari a 210 Mb. |
| [setDirection](#setDirection-com.aspose.pdf.Direction-) | Imposta l'ordine di lettura del testo: L2R (da sinistra a destra) o R2L (da destra a sinistra). |
| [setDisableFontLicenseVerifications](#setDisableFontLicenseVerifications-boolean-) | Molte operazioni con il font non possono essere eseguite se queste operazioni sono vietate dalla licenza di questo font. |
| [setDisplayDocTitle](#setDisplayDocTitle-boolean-) | Imposta il flag che specifica se la barra del titolo della finestra del documento deve visualizzare il titolo del documento. |
| [setDuplex](#setDuplex-int-) | Ottiene o imposta l'opzione di gestione della stampa duplex da utilizzare quando si stampa il file dalla finestra di stampa. |
| [setEmbedStandardFonts](#setEmbedStandardFonts-boolean-) | Proprietà che dichiara che il documento deve incorporare tutti i font Type1 standard il cui flag IsEmbedded è impostato su true. |
| [setEnableNotificationLogging](#setEnableNotificationLogging-boolean-) | Ottiene o imposta un valore che indica se abilitare la registrazione delle notifiche. |
| [setEnableObjectUnload](#setEnableObjectUnload-boolean-) | Ottiene o imposta il flag che consente al documento di essere parzialmente scaricato dalla memoria. |
| [setEnableSignatureSanitization](#setEnableSignatureSanitization-boolean-) | Ottiene o imposta il flag per gestire la sanificazione dei campi firma. |
| [setFileSizeLimitToMemoryLoading](#setFileSizeLimitToMemoryLoading-int-) | Ottieni e imposta il limite di dimensione del file per caricare un intero file in memoria. |
| [setFitWindow](#setFitWindow-boolean-) | Imposta il flag che specifica se la finestra del documento deve essere ridimensionata per adattarsi alla prima pagina visualizzata. |
| [setHandleSignatureChange](#setHandleSignatureChange-boolean-) | Lancia un'eccezione se il documento viene salvato con modifiche e contiene una firma |
| [setHideMenubar](#setHideMenubar-boolean-) | Imposta il flag che specifica se la barra dei menu deve essere nascosta quando il documento è attivo. |
| [setHideToolBar](#setHideToolBar-boolean-) | Imposta il flag che specifica se la barra degli strumenti deve essere nascosta quando il documento è attivo. |
| [setHideWindowUI](#setHideWindowUI-boolean-) | Imposta il flag che specifica se gli elementi dell'interfaccia utente devono essere nascosti quando il documento è attivo. |
| [setIgnoreCorruptedObjects](#setIgnoreCorruptedObjects-boolean-) | Ottiene o imposta il flag per ignorare gli errori nei file sorgente. |
| [setLinearized](#setLinearized-boolean-) | Imposta un valore che indica se il documento è linearizzato. |
| [setManualDisposeEnabled](#setManualDisposeEnabled-boolean-) | Per impostazione predefinita il metodo save chiude i flussi interni e rilascia le risorse di memoria. |
| [setNonFullScreenPageMode](#setNonFullScreenPageMode-com.aspose.pdf.PageMode-) | Imposta la modalità pagina, specificando come visualizzare il documento uscendo dalla modalità a schermo intero. |
| [setOpenAction](#setOpenAction-com.aspose.pdf.IAppointment-) | Imposta l'azione eseguita all'apertura del documento. |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Imposta il flag di ottimizzazione. |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Imposta le informazioni della pagina (solo per il generatore, non compilate durante la lettura del documento). |
| [setPageLayout](#setPageLayout-com.aspose.pdf.PageLayout-) | Imposta il layout della pagina da utilizzare quando il documento viene aperto. |
| [setPageMode](#setPageMode-com.aspose.pdf.PageMode-) | Imposta la modalità pagina, specificando come il documento deve essere visualizzato quando aperto. |
| [setPickTrayByPdfSize](#setPickTrayByPdfSize-boolean-) | Imposta un flag che specifica se la dimensione della pagina PDF deve essere usata per selezionare il vassoio di ingresso della carta. |
| [setPrintScaling](#setPrintScaling-int-) | Imposta l'opzione di gestione della scala di stampa da utilizzare quando si stampa il file dalla finestra di dialogo di stampa. |
| [setSkipPdfaCompliantValidationBeforeSave](#setSkipPdfaCompliantValidationBeforeSave-boolean-) | Per impostazione predefinita, il processo di convalida pdfa è necessario per aggiornare o rimuovere pdfa se alcune regole sono state violate. |
| [setTitle](#setTitle-java.lang.String-) | Imposta il titolo per il documento PDF. |
| [setXmpMetadata](#setXmpMetadata-java.io.InputStream-) | Imposta i metadati XMP del documento. |
| [setXrefGapsAllowed](#setXrefGapsAllowed-boolean-) | Ottiene o imposta se il documento è conforme a PDF/A. |
| [suppressUpdate](#suppressUpdate--) | Sopprime l'aggiornamento dei contenuti per tutte le pagine. I contenuti non vengono aggiornati fino a quando non viene chiamato ResumeUpdate. |
| [updatePages](#updatePages--) | updatePages |
| [validate](#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-) | Convalida il documento nel file specificato. |
| [validate](#validate-com.aspose.pdf.PdfFormatConversionOptions-) | Convalida il documento nel file specificato. |
| [validate](#validate-java.lang.String-com.aspose.pdf.PdfFormat-) | Convalida il documento nel file specificato. |

### DefaultNodesNumInSubtrees {#DefaultNodesNumInSubtrees}
```
public static final byte DefaultNodesNumInSubtrees
```



### FontSubstitution {#FontSubstitution}
```
public final PdfEvent <com.aspose.pdf.ADocument.FontSubstitutionHandler> FontSubstitution
```

Si verifica quando il font sostituisce un altro font nel documento.

### DocumentWeb {#DocumentWeb--}
```
public DocumentWeb()
```

Inizializza un DocumentWeb vuoto.

### DocumentWeb {#DocumentWeb-java.io.InputStream-}
Inizializza un DocumentWeb vuoto.

### DocumentWeb {#DocumentWeb-java.io.InputStream-com.aspose.pdf.LoadOptions-}
Inizializza un DocumentWeb vuoto.

### DocumentWeb {#DocumentWeb-java.io.InputStream-java.lang.String-}
Inizializza un DocumentWeb vuoto.

### DocumentWeb {#DocumentWeb-java.lang.String-}
Inizializza un DocumentWeb vuoto.

### DocumentWeb {#DocumentWeb-java.lang.String-com.aspose.pdf.LoadOptions-}
Inizializza un DocumentWeb vuoto.

### DocumentWeb {#DocumentWeb-java.lang.String-java.lang.String-}
Inizializza un DocumentWeb vuoto.

### afterImport {#afterImport--}
```
public void afterImport()
```

Enumera tutte le annotazioni registrate e chiama AfterImport per ciascuna di esse.

### bindXml {#bindXml-java.io.InputStream-}
Associa xml al documento

### bindXml {#bindXml-java.io.InputStream-java.io.InputStream-}
Associa xml/xsl al documento

### bindXml {#bindXml-java.io.InputStream-java.io.InputStream-com.aspose.ms.System.Xml.XmlReaderSettings-}
Associa xml/xsl al documento

### bindXml {#bindXml-java.lang.String-}
Associa xml al documento

### bindXml {#bindXml-java.lang.String-java.lang.String-}
Associa xml/xsl al documento

### changePasswords {#changePasswords-java.lang.String-java.lang.String-java.lang.String-}
Modifica le password del documento.

### check {#check-boolean-}
```
public boolean check(boolean doRepair)
```

Convalida il documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| doRepair |  | Se vero, i problemi trovati saranno riparati. |

**Returns:**
valore booleano True - se il documento è stato riparato; altrimenti, false.

### close {#close--}
```
public void close()
```

Chiude tutte le risorse utilizzate da questo documento.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-}
Converti il documento in un documento ricercabile.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-}
Converti il documento e salva gli errori nel file specificato.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-}
Converti il documento e salva gli errori nel file specificato.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrBase-boolean-boolean-boolean-}
Converti il documento e salva gli errori nel file specificato.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocr-boolean-boolean-boolean-boolean-}
Converti il documento e salva gli errori nel file specificato.

### convert {#convert-com.aspose.pdf.Document.CallBackGetHocrWithPage-boolean-boolean-boolean-boolean-}
Converti il documento e salva gli errori nel file specificato.

### convert {#convert-com.aspose.pdf.Fixup-java.io.OutputStream-}
Converti il documento applicando il Fixup.

### convert {#convert-com.aspose.pdf.Fixup-java.io.OutputStream-boolean-java.lang.Object:A-}
Converti il documento applicando il Fixup.

### convert {#convert-com.aspose.pdf.Fixup-java.lang.String-}
Converti il documento applicando il Fixup.

### convert {#convert-com.aspose.pdf.Fixup-java.lang.String-boolean-java.lang.Object:A-}
Converti il documento applicando il Fixup.

### convert {#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
Converte lo stream nel formato di origine in uno stream nel formato di destinazione.

### convert {#convert-java.io.InputStream-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-}
Converte lo stream nel formato di origine in un file di destinazione nel formato di destinazione.

### convert {#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Converti il documento e salva gli errori nello stream specificato.

### convert {#convert-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
Converti il documento e salva gli errori nel file specificato.

### convert {#convert-com.aspose.pdf.PdfFormatConversionOptions-}
Converti il documento usando le opzioni di conversione specificate

### convert {#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
Converte il file di origine nel formato di origine in uno stream nel formato di destinazione.

### convert {#convert-java.lang.String-com.aspose.pdf.LoadOptions-java.lang.String-com.aspose.pdf.SaveOptions-}
Converte il file di origine nel formato di origine in un file di destinazione nel formato di destinazione.

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Converti il documento e salva gli errori nel file specificato.

### convert {#convert-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
Converti il documento e salva gli errori nel file specificato.

### convertInternal {#convertInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Converti il documento e salva gli errori nello stream specificato.

### convertPageToPNGMemoryStream {#convertPageToPNGMemoryStream-com.aspose.pdf.Page-}
Converti la pagina in PNG per lo stream di immagine DSR, OMR, OCR.

### convertWithFlatten {#convertWithFlatten-com.aspose.pdf.Document.CallBackGetHocrBase-}
Converti il documento in un documento ricercabile e ignora gli errori di hochr che non possono essere convertiti.

### convertWithSkippingErrors {#convertWithSkippingErrors-com.aspose.pdf.Document.CallBackGetHocrBase-}
Converti il documento in un documento ricercabile e ignora gli errori di hochr che non possono essere convertiti.

### decrypt {#decrypt--}
```
public void decrypt()
```

Decripta il documento.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Obsoleto.

### encrypt {#encrypt-int-com.aspose.pdf.CryptoAlgorithm-com.aspose.ms.System.Collections.Generic.IGenericList-}
Cripta il documento.

### encrypt {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.CryptoAlgorithm-boolean-}
Cripta il documento.

### encrypt {#encrypt-java.lang.String-java.lang.String-com.aspose.pdf.facades.DocumentPrivilege-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Cripta il documento.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-}
Cripta il documento.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.CryptoAlgorithm-boolean-}
Cripta il documento.

### encrypt {#encrypt-java.lang.String-java.lang.String-int-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
Cripta il documento.

### exportAnnotationsToXfdf {#exportAnnotationsToXfdf-java.io.OutputStream-}
Esporta tutte le annotazioni del documento nello stream.

### exportAnnotationsToXfdf {#exportAnnotationsToXfdf-java.lang.String-}
Esporta tutte le annotazioni del documento in un file XFDF

### flatten {#flatten--}
```
public void flatten()
```

Rimuove tutti i campi (e le annotazioni) dal documento e ne inserisce i valori al loro posto.

### flatten {#flatten-com.aspose.pdf.Form.FlattenSettings-}
Rimuove tutti i campi dal documento e ne inserisce i valori al loro posto.

### flattenTransparency {#flattenTransparency--}
```
public void flattenTransparency()
```

Sostituisce il contenuto trasparente con grafica raster e vettoriale non trasparente.

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

Cancella la memoria

### getAbsentFontHandler {#getAbsentFontHandler--}
```
public com.aspose.pdf.ADocument.AbsentFontHandler getAbsentFontHandler()
```

Notifica dei font mancanti durante l'elaborazione dei documenti.

**Returns:**
ADocument.AbsentFontHandler instance

### getActions {#getActions--}
```
public DocumentActionCollection getActions()
```

Ottiene le azioni del documento.

**Returns:**
DocumentActionCollection oggetto

### getAllowReusePageContent {#getAllowReusePageContent--}
```
public boolean getAllowReusePageContent()
```

Consente di unire i contenuti delle pagine per ottimizzare le dimensioni del documento.

**Returns:**
valore booleano

### getBackground {#getBackground--}
```
public Color getBackground()
```

Ottiene il colore di sfondo del documento.

**Returns:**
java.awt.Color oggetto

### getCatalogValue {#getCatalogValue-java.lang.String-}
Restituisce il valore dell'elemento dal dizionario del catalogo.

### getCollection {#getCollection--}
```
public Collection getCollection()
```

Ottiene la collezione del documento.

**Returns:**
Collection oggetto

### getCryptoAlgorithm {#getCryptoAlgorithm--}
```
public CryptoAlgorithm getCryptoAlgorithm()
```

Ottiene le impostazioni di sicurezza se il documento è crittografato.

**Returns:**
CryptoAlgorithm elemento oppure null

### getCustomSecurityHandler {#getCustomSecurityHandler--}
```
public com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler getCustomSecurityHandler()
```

Ottiene un gestore di sicurezza personalizzato.

**Returns:**
ICustomSecurityHandler istanza

### getDefaultCopier {#getDefaultCopier--}
```
public Copier getDefaultCopier()
```

Restituisce il copiatore usato per copiare le pagine in questo documento.

**Returns:**
Copier oggetto

### getDestinations {#getDestinations--}
```
@Deprecated public DestinationCollection getDestinations()
```

Obsoleto.

**Returns:**
DestinationCollection oggetto

### getDirection {#getDirection--}
```
public Direction getDirection()
```

Ottiene l'ordine di lettura del testo: L2R (da sinistra a destra) o R2L (da destra a sinistra).

**Returns:**
Direction elemento

### getDuplex {#getDuplex--}
```
public int getDuplex()
```

Ottiene o imposta l'opzione di gestione della stampa duplex da utilizzare quando si stampa il file dalla finestra di stampa.

**Returns:**
PrintDuplex elemento

### getEmbeddedFiles {#getEmbeddedFiles--}
```
public EmbeddedFileCollection getEmbeddedFiles()
```

Ottiene la collezione dei file incorporati nel documento.

**Returns:**
EmbeddedFileCollection oggetto

### getEmbedStandardFonts {#getEmbedStandardFonts--}
```
public boolean getEmbedStandardFonts()
```

Proprietà che dichiara che il documento deve incorporare tutti i font Type1 standard il cui flag IsEmbedded è impostato su true.

**Returns:**
valore booleano

### getEnableSignatureSanitization {#getEnableSignatureSanitization--}
```
public final boolean getEnableSignatureSanitization()
```

Ottiene o imposta il flag per gestire la sanificazione dei campi firma.

**Returns:**
valore booleano

### getEngineDoc {#getEngineDoc--}
```
public com.aspose.pdf.engine.IPdfDocument getEngineDoc()
```

Istanza di **IPdfDocument** usata per accedere alla struttura interna del documento.

**Returns:**
IPdfDocument oggetto

### getFileName {#getFileName--}
```
public String getFileName()
```

Nome del file PDF che ha generato questo documento

**Returns:**
valore String

### getFileSizeLimitToMemoryLoading {#getFileSizeLimitToMemoryLoading--}
```
public static int getFileSizeLimitToMemoryLoading()
```

Ottieni e imposta il limite di dimensione del file per caricare un intero file in memoria.

**Returns:**
valore int

### getForm {#getForm--}
```
public Form getForm()
```

Ottiene il modulo Acro Form del documento.

**Returns:**
Form oggetto

### getId {#getId--}
```
public Id getId()
```

Ottiene l'ID.

**Returns:**
Id oggetto

### getIgnoreCorruptedObjects {#getIgnoreCorruptedObjects--}
```
public boolean getIgnoreCorruptedObjects()
```

Ottiene o imposta il flag per ignorare gli errori nei file sorgente.

**Returns:**
valori booleani

### getInfo {#getInfo--}
```
public DocumentInfo getInfo()
```

Ottiene le informazioni del documento.

**Returns:**
DocumentInfo oggetto

### getJavaScript {#getJavaScript--}
```
public JavaScriptCollection getJavaScript()
```

Raccolta di JavaScript a livello di documento.

**Returns:**
Oggetto JavaScriptCollection

### getLogicalStructure {#getLogicalStructure--}
```
public RootElement getLogicalStructure()
```

Ottiene la struttura logica del documento.

**Returns:**
RootElement oggetto

### getMetadata {#getMetadata--}
```
public Metadata getMetadata()
```

Metadati del documento.

**Returns:**
Metadata oggetto

### getMetadataStream {#getMetadataStream--}
```
public com.aspose.pdf.engine.data.types.IPdfStreamAccessor getMetadataStream()
```

Solo per uso interno!

**Returns:**
IPdfStreamAccessor oggetto

### getNamedDestinations {#getNamedDestinations--}
```
public NamedDestinationCollection getNamedDestinations()
```

Raccolta di Destinazioni Nominative nel documento.

**Returns:**
NamedDestinationCollection istanza

### getNonFullScreenPageMode {#getNonFullScreenPageMode--}
```
public PageMode getNonFullScreenPageMode()
```

Ottiene la modalità pagina, specificando come visualizzare il documento uscendo dalla modalità a schermo intero.

**Returns:**
PageMode elemento

### getObjectById {#getObjectById-java.lang.String-}
Ottiene un oggetto con ID specificato nel documento.

### getOpenAction {#getOpenAction--}
```
public IAppointment getOpenAction()
```

Ottiene l'azione eseguita all'apertura del documento.

**Returns:**
IAppointment oggetto

### getOptimizeSize {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```

Ottiene il flag di ottimizzazione.

**Returns:**
valore booleano

### getOutlines {#getOutlines--}
```
public OutlineCollection getOutlines()
```

Ottiene la struttura del documento.

**Returns:**
Oggetto OutlineCollection

### getOutputIntents {#getOutputIntents--}
```
public final OutputIntents getOutputIntents()
```

Ottiene la raccolta di Intenti di Output nel documento.

**Returns:**
Istanza OutputIntents

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

Ottiene le informazioni della pagina (solo per il generatore, non compilate durante la lettura del documento)

**Returns:**
Le informazioni della pagina.

### getPageLabels {#getPageLabels--}
```
public PageLabelCollection getPageLabels()
```

Ottiene le etichette delle pagine nel documento.

**Returns:**
Oggetto PageLabelCollection

### getPageLayout {#getPageLayout--}
```
public PageLayout getPageLayout()
```

Ottiene il layout della pagina da utilizzare quando il documento viene aperto.

**Returns:**
Elemento PageLayout

### getPageMode {#getPageMode--}
```
public PageMode getPageMode()
```

Ottiene la modalità pagina, specificando come il documento dovrebbe essere visualizzato all'apertura.

**Returns:**
PageMode elemento

### getPages {#getPages--}
```
public PageCollection getPages()
```

Ottiene la raccolta delle pagine del documento.

**Returns:**
valore booleano

### getPdfFormat {#getPdfFormat--}
```
public PdfFormat getPdfFormat()
```

Ottiene il formato PDF.

**Returns:**
PdfFormat

### getPermissions {#getPermissions--}
```
public int getPermissions()
```

Ottiene i permessi del documento.

**Returns:**
valore int

### getPrintScaling {#getPrintScaling--}
```
public int getPrintScaling()
```

Ottiene l'opzione di gestione della scala di stampa da utilizzare quando si stampa il file dalla finestra di stampa.

**Returns:**
Elemento PrintScaling

### getTaggedContent {#getTaggedContent--}
```
public ITaggedContent getTaggedContent()
```

Ottiene l'accesso al contenuto TaggedPdf.

**Returns:**
Istanza ITaggedContent

### getVersion {#getVersion--}
```
public String getVersion()
```

Ottiene una versione di Pdf dall'intestazione del file Pdf.

**Returns:**
Oggetto stringa

### getXmpMetadata {#getXmpMetadata-java.io.OutputStream-}
Ottieni i metadati XMP dal documento.

### hasIncrementalUpdate {#hasIncrementalUpdate--}
```
public final boolean hasIncrementalUpdate()
```

Verifica se il PDF corrente è stato salvato con aggiornamenti incrementali.

**Returns:**
true se il documento PDF ha aggiornamenti incrementali; altrimenti, false.

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.io.InputStream-}
Importa le annotazioni dallo stream al documento.

### importAnnotationsFromXfdf {#importAnnotationsFromXfdf-java.lang.String-}
Importa le annotazioni dal file XFDF al documento.

### isAbsentFontTryToSubstitute {#isAbsentFontTryToSubstitute--}
```
public boolean isAbsentFontTryToSubstitute()
```

Flag che indica la sostituzione del font mancante.

**Returns:**
valore booleano

### isCenterWindow {#isCenterWindow--}
```
public boolean isCenterWindow()
```

Ottiene il flag che specifica se la posizione della finestra del documento sarà centrata sullo schermo.

**Returns:**
valore booleano

### isDisableFontLicenseVerifications {#isDisableFontLicenseVerifications--}
```
public final boolean isDisableFontLicenseVerifications()
```

Molte operazioni con il font non possono essere eseguite se queste operazioni sono vietate dalla licenza di questo font.

**Returns:**
Valore booleano, per impostazione predefinita false.

### isDisplayDocTitle {#isDisplayDocTitle--}
```
public boolean isDisplayDocTitle()
```

Ottiene il flag che specifica se la barra del titolo della finestra del documento deve visualizzare il titolo del documento.

**Returns:**
valore booleano

### isEnableNotificationLogging {#isEnableNotificationLogging--}
```
public final boolean isEnableNotificationLogging()
```

Ottiene o imposta un valore che indica se abilitare la registrazione delle notifiche.

**Returns:**
valore booleano

### isEnableObjectUnload {#isEnableObjectUnload--}
```
public boolean isEnableObjectUnload()
```

Ottiene o imposta il flag che consente al documento di essere parzialmente scaricato dalla memoria.

**Returns:**
valore booleano

### isEncrypted {#isEncrypted--}
```
public boolean isEncrypted()
```

Ottiene lo stato di crittografia del documento.

**Returns:**
valore booleano

### isFitWindow {#isFitWindow--}
```
public boolean isFitWindow()
```

Ottiene il flag che specifica se la finestra del documento deve essere ridimensionata per adattarsi alla prima pagina visualizzata.

**Returns:**
valore booleano

### isHandleSignatureChange {#isHandleSignatureChange--}
```
public final boolean isHandleSignatureChange()
```

Lancia un'eccezione se il documento viene salvato con modifiche e contiene una firma

**Returns:**
valore booleano

### isHideMenubar {#isHideMenubar--}
```
public boolean isHideMenubar()
```

Ottiene il flag che specifica se la barra dei menu deve essere nascosta quando il documento è attivo.

**Returns:**
valore booleano

### isHideToolBar {#isHideToolBar--}
```
public boolean isHideToolBar()
```

Ottiene il flag che specifica se la barra degli strumenti deve essere nascosta quando il documento è attivo.

**Returns:**
valore booleano

### isHideWindowUI {#isHideWindowUI--}
```
public boolean isHideWindowUI()
```

Ottiene o imposta il flag che specifica se gli elementi dell'interfaccia utente devono essere nascosti quando il documento è attivo.

**Returns:**
valore booleano

### isLicensed {#isLicensed--}
```
public static boolean isLicensed()
```

Ottiene lo stato di licenza del sistema.

**Returns:**
valore booleano

### isLinearized {#isLinearized--}
```
public boolean isLinearized()
```

Ottiene o imposta un valore che indica se il documento è linearizzato.

**Returns:**
valore booleano

### isManualDisposeEnabled {#isManualDisposeEnabled--}
```
public boolean isManualDisposeEnabled()
```

Per impostazione predefinita il metodo save chiude i flussi interni e rilascia le risorse di memoria.

**Returns:**
Valore booleano. (Valore predefinito == false)

### isPdfaCompliant {#isPdfaCompliant--}
```
public boolean isPdfaCompliant()
```

Restituisce se il documento è conforme a pdfa.

**Returns:**
valore booleano

### isPdfUaCompliant {#isPdfUaCompliant--}
```
public boolean isPdfUaCompliant()
```

Ottiene se il documento è conforme a PDF/UA.

**Returns:**
valore booleano

### isPickTrayByPdfSize {#isPickTrayByPdfSize--}
```
public final boolean isPickTrayByPdfSize()
```

Ottiene un flag che specifica se la dimensione della pagina PDF deve essere usata per selezionare il vassoio di ingresso della carta.

**Returns:**
valore booleano

### isRepairNeeded {#isRepairNeeded-com.aspose.pdf.Document.RepairOptions:A-}
Verifica se il documento richiede la chiamata al metodo Repair.

### isSkippedPdfaCompliantValidationBeforeSave {#isSkippedPdfaCompliantValidationBeforeSave--}
```
public boolean isSkippedPdfaCompliantValidationBeforeSave()
```

Per impostazione predefinita, il processo di convalida pdfa è necessario per aggiornare o rimuovere i dati conformi a pdfa se alcune regole sono state violate.

**Returns:**
valore booleano

### isXrefGapsAllowed {#isXrefGapsAllowed--}
```
public boolean isXrefGapsAllowed()
```

Ottiene o imposta se il documento è conforme a PDF/A.

**Returns:**
valore booleano

### loadFrom {#loadFrom-java.lang.String-com.aspose.pdf.LoadOptions-}
Carica un file, convertendolo in PDF.

### merge {#merge-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-}
Unisce i documenti.

### merge {#merge-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-}
Unisce i documenti.

### merge {#merge-com.aspose.pdf.Document...-}
Unisce i documenti.

### merge {#merge-java.lang.String...-}
Unisce i file pdf.

### mergeDocuments {#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-com.aspose.pdf.Document...-}
Unisce i documenti.

### mergeDocuments {#mergeDocuments-com.aspose.pdf.ADocument.MergeOptions-java.lang.String...-}
Unisce i documenti.

### mergeDocuments {#mergeDocuments-com.aspose.pdf.Document...-}
Unisce i documenti.

### mergeDocuments {#mergeDocuments-java.lang.String...-}
Unisce i file pdf.

### optimize {#optimize--}
```
public void optimize()
```

Linearizzare il documento al fine di - aprire la prima pagina il più rapidamente possibile; - visualizzare la pagina successiva o seguirne il collegamento il più rapidamente possibile; - visualizzare la pagina in modo incrementale man mano che arriva, quando i dati per una pagina vengono trasmessi su un canale lento (visualizzare prima i dati più utili); - consentire l'interazione dell'utente, come seguire un collegamento, anche prima che l'intera pagina sia stata ricevuta e visualizzata.

### optimizeResources {#optimizeResources--}
```
public void optimizeResources()
```

Ottimizza le risorse nel documento: 1.

### optimizeResources {#optimizeResources-com.aspose.pdf.optimization.OptimizationOptions-}
Ottimizza le risorse nel documento secondo la strategia di ottimizzazione definita.

### pageNodesToBalancedTree {#pageNodesToBalancedTree--}
```
public void pageNodesToBalancedTree()
```

Organizza i nodi dell'albero delle pagine in un documento in un albero bilanciato.

### pageNodesToBalancedTree {#pageNodesToBalancedTree-byte-}
```
public void pageNodesToBalancedTree(byte nodesNumInSubtrees)
```

Organizza i nodi dell'albero delle pagine in un documento in un albero bilanciato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nodesNumInSubtrees |  | Numero desiderato di sotto-nodi. Valore predefinito è dieci. |

### preSave {#preSave-com.aspose.pdf.PageCollection-com.aspose.pdf.SaveOptions-}
Metodo interno

### processParagraphs {#processParagraphs--}
```
public void processParagraphs()
```

Memorizza il documento nel generatore.

### removeMetadata {#removeMetadata--}
```
public void removeMetadata()
```

Rimuove i metadati dal documento.

### removePdfaCompliance {#removePdfaCompliance--}
```
public void removePdfaCompliance()
```

Rimuove la conformità PDF/A dal documento

### removePdfUaCompliance {#removePdfUaCompliance--}
```
public void removePdfUaCompliance()
```

Rimuove la conformità PDF/UA dal documento

### repair {#repair--}
```
public void repair()
```

Ripara il documento danneggiato.

### repair {#repair-com.aspose.pdf.Document.RepairOptions-}
Ripara il documento danneggiato.

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

riprende l'aggiornamento del documento

### save {#save--}
```
public void save()
```

Salva il documento in modo incrementale (ad es.

### save {#save-javax.servlet.http.HttpServletResponse-java.lang.String-com.aspose.pdf.ContentDisposition-com.aspose.pdf.SaveOptions-}
Salva il documento in un flusso di risposta con le opzioni di salvataggio.

### save {#save-java.io.OutputStream-}
Memorizza il documento in un flusso.

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveFormat-}
Salva il documento con un nuovo nome insieme a un formato file.

### save {#save-java.io.OutputStream-com.aspose.pdf.SaveOptions-}
Salva il documento con un nuovo nome impostando le sue opzioni di salvataggio.

### save {#save-com.aspose.pdf.SaveOptions-}
Salva il documento con le opzioni di salvataggio.

### save {#save-com.aspose.ms.System.IO.Stream-}
Solo per uso interno

### save {#save-java.lang.String-}
Salva il documento nel file specificato.

### save {#save-java.lang.String-com.aspose.pdf.SaveFormat-}
Salva il documento con un nuovo nome insieme a un formato file.

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

### setAbsentFontHandler {#setAbsentFontHandler-com.aspose.pdf.ADocument.AbsentFontHandler-}
Notifica dei font mancanti durante l'elaborazione dei documenti.

### setAbsentFontTryToSubstitute {#setAbsentFontTryToSubstitute-boolean-}
```
public void setAbsentFontTryToSubstitute(boolean substitute)
```

Impostazione del flag per sostituire il font mancante.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sostituto |  | valore booleano |

### setAllowReusePageContent {#setAllowReusePageContent-boolean-}
```
public void setAllowReusePageContent(boolean value)
```

Consente di unire i contenuti delle pagine per ottimizzare le dimensioni del documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setBackground {#setBackground-java.awt.Color-}
Imposta il colore di sfondo del documento.

### setCenterWindow {#setCenterWindow-boolean-}
```
public void setCenterWindow(boolean value)
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
public final void setConvertMetadataAndCatalogOnly(boolean value)
```

Ottiene il parametro di conversione per il convertitore pdf/ua (Converti solo i Metadati e il Catalogo del Documento se impostato su true).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setDefaultFileSizeLimitToMemoryLoading {#setDefaultFileSizeLimitToMemoryLoading--}
```
public static void setDefaultFileSizeLimitToMemoryLoading()
```

Imposta il limite di dimensione del file per caricare un intero file in memoria al valore predefinito pari a 210 Mb.

### setDirection {#setDirection-com.aspose.pdf.Direction-}
Imposta l'ordine di lettura del testo: L2R (da sinistra a destra) o R2L (da destra a sinistra).

### setDisableFontLicenseVerifications {#setDisableFontLicenseVerifications-boolean-}
```
public final void setDisableFontLicenseVerifications(boolean value)
```

Molte operazioni con il font non possono essere eseguite se queste operazioni sono vietate dalla licenza di questo font.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Valore booleano, per impostazione predefinita false. |

### setDisplayDocTitle {#setDisplayDocTitle-boolean-}
```
public void setDisplayDocTitle(boolean value)
```

Imposta il flag che specifica se la barra del titolo della finestra del documento deve visualizzare il titolo del documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setDuplex {#setDuplex-int-}
```
public void setDuplex(int value)
```

Ottiene o imposta l'opzione di gestione della stampa duplex da utilizzare quando si stampa il file dalla finestra di stampa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | PrintDuplex elemento |

### setEmbedStandardFonts {#setEmbedStandardFonts-boolean-}
```
public void setEmbedStandardFonts(boolean value)
```

Proprietà che dichiara che il documento deve incorporare tutti i font Type1 standard il cui flag IsEmbedded è impostato su true.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setEnableNotificationLogging {#setEnableNotificationLogging-boolean-}
```
public final void setEnableNotificationLogging(boolean value)
```

Ottiene o imposta un valore che indica se abilitare la registrazione delle notifiche.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setEnableObjectUnload {#setEnableObjectUnload-boolean-}
```
public void setEnableObjectUnload(boolean value)
```

Ottiene o imposta il flag che consente al documento di essere parzialmente scaricato dalla memoria.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setEnableSignatureSanitization {#setEnableSignatureSanitization-boolean-}
```
public final void setEnableSignatureSanitization(boolean value)
```

Ottiene o imposta il flag per gestire la sanificazione dei campi firma.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setFileSizeLimitToMemoryLoading {#setFileSizeLimitToMemoryLoading-int-}
```
public static void setFileSizeLimitToMemoryLoading(int value)
```

Ottieni e imposta il limite di dimensione del file per caricare un intero file in memoria.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setFitWindow {#setFitWindow-boolean-}
```
public void setFitWindow(boolean value)
```

Imposta il flag che specifica se la finestra del documento deve essere ridimensionata per adattarsi alla prima pagina visualizzata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setHandleSignatureChange {#setHandleSignatureChange-boolean-}
```
public final void setHandleSignatureChange(boolean value)
```

Lancia un'eccezione se il documento viene salvato con modifiche e contiene una firma

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setHideMenubar {#setHideMenubar-boolean-}
```
public void setHideMenubar(boolean value)
```

Imposta il flag che specifica se la barra dei menu deve essere nascosta quando il documento è attivo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setHideToolBar {#setHideToolBar-boolean-}
```
public void setHideToolBar(boolean value)
```

Imposta il flag che specifica se la barra degli strumenti deve essere nascosta quando il documento è attivo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setHideWindowUI {#setHideWindowUI-boolean-}
```
public void setHideWindowUI(boolean value)
```

Imposta il flag che specifica se gli elementi dell'interfaccia utente devono essere nascosti quando il documento è attivo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setIgnoreCorruptedObjects {#setIgnoreCorruptedObjects-boolean-}
```
public void setIgnoreCorruptedObjects(boolean value)
```

Ottiene o imposta il flag per ignorare gli errori nei file sorgente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valori booleani |

### setLinearized {#setLinearized-boolean-}
```
public void setLinearized(boolean value)
```

Imposta un valore che indica se il documento è linearizzato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setManualDisposeEnabled {#setManualDisposeEnabled-boolean-}
```
public void setManualDisposeEnabled(boolean manualDisposeEnabled)
```

Per impostazione predefinita il metodo save chiude i flussi interni e rilascia le risorse di memoria.

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
public void setOptimizeSize(boolean value)
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
public final void setPickTrayByPdfSize(boolean value)
```

Imposta un flag che specifica se la dimensione della pagina PDF deve essere usata per selezionare il vassoio di ingresso della carta.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setPrintScaling {#setPrintScaling-int-}
```
public void setPrintScaling(int value)
```

Imposta l'opzione di gestione della scala di stampa da utilizzare quando si stampa il file dalla finestra di dialogo di stampa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | PrintDuplex elemento |

### setSkipPdfaCompliantValidationBeforeSave {#setSkipPdfaCompliantValidationBeforeSave-boolean-}
```
public void setSkipPdfaCompliantValidationBeforeSave(boolean pdfaCompliantValidationBeforeSave)
```

Per impostazione predefinita, il processo di convalida pdfa è necessario per aggiornare o rimuovere pdfa se alcune regole sono state violate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pdfaCompliantValidationBeforeSave |  | valore booleano |

### setTitle {#setTitle-java.lang.String-}
Imposta il titolo per il documento PDF.

### setXmpMetadata {#setXmpMetadata-java.io.InputStream-}
Imposta i metadati XMP del documento.

### setXrefGapsAllowed {#setXrefGapsAllowed-boolean-}
```
public void setXrefGapsAllowed(boolean value)
```

Ottiene o imposta se il documento è conforme a PDF/A.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### suppressUpdate {#suppressUpdate--}
```
public void suppressUpdate()
```

Sopprime l'aggiornamento dei contenuti per tutte le pagine. I contenuti non vengono aggiornati fino a quando non viene chiamato ResumeUpdate.

### updatePages {#updatePages--}
```
public void updatePages()
```

updatePages

### validate {#validate-java.io.OutputStream-com.aspose.pdf.PdfFormat-}
Convalida il documento nel file specificato.

### validate {#validate-com.aspose.pdf.PdfFormatConversionOptions-}
Convalida il documento nel file specificato.

### validate {#validate-java.lang.String-com.aspose.pdf.PdfFormat-}
Convalida il documento nel file specificato.
