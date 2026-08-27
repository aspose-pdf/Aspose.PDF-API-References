---
title: "PdfPageEditor"
linktitle: "PdfPageEditor"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una classe per modificare la pagina del file PDF, inclusa la rotazione della pagina, lo zoom, lo spostamento della posizione e la modifica delle dimensioni della pagina."
type: docs
weight: 570
url: /it/java/com.aspose.pdf.facades/pdfpageeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfPageEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfPageEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfPageEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfPageEditor extends SaveableFacade
```

Rappresenta una classe per modificare la pagina del file PDF, inclusa la rotazione della pagina, lo zoom, lo spostamento della posizione e la modifica delle dimensioni della pagina.

## Campi

| Campo | Descrizione |
| --- | --- |
| [BLINDH](#BLINDH) | Tende verticali |
| [BLINDV](#BLINDV) | Tende verticali |
| [BTWIPE](#BTWIPE) | Cancellazione dal basso verso l'alto |
| [DGLITTER](#DGLITTER) | Scintillio diagonale |
| [DISSOLVE](#DISSOLVE) | La vecchia pagina si dissolve |
| [INBOX](#INBOX) | Scatola verso l'interno |
| [LRGLITTER](#LRGLITTER) | Scintillio da sinistra a destra |
| [LRWIPE](#LRWIPE) | Cancellazione da sinistra a destra |
| [OUTBOX](#OUTBOX) | Scatola verso l'esterno |
| [RLWIPE](#RLWIPE) | Cancellazione da destra a sinistra |
| [SPLITHIN](#SPLITHIN) | IN divisione orizzontale |
| [SPLITHOUT](#SPLITHOUT) | Divisione orizzontale esterna |
| [SPLITVIN](#SPLITVIN) | Divisione verticale interna |
| [SPLITVOUT](#SPLITVOUT) | Divisione verticale esterna |
| [TBGLITTER](#TBGLITTER) | Scintillio dall'alto al basso |
| [TBWIPE](#TBWIPE) | Cancellazione dall'alto al basso |

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PdfPageEditor](#PdfPageEditor--) | Costruttore per la classe PdfPageEditor. |
| [PdfPageEditor](#PdfPageEditor-com.aspose.pdf.Document-) | Costruttore per la classe PdfPageEditor. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [applyChanges](#applyChanges--) | Applica le modifiche apportate alle pagine del documento. |
| [getAlignment](#getAlignment--) | Restituisce l'allineamento orizzontale del contenuto PDF originale nella pagina di risultato, il valore predefinito è AlignmentType.Left. Usa getHorizontalAlignment invece |
| [getDisplayDuration](#getDisplayDuration--) | Restituisce la durata di visualizzazione per le pagine. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Restituisce l'allineamento orizzontale del contenuto PDF originale nella pagina di risultato, il valore predefinito è AlignmentType.Left. |
| [getPageBoxSize](#getPageBoxSize-int-java.lang.String-) | <p> Restituisce la dimensione della casella specificata nel documento. </p> <hr> <pre> The following example demonstrates how to get media box of the 1st page: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); Rectangle rect = editor.getBoxSize(1, "media"); </pre> |
| [getPageRectangle](#getPageRectangle-com.aspose.pdf.Page-) | Restituisce la dimensione della pagina. |
| [getPageRotation](#getPageRotation-int-) | <p> Restituisce la rotazione della pagina specificata. </p> <hr> <pre> Il seguente esempio dimostra come ottenere la rotazione della pagina: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf(\"sample.pdf\"); int rotation = editor.getPageSize(1); System.out.println(\"Rotation of 1st page : \" + rotation + \" degrees\"); </pre> |
| [getPageRotations](#getPageRotations--) | <p> Ottiene la rotazione delle pagine, una tabella hash contiene il numero di pagina e il grado di rotazione, la chiave rappresenta il numero di pagina, il valore della chiave rappresenta la rotazione in gradi. </p> |
| [getPages](#getPages--) | <p> Restituisce il numero totale di pagine. </p> <hr> <pre> Il seguente esempio dimostra l'uso del metodo GetPages(): PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf(\"sample.pdf\"); System.out.println(\"Document has: \" + editor.GetPages()); </pre> |
| [getPageSize](#getPageSize--) | Ottiene la dimensione della pagina del file di output. |
| [getPageSize](#getPageSize-int-) | <p> Restituisce la dimensione della pagina specificata. </p> <hr> <pre> Il seguente esempio dimostra l'uso del metodo GetPageSize: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf(\"sample.pdf\"); PageSize size = editor.getPageSize(1); System.out.println(\"Size of 1st page : \" + size.getWidth() + \" x \" + size.getHeight()); </pre> |
| [getProcessPages](#getProcessPages--) | Ottiene i numeri di pagina da modificare. Per impostazione predefinita, ogni pagina verrebbe modificata. |
| [getRotation](#getRotation--) | Ottiene la rotazione delle pagine, la rotazione deve essere 0, 90, 180 o 270. Il valore predefinito è 0. |
| [getTransitionDuration](#getTransitionDuration--) | Ottiene la durata dell'effetto di transizione. |
| [getTransitionType](#getTransitionType--) | Ottiene lo stile di transizione da utilizzare quando si passa a questa pagina da un'altra durante una presentazione. |
| [getVerticalAlignment](#getVerticalAlignment--) | Ottiene l'allineamento verticale del contenuto PDF originale nella pagina risultante, il valore predefinito è VerticalAlignmentType.Bottom. Usa getVerticalAlignmentType invece. |
| [getVerticalAlignmentType](#getVerticalAlignmentType--) | Ottiene l'allineamento verticale del contenuto PDF originale nella pagina risultante, il valore predefinito è VerticalAlignmentType.Bottom. |
| [getZoom](#getZoom--) | Ottieni il coefficiente di zoom. Il valore 1.0 corrisponde al 100%. Il valore predefinito è 1.0. |
| [isBoxDefined](#isBoxDefined-com.aspose.pdf.Page-java.lang.String-) | Verifica se la casella è definita nella pagina. |
| [movePosition](#movePosition-float-float-) | <p> Sposta l'origine da (0, 0) al punto indicato. L'origine è in basso a sinistra e l'unità è il punto (1 pollice = 72 punti). </p> <hr> <pre> PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf(\"input.pdf\"); editor.movePosition(-100, 60); editor.save(\"moved.pdf\"); </pre> |
| [save](#save-java.io.OutputStream-) | <p> Salva il documento modificato in uno stream. </p> <hr> <pre> Il seguente esempio dimostra come salvare il documento PDF modificato in uno stream. PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf(\"sample.pdf\"); editor.setZoom ( 0.5f); editor.save(\"newdocument.pdf\"); </pre> |
| [save](#save-java.lang.String-) | <p> Salva il documento modificato in un file. </p> <hr> <pre> Il seguente esempio dimostra come salvare il documento PDF modificato PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf(\"sample.pdf\"); editor.setZoom ( 0.5f); editor.save(\"newdocument.pdf\"); </pre> |
| [setAlignment](#setAlignment-com.aspose.pdf.facades.AlignmentType-) | Imposta l'allineamento orizzontale del contenuto PDF originale nella pagina risultante, il valore predefinito è AlignmentType.Left. Usa setHorizontalAlignment invece. |
| [setDisplayDuration](#setDisplayDuration-int-) | Imposta la durata di visualizzazione per le pagine. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Imposta l'allineamento orizzontale del contenuto PDF originale nella pagina risultante, il valore predefinito è AlignmentType.Left. |
| [setPageRotations](#setPageRotations-java.util.Map-) | Imposta la rotazione delle pagine, una tabella hash contiene il numero di pagina e il grado di rotazione, la chiave rappresenta il numero di pagina, il valore della chiave rappresenta la rotazione in gradi. |
| [setPageSize](#setPageSize-com.aspose.pdf.PageSize-) | Imposta la dimensione della pagina del file di output. |
| [setProcessPages](#setProcessPages-int:A-) | Imposta i numeri di pagina da modificare. Per impostazione predefinita, ogni pagina verrebbe modificata. |
| [setRotation](#setRotation-int-) | Imposta la rotazione delle pagine, la rotazione deve essere 0, 90, 180 o 270. Il valore predefinito è 0. |
| [setTransitionDuration](#setTransitionDuration-int-) | Imposta la durata dell'effetto di transizione. |
| [setTransitionType](#setTransitionType-int-) | Imposta lo stile di transizione da utilizzare quando si passa a questa pagina da un'altra durante una presentazione. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.facades.VerticalAlignmentType-) | Imposta l'allineamento verticale del contenuto PDF originale nella pagina di risultato, il valore predefinito è VerticalAlignmentType.Bottom. Usa setVerticalAlignmentType invece |
| [setVerticalAlignmentType](#setVerticalAlignmentType-com.aspose.pdf.VerticalAlignment-) | Imposta l'allineamento verticale del contenuto PDF originale nella pagina di risultato, il valore predefinito è VerticalAlignmentType.Bottom. |
| [setZoom](#setZoom-float-) | <p> Imposta il coefficiente di zoom. Il valore 1.0 corrisponde al 100%. Il valore predefinito è 1.0. </p> |

### BLINDH {#BLINDH}
```
public static final int BLINDH
```

Tende verticali

### BLINDV {#BLINDV}
```
public static final int BLINDV
```

Tende verticali

### BTWIPE {#BTWIPE}
```
public static final int BTWIPE
```

Cancellazione dal basso verso l'alto

### DGLITTER {#DGLITTER}
```
public static final int DGLITTER
```

Scintillio diagonale

### DISSOLVE {#DISSOLVE}
```
public static final int DISSOLVE
```

La vecchia pagina si dissolve

### INBOX {#INBOX}
```
public static final int INBOX
```

Scatola verso l'interno

### LRGLITTER {#LRGLITTER}
```
public static final int LRGLITTER
```

Scintillio da sinistra a destra

### LRWIPE {#LRWIPE}
```
public static final int LRWIPE
```

Cancellazione da sinistra a destra

### OUTBOX {#OUTBOX}
```
public static final int OUTBOX
```

Scatola verso l'esterno

### RLWIPE {#RLWIPE}
```
public static final int RLWIPE
```

Cancellazione da destra a sinistra

### SPLITHIN {#SPLITHIN}
```
public static final int SPLITHIN
```

IN divisione orizzontale

### SPLITHOUT {#SPLITHOUT}
```
public static final int SPLITHOUT
```

Divisione orizzontale esterna

### SPLITVIN {#SPLITVIN}
```
public static final int SPLITVIN
```

Divisione verticale interna

### SPLITVOUT {#SPLITVOUT}
```
public static final int SPLITVOUT
```

Divisione verticale esterna

### TBGLITTER {#TBGLITTER}
```
public static final int TBGLITTER
```

Scintillio dall'alto al basso

### TBWIPE {#TBWIPE}
```
public static final int TBWIPE
```

Cancellazione dall'alto al basso

### PdfPageEditor {#PdfPageEditor--}
```
public PdfPageEditor()
```

Costruttore per la classe PdfPageEditor.

### PdfPageEditor {#PdfPageEditor-com.aspose.pdf.Document-}
Costruttore per la classe PdfPageEditor.

### applyChanges {#applyChanges--}
```
public void applyChanges()
```

Applica le modifiche apportate alle pagine del documento.

### getAlignment {#getAlignment--}
```
@Deprecated public AlignmentType getAlignment()
```

Restituisce l'allineamento orizzontale del contenuto PDF originale nella pagina di risultato, il valore predefinito è AlignmentType.Left. Usa getHorizontalAlignment invece

**Returns:**
Oggetto AlignmentType @see HorizontalAlignment

### getDisplayDuration {#getDisplayDuration--}
```
public int getDisplayDuration()
```

Restituisce la durata di visualizzazione per le pagine.

**Returns:**
valore int

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Restituisce l'allineamento orizzontale del contenuto PDF originale nella pagina di risultato, il valore predefinito è AlignmentType.Left.

**Returns:**
Elemento HorizontalAlignment @see HorizontalAlignment

### getPageBoxSize {#getPageBoxSize-int-java.lang.String-}
<p> Restituisce la dimensione della casella specificata nel documento. </p> <hr> <pre> The following example demonstrates how to get media box of the 1st page: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); Rectangle rect = editor.getBoxSize(1, "media"); </pre>

### getPageRectangle {#getPageRectangle-com.aspose.pdf.Page-}
Restituisce la dimensione della pagina.

### getPageRotation {#getPageRotation-int-}
```
public int getPageRotation(int page)
```

<p> Restituisce la rotazione della pagina specificata. </p> <hr> <pre> Il seguente esempio dimostra come ottenere la rotazione della pagina: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf(\"sample.pdf\"); int rotation = editor.getPageSize(1); System.out.println(\"Rotation of 1st page : \" + rotation + \" degrees\"); </pre>

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pagina |  | Indice della pagina. Le pagine del documento sono numerate a partire da 1. |

**Returns:**
Rotazione della pagina in gradi.

### getPageRotations {#getPageRotations--}
```
public Map < Integer , Integer > getPageRotations()
```

<p> Ottiene la rotazione delle pagine, una tabella hash contiene il numero di pagina e il grado di rotazione, la chiave rappresenta il numero di pagina, il valore della chiave rappresenta la rotazione in gradi. </p>

**Returns:**
Oggetto {@code Map<Integer, Integer>}

### getPages {#getPages--}
```
public int getPages()
```

<p> Restituisce il numero totale di pagine. </p> <hr> <pre> Il seguente esempio dimostra l'uso del metodo GetPages(): PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf(\"sample.pdf\"); System.out.println(\"Document has: \" + editor.GetPages()); </pre>

**Returns:**
Numero di pagine.

### getPageSize {#getPageSize--}
```
public PageSize getPageSize()
```

Ottiene la dimensione della pagina del file di output.

**Returns:**
Oggetto PageSize

### getPageSize {#getPageSize-int-}
```
public PageSize getPageSize(int page)
```

<p> Restituisce la dimensione della pagina specificata. </p> <hr> <pre> Il seguente esempio dimostra l'uso del metodo GetPageSize: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf(\"sample.pdf\"); PageSize size = editor.getPageSize(1); System.out.println(\"Size of 1st page : \" + size.getWidth() + \" x \" + size.getHeight()); </pre>

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pagina |  | Indice della pagina. Le pagine del documento sono numerate a partire da 1. |

**Returns:**
Il risultato è un'istanza di PageSize. Usa le proprietà Width e Height dell'oggetto restituito per ottenere la larghezza e l'altezza della pagina.

### getProcessPages {#getProcessPages--}
```
public int[] getProcessPages()
```

Ottiene i numeri di pagina da modificare. Per impostazione predefinita, ogni pagina verrebbe modificata.

**Returns:**
array di valori int

### getRotation {#getRotation--}
```
public int getRotation()
```

Ottiene la rotazione delle pagine, la rotazione deve essere 0, 90, 180 o 270. Il valore predefinito è 0.

**Returns:**
valore int

### getTransitionDuration {#getTransitionDuration--}
```
public int getTransitionDuration()
```

Ottiene la durata dell'effetto di transizione.

**Returns:**
valore int

### getTransitionType {#getTransitionType--}
```
public int getTransitionType()
```

Ottiene lo stile di transizione da utilizzare quando si passa a questa pagina da un'altra durante una presentazione.

**Returns:**
valore int

### getVerticalAlignment {#getVerticalAlignment--}
```
@Deprecated public VerticalAlignmentType getVerticalAlignment()
```

Ottiene l'allineamento verticale del contenuto PDF originale nella pagina risultante, il valore predefinito è VerticalAlignmentType.Bottom. Usa getVerticalAlignmentType invece.

**Returns:**
Oggetto VerticalAlignmentType

### getVerticalAlignmentType {#getVerticalAlignmentType--}
```
public VerticalAlignment getVerticalAlignmentType()
```

Ottiene l'allineamento verticale del contenuto PDF originale nella pagina risultante, il valore predefinito è VerticalAlignmentType.Bottom.

**Returns:**
Elemento VerticalAlignmentType @see VerticalAlignmentType

### getZoom {#getZoom--}
```
public float getZoom()
```

Ottieni il coefficiente di zoom. Il valore 1.0 corrisponde al 100%. Il valore predefinito è 1.0.

**Returns:**
valore float

### isBoxDefined {#isBoxDefined-com.aspose.pdf.Page-java.lang.String-}
Verifica se la casella è definita nella pagina.

### movePosition {#movePosition-float-float-}
```
public void movePosition(float moveX, float moveY)
```

<p> Sposta l'origine da (0, 0) al punto indicato. L'origine è in basso a sinistra e l'unità è il punto (1 pollice = 72 punti). </p> <hr> <pre> PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf(\"input.pdf\"); editor.movePosition(-100, 60); editor.save(\"moved.pdf\"); </pre>

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| moveX |  | Coordinata X. |
| moveY |  | Coordinata Y. |

### save {#save-java.io.OutputStream-}
<p> Salva il documento modificato in uno stream. </p> <hr> <pre> Il seguente esempio dimostra come salvare il documento PDF modificato in uno stream. PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf(\"sample.pdf\"); editor.setZoom ( 0.5f); editor.save(\"newdocument.pdf\"); </pre>

### save {#save-java.lang.String-}
<p> Salva il documento modificato in un file. </p> <hr> <pre> Il seguente esempio dimostra come salvare il documento PDF modificato PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf(\"sample.pdf\"); editor.setZoom ( 0.5f); editor.save(\"newdocument.pdf\"); </pre>

### setAlignment {#setAlignment-com.aspose.pdf.facades.AlignmentType-}
Imposta l'allineamento orizzontale del contenuto PDF originale nella pagina risultante, il valore predefinito è AlignmentType.Left. Usa setHorizontalAlignment invece.

### setDisplayDuration {#setDisplayDuration-int-}
```
public void setDisplayDuration(int value)
```

Imposta la durata di visualizzazione per le pagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Imposta l'allineamento orizzontale del contenuto PDF originale nella pagina risultante, il valore predefinito è AlignmentType.Left.

### setPageRotations {#setPageRotations-java.util.Map-}
Imposta la rotazione delle pagine, una tabella hash contiene il numero di pagina e il grado di rotazione, la chiave rappresenta il numero di pagina, il valore della chiave rappresenta la rotazione in gradi.

### setPageSize {#setPageSize-com.aspose.pdf.PageSize-}
Imposta la dimensione della pagina del file di output.

### setProcessPages {#setProcessPages-int:A-}
```
public void setProcessPages(int[] value)
```

Imposta i numeri di pagina da modificare. Per impostazione predefinita, ogni pagina verrebbe modificata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | array di valori int |

### setRotation {#setRotation-int-}
```
public void setRotation(int value)
```

Imposta la rotazione delle pagine, la rotazione deve essere 0, 90, 180 o 270. Il valore predefinito è 0.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setTransitionDuration {#setTransitionDuration-int-}
```
public void setTransitionDuration(int value)
```

Imposta la durata dell'effetto di transizione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setTransitionType {#setTransitionType-int-}
```
public void setTransitionType(int value)
```

Imposta lo stile di transizione da utilizzare quando si passa a questa pagina da un'altra durante una presentazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.facades.VerticalAlignmentType-}
Imposta l'allineamento verticale del contenuto PDF originale nella pagina di risultato, il valore predefinito è VerticalAlignmentType.Bottom. Usa setVerticalAlignmentType invece

### setVerticalAlignmentType {#setVerticalAlignmentType-com.aspose.pdf.VerticalAlignment-}
Imposta l'allineamento verticale del contenuto PDF originale nella pagina di risultato, il valore predefinito è VerticalAlignmentType.Bottom.

### setZoom {#setZoom-float-}
```
public void setZoom(float value)
```

<p> Imposta il coefficiente di zoom. Il valore 1.0 corrisponde al 100%. Il valore predefinito è 1.0. </p>

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore float <hr> <pre> Il seguente esempio dimostra come modificare lo zoom delle pagine del documento. PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); </pre> |
