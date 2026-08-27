---
title: "PdfPageEditor"
linktitle: "PdfPageEditor"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar en klass för att redigera PDF-filens sida, inklusive rotera sidan, zooma sidan, flytta position och ändra sidstorlek."
type: docs
weight: 570
url: /sv/java/com.aspose.pdf.facades/pdfpageeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfPageEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfPageEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfPageEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfPageEditor extends SaveableFacade
```

Representerar en klass för att redigera PDF-filens sida, inklusive rotera sidan, zooma sidan, flytta position och ändra sidstorlek.

## Fält

| Fält | Beskrivning |
| --- | --- |
| [BLINDH](#BLINDH) | Vertikala persienner |
| [BLINDV](#BLINDV) | Vertikala persienner |
| [BTWIPE](#BTWIPE) | Botten-topp svep |
| [DGLITTER](#DGLITTER) | Diagonal glitter |
| [DISSOLVE](#DISSOLVE) | Den gamla sidan upplöses |
| [INBOX](#INBOX) | Inåtriktad ruta |
| [LRGLITTER](#LRGLITTER) | Vänster-höger glitter |
| [LRWIPE](#LRWIPE) | Vänster-höger svep |
| [OUTBOX](#OUTBOX) | Utvändig ruta |
| [RLWIPE](#RLWIPE) | Höger-vänster svep |
| [SPLITHIN](#SPLITHIN) | IN horisontell delning |
| [SPLITHOUT](#SPLITHOUT) | Ut horisontell delning |
| [SPLITVIN](#SPLITVIN) | In vertikal delning |
| [SPLITVOUT](#SPLITVOUT) | Ut vertikal delning |
| [TBGLITTER](#TBGLITTER) | Topp-botten glitter |
| [TBWIPE](#TBWIPE) | Topp-botten svep |

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PdfPageEditor](#PdfPageEditor--) | Konstruktor för PdfPageEditor-klassen. |
| [PdfPageEditor](#PdfPageEditor-com.aspose.pdf.Document-) | Konstruktor för PdfPageEditor-klassen. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [applyChanges](#applyChanges--) | Tillämpa ändringar som gjorts på dokumentets sidor. |
| [getAlignment](#getAlignment--) | Hämtar den horisontella justeringen av det ursprungliga PDF-innehållet på resultatsidan, standard är AlignmentType.Left. Använd getHorizontalAlignment istället. |
| [getDisplayDuration](#getDisplayDuration--) | Hämtar visningstid för sidor. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Hämtar den horisontella justeringen av det ursprungliga PDF-innehållet på resultatsidan, standard är AlignmentType.Left. |
| [getPageBoxSize](#getPageBoxSize-int-java.lang.String-) | <p> Returnerar storleken på den angivna rutan i dokumentet. </p> <hr> <pre> Följande exempel visar hur man hämtar mediaboxen för den första sidan: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); Rectangle rect = editor.getBoxSize(1, "media"); </pre> |
| [getPageRectangle](#getPageRectangle-com.aspose.pdf.Page-) | Returnera sidstorlek för sidan. |
| [getPageRotation](#getPageRotation-int-) | <p> Returnerar rotationen för den angivna sidan. </p> <hr> <pre> Följande exempel visar hur man hämtar sidrotation: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); int rotation = editor.getPageSize(1); System.out.println("Rotation of 1st page : " + rotation + " degrees"); </pre> |
| [getPageRotations](#getPageRotations--) | <p> Hämtar rotationen för sidorna, en hashtabell innehåller sidnumret och rotationsgraden, nyckeln representerar sidnumret, värdet för nyckeln representerar rotationen i grader. </p> |
| [getPages](#getPages--) | <p> Returnerar totalt antal sidor. </p> <hr> <pre> Följande exempel visar hur man använder GetPages() metoden: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); System.out.println("Document has: " + editor.GetPages()); </pre> |
| [getPageSize](#getPageSize--) | Hämtar sidstorleken för utdatafilen. |
| [getPageSize](#getPageSize-int-) | <p> Returnerar sidstorleken för den angivna sidan. </p> <hr> <pre> Följande exempel visar hur man använder GetPageSize-metoden: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); PageSize size = editor.getPageSize(1); System.out.println("Size of 1st page : " + size.getWidth() + " x " + size.getHeight()); </pre> |
| [getProcessPages](#getProcessPages--) | Hämtar sidnumren som ska redigeras. Som standard redigeras varje sida. |
| [getRotation](#getRotation--) | Hämtar rotationen för sidorna, rotationen måste vara 0, 90, 180 eller 270. Standardvärdet är 0. |
| [getTransitionDuration](#getTransitionDuration--) | Hämtar varaktigheten för övergångseffekten. |
| [getTransitionType](#getTransitionType--) | Hämtar övergångsstilen som ska användas när man går till den här sidan från en annan under en presentation. |
| [getVerticalAlignment](#getVerticalAlignment--) | Hämtar den vertikala justeringen av det ursprungliga PDF-innehållet på resultatsidan, standard är VerticalAlignmentType.Bottom. Använd getVerticalAlignmentType istället |
| [getVerticalAlignmentType](#getVerticalAlignmentType--) | Hämtar den vertikala justeringen av det ursprungliga PDF-innehållet på resultatsidan, standard är VerticalAlignmentType.Bottom. |
| [getZoom](#getZoom--) | Hämta zoomkoefficient. Värde 1.0 motsvarar 100%. Standardvärde är 1.0. |
| [isBoxDefined](#isBoxDefined-com.aspose.pdf.Page-java.lang.String-) | Kontrollera om rutan är definierad på sidan. |
| [movePosition](#movePosition-float-float-) | <p> Flyttar origo från (0, 0) till den angivna punkten. Origo är vänster-nederkant och enheten är punkt(1 inch = 72 points). </p> <hr> <pre> PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("input.pdf"); editor.movePosition(-100, 60); editor.save("moved.pdf"); </pre> |
| [save](#save-java.io.OutputStream-) | <p> Sparar ändrat dokument till en ström. </p> <hr> <pre> Följande exempel visar hur man sparar ett ändrat PDF-dokument till en ström. PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); editor.save("newdocument.pdf"); </pre> |
| [save](#save-java.lang.String-) | <p> Sparar ändrat dokument till en fil. </p> <hr> <pre> Följande exempel visar hur man sparar ett ändrat PDF-dokument PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); editor.save("newdocument.pdf"); </pre> |
| [setAlignment](#setAlignment-com.aspose.pdf.facades.AlignmentType-) | Ställer in den horisontella justeringen av det ursprungliga PDF-innehållet på resultatsidan, standard är AlignmentType.Left. Använd setHorizontalAlignment istället |
| [setDisplayDuration](#setDisplayDuration-int-) | Ställer in visningstid för sidor. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Ställer in den horisontella justeringen av det ursprungliga PDF-innehållet på resultatsidan, standard är AlignmentType.Left. |
| [setPageRotations](#setPageRotations-java.util.Map-) | Ställer in rotationen av sidorna, en hashtabell innehåller sidnumret och rotationsgraden, nyckeln representerar sidnumret, värdet för nyckeln representerar rotationen i grader. |
| [setPageSize](#setPageSize-com.aspose.pdf.PageSize-) | Ställer in sidstorleken för utdatafilen. |
| [setProcessPages](#setProcessPages-int:A-) | Ställer in sidnumren som ska redigeras. Som standard kommer varje sida att redigeras. |
| [setRotation](#setRotation-int-) | Ställer in rotationen av sidorna, rotationen måste vara 0, 90, 180 eller 270. Standardvärdet är 0. |
| [setTransitionDuration](#setTransitionDuration-int-) | Ställer in varaktigheten för övergångseffekten. |
| [setTransitionType](#setTransitionType-int-) | Ställer in övergångsstilen som ska användas när man går till den här sidan från en annan under en presentation. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.facades.VerticalAlignmentType-) | Ställer in den vertikala justeringen av det ursprungliga PDF-innehållet på resultatsidan, standard är VerticalAlignmentType.Bottom. Använd setVerticalAlignmentType istället |
| [setVerticalAlignmentType](#setVerticalAlignmentType-com.aspose.pdf.VerticalAlignment-) | Ställer in den vertikala justeringen av det ursprungliga PDF-innehållet på resultatsidan, standard är VerticalAlignmentType.Bottom. |
| [setZoom](#setZoom-float-) | <p> Ställer in zoomkoefficient. Värde 1.0 motsvarar 100 %. Standardvärdet är 1.0. </p> |

### BLINDH {#BLINDH}
```
public static final int BLINDH
```

Vertikala persienner

### BLINDV {#BLINDV}
```
public static final int BLINDV
```

Vertikala persienner

### BTWIPE {#BTWIPE}
```
public static final int BTWIPE
```

Botten-topp svep

### DGLITTER {#DGLITTER}
```
public static final int DGLITTER
```

Diagonal glitter

### DISSOLVE {#DISSOLVE}
```
public static final int DISSOLVE
```

Den gamla sidan upplöses

### INBOX {#INBOX}
```
public static final int INBOX
```

Inåtriktad ruta

### LRGLITTER {#LRGLITTER}
```
public static final int LRGLITTER
```

Vänster-höger glitter

### LRWIPE {#LRWIPE}
```
public static final int LRWIPE
```

Vänster-höger svep

### OUTBOX {#OUTBOX}
```
public static final int OUTBOX
```

Utvändig ruta

### RLWIPE {#RLWIPE}
```
public static final int RLWIPE
```

Höger-vänster svep

### SPLITHIN {#SPLITHIN}
```
public static final int SPLITHIN
```

IN horisontell delning

### SPLITHOUT {#SPLITHOUT}
```
public static final int SPLITHOUT
```

Ut horisontell delning

### SPLITVIN {#SPLITVIN}
```
public static final int SPLITVIN
```

In vertikal delning

### SPLITVOUT {#SPLITVOUT}
```
public static final int SPLITVOUT
```

Ut vertikal delning

### TBGLITTER {#TBGLITTER}
```
public static final int TBGLITTER
```

Topp-botten glitter

### TBWIPE {#TBWIPE}
```
public static final int TBWIPE
```

Topp-botten svep

### PdfPageEditor {#PdfPageEditor--}
```
public PdfPageEditor()
```

Konstruktor för PdfPageEditor-klassen.

### PdfPageEditor {#PdfPageEditor-com.aspose.pdf.Document-}
Konstruktor för PdfPageEditor-klassen.

### applyChanges {#applyChanges--}
```
public void applyChanges()
```

Tillämpa ändringar som gjorts på dokumentets sidor.

### getAlignment {#getAlignment--}
```
@Deprecated public AlignmentType getAlignment()
```

Hämtar den horisontella justeringen av det ursprungliga PDF-innehållet på resultatsidan, standard är AlignmentType.Left. Använd getHorizontalAlignment istället.

**Returns:**
AlignmentType-objekt @see HorizontalAlignment

### getDisplayDuration {#getDisplayDuration--}
```
public int getDisplayDuration()
```

Hämtar visningstid för sidor.

**Returns:**
int‑värde

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Hämtar den horisontella justeringen av det ursprungliga PDF-innehållet på resultatsidan, standard är AlignmentType.Left.

**Returns:**
HorizontalAlignment-element @see HorizontalAlignment

### getPageBoxSize {#getPageBoxSize-int-java.lang.String-}
<p> Returnerar storleken på den angivna rutan i dokumentet. </p> <hr> <pre> Följande exempel visar hur man hämtar mediaboxen för den första sidan: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); Rectangle rect = editor.getBoxSize(1, "media"); </pre>

### getPageRectangle {#getPageRectangle-com.aspose.pdf.Page-}
Returnera sidstorlek för sidan.

### getPageRotation {#getPageRotation-int-}
```
public int getPageRotation(int page)
```

<p> Returnerar rotationen för den angivna sidan. </p> <hr> <pre> Följande exempel visar hur man hämtar sidrotation: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); int rotation = editor.getPageSize(1); System.out.println("Rotation of 1st page : " + rotation + " degrees"); </pre>

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida |  | Sidindex. Dokumentets sidor är numrerade från 1. |

**Returns:**
Sidrotation i grader.

### getPageRotations {#getPageRotations--}
```
public Map < Integer , Integer > getPageRotations()
```

<p> Hämtar rotationen för sidorna, en hashtabell innehåller sidnumret och rotationsgraden, nyckeln representerar sidnumret, värdet för nyckeln representerar rotationen i grader. </p>

**Returns:**
{@code Map<Integer, Integer>}-objekt

### getPages {#getPages--}
```
public int getPages()
```

<p> Returnerar totalt antal sidor. </p> <hr> <pre> Följande exempel visar hur man använder GetPages() metoden: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); System.out.println("Document has: " + editor.GetPages()); </pre>

**Returns:**
Antal sidor.

### getPageSize {#getPageSize--}
```
public PageSize getPageSize()
```

Hämtar sidstorleken för utdatafilen.

**Returns:**
PageSize-objekt

### getPageSize {#getPageSize-int-}
```
public PageSize getPageSize(int page)
```

<p> Returnerar sidstorleken för den angivna sidan. </p> <hr> <pre> Följande exempel visar hur man använder GetPageSize-metoden: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); PageSize size = editor.getPageSize(1); System.out.println("Size of 1st page : " + size.getWidth() + " x " + size.getHeight()); </pre>

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida |  | Sidindex. Dokumentets sidor är numrerade från 1. |

**Returns:**
Resultatet är en instans av PageSize. Använd egenskaperna Width och Height i det returnerade objektet för att få sidbredd och sidhöjd.

### getProcessPages {#getProcessPages--}
```
public int[] getProcessPages()
```

Hämtar sidnumren som ska redigeras. Som standard redigeras varje sida.

**Returns:**
array med int‑värden

### getRotation {#getRotation--}
```
public int getRotation()
```

Hämtar rotationen för sidorna, rotationen måste vara 0, 90, 180 eller 270. Standardvärdet är 0.

**Returns:**
int‑värde

### getTransitionDuration {#getTransitionDuration--}
```
public int getTransitionDuration()
```

Hämtar varaktigheten för övergångseffekten.

**Returns:**
int‑värde

### getTransitionType {#getTransitionType--}
```
public int getTransitionType()
```

Hämtar övergångsstilen som ska användas när man går till den här sidan från en annan under en presentation.

**Returns:**
int‑värde

### getVerticalAlignment {#getVerticalAlignment--}
```
@Deprecated public VerticalAlignmentType getVerticalAlignment()
```

Hämtar den vertikala justeringen av det ursprungliga PDF-innehållet på resultatsidan, standard är VerticalAlignmentType.Bottom. Använd getVerticalAlignmentType istället

**Returns:**
VerticalAlignmentType-objekt

### getVerticalAlignmentType {#getVerticalAlignmentType--}
```
public VerticalAlignment getVerticalAlignmentType()
```

Hämtar den vertikala justeringen av det ursprungliga PDF-innehållet på resultatsidan, standard är VerticalAlignmentType.Bottom.

**Returns:**
VerticalAlignmentType-element @see VerticalAlignmentType

### getZoom {#getZoom--}
```
public float getZoom()
```

Hämta zoomkoefficient. Värde 1.0 motsvarar 100%. Standardvärde är 1.0.

**Returns:**
flyttalsvärde

### isBoxDefined {#isBoxDefined-com.aspose.pdf.Page-java.lang.String-}
Kontrollera om rutan är definierad på sidan.

### movePosition {#movePosition-float-float-}
```
public void movePosition(float moveX, float moveY)
```

<p> Flyttar origo från (0, 0) till den angivna punkten. Origo är vänster-nederkant och enheten är punkt(1 inch = 72 points). </p> <hr> <pre> PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("input.pdf"); editor.movePosition(-100, 60); editor.save("moved.pdf"); </pre>

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| moveX |  | X-koordinat. |
| moveY |  | Y-koordinat. |

### save {#save-java.io.OutputStream-}
<p> Sparar ändrat dokument till en ström. </p> <hr> <pre> Följande exempel visar hur man sparar ett ändrat PDF-dokument till en ström. PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); editor.save("newdocument.pdf"); </pre>

### save {#save-java.lang.String-}
<p> Sparar ändrat dokument till en fil. </p> <hr> <pre> Följande exempel visar hur man sparar ett ändrat PDF-dokument PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); editor.save("newdocument.pdf"); </pre>

### setAlignment {#setAlignment-com.aspose.pdf.facades.AlignmentType-}
Ställer in den horisontella justeringen av det ursprungliga PDF-innehållet på resultatsidan, standard är AlignmentType.Left. Använd setHorizontalAlignment istället

### setDisplayDuration {#setDisplayDuration-int-}
```
public void setDisplayDuration(int value)
```

Ställer in visningstid för sidor.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Ställer in den horisontella justeringen av det ursprungliga PDF-innehållet på resultatsidan, standard är AlignmentType.Left.

### setPageRotations {#setPageRotations-java.util.Map-}
Ställer in rotationen av sidorna, en hashtabell innehåller sidnumret och rotationsgraden, nyckeln representerar sidnumret, värdet för nyckeln representerar rotationen i grader.

### setPageSize {#setPageSize-com.aspose.pdf.PageSize-}
Ställer in sidstorleken för utdatafilen.

### setProcessPages {#setProcessPages-int:A-}
```
public void setProcessPages(int[] value)
```

Ställer in sidnumren som ska redigeras. Som standard kommer varje sida att redigeras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | array med int‑värden |

### setRotation {#setRotation-int-}
```
public void setRotation(int value)
```

Ställer in rotationen av sidorna, rotationen måste vara 0, 90, 180 eller 270. Standardvärdet är 0.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setTransitionDuration {#setTransitionDuration-int-}
```
public void setTransitionDuration(int value)
```

Ställer in varaktigheten för övergångseffekten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setTransitionType {#setTransitionType-int-}
```
public void setTransitionType(int value)
```

Ställer in övergångsstilen som ska användas när man går till den här sidan från en annan under en presentation.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.facades.VerticalAlignmentType-}
Ställer in den vertikala justeringen av det ursprungliga PDF-innehållet på resultatsidan, standard är VerticalAlignmentType.Bottom. Använd setVerticalAlignmentType istället

### setVerticalAlignmentType {#setVerticalAlignmentType-com.aspose.pdf.VerticalAlignment-}
Ställer in den vertikala justeringen av det ursprungliga PDF-innehållet på resultatsidan, standard är VerticalAlignmentType.Bottom.

### setZoom {#setZoom-float-}
```
public void setZoom(float value)
```

<p> Ställer in zoomkoefficient. Värde 1.0 motsvarar 100 %. Standardvärdet är 1.0. </p>

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | float value <hr> <pre> Följande exempel visar hur man ändrar zoom på dokumentets sidor. PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); </pre> |
