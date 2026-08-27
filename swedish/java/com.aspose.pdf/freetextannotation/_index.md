---
title: "FreeTextAnnotation"
linktitle: "FreeTextAnnotation"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en fri text‑annotation som visar text direkt på sidan. Till skillnad från en vanlig text‑annotation har en fri text‑annotation inget öppet eller stängt tillstånd; istället för."
type: docs
weight: 1790
url: /sv/java/com.aspose.pdf/freetextannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FreeTextAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FreeTextAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.MarkupAnnotation com.aspose.pdf.FreeTextAnnotation, com.aspose.pdf.MarkupAnnotation, com.aspose.pdf.FreeTextAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable, com.aspose.pdf.engine.ITitledAnnotation

```
public final class FreeTextAnnotation extends MarkupAnnotation
```

Representerar en fri textanteckning som visar text direkt på sidan. Till skillnad från en vanlig textanteckning har en fri textanteckning inget öppet eller stängt tillstånd; istället för att visas i ett popup‑fönster är texten alltid synlig.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [FreeTextAnnotation](#FreeTextAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.DefaultAppearance-) | Konstruktor att använda med Generator. |
| [FreeTextAnnotation](#FreeTextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.DefaultAppearance-) | Skapar en ny FreeText‑annotation på den angivna sidan. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepterar besökarobjekt för att bearbeta annotationen. |
| [getAnnotationType](#getAnnotationType--) | Hämtar typ av annotering. |
| [getCallout](#getCallout--) | Array av punkt som specificerar förklaringslinjen. |
| [getDefaultAppearance](#getDefaultAppearance--) | Hämtar standardutseende‑strängen som ska användas vid formatering av texten. |
| [getDefaultAppearanceObject](#getDefaultAppearanceObject--) | Objekt som representerar standardutseendet för FreeText‑annotation. |
| [getDefaultStyle](#getDefaultStyle--) | Hämtar en standard‑stilssträng. |
| [getEndingStyle](#getEndingStyle--) | Hämtar linjeavslutningsstil för linjeavslutningspunkt. |
| [getIntent](#getIntent--) | Hämtar avsikten med den fria text‑annotation. |
| [getJustification](#getJustification--) | Hämtar en kod som specificerar formen av quadding (justering) som ska användas vid visning av annotationens text. |
| [getRotate](#getRotate--) | Vinkel för annotationens rotation. |
| [getStartingStyle](#getStartingStyle--) | Hämtar eller anger linjeavslutningsstil för linjeavslutningspunkt. Denna egenskap är föråldrad, vänligen använd EndingStyle. |
| [getTextRectangle](#getTextRectangle--) | Rektangel som beskriver de numeriska skillnaderna mellan två rektanglar: Rect‑posten för annoteringen och en rektangel som finns inom den rektangeln. Den inre rektangeln är där annoteringens text ska visas. |
| [getTextStyle](#getTextStyle--) | Hämtar eller anger stil för texten i utseendet. När textstilen ändras uppdateras textens utseende. |
| [isValidXml](#isValidXml-java.lang.String-) |  |
| [setCallout](#setCallout-com.aspose.pdf.Point:A-) | Array av punkt som specificerar förklaringslinjen. |
| [setDefaultAppearance](#setDefaultAppearance-java.lang.String-) | Anger standardutseende‑strängen som ska användas vid formatering av texten. |
| [setDefaultStyle](#setDefaultStyle-java.lang.String-) | Anger en standardstilsträng. |
| [setEndingStyle](#setEndingStyle-com.aspose.pdf.LineEnding-) | Anger linjeändningsstil för linjeändningspunkten. |
| [setIntent](#setIntent-com.aspose.pdf.FreeTextIntent-) | Anger avsikten med fri‑text‑annoteringen. |
| [setJustification](#setJustification-com.aspose.pdf.Justification-) | Anger en kod som specificerar formen av justering (quadding) som ska användas vid visning av annoteringens text. |
| [setRotate](#setRotate-com.aspose.pdf.Rotation-) | Vinkel för annotationens rotation. |
| [setStartingStyle](#setStartingStyle-com.aspose.pdf.LineEnding-) | Hämtar eller anger linjeavslutningsstil för linjeavslutningspunkt. Denna egenskap är föråldrad, vänligen använd EndingStyle. |
| [setTextRectangle](#setTextRectangle-com.aspose.pdf.Rectangle-) | Rektangel som beskriver de numeriska skillnaderna mellan två rektanglar: Rect‑posten för annoteringen och en rektangel som finns inom den rektangeln. Den inre rektangeln är där annoteringens text ska visas. |
| [setTextStyle](#setTextStyle-int-int-int-) | Anger formateringen som bestäms av parametern textStyle för ett textfragment från index fromInd till index toInd. |
| [setTextStyle](#setTextStyle-int-java.lang.String-double-java.awt.Color-) | Anger formateringen som bestäms av parametern textStyle för all annoteringstext. |
| [setTextStyle](#setTextStyle-com.aspose.pdf.TextStyle-) | Anger stil för texten i utseendet. När textstilen ändras uppdateras textens utseende. |
| [updateAppearance](#updateAppearance--) | Uppdaterar utseendet efter att text har ändrats/flyttats. |

### FreeTextAnnotation {#FreeTextAnnotation-com.aspose.pdf.IDocument-com.aspose.pdf.DefaultAppearance-}
Konstruktor att använda med Generator.

### FreeTextAnnotation {#FreeTextAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.DefaultAppearance-}
Skapar en ny FreeText‑annotation på den angivna sidan.

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepterar besökarobjekt för att bearbeta annotationen.

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

Hämtar typ av annotering.

**Returns:**
int‑värde

### getCallout {#getCallout--}
```
public final Point [] getCallout()
```

Array av punkt som specificerar förklaringslinjen.

**Returns:**
array av Point

### getDefaultAppearance {#getDefaultAppearance--}
```
public String getDefaultAppearance()
```

Hämtar standardutseende‑strängen som ska användas vid formatering av texten.

**Returns:**
String värde

### getDefaultAppearanceObject {#getDefaultAppearanceObject--}
```
public final DefaultAppearance getDefaultAppearanceObject()
```

Objekt som representerar standardutseendet för FreeText‑annotation.

**Returns:**
DefaultAppearance‑objekt

### getDefaultStyle {#getDefaultStyle--}
```
public String getDefaultStyle()
```

Hämtar en standard‑stilssträng.

**Returns:**
String värde

### getEndingStyle {#getEndingStyle--}
```
public LineEnding getEndingStyle()
```

Hämtar linjeavslutningsstil för linjeavslutningspunkt.

**Returns:**
LineEnding‑värde @see LineEnding

### getIntent {#getIntent--}
```
public FreeTextIntent getIntent()
```

Hämtar avsikten med den fria text‑annotation.

**Returns:**
int‑värde @see FreeTextIntent

### getJustification {#getJustification--}
```
public Justification getJustification()
```

Hämtar en kod som specificerar formen av quadding (justering) som ska användas vid visning av annotationens text.

**Returns:**
int‑värde @see Justification

### getRotate {#getRotate--}
```
public Rotation getRotate()
```

Vinkel för annotationens rotation.

**Returns:**
Rotation‑element @see Rotation

### getStartingStyle {#getStartingStyle--}
```
public final LineEnding getStartingStyle()
```

Hämtar eller anger linjeavslutningsstil för linjeavslutningspunkt. Denna egenskap är föråldrad, vänligen använd EndingStyle.

**Returns:**
LineEnding‑element

### getTextRectangle {#getTextRectangle--}
```
public final Rectangle getTextRectangle()
```

Rektangel som beskriver de numeriska skillnaderna mellan två rektanglar: Rect‑posten för annoteringen och en rektangel som finns inom den rektangeln. Den inre rektangeln är där annoteringens text ska visas.

**Returns:**
Rektangelinstans

### getTextStyle {#getTextStyle--}
```
public TextStyle getTextStyle()
```

Hämtar eller anger stil för texten i utseendet. När textstilen ändras uppdateras textens utseende.

**Returns:**
TextStyle‑värde

### isValidXml {#isValidXml-java.lang.String-}


### setCallout {#setCallout-com.aspose.pdf.Point:A-}
Array av punkt som specificerar förklaringslinjen.

### setDefaultAppearance {#setDefaultAppearance-java.lang.String-}
Anger standardutseende‑strängen som ska användas vid formatering av texten.

### setDefaultStyle {#setDefaultStyle-java.lang.String-}
Anger en standardstilsträng.

### setEndingStyle {#setEndingStyle-com.aspose.pdf.LineEnding-}
Anger linjeändningsstil för linjeändningspunkten.

### setIntent {#setIntent-com.aspose.pdf.FreeTextIntent-}
Anger avsikten med fri‑text‑annoteringen.

### setJustification {#setJustification-com.aspose.pdf.Justification-}
Anger en kod som specificerar formen av justering (quadding) som ska användas vid visning av annoteringens text.

### setRotate {#setRotate-com.aspose.pdf.Rotation-}
Vinkel för annotationens rotation.

### setStartingStyle {#setStartingStyle-com.aspose.pdf.LineEnding-}
Hämtar eller anger linjeavslutningsstil för linjeavslutningspunkt. Denna egenskap är föråldrad, vänligen använd EndingStyle.

### setTextRectangle {#setTextRectangle-com.aspose.pdf.Rectangle-}
Rektangel som beskriver de numeriska skillnaderna mellan två rektanglar: Rect‑posten för annoteringen och en rektangel som finns inom den rektangeln. Den inre rektangeln är där annoteringens text ska visas.

### setTextStyle {#setTextStyle-int-int-int-}
```
public final void setTextStyle(int fromInd, int toInd, int textStyles)
```

Anger formateringen som bestäms av parametern textStyle för ett textfragment från index fromInd till index toInd.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fromInd |  | Startindex för textfragmentet (från 0). |
| toInd |  | Slutindex för textfragmentet (räknat från 0, detta är inte inkluderat). |
| textStyles |  | Stil(ar) som tillämpas på textfragmentet. |

### setTextStyle {#setTextStyle-int-java.lang.String-double-java.awt.Color-}
Anger formateringen som bestäms av parametern textStyle för all annoteringstext.

### setTextStyle {#setTextStyle-com.aspose.pdf.TextStyle-}
Anger stil för texten i utseendet. När textstilen ändras uppdateras textens utseende.

### updateAppearance {#updateAppearance--}
```
public void updateAppearance()
```

Uppdaterar utseendet efter att text har ändrats/flyttats.
