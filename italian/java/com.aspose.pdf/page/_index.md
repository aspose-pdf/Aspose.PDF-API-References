---
title: "Page"
linktitle: "Page"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta una pagina di un documento PDF."
type: docs
weight: 3310
url: /it/java/com.aspose.pdf/page/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Page

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.IOperatorContainer, Closeable, AutoCloseable

```
public final class Page extends Object implements com.aspose.ms.System.IDisposable, Closeable , com.aspose.pdf.engine.IOperatorContainer
```

Classe che rappresenta una pagina di un documento PDF.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accetta l'oggetto visitatore {@code AnnotationSelector} che fornisce funzionalità per lavorare con le annotazioni. |
| [accept](#accept-com.aspose.pdf.ImagePlacementAbsorber-) | Accetta l'oggetto visitor {@code ImagePlacementAbsorber} che fornisce funzionalità per lavorare con gli oggetti di posizionamento immagine. |
| [accept](#accept-com.aspose.pdf.TextAbsorber-) | Accetta l'oggetto visitor {@code TextAbsorber} che fornisce funzionalità per lavorare con gli oggetti di testo. |
| [accept](#accept-com.aspose.pdf.TextFragmentAbsorber-) | Accetta l'oggetto visitor {@code TextFragmentAbsorber} che fornisce funzionalità per lavorare con gli oggetti di testo. |
| [addGraphics](#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-) | Aggiunge grafica alla pagina. Funziona più velocemente rispetto all'aggiunta di elementi uno per uno con il metodo GraphicElement#addOnPage(Page). |
| [addGraphics](#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-com.aspose.pdf.Rectangle-) | Aggiunge grafica alla pagina. Funziona più velocemente rispetto all'aggiunta di elementi uno per uno con il metodo GraphicElement#addOnPage(Page). |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-) | Aggiunge un'immagine alla pagina e la posiziona al centro del rettangolo specificato mantenendo le proporzioni dell'immagine. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-) | Aggiunge un'immagine ricercabile alla pagina e la posiziona al centro del rettangolo specificato mantenendo le proporzioni dell'immagine. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-com.aspose.pdf.Rectangle-) | Aggiunge un'immagine ricercabile alla pagina e la posiziona al centro del rettangolo specificato mantenendo le proporzioni dell'immagine. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-) | Aggiunge un'immagine alla pagina e la posiziona al centro del rettangolo specificato mantenendo le proporzioni dell'immagine. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-) | Aggiunge un'immagine alla pagina e la posiziona al centro del rettangolo specificato mantenendo le proporzioni dell'immagine. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-boolean-) | Aggiunge un'immagine alla pagina e la posiziona al centro del rettangolo specificato mantenendo le proporzioni dell'immagine. |
| [addImage](#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-) | Aggiunge un'immagine ricercabile alla pagina e la posiziona al centro del rettangolo specificato mantenendo le proporzioni dell'immagine. |
| [addImage](#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-) | Aggiunge un'immagine ricercabile alla pagina e la posiziona al centro del rettangolo specificato mantenendo le proporzioni dell'immagine. |
| [addImage](#addImage-java.lang.String-com.aspose.pdf.Rectangle-) | Aggiunge un'immagine alla pagina e la posiziona al centro del rettangolo specificato mantenendo le proporzioni dell'immagine. |
| [addStamp](#addStamp-com.aspose.pdf.Stamp-) | Inserisci un timbro nella pagina. Il timbro può essere il numero di pagina, un'immagine o un semplice testo, ad es. qualche logo. |
| [asByteArray](#asByteArray-com.aspose.pdf.devices.Resolution-) | Converte la pagina corrente in bitmap BMP e poi restituisce un array di byte. |
| [asXml](#asXml--) | Converte la pagina corrente in XML con codifica UTF-8. |
| [calculateContentBBox](#calculateContentBBox--) | Calcola il valore bbox - rettangolo che contiene i contenuti senza margini visibili. |
| [clearContents](#clearContents--) | Solo per uso interno |
| [close](#close--) | Chiude tutte le risorse utilizzate da questo documento. |
| [convertToPNGMemoryStream](#convertToPNGMemoryStream--) | Converti la pagina in PNG per lo stream di immagine DSR, OMR, OCR. |
| [deleteGraphics](#deleteGraphics-com.aspose.pdf.vector.GraphicElementCollection-) | Elimina la grafica dalla pagina. Funziona più velocemente rispetto all'eliminazione di elementi uno per uno con il metodo {@link GraphicElement#remove}. |
| [deleteUnusedResources](#deleteUnusedResources-com.aspose.ms.System.Collections.Generic.Dictionary-) |  |
| [dispose](#dispose--) | Libera la memoria. Questo metodo è obsoleto, usa close() al suo posto. |
| [fillUsedObjectsTable](#fillUsedObjectsTable-com.aspose.ms.System.Collections.Generic.Dictionary-com.aspose.pdf.engine.data.IPdfDictionary-) |  |
| [findReferences](#findReferences-com.aspose.pdf.OperatorCollection-java.lang.String-) | Restituisce l'elenco degli operatori che utilizzano la risorsa con il nome specificato. |
| [findReferences](#findReferences-java.lang.String-) | <p> Trova riferimenti </p> |
| [flatten](#flatten--) | Rimuove tutti i campi statici presenti nella pagina e inserisce i loro valori al loro posto. |
| [freeMemory](#freeMemory--) | Cancella i dati memorizzati nella cache |
| [getActions](#getActions--) | Ottiene la collezione delle proprietà della pagina. |
| [getAnnotations](#getAnnotations--) | Ottiene la collezione delle annotazioni della pagina. {@code Annotations} |
| [getArtBox](#getArtBox--) | <p> Ottiene la art box della pagina. </p> |
| [getArtifacts](#getArtifacts--) | Ottiene la collezione degli artefatti nella pagina. |
| [getBackground](#getBackground--) | Ottiene il colore di sfondo della pagina. |
| [getBackgroundImage](#getBackgroundImage--) | Ottiene o imposta l'immagine di sfondo per la pagina (solo per il generatore, non viene compilata durante la lettura del documento). |
| [getBleedBox](#getBleedBox--) | <p> Ottiene la bleed box della pagina. </p> |
| [getColorType](#getColorType--) | Ottiene il tipo di colore delle pagine in base alle informazioni ottenute dagli operatori SetColor, immagini e moduli. |
| [getContents](#getContents--) | <p> Ottiene la collezione di operatori nel flusso di contenuto della pagina. {@code OperatorCollection} </p> |
| [getContentsAppender](#getContentsAppender--) | Ottiene l'appender dei contenuti corrente. {@code ContentsAppender} |
| [getCropBox](#getCropBox--) | <p> Ottiene la crop box della pagina. </p> |
| [getDocument](#getDocument--) | Ottieni documento |
| [getDuration](#getDuration--) | <p> Ottiene la durata di visualizzazione della pagina. Questo è il tempo in secondi per cui la pagina deve essere visualizzata durante la presentazione. Restituisce -1 se la durata non è definita. </p> <hr> L'esempio dimostra come ottenere la durata della pagina <p> Document document = new Document("sample.pdf"); Page page = document.getPages().get(1); int pageRect = page.getDuration(); </p> |
| [getEnginePage](#getEnginePage--) | Solo per uso interno |
| [getFieldsInTabOrder](#getFieldsInTabOrder--) | Ottiene l'elenco di oggetti Field in ordine Tab su questa pagina. |
| [getFooter](#getFooter--) | Ottiene il Footer della pagina. |
| [getGroup](#getGroup--) | Ottiene una classe di attributi di gruppo che specifica gli attributi del gruppo di pagine della pagina per l'uso nel modello di imaging trasparente. |
| [getHeader](#getHeader--) | Ottiene l'header della pagina. |
| [getLayers](#getLayers--) | Ottiene la collezione di layer. |
| [getMediaBox](#getMediaBox--) | <p> Ottiene la media box della pagina. </p> |
| [getNoteLineStyle](#getNoteLineStyle--) | Ottiene lo stile di linea per le note. (solo per il generatore, non compilato durante la lettura del documento) |
| [getNotifications](#getNotifications--) | Restituisce notifiche sulle operazioni interne con il contenuto della pagina. (Attualmente sono supportate solo notifiche sugli eventi di paragrafo negli scenari di aggiunta di testo.) |
| [getNumber](#getNumber--) | Ottieni il numero della pagina. |
| [getOnBeforePageGenerate](#getOnBeforePageGenerate--) | Evento per personalizzare header e footer. |
| [getPageInfo](#getPageInfo--) | Ottiene le informazioni della pagina. (solo per il generatore, non compilato durante la lettura del documento). |
| [getPageRect](#getPageRect-boolean-) | Restituisce il rettangolo della pagina secondo la sua CropBox (o MediaBox se CropBox è null). |
| [getParagraphs](#getParagraphs--) | Ottiene i paragrafi. |
| [getRect_Rename_Namesake](#getRect_Rename_Namesake--) | <p> Restituisce il rettangolo della pagina secondo la sua CropBox e MediaBox; </p> Internal |
| [getRect](#getRect--) | <p> Restituisce il rettangolo della pagina secondo la sua CropBox e MediaBox; Per il get: la crop box della pagina è restituita se specificata, altrimenti è restituita la media box della pagina. Per il set: la media box della pagina è sempre impostata. </p> |
| [getResources](#getResources--) | Recupera le risorse associate alla pagina. |
| [getResourcesField](#getResourcesField--) | <p> Ottiene le risorse della pagina. L'oggetto Resources contiene collezioni di immagini, moduli e font. {@code Resources} </p> |
| [getRotate](#getRotate--) | <p> Ottiene la rotazione della pagina. </p> |
| [getRotationMatrix](#getRotationMatrix--) | Ottiene la matrice di trasformazione per la pagina. |
| [getTabOrder](#getTabOrder--) | Ottiene l'ordine delle schede della pagina. Valori possibili: Row, Column. Predefinito, Manual |
| [getTocInfo](#getTocInfo--) | Ottiene le informazioni dell'indice. |
| [getTrimBox](#getTrimBox--) | <p> Ottiene il trim box della pagina. </p> |
| [getUserUnit](#getUserUnit--) | Ottiene o imposta il valore UserUnit. Un numero positivo che indica la dimensione delle unità di spazio utente predefinite, in multipli di 1/72 di pollice. Il valore predefinito è 1. Impostare zero o un valore negativo per cancellare questa voce nella pagina. |
| [getWatermark](#getWatermark--) | Ottiene la filigrana della pagina. |
| [hasVectorGraphics](#hasVectorGraphics--) | Rileva la presenza di grafica vettoriale, se è presente nella pagina. |
| [intToRotation](#intToRotation-int-) | Traduce il valore intero nel corrispondente membro dell'enumerazione di rotazione. |
| [isAddParagraphsAfterLast](#isAddParagraphsAfterLast--) | Ottiene o imposta l'aggiunta di paragrafi dopo l'ultimo paragrafo della pagina. Valore: il valore indica se i paragrafi saranno aggiunti dopo l'ultimo paragrafo della pagina. I paragrafi saranno aggiunti dopo l'ultimo paragrafo della pagina se il valore è true. |
| [isBlank](#isBlank-double-) | Ottiene il flag che indica se la pagina è vuota o meno. |
| [isBlank](#isBlank-double-boolean-) | Ottiene il flag che indica se la pagina è vuota o meno. |
| [makeGrayscale](#makeGrayscale--) | Converte la pagina in scala di grigi. |
| [mergeLayers](#mergeLayers-java.lang.String-) | Unisce tutti i livelli della pagina in un unico livello con il nome del nuovo livello specificato. |
| [mergeLayers](#mergeLayers-java.lang.String-java.lang.String-) | Unisce tutti i livelli della pagina in un unico livello con il nome del nuovo livello specificato e l'Id opzionale del gruppo di contenuto. |
| [removeObjectReferences](#removeObjectReferences-com.aspose.pdf.OperatorCollection-java.lang.String-) | Rimuovi i riferimenti agli oggetti |
| [removeObjectReferences](#removeObjectReferences-java.lang.String-) | Rimuovi i riferimenti a XObject dal contenuto della pagina (ad esempio tutti gli operatori Do che utilizzano il nome dell'oggetto). |
| [resize](#resize-com.aspose.pdf.PageSize-) | Ridimensiona la pagina. |
| [rotationToInt](#rotationToInt-com.aspose.pdf.Rotation-) | Traduce il membro dell'enumerazione di rotazione in valore intero. |
| [sendTo](#sendTo-com.aspose.pdf.devices.PageDevice-java.io.OutputStream-) | Invia la pagina al processo con il dispositivo di pagina fornito. |
| [sendTo](#sendTo-com.aspose.pdf.devices.PageDevice-java.lang.String-) | Invia la pagina al processo con il dispositivo di pagina fornito. |
| [setAddParagraphsAfterLast](#setAddParagraphsAfterLast-boolean-) | Ottiene o imposta l'aggiunta di paragrafi dopo l'ultimo paragrafo della pagina. Valore: il valore indica se i paragrafi saranno aggiunti dopo l'ultimo paragrafo della pagina. I paragrafi saranno aggiunti dopo l'ultimo paragrafo della pagina se il valore è true. |
| [setArtBox](#setArtBox-com.aspose.pdf.Rectangle-) | Imposta l'art box della pagina. |
| [setBackground](#setBackground-java.awt.Color-) | Imposta il colore di sfondo della pagina. |
| [setBackground](#setBackground-com.aspose.pdf.Color-) | Imposta il colore di sfondo della pagina. |
| [setBackgroundImage](#setBackgroundImage-com.aspose.pdf.Image-) | Ottiene o imposta l'immagine di sfondo per la pagina (solo per il generatore, non viene compilata durante la lettura del documento). |
| [setBleedBox](#setBleedBox-com.aspose.pdf.Rectangle-) | Imposta il bleed box della pagina. |
| [setCropBox](#setCropBox-com.aspose.pdf.Rectangle-) | <p> Imposta il crop box della pagina. </p> <hr> <pre> Example demonstrates how to get crop box of the page: Document document = new Document(\"sample.pdf\"); document.getPages().get_Item(1).setCropBox(new Rectangle(0d,0d,100d,100d)); </pre> |
| [setDuration](#setDuration-double-) | Imposta la durata di visualizzazione della pagina. Questo è il tempo in secondi per cui la pagina deve essere mostrata durante la presentazione. Restituisce -1 se la durata non è definita. |
| [setEnginePage](#setEnginePage-com.aspose.pdf.engine.commondata.IPage-) | Solo per uso interno |
| [setFooter](#setFooter-com.aspose.pdf.HeaderFooter-) | Imposta il Footer della pagina. |
| [setGroup](#setGroup-com.aspose.pdf.Group-) | Imposta una classe di attributi di gruppo che specifica gli attributi del gruppo di pagine della pagina per l'uso nel modello di imaging trasparente. |
| [setHeader](#setHeader-com.aspose.pdf.HeaderFooter-) | Imposta l'intestazione della pagina. |
| [setLayers](#setLayers-java.util.ArrayList-) | Imposta la raccolta dei livelli. |
| [setLayersInternal](#setLayersInternal-com.aspose.ms.System.Collections.Generic.List-) | Imposta la raccolta dei livelli. |
| [setMediaBox](#setMediaBox-com.aspose.pdf.Rectangle-) | Imposta la media box della pagina. |
| [setNoteLineStyle](#setNoteLineStyle-com.aspose.pdf.GraphInfo-) | Imposta lo stile della linea per le note. (solo per il generatore, non compilato durante la lettura del documento) |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Imposta le informazioni della pagina. (solo per il generatore, non compilato durante la lettura del documento). |
| [setPageSize](#setPageSize-double-double-) | Imposta la dimensione della pagina. |
| [setParagraphs](#setParagraphs-com.aspose.pdf.Paragraphs-) | Imposta i paragrafi. |
| [setRect](#setRect-com.aspose.pdf.Rectangle-) | Ottiene o imposta il rettangolo della pagina. Per l'ottenimento: viene restituita la crop box della pagina se specificata, altrimenti viene restituita la media box della pagina. Per l'impostazione: la media box della pagina viene sempre impostata. Si noti che questa proprietà non considera la rotazione della pagina. Per ottenere il rettangolo della pagina considerando la rotazione, utilizzare ActualRect. |
| [setRotate](#setRotate-com.aspose.pdf.Rotation-) | Imposta la rotazione della pagina. |
| [setTabOrder](#setTabOrder-int-) | Imposta l'ordine delle schede della pagina. Valori possibili: Row, Column. Predefinito, Manual |
| [setTocInfo](#setTocInfo-com.aspose.pdf.TocInfo-) | Imposta le informazioni dell'indice. |
| [setTransition](#setTransition-com.aspose.pdf.engine.data.IPdfDictionary-) | Imposta la transizione |
| [setTrimBox](#setTrimBox-com.aspose.pdf.Rectangle-) | Imposta la trim box della pagina. |
| [setUserUnit](#setUserUnit-double-) | Ottiene o imposta il valore UserUnit. Un numero positivo che indica la dimensione delle unità di spazio utente predefinite, in multipli di 1/72 di pollice. Il valore predefinito è 1. Impostare zero o un valore negativo per cancellare questa voce nella pagina. |
| [setWatermark](#setWatermark-com.aspose.pdf.Watermark-) | Imposta la filigrana della pagina. |
| [trySaveVectorGraphics](#trySaveVectorGraphics-java.lang.String-) | Tenta di salvare la grafica vettoriale se è presente nella pagina. Il formato di salvataggio è SVG. |

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accetta l'oggetto visitatore {@code AnnotationSelector} che fornisce funzionalità per lavorare con le annotazioni.

### accept {#accept-com.aspose.pdf.ImagePlacementAbsorber-}
Accetta l'oggetto visitor {@code ImagePlacementAbsorber} che fornisce funzionalità per lavorare con gli oggetti di posizionamento immagine.

### accept {#accept-com.aspose.pdf.TextAbsorber-}
Accetta l'oggetto visitor {@code TextAbsorber} che fornisce funzionalità per lavorare con gli oggetti di testo.

### accept {#accept-com.aspose.pdf.TextFragmentAbsorber-}
Accetta l'oggetto visitor {@code TextFragmentAbsorber} che fornisce funzionalità per lavorare con gli oggetti di testo.

### addGraphics {#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-}
Aggiunge grafica alla pagina. Funziona più velocemente rispetto all'aggiunta di elementi uno per uno con il metodo GraphicElement#addOnPage(Page).

### addGraphics {#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-com.aspose.pdf.Rectangle-}
Aggiunge grafica alla pagina. Funziona più velocemente rispetto all'aggiunta di elementi uno per uno con il metodo GraphicElement#addOnPage(Page).

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-}
Aggiunge un'immagine alla pagina e la posiziona al centro del rettangolo specificato mantenendo le proporzioni dell'immagine.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-}
Aggiunge un'immagine ricercabile alla pagina e la posiziona al centro del rettangolo specificato mantenendo le proporzioni dell'immagine.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-com.aspose.pdf.Rectangle-}
Aggiunge un'immagine ricercabile alla pagina e la posiziona al centro del rettangolo specificato mantenendo le proporzioni dell'immagine.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-}
Aggiunge un'immagine alla pagina e la posiziona al centro del rettangolo specificato mantenendo le proporzioni dell'immagine.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-}
Aggiunge un'immagine alla pagina e la posiziona al centro del rettangolo specificato mantenendo le proporzioni dell'immagine.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-boolean-}
Aggiunge un'immagine alla pagina e la posiziona al centro del rettangolo specificato mantenendo le proporzioni dell'immagine.

### addImage {#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-}
Aggiunge un'immagine ricercabile alla pagina e la posiziona al centro del rettangolo specificato mantenendo le proporzioni dell'immagine.

### addImage {#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-}
Aggiunge un'immagine ricercabile alla pagina e la posiziona al centro del rettangolo specificato mantenendo le proporzioni dell'immagine.

### addImage {#addImage-java.lang.String-com.aspose.pdf.Rectangle-}
Aggiunge un'immagine alla pagina e la posiziona al centro del rettangolo specificato mantenendo le proporzioni dell'immagine.

### addStamp {#addStamp-com.aspose.pdf.Stamp-}
Inserisci un timbro nella pagina. Il timbro può essere il numero di pagina, un'immagine o un semplice testo, ad es. qualche logo.

### asByteArray {#asByteArray-com.aspose.pdf.devices.Resolution-}
Converte la pagina corrente in bitmap BMP e poi restituisce un array di byte.

### asXml {#asXml--}
```
public String asXml()
```

Converte la pagina corrente in XML con codifica UTF-8.

**Returns:**
Stringa XML convertita.

### calculateContentBBox {#calculateContentBBox--}
```
public Rectangle calculateContentBBox()
```

Calcola il valore bbox - rettangolo che contiene i contenuti senza margini visibili.

**Returns:**
Valore Bbox - rettangolo che contiene i contenuti senza margini visibili

### clearContents {#clearContents--}
```
public void clearContents()
```

Solo per uso interno

### close {#close--}
```
public void close()
```

Chiude tutte le risorse utilizzate da questo documento.

### convertToPNGMemoryStream {#convertToPNGMemoryStream--}
```
public byte[] convertToPNGMemoryStream()
```

Converti la pagina in PNG per lo stream di immagine DSR, OMR, OCR.

**Returns:**
Flusso immagine in array byte[] .

### deleteGraphics {#deleteGraphics-com.aspose.pdf.vector.GraphicElementCollection-}
Elimina la grafica dalla pagina. Funziona più velocemente rispetto all'eliminazione di elementi uno per uno con il metodo {@link GraphicElement#remove}.

### deleteUnusedResources {#deleteUnusedResources-com.aspose.ms.System.Collections.Generic.Dictionary-}


### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Libera la memoria. Questo metodo è obsoleto, usa close() al suo posto.

### fillUsedObjectsTable {#fillUsedObjectsTable-com.aspose.ms.System.Collections.Generic.Dictionary-com.aspose.pdf.engine.data.IPdfDictionary-}


### findReferences {#findReferences-com.aspose.pdf.OperatorCollection-java.lang.String-}
Restituisce l'elenco degli operatori che utilizzano la risorsa con il nome specificato.

### findReferences {#findReferences-java.lang.String-}
<p> Trova riferimenti </p>

### flatten {#flatten--}
```
public void flatten()
```

Rimuove tutti i campi statici presenti nella pagina e inserisce i loro valori al loro posto.

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

Cancella i dati memorizzati nella cache

### getActions {#getActions--}
```
public PageActionCollection getActions()
```

Ottiene la collezione delle proprietà della pagina.

**Returns:**
Valore PageActionCollection

### getAnnotations {#getAnnotations--}
```
public AnnotationCollection getAnnotations()
```

Ottiene la collezione delle annotazioni della pagina. {@code Annotations}

**Returns:**
Valore AnnotationCollection

### getArtBox {#getArtBox--}
```
public Rectangle getArtBox()
```

<p> Ottiene la art box della pagina. </p>

**Returns:**
Valore Rectangle <hr> <pre> Esempio che dimostra come ottenere la art box della pagina: Document document = new Document("sample.pdf"); Rectangle artBox = document.getPages().get(1).getArtBox(); </pre>

### getArtifacts {#getArtifacts--}
```
public ArtifactCollection getArtifacts()
```

Ottiene la collezione degli artefatti nella pagina.

**Returns:**
Valore ArtifactCollection

### getBackground {#getBackground--}
```
public Color getBackground()
```

Ottiene il colore di sfondo della pagina.

**Returns:**
Valore colore

### getBackgroundImage {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```

Ottiene o imposta l'immagine di sfondo per la pagina (solo per il generatore, non viene compilata durante la lettura del documento).

**Returns:**
Istanza immagine

### getBleedBox {#getBleedBox--}
```
public Rectangle getBleedBox()
```

<p> Ottiene la bleed box della pagina. </p>

**Returns:**
Valore Rectangle <hr> <pre> Esempio che dimostra come ottenere la bleed box della pagina: Document document = new Document("sample.pdf"); Rectangle bleedBox = document.getPages().get(1).getBleedBox(); </pre>

### getColorType {#getColorType--}
```
public ColorType getColorType()
```

Ottiene il tipo di colore delle pagine in base alle informazioni ottenute dagli operatori SetColor, immagini e moduli.

**Returns:**
Elemento ColorType @see ColorType

### getContents {#getContents--}
```
public OperatorCollection getContents()
```

<p> Ottiene la collezione di operatori nel flusso di contenuto della pagina. {@code OperatorCollection} </p>

**Returns:**
Oggetto OperatorCollection <hr> <pre> Esempio che dimostra come scansionare lo stream degli operatori della pagina. Document document = new Document("sample.pdf"); Operators contents = document.getPages().get_Item(1).getContents(); for(Operator op : {@code (Iterable<Operator>)}contents) { System.out.println(op); } </pre>

### getContentsAppender {#getContentsAppender--}
```
public ContentsAppender getContentsAppender()
```

Ottiene l'appender dei contenuti corrente. {@code ContentsAppender}

**Returns:**
ContentsAppender valore

### getCropBox {#getCropBox--}
```
public Rectangle getCropBox()
```

<p> Ottiene la crop box della pagina. </p>

**Returns:**
Rectangle valore <hr> <pre> Esempio dimostra come ottenere il crop box della pagina: Document document = new Document("sample.pdf"); Rectangle cropBox = document.getPages().get_Item(1).getCropBox(); </pre>

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

Ottieni documento

**Returns:**
Oggetto IDocument

### getDuration {#getDuration--}
```
public double getDuration()
```

<p> Ottiene la durata di visualizzazione della pagina. Questo è il tempo in secondi per cui la pagina deve essere visualizzata durante la presentazione. Restituisce -1 se la durata non è definita. </p> <hr> L'esempio dimostra come ottenere la durata della pagina <p> Document document = new Document("sample.pdf"); Page page = document.getPages().get(1); int pageRect = page.getDuration(); </p>

**Returns:**
valore double

### getEnginePage {#getEnginePage--}
```
public com.aspose.pdf.engine.commondata.IPage getEnginePage()
```

Solo per uso interno

**Returns:**
istanza interna

### getFieldsInTabOrder {#getFieldsInTabOrder--}
```
public List < Field > getFieldsInTabOrder()
```

Ottiene l'elenco di oggetti Field in ordine Tab su questa pagina.

**Returns:**
Elenco di oggetti campo

### getFooter {#getFooter--}
```
public HeaderFooter getFooter()
```

Ottiene il Footer della pagina.

**Returns:**
Il Footer della pagina.

### getGroup {#getGroup--}
```
public Group getGroup()
```

Ottiene una classe di attributi di gruppo che specifica gli attributi del gruppo di pagine della pagina per l'uso nel modello di imaging trasparente.

**Returns:**
Group valore

### getHeader {#getHeader--}
```
public HeaderFooter getHeader()
```

Ottiene l'header della pagina.

**Returns:**
L'header della pagina.

### getLayers {#getLayers--}
```
public List < Layer > getLayers()
```

Ottiene la collezione di layer.

**Returns:**
Valore: la collezione dei layer.

### getMediaBox {#getMediaBox--}
```
public Rectangle getMediaBox()
```

<p> Ottiene la media box della pagina. </p>

**Returns:**
Rectangle valore <hr> <pre> Esempio dimostra come ottenere il media box della pagina: Document document = new Document("sample.pdf"); Rectangle mediaBox = document.getPages().get(1).getMediaBox(); </pre>

### getNoteLineStyle {#getNoteLineStyle--}
```
public GraphInfo getNoteLineStyle()
```

Ottiene lo stile di linea per le note. (solo per il generatore, non compilato durante la lettura del documento)

**Returns:**
GraphInfo valore

### getNotifications {#getNotifications--}
```
public String getNotifications()
```

Restituisce notifiche sulle operazioni interne con il contenuto della pagina. (Attualmente sono supportate solo notifiche sugli eventi di paragrafo negli scenari di aggiunta di testo.)

**Returns:**
Stringa che rappresenta le notifiche relative alle operazioni interne con il contenuto della pagina.

### getNumber {#getNumber--}
```
public final int getNumber()
```

Ottieni il numero della pagina.

**Returns:**
valore int

### getOnBeforePageGenerate {#getOnBeforePageGenerate--}
```
public PdfEvent < Page.BeforePageGenerate > getOnBeforePageGenerate()
```

Evento per personalizzare header e footer.

**Returns:**
{@code PdfEvent<BeforePageGenerate> istanza}

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

Ottiene le informazioni della pagina. (solo per il generatore, non compilato durante la lettura del documento).

**Returns:**
Le informazioni della pagina.

### getPageRect {#getPageRect-boolean-}
```
public Rectangle getPageRect(boolean considerRotation)
```

Restituisce il rettangolo della pagina secondo la sua CropBox (o MediaBox se CropBox è null).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| considerRotation |  | Se true, la rotazione della pagina sarà considerata nel calcolo del rettangolo. |

**Returns:**
Rettangolo della pagina.

### getParagraphs {#getParagraphs--}
```
public Paragraphs getParagraphs()
```

Ottiene i paragrafi.

**Returns:**
I paragrafi.

### getRect_Rename_Namesake {#getRect_Rename_Namesake--}
```
public Rectangle getRect_Rename_Namesake()
```

<p> Restituisce il rettangolo della pagina secondo la sua CropBox e MediaBox; </p> Internal

**Returns:**
Rectangle valore <hr> <pre> Esempio dimostra come ottenere il rettangolo della pagina: Document document = new Document("sample.pdf"); Page page = document.getPages().get(1); Rectangle pageRect = page.getRect(); </pre>

### getRect {#getRect--}
```
public Rectangle getRect()
```

<p> Restituisce il rettangolo della pagina secondo la sua CropBox e MediaBox; Per il get: la crop box della pagina è restituita se specificata, altrimenti è restituita la media box della pagina. Per il set: la media box della pagina è sempre impostata. </p>

**Returns:**
Rectangle valore <hr> <pre> Esempio dimostra come ottenere il rettangolo della pagina: Document document = new Document("sample.pdf"); Page page = document.getPages().get(1); Rectangle pageRect = page.getRect(); </pre>

### getResources {#getResources--}
```
public final Resources getResources()
```

Recupera le risorse associate alla pagina.

**Returns:**
Un oggetto {@code Resources}({@link #getResources()}) che rappresenta le risorse della pagina.

### getResourcesField {#getResourcesField--}
```
public Resources getResourcesField()
```

<p> Ottiene le risorse della pagina. L'oggetto Resources contiene collezioni di immagini, moduli e font. {@code Resources} </p>

**Returns:**
Resources valore <hr> <pre> Esempio dimostra la scansione delle immagini della pagina: Document document = new Document("sample.pdf"); DocumentActions actions = document.getActions(); Resources resources = document.getPages().get(1).getResources(); for(XImage image : {@code (Iterable<XImage>)resources}.getImages()) { System.out.println(image.getWidth() + ":" + image.getHeight()); } </pre>

### getRotate {#getRotate--}
```
public Rotation getRotate()
```

<p> Ottiene la rotazione della pagina. </p>

**Returns:**
Rotation elemento <hr> <pre> Esempio dimostra come determinare la rotazione della pagina. Document document = new Document("sample.pdf"); System.out.println(document.getPages().get(1).getRotate()); </pre> @see Rotation

### getRotationMatrix {#getRotationMatrix--}
```
public Matrix getRotationMatrix()
```

Ottiene la matrice di trasformazione per la pagina.

**Returns:**
Matrix valore

### getTabOrder {#getTabOrder--}
```
public int getTabOrder()
```

Ottiene l'ordine delle schede della pagina. Valori possibili: Row, Column. Predefinito, Manual

**Returns:**
TabOrder valore @see TabOrder

### getTocInfo {#getTocInfo--}
```
public TocInfo getTocInfo()
```

Ottiene le informazioni dell'indice.

**Returns:**
Le informazioni del sommario - default null. Se impostato, questa pagina conterrà il sommario.

### getTrimBox {#getTrimBox--}
```
public Rectangle getTrimBox()
```

<p> Ottiene il trim box della pagina. </p>

**Returns:**
Rectangle valore <hr> <pre> Esempio dimostra come ottenere il trim box della pagina: Document document = new Document("sample.pdf"); Rectangle trimBox = document.getPages().get(1).getTrimBox(); </pre>

### getUserUnit {#getUserUnit--}
```
public final double getUserUnit()
```

Ottiene o imposta il valore UserUnit. Un numero positivo che indica la dimensione delle unità di spazio utente predefinite, in multipli di 1/72 di pollice. Il valore predefinito è 1. Impostare zero o un valore negativo per cancellare questa voce nella pagina.

**Returns:**
valore double

### getWatermark {#getWatermark--}
```
public Watermark getWatermark()
```

Ottiene la filigrana della pagina.

**Returns:**
Watermark valore

### hasVectorGraphics {#hasVectorGraphics--}
```
public final boolean hasVectorGraphics()
```

Rileva la presenza di grafica vettoriale, se è presente nella pagina.

**Returns:**
True se la pagina contiene operatori di costruzione del percorso; altrimenti, False.

### intToRotation {#intToRotation-int-}
```
public static Rotation intToRotation(int rotation)
```

Traduce il valore intero nel corrispondente membro dell'enumerazione di rotazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rotazione |  | Valore intero da convertire |

**Returns:**
Membro dell'enumerazione Rotation @see Rotation

### isAddParagraphsAfterLast {#isAddParagraphsAfterLast--}
```
public final boolean isAddParagraphsAfterLast()
```

Ottiene o imposta l'aggiunta di paragrafi dopo l'ultimo paragrafo della pagina. Valore: il valore indica se i paragrafi saranno aggiunti dopo l'ultimo paragrafo della pagina. I paragrafi saranno aggiunti dopo l'ultimo paragrafo della pagina se il valore è true.

**Returns:**
valore booleano

### isBlank {#isBlank-double-}
```
public boolean isBlank(double fillThresholdFactor)
```

Ottiene il flag che indica se la pagina è vuota o meno.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fillThresholdFactor |  | Il valore della soglia di riempimento che gestisce la sensibilità del rilevamento. Deve essere nell'intervallo [0..1). Per determinare se una pagina è vuota o meno, viene calcolato il rapporto tra lo spazio riempito e lo spazio totale della pagina. Questo rapporto è confrontato con il parametro fillThresholdFactor e se è inferiore, la pagina è considerata vuota. |

**Returns:**
Valore booleano True - se la pagina è vuota; altrimenti, false.

### isBlank {#isBlank-double-boolean-}
```
public boolean isBlank(double fillThresholdFactor, boolean parseWhiteContent)
```

Ottiene il flag che indica se la pagina è vuota o meno.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fillThresholdFactor |  | Il valore della soglia di riempimento che gestisce la sensibilità del rilevamento. Deve essere uguale o maggiore di 0,01. |
| parseWhiteContent |  | True per la scansione completa della pagina con analisi del contenuto bianco, False (predefinito) - algoritmo veloce, dove la grafica bianca è considerata come pagina non vuota. |

**Returns:**
Valore booleano True - se la pagina è vuota; altrimenti, false.

### makeGrayscale {#makeGrayscale--}
```
public final void makeGrayscale()
```

Converte la pagina in scala di grigi.

### mergeLayers {#mergeLayers-java.lang.String-}
Unisce tutti i livelli della pagina in un unico livello con il nome del nuovo livello specificato.

### mergeLayers {#mergeLayers-java.lang.String-java.lang.String-}
Unisce tutti i livelli della pagina in un unico livello con il nome del nuovo livello specificato e l'Id opzionale del gruppo di contenuto.

### removeObjectReferences {#removeObjectReferences-com.aspose.pdf.OperatorCollection-java.lang.String-}
Rimuovi i riferimenti agli oggetti

### removeObjectReferences {#removeObjectReferences-java.lang.String-}
Rimuovi i riferimenti a XObject dal contenuto della pagina (ad esempio tutti gli operatori Do che utilizzano il nome dell'oggetto).

### resize {#resize-com.aspose.pdf.PageSize-}
Ridimensiona la pagina.

### rotationToInt {#rotationToInt-com.aspose.pdf.Rotation-}
Traduce il membro dell'enumerazione di rotazione in valore intero.

### sendTo {#sendTo-com.aspose.pdf.devices.PageDevice-java.io.OutputStream-}
Invia la pagina al processo con il dispositivo di pagina fornito.

### sendTo {#sendTo-com.aspose.pdf.devices.PageDevice-java.lang.String-}
Invia la pagina al processo con il dispositivo di pagina fornito.

### setAddParagraphsAfterLast {#setAddParagraphsAfterLast-boolean-}
```
public final void setAddParagraphsAfterLast(boolean value)
```

Ottiene o imposta l'aggiunta di paragrafi dopo l'ultimo paragrafo della pagina. Valore: il valore indica se i paragrafi saranno aggiunti dopo l'ultimo paragrafo della pagina. I paragrafi saranno aggiunti dopo l'ultimo paragrafo della pagina se il valore è true.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setArtBox {#setArtBox-com.aspose.pdf.Rectangle-}
Imposta l'art box della pagina.

### setBackground {#setBackground-java.awt.Color-}
Imposta il colore di sfondo della pagina.

### setBackground {#setBackground-com.aspose.pdf.Color-}
Imposta il colore di sfondo della pagina.

### setBackgroundImage {#setBackgroundImage-com.aspose.pdf.Image-}
Ottiene o imposta l'immagine di sfondo per la pagina (solo per il generatore, non viene compilata durante la lettura del documento).

### setBleedBox {#setBleedBox-com.aspose.pdf.Rectangle-}
Imposta il bleed box della pagina.

### setCropBox {#setCropBox-com.aspose.pdf.Rectangle-}
<p> Imposta il crop box della pagina. </p> <hr> <pre> Example demonstrates how to get crop box of the page: Document document = new Document(\"sample.pdf\"); document.getPages().get_Item(1).setCropBox(new Rectangle(0d,0d,100d,100d)); </pre>

### setDuration {#setDuration-double-}
```
public void setDuration(double value)
```

Imposta la durata di visualizzazione della pagina. Questo è il tempo in secondi per cui la pagina deve essere mostrata durante la presentazione. Restituisce -1 se la durata non è definita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | durata visualizzazione pagina. |

### setEnginePage {#setEnginePage-com.aspose.pdf.engine.commondata.IPage-}
Solo per uso interno

### setFooter {#setFooter-com.aspose.pdf.HeaderFooter-}
Imposta il Footer della pagina.

### setGroup {#setGroup-com.aspose.pdf.Group-}
Imposta una classe di attributi di gruppo che specifica gli attributi del gruppo di pagine della pagina per l'uso nel modello di imaging trasparente.

### setHeader {#setHeader-com.aspose.pdf.HeaderFooter-}
Imposta l'intestazione della pagina.

### setLayers {#setLayers-java.util.ArrayList-}
Imposta la raccolta dei livelli.

### setLayersInternal {#setLayersInternal-com.aspose.ms.System.Collections.Generic.List-}
Imposta la raccolta dei livelli.

### setMediaBox {#setMediaBox-com.aspose.pdf.Rectangle-}
Imposta la media box della pagina.

### setNoteLineStyle {#setNoteLineStyle-com.aspose.pdf.GraphInfo-}
Imposta lo stile della linea per le note. (solo per il generatore, non compilato durante la lettura del documento)

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
Imposta le informazioni della pagina. (solo per il generatore, non compilato durante la lettura del documento).

### setPageSize {#setPageSize-double-double-}
```
public void setPageSize(double width, double height)
```

Imposta la dimensione della pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| larghezza |  | Larghezza pagina. |
| altezza |  | Dimensione pagina. |

### setParagraphs {#setParagraphs-com.aspose.pdf.Paragraphs-}
Imposta i paragrafi.

### setRect {#setRect-com.aspose.pdf.Rectangle-}
Ottiene o imposta il rettangolo della pagina. Per l'ottenimento: viene restituita la crop box della pagina se specificata, altrimenti viene restituita la media box della pagina. Per l'impostazione: la media box della pagina viene sempre impostata. Si noti che questa proprietà non considera la rotazione della pagina. Per ottenere il rettangolo della pagina considerando la rotazione, utilizzare ActualRect.

### setRotate {#setRotate-com.aspose.pdf.Rotation-}
Imposta la rotazione della pagina.

### setTabOrder {#setTabOrder-int-}
```
public void setTabOrder(int value)
```

Imposta l'ordine delle schede della pagina. Valori possibili: Row, Column. Predefinito, Manual

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Oggetto TabOrder @see TabOrder |

### setTocInfo {#setTocInfo-com.aspose.pdf.TocInfo-}
Imposta le informazioni dell'indice.

### setTransition {#setTransition-com.aspose.pdf.engine.data.IPdfDictionary-}
Imposta la transizione

### setTrimBox {#setTrimBox-com.aspose.pdf.Rectangle-}
Imposta la trim box della pagina.

### setUserUnit {#setUserUnit-double-}
```
public final void setUserUnit(double value)
```

Ottiene o imposta il valore UserUnit. Un numero positivo che indica la dimensione delle unità di spazio utente predefinite, in multipli di 1/72 di pollice. Il valore predefinito è 1. Impostare zero o un valore negativo per cancellare questa voce nella pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setWatermark {#setWatermark-com.aspose.pdf.Watermark-}
Imposta la filigrana della pagina.

### trySaveVectorGraphics {#trySaveVectorGraphics-java.lang.String-}
Tenta di salvare la grafica vettoriale se è presente nella pagina. Il formato di salvataggio è SVG.
