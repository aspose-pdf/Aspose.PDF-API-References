---
title: "FormFieldFacade"
linktitle: "FormFieldFacade"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe per rappresentare le proprietà del campo."
type: docs
weight: 220
url: /it/java/com.aspose.pdf.facades/formfieldfacade/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.FormFieldFacade

```
public final class FormFieldFacade extends Object
```

Classe per rappresentare le proprietà del campo.

## Campi

| Campo | Descrizione |
| --- | --- |
| [ALIGN_BOTTOM](#ALIGN_BOTTOM) | Definisce l'allineamento verticale come stile inferiore. |
| [ALIGN_CENTER](#ALIGN_CENTER) | Definisce l'allineamento allo stile centrale. |
| [ALIGN_JUSTIFIED](#ALIGN_JUSTIFIED) | Definisce lo stile di allineamento di giustificazione del testo. |
| [ALIGN_LEFT](#ALIGN_LEFT) | Definisce l'allineamento allo stile sinistro. |
| [ALIGN_MIDDLE](#ALIGN_MIDDLE) | Definisce l'allineamento verticale come stile intermedio. |
| [ALIGN_RIGHT](#ALIGN_RIGHT) | Definisce l'allineamento allo stile destro. |
| [ALIGN_TOP](#ALIGN_TOP) | Definisce l'allineamento verticale come stile superiore. |
| [ALIGN_UNDEFINED](#ALIGN_UNDEFINED) | Stile di allineamento non definito. |
| [BORDER_STYLE_BEVELED](#BORDER_STYLE_BEVELED) | Definisce uno stile di bordo smussato. |
| [BORDER_STYLE_DASHED](#BORDER_STYLE_DASHED) | Definisce uno stile di bordo tratteggiato. |
| [BORDER_STYLE_INSET](#BORDER_STYLE_INSET) | Definisce uno stile di bordo incassato. |
| [BORDER_STYLE_SOLID](#BORDER_STYLE_SOLID) | Definisce uno stile di bordo solido. |
| [BORDER_STYLE_UNDEFINED](#BORDER_STYLE_UNDEFINED) | Stile di bordo non definito. |
| [BORDER_STYLE_UNDERLINE](#BORDER_STYLE_UNDERLINE) | Definisce uno stile di bordo sottolineato. |
| [BORDER_WIDTH_MEDIUM](#BORDER_WIDTH_MEDIUM) | Definisce una larghezza di bordo media. |
| [BORDER_WIDTH_THICK](#BORDER_WIDTH_THICK) | Definisce una larghezza di bordo spessa. |
| [BORDER_WIDTH_THIN](#BORDER_WIDTH_THIN) | Definisce una larghezza di bordo sottile. |
| [BORDER_WIDTH_UNDEFINED](#BORDER_WIDTH_UNDEFINED) | Larghezza di bordo non definita. |
| [BORDER_WIDTH_UNDIFIED](#BORDER_WIDTH_UNDIFIED) | Larghezza di bordo non definita. |
| [CHECK_BOX_STYLE_CHECK](#CHECK_BOX_STYLE_CHECK) | Definisce la forma di un campo casella di controllo quando è selezionato. |
| [CHECK_BOX_STYLE_CIRCLE](#CHECK_BOX_STYLE_CIRCLE) | Definisce uno stile di casella di controllo circolare. |
| [CHECK_BOX_STYLE_CROSS](#CHECK_BOX_STYLE_CROSS) | Definisce uno stile di casella di controllo a croce. |
| [CHECK_BOX_STYLE_DIAMOND](#CHECK_BOX_STYLE_DIAMOND) | Definisce uno stile di casella di controllo a diamante. |
| [CHECK_BOX_STYLE_SQUARE](#CHECK_BOX_STYLE_SQUARE) | Definisce uno stile di casella di controllo quadrato. |
| [CHECK_BOX_STYLE_STAR](#CHECK_BOX_STYLE_STAR) | Definisce uno stile di casella di controllo a stella. |
| [CHECK_BOX_STYLE_UNDEFINED](#CHECK_BOX_STYLE_UNDEFINED) | Definisce uno stile di casella di controllo non definito. |

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FormFieldFacade](#FormFieldFacade--) |  |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAlignment](#getAlignment--) | Ottieni l'allineamento del testo di un campo, il valore predefinito è allineamento a sinistra. |
| [getBackgroudColor](#getBackgroudColor--) | Proprietà obsoleta. Usa BackgroundColor. Questo metodo è deprecato. |
| [getBackgroundColor](#getBackgroundColor--) | Ottieni il colore dello sfondo di un campo, il valore predefinito è bianco. |
| [getBorderColor](#getBorderColor--) | Ottiene il colore del bordo di un campo. |
| [getBorderStyle](#getBorderStyle--) | Ottiene lo stile del bordo di un campo. |
| [getBorderWidth](#getBorderWidth--) | Ottieni la larghezza del bordo di un campo. |
| [getBox](#getBox--) | Ottieni un oggetto rettangolo che contiene la posizione del campo. |
| [getButtonStyle](#getButtonStyle--) | Ottieni lo stile del campo casella di controllo o pulsante radio, definito da FormFieldFacade.CheckBoxStyle*. |
| [getCaption](#getCaption--) | Ottieni la didascalia normale del campo modulo. |
| [getCustomFont](#getCustomFont--) | Ottiene il nome del carattere quando non è standard (diverso dai 14 caratteri standard). |
| [getExportItems](#getExportItems--) | Ottieni le opzioni per aggiungere una lista/combobox/pulsante radio |
| [getFont](#getFont--) | Ottiene il tipo di stile del carattere del testo di un campo. |
| [getFontSize](#getFontSize--) | Ottiene la dimensione del testo di un campo. |
| [getItems](#getItems--) | Ottieni un array di stringhe, ciascuna rappresentante un'opzione di un campo combobox/lista/pulsante radio. |
| [getPageNumber](#getPageNumber--) | Ottieni un valore intero che indica il numero di pagina in cui si trova il campo. |
| [getPosition](#getPosition--) | Ottieni un oggetto rettangolo che contiene la posizione del campo. |
| [getRotation](#getRotation--) | Ottieni la rotazione del testo di un campo. |
| [getTextColor](#getTextColor--) | Ottieni il colore del testo del campo. |
| [getTextEncoding](#getTextEncoding--) | Ottieni il tipo di codifica del testo del campo. |
| [reset](#reset--) | Reimposta tutti gli attributi visivi a valore vuoto. |
| [setAlignment](#setAlignment-int-) | Imposta l'allineamento del testo di un campo, il valore predefinito è allineamento a sinistra. |
| [setBackgroudColor](#setBackgroudColor-java.awt.Color-) | Obsoleto. |
| [setBackgroundColor](#setBackgroundColor-java.awt.Color-) | Imposta il colore dello sfondo di un campo, il valore predefinito è bianco. |
| [setBorderColor](#setBorderColor-java.awt.Color-) | Imposta il colore del bordo di un campo. |
| [setBorderStyle](#setBorderStyle-int-) | Imposta lo stile del bordo di un campo. |
| [setBorderWidth](#setBorderWidth-float-) | Imposta la larghezza del bordo di un campo. |
| [setBox](#setBox-java.awt.Rectangle-) | Imposta un oggetto rettangolo che contiene la posizione del campo. |
| [setButtonStyle](#setButtonStyle-int-) | Imposta lo stile del campo casella di controllo o pulsante radio, definito da FormFieldFacade.CheckBoxStyle*. |
| [setCaption](#setCaption-java.lang.String-) | Imposta la didascalia normale del campo modulo. |
| [setCustomFont](#setCustomFont-java.lang.String-) | Imposta il nome del carattere quando questo non è standard (diverso dai 14 caratteri standard). |
| [setExportItems](#setExportItems-java.lang.String:A:A-) | Imposta le opzioni per aggiungere un elenco/combobox/pulsante radio |
| [setFont](#setFont-com.aspose.pdf.facades.FontStyle-) | Imposta il tipo di stile del carattere di un testo di campo. |
| [setFontSize](#setFontSize-float-) | Imposta la dimensione di un testo di campo. |
| [setItems](#setItems-java.lang.String:A-) | Imposta un array di stringhe, ciascuna rappresentante un'opzione di un campo combobox/elenco/pulsante radio. |
| [setPageNumber](#setPageNumber-int-) | Imposta un valore intero che contiene il numero di pagina su cui si trova il campo. |
| [setPosition](#setPosition-float:A-) | Imposta un oggetto rettangolo che contiene la posizione del campo. |
| [setRotation](#setRotation-int-) | Imposta la rotazione di un testo di campo. |
| [setTextColor](#setTextColor-java.awt.Color-) | Imposta il colore del testo del campo. |
| [setTextEncoding](#setTextEncoding-int-) | Imposta il tipo di codifica del testo {@link EncodingType} del campo. |

### ALIGN_BOTTOM {#ALIGN_BOTTOM}
```
public static final int ALIGN_BOTTOM
```

Definisce l'allineamento verticale come stile inferiore.

### ALIGN_CENTER {#ALIGN_CENTER}
```
public static final int ALIGN_CENTER
```

Definisce l'allineamento allo stile centrale.

### ALIGN_JUSTIFIED {#ALIGN_JUSTIFIED}
```
public static final int ALIGN_JUSTIFIED
```

Definisce lo stile di allineamento di giustificazione del testo.

### ALIGN_LEFT {#ALIGN_LEFT}
```
public static final int ALIGN_LEFT
```

Definisce l'allineamento allo stile sinistro.

### ALIGN_MIDDLE {#ALIGN_MIDDLE}
```
public static final int ALIGN_MIDDLE
```

Definisce l'allineamento verticale come stile intermedio.

### ALIGN_RIGHT {#ALIGN_RIGHT}
```
public static final int ALIGN_RIGHT
```

Definisce l'allineamento allo stile destro.

### ALIGN_TOP {#ALIGN_TOP}
```
public static final int ALIGN_TOP
```

Definisce l'allineamento verticale come stile superiore.

### ALIGN_UNDEFINED {#ALIGN_UNDEFINED}
```
public static final int ALIGN_UNDEFINED
```

Stile di allineamento non definito.

### BORDER_STYLE_BEVELED {#BORDER_STYLE_BEVELED}
```
public static final int BORDER_STYLE_BEVELED
```

Definisce uno stile di bordo smussato.

### BORDER_STYLE_DASHED {#BORDER_STYLE_DASHED}
```
public static final int BORDER_STYLE_DASHED
```

Definisce uno stile di bordo tratteggiato.

### BORDER_STYLE_INSET {#BORDER_STYLE_INSET}
```
public static final int BORDER_STYLE_INSET
```

Definisce uno stile di bordo incassato.

### BORDER_STYLE_SOLID {#BORDER_STYLE_SOLID}
```
public static final int BORDER_STYLE_SOLID
```

Definisce uno stile di bordo solido.

### BORDER_STYLE_UNDEFINED {#BORDER_STYLE_UNDEFINED}
```
public static final int BORDER_STYLE_UNDEFINED
```

Stile di bordo non definito.

### BORDER_STYLE_UNDERLINE {#BORDER_STYLE_UNDERLINE}
```
public static final int BORDER_STYLE_UNDERLINE
```

Definisce uno stile di bordo sottolineato.

### BORDER_WIDTH_MEDIUM {#BORDER_WIDTH_MEDIUM}
```
public static final float BORDER_WIDTH_MEDIUM
```

Definisce una larghezza di bordo media.

### BORDER_WIDTH_THICK {#BORDER_WIDTH_THICK}
```
public static final float BORDER_WIDTH_THICK
```

Definisce una larghezza di bordo spessa.

### BORDER_WIDTH_THIN {#BORDER_WIDTH_THIN}
```
public static final float BORDER_WIDTH_THIN
```

Definisce una larghezza di bordo sottile.

### BORDER_WIDTH_UNDEFINED {#BORDER_WIDTH_UNDEFINED}
```
public static final float BORDER_WIDTH_UNDEFINED
```

Larghezza di bordo non definita.

### BORDER_WIDTH_UNDIFIED {#BORDER_WIDTH_UNDIFIED}
```
@Deprecated public static final float BORDER_WIDTH_UNDIFIED
```

Larghezza di bordo non definita.

### CHECK_BOX_STYLE_CHECK {#CHECK_BOX_STYLE_CHECK}
```
public static final int CHECK_BOX_STYLE_CHECK
```

Definisce la forma di un campo casella di controllo quando è selezionato.

### CHECK_BOX_STYLE_CIRCLE {#CHECK_BOX_STYLE_CIRCLE}
```
public static final int CHECK_BOX_STYLE_CIRCLE
```

Definisce uno stile di casella di controllo circolare.

### CHECK_BOX_STYLE_CROSS {#CHECK_BOX_STYLE_CROSS}
```
public static final int CHECK_BOX_STYLE_CROSS
```

Definisce uno stile di casella di controllo a croce.

### CHECK_BOX_STYLE_DIAMOND {#CHECK_BOX_STYLE_DIAMOND}
```
public static final int CHECK_BOX_STYLE_DIAMOND
```

Definisce uno stile di casella di controllo a diamante.

### CHECK_BOX_STYLE_SQUARE {#CHECK_BOX_STYLE_SQUARE}
```
public static final int CHECK_BOX_STYLE_SQUARE
```

Definisce uno stile di casella di controllo quadrato.

### CHECK_BOX_STYLE_STAR {#CHECK_BOX_STYLE_STAR}
```
public static final int CHECK_BOX_STYLE_STAR
```

Definisce uno stile di casella di controllo a stella.

### CHECK_BOX_STYLE_UNDEFINED {#CHECK_BOX_STYLE_UNDEFINED}
```
public static final int CHECK_BOX_STYLE_UNDEFINED
```

Definisce uno stile di casella di controllo non definito.

### FormFieldFacade {#FormFieldFacade--}
```
public FormFieldFacade()
```



### getAlignment {#getAlignment--}
```
public int getAlignment()
```

Ottieni l'allineamento del testo di un campo, il valore predefinito è allineamento a sinistra.

**Returns:**
valore int

### getBackgroudColor {#getBackgroudColor--}
```
@Deprecated public Color getBackgroudColor()
```

Proprietà obsoleta. Usa BackgroundColor. Questo metodo è deprecato.

**Returns:**
colore di sfondo

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

Ottieni il colore dello sfondo di un campo, il valore predefinito è bianco.

**Returns:**
Elemento colore

### getBorderColor {#getBorderColor--}
```
public Color getBorderColor()
```

Ottiene il colore del bordo di un campo.

**Returns:**
colore del bordo del campo.

### getBorderStyle {#getBorderStyle--}
```
public int getBorderStyle()
```

Ottiene lo stile del bordo di un campo.

**Returns:**
stile del bordo del campo.

### getBorderWidth {#getBorderWidth--}
```
public float getBorderWidth()
```

Ottieni la larghezza del bordo di un campo.

**Returns:**
larghezza del bordo del campo.

### getBox {#getBox--}
```
public Rectangle getBox()
```

Ottieni un oggetto rettangolo che contiene la posizione del campo.

**Returns:**
Elemento rettangolo

### getButtonStyle {#getButtonStyle--}
```
public int getButtonStyle()
```

Ottieni lo stile del campo casella di controllo o pulsante radio, definito da FormFieldFacade.CheckBoxStyle*.

**Returns:**
valore int

### getCaption {#getCaption--}
```
public String getCaption()
```

Ottieni la didascalia normale del campo modulo.

**Returns:**
valore String

### getCustomFont {#getCustomFont--}
```
public String getCustomFont()
```

Ottiene il nome del carattere quando non è standard (diverso dai 14 caratteri standard).

**Returns:**
valore String

### getExportItems {#getExportItems--}
```
public String [][] getExportItems()
```

Ottieni le opzioni per aggiungere una lista/combobox/pulsante radio

**Returns:**
array di valore String

### getFont {#getFont--}
```
public FontStyle getFont()
```

Ottiene il tipo di stile del carattere del testo di un campo.

**Returns:**
Elemento FontStyle @see FontStyle

### getFontSize {#getFontSize--}
```
public float getFontSize()
```

Ottiene la dimensione del testo di un campo.

**Returns:**
valore float

### getItems {#getItems--}
```
public String [] getItems()
```

Ottieni un array di stringhe, ciascuna rappresentante un'opzione di un campo combobox/lista/pulsante radio.

**Returns:**
array di valore String

### getPageNumber {#getPageNumber--}
```
public int getPageNumber()
```

Ottieni un valore intero che indica il numero di pagina in cui si trova il campo.

**Returns:**
valore int

### getPosition {#getPosition--}
```
public float[] getPosition()
```

Ottieni un oggetto rettangolo che contiene la posizione del campo.

**Returns:**
array di valore float

### getRotation {#getRotation--}
```
public int getRotation()
```

Ottieni la rotazione del testo di un campo.

**Returns:**
valore int

### getTextColor {#getTextColor--}
```
public Color getTextColor()
```

Ottieni il colore del testo del campo.

**Returns:**
Elemento colore

### getTextEncoding {#getTextEncoding--}
```
public int getTextEncoding()
```

Ottieni il tipo di codifica del testo del campo.

**Returns:**
Elemento EncodingType @see EncodingType

### reset {#reset--}
```
public void reset()
```

Reimposta tutti gli attributi visivi a valore vuoto.

### setAlignment {#setAlignment-int-}
```
public void setAlignment(int value)
```

Imposta l'allineamento del testo di un campo, il valore predefinito è allineamento a sinistra.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setBackgroudColor {#setBackgroudColor-java.awt.Color-}
Obsoleto.

### setBackgroundColor {#setBackgroundColor-java.awt.Color-}
Imposta il colore dello sfondo di un campo, il valore predefinito è bianco.

### setBorderColor {#setBorderColor-java.awt.Color-}
Imposta il colore del bordo di un campo.

### setBorderStyle {#setBorderStyle-int-}
```
public void setBorderStyle(int value)
```

Imposta lo stile del bordo di un campo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | stile del bordo del campo. |

### setBorderWidth {#setBorderWidth-float-}
```
public void setBorderWidth(float value)
```

Imposta la larghezza del bordo di un campo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | larghezza del bordo del campo. |

### setBox {#setBox-java.awt.Rectangle-}
Imposta un oggetto rettangolo che contiene la posizione del campo.

### setButtonStyle {#setButtonStyle-int-}
```
public void setButtonStyle(int value)
```

Imposta lo stile del campo casella di controllo o pulsante radio, definito da FormFieldFacade.CheckBoxStyle*.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setCaption {#setCaption-java.lang.String-}
Imposta la didascalia normale del campo modulo.

### setCustomFont {#setCustomFont-java.lang.String-}
Imposta il nome del carattere quando questo non è standard (diverso dai 14 caratteri standard).

### setExportItems {#setExportItems-java.lang.String:A:A-}
Imposta le opzioni per aggiungere un elenco/combobox/pulsante radio

### setFont {#setFont-com.aspose.pdf.facades.FontStyle-}
Imposta il tipo di stile del carattere di un testo di campo.

### setFontSize {#setFontSize-float-}
```
public void setFontSize(float value)
```

Imposta la dimensione di un testo di campo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore float |

### setItems {#setItems-java.lang.String:A-}
Imposta un array di stringhe, ciascuna rappresentante un'opzione di un campo combobox/elenco/pulsante radio.

### setPageNumber {#setPageNumber-int-}
```
public void setPageNumber(int value)
```

Imposta un valore intero che contiene il numero di pagina su cui si trova il campo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setPosition {#setPosition-float:A-}
```
public void setPosition(float[] value)
```

Imposta un oggetto rettangolo che contiene la posizione del campo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | array di valore float |

### setRotation {#setRotation-int-}
```
public void setRotation(int value)
```

Imposta la rotazione di un testo di campo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setTextColor {#setTextColor-java.awt.Color-}
Imposta il colore del testo del campo.

### setTextEncoding {#setTextEncoding-int-}
```
public void setTextEncoding(int value)
```

Imposta il tipo di codifica del testo {@link EncodingType} del campo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Elemento EncodingType @see EncodingType |
