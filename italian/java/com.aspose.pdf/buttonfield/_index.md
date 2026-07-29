---
title: "ButtonField"
linktitle: "ButtonField"
second_title: "Riferimento API Aspose.PDF per Java"
description: "La classe rappresenta un campo pulsante."
type: docs
weight: 440
url: /it/java/com.aspose.pdf/buttonfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.ButtonField, com.aspose.pdf.Field, com.aspose.pdf.ButtonField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class ButtonField extends Field
```

La classe rappresenta un campo pulsante.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ButtonField](#ButtonField--) | Costruttore del campo pulsante per Generator. |
| [ButtonField](#ButtonField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Costruttore del campo pulsante per Generator. |
| [ButtonField](#ButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Costruttore del campo pulsante per Generator. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addImage](#addImage-java.awt.image.BufferedImage-) | Aggiunge un'immagine nelle risorse del campo e la disegna. |
| [addImage](#addImage-java.awt.image.BufferedImage-boolean-) | Aggiunge l'immagine nelle risorse del campo e la disegna. |
| [getAlternateCaption](#getAlternateCaption--) | Ottiene la didascalia alternativa del pulsante che deve essere visualizzata quando il pulsante del mouse è premuto nella sua area attiva. |
| [getAlternateIcon](#getAlternateIcon--) | Ottiene l'icona alternativa che deve essere visualizzata quando il pulsante del mouse è premuto nella sua area attiva. |
| [getIconFit](#getIconFit--) | Ottiene l'oggetto di adattamento dell'icona che specifica come l'icona dell'annotazione widget deve essere visualizzata all'interno del rettangolo dell'annotazione. |
| [getICPosition](#getICPosition--) | Ottiene la posizione della didascalia dell'icona. |
| [getNormalCaption](#getNormalCaption--) | Ottiene la didascalia normale. |
| [getNormalIcon](#getNormalIcon--) | Ottiene l'icona normale del pulsante che deve essere visualizzata quando non sta interagendo con l'utente. |
| [getRolloverCaption](#getRolloverCaption--) | Ottiene la didascalia rollover del pulsante che deve essere visualizzata quando l'utente sposta il cursore nella sua area attiva senza premere il pulsante del mouse. |
| [getRolloverIcon](#getRolloverIcon--) | Ottiene l'icona rollover del pulsante che deve essere visualizzata quando l'utente sposta il cursore nella sua area attiva senza premere il pulsante del mouse. |
| [setAlternateCaption](#setAlternateCaption-java.lang.String-) | Imposta la didascalia alternativa del pulsante che deve essere visualizzata quando il pulsante del mouse è premuto nella sua area attiva. |
| [setAlternateIcon](#setAlternateIcon-com.aspose.pdf.XForm-) | Imposta l'icona alternativa che deve essere visualizzata quando il pulsante del mouse è premuto nella sua area attiva. |
| [setICPosition](#setICPosition-com.aspose.pdf.IconCaptionPosition-) | Imposta la posizione della didascalia dell'icona. |
| [setNormalCaption](#setNormalCaption-java.lang.String-) | Imposta la didascalia normale. |
| [setNormalIcon](#setNormalIcon-com.aspose.pdf.XForm-) | Imposta l'icona normale del pulsante che deve essere visualizzata quando non sta interagendo con l'utente. |
| [setRolloverCaption](#setRolloverCaption-java.lang.String-) | Imposta la didascalia rollover del pulsante che deve essere visualizzata quando l'utente sposta il cursore nella sua area attiva senza premere il pulsante del mouse. |
| [setRolloverIcon](#setRolloverIcon-com.aspose.pdf.XForm-) | Imposta l'icona di rollover del pulsante che deve essere visualizzata quando l'utente sposta il cursore nella sua area attiva senza premere il pulsante del mouse. |

### ButtonField {#ButtonField--}
```
public ButtonField()
```

Costruttore del campo pulsante per Generator.

### ButtonField {#ButtonField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Costruttore del campo pulsante per Generator.

### ButtonField {#ButtonField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Costruttore del campo pulsante per Generator.

### addImage {#addImage-java.awt.image.BufferedImage-}
Aggiunge un'immagine nelle risorse del campo e la disegna.

### addImage {#addImage-java.awt.image.BufferedImage-boolean-}
Aggiunge l'immagine nelle risorse del campo e la disegna.

### getAlternateCaption {#getAlternateCaption--}
```
public String getAlternateCaption()
```

Ottiene la didascalia alternativa del pulsante che deve essere visualizzata quando il pulsante del mouse è premuto nella sua area attiva.

**Returns:**
valore String

### getAlternateIcon {#getAlternateIcon--}
```
public XForm getAlternateIcon()
```

Ottiene l'icona alternativa che deve essere visualizzata quando il pulsante del mouse è premuto nella sua area attiva.

**Returns:**
oggetto XForm

### getIconFit {#getIconFit--}
```
public IconFit getIconFit()
```

Ottiene l'oggetto di adattamento dell'icona che specifica come l'icona dell'annotazione widget deve essere visualizzata all'interno del rettangolo dell'annotazione.

**Returns:**
Oggetto IconFit

### getICPosition {#getICPosition--}
```
public IconCaptionPosition getICPosition()
```

Ottiene la posizione della didascalia dell'icona.

**Returns:**
posizione della didascalia dell'icona. @see IconCaptionPosition

### getNormalCaption {#getNormalCaption--}
```
public String getNormalCaption()
```

Ottiene la didascalia normale.

**Returns:**
valore String

### getNormalIcon {#getNormalIcon--}
```
public XForm getNormalIcon()
```

Ottiene l'icona normale del pulsante che deve essere visualizzata quando non sta interagendo con l'utente.

**Returns:**
oggetto XForm

### getRolloverCaption {#getRolloverCaption--}
```
public String getRolloverCaption()
```

Ottiene la didascalia rollover del pulsante che deve essere visualizzata quando l'utente sposta il cursore nella sua area attiva senza premere il pulsante del mouse.

**Returns:**
valore String

### getRolloverIcon {#getRolloverIcon--}
```
public XForm getRolloverIcon()
```

Ottiene l'icona rollover del pulsante che deve essere visualizzata quando l'utente sposta il cursore nella sua area attiva senza premere il pulsante del mouse.

**Returns:**
oggetto XForm

### setAlternateCaption {#setAlternateCaption-java.lang.String-}
Imposta la didascalia alternativa del pulsante che deve essere visualizzata quando il pulsante del mouse è premuto nella sua area attiva.

### setAlternateIcon {#setAlternateIcon-com.aspose.pdf.XForm-}
Imposta l'icona alternativa che deve essere visualizzata quando il pulsante del mouse è premuto nella sua area attiva.

### setICPosition {#setICPosition-com.aspose.pdf.IconCaptionPosition-}
Imposta la posizione della didascalia dell'icona.

### setNormalCaption {#setNormalCaption-java.lang.String-}
Imposta la didascalia normale.

### setNormalIcon {#setNormalIcon-com.aspose.pdf.XForm-}
Imposta l'icona normale del pulsante che deve essere visualizzata quando non sta interagendo con l'utente.

### setRolloverCaption {#setRolloverCaption-java.lang.String-}
Imposta la didascalia rollover del pulsante che deve essere visualizzata quando l'utente sposta il cursore nella sua area attiva senza premere il pulsante del mouse.

### setRolloverIcon {#setRolloverIcon-com.aspose.pdf.XForm-}
Imposta l'icona di rollover del pulsante che deve essere visualizzata quando l'utente sposta il cursore nella sua area attiva senza premere il pulsante del mouse.
