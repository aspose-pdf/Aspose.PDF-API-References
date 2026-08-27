---
title: "Artefatto"
linktitle: "Artefatto"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta l'oggetto PDF Artifact."
type: docs
weight: 190
url: /it/java/com.aspose.pdf/artifact/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Artifact

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public class Artifact extends Object implements com.aspose.ms.System.IDisposable, Closeable
```

Classe che rappresenta l'oggetto PDF Artifact.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Artifact](#Artifact-com.aspose.pdf.Artifact.ArtifactType-com.aspose.pdf.Artifact.ArtifactSubtype-) | Costruttore dell'artefatto con tipo e sottotipo specificati |
| [Artifact](#Artifact-com.aspose.pdf.ArtifactCollection-com.aspose.pdf.Artifact.ArtifactContext-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.engine.data.IPdfDictionary-) | Questo costruttore è usato quando l'artefatto viene letto dalla pagina. |
| [Artifact](#Artifact-java.lang.String-java.lang.String-) | Costruttore dell'artefatto con tipo e sottotipo specificati |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [beginUpdates](#beginUpdates--) | Avvia aggiornamenti cancellati. Usa questa funzionalità se devi apportare diverse modifiche allo stesso artefatto per migliorare le prestazioni. Di solito gli operatori dell'artefatto vengono modificati ogni volta che una proprietà dell'artefatto è cambiata. Ciò provoca la modifica del contenuto della pagina ogni volta che l'artefatto è cambiato. Per evitare questo effetto, inserisci tutti gli aggiornamenti dell'artefatto tra le chiamate StartUpdates/SaveUpdates. Questo consente di modificare il contenuto della pagina una sola volta. Artifact art = doc.getPages().get_Item(1).getArtifacts().get_Item(1); art.beginUpdates(); art.setOpacity ( 0.3f); art.setPosition ( new Point(10,10)); art.setRotation (30); art.saveUpdates(); |
| [close](#close--) | Chiude tutte le risorse utilizzate da questo documento. |
| [dispose](#dispose--) | Elimina l'artefatto. Questo metodo è obsoleto, usa close() invece. |
| [getArtifactHorizontalAlignment](#getArtifactHorizontalAlignment--) | Restituisce l'allineamento orizzontale dell'artefatto. Se la posizione è specificata esplicitamente (nella proprietà Position) questo valore è ignorato. |
| [getArtifactVerticalAlignment](#getArtifactVerticalAlignment--) | Restituisce l'allineamento verticale dell'artefatto. Se la posizione è specificata esplicitamente (nella proprietà Position) questo valore è ignorato. |
| [getBottomMargin](#getBottomMargin--) | Restituisce il margine inferiore dell'artefatto. Se la posizione è specificata esplicitamente (nella proprietà Position) questo valore è ignorato. |
| [getContents](#getContents--) | Restituisce la collezione degli operatori interni dell'artefatto. |
| [getCustomSubtype](#getCustomSubtype--) | Restituisce il nome del sottotipo dell'artefatto. Può essere usato se il sottotipo dell'artefatto non è standard. |
| [getCustomType](#getCustomType--) | Restituisce il nome del tipo dell'artefatto. Può essere usato se il tipo dell'artefatto non è standard. |
| [getForm](#getForm--) | Restituisce XForm dell'artefatto (se XForm è usato). |
| [getImage](#getImage--) | Restituisce l'immagine dell'artefatto (se presente). |
| [getLeftMargin](#getLeftMargin--) | Restituisce il margine sinistro dell'artefatto. Se la posizione è specificata esplicitamente (nella proprietà Position) questo valore è ignorato. |
| [getLines](#getLines--) | Righe dell'artefatto di testo multilinea. |
| [getOpacity](#getOpacity--) | Restituisce l'opacità dell'artefatto. I valori possibili sono nell'intervallo 0..1. |
| [getPosition](#getPosition--) | Restituisce la posizione dell'artefatto. Se questa proprietà è specificata, i margini e gli allineamenti sono ignorati. |
| [getRectangle](#getRectangle--) | Restituisce il rettangolo dell'artefatto. |
| [getRightMargin](#getRightMargin--) | Restituisce il margine destro dell'artefatto. Se la posizione è specificata esplicitamente (nella proprietà Position) questo valore è ignorato. |
| [getRotation](#getRotation--) | Restituisce l'angolo di rotazione dell'artefatto. |
| [getSubtype](#getSubtype--) | Restituisce il sottotipo dell'artefatto. Se l'artefatto ha un sottotipo non standard, il nome del sottotipo può essere letto tramite CustomSubtype. |
| [getText](#getText--) | Restituisce il testo dell'artefatto. |
| [getTextState](#getTextState--) | Stato del testo per il testo dell'artefatto. |
| [getTopMargin](#getTopMargin--) | Ottiene il margine superiore dell'artefatto. Se la posizione è specificata esplicitamente (nella proprietà Position) questo valore è ignorato. |
| [getType](#getType--) | Ottiene il tipo di artefatto. |
| [getValue](#getValue-java.lang.String-) | Ottiene il valore personalizzato dell'artefatto. |
| [isBackground](#isBackground--) | Se vero, l'artefatto è posizionato dietro il contenuto della pagina. |
| [removeValue](#removeValue-java.lang.String-) | Rimuove il valore personalizzato dall'artefatto. |
| [saveUpdates](#saveUpdates--) | Salva tutti gli aggiornamenti nell'artefatto effettuati dopo la chiamata a BeginUpdates(). |
| [setArtifactHorizontalAlignment](#setArtifactHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Ottiene l'allineamento orizzontale dell'artefatto. |
| [setArtifactVerticalAlignment](#setArtifactVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Imposta l'allineamento verticale dell'artefatto. |
| [setBackground](#setBackground-boolean-) | Se vero, l'artefatto è posizionato dietro il contenuto della pagina. |
| [setBottomMargin](#setBottomMargin-double-) | Imposta il margine inferiore dell'artefatto. |
| [setCustomSubtype](#setCustomSubtype-java.lang.String-) |  |
| [setCustomType](#setCustomType-java.lang.String-) | Imposta il nome del tipo di artefatto. Può essere usato se il tipo di artefatto non è standard. |
| [setImage](#setImage-java.io.InputStream-) | Imposta l'immagine dell'artefatto. |
| [setImage](#setImage-java.lang.String-) | Imposta l'immagine dell'artefatto. |
| [setLeftMargin](#setLeftMargin-double-) | Imposta il margine sinistro dell'artefatto. Se la posizione è specificata esplicitamente (nella proprietà Position) questo valore è ignorato. |
| [setLinesAndState](#setLinesAndState-java.lang.String:A-com.aspose.pdf.TextState-) | Imposta il testo e le proprietà del testo dell'artefatto. Consente di specificare più righe. |
| [setOpacity](#setOpacity-double-) | Imposta l'opacità dell'artefatto. I valori possibili sono nell'intervallo 0..1. |
| [setPageNumberReplacementString](#setPageNumberReplacementString-java.lang.String-) | Imposta quale stringa sarà sostituita con il numero di pagina. Il valore predefinito è #. |
| [setPdfPage](#setPdfPage-com.aspose.pdf.Page-) | Imposta la pagina PDF che viene posizionata sulla pagina del documento come artefatto. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Imposta la posizione dell'artefatto. |
| [setRightMargin](#setRightMargin-double-) | Imposta il margine destro dell'artefatto. |
| [setRotation](#setRotation-double-) | Imposta l'angolo di rotazione dell'artefatto. |
| [setSubtype](#setSubtype-com.aspose.pdf.Artifact.ArtifactSubtype-) | Imposta il sottotipo dell'artefatto. |
| [setText](#setText-com.aspose.pdf.facades.FormattedText-) | Imposta il testo dell'artefatto. |
| [setText](#setText-java.lang.String-) | Imposta il testo dell'artefatto. |
| [setTextAndState](#setTextAndState-java.lang.String-com.aspose.pdf.TextState-) | Imposta il testo e le proprietà del testo dell'artefatto. |
| [setTextState](#setTextState-com.aspose.pdf.TextState-) | Stato del testo per il testo dell'artefatto. |
| [setTopMargin](#setTopMargin-double-) | Imposta il margine superiore dell'artefatto. |
| [setType](#setType-com.aspose.pdf.Artifact.ArtifactType-) | Imposta il tipo di artefatto. |
| [setValue](#setValue-java.lang.String-java.lang.String-) | Imposta il valore personalizzato dell'artifact. |

### Artifact {#Artifact-com.aspose.pdf.Artifact.ArtifactType-com.aspose.pdf.Artifact.ArtifactSubtype-}
Costruttore dell'artefatto con tipo e sottotipo specificati

### Artifact {#Artifact-com.aspose.pdf.ArtifactCollection-com.aspose.pdf.Artifact.ArtifactContext-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.engine.data.IPdfDictionary-}
Questo costruttore è usato quando l'artefatto viene letto dalla pagina.

### Artifact {#Artifact-java.lang.String-java.lang.String-}
Costruttore dell'artefatto con tipo e sottotipo specificati

### beginUpdates {#beginUpdates--}
```
public void beginUpdates()
```

Avvia aggiornamenti cancellati. Usa questa funzionalità se devi apportare diverse modifiche allo stesso artefatto per migliorare le prestazioni. Di solito gli operatori dell'artefatto vengono modificati ogni volta che una proprietà dell'artefatto è cambiata. Ciò provoca la modifica del contenuto della pagina ogni volta che l'artefatto è cambiato. Per evitare questo effetto, inserisci tutti gli aggiornamenti dell'artefatto tra le chiamate StartUpdates/SaveUpdates. Questo consente di modificare il contenuto della pagina una sola volta. Artifact art = doc.getPages().get_Item(1).getArtifacts().get_Item(1); art.beginUpdates(); art.setOpacity ( 0.3f); art.setPosition ( new Point(10,10)); art.setRotation (30); art.saveUpdates();

### close {#close--}
```
public void close()
```

Chiude tutte le risorse utilizzate da questo documento.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Elimina l'artefatto. Questo metodo è obsoleto, usa close() invece.

### getArtifactHorizontalAlignment {#getArtifactHorizontalAlignment--}
```
public HorizontalAlignment getArtifactHorizontalAlignment()
```

Restituisce l'allineamento orizzontale dell'artefatto. Se la posizione è specificata esplicitamente (nella proprietà Position) questo valore è ignorato.

**Returns:**
Valore HorizontalAlignment @see HorizontalAlignment

### getArtifactVerticalAlignment {#getArtifactVerticalAlignment--}
```
public VerticalAlignment getArtifactVerticalAlignment()
```

Restituisce l'allineamento verticale dell'artefatto. Se la posizione è specificata esplicitamente (nella proprietà Position) questo valore è ignorato.

**Returns:**
Valore di VerticalAlignment. @see VerticalAlignment

### getBottomMargin {#getBottomMargin--}
```
public double getBottomMargin()
```

Restituisce il margine inferiore dell'artefatto. Se la posizione è specificata esplicitamente (nella proprietà Position) questo valore è ignorato.

**Returns:**
margine inferiore.

### getContents {#getContents--}
```
public List < Operator > getContents()
```

Restituisce la collezione degli operatori interni dell'artefatto.

**Returns:**
Elenca gli operatori interni dell'artifact.

### getCustomSubtype {#getCustomSubtype--}
```
public String getCustomSubtype()
```

Restituisce il nome del sottotipo dell'artefatto. Può essere usato se il sottotipo dell'artefatto non è standard.

**Returns:**
valore String

### getCustomType {#getCustomType--}
```
public String getCustomType()
```

Restituisce il nome del tipo dell'artefatto. Può essere usato se il tipo dell'artefatto non è standard.

**Returns:**
Nome dell'artifact String

### getForm {#getForm--}
```
public XForm getForm()
```

Restituisce XForm dell'artefatto (se XForm è usato).

**Returns:**
oggetto XForm

### getImage {#getImage--}
```
public XImage getImage()
```

Restituisce l'immagine dell'artefatto (se presente).

**Returns:**
oggetto XImage

### getLeftMargin {#getLeftMargin--}
```
public double getLeftMargin()
```

Restituisce il margine sinistro dell'artefatto. Se la posizione è specificata esplicitamente (nella proprietà Position) questo valore è ignorato.

**Returns:**
margine sinistro dell'artifact.

### getLines {#getLines--}
```
public final List < String > getLines()
```

Righe dell'artefatto di testo multilinea.

**Returns:**
Elenco di Strings

### getOpacity {#getOpacity--}
```
public double getOpacity()
```

Restituisce l'opacità dell'artefatto. I valori possibili sono nell'intervallo 0..1.

**Returns:**
opacità dell'artifact.

### getPosition {#getPosition--}
```
public Point getPosition()
```

Restituisce la posizione dell'artefatto. Se questa proprietà è specificata, i margini e gli allineamenti sono ignorati.

**Returns:**
posizione dell'artifact.

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Restituisce il rettangolo dell'artefatto.

**Returns:**
oggetto Rectangle

### getRightMargin {#getRightMargin--}
```
public double getRightMargin()
```

Restituisce il margine destro dell'artefatto. Se la posizione è specificata esplicitamente (nella proprietà Position) questo valore è ignorato.

**Returns:**
margine destro dell'artifact.

### getRotation {#getRotation--}
```
public double getRotation()
```

Restituisce l'angolo di rotazione dell'artefatto.

**Returns:**
angolo di rotazione dell'artifact.

### getSubtype {#getSubtype--}
```
public Artifact.ArtifactSubtype getSubtype()
```

Restituisce il sottotipo dell'artefatto. Se l'artefatto ha un sottotipo non standard, il nome del sottotipo può essere letto tramite CustomSubtype.

**Returns:**
sottotipo dell'artifact. @see ArtifactSubtype

### getText {#getText--}
```
public String getText()
```

Restituisce il testo dell'artefatto.

**Returns:**
valore String

### getTextState {#getTextState--}
```
public final TextState getTextState()
```

Stato del testo per il testo dell'artefatto.

**Returns:**
istanza TextState

### getTopMargin {#getTopMargin--}
```
public double getTopMargin()
```

Ottiene il margine superiore dell'artefatto. Se la posizione è specificata esplicitamente (nella proprietà Position) questo valore è ignorato.

**Returns:**
margine superiore dell'artifact.

### getType {#getType--}
```
public Artifact.ArtifactType getType()
```

Ottiene il tipo di artefatto.

**Returns:**
valore del tipo di artifact. @see ArtifactType

### getValue {#getValue-java.lang.String-}
Ottiene il valore personalizzato dell'artefatto.

### isBackground {#isBackground--}
```
public boolean isBackground()
```

Se vero, l'artefatto è posizionato dietro il contenuto della pagina.

**Returns:**
valore booleano

### removeValue {#removeValue-java.lang.String-}
Rimuove il valore personalizzato dall'artefatto.

### saveUpdates {#saveUpdates--}
```
public void saveUpdates()
```

Salva tutti gli aggiornamenti nell'artefatto effettuati dopo la chiamata a BeginUpdates().

### setArtifactHorizontalAlignment {#setArtifactHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Ottiene l'allineamento orizzontale dell'artefatto.

### setArtifactVerticalAlignment {#setArtifactVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Imposta l'allineamento verticale dell'artefatto.

### setBackground {#setBackground-boolean-}
```
public void setBackground(boolean value)
```

Se vero, l'artefatto è posizionato dietro il contenuto della pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setBottomMargin {#setBottomMargin-double-}
```
public void setBottomMargin(double value)
```

Imposta il margine inferiore dell'artefatto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | margine inferiore. |

### setCustomSubtype {#setCustomSubtype-java.lang.String-}


### setCustomType {#setCustomType-java.lang.String-}
Imposta il nome del tipo di artefatto. Può essere usato se il tipo di artefatto non è standard.

### setImage {#setImage-java.io.InputStream-}
Imposta l'immagine dell'artefatto.

### setImage {#setImage-java.lang.String-}
Imposta l'immagine dell'artefatto.

### setLeftMargin {#setLeftMargin-double-}
```
public void setLeftMargin(double value)
```

Imposta il margine sinistro dell'artefatto. Se la posizione è specificata esplicitamente (nella proprietà Position) questo valore è ignorato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | margine sinistro dell'artifact. |

### setLinesAndState {#setLinesAndState-java.lang.String:A-com.aspose.pdf.TextState-}
Imposta il testo e le proprietà del testo dell'artefatto. Consente di specificare più righe.

### setOpacity {#setOpacity-double-}
```
public void setOpacity(double value)
```

Imposta l'opacità dell'artefatto. I valori possibili sono nell'intervallo 0..1.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | opacità dell'artifact. |

### setPageNumberReplacementString {#setPageNumberReplacementString-java.lang.String-}
Imposta quale stringa sarà sostituita con il numero di pagina. Il valore predefinito è #.

### setPdfPage {#setPdfPage-com.aspose.pdf.Page-}
Imposta la pagina PDF che viene posizionata sulla pagina del documento come artefatto.

### setPosition {#setPosition-com.aspose.pdf.Point-}
Imposta la posizione dell'artefatto.

### setRightMargin {#setRightMargin-double-}
```
public void setRightMargin(double value)
```

Imposta il margine destro dell'artefatto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | margine destro dell'artifact. |

### setRotation {#setRotation-double-}
```
public void setRotation(double value)
```

Imposta l'angolo di rotazione dell'artefatto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | angolo di rotazione dell'artifact. |

### setSubtype {#setSubtype-com.aspose.pdf.Artifact.ArtifactSubtype-}
Imposta il sottotipo dell'artefatto.

### setText {#setText-com.aspose.pdf.facades.FormattedText-}
Imposta il testo dell'artefatto.

### setText {#setText-java.lang.String-}
Imposta il testo dell'artefatto.

### setTextAndState {#setTextAndState-java.lang.String-com.aspose.pdf.TextState-}
Imposta il testo e le proprietà del testo dell'artefatto.

### setTextState {#setTextState-com.aspose.pdf.TextState-}
Stato del testo per il testo dell'artefatto.

### setTopMargin {#setTopMargin-double-}
```
public void setTopMargin(double value)
```

Imposta il margine superiore dell'artefatto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | margine superiore dell'artifact. |

### setType {#setType-com.aspose.pdf.Artifact.ArtifactType-}
Imposta il tipo di artefatto.

### setValue {#setValue-java.lang.String-java.lang.String-}
Imposta il valore personalizzato dell'artifact.
