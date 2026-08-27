---
title: "MarkupAnnotation"
linktitle: "MarkupAnnotation"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe astratta che rappresenta un'annotazione di markup."
type: docs
weight: 2870
url: /it/java/com.aspose.pdf/markupannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public abstract class MarkupAnnotation extends Annotation implements com.aspose.pdf.engine.ITitledAnnotation
```

Classe astratta che rappresenta un'annotazione di markup.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MarkupAnnotation](#MarkupAnnotation--) | Costruttore |
| [MarkupAnnotation](#MarkupAnnotation-com.aspose.pdf.IDocument-) | Costruttore |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [clearState](#clearState--) | Cancella lo stato e il modello di stato per l'annotazione. Per esempio, cancella lo stato di revisione per un'annotazione. Nota, lo stato è memorizzato in altre annotazioni di testo che hanno le chiavi state e statemodel. |
| [getCreationDate](#getCreationDate--) | Restituisce data e ora in cui l'annotazione è stata creata. |
| [getInReplyTo](#getInReplyTo--) | Un riferimento all'annotazione a cui questa annotazione è "in risposta a". Entrambe le annotazioni devono trovarsi nella stessa pagina del documento. |
| [getOpacity](#getOpacity--) | Restituisce il valore di opacità costante da utilizzare nel disegno dell'annotazione. |
| [getPopup](#getPopup--) | Annotazione pop-up per inserire o modificare il testo associato a questa annotazione. |
| [getReplyType](#getReplyType--) | Una stringa che specifica la relazione (il "tipo di risposta") tra questa annotazione e quella specificata da InReplyTo. |
| [getRichText](#getRichText--) | Restituisce una stringa di testo formattato da visualizzare nella finestra pop-up quando l'annotazione viene aperta. |
| [getRichText](#getRichText-com.aspose.pdf.engine.data.IPdfDictionary-) | Restituisce una stringa di testo formattato da visualizzare nella finestra pop-up quando l'annotazione viene aperta. |
| [getState](#getState--) | Restituisce lo stato dell'annotazione. Nota, lo stato è memorizzato in altre annotazioni di testo che hanno le chiavi state e statemodel. |
| [getStateModel](#getStateModel--) | Restituisce il modello di stato dell'annotazione. Nota, lo stato è memorizzato in altre annotazioni di testo che hanno le chiavi state e statemodel. |
| [getSubject](#getSubject--) | Restituisce il testo che rappresenta la descrizione dell'oggetto. |
| [getTitle](#getTitle--) | Restituisce un'etichetta di testo che deve essere visualizzata nella barra del titolo della finestra pop-up dell'annotazione quando è aperta e attiva. Questa voce deve identificare l'utente che ha aggiunto l'annotazione. |
| [setCreationDate](#setCreationDate-java.util.Date-) | Restituisce data e ora in cui l'annotazione è stata creata. |
| [setInReplyTo](#setInReplyTo-com.aspose.pdf.Annotation-) | Un riferimento all'annotazione a cui questa annotazione è "in risposta a". Entrambe le annotazioni devono trovarsi nella stessa pagina del documento. |
| [setMarkedState](#setMarkedState-boolean-) | Imposta lo stato Contrassegnato e Non contrassegnato per l'annotazione. Nota, lo stato è memorizzato in altre annotazioni di testo che hanno le chiavi state e statemodel. |
| [setOpacity](#setOpacity-double-) | Imposta il valore di opacità costante da utilizzare nel disegno dell'annotazione. |
| [setPopup](#setPopup-com.aspose.pdf.PopupAnnotation-) | Annotazione pop-up per inserire o modificare il testo associato a questa annotazione. |
| [setReplyType](#setReplyType-com.aspose.pdf.ReplyType-) | Una stringa che specifica la relazione (il "tipo di risposta") tra questa annotazione e quella specificata da InReplyTo. |
| [setReviewState](#setReviewState-com.aspose.pdf.AnnotationState-) | Imposta lo stato di revisione per un'annotazione. Gli stati Contrassegnato e Non contrassegnato sono ignorati poiché non appartengono al Review StateModel. Lo stato è impostato dall'utente che ha creato l'annotazione di destinazione. Il valore è preso dalla proprietà Title dell'annotazione di destinazione. Nota, lo stato è memorizzato in altre annotazioni di testo che hanno le chiavi state e statemodel. |
| [setReviewState](#setReviewState-com.aspose.pdf.AnnotationState-java.lang.String-) | Imposta lo stato di revisione per un'annotazione. Gli stati Contrassegnato e Non contrassegnato sono ignorati poiché non appartengono al Review StateModel. Nota, lo stato è memorizzato in altre annotazioni di testo che hanno le chiavi state e statemodel. |
| [setRichText](#setRichText-java.lang.String-) | Imposta una stringa di testo formattato da visualizzare nella finestra pop-up quando l'annotazione viene aperta. |
| [setSubject](#setSubject-java.lang.String-) | Imposta il testo che rappresenta la descrizione dell'oggetto. |
| [setTitle](#setTitle-java.lang.String-) | Imposta un'etichetta di testo che deve essere visualizzata nella barra del titolo della finestra pop-up dell'annotazione quando è aperta e attiva. Questa voce deve identificare l'utente che ha aggiunto l'annotazione. |

### MarkupAnnotation {#MarkupAnnotation--}
```
public MarkupAnnotation()
```

Costruttore

### MarkupAnnotation {#MarkupAnnotation-com.aspose.pdf.IDocument-}
Costruttore

### clearState {#clearState--}
```
public final void clearState()
```

Cancella lo stato e il modello di stato per l'annotazione. Per esempio, cancella lo stato di revisione per un'annotazione. Nota, lo stato è memorizzato in altre annotazioni di testo che hanno le chiavi state e statemodel.

### getCreationDate {#getCreationDate--}
```
public Date getCreationDate()
```

Restituisce data e ora in cui l'annotazione è stata creata.

**Returns:**
Oggetto Date

### getInReplyTo {#getInReplyTo--}
```
public Annotation getInReplyTo()
```

Un riferimento all'annotazione a cui questa annotazione è "in risposta a". Entrambe le annotazioni devono trovarsi nella stessa pagina del documento.

**Returns:**
Valore dell'annotazione

### getOpacity {#getOpacity--}
```
public double getOpacity()
```

Restituisce il valore di opacità costante da utilizzare nel disegno dell'annotazione.

**Returns:**
valore double

### getPopup {#getPopup--}
```
public PopupAnnotation getPopup()
```

Annotazione pop-up per inserire o modificare il testo associato a questa annotazione.

**Returns:**
Valore PopupAnnotation

### getReplyType {#getReplyType--}
```
public ReplyType getReplyType()
```

Una stringa che specifica la relazione (il "tipo di risposta") tra questa annotazione e quella specificata da InReplyTo.

**Returns:**
Valore ReplyType @see ReplyType

### getRichText {#getRichText--}
```
public final String getRichText()
```

Restituisce una stringa di testo formattato da visualizzare nella finestra pop-up quando l'annotazione viene aperta.

**Returns:**
valore String

### getRichText {#getRichText-com.aspose.pdf.engine.data.IPdfDictionary-}
Restituisce una stringa di testo formattato da visualizzare nella finestra pop-up quando l'annotazione viene aperta.

**Returns:**
valore String

### getState {#getState--}
```
public final AnnotationState getState()
```

Restituisce lo stato dell'annotazione. Nota, lo stato è memorizzato in altre annotazioni di testo che hanno le chiavi state e statemodel.

**Returns:**
Stato dell'annotazione.

### getStateModel {#getStateModel--}
```
public final AnnotationStateModel getStateModel()
```

Restituisce il modello di stato dell'annotazione. Nota, lo stato è memorizzato in altre annotazioni di testo che hanno le chiavi state e statemodel.

**Returns:**
Modello di stato dell'annotazione.

### getSubject {#getSubject--}
```
public String getSubject()
```

Restituisce il testo che rappresenta la descrizione dell'oggetto.

**Returns:**
valore String

### getTitle {#getTitle--}
```
public String getTitle()
```

Restituisce un'etichetta di testo che deve essere visualizzata nella barra del titolo della finestra pop-up dell'annotazione quando è aperta e attiva. Questa voce deve identificare l'utente che ha aggiunto l'annotazione.

**Returns:**
valore String

### setCreationDate {#setCreationDate-java.util.Date-}
Restituisce data e ora in cui l'annotazione è stata creata.

### setInReplyTo {#setInReplyTo-com.aspose.pdf.Annotation-}
Un riferimento all'annotazione a cui questa annotazione è "in risposta a". Entrambe le annotazioni devono trovarsi nella stessa pagina del documento.

### setMarkedState {#setMarkedState-boolean-}
```
public final void setMarkedState(boolean marked)
```

Imposta lo stato Contrassegnato e Non contrassegnato per l'annotazione. Nota, lo stato è memorizzato in altre annotazioni di testo che hanno le chiavi state e statemodel.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contrassegnato |  | Vero se imposta lo stato Contrassegnato, e falso se imposta lo stato Non contrassegnato. |

### setOpacity {#setOpacity-double-}
```
public void setOpacity(double value)
```

Imposta il valore di opacità costante da utilizzare nel disegno dell'annotazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setPopup {#setPopup-com.aspose.pdf.PopupAnnotation-}
Annotazione pop-up per inserire o modificare il testo associato a questa annotazione.

### setReplyType {#setReplyType-com.aspose.pdf.ReplyType-}
Una stringa che specifica la relazione (il "tipo di risposta") tra questa annotazione e quella specificata da InReplyTo.

### setReviewState {#setReviewState-com.aspose.pdf.AnnotationState-}
Imposta lo stato di revisione per un'annotazione. Gli stati Contrassegnato e Non contrassegnato sono ignorati poiché non appartengono al Review StateModel. Lo stato è impostato dall'utente che ha creato l'annotazione di destinazione. Il valore è preso dalla proprietà Title dell'annotazione di destinazione. Nota, lo stato è memorizzato in altre annotazioni di testo che hanno le chiavi state e statemodel.

### setReviewState {#setReviewState-com.aspose.pdf.AnnotationState-java.lang.String-}
Imposta lo stato di revisione per un'annotazione. Gli stati Contrassegnato e Non contrassegnato sono ignorati poiché non appartengono al Review StateModel. Nota, lo stato è memorizzato in altre annotazioni di testo che hanno le chiavi state e statemodel.

### setRichText {#setRichText-java.lang.String-}
Imposta una stringa di testo formattato da visualizzare nella finestra pop-up quando l'annotazione viene aperta.

### setSubject {#setSubject-java.lang.String-}
Imposta il testo che rappresenta la descrizione dell'oggetto.

### setTitle {#setTitle-java.lang.String-}
Imposta un'etichetta di testo che deve essere visualizzata nella barra del titolo della finestra pop-up dell'annotazione quando è aperta e attiva. Questa voce deve identificare l'utente che ha aggiunto l'annotazione.
