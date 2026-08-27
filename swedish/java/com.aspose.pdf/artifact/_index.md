---
title: "Artefakt"
linktitle: "Artefakt"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass representerar PDF‑artefaktobjekt."
type: docs
weight: 190
url: /sv/java/com.aspose.pdf/artifact/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Artifact

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public class Artifact extends Object implements com.aspose.ms.System.IDisposable, Closeable
```

Klass representerar PDF‑artefaktobjekt.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Artifact](#Artifact-com.aspose.pdf.Artifact.ArtifactType-com.aspose.pdf.Artifact.ArtifactSubtype-) | Konstruktor för artefakt med angiven typ och subtyp |
| [Artifact](#Artifact-com.aspose.pdf.ArtifactCollection-com.aspose.pdf.Artifact.ArtifactContext-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.engine.data.IPdfDictionary-) | Denna konstruktor används när artefakt läses från sidan. |
| [Artifact](#Artifact-java.lang.String-java.lang.String-) | Konstruktor för artefakt med angiven typ och subtyp |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [beginUpdates](#beginUpdates--) | Starta borttagna uppdateringar. Använd den här funktionen om du behöver göra flera ändringar av samma artefakt för att förbättra prestanda. Vanligtvis ändras artefaktoperatorer varje gång en artefakt‑egenskap ändras. Detta orsakar att sidinnehållet ändras varje gång artefakten ändras. För att undvika denna effekt, placera alla artefaktuppdateringar mellan anropen StartUpdates/SaveUpdates. Detta gör att sidinnehållet bara ändras en gång. Artifact art = doc.getPages().get_Item(1).getArtifacts().get_Item(1); art.beginUpdates(); art.setOpacity ( 0.3f); art.setPosition ( new Point(10,10)); art.setRotation (30); art.saveUpdates(); |
| [close](#close--) | Stänger alla resurser som används av detta dokument. |
| [dispose](#dispose--) | Frigör artefakten. Denna metod är föråldrad, använd close() istället. |
| [getArtifactHorizontalAlignment](#getArtifactHorizontalAlignment--) | Hämtar horisontell justering av artefakten. Om position anges explicit (i egenskapen Position) ignoreras detta värde. |
| [getArtifactVerticalAlignment](#getArtifactVerticalAlignment--) | Hämtar vertikal justering av artefakten. Om position anges explicit (i egenskapen Position) ignoreras detta värde. |
| [getBottomMargin](#getBottomMargin--) | Hämtar bottenmarginalen för artefakten. Om position anges explicit (i egenskapen Position) ignoreras detta värde. |
| [getContents](#getContents--) | Hämtar samling av artefaktens interna operatorer. |
| [getCustomSubtype](#getCustomSubtype--) | Hämtar namn på artefaktens subtyp. Kan användas om artefaktens subtyp inte är en standardsubtyp. |
| [getCustomType](#getCustomType--) | Hämtar namn på artefaktens typ. Kan användas om artefaktens typ är icke‑standard. |
| [getForm](#getForm--) | Hämtar XForm för artefakten (om XForm används). |
| [getImage](#getImage--) | Hämtar bild av artefakten (om den finns). |
| [getLeftMargin](#getLeftMargin--) | Hämtar vänstermarginalen för artefakten. Om position anges explicit (i egenskapen Position) ignoreras detta värde. |
| [getLines](#getLines--) | Rader i flerradig textartefakt. |
| [getOpacity](#getOpacity--) | Hämtar opaciteten för artefakten. Möjliga värden ligger i intervallet 0..1. |
| [getPosition](#getPosition--) | Hämtar artefaktens position. Om denna egenskap är angiven ignoreras marginaler och justeringar. |
| [getRectangle](#getRectangle--) | Hämtar rektangeln för artefakten. |
| [getRightMargin](#getRightMargin--) | Hämtar högermarginalen för artefakten. Om position anges explicit (i egenskapen Position) ignoreras detta värde. |
| [getRotation](#getRotation--) | Hämtar artefaktens rotationsvinkel. |
| [getSubtype](#getSubtype--) | Hämtar artefaktens undertyp. Om artefakten har en icke-standard undertyp kan namnet på undertypen läsas via CustomSubtype. |
| [getText](#getText--) | Hämtar artefaktens text. |
| [getTextState](#getTextState--) | Textstatus för artefaktens text. |
| [getTopMargin](#getTopMargin--) | Hämtar artefaktens övre marginal. Om position anges explicit (i egenskapen Position) ignoreras detta värde. |
| [getType](#getType--) | Hämtar artefaktens typ. |
| [getValue](#getValue-java.lang.String-) | Hämtar artefaktens anpassade värde. |
| [isBackground](#isBackground--) | Om true placeras artefakten bakom sidans innehåll. |
| [removeValue](#removeValue-java.lang.String-) | Ta bort anpassat värde från artefakten. |
| [saveUpdates](#saveUpdates--) | Sparar alla uppdateringar i artefakten som gjordes efter anropet av BeginUpdates(). |
| [setArtifactHorizontalAlignment](#setArtifactHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Hämtar artefaktens horisontella justering. |
| [setArtifactVerticalAlignment](#setArtifactVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Ställer in artefaktens vertikala justering. |
| [setBackground](#setBackground-boolean-) | Om true placeras artefakten bakom sidans innehåll. |
| [setBottomMargin](#setBottomMargin-double-) | Ställer in artefaktens nedre marginal. |
| [setCustomSubtype](#setCustomSubtype-java.lang.String-) |  |
| [setCustomType](#setCustomType-java.lang.String-) | Ställer in namn på artefaktens typ. Kan användas om artefaktens typ är icke-standard. |
| [setImage](#setImage-java.io.InputStream-) | Ställer in bild för artefakten. |
| [setImage](#setImage-java.lang.String-) | Ställer in bild för artefakten. |
| [setLeftMargin](#setLeftMargin-double-) | Ställer in artefaktens vänstra marginal. Om position anges explicit (i egenskapen Position) ignoreras detta värde. |
| [setLinesAndState](#setLinesAndState-java.lang.String:A-com.aspose.pdf.TextState-) | Ställ in text och textegenskaper för artefakten. Tillåter att ange flera rader. |
| [setOpacity](#setOpacity-double-) | Ställer in artefaktens opacitet. Möjliga värden är i intervallet 0..1. |
| [setPageNumberReplacementString](#setPageNumberReplacementString-java.lang.String-) | Ställer in vilken sträng som ska ersättas med sidnumret. Standardvärdet är #. |
| [setPdfPage](#setPdfPage-com.aspose.pdf.Page-) | Ställer in PDF-sida som placeras på dokumentsidan som artefakt. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Ställer in artefaktens position. |
| [setRightMargin](#setRightMargin-double-) | Ställer in artefaktens högra marginal. |
| [setRotation](#setRotation-double-) | Ställer in artefaktens rotationsvinkel. |
| [setSubtype](#setSubtype-com.aspose.pdf.Artifact.ArtifactSubtype-) | Ställer in artefaktens undertyp. |
| [setText](#setText-com.aspose.pdf.facades.FormattedText-) | Ställer in artefaktens text. |
| [setText](#setText-java.lang.String-) | Ställer in artefaktens text. |
| [setTextAndState](#setTextAndState-java.lang.String-com.aspose.pdf.TextState-) | Ställ in text och textegenskaper för artifact. |
| [setTextState](#setTextState-com.aspose.pdf.TextState-) | Textstatus för artefaktens text. |
| [setTopMargin](#setTopMargin-double-) | Ställer in översta marginalen för artifact. |
| [setType](#setType-com.aspose.pdf.Artifact.ArtifactType-) | Ställer in artifact-typ. |
| [setValue](#setValue-java.lang.String-java.lang.String-) | Ställer in anpassat värde för artifact. |

### Artifact {#Artifact-com.aspose.pdf.Artifact.ArtifactType-com.aspose.pdf.Artifact.ArtifactSubtype-}
Konstruktor för artefakt med angiven typ och subtyp

### Artifact {#Artifact-com.aspose.pdf.ArtifactCollection-com.aspose.pdf.Artifact.ArtifactContext-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.engine.data.IPdfDictionary-}
Denna konstruktor används när artefakt läses från sidan.

### Artifact {#Artifact-java.lang.String-java.lang.String-}
Konstruktor för artefakt med angiven typ och subtyp

### beginUpdates {#beginUpdates--}
```
public void beginUpdates()
```

Starta borttagna uppdateringar. Använd den här funktionen om du behöver göra flera ändringar av samma artefakt för att förbättra prestanda. Vanligtvis ändras artefaktoperatorer varje gång en artefakt‑egenskap ändras. Detta orsakar att sidinnehållet ändras varje gång artefakten ändras. För att undvika denna effekt, placera alla artefaktuppdateringar mellan anropen StartUpdates/SaveUpdates. Detta gör att sidinnehållet bara ändras en gång. Artifact art = doc.getPages().get_Item(1).getArtifacts().get_Item(1); art.beginUpdates(); art.setOpacity ( 0.3f); art.setPosition ( new Point(10,10)); art.setRotation (30); art.saveUpdates();

### close {#close--}
```
public void close()
```

Stänger alla resurser som används av detta dokument.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Frigör artefakten. Denna metod är föråldrad, använd close() istället.

### getArtifactHorizontalAlignment {#getArtifactHorizontalAlignment--}
```
public HorizontalAlignment getArtifactHorizontalAlignment()
```

Hämtar horisontell justering av artefakten. Om position anges explicit (i egenskapen Position) ignoreras detta värde.

**Returns:**
HorizontalAlignment‑värde @see HorizontalAlignment

### getArtifactVerticalAlignment {#getArtifactVerticalAlignment--}
```
public VerticalAlignment getArtifactVerticalAlignment()
```

Hämtar vertikal justering av artefakten. Om position anges explicit (i egenskapen Position) ignoreras detta värde.

**Returns:**
VerticalAlignment-värde. @see VerticalAlignment

### getBottomMargin {#getBottomMargin--}
```
public double getBottomMargin()
```

Hämtar bottenmarginalen för artefakten. Om position anges explicit (i egenskapen Position) ignoreras detta värde.

**Returns:**
nedre marginal.

### getContents {#getContents--}
```
public List < Operator > getContents()
```

Hämtar samling av artefaktens interna operatorer.

**Returns:**
lista artifact interna operatorer.

### getCustomSubtype {#getCustomSubtype--}
```
public String getCustomSubtype()
```

Hämtar namn på artefaktens subtyp. Kan användas om artefaktens subtyp inte är en standardsubtyp.

**Returns:**
String värde

### getCustomType {#getCustomType--}
```
public String getCustomType()
```

Hämtar namn på artefaktens typ. Kan användas om artefaktens typ är icke‑standard.

**Returns:**
String artifact namn

### getForm {#getForm--}
```
public XForm getForm()
```

Hämtar XForm för artefakten (om XForm används).

**Returns:**
XForm‑objekt

### getImage {#getImage--}
```
public XImage getImage()
```

Hämtar bild av artefakten (om den finns).

**Returns:**
XImage-objekt

### getLeftMargin {#getLeftMargin--}
```
public double getLeftMargin()
```

Hämtar vänstermarginalen för artefakten. Om position anges explicit (i egenskapen Position) ignoreras detta värde.

**Returns:**
vänster marginal för artifact.

### getLines {#getLines--}
```
public final List < String > getLines()
```

Rader i flerradig textartefakt.

**Returns:**
Lista med Strings

### getOpacity {#getOpacity--}
```
public double getOpacity()
```

Hämtar opaciteten för artefakten. Möjliga värden ligger i intervallet 0..1.

**Returns:**
opacitet för artifact.

### getPosition {#getPosition--}
```
public Point getPosition()
```

Hämtar artefaktens position. Om denna egenskap är angiven ignoreras marginaler och justeringar.

**Returns:**
artifact-position.

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Hämtar rektangeln för artefakten.

**Returns:**
Rectangle‑objekt

### getRightMargin {#getRightMargin--}
```
public double getRightMargin()
```

Hämtar högermarginalen för artefakten. Om position anges explicit (i egenskapen Position) ignoreras detta värde.

**Returns:**
höger marginal för artifact.

### getRotation {#getRotation--}
```
public double getRotation()
```

Hämtar artefaktens rotationsvinkel.

**Returns:**
artifact rotationsvinkel.

### getSubtype {#getSubtype--}
```
public Artifact.ArtifactSubtype getSubtype()
```

Hämtar artefaktens undertyp. Om artefakten har en icke-standard undertyp kan namnet på undertypen läsas via CustomSubtype.

**Returns:**
artifact-subtyp. @see ArtifactSubtype

### getText {#getText--}
```
public String getText()
```

Hämtar artefaktens text.

**Returns:**
String värde

### getTextState {#getTextState--}
```
public final TextState getTextState()
```

Textstatus för artefaktens text.

**Returns:**
TextState-instans

### getTopMargin {#getTopMargin--}
```
public double getTopMargin()
```

Hämtar artefaktens övre marginal. Om position anges explicit (i egenskapen Position) ignoreras detta värde.

**Returns:**
övre marginal för artifact.

### getType {#getType--}
```
public Artifact.ArtifactType getType()
```

Hämtar artefaktens typ.

**Returns:**
artifact-typvärde. @see ArtifactType

### getValue {#getValue-java.lang.String-}
Hämtar artefaktens anpassade värde.

### isBackground {#isBackground--}
```
public boolean isBackground()
```

Om true placeras artefakten bakom sidans innehåll.

**Returns:**
booleskt värde

### removeValue {#removeValue-java.lang.String-}
Ta bort anpassat värde från artefakten.

### saveUpdates {#saveUpdates--}
```
public void saveUpdates()
```

Sparar alla uppdateringar i artefakten som gjordes efter anropet av BeginUpdates().

### setArtifactHorizontalAlignment {#setArtifactHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Hämtar artefaktens horisontella justering.

### setArtifactVerticalAlignment {#setArtifactVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Ställer in artefaktens vertikala justering.

### setBackground {#setBackground-boolean-}
```
public void setBackground(boolean value)
```

Om true placeras artefakten bakom sidans innehåll.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setBottomMargin {#setBottomMargin-double-}
```
public void setBottomMargin(double value)
```

Ställer in artefaktens nedre marginal.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | nedre marginal. |

### setCustomSubtype {#setCustomSubtype-java.lang.String-}


### setCustomType {#setCustomType-java.lang.String-}
Ställer in namn på artefaktens typ. Kan användas om artefaktens typ är icke-standard.

### setImage {#setImage-java.io.InputStream-}
Ställer in bild för artefakten.

### setImage {#setImage-java.lang.String-}
Ställer in bild för artefakten.

### setLeftMargin {#setLeftMargin-double-}
```
public void setLeftMargin(double value)
```

Ställer in artefaktens vänstra marginal. Om position anges explicit (i egenskapen Position) ignoreras detta värde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | vänster marginal för artifact. |

### setLinesAndState {#setLinesAndState-java.lang.String:A-com.aspose.pdf.TextState-}
Ställ in text och textegenskaper för artefakten. Tillåter att ange flera rader.

### setOpacity {#setOpacity-double-}
```
public void setOpacity(double value)
```

Ställer in artefaktens opacitet. Möjliga värden är i intervallet 0..1.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | opacitet för artifact. |

### setPageNumberReplacementString {#setPageNumberReplacementString-java.lang.String-}
Ställer in vilken sträng som ska ersättas med sidnumret. Standardvärdet är #.

### setPdfPage {#setPdfPage-com.aspose.pdf.Page-}
Ställer in PDF-sida som placeras på dokumentsidan som artefakt.

### setPosition {#setPosition-com.aspose.pdf.Point-}
Ställer in artefaktens position.

### setRightMargin {#setRightMargin-double-}
```
public void setRightMargin(double value)
```

Ställer in artefaktens högra marginal.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | höger marginal för artifact. |

### setRotation {#setRotation-double-}
```
public void setRotation(double value)
```

Ställer in artefaktens rotationsvinkel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | artifact rotationsvinkel. |

### setSubtype {#setSubtype-com.aspose.pdf.Artifact.ArtifactSubtype-}
Ställer in artefaktens undertyp.

### setText {#setText-com.aspose.pdf.facades.FormattedText-}
Ställer in artefaktens text.

### setText {#setText-java.lang.String-}
Ställer in artefaktens text.

### setTextAndState {#setTextAndState-java.lang.String-com.aspose.pdf.TextState-}
Ställ in text och textegenskaper för artifact.

### setTextState {#setTextState-com.aspose.pdf.TextState-}
Textstatus för artefaktens text.

### setTopMargin {#setTopMargin-double-}
```
public void setTopMargin(double value)
```

Ställer in översta marginalen för artifact.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | övre marginal för artifact. |

### setType {#setType-com.aspose.pdf.Artifact.ArtifactType-}
Ställer in artifact-typ.

### setValue {#setValue-java.lang.String-java.lang.String-}
Ställer in anpassat värde för artifact.
