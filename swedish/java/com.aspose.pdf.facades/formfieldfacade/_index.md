---
title: "FormFieldFacade"
linktitle: "FormFieldFacade"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass för att representera fältegenskaper."
type: docs
weight: 220
url: /sv/java/com.aspose.pdf.facades/formfieldfacade/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.FormFieldFacade

```
public final class FormFieldFacade extends Object
```

Klass för att representera fältegenskaper.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [ALIGN_BOTTOM](#ALIGN_BOTTOM) | Definierar vertikal justering som bottenstil. |
| [ALIGN_CENTER](#ALIGN_CENTER) | Definierar justering till centrerad stil. |
| [ALIGN_JUSTIFIED](#ALIGN_JUSTIFIED) | Definierar textjusteringens stil. |
| [ALIGN_LEFT](#ALIGN_LEFT) | Definierar justering till vänster stil. |
| [ALIGN_MIDDLE](#ALIGN_MIDDLE) | Definierar vertikal justering som mittstil. |
| [ALIGN_RIGHT](#ALIGN_RIGHT) | Definierar justering till höger stil. |
| [ALIGN_TOP](#ALIGN_TOP) | Definierar vertikal justering som toppstil. |
| [ALIGN_UNDEFINED](#ALIGN_UNDEFINED) | Odefinierad justeringsstil. |
| [BORDER_STYLE_BEVELED](#BORDER_STYLE_BEVELED) | Definierar en avfasad kantstil. |
| [BORDER_STYLE_DASHED](#BORDER_STYLE_DASHED) | Definierar en streckad kantstil. |
| [BORDER_STYLE_INSET](#BORDER_STYLE_INSET) | Definierar en infälld kantstil. |
| [BORDER_STYLE_SOLID](#BORDER_STYLE_SOLID) | Definierar en solid kantstil. |
| [BORDER_STYLE_UNDEFINED](#BORDER_STYLE_UNDEFINED) | Odefinierad kantstil. |
| [BORDER_STYLE_UNDERLINE](#BORDER_STYLE_UNDERLINE) | Definierar en understruken kantstil. |
| [BORDER_WIDTH_MEDIUM](#BORDER_WIDTH_MEDIUM) | Definierar en medelbredd på kanten. |
| [BORDER_WIDTH_THICK](#BORDER_WIDTH_THICK) | Definierar en tjock kantbredd. |
| [BORDER_WIDTH_THIN](#BORDER_WIDTH_THIN) | Definierar en tunn kantbredd. |
| [BORDER_WIDTH_UNDEFINED](#BORDER_WIDTH_UNDEFINED) | Odefinierad kantbredd. |
| [BORDER_WIDTH_UNDIFIED](#BORDER_WIDTH_UNDIFIED) | Odefinierad kantbredd. |
| [CHECK_BOX_STYLE_CHECK](#CHECK_BOX_STYLE_CHECK) | Definierar formen på ett kryssrutan-fält när det är markerat. |
| [CHECK_BOX_STYLE_CIRCLE](#CHECK_BOX_STYLE_CIRCLE) | Definierar en cirkelkryssruta-stil. |
| [CHECK_BOX_STYLE_CROSS](#CHECK_BOX_STYLE_CROSS) | Definierar en korskryssruta-stil. |
| [CHECK_BOX_STYLE_DIAMOND](#CHECK_BOX_STYLE_DIAMOND) | Definierar en diamantkryssruta-stil. |
| [CHECK_BOX_STYLE_SQUARE](#CHECK_BOX_STYLE_SQUARE) | Definierar en fyrkantig kryssruta-stil. |
| [CHECK_BOX_STYLE_STAR](#CHECK_BOX_STYLE_STAR) | Definierar en stjärnkryssruta-stil. |
| [CHECK_BOX_STYLE_UNDEFINED](#CHECK_BOX_STYLE_UNDEFINED) | Definierar en odefinierad kryssruta-stil. |

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [FormFieldFacade](#FormFieldFacade--) |  |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAlignment](#getAlignment--) | Hämta justeringen av ett fälttext, standard är vänsterjustering. |
| [getBackgroudColor](#getBackgroudColor--) | Föråldrad egenskap. Använd BackgroundColor. Denna metod är föråldrad. |
| [getBackgroundColor](#getBackgroundColor--) | Hämta färgen på ett fältbakgrund, standard är vit. |
| [getBorderColor](#getBorderColor--) | Hämtar färgen på ett fältkant. |
| [getBorderStyle](#getBorderStyle--) | Hämtar stil på ett fältkant. |
| [getBorderWidth](#getBorderWidth--) | Hämta bredden på ett fältkant. |
| [getBox](#getBox--) | Hämta ett rektangelobjekt som innehåller fältets position. |
| [getButtonStyle](#getButtonStyle--) | Hämta stilen på kryssruta- eller radioknappsfält, definierad av FormFieldFacade.CheckBoxStyle*. |
| [getCaption](#getCaption--) | Hämta den normala rubriken för formulärfältet. |
| [getCustomFont](#getCustomFont--) | Hämtar namnet på teckensnittet när det är icke-standard (annat än de 14 standardteckensnitten). |
| [getExportItems](#getExportItems--) | Hämta alternativen för att lägga till en lista/kombinationsruta/radioknapp |
| [getFont](#getFont--) | Hämtar teckensnittsstiltypen för ett fälttext. |
| [getFontSize](#getFontSize--) | Hämtar storleken på ett fälttext. |
| [getItems](#getItems--) | Hämta en array av strängar, där varje representerar ett alternativ för ett kombinationsruta/lista/radioknapp-fält. |
| [getPageNumber](#getPageNumber--) | Hämta ett heltalsvärde som innehåller sidnumret där fältet är placerat. |
| [getPosition](#getPosition--) | Hämta ett rektangelobjekt som innehåller fältets position. |
| [getRotation](#getRotation--) | Hämta rotationen för en fälttext. |
| [getTextColor](#getTextColor--) | Hämta färgen på fälttexten. |
| [getTextEncoding](#getTextEncoding--) | Hämta textkodningstypen för fälttexten. |
| [reset](#reset--) | Återställ alla visuella attribut till tomt värde. |
| [setAlignment](#setAlignment-int-) | Ställ in justeringen för en fälttext, standard är vänsterjustering. |
| [setBackgroudColor](#setBackgroudColor-java.awt.Color-) | Föråldrad. |
| [setBackgroundColor](#setBackgroundColor-java.awt.Color-) | Ställ in färgen på ett fältbakgrund, standard är vit. |
| [setBorderColor](#setBorderColor-java.awt.Color-) | Ställer in färgen på en fältgräns. |
| [setBorderStyle](#setBorderStyle-int-) | Ställer in stil för en fältgräns. |
| [setBorderWidth](#setBorderWidth-float-) | Ställ in bredden på en fältgräns. |
| [setBox](#setBox-java.awt.Rectangle-) | Ställ in ett rektangelobjekt som håller fältets plats. |
| [setButtonStyle](#setButtonStyle-int-) | Ställ in stilen för kryssruta- eller radioknappfält, definierad av FormFieldFacade.CheckBoxStyle*. |
| [setCaption](#setCaption-java.lang.String-) | Ställ in den normala rubriken för formulärfältet. |
| [setCustomFont](#setCustomFont-java.lang.String-) | Ställer in namnet på teckensnittet när det är icke‑standard (annat än de 14 standardteckensnitten). |
| [setExportItems](#setExportItems-java.lang.String:A:A-) | Ställ in alternativen för att lägga till en lista/kombinationsruta/radioknapp. |
| [setFont](#setFont-com.aspose.pdf.facades.FontStyle-) | Ställer in teckensnittsstilstypen för en fälttext. |
| [setFontSize](#setFontSize-float-) | Ställer in storleken på en fälttext. |
| [setItems](#setItems-java.lang.String:A-) | Ställ in en array av strängar, där varje representerar ett alternativ för ett kombinationsruta/lista/radioknappfält. |
| [setPageNumber](#setPageNumber-int-) | Ställ in ett heltal som anger antalet sida där fältet är placerat. |
| [setPosition](#setPosition-float:A-) | Ställ in ett rektangelobjekt som håller fältets plats. |
| [setRotation](#setRotation-int-) | Ställ in rotationen för en fälttext. |
| [setTextColor](#setTextColor-java.awt.Color-) | Ställ in färgen på fälttexten. |
| [setTextEncoding](#setTextEncoding-int-) | Ställ in {@link EncodingType} textkodningstyp för fälttexten. |

### ALIGN_BOTTOM {#ALIGN_BOTTOM}
```
public static final int ALIGN_BOTTOM
```

Definierar vertikal justering som bottenstil.

### ALIGN_CENTER {#ALIGN_CENTER}
```
public static final int ALIGN_CENTER
```

Definierar justering till centrerad stil.

### ALIGN_JUSTIFIED {#ALIGN_JUSTIFIED}
```
public static final int ALIGN_JUSTIFIED
```

Definierar textjusteringens stil.

### ALIGN_LEFT {#ALIGN_LEFT}
```
public static final int ALIGN_LEFT
```

Definierar justering till vänster stil.

### ALIGN_MIDDLE {#ALIGN_MIDDLE}
```
public static final int ALIGN_MIDDLE
```

Definierar vertikal justering som mittstil.

### ALIGN_RIGHT {#ALIGN_RIGHT}
```
public static final int ALIGN_RIGHT
```

Definierar justering till höger stil.

### ALIGN_TOP {#ALIGN_TOP}
```
public static final int ALIGN_TOP
```

Definierar vertikal justering som toppstil.

### ALIGN_UNDEFINED {#ALIGN_UNDEFINED}
```
public static final int ALIGN_UNDEFINED
```

Odefinierad justeringsstil.

### BORDER_STYLE_BEVELED {#BORDER_STYLE_BEVELED}
```
public static final int BORDER_STYLE_BEVELED
```

Definierar en avfasad kantstil.

### BORDER_STYLE_DASHED {#BORDER_STYLE_DASHED}
```
public static final int BORDER_STYLE_DASHED
```

Definierar en streckad kantstil.

### BORDER_STYLE_INSET {#BORDER_STYLE_INSET}
```
public static final int BORDER_STYLE_INSET
```

Definierar en infälld kantstil.

### BORDER_STYLE_SOLID {#BORDER_STYLE_SOLID}
```
public static final int BORDER_STYLE_SOLID
```

Definierar en solid kantstil.

### BORDER_STYLE_UNDEFINED {#BORDER_STYLE_UNDEFINED}
```
public static final int BORDER_STYLE_UNDEFINED
```

Odefinierad kantstil.

### BORDER_STYLE_UNDERLINE {#BORDER_STYLE_UNDERLINE}
```
public static final int BORDER_STYLE_UNDERLINE
```

Definierar en understruken kantstil.

### BORDER_WIDTH_MEDIUM {#BORDER_WIDTH_MEDIUM}
```
public static final float BORDER_WIDTH_MEDIUM
```

Definierar en medelbredd på kanten.

### BORDER_WIDTH_THICK {#BORDER_WIDTH_THICK}
```
public static final float BORDER_WIDTH_THICK
```

Definierar en tjock kantbredd.

### BORDER_WIDTH_THIN {#BORDER_WIDTH_THIN}
```
public static final float BORDER_WIDTH_THIN
```

Definierar en tunn kantbredd.

### BORDER_WIDTH_UNDEFINED {#BORDER_WIDTH_UNDEFINED}
```
public static final float BORDER_WIDTH_UNDEFINED
```

Odefinierad kantbredd.

### BORDER_WIDTH_UNDIFIED {#BORDER_WIDTH_UNDIFIED}
```
@Deprecated public static final float BORDER_WIDTH_UNDIFIED
```

Odefinierad kantbredd.

### CHECK_BOX_STYLE_CHECK {#CHECK_BOX_STYLE_CHECK}
```
public static final int CHECK_BOX_STYLE_CHECK
```

Definierar formen på ett kryssrutan-fält när det är markerat.

### CHECK_BOX_STYLE_CIRCLE {#CHECK_BOX_STYLE_CIRCLE}
```
public static final int CHECK_BOX_STYLE_CIRCLE
```

Definierar en cirkelkryssruta-stil.

### CHECK_BOX_STYLE_CROSS {#CHECK_BOX_STYLE_CROSS}
```
public static final int CHECK_BOX_STYLE_CROSS
```

Definierar en korskryssruta-stil.

### CHECK_BOX_STYLE_DIAMOND {#CHECK_BOX_STYLE_DIAMOND}
```
public static final int CHECK_BOX_STYLE_DIAMOND
```

Definierar en diamantkryssruta-stil.

### CHECK_BOX_STYLE_SQUARE {#CHECK_BOX_STYLE_SQUARE}
```
public static final int CHECK_BOX_STYLE_SQUARE
```

Definierar en fyrkantig kryssruta-stil.

### CHECK_BOX_STYLE_STAR {#CHECK_BOX_STYLE_STAR}
```
public static final int CHECK_BOX_STYLE_STAR
```

Definierar en stjärnkryssruta-stil.

### CHECK_BOX_STYLE_UNDEFINED {#CHECK_BOX_STYLE_UNDEFINED}
```
public static final int CHECK_BOX_STYLE_UNDEFINED
```

Definierar en odefinierad kryssruta-stil.

### FormFieldFacade {#FormFieldFacade--}
```
public FormFieldFacade()
```



### getAlignment {#getAlignment--}
```
public int getAlignment()
```

Hämta justeringen av ett fälttext, standard är vänsterjustering.

**Returns:**
int‑värde

### getBackgroudColor {#getBackgroudColor--}
```
@Deprecated public Color getBackgroudColor()
```

Föråldrad egenskap. Använd BackgroundColor. Denna metod är föråldrad.

**Returns:**
bakgrundsfärg

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

Hämta färgen på ett fältbakgrund, standard är vit.

**Returns:**
Färgelement

### getBorderColor {#getBorderColor--}
```
public Color getBorderColor()
```

Hämtar färgen på ett fältkant.

**Returns:**
färg på en fältgräns.

### getBorderStyle {#getBorderStyle--}
```
public int getBorderStyle()
```

Hämtar stil på ett fältkant.

**Returns:**
stil för en fältgräns.

### getBorderWidth {#getBorderWidth--}
```
public float getBorderWidth()
```

Hämta bredden på ett fältkant.

**Returns:**
bredd på en fältgräns.

### getBox {#getBox--}
```
public Rectangle getBox()
```

Hämta ett rektangelobjekt som innehåller fältets position.

**Returns:**
Rektangel-element

### getButtonStyle {#getButtonStyle--}
```
public int getButtonStyle()
```

Hämta stilen på kryssruta- eller radioknappsfält, definierad av FormFieldFacade.CheckBoxStyle*.

**Returns:**
int‑värde

### getCaption {#getCaption--}
```
public String getCaption()
```

Hämta den normala rubriken för formulärfältet.

**Returns:**
String värde

### getCustomFont {#getCustomFont--}
```
public String getCustomFont()
```

Hämtar namnet på teckensnittet när det är icke-standard (annat än de 14 standardteckensnitten).

**Returns:**
String värde

### getExportItems {#getExportItems--}
```
public String [][] getExportItems()
```

Hämta alternativen för att lägga till en lista/kombinationsruta/radioknapp

**Returns:**
array av String-värde

### getFont {#getFont--}
```
public FontStyle getFont()
```

Hämtar teckensnittsstiltypen för ett fälttext.

**Returns:**
FontStyle-element @see FontStyle

### getFontSize {#getFontSize--}
```
public float getFontSize()
```

Hämtar storleken på ett fälttext.

**Returns:**
flyttalsvärde

### getItems {#getItems--}
```
public String [] getItems()
```

Hämta en array av strängar, där varje representerar ett alternativ för ett kombinationsruta/lista/radioknapp-fält.

**Returns:**
array av String-värde

### getPageNumber {#getPageNumber--}
```
public int getPageNumber()
```

Hämta ett heltalsvärde som innehåller sidnumret där fältet är placerat.

**Returns:**
int‑värde

### getPosition {#getPosition--}
```
public float[] getPosition()
```

Hämta ett rektangelobjekt som innehåller fältets position.

**Returns:**
array av float-värde

### getRotation {#getRotation--}
```
public int getRotation()
```

Hämta rotationen för en fälttext.

**Returns:**
int‑värde

### getTextColor {#getTextColor--}
```
public Color getTextColor()
```

Hämta färgen på fälttexten.

**Returns:**
Färgelement

### getTextEncoding {#getTextEncoding--}
```
public int getTextEncoding()
```

Hämta textkodningstypen för fälttexten.

**Returns:**
EncodingType-element @see EncodingType

### reset {#reset--}
```
public void reset()
```

Återställ alla visuella attribut till tomt värde.

### setAlignment {#setAlignment-int-}
```
public void setAlignment(int value)
```

Ställ in justeringen för en fälttext, standard är vänsterjustering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setBackgroudColor {#setBackgroudColor-java.awt.Color-}
Föråldrad.

### setBackgroundColor {#setBackgroundColor-java.awt.Color-}
Ställ in färgen på ett fältbakgrund, standard är vit.

### setBorderColor {#setBorderColor-java.awt.Color-}
Ställer in färgen på en fältgräns.

### setBorderStyle {#setBorderStyle-int-}
```
public void setBorderStyle(int value)
```

Ställer in stil för en fältgräns.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | stil för en fältgräns. |

### setBorderWidth {#setBorderWidth-float-}
```
public void setBorderWidth(float value)
```

Ställ in bredden på en fältgräns.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | bredd på en fältgräns. |

### setBox {#setBox-java.awt.Rectangle-}
Ställ in ett rektangelobjekt som håller fältets plats.

### setButtonStyle {#setButtonStyle-int-}
```
public void setButtonStyle(int value)
```

Ställ in stilen för kryssruta- eller radioknappfält, definierad av FormFieldFacade.CheckBoxStyle*.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setCaption {#setCaption-java.lang.String-}
Ställ in den normala rubriken för formulärfältet.

### setCustomFont {#setCustomFont-java.lang.String-}
Ställer in namnet på teckensnittet när det är icke‑standard (annat än de 14 standardteckensnitten).

### setExportItems {#setExportItems-java.lang.String:A:A-}
Ställ in alternativen för att lägga till en lista/kombinationsruta/radioknapp.

### setFont {#setFont-com.aspose.pdf.facades.FontStyle-}
Ställer in teckensnittsstilstypen för en fälttext.

### setFontSize {#setFontSize-float-}
```
public void setFontSize(float value)
```

Ställer in storleken på en fälttext.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | flyttalsvärde |

### setItems {#setItems-java.lang.String:A-}
Ställ in en array av strängar, där varje representerar ett alternativ för ett kombinationsruta/lista/radioknappfält.

### setPageNumber {#setPageNumber-int-}
```
public void setPageNumber(int value)
```

Ställ in ett heltal som anger antalet sida där fältet är placerat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setPosition {#setPosition-float:A-}
```
public void setPosition(float[] value)
```

Ställ in ett rektangelobjekt som håller fältets plats.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | array av float-värde |

### setRotation {#setRotation-int-}
```
public void setRotation(int value)
```

Ställ in rotationen för en fälttext.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setTextColor {#setTextColor-java.awt.Color-}
Ställ in färgen på fälttexten.

### setTextEncoding {#setTextEncoding-int-}
```
public void setTextEncoding(int value)
```

Ställ in {@link EncodingType} textkodningstyp för fälttexten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | EncodingType-element @see EncodingType |
