---
title: "Page"
linktitle: "Page"
second_title: "Aspose.PDF för Java API-referens"
description: "Klassen som representerar en sida i ett PDF‑dokument."
type: docs
weight: 3310
url: /sv/java/com.aspose.pdf/page/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Page

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.IOperatorContainer, Closeable, AutoCloseable

```
public final class Page extends Object implements com.aspose.ms.System.IDisposable, Closeable , com.aspose.pdf.engine.IOperatorContainer
```

Klassen som representerar en sida i ett PDF‑dokument.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Accepterar {@code AnnotationSelector} besökarobjekt som tillhandahåller funktionalitet för att arbeta med annotationer. |
| [accept](#accept-com.aspose.pdf.ImagePlacementAbsorber-) | Accepterar {@code ImagePlacementAbsorber} besökarobjekt som tillhandahåller funktionalitet för att arbeta med bildplaceringsobjekt. |
| [accept](#accept-com.aspose.pdf.TextAbsorber-) | Accepterar {@code TextAbsorber} besökarobjekt som tillhandahåller funktionalitet för att arbeta med textobjekt. |
| [accept](#accept-com.aspose.pdf.TextFragmentAbsorber-) | Accepterar {@code TextFragmentAbsorber} besökarobjekt som tillhandahåller funktionalitet för att arbeta med textobjekt. |
| [addGraphics](#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-) | Lägger till grafik på sidan. Fungerar snabbare än att lägga till element ett i taget med GraphicElement#addOnPage(Page)-metoden. |
| [addGraphics](#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-com.aspose.pdf.Rectangle-) | Lägger till grafik på sidan. Fungerar snabbare än att lägga till element ett i taget med GraphicElement#addOnPage(Page)-metoden. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-) | Lägger till en bild på sidan och placerar den i mitten av den angivna rektangeln samtidigt som bildens proportioner bevaras. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-) | Lägger till en sökbar bild på sidan och placerar den i mitten av den angivna rektangeln samtidigt som bildens proportioner bevaras. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-com.aspose.pdf.Rectangle-) | Lägger till en sökbar bild på sidan och placerar den i mitten av den angivna rektangeln samtidigt som bildens proportioner bevaras. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-) | Lägger till en bild på sidan och placerar den i mitten av den angivna rektangeln samtidigt som bildens proportioner bevaras. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-) | Lägger till en bild på sidan och placerar den i mitten av den angivna rektangeln samtidigt som bildens proportioner bevaras. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-boolean-) | Lägger till en bild på sidan och placerar den i mitten av den angivna rektangeln samtidigt som bildens proportioner bevaras. |
| [addImage](#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-) | Lägger till en sökbar bild på sidan och placerar den i mitten av den angivna rektangeln samtidigt som bildens proportioner bevaras. |
| [addImage](#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-) | Lägger till en sökbar bild på sidan och placerar den i mitten av den angivna rektangeln samtidigt som bildens proportioner bevaras. |
| [addImage](#addImage-java.lang.String-com.aspose.pdf.Rectangle-) | Lägger till en bild på sidan och placerar den i mitten av den angivna rektangeln samtidigt som bildens proportioner bevaras. |
| [addStamp](#addStamp-com.aspose.pdf.Stamp-) | Sätt in en stämpel på sidan. Stämpeln kan vara sidnummer, bild eller enkel text, t.ex. en logotyp. |
| [asByteArray](#asByteArray-com.aspose.pdf.devices.Resolution-) | Konverterar aktuell sida till BMP-bitmap och returnerar sedan en bytearray. |
| [asXml](#asXml--) | Konverterar aktuell sida till XML i UTF-8-kodning. |
| [calculateContentBBox](#calculateContentBBox--) | Beräknar bbox-värdet – rektangel som innehåller innehållet utan synliga marginaler. |
| [clearContents](#clearContents--) | Endast för internt bruk |
| [close](#close--) | Stänger alla resurser som används av detta dokument. |
| [convertToPNGMemoryStream](#convertToPNGMemoryStream--) | Konvertera sida till PNG för DSR-, OMR- och OCR-bildström. |
| [deleteGraphics](#deleteGraphics-com.aspose.pdf.vector.GraphicElementCollection-) | Tar bort grafik från sidan. Fungerar snabbare än att ta bort element ett i taget med {@link GraphicElement#remove}-metoden. |
| [deleteUnusedResources](#deleteUnusedResources-com.aspose.ms.System.Collections.Generic.Dictionary-) |  |
| [dispose](#dispose--) | Frigör minne. Denna metod är föråldrad, använd close() istället. |
| [fillUsedObjectsTable](#fillUsedObjectsTable-com.aspose.ms.System.Collections.Generic.Dictionary-com.aspose.pdf.engine.data.IPdfDictionary-) |  |
| [findReferences](#findReferences-com.aspose.pdf.OperatorCollection-java.lang.String-) | Returnerar en lista med operatorer som använder resursen med angivet namn. |
| [findReferences](#findReferences-java.lang.String-) | <p> Hitta referenser </p> |
| [flatten](#flatten--) | Tar bort alla statiska fält som finns på sidan och placerar deras värden istället. |
| [freeMemory](#freeMemory--) | Rensar cachad data |
| [getActions](#getActions--) | Hämtar samling av sidegenskaper. |
| [getAnnotations](#getAnnotations--) | Hämtar samling av sidannoteringar. {@code Annotations} |
| [getArtBox](#getArtBox--) | <p> Hämtar art box för sidan. </p> |
| [getArtifacts](#getArtifacts--) | Hämtar samling av artefakter på sidan. |
| [getBackground](#getBackground--) | Hämtar bakgrundsfärgen för sidan. |
| [getBackgroundImage](#getBackgroundImage--) | Hämtar eller anger bakgrundsbild för sidan (endast för generator, fylls inte i vid läsning av dokument). |
| [getBleedBox](#getBleedBox--) | <p> Hämtar bleed box för sidan. </p> |
| [getColorType](#getColorType--) | Hämtar färgtyp för sidorna baserat på information som erhålls från operatorerna SetColor, bilder och formulär. |
| [getContents](#getContents--) | <p> Hämtar samling av operatorer i sidans innehållsström. {@code OperatorCollection} </p> |
| [getContentsAppender](#getContentsAppender--) | Hämtar aktuell innehållsappender. {@code ContentsAppender} |
| [getCropBox](#getCropBox--) | <p> Hämtar beskärningsboxen för sidan. </p> |
| [getDocument](#getDocument--) | Hämta dokument |
| [getDuration](#getDuration--) | <p> Hämtar sidans visningstid. Detta är tiden i sekunder som sidan ska visas under presentationen. Returnerar -1 om varaktigheten inte är definierad. </p> <hr> Exempel visar hur man hämtar sidans varaktighet <p> Document document = new Document(\"sample.pdf\"); Page page = document.getPages().get(1); int pageRect = page.getDuration(); </p> |
| [getEnginePage](#getEnginePage--) | Endast för intern användning |
| [getFieldsInTabOrder](#getFieldsInTabOrder--) | Hämtar lista över Field-objekt i Tab-ordning på denna sida. |
| [getFooter](#getFooter--) | Hämtar sidfot. |
| [getGroup](#getGroup--) | Hämtar en gruppattributklass som specificerar attributen för sidans sidgrupp för användning i den transparenta bildmodellen. |
| [getHeader](#getHeader--) | Hämtar sidhuvud. |
| [getLayers](#getLayers--) | Hämtar lagerkollektion. |
| [getMediaBox](#getMediaBox--) | <p> Hämtar mediabox för sidan. </p> |
| [getNoteLineStyle](#getNoteLineStyle--) | Hämtar linjestilen för anteckningar. (endast för generator, fylls inte i vid läsning av dokumentet) |
| [getNotifications](#getNotifications--) | Returnerar aviseringar om interna operationer med sidinnehåll. (Endast aviseringar om styckehändelser i scenarier för texttillägg stöds för närvarande.) |
| [getNumber](#getNumber--) | Hämta sidnummer. |
| [getOnBeforePageGenerate](#getOnBeforePageGenerate--) | Händelse för att anpassa sidhuvud och sidfot. |
| [getPageInfo](#getPageInfo--) | Hämtar sidinformationen. (endast för generator, fylls inte i vid läsning av dokumentet). |
| [getPageRect](#getPageRect-boolean-) | Returnerar rektangeln för sidan enligt dess CropBox (eller MediaBox om CropBox är null). |
| [getParagraphs](#getParagraphs--) | Hämtar styckena. |
| [getRect_Rename_Namesake](#getRect_Rename_Namesake--) | <p> Returnerar rektangeln för sidan enligt dess CropBox och MediaBox; </p> Intern |
| [getRect](#getRect--) | <p> Returnerar rektangeln för sidan enligt dess CropBox och MediaBox; Vid hämtning: sidans crop box returneras om den är specificerad, annars returneras sidans media box. Vid inställning: sidans media box sätts alltid. </p> |
| [getResources](#getResources--) | Hämtar resurserna som är associerade med sidan. |
| [getResourcesField](#getResourcesField--) | <p> Hämtar sidresurser. Resources-objektet innehåller samlingar av bilder, formulär och teckensnitt. {@code Resources} </p> |
| [getRotate](#getRotate--) | <p> Hämtar rotationen för sidan. </p> |
| [getRotationMatrix](#getRotationMatrix--) | Hämtar transformationsmatrisen för sidan. |
| [getTabOrder](#getTabOrder--) | Hämtar flikordningen för sidan. Möjliga värden: Rad, Kolumn. Standard, Manuell |
| [getTocInfo](#getTocInfo--) | Hämtar information om innehållsförteckning. |
| [getTrimBox](#getTrimBox--) | <p> Hämtar trimboxen för sidan. </p> |
| [getUserUnit](#getUserUnit--) | Hämtar eller anger UserUnit‑värdet. Ett positivt tal som anger storleken på standardenheterna i användarutrymmet, i multiplar av 1 / 72 tum. Standardvärdet är 1. Ange noll eller ett negativt värde för att rensa detta fält på sidan. |
| [getWatermark](#getWatermark--) | Hämtar vattenstämpeln för sidan. |
| [hasVectorGraphics](#hasVectorGraphics--) | Detekterar förekomsten av vektorgrafik, om den finns på sidan. |
| [intToRotation](#intToRotation-int-) | Översätter heltalsvärdet till motsvarande rotationsenumerationsmedlem. |
| [isAddParagraphsAfterLast](#isAddParagraphsAfterLast--) | Hämtar eller anger tillägget av stycken efter det sista stycket på sidan. Värde: Värdet indikerar om stycken ska läggas till efter det sista stycket på sidan. Stycken kommer att läggas till efter det sista stycket på sidan om värdet är sant. |
| [isBlank](#isBlank-double-) | Hämtar flaggan som anger om sidan är tom eller inte. |
| [isBlank](#isBlank-double-boolean-) | Hämtar flaggan som anger om sidan är tom eller inte. |
| [makeGrayscale](#makeGrayscale--) | Konverterar sidan till gråskala. |
| [mergeLayers](#mergeLayers-java.lang.String-) | Slår samman alla lager på sidan till ett enda lager med det angivna nya lagernamnet. |
| [mergeLayers](#mergeLayers-java.lang.String-java.lang.String-) | Slår samman alla lager på sidan till ett enda lager med det angivna nya lagernamnet och valfritt innehållsgrupps‑ID. |
| [removeObjectReferences](#removeObjectReferences-com.aspose.pdf.OperatorCollection-java.lang.String-) | Ta bort objektreferenser |
| [removeObjectReferences](#removeObjectReferences-java.lang.String-) | Ta bort referenser till XObject från sidinnehållet (dvs. alla Do‑operatorer som använder objektets namn). |
| [resize](#resize-com.aspose.pdf.PageSize-) | Ändrar storlek på sidan. |
| [rotationToInt](#rotationToInt-com.aspose.pdf.Rotation-) | Översätter rotationsenumerationsmedlem till heltalsvärde. |
| [sendTo](#sendTo-com.aspose.pdf.devices.PageDevice-java.io.OutputStream-) | Skickar sidan till bearbetning med given sid‑enhet. |
| [sendTo](#sendTo-com.aspose.pdf.devices.PageDevice-java.lang.String-) | Skickar sidan till bearbetning med given sid‑enhet. |
| [setAddParagraphsAfterLast](#setAddParagraphsAfterLast-boolean-) | Hämtar eller anger tillägget av stycken efter det sista stycket på sidan. Värde: Värdet indikerar om stycken ska läggas till efter det sista stycket på sidan. Stycken kommer att läggas till efter det sista stycket på sidan om värdet är sant. |
| [setArtBox](#setArtBox-com.aspose.pdf.Rectangle-) | Anger art‑boxen för sidan. |
| [setBackground](#setBackground-java.awt.Color-) | Anger bakgrundsfärgen för sidan. |
| [setBackground](#setBackground-com.aspose.pdf.Color-) | Anger bakgrundsfärgen för sidan. |
| [setBackgroundImage](#setBackgroundImage-com.aspose.pdf.Image-) | Hämtar eller anger bakgrundsbild för sidan (endast för generator, fylls inte i vid läsning av dokument). |
| [setBleedBox](#setBleedBox-com.aspose.pdf.Rectangle-) | Anger bleed‑boxen för sidan. |
| [setCropBox](#setCropBox-com.aspose.pdf.Rectangle-) | <p> Anger beskärningsrutan för sidan. </p> <hr> <pre> Exempel visar hur man hämtar beskärningsrutan för sidan: Document document = new Document("sample.pdf"); document.getPages().get_Item(1).setCropBox(new Rectangle(0d,0d,100d,100d)); </pre> |
| [setDuration](#setDuration-double-) | Anger sidans visningstid. Detta är tiden i sekunder som sidan ska visas under en presentation. Returnerar -1 om varaktigheten inte är definierad. |
| [setEnginePage](#setEnginePage-com.aspose.pdf.engine.commondata.IPage-) | Endast för intern användning |
| [setFooter](#setFooter-com.aspose.pdf.HeaderFooter-) | Anger sidfot. |
| [setGroup](#setGroup-com.aspose.pdf.Group-) | Anger en gruppattributklass som specificerar attributen för sidans sidgrupp för användning i den transparenta bildmodellen. |
| [setHeader](#setHeader-com.aspose.pdf.HeaderFooter-) | Ställer in sidhuvud. |
| [setLayers](#setLayers-java.util.ArrayList-) | Ställer in lagerkollektionen. |
| [setLayersInternal](#setLayersInternal-com.aspose.ms.System.Collections.Generic.List-) | Ställer in lagerkollektionen. |
| [setMediaBox](#setMediaBox-com.aspose.pdf.Rectangle-) | Ställer in mediaboxen för sidan. |
| [setNoteLineStyle](#setNoteLineStyle-com.aspose.pdf.GraphInfo-) | Ställer in linjestilen för anteckningar.(endast för generator, inte fyllt i när dokumentet läses) |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Ställer in sidinformationen.(endast för generator, inte fyllt i när dokumentet läses). |
| [setPageSize](#setPageSize-double-double-) | Ställer in sidstorlek för sidan. |
| [setParagraphs](#setParagraphs-com.aspose.pdf.Paragraphs-) | Ställer in styckena. |
| [setRect](#setRect-com.aspose.pdf.Rectangle-) | Hämtar eller anger rektangeln för sidan. Vid hämtning: returneras sidans beskärningsruta om den är specificerad, annars returneras sidans mediabox. Vid inställning: sidans mediabox sätts alltid. returneras. Observera att denna egenskap inte beaktar sidrotation. För att hämta sidrektangeln med hänsyn till rotation, använd ActualRect. |
| [setRotate](#setRotate-com.aspose.pdf.Rotation-) | Ställer in rotationen för sidan. |
| [setTabOrder](#setTabOrder-int-) | Ställer in flikordningen för sidan. Möjliga värden: Row, Column. Standard, Manual |
| [setTocInfo](#setTocInfo-com.aspose.pdf.TocInfo-) | Ställer in innehållsförteckningens information. |
| [setTransition](#setTransition-com.aspose.pdf.engine.data.IPdfDictionary-) | Ställ in övergång |
| [setTrimBox](#setTrimBox-com.aspose.pdf.Rectangle-) | Ställer in trimboxen för sidan. |
| [setUserUnit](#setUserUnit-double-) | Hämtar eller anger UserUnit‑värdet. Ett positivt tal som anger storleken på standardenheterna i användarutrymmet, i multiplar av 1 / 72 tum. Standardvärdet är 1. Ange noll eller ett negativt värde för att rensa detta fält på sidan. |
| [setWatermark](#setWatermark-com.aspose.pdf.Watermark-) | Ställer in vattenstämpeln för sidan. |
| [trySaveVectorGraphics](#trySaveVectorGraphics-java.lang.String-) | Försöker spara vektorgrafik om den finns på sidan. Sparaformatet är SVG. |

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Accepterar {@code AnnotationSelector} besökarobjekt som tillhandahåller funktionalitet för att arbeta med annotationer.

### accept {#accept-com.aspose.pdf.ImagePlacementAbsorber-}
Accepterar {@code ImagePlacementAbsorber} besökarobjekt som tillhandahåller funktionalitet för att arbeta med bildplaceringsobjekt.

### accept {#accept-com.aspose.pdf.TextAbsorber-}
Accepterar {@code TextAbsorber} besökarobjekt som tillhandahåller funktionalitet för att arbeta med textobjekt.

### accept {#accept-com.aspose.pdf.TextFragmentAbsorber-}
Accepterar {@code TextFragmentAbsorber} besökarobjekt som tillhandahåller funktionalitet för att arbeta med textobjekt.

### addGraphics {#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-}
Lägger till grafik på sidan. Fungerar snabbare än att lägga till element ett i taget med GraphicElement#addOnPage(Page)-metoden.

### addGraphics {#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-com.aspose.pdf.Rectangle-}
Lägger till grafik på sidan. Fungerar snabbare än att lägga till element ett i taget med GraphicElement#addOnPage(Page)-metoden.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-}
Lägger till en bild på sidan och placerar den i mitten av den angivna rektangeln samtidigt som bildens proportioner bevaras.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-}
Lägger till en sökbar bild på sidan och placerar den i mitten av den angivna rektangeln samtidigt som bildens proportioner bevaras.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-com.aspose.pdf.Rectangle-}
Lägger till en sökbar bild på sidan och placerar den i mitten av den angivna rektangeln samtidigt som bildens proportioner bevaras.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-}
Lägger till en bild på sidan och placerar den i mitten av den angivna rektangeln samtidigt som bildens proportioner bevaras.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-}
Lägger till en bild på sidan och placerar den i mitten av den angivna rektangeln samtidigt som bildens proportioner bevaras.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-boolean-}
Lägger till en bild på sidan och placerar den i mitten av den angivna rektangeln samtidigt som bildens proportioner bevaras.

### addImage {#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-}
Lägger till en sökbar bild på sidan och placerar den i mitten av den angivna rektangeln samtidigt som bildens proportioner bevaras.

### addImage {#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-}
Lägger till en sökbar bild på sidan och placerar den i mitten av den angivna rektangeln samtidigt som bildens proportioner bevaras.

### addImage {#addImage-java.lang.String-com.aspose.pdf.Rectangle-}
Lägger till en bild på sidan och placerar den i mitten av den angivna rektangeln samtidigt som bildens proportioner bevaras.

### addStamp {#addStamp-com.aspose.pdf.Stamp-}
Sätt in en stämpel på sidan. Stämpeln kan vara sidnummer, bild eller enkel text, t.ex. en logotyp.

### asByteArray {#asByteArray-com.aspose.pdf.devices.Resolution-}
Konverterar aktuell sida till BMP-bitmap och returnerar sedan en bytearray.

### asXml {#asXml--}
```
public String asXml()
```

Konverterar aktuell sida till XML i UTF-8-kodning.

**Returns:**
Konverterad xml-sträng.

### calculateContentBBox {#calculateContentBBox--}
```
public Rectangle calculateContentBBox()
```

Beräknar bbox-värdet – rektangel som innehåller innehållet utan synliga marginaler.

**Returns:**
Bbox-värde - rektangel som innehåller innehållet utan synliga marginaler

### clearContents {#clearContents--}
```
public void clearContents()
```

Endast för internt bruk

### close {#close--}
```
public void close()
```

Stänger alla resurser som används av detta dokument.

### convertToPNGMemoryStream {#convertToPNGMemoryStream--}
```
public byte[] convertToPNGMemoryStream()
```

Konvertera sida till PNG för DSR-, OMR- och OCR-bildström.

**Returns:**
Bildström i byte[]-array.

### deleteGraphics {#deleteGraphics-com.aspose.pdf.vector.GraphicElementCollection-}
Tar bort grafik från sidan. Fungerar snabbare än att ta bort element ett i taget med {@link GraphicElement#remove}-metoden.

### deleteUnusedResources {#deleteUnusedResources-com.aspose.ms.System.Collections.Generic.Dictionary-}


### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Frigör minne. Denna metod är föråldrad, använd close() istället.

### fillUsedObjectsTable {#fillUsedObjectsTable-com.aspose.ms.System.Collections.Generic.Dictionary-com.aspose.pdf.engine.data.IPdfDictionary-}


### findReferences {#findReferences-com.aspose.pdf.OperatorCollection-java.lang.String-}
Returnerar en lista med operatorer som använder resursen med angivet namn.

### findReferences {#findReferences-java.lang.String-}
<p> Hitta referenser </p>

### flatten {#flatten--}
```
public void flatten()
```

Tar bort alla statiska fält som finns på sidan och placerar deras värden istället.

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

Rensar cachad data

### getActions {#getActions--}
```
public PageActionCollection getActions()
```

Hämtar samling av sidegenskaper.

**Returns:**
PageActionCollection-värde

### getAnnotations {#getAnnotations--}
```
public AnnotationCollection getAnnotations()
```

Hämtar samling av sidannoteringar. {@code Annotations}

**Returns:**
AnnotationCollection-värde

### getArtBox {#getArtBox--}
```
public Rectangle getArtBox()
```

<p> Hämtar art box för sidan. </p>

**Returns:**
Rektangelvärde <hr> <pre> Exempel visar hur man får art box för sidan: Document document = new Document("sample.pdf"); Rectangle artBox = document.getPages().get(1).getArtBox(); </pre>

### getArtifacts {#getArtifacts--}
```
public ArtifactCollection getArtifacts()
```

Hämtar samling av artefakter på sidan.

**Returns:**
ArtifactCollection-värde

### getBackground {#getBackground--}
```
public Color getBackground()
```

Hämtar bakgrundsfärgen för sidan.

**Returns:**
Färgvärde

### getBackgroundImage {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```

Hämtar eller anger bakgrundsbild för sidan (endast för generator, fylls inte i vid läsning av dokument).

**Returns:**
Bildinstans

### getBleedBox {#getBleedBox--}
```
public Rectangle getBleedBox()
```

<p> Hämtar bleed box för sidan. </p>

**Returns:**
Rektangelvärde <hr> <pre> Exempel visar hur man får bleed box för sidan: Document document = new Document("sample.pdf"); Rectangle bleedBox = document.getPages().get(1).getBleedBox(); </pre>

### getColorType {#getColorType--}
```
public ColorType getColorType()
```

Hämtar färgtyp för sidorna baserat på information som erhålls från operatorerna SetColor, bilder och formulär.

**Returns:**
ColorType-element @see ColorType

### getContents {#getContents--}
```
public OperatorCollection getContents()
```

<p> Hämtar samling av operatorer i sidans innehållsström. {@code OperatorCollection} </p>

**Returns:**
OperatorCollection-objekt <hr> <pre> Exempel visar hur man skannar operatorströmmen för sidan. Document document = new Document("sample.pdf"); Operators contents = document.getPages().get_Item(1).getContents(); for(Operator op : {@code (Iterable<Operator>)}contents) { System.out.println(op); } </pre>

### getContentsAppender {#getContentsAppender--}
```
public ContentsAppender getContentsAppender()
```

Hämtar aktuell innehållsappender. {@code ContentsAppender}

**Returns:**
ContentsAppender värde

### getCropBox {#getCropBox--}
```
public Rectangle getCropBox()
```

<p> Hämtar beskärningsboxen för sidan. </p>

**Returns:**
Rektangelvärde <hr> <pre> Exempel visar hur man får beskärningsrutan för sidan: Document document = new Document("sample.pdf"); Rectangle cropBox = document.getPages().get_Item(1).getCropBox(); </pre>

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

Hämta dokument

**Returns:**
IDocument-objekt

### getDuration {#getDuration--}
```
public double getDuration()
```

<p> Hämtar sidans visningstid. Detta är tiden i sekunder som sidan ska visas under presentationen. Returnerar -1 om varaktigheten inte är definierad. </p> <hr> Exempel visar hur man hämtar sidans varaktighet <p> Document document = new Document(\"sample.pdf\"); Page page = document.getPages().get(1); int pageRect = page.getDuration(); </p>

**Returns:**
double-värde

### getEnginePage {#getEnginePage--}
```
public com.aspose.pdf.engine.commondata.IPage getEnginePage()
```

Endast för intern användning

**Returns:**
intern instans

### getFieldsInTabOrder {#getFieldsInTabOrder--}
```
public List < Field > getFieldsInTabOrder()
```

Hämtar lista över Field-objekt i Tab-ordning på denna sida.

**Returns:**
Lista över fältobjekt

### getFooter {#getFooter--}
```
public HeaderFooter getFooter()
```

Hämtar sidfot.

**Returns:**
Sidans sidfot.

### getGroup {#getGroup--}
```
public Group getGroup()
```

Hämtar en gruppattributklass som specificerar attributen för sidans sidgrupp för användning i den transparenta bildmodellen.

**Returns:**
Gruppvärde

### getHeader {#getHeader--}
```
public HeaderFooter getHeader()
```

Hämtar sidhuvud.

**Returns:**
Sidans sidhuvud.

### getLayers {#getLayers--}
```
public List < Layer > getLayers()
```

Hämtar lagerkollektion.

**Returns:**
Värde: lagrens samling.

### getMediaBox {#getMediaBox--}
```
public Rectangle getMediaBox()
```

<p> Hämtar mediabox för sidan. </p>

**Returns:**
Rektangelvärde <hr> <pre> Exempel visar hur man får mediaboxen för sidan: Document document = new Document("sample.pdf"); Rectangle mediaBox = document.getPages().get(1).getMediaBox(); </pre>

### getNoteLineStyle {#getNoteLineStyle--}
```
public GraphInfo getNoteLineStyle()
```

Hämtar linjestilen för anteckningar. (endast för generator, fylls inte i vid läsning av dokumentet)

**Returns:**
GraphInfo värde

### getNotifications {#getNotifications--}
```
public String getNotifications()
```

Returnerar aviseringar om interna operationer med sidinnehåll. (Endast aviseringar om styckehändelser i scenarier för texttillägg stöds för närvarande.)

**Returns:**
Sträng som representerar aviseringar om interna operationer med sidinnehåll.

### getNumber {#getNumber--}
```
public final int getNumber()
```

Hämta sidnummer.

**Returns:**
int‑värde

### getOnBeforePageGenerate {#getOnBeforePageGenerate--}
```
public PdfEvent < Page.BeforePageGenerate > getOnBeforePageGenerate()
```

Händelse för att anpassa sidhuvud och sidfot.

**Returns:**
{@code PdfEvent<BeforePageGenerate> instans}

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

Hämtar sidinformationen. (endast för generator, fylls inte i vid läsning av dokumentet).

**Returns:**
Sidans information.

### getPageRect {#getPageRect-boolean-}
```
public Rectangle getPageRect(boolean considerRotation)
```

Returnerar rektangeln för sidan enligt dess CropBox (eller MediaBox om CropBox är null).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| considerRotation |  | Om true så kommer sidrotation att beaktas i rektberäkning. |

**Returns:**
Rektangel för sidan.

### getParagraphs {#getParagraphs--}
```
public Paragraphs getParagraphs()
```

Hämtar styckena.

**Returns:**
Paragraferna.

### getRect_Rename_Namesake {#getRect_Rename_Namesake--}
```
public Rectangle getRect_Rename_Namesake()
```

<p> Returnerar rektangeln för sidan enligt dess CropBox och MediaBox; </p> Intern

**Returns:**
Rektangelvärde <hr> <pre> Exempel visar hur man får sidans rektangel: Document document = new Document("sample.pdf"); Page page = document.getPages().get(1); Rectangle pageRect = page.getRect(); </pre>

### getRect {#getRect--}
```
public Rectangle getRect()
```

<p> Returnerar rektangeln för sidan enligt dess CropBox och MediaBox; Vid hämtning: sidans crop box returneras om den är specificerad, annars returneras sidans media box. Vid inställning: sidans media box sätts alltid. </p>

**Returns:**
Rektangelvärde <hr> <pre> Exempel visar hur man får sidans rektangel: Document document = new Document("sample.pdf"); Page page = document.getPages().get(1); Rectangle pageRect = page.getRect(); </pre>

### getResources {#getResources--}
```
public final Resources getResources()
```

Hämtar resurserna som är associerade med sidan.

**Returns:**
Ett {@code Resources}({@link #getResources()})-objekt som representerar sidans resurser.

### getResourcesField {#getResourcesField--}
```
public Resources getResourcesField()
```

<p> Hämtar sidresurser. Resources-objektet innehåller samlingar av bilder, formulär och teckensnitt. {@code Resources} </p>

**Returns:**
Resurservärde <hr> <pre> Exempel visar hur man skannar igenom sidbilder: Document document = new Document("sample.pdf"); DocumentActions actions = document.getActions(); Resources resources = document.getPages().get(1).getResources(); for(XImage image : {@code (Iterable<XImage>)resources}.getImages()) { System.out.println(image.getWidth() + ":" + image.getHeight()); } </pre>

### getRotate {#getRotate--}
```
public Rotation getRotate()
```

<p> Hämtar rotationen för sidan. </p>

**Returns:**
Rotationselement <hr> <pre> Exempel visar hur man bestämmer sidrotation. Document document = new Document("sample.pdf"); System.out.println(document.getPages().get(1).getRotate()); </pre> @see Rotation

### getRotationMatrix {#getRotationMatrix--}
```
public Matrix getRotationMatrix()
```

Hämtar transformationsmatrisen för sidan.

**Returns:**
Matrixvärde

### getTabOrder {#getTabOrder--}
```
public int getTabOrder()
```

Hämtar flikordningen för sidan. Möjliga värden: Rad, Kolumn. Standard, Manuell

**Returns:**
TabOrder-värde @see TabOrder

### getTocInfo {#getTocInfo--}
```
public TocInfo getTocInfo()
```

Hämtar information om innehållsförteckning.

**Returns:**
Innehållsförteckningsinformationen - standard null. Om den är satt kommer denna sida att innehålla en innehållsförteckning.

### getTrimBox {#getTrimBox--}
```
public Rectangle getTrimBox()
```

<p> Hämtar trimboxen för sidan. </p>

**Returns:**
Rektangelvärde <hr> <pre> Exempel visar hur man får trimrutan för sidan: Document document = new Document("sample.pdf"); Rectangle trimBox = document.getPages().get(1).getTrimBox(); </pre>

### getUserUnit {#getUserUnit--}
```
public final double getUserUnit()
```

Hämtar eller anger UserUnit‑värdet. Ett positivt tal som anger storleken på standardenheterna i användarutrymmet, i multiplar av 1 / 72 tum. Standardvärdet är 1. Ange noll eller ett negativt värde för att rensa detta fält på sidan.

**Returns:**
double-värde

### getWatermark {#getWatermark--}
```
public Watermark getWatermark()
```

Hämtar vattenstämpeln för sidan.

**Returns:**
Vattenstämpelvärde

### hasVectorGraphics {#hasVectorGraphics--}
```
public final boolean hasVectorGraphics()
```

Detekterar förekomsten av vektorgrafik, om den finns på sidan.

**Returns:**
True om sidan innehåller sökvägskonstruktionsoperatorer; annars False.

### intToRotation {#intToRotation-int-}
```
public static Rotation intToRotation(int rotation)
```

Översätter heltalsvärdet till motsvarande rotationsenumerationsmedlem.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rotation |  | Heltalsvärde att konvertera |

**Returns:**
Rotationsuppräkningselement @see Rotation

### isAddParagraphsAfterLast {#isAddParagraphsAfterLast--}
```
public final boolean isAddParagraphsAfterLast()
```

Hämtar eller anger tillägget av stycken efter det sista stycket på sidan. Värde: Värdet indikerar om stycken ska läggas till efter det sista stycket på sidan. Stycken kommer att läggas till efter det sista stycket på sidan om värdet är sant.

**Returns:**
booleskt värde

### isBlank {#isBlank-double-}
```
public boolean isBlank(double fillThresholdFactor)
```

Hämtar flaggan som anger om sidan är tom eller inte.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fillThresholdFactor |  | Fyllnadströskelvärdet som styr känsligheten för detektering. Bör vara i intervallet [0..1). För att avgöra om en sida är tom eller inte beräknas förhållandet mellan det fyllda utrymmet och sidans totala utrymme. Detta förhållande jämförs med parametern fillThresholdFactor och om det är mindre anses sidan vara tom. |

**Returns:**
booleskt värde True - om sidan är tom; annars false.

### isBlank {#isBlank-double-boolean-}
```
public boolean isBlank(double fillThresholdFactor, boolean parseWhiteContent)
```

Hämtar flaggan som anger om sidan är tom eller inte.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fillThresholdFactor |  | Fyllnadströskelvärdet som styr känsligheten för detektering. Ska vara lika med eller större än 0,01. |
| parseWhiteContent |  | True för fullständig sidavskanning med analys av vitt innehåll, False (standard) - snabb algoritm där vita grafik räknas som icke-tom sida. |

**Returns:**
booleskt värde True - om sidan är tom; annars false.

### makeGrayscale {#makeGrayscale--}
```
public final void makeGrayscale()
```

Konverterar sidan till gråskala.

### mergeLayers {#mergeLayers-java.lang.String-}
Slår samman alla lager på sidan till ett enda lager med det angivna nya lagernamnet.

### mergeLayers {#mergeLayers-java.lang.String-java.lang.String-}
Slår samman alla lager på sidan till ett enda lager med det angivna nya lagernamnet och valfritt innehållsgrupps‑ID.

### removeObjectReferences {#removeObjectReferences-com.aspose.pdf.OperatorCollection-java.lang.String-}
Ta bort objektreferenser

### removeObjectReferences {#removeObjectReferences-java.lang.String-}
Ta bort referenser till XObject från sidinnehållet (dvs. alla Do‑operatorer som använder objektets namn).

### resize {#resize-com.aspose.pdf.PageSize-}
Ändrar storlek på sidan.

### rotationToInt {#rotationToInt-com.aspose.pdf.Rotation-}
Översätter rotationsenumerationsmedlem till heltalsvärde.

### sendTo {#sendTo-com.aspose.pdf.devices.PageDevice-java.io.OutputStream-}
Skickar sidan till bearbetning med given sid‑enhet.

### sendTo {#sendTo-com.aspose.pdf.devices.PageDevice-java.lang.String-}
Skickar sidan till bearbetning med given sid‑enhet.

### setAddParagraphsAfterLast {#setAddParagraphsAfterLast-boolean-}
```
public final void setAddParagraphsAfterLast(boolean value)
```

Hämtar eller anger tillägget av stycken efter det sista stycket på sidan. Värde: Värdet indikerar om stycken ska läggas till efter det sista stycket på sidan. Stycken kommer att läggas till efter det sista stycket på sidan om värdet är sant.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setArtBox {#setArtBox-com.aspose.pdf.Rectangle-}
Anger art‑boxen för sidan.

### setBackground {#setBackground-java.awt.Color-}
Anger bakgrundsfärgen för sidan.

### setBackground {#setBackground-com.aspose.pdf.Color-}
Anger bakgrundsfärgen för sidan.

### setBackgroundImage {#setBackgroundImage-com.aspose.pdf.Image-}
Hämtar eller anger bakgrundsbild för sidan (endast för generator, fylls inte i vid läsning av dokument).

### setBleedBox {#setBleedBox-com.aspose.pdf.Rectangle-}
Anger bleed‑boxen för sidan.

### setCropBox {#setCropBox-com.aspose.pdf.Rectangle-}
<p> Anger beskärningsrutan för sidan. </p> <hr> <pre> Exempel visar hur man hämtar beskärningsrutan för sidan: Document document = new Document("sample.pdf"); document.getPages().get_Item(1).setCropBox(new Rectangle(0d,0d,100d,100d)); </pre>

### setDuration {#setDuration-double-}
```
public void setDuration(double value)
```

Anger sidans visningstid. Detta är tiden i sekunder som sidan ska visas under en presentation. Returnerar -1 om varaktigheten inte är definierad.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | sidvisningens varaktighet. |

### setEnginePage {#setEnginePage-com.aspose.pdf.engine.commondata.IPage-}
Endast för intern användning

### setFooter {#setFooter-com.aspose.pdf.HeaderFooter-}
Anger sidfot.

### setGroup {#setGroup-com.aspose.pdf.Group-}
Anger en gruppattributklass som specificerar attributen för sidans sidgrupp för användning i den transparenta bildmodellen.

### setHeader {#setHeader-com.aspose.pdf.HeaderFooter-}
Ställer in sidhuvud.

### setLayers {#setLayers-java.util.ArrayList-}
Ställer in lagerkollektionen.

### setLayersInternal {#setLayersInternal-com.aspose.ms.System.Collections.Generic.List-}
Ställer in lagerkollektionen.

### setMediaBox {#setMediaBox-com.aspose.pdf.Rectangle-}
Ställer in mediaboxen för sidan.

### setNoteLineStyle {#setNoteLineStyle-com.aspose.pdf.GraphInfo-}
Ställer in linjestilen för anteckningar.(endast för generator, inte fyllt i när dokumentet läses)

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
Ställer in sidinformationen.(endast för generator, inte fyllt i när dokumentet läses).

### setPageSize {#setPageSize-double-double-}
```
public void setPageSize(double width, double height)
```

Ställer in sidstorlek för sidan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd |  | Sidbredd. |
| höjd |  | Sidstorlek. |

### setParagraphs {#setParagraphs-com.aspose.pdf.Paragraphs-}
Ställer in styckena.

### setRect {#setRect-com.aspose.pdf.Rectangle-}
Hämtar eller anger rektangeln för sidan. Vid hämtning: returneras sidans beskärningsruta om den är specificerad, annars returneras sidans mediabox. Vid inställning: sidans mediabox sätts alltid. returneras. Observera att denna egenskap inte beaktar sidrotation. För att hämta sidrektangeln med hänsyn till rotation, använd ActualRect.

### setRotate {#setRotate-com.aspose.pdf.Rotation-}
Ställer in rotationen för sidan.

### setTabOrder {#setTabOrder-int-}
```
public void setTabOrder(int value)
```

Ställer in flikordningen för sidan. Möjliga värden: Row, Column. Standard, Manual

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | TabOrder-objekt @see TabOrder |

### setTocInfo {#setTocInfo-com.aspose.pdf.TocInfo-}
Ställer in innehållsförteckningens information.

### setTransition {#setTransition-com.aspose.pdf.engine.data.IPdfDictionary-}
Ställ in övergång

### setTrimBox {#setTrimBox-com.aspose.pdf.Rectangle-}
Ställer in trimboxen för sidan.

### setUserUnit {#setUserUnit-double-}
```
public final void setUserUnit(double value)
```

Hämtar eller anger UserUnit‑värdet. Ett positivt tal som anger storleken på standardenheterna i användarutrymmet, i multiplar av 1 / 72 tum. Standardvärdet är 1. Ange noll eller ett negativt värde för att rensa detta fält på sidan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setWatermark {#setWatermark-com.aspose.pdf.Watermark-}
Ställer in vattenstämpeln för sidan.

### trySaveVectorGraphics {#trySaveVectorGraphics-java.lang.String-}
Försöker spara vektorgrafik om den finns på sidan. Sparaformatet är SVG.
