---
title: "Annotation"
linktitle: "Annotation"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta un oggetto di annotazione."
type: docs
weight: 60
url: /it/java/com.aspose.pdf/annotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public abstract class Annotation extends BaseParagraph
```

Classe che rappresenta un oggetto di annotazione.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accetta un visitor per l'elaborazione dell'annotazione. |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | Aggiorna parametri e aspetto, secondo la trasformazione della matrice. |
| [createAnnotation](#createAnnotation-com.aspose.pdf.engine.data.IPdfObject-com.aspose.pdf.Page-) | Solo per uso interno |
| [flatten](#flatten--) | Posiziona i contenuti dell'annotazione direttamente sulla pagina, l'oggetto annotazione verrà rimosso. |
| [getActiveState](#getActiveState--) | Ottiene lo stato di aspetto corrente dell'annotazione. |
| [getAlignment](#getAlignment--) | ff / * / * Restituisce il nome dello stato "checked" in base ai nomi degli stati esistenti. / * / * / * |
| [getAnnotationType](#getAnnotationType--) | Ottiene il tipo di annotazione. |
| [getAppearance](#getAppearance--) | Ottiene il dizionario di aspetto dell'annotazione. |
| [getAssignedPageIndex](#getAssignedPageIndex--) | Ottiene l'indice della pagina (basato su 1) dove l'annotazione dovrebbe apparire. |
| [getBorder](#getBorder--) | Ottiene le caratteristiche del bordo dell'annotazione. {@code Border} |
| [getCharacteristics](#getCharacteristics--) | Ottiene le caratteristiche dell'annotazione. |
| [getColor](#getColor--) | Ottiene il colore dell'annotazione. |
| [getContents](#getContents--) | Ottiene il testo dell'annotazione. |
| [getEngineDict](#getEngineDict--) | Solo interno |
| [getEngineObj](#getEngineObj--) | Solo per uso interno |
| [getFlags](#getFlags--) | Ottiene i flag dell'annotazione. |
| [getFullName](#getFullName--) | Ottiene il nome completo qualificato dell'annotazione. |
| [getHeight](#getHeight--) | Ottiene l'altezza dell'annotazione. |
| [getHorizontalAlignment_Annotation_New](#getHorizontalAlignment_Annotation_New--) | Ottiene o imposta l'allineamento del testo per l'annotazione. |
| [getModified](#getModified--) | Ottiene data e ora in cui l'annotazione è stata modificata di recente. |
| [getModifiedInternal](#getModifiedInternal--) | Ottiene data e ora in cui l'annotazione è stata modificata di recente. |
| [getName](#getName--) | Ottiene il nome dell'annotazione nella pagina. |
| [getNormalAppearance](#getNormalAppearance--) | Ottiene l'aspetto normale. |
| [getPage](#getPage--) | Ottiene l'oggetto pagina con cui questa annotazione è associata. |
| [getPageIndex](#getPageIndex--) | Ottiene l'indice della pagina che contiene l'annotazione. |
| [getPageIndex](#getPageIndex-com.aspose.pdf.Annotation-) | Ottiene l'indice della pagina che contiene l'annotazione. |
| [getPdfActions](#getPdfActions--) | Ottiene l'elenco delle azioni dell'annotazione. |
| [getRect](#getRect--) | Ottiene il rettangolo dell'annotazione. |
| [getRectangle](#getRectangle-boolean-) | Restituisce il rettangolo dell'annotazione tenendo conto della rotazione della pagina. |
| [getStates](#getStates--) | Ottiene il dizionario di aspetto dell'annotazione. |
| [getTextHorizontalAlignment](#getTextHorizontalAlignment--) | Ottiene l'allineamento del testo per l'annotazione. |
| [getWidth](#getWidth--) | Ottiene la larghezza dell'annotazione. |
| [initialize](#initialize-com.aspose.pdf.IDocument-) | Inizializzazione dell'istanza |
| [isUpdateAppearanceOnConvert](#isUpdateAppearanceOnConvert--) | Se vero, l'aspetto dell'annotazione verrà aggiornato prima di convertire il documento PDF in immagine. Questo consente di convertire correttamente i campi ma probabilmente richiede più tempo. |
| [isUseFontSubset](#isUseFontSubset--) | Se questa proprietà è impostata su vero, i caratteri verranno aggiunti al documento come sottoinsiemi. Il valore predefinito è vero. |
| [setActiveState](#setActiveState-java.lang.String-) | Imposta lo stato attuale dell'aspetto dell'annotazione. |
| [setAlignment](#setAlignment-com.aspose.pdf.TextAlignment-) | Allineamento dell'annotazione. Questa proprietà è obsoleta. Utilizzare getHorizontalAlignment_Annotation_New al suo posto. |
| [setAssignedPageIndex](#setAssignedPageIndex-com.aspose.ms.System.Nullable-) | Imposta l'indice della pagina (basato su 1) dove l'annotazione deve apparire. |
| [setBorder](#setBorder-com.aspose.pdf.Border-) | Imposta le caratteristiche del bordo dell'annotazione. {@code Border} |
| [setColor](#setColor-com.aspose.pdf.Color-) | Imposta il colore dell'annotazione. |
| [setContents](#setContents-java.lang.String-) | Imposta il testo dell'annotazione. |
| [setFlags](#setFlags-int-) | Imposta i flag dell'annotazione. |
| [setHeight](#setHeight-double-) | Imposta l'altezza dell'annotazione. |
| [setHorizontalAlignment_Annotation_New](#setHorizontalAlignment_Annotation_New-com.aspose.pdf.HorizontalAlignment-) | Ottiene o imposta l'allineamento del testo per l'annotazione. |
| [setModified](#setModified-java.util.Date-) | Imposta data e ora in cui l'annotazione è stata modificata di recente. |
| [setModifiedInternal](#setModifiedInternal-com.aspose.ms.System.DateTime-) | Imposta data e ora in cui l'annotazione è stata modificata di recente. |
| [setName](#setName-java.lang.String-) | Imposta il nome dell'annotazione nella pagina. |
| [setRect](#setRect-com.aspose.pdf.Rectangle-) | Imposta il rettangolo dell'annotazione. |
| [setTextHorizontalAlignment](#setTextHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Imposta l'allineamento del testo per l'annotazione. |
| [setUpdateAppearanceOnConvert](#setUpdateAppearanceOnConvert-boolean-) | Se vero, l'aspetto dell'annotazione verrà aggiornato prima di convertire il documento PDF in immagine. Questo consente di convertire correttamente i campi ma probabilmente richiede più tempo. |
| [setUseFontSubset](#setUseFontSubset-boolean-) | Se questa proprietà è impostata su vero, i caratteri verranno aggiunti al documento come sottoinsiemi. Il valore predefinito è vero. |
| [setWidth](#setWidth-double-) | Imposta la larghezza dell'annotazione. |

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accetta un visitor per l'elaborazione dell'annotazione.

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
Aggiorna parametri e aspetto, secondo la trasformazione della matrice.

### createAnnotation {#createAnnotation-com.aspose.pdf.engine.data.IPdfObject-com.aspose.pdf.Page-}
Solo per uso interno

### flatten {#flatten--}
```
public void flatten()
```

Posiziona i contenuti dell'annotazione direttamente sulla pagina, l'oggetto annotazione verrà rimosso.

### getActiveState {#getActiveState--}
```
public String getActiveState()
```

Ottiene lo stato di aspetto corrente dell'annotazione.

**Returns:**
valore String

### getAlignment {#getAlignment--}
```
@Deprecated public TextAlignment getAlignment()
```

ff / * / * Restituisce il nome dello stato "checked" in base ai nomi degli stati esistenti. / * / * / *

**Returns:**
Valore stringa /

### getAnnotationType {#getAnnotationType--}
```
public abstract AnnotationType getAnnotationType()
```

Ottiene il tipo di annotazione.

**Returns:**
valore int @see AnnotationType

### getAppearance {#getAppearance--}
```
public AppearanceDictionary getAppearance()
```

Ottiene il dizionario di aspetto dell'annotazione.

**Returns:**
oggetto AppearanceDictionary

### getAssignedPageIndex {#getAssignedPageIndex--}
```
public final com.aspose.ms.System.Nullable< Integer > getAssignedPageIndex()
```

Ottiene l'indice della pagina (basato su 1) dove l'annotazione dovrebbe apparire.

**Returns:**
l'indice della pagina (basato su 1) dove l'annotazione deve apparire.

### getBorder {#getBorder--}
```
public Border getBorder()
```

Ottiene le caratteristiche del bordo dell'annotazione. {@code Border}

**Returns:**
oggetto Border

### getCharacteristics {#getCharacteristics--}
```
public Characteristics getCharacteristics()
```

Ottiene le caratteristiche dell'annotazione.

**Returns:**
oggetto Characteristics

### getColor {#getColor--}
```
public Color getColor()
```

Ottiene il colore dell'annotazione.

**Returns:**
oggetto Color

### getContents {#getContents--}
```
public String getContents()
```

Ottiene il testo dell'annotazione.

**Returns:**
valore String

### getEngineDict {#getEngineDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getEngineDict()
```

Solo interno

**Returns:**
oggetto IPdfDictionary

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

Solo per uso interno

**Returns:**
Oggetto interno

### getFlags {#getFlags--}
```
public int getFlags()
```

Ottiene i flag dell'annotazione.

**Returns:**
Flag dell'annotazione @see AnnotationFlags

### getFullName {#getFullName--}
```
public String getFullName()
```

Ottiene il nome completo qualificato dell'annotazione.

**Returns:**
valore String

### getHeight {#getHeight--}
```
public double getHeight()
```

Ottiene l'altezza dell'annotazione.

**Returns:**
altezza dell'annotazione

### getHorizontalAlignment_Annotation_New {#getHorizontalAlignment_Annotation_New--}
```
@Deprecated public final HorizontalAlignment getHorizontalAlignment_Annotation_New()
```

Ottiene o imposta l'allineamento del testo per l'annotazione.

**Returns:**
allineamento del testo per l'annotazione. @see HorizontalAlignment @deprecated Usa la proprietà TextHorizontalAlignment

### getModified {#getModified--}
```
public Date getModified()
```

Ottiene data e ora in cui l'annotazione è stata modificata di recente.

**Returns:**
data e ora in cui l'annotazione è stata modificata di recente.

### getModifiedInternal {#getModifiedInternal--}
```
public com.aspose.ms.System.DateTime getModifiedInternal()
```

Ottiene data e ora in cui l'annotazione è stata modificata di recente.

**Returns:**
oggetto DateTime

### getName {#getName--}
```
public String getName()
```

Ottiene il nome dell'annotazione nella pagina.

**Returns:**
valore String

### getNormalAppearance {#getNormalAppearance--}
```
public XForm getNormalAppearance()
```

Ottiene l'aspetto normale.

**Returns:**
oggetto XForm

### getPage {#getPage--}
```
public Page getPage()
```

Ottiene l'oggetto pagina con cui questa annotazione è associata.

**Returns:**
oggetto Page

### getPageIndex {#getPageIndex--}
```
public int getPageIndex()
```

Ottiene l'indice della pagina che contiene l'annotazione.

**Returns:**
valore int

### getPageIndex {#getPageIndex-com.aspose.pdf.Annotation-}
Ottiene l'indice della pagina che contiene l'annotazione.

**Returns:**
valore int

### getPdfActions {#getPdfActions--}
```
public PdfActionCollection getPdfActions()
```

Ottiene l'elenco delle azioni dell'annotazione.

**Returns:**
istanza PdfActionCollection

### getRect {#getRect--}
```
public Rectangle getRect()
```

Ottiene il rettangolo dell'annotazione.

**Returns:**
oggetto Rectangle

### getRectangle {#getRectangle-boolean-}
```
public Rectangle getRectangle(boolean considerRotation)
```

Restituisce il rettangolo dell'annotazione tenendo conto della rotazione della pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| considerRotation |  | Se vero, la rotazione della pagina viene presa in considerazione. |

**Returns:**
oggetto Rectangle

### getStates {#getStates--}
```
public AppearanceDictionary getStates()
```

Ottiene il dizionario di aspetto dell'annotazione.

**Returns:**
oggetto AppearanceDictionary

### getTextHorizontalAlignment {#getTextHorizontalAlignment--}
```
public HorizontalAlignment getTextHorizontalAlignment()
```

Ottiene l'allineamento del testo per l'annotazione.

**Returns:**
allineamento del testo per l'annotazione. @see HorizontalAlignment

### getWidth {#getWidth--}
```
public double getWidth()
```

Ottiene la larghezza dell'annotazione.

**Returns:**
valore double, larghezza dell'annotazione.

### initialize {#initialize-com.aspose.pdf.IDocument-}
Inizializzazione dell'istanza

### isUpdateAppearanceOnConvert {#isUpdateAppearanceOnConvert--}
```
public static boolean isUpdateAppearanceOnConvert()
```

Se vero, l'aspetto dell'annotazione verrà aggiornato prima di convertire il documento PDF in immagine. Questo consente di convertire correttamente i campi ma probabilmente richiede più tempo.

**Returns:**
valore booleano

### isUseFontSubset {#isUseFontSubset--}
```
public static boolean isUseFontSubset()
```

Se questa proprietà è impostata su vero, i caratteri verranno aggiunti al documento come sottoinsiemi. Il valore predefinito è vero.

**Returns:**
valore booleano

### setActiveState {#setActiveState-java.lang.String-}
Imposta lo stato attuale dell'aspetto dell'annotazione.

### setAlignment {#setAlignment-com.aspose.pdf.TextAlignment-}
Allineamento dell'annotazione. Questa proprietà è obsoleta. Utilizzare getHorizontalAlignment_Annotation_New al suo posto.

### setAssignedPageIndex {#setAssignedPageIndex-com.aspose.ms.System.Nullable-}
Imposta l'indice della pagina (basato su 1) dove l'annotazione deve apparire.

### setBorder {#setBorder-com.aspose.pdf.Border-}
Imposta le caratteristiche del bordo dell'annotazione. {@code Border}

### setColor {#setColor-com.aspose.pdf.Color-}
Imposta il colore dell'annotazione.

### setContents {#setContents-java.lang.String-}
Imposta il testo dell'annotazione.

### setFlags {#setFlags-int-}
```
public void setFlags(int value)
```

Imposta i flag dell'annotazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | flag dell'annotazione @see AnnotationFlags |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Imposta l'altezza dell'annotazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | altezza dell'annotazione |

### setHorizontalAlignment_Annotation_New {#setHorizontalAlignment_Annotation_New-com.aspose.pdf.HorizontalAlignment-}
Ottiene o imposta l'allineamento del testo per l'annotazione.

### setModified {#setModified-java.util.Date-}
Imposta data e ora in cui l'annotazione è stata modificata di recente.

### setModifiedInternal {#setModifiedInternal-com.aspose.ms.System.DateTime-}
Imposta data e ora in cui l'annotazione è stata modificata di recente.

### setName {#setName-java.lang.String-}
Imposta il nome dell'annotazione nella pagina.

### setRect {#setRect-com.aspose.pdf.Rectangle-}
Imposta il rettangolo dell'annotazione.

### setTextHorizontalAlignment {#setTextHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Imposta l'allineamento del testo per l'annotazione.

### setUpdateAppearanceOnConvert {#setUpdateAppearanceOnConvert-boolean-}
```
public static void setUpdateAppearanceOnConvert(boolean value)
```

Se vero, l'aspetto dell'annotazione verrà aggiornato prima di convertire il documento PDF in immagine. Questo consente di convertire correttamente i campi ma probabilmente richiede più tempo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setUseFontSubset {#setUseFontSubset-boolean-}
```
public static void setUseFontSubset(boolean value)
```

Se questa proprietà è impostata su vero, i caratteri verranno aggiunti al documento come sottoinsiemi. Il valore predefinito è vero.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Imposta la larghezza dell'annotazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | larghezza dell'annotazione. |
