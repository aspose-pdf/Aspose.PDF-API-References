---
title: "TextBoxField"
linktitle: "TextBoxField"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta il campo casella di testo."
type: docs
weight: 4930
url: /it/java/com.aspose.pdf/textboxfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.TextBoxField, com.aspose.pdf.Field, com.aspose.pdf.TextBoxField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class TextBoxField extends Field
```

Classe che rappresenta il campo casella di testo.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TextBoxField](#TextBoxField--) | Crea un'istanza di TextBoxField. @deprecated Per la piena funzionalità del campo, è necessario un collegamento al documento - usa TextBoxField(Document doc) |
| [TextBoxField](#TextBoxField-com.aspose.pdf.IDocument-) | Crea un'istanza di TextBoxField. @deprecated Per la piena funzionalità del campo, è necessario un collegamento al documento - usa TextBoxField(Document doc) |
| [TextBoxField](#TextBoxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | Crea un'istanza di TextBoxField. @deprecated Per la piena funzionalità del campo, è necessario un collegamento al documento - usa TextBoxField(Document doc) |
| [TextBoxField](#TextBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | Crea un'istanza di TextBoxField. @deprecated Per la piena funzionalità del campo, è necessario un collegamento al documento - usa TextBoxField(Document doc) |
| [TextBoxField](#TextBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle:A-) | Crea un'istanza di TextBoxField. @deprecated Per la piena funzionalità del campo, è necessario un collegamento al documento - usa TextBoxField(Document doc) |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addBarcode](#addBarcode-java.lang.String-) | Aggiunge il codice a barre 128 nel campo. Il valore del campo verrà modificato con il codice e il campo diventerà di sola lettura. |
| [addImage](#addImage-java.awt.image.BufferedImage-) | Aggiunge un'immagine nelle risorse del campo e la disegna. |
| [getForceCombs](#getForceCombs--) | Restituisce il flag che indica se il campo è diviso in posizioni spaziate. |
| [getMaxLen](#getMaxLen--) | Restituisce la lunghezza massima del testo nel campo. |
| [getMultiline](#getMultiline--) | Restituisce il flag multilinea del campo. Se Multiline è true, il campo può contenere più righe di testo. |
| [getScrollable](#getScrollable--) | Restituisce il flag di scorrimento del campo. Se true, il campo può essere scorrevole. |
| [getSpellCheck](#getSpellCheck--) | Restituisce il flag di correzione ortografica per il campo. Se true, il campo sarà controllato ortograficamente. |
| [getTextVerticalAlignment](#getTextVerticalAlignment--) | Restituisce o imposta l'allineamento verticale del testo per l'annotazione. |
| [getValue](#getValue--) | Restituisce il valore del campo. |
| [setForceCombs](#setForceCombs-boolean-) | Imposta il flag che indica se il campo è diviso in posizioni spaziate. |
| [setJustification](#setJustification-boolean-) | Imposta l'allineamento |
| [setMaxLen](#setMaxLen-int-) | Imposta la lunghezza massima del testo nel campo. |
| [setMultiline](#setMultiline-boolean-) | Imposta il flag multilinea del campo. Se Multiline è true, il campo può contenere più righe di testo. |
| [setScrollable](#setScrollable-boolean-) | Imposta il flag scrollabile del campo. Se true, il campo può essere scorrevole. |
| [setSpellCheck](#setSpellCheck-boolean-) | Imposta il flag di correzione ortografica per il campo. Se true, il campo verrà controllato ortograficamente. |
| [setTextVerticalAlignment](#setTextVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Restituisce o imposta l'allineamento verticale del testo per l'annotazione. |
| [setValue](#setValue-java.lang.String-) | Imposta il valore del campo. |

### TextBoxField {#TextBoxField--}
```
@Deprecated public TextBoxField()
```

Crea un'istanza di TextBoxField. @deprecated Per la piena funzionalità del campo, è necessario un collegamento al documento - usa TextBoxField(Document doc)

### TextBoxField {#TextBoxField-com.aspose.pdf.IDocument-}
Crea un'istanza di TextBoxField. @deprecated Per la piena funzionalità del campo, è necessario un collegamento al documento - usa TextBoxField(Document doc)

### TextBoxField {#TextBoxField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
Crea un'istanza di TextBoxField. @deprecated Per la piena funzionalità del campo, è necessario un collegamento al documento - usa TextBoxField(Document doc)

### TextBoxField {#TextBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
Crea un'istanza di TextBoxField. @deprecated Per la piena funzionalità del campo, è necessario un collegamento al documento - usa TextBoxField(Document doc)

### TextBoxField {#TextBoxField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle:A-}
Crea un'istanza di TextBoxField. @deprecated Per la piena funzionalità del campo, è necessario un collegamento al documento - usa TextBoxField(Document doc)

### addBarcode {#addBarcode-java.lang.String-}
Aggiunge il codice a barre 128 nel campo. Il valore del campo verrà modificato con il codice e il campo diventerà di sola lettura.

### addImage {#addImage-java.awt.image.BufferedImage-}
Aggiunge un'immagine nelle risorse del campo e la disegna.

### getForceCombs {#getForceCombs--}
```
public boolean getForceCombs()
```

Restituisce il flag che indica se il campo è diviso in posizioni spaziate.

**Returns:**
valore booleano

### getMaxLen {#getMaxLen--}
```
public int getMaxLen()
```

Restituisce la lunghezza massima del testo nel campo.

**Returns:**
valore int

### getMultiline {#getMultiline--}
```
public boolean getMultiline()
```

Restituisce il flag multilinea del campo. Se Multiline è true, il campo può contenere più righe di testo.

**Returns:**
valore booleano

### getScrollable {#getScrollable--}
```
public boolean getScrollable()
```

Restituisce il flag di scorrimento del campo. Se true, il campo può essere scorrevole.

**Returns:**
valore booleano

### getSpellCheck {#getSpellCheck--}
```
public boolean getSpellCheck()
```

Restituisce il flag di correzione ortografica per il campo. Se true, il campo sarà controllato ortograficamente.

**Returns:**
valore booleano

### getTextVerticalAlignment {#getTextVerticalAlignment--}
```
public final VerticalAlignment getTextVerticalAlignment()
```

Restituisce o imposta l'allineamento verticale del testo per l'annotazione.

**Returns:**
Elemento VerticalAlignment

### getValue {#getValue--}
```
public String getValue()
```

Restituisce il valore del campo.

**Returns:**
valore String

### setForceCombs {#setForceCombs-boolean-}
```
public void setForceCombs(boolean value)
```

Imposta il flag che indica se il campo è diviso in posizioni spaziate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setJustification {#setJustification-boolean-}
```
public void setJustification(boolean value)
```

Imposta l'allineamento

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setMaxLen {#setMaxLen-int-}
```
public void setMaxLen(int value)
```

Imposta la lunghezza massima del testo nel campo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setMultiline {#setMultiline-boolean-}
```
public void setMultiline(boolean value)
```

Imposta il flag multilinea del campo. Se Multiline è true, il campo può contenere più righe di testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setScrollable {#setScrollable-boolean-}
```
public void setScrollable(boolean value)
```

Imposta il flag scrollabile del campo. Se true, il campo può essere scorrevole.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setSpellCheck {#setSpellCheck-boolean-}
```
public void setSpellCheck(boolean value)
```

Imposta il flag di correzione ortografica per il campo. Se true, il campo verrà controllato ortograficamente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setTextVerticalAlignment {#setTextVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Restituisce o imposta l'allineamento verticale del testo per l'annotazione.

### setValue {#setValue-java.lang.String-}
Imposta il valore del campo.
