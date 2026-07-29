---
title: "MarkupAnnotation"
linktitle: "MarkupAnnotation"
second_title: "Aspose.PDF för Java API-referens"
description: "Abstrakt klass som representerar markup-anteckning."
type: docs
weight: 2870
url: /sv/java/com.aspose.pdf/markupannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public abstract class MarkupAnnotation extends Annotation implements com.aspose.pdf.engine.ITitledAnnotation
```

Abstrakt klass som representerar markup-anteckning.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [MarkupAnnotation](#MarkupAnnotation--) | Konstruktör |
| [MarkupAnnotation](#MarkupAnnotation-com.aspose.pdf.IDocument-) | Konstruktör |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [clearState](#clearState--) | Rensar tillstånd och tillståndsmodell för annoteringen. Till exempel rensar den granskningsstatusen för en annotering. Observera att tillståndet lagras i andra textannoteringar som har nycklarna state och statemodel. |
| [getCreationDate](#getCreationDate--) | Hämtar datum och tid då annoteringen skapades. |
| [getInReplyTo](#getInReplyTo--) | En referens till den annotering som denna annotering är "i svar på". Båda annoteringarna måste vara på samma sida i dokumentet. |
| [getOpacity](#getOpacity--) | Hämtar det konstanta opacitetsvärdet som ska användas vid målning av annoteringen. |
| [getPopup](#getPopup--) | Popup‑annotering för att ange eller redigera texten som är associerad med denna annotering. |
| [getReplyType](#getReplyType--) | En sträng som specificerar förhållandet ("svarstypen") mellan denna annotering och den som anges av InReplyTo. |
| [getRichText](#getRichText--) | Hämtar en riktextsträng som ska visas i popup‑fönstret när annoteringen öppnas. |
| [getRichText](#getRichText-com.aspose.pdf.engine.data.IPdfDictionary-) | Hämtar en riktextsträng som ska visas i popup‑fönstret när annoteringen öppnas. |
| [getState](#getState--) | Hämtar annoteringens tillstånd. Observera att tillståndet lagras i andra textannoteringar som har nycklarna state och statemodel. |
| [getStateModel](#getStateModel--) | Hämtar tillståndsmodellen för annoteringen. Obs, tillståndet lagras i annan textannotering som har nycklarna state och statemodel. |
| [getSubject](#getSubject--) | Hämtar text som representerar beskrivning av objektet. |
| [getTitle](#getTitle--) | Hämtar en textetikett som ska visas i titelraden på annotationпїЅs popup‑fönster när det är öppet och aktivt. Denna post ska identifiera användaren som lade till annoteringen. |
| [setCreationDate](#setCreationDate-java.util.Date-) | Hämtar datum och tid då annoteringen skapades. |
| [setInReplyTo](#setInReplyTo-com.aspose.pdf.Annotation-) | En referens till den annotering som denna annotering är "i svar på". Båda annoteringarna måste vara på samma sida i dokumentet. |
| [setMarkedState](#setMarkedState-boolean-) | Ställer in markerat och omarkerat tillstånd för annoteringen. Obs, tillståndet lagras i annan textannotering som har nycklarna state och statemodel. |
| [setOpacity](#setOpacity-double-) | Ställer in det konstanta opacitetsvärdet som ska användas vid rendering av annoteringen. |
| [setPopup](#setPopup-com.aspose.pdf.PopupAnnotation-) | Popup‑annotering för att ange eller redigera texten som är associerad med denna annotering. |
| [setReplyType](#setReplyType-com.aspose.pdf.ReplyType-) | En sträng som specificerar förhållandet ("svarstypen") mellan denna annotering och den som anges av InReplyTo. |
| [setReviewState](#setReviewState-com.aspose.pdf.AnnotationState-) | Ställer in granskningsstatus för en annotering. Markerade och omarkerade tillstånd ignoreras eftersom de inte tillhör Review StateModel. Tillståndet sätts av användaren som skapade målannoteringen. Värdet hämtas från Title‑egenskapen för målannoteringen. Obs, tillståndet lagras i annan textannotering som har nycklarna state och statemodel. |
| [setReviewState](#setReviewState-com.aspose.pdf.AnnotationState-java.lang.String-) | Ställer in granskningsstatus för en annotering. Markerade och omarkerade tillstånd ignoreras eftersom de inte tillhör Review StateModel. Obs, tillståndet lagras i annan textannotering som har nycklarna state och statemodel. |
| [setRichText](#setRichText-java.lang.String-) | Ställer in en rich‑textsträng som ska visas i popup‑fönstret när annoteringen öppnas. |
| [setSubject](#setSubject-java.lang.String-) | Ställer in text som representerar beskrivning av objektet. |
| [setTitle](#setTitle-java.lang.String-) | Ställer in en textetikett som ska visas i titelraden på annotationпїЅs popup‑fönster när det är öppet och aktivt. Denna post ska identifiera användaren som lade till annoteringen. |

### MarkupAnnotation {#MarkupAnnotation--}
```
public MarkupAnnotation()
```

Konstruktör

### MarkupAnnotation {#MarkupAnnotation-com.aspose.pdf.IDocument-}
Konstruktör

### clearState {#clearState--}
```
public final void clearState()
```

Rensar tillstånd och tillståndsmodell för annoteringen. Till exempel rensar den granskningsstatusen för en annotering. Observera att tillståndet lagras i andra textannoteringar som har nycklarna state och statemodel.

### getCreationDate {#getCreationDate--}
```
public Date getCreationDate()
```

Hämtar datum och tid då annoteringen skapades.

**Returns:**
Date-objekt

### getInReplyTo {#getInReplyTo--}
```
public Annotation getInReplyTo()
```

En referens till den annotering som denna annotering är "i svar på". Båda annoteringarna måste vara på samma sida i dokumentet.

**Returns:**
Annoteringsvärde

### getOpacity {#getOpacity--}
```
public double getOpacity()
```

Hämtar det konstanta opacitetsvärdet som ska användas vid målning av annoteringen.

**Returns:**
double-värde

### getPopup {#getPopup--}
```
public PopupAnnotation getPopup()
```

Popup‑annotering för att ange eller redigera texten som är associerad med denna annotering.

**Returns:**
PopupAnnotation‑värde

### getReplyType {#getReplyType--}
```
public ReplyType getReplyType()
```

En sträng som specificerar förhållandet ("svarstypen") mellan denna annotering och den som anges av InReplyTo.

**Returns:**
ReplyType‑värde @see ReplyType

### getRichText {#getRichText--}
```
public final String getRichText()
```

Hämtar en riktextsträng som ska visas i popup‑fönstret när annoteringen öppnas.

**Returns:**
String värde

### getRichText {#getRichText-com.aspose.pdf.engine.data.IPdfDictionary-}
Hämtar en riktextsträng som ska visas i popup‑fönstret när annoteringen öppnas.

**Returns:**
String värde

### getState {#getState--}
```
public final AnnotationState getState()
```

Hämtar annoteringens tillstånd. Observera att tillståndet lagras i andra textannoteringar som har nycklarna state och statemodel.

**Returns:**
Annoteringstillstånd.

### getStateModel {#getStateModel--}
```
public final AnnotationStateModel getStateModel()
```

Hämtar tillståndsmodellen för annoteringen. Obs, tillståndet lagras i annan textannotering som har nycklarna state och statemodel.

**Returns:**
Annoteringstillståndsmodell.

### getSubject {#getSubject--}
```
public String getSubject()
```

Hämtar text som representerar beskrivning av objektet.

**Returns:**
String värde

### getTitle {#getTitle--}
```
public String getTitle()
```

Hämtar en textetikett som ska visas i titelraden på annotationпїЅs popup‑fönster när det är öppet och aktivt. Denna post ska identifiera användaren som lade till annoteringen.

**Returns:**
String värde

### setCreationDate {#setCreationDate-java.util.Date-}
Hämtar datum och tid då annoteringen skapades.

### setInReplyTo {#setInReplyTo-com.aspose.pdf.Annotation-}
En referens till den annotering som denna annotering är "i svar på". Båda annoteringarna måste vara på samma sida i dokumentet.

### setMarkedState {#setMarkedState-boolean-}
```
public final void setMarkedState(boolean marked)
```

Ställer in markerat och omarkerat tillstånd för annoteringen. Obs, tillståndet lagras i annan textannotering som har nycklarna state och statemodel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| markerad |  | Sant om markerat tillstånd sätts, och falskt om omarkerat tillstånd sätts. |

### setOpacity {#setOpacity-double-}
```
public void setOpacity(double value)
```

Ställer in det konstanta opacitetsvärdet som ska användas vid rendering av annoteringen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setPopup {#setPopup-com.aspose.pdf.PopupAnnotation-}
Popup‑annotering för att ange eller redigera texten som är associerad med denna annotering.

### setReplyType {#setReplyType-com.aspose.pdf.ReplyType-}
En sträng som specificerar förhållandet ("svarstypen") mellan denna annotering och den som anges av InReplyTo.

### setReviewState {#setReviewState-com.aspose.pdf.AnnotationState-}
Ställer in granskningsstatus för en annotering. Markerade och omarkerade tillstånd ignoreras eftersom de inte tillhör Review StateModel. Tillståndet sätts av användaren som skapade målannoteringen. Värdet hämtas från Title‑egenskapen för målannoteringen. Obs, tillståndet lagras i annan textannotering som har nycklarna state och statemodel.

### setReviewState {#setReviewState-com.aspose.pdf.AnnotationState-java.lang.String-}
Ställer in granskningsstatus för en annotering. Markerade och omarkerade tillstånd ignoreras eftersom de inte tillhör Review StateModel. Obs, tillståndet lagras i annan textannotering som har nycklarna state och statemodel.

### setRichText {#setRichText-java.lang.String-}
Ställer in en rich‑textsträng som ska visas i popup‑fönstret när annoteringen öppnas.

### setSubject {#setSubject-java.lang.String-}
Ställer in text som representerar beskrivning av objektet.

### setTitle {#setTitle-java.lang.String-}
Ställer in en textetikett som ska visas i titelraden på annotationпїЅs popup‑fönster när det är öppet och aktivt. Denna post ska identifiera användaren som lade till annoteringen.
