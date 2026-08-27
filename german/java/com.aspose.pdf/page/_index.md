---
title: "Page"
linktitle: "Page"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die eine Seite eines PDF-Dokuments darstellt."
type: docs
weight: 3310
url: /de/java/com.aspose.pdf/page/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Page

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.IOperatorContainer, Closeable, AutoCloseable

```
public final class Page extends Object implements com.aspose.ms.System.IDisposable, Closeable , com.aspose.pdf.engine.IOperatorContainer
```

Klasse, die eine Seite eines PDF-Dokuments darstellt.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | Akzeptiert {@code AnnotationSelector} Besucherobjekt, das Funktionalität zum Arbeiten mit Anmerkungen bereitstellt. |
| [accept](#accept-com.aspose.pdf.ImagePlacementAbsorber-) | Akzeptiert {@code ImagePlacementAbsorber} Besucherobjekt, das Funktionalität zum Arbeiten mit Bildplatzierungsobjekten bereitstellt. |
| [accept](#accept-com.aspose.pdf.TextAbsorber-) | Akzeptiert {@code TextAbsorber} Besucherobjekt, das Funktionalität zum Arbeiten mit Textobjekten bereitstellt. |
| [accept](#accept-com.aspose.pdf.TextFragmentAbsorber-) | Akzeptiert {@code TextFragmentAbsorber} Besucherobjekt, das Funktionalität zum Arbeiten mit Textobjekten bereitstellt. |
| [addGraphics](#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-) | Fügt Grafiken zur Seite hinzu. Ist schneller als das Hinzufügen von Elementen einzeln mit der Methode GraphicElement#addOnPage(Page). |
| [addGraphics](#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-com.aspose.pdf.Rectangle-) | Fügt Grafiken zur Seite hinzu. Ist schneller als das Hinzufügen von Elementen einzeln mit der Methode GraphicElement#addOnPage(Page). |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-) | Fügt ein Bild zur Seite hinzu und positioniert es in der Mitte des angegebenen Rechtecks, wobei das Bildseitenverhältnis beibehalten wird. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-) | Fügt ein durchsuchbares Bild zur Seite hinzu und positioniert es in der Mitte des angegebenen Rechtecks, wobei das Bildseitenverhältnis beibehalten wird. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-com.aspose.pdf.Rectangle-) | Fügt ein durchsuchbares Bild zur Seite hinzu und positioniert es in der Mitte des angegebenen Rechtecks, wobei das Bildseitenverhältnis beibehalten wird. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-) | Fügt ein Bild zur Seite hinzu und positioniert es in der Mitte des angegebenen Rechtecks, wobei das Bildseitenverhältnis beibehalten wird. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-) | Fügt ein Bild zur Seite hinzu und positioniert es in der Mitte des angegebenen Rechtecks, wobei das Bildseitenverhältnis beibehalten wird. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-boolean-) | Fügt ein Bild zur Seite hinzu und positioniert es in der Mitte des angegebenen Rechtecks, wobei das Bildseitenverhältnis beibehalten wird. |
| [addImage](#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-) | Fügt ein durchsuchbares Bild zur Seite hinzu und positioniert es in der Mitte des angegebenen Rechtecks, wobei das Bildseitenverhältnis beibehalten wird. |
| [addImage](#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-) | Fügt ein durchsuchbares Bild zur Seite hinzu und positioniert es in der Mitte des angegebenen Rechtecks, wobei das Bildseitenverhältnis beibehalten wird. |
| [addImage](#addImage-java.lang.String-com.aspose.pdf.Rectangle-) | Fügt ein Bild zur Seite hinzu und positioniert es in der Mitte des angegebenen Rechtecks, wobei das Bildseitenverhältnis beibehalten wird. |
| [addStamp](#addStamp-com.aspose.pdf.Stamp-) | Setzen Sie den Stempel auf die Seite. Der Stempel kann eine Seitenzahl, ein Bild oder einfacher Text sein, z. B. ein Logo. |
| [asByteArray](#asByteArray-com.aspose.pdf.devices.Resolution-) | Konvertiert die aktuelle Seite als BMP-Bitmap und gibt anschließend ein Byte‑Array zurück. |
| [asXml](#asXml--) | Konvertiert die aktuelle Seite als XML in UTF‑8‑Kodierung. |
| [calculateContentBBox](#calculateContentBBox--) | Berechnet den BBox‑Wert – ein Rechteck, das den Inhalt ohne sichtbare Ränder enthält. |
| [clearContents](#clearContents--) | Nur für den internen Gebrauch. |
| [close](#close--) | Schließt alle von diesem Dokument verwendeten Ressourcen. |
| [convertToPNGMemoryStream](#convertToPNGMemoryStream--) | Konvertiert die Seite zu PNG für DSR-, OMR‑ und OCR‑Bildstreams. |
| [deleteGraphics](#deleteGraphics-com.aspose.pdf.vector.GraphicElementCollection-) | Löscht Grafiken von der Seite. Ist schneller als das Löschen von Elementen einzeln mit der {@link GraphicElement#remove}-Methode. |
| [deleteUnusedResources](#deleteUnusedResources-com.aspose.ms.System.Collections.Generic.Dictionary-) |  |
| [dispose](#dispose--) | Gibt Speicher frei. Diese Methode ist veraltet, verwenden Sie stattdessen close(). |
| [fillUsedObjectsTable](#fillUsedObjectsTable-com.aspose.ms.System.Collections.Generic.Dictionary-com.aspose.pdf.engine.data.IPdfDictionary-) |  |
| [findReferences](#findReferences-com.aspose.pdf.OperatorCollection-java.lang.String-) | Gibt eine Liste von Operatoren zurück, die die Ressource mit dem angegebenen Namen verwenden. |
| [findReferences](#findReferences-java.lang.String-) | <p> Verweise finden </p> |
| [flatten](#flatten--) | Entfernt alle statischen Felder, die sich auf der Seite befinden, und legt stattdessen deren Werte ab. |
| [freeMemory](#freeMemory--) | Löscht zwischengespeicherte Daten |
| [getActions](#getActions--) | Liefert die Sammlung von Seiteneigenschaften. |
| [getAnnotations](#getAnnotations--) | Liefert die Sammlung von Seitenanmerkungen. {@code Annotations} |
| [getArtBox](#getArtBox--) | <p> Liefert die Art‑Box der Seite. </p> |
| [getArtifacts](#getArtifacts--) | Liefert die Sammlung von Artefakten auf der Seite. |
| [getBackground](#getBackground--) | Liefert die Hintergrundfarbe der Seite. |
| [getBackgroundImage](#getBackgroundImage--) | Liest oder setzt das Hintergrundbild für die Seite (nur für den Generator, beim Lesen des Dokuments nicht befüllt). |
| [getBleedBox](#getBleedBox--) | <p> Liefert die Beschnittbox der Seite. </p> |
| [getColorType](#getColorType--) | Liefert den Farbtyp der Seiten basierend auf Informationen, die von den Operatoren SetColor, Bildern und Formularen erhalten werden. |
| [getContents](#getContents--) | <p> Liefert die Sammlung von Operatoren im Inhaltsstrom der Seite. {@code OperatorCollection} </p> |
| [getContentsAppender](#getContentsAppender--) | Liefert den aktuellen Inhalts‑Appender. {@code ContentsAppender} |
| [getCropBox](#getCropBox--) | <p> Liefert die Beschnittbox der Seite. </p> |
| [getDocument](#getDocument--) | Dokument abrufen |
| [getDuration](#getDuration--) | <p> Liefert die Anzeigedauer der Seite. Dies ist die Zeit in Sekunden, die die Seite während einer Präsentation angezeigt werden soll. Gibt -1 zurück, wenn die Dauer nicht definiert ist. </p> <hr> Beispiel zeigt, wie man die Seitendauer abruft <p> Document document = new Document("sample.pdf"); Page page = document.getPages().get(1); int pageRect = page.getDuration(); </p> |
| [getEnginePage](#getEnginePage--) | Nur für den internen Gebrauch |
| [getFieldsInTabOrder](#getFieldsInTabOrder--) | Liefert die Liste von Field‑Objekten in Tab‑Reihenfolge auf dieser Seite. |
| [getFooter](#getFooter--) | Liefert die Seitenfußzeile. |
| [getGroup](#getGroup--) | Liefert eine Gruppen‑Attribut‑Klasse, die die Attribute der Seitengruppe für die Verwendung im transparenten Bildgebungsmodell spezifiziert. |
| [getHeader](#getHeader--) | Liefert die Seitenkopfzeile. |
| [getLayers](#getLayers--) | Ruft die Ebenensammlung ab. |
| [getMediaBox](#getMediaBox--) | <p> Ruft die MediaBox der Seite ab. </p> |
| [getNoteLineStyle](#getNoteLineStyle--) | Ruft den Linienstil für Notizen ab. (nur für Generator, beim Lesen des Dokuments nicht ausgefüllt) |
| [getNotifications](#getNotifications--) | Gibt Benachrichtigungen über interne Vorgänge mit Seiteninhalt zurück. (Derzeit werden nur Benachrichtigungen über Absatzereignisse in Text‑Hinzufügungs‑Szenarien unterstützt.) |
| [getNumber](#getNumber--) | Ruft die Seitennummer ab. |
| [getOnBeforePageGenerate](#getOnBeforePageGenerate--) | Ereignis zum Anpassen von Kopf‑ und Fußzeile. |
| [getPageInfo](#getPageInfo--) | Ruft die Seiteninformationen ab. (nur für Generator, beim Lesen des Dokuments nicht ausgefüllt). |
| [getPageRect](#getPageRect-boolean-) | Gibt das Rechteck der Seite gemäß ihrer CropBox zurück (oder MediaBox, falls CropBox null ist). |
| [getParagraphs](#getParagraphs--) | Ruft die Absätze ab. |
| [getRect_Rename_Namesake](#getRect_Rename_Namesake--) | <p> Gibt das Rechteck der Seite gemäß ihrer CropBox und MediaBox zurück; </p> Internal |
| [getRect](#getRect--) | <p> Gibt das Rechteck der Seite gemäß ihrer CropBox und MediaBox zurück; Beim Abrufen: Wird die CropBox der Seite zurückgegeben, wenn angegeben, sonst wird die MediaBox der Seite zurückgegeben. Beim Setzen: Wird die MediaBox der Seite immer gesetzt. </p> |
| [getResources](#getResources--) | Ruft die mit der Seite verbundenen Ressourcen ab. |
| [getResourcesField](#getResourcesField--) | <p> Ruft Seitenressourcen ab. Das Ressourcen‑Objekt enthält Sammlungen von Bildern, Formularen und Schriften. {@code Resources} </p> |
| [getRotate](#getRotate--) | <p> Ruft die Drehung der Seite ab. </p> |
| [getRotationMatrix](#getRotationMatrix--) | Ruft die Transformationsmatrix für die Seite ab. |
| [getTabOrder](#getTabOrder--) | Ruft die Tab‑Reihenfolge der Seite ab. Mögliche Werte: Zeile, Spalte. Standard, Manuell |
| [getTocInfo](#getTocInfo--) | Ruft die Informationen zum Inhaltsverzeichnis ab. |
| [getTrimBox](#getTrimBox--) | <p> Ruft die TrimBox der Seite ab. </p> |
| [getUserUnit](#getUserUnit--) | Liest oder setzt den UserUnit-Wert. Eine positive Zahl, die die Größe der Standard‑User‑Space‑Einheiten in Vielfachen von 1/72 Zoll angibt. Der Standardwert ist 1. Bitte setzen Sie null oder einen negativen Wert, um diesen Eintrag auf der Seite zu löschen. |
| [getWatermark](#getWatermark--) | Ruft das Wasserzeichen der Seite ab. |
| [hasVectorGraphics](#hasVectorGraphics--) | Erkennt das Vorhandensein von Vektorgrafiken, falls sie auf der Seite vorhanden sind. |
| [intToRotation](#intToRotation-int-) | Übersetzt einen Ganzzahlwert in das entsprechende Rotations‑Enum‑Mitglied. |
| [isAddParagraphsAfterLast](#isAddParagraphsAfterLast--) | Liest oder setzt das Hinzufügen von Absätzen nach dem letzten Absatz der Seite. Wert: Der Wert gibt an, ob Absätze nach dem letzten Absatz der Seite hinzugefügt werden. Absätze werden nach dem letzten Absatz der Seite hinzugefügt, wenn der Wert true ist. |
| [isBlank](#isBlank-double-) | Ruft das Flag ab, ob die Seite leer ist oder nicht. |
| [isBlank](#isBlank-double-boolean-) | Ruft das Flag ab, ob die Seite leer ist oder nicht. |
| [makeGrayscale](#makeGrayscale--) | Konvertiert die Seite in Graustufen. |
| [mergeLayers](#mergeLayers-java.lang.String-) | Fügt alle Ebenen auf der Seite zu einer einzelnen Ebene mit dem angegebenen neuen Ebenennamen zusammen. |
| [mergeLayers](#mergeLayers-java.lang.String-java.lang.String-) | Fügt alle Ebenen auf der Seite zu einer einzelnen Ebene mit dem angegebenen neuen Ebenennamen und optionaler Inhaltsgruppen‑Id zusammen. |
| [removeObjectReferences](#removeObjectReferences-com.aspose.pdf.OperatorCollection-java.lang.String-) | Objektverweise entfernen |
| [removeObjectReferences](#removeObjectReferences-java.lang.String-) | Entfernt Verweise auf XObject aus dem Seiteninhalt (d. h. alle Do‑Operatoren, die den Namen des Objekts verwenden). |
| [resize](#resize-com.aspose.pdf.PageSize-) | Ändert die Größe der Seite. |
| [rotationToInt](#rotationToInt-com.aspose.pdf.Rotation-) | Übersetzt das Rotations‑Enum‑Element in einen Ganzzahlwert. |
| [sendTo](#sendTo-com.aspose.pdf.devices.PageDevice-java.io.OutputStream-) | Sendet die Seite zur Verarbeitung mit dem angegebenen Seiten‑Gerät. |
| [sendTo](#sendTo-com.aspose.pdf.devices.PageDevice-java.lang.String-) | Sendet die Seite zur Verarbeitung mit dem angegebenen Seiten‑Gerät. |
| [setAddParagraphsAfterLast](#setAddParagraphsAfterLast-boolean-) | Liest oder setzt das Hinzufügen von Absätzen nach dem letzten Absatz der Seite. Wert: Der Wert gibt an, ob Absätze nach dem letzten Absatz der Seite hinzugefügt werden. Absätze werden nach dem letzten Absatz der Seite hinzugefügt, wenn der Wert true ist. |
| [setArtBox](#setArtBox-com.aspose.pdf.Rectangle-) | Setzt die Art‑Box der Seite. |
| [setBackground](#setBackground-java.awt.Color-) | Setzt die Hintergrundfarbe der Seite. |
| [setBackground](#setBackground-com.aspose.pdf.Color-) | Setzt die Hintergrundfarbe der Seite. |
| [setBackgroundImage](#setBackgroundImage-com.aspose.pdf.Image-) | Liest oder setzt das Hintergrundbild für die Seite (nur für den Generator, beim Lesen des Dokuments nicht befüllt). |
| [setBleedBox](#setBleedBox-com.aspose.pdf.Rectangle-) | Setzt die Beschnitt‑Box der Seite. |
| [setCropBox](#setCropBox-com.aspose.pdf.Rectangle-) | <p> Setzt die Beschnitt‑Box der Seite. </p> <hr> <pre> Beispiel zeigt, wie man die Beschnitt‑Box der Seite erhält: Document document = new Document("sample.pdf"); document.getPages().get_Item(1).setCropBox(new Rectangle(0d,0d,100d,100d)); </pre> |
| [setDuration](#setDuration-double-) | Setzt die Anzeigedauer der Seite. Dies ist die Zeit in Sekunden, die die Seite während einer Präsentation angezeigt werden soll. Gibt -1 zurück, wenn die Dauer nicht definiert ist. |
| [setEnginePage](#setEnginePage-com.aspose.pdf.engine.commondata.IPage-) | Nur für den internen Gebrauch |
| [setFooter](#setFooter-com.aspose.pdf.HeaderFooter-) | Setzt die Seitenfußzeile. |
| [setGroup](#setGroup-com.aspose.pdf.Group-) | Setzt eine Gruppenattribute‑Klasse, die die Attribute der Seiten‑Gruppierung für die Verwendung im transparenten Bildgebungsmodell spezifiziert. |
| [setHeader](#setHeader-com.aspose.pdf.HeaderFooter-) | Setzt die Seitenkopfzeile. |
| [setLayers](#setLayers-java.util.ArrayList-) | Setzt die Ebenensammlung. |
| [setLayersInternal](#setLayersInternal-com.aspose.ms.System.Collections.Generic.List-) | Setzt die Ebenensammlung. |
| [setMediaBox](#setMediaBox-com.aspose.pdf.Rectangle-) | Setzt die Medien‑Box der Seite. |
| [setNoteLineStyle](#setNoteLineStyle-com.aspose.pdf.GraphInfo-) | Setzt den Linienstil für Anmerkungen. (nur für Generator, beim Lesen des Dokuments nicht ausgefüllt) |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Setzt die Seiteninformationen. (nur für Generator, beim Lesen des Dokuments nicht ausgefüllt). |
| [setPageSize](#setPageSize-double-double-) | Setzt die Seitengröße für die Seite. |
| [setParagraphs](#setParagraphs-com.aspose.pdf.Paragraphs-) | Setzt die Absätze. |
| [setRect](#setRect-com.aspose.pdf.Rectangle-) | Liest oder setzt das Rechteck der Seite. Beim Lesen: page crop box wird zurückgegeben, wenn angegeben, sonst wird page media box zurückgegeben. Beim Schreiben: page media box wird immer gesetzt. Bitte beachten Sie, dass diese Eigenschaft die Seitenrotation nicht berücksichtigt. Um das Seitenrechteck unter Berücksichtigung der Rotation zu erhalten, verwenden Sie bitte ActualRect. |
| [setRotate](#setRotate-com.aspose.pdf.Rotation-) | Setzt die Rotation der Seite. |
| [setTabOrder](#setTabOrder-int-) | Setzt die Tab‑Reihenfolge der Seite. Mögliche Werte: Row, Column. Standard, Manual |
| [setTocInfo](#setTocInfo-com.aspose.pdf.TocInfo-) | Setzt die Informationen zum Inhaltsverzeichnis. |
| [setTransition](#setTransition-com.aspose.pdf.engine.data.IPdfDictionary-) | Übergang festlegen |
| [setTrimBox](#setTrimBox-com.aspose.pdf.Rectangle-) | Legt die Beschnittbox der Seite fest. |
| [setUserUnit](#setUserUnit-double-) | Liest oder setzt den UserUnit-Wert. Eine positive Zahl, die die Größe der Standard‑User‑Space‑Einheiten in Vielfachen von 1/72 Zoll angibt. Der Standardwert ist 1. Bitte setzen Sie null oder einen negativen Wert, um diesen Eintrag auf der Seite zu löschen. |
| [setWatermark](#setWatermark-com.aspose.pdf.Watermark-) | Legt das Wasserzeichen der Seite fest. |
| [trySaveVectorGraphics](#trySaveVectorGraphics-java.lang.String-) | Versucht, Vektorgrafiken zu speichern, wenn sie auf der Seite vorhanden sind. Das Speicherformat ist SVG. |

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
Akzeptiert {@code AnnotationSelector} Besucherobjekt, das Funktionalität zum Arbeiten mit Anmerkungen bereitstellt.

### accept {#accept-com.aspose.pdf.ImagePlacementAbsorber-}
Akzeptiert {@code ImagePlacementAbsorber} Besucherobjekt, das Funktionalität zum Arbeiten mit Bildplatzierungsobjekten bereitstellt.

### accept {#accept-com.aspose.pdf.TextAbsorber-}
Akzeptiert {@code TextAbsorber} Besucherobjekt, das Funktionalität zum Arbeiten mit Textobjekten bereitstellt.

### accept {#accept-com.aspose.pdf.TextFragmentAbsorber-}
Akzeptiert {@code TextFragmentAbsorber} Besucherobjekt, das Funktionalität zum Arbeiten mit Textobjekten bereitstellt.

### addGraphics {#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-}
Fügt Grafiken zur Seite hinzu. Ist schneller als das Hinzufügen von Elementen einzeln mit der Methode GraphicElement#addOnPage(Page).

### addGraphics {#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-com.aspose.pdf.Rectangle-}
Fügt Grafiken zur Seite hinzu. Ist schneller als das Hinzufügen von Elementen einzeln mit der Methode GraphicElement#addOnPage(Page).

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-}
Fügt ein Bild zur Seite hinzu und positioniert es in der Mitte des angegebenen Rechtecks, wobei das Bildseitenverhältnis beibehalten wird.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-}
Fügt ein durchsuchbares Bild zur Seite hinzu und positioniert es in der Mitte des angegebenen Rechtecks, wobei das Bildseitenverhältnis beibehalten wird.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-com.aspose.pdf.Rectangle-}
Fügt ein durchsuchbares Bild zur Seite hinzu und positioniert es in der Mitte des angegebenen Rechtecks, wobei das Bildseitenverhältnis beibehalten wird.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-}
Fügt ein Bild zur Seite hinzu und positioniert es in der Mitte des angegebenen Rechtecks, wobei das Bildseitenverhältnis beibehalten wird.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-}
Fügt ein Bild zur Seite hinzu und positioniert es in der Mitte des angegebenen Rechtecks, wobei das Bildseitenverhältnis beibehalten wird.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-boolean-}
Fügt ein Bild zur Seite hinzu und positioniert es in der Mitte des angegebenen Rechtecks, wobei das Bildseitenverhältnis beibehalten wird.

### addImage {#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-}
Fügt ein durchsuchbares Bild zur Seite hinzu und positioniert es in der Mitte des angegebenen Rechtecks, wobei das Bildseitenverhältnis beibehalten wird.

### addImage {#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-}
Fügt ein durchsuchbares Bild zur Seite hinzu und positioniert es in der Mitte des angegebenen Rechtecks, wobei das Bildseitenverhältnis beibehalten wird.

### addImage {#addImage-java.lang.String-com.aspose.pdf.Rectangle-}
Fügt ein Bild zur Seite hinzu und positioniert es in der Mitte des angegebenen Rechtecks, wobei das Bildseitenverhältnis beibehalten wird.

### addStamp {#addStamp-com.aspose.pdf.Stamp-}
Setzen Sie den Stempel auf die Seite. Der Stempel kann eine Seitenzahl, ein Bild oder einfacher Text sein, z. B. ein Logo.

### asByteArray {#asByteArray-com.aspose.pdf.devices.Resolution-}
Konvertiert die aktuelle Seite als BMP-Bitmap und gibt anschließend ein Byte‑Array zurück.

### asXml {#asXml--}
```
public String asXml()
```

Konvertiert die aktuelle Seite als XML in UTF‑8‑Kodierung.

**Returns:**
Konvertierte XML-Zeichenkette.

### calculateContentBBox {#calculateContentBBox--}
```
public Rectangle calculateContentBBox()
```

Berechnet den BBox‑Wert – ein Rechteck, das den Inhalt ohne sichtbare Ränder enthält.

**Returns:**
Bbox-Wert – Rechteck, das Inhalte ohne sichtbare Ränder enthält

### clearContents {#clearContents--}
```
public void clearContents()
```

Nur für den internen Gebrauch.

### close {#close--}
```
public void close()
```

Schließt alle von diesem Dokument verwendeten Ressourcen.

### convertToPNGMemoryStream {#convertToPNGMemoryStream--}
```
public byte[] convertToPNGMemoryStream()
```

Konvertiert die Seite zu PNG für DSR-, OMR‑ und OCR‑Bildstreams.

**Returns:**
Bildstrom im byte[]-Array.

### deleteGraphics {#deleteGraphics-com.aspose.pdf.vector.GraphicElementCollection-}
Löscht Grafiken von der Seite. Ist schneller als das Löschen von Elementen einzeln mit der {@link GraphicElement#remove}-Methode.

### deleteUnusedResources {#deleteUnusedResources-com.aspose.ms.System.Collections.Generic.Dictionary-}


### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Gibt Speicher frei. Diese Methode ist veraltet, verwenden Sie stattdessen close().

### fillUsedObjectsTable {#fillUsedObjectsTable-com.aspose.ms.System.Collections.Generic.Dictionary-com.aspose.pdf.engine.data.IPdfDictionary-}


### findReferences {#findReferences-com.aspose.pdf.OperatorCollection-java.lang.String-}
Gibt eine Liste von Operatoren zurück, die die Ressource mit dem angegebenen Namen verwenden.

### findReferences {#findReferences-java.lang.String-}
<p> Verweise finden </p>

### flatten {#flatten--}
```
public void flatten()
```

Entfernt alle statischen Felder, die sich auf der Seite befinden, und legt stattdessen deren Werte ab.

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

Löscht zwischengespeicherte Daten

### getActions {#getActions--}
```
public PageActionCollection getActions()
```

Liefert die Sammlung von Seiteneigenschaften.

**Returns:**
PageActionCollection-Wert

### getAnnotations {#getAnnotations--}
```
public AnnotationCollection getAnnotations()
```

Liefert die Sammlung von Seitenanmerkungen. {@code Annotations}

**Returns:**
AnnotationCollection-Wert

### getArtBox {#getArtBox--}
```
public Rectangle getArtBox()
```

<p> Liefert die Art‑Box der Seite. </p>

**Returns:**
Rechteck-Wert <hr> <pre> Beispiel zeigt, wie man die Art-Box der Seite erhält: Document document = new Document("sample.pdf"); Rectangle artBox = document.getPages().get(1).getArtBox(); </pre>

### getArtifacts {#getArtifacts--}
```
public ArtifactCollection getArtifacts()
```

Liefert die Sammlung von Artefakten auf der Seite.

**Returns:**
ArtifactCollection-Wert

### getBackground {#getBackground--}
```
public Color getBackground()
```

Liefert die Hintergrundfarbe der Seite.

**Returns:**
Farbwert

### getBackgroundImage {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```

Liest oder setzt das Hintergrundbild für die Seite (nur für den Generator, beim Lesen des Dokuments nicht befüllt).

**Returns:**
Bildinstanz

### getBleedBox {#getBleedBox--}
```
public Rectangle getBleedBox()
```

<p> Liefert die Beschnittbox der Seite. </p>

**Returns:**
Rechteck-Wert <hr> <pre> Beispiel zeigt, wie man die Beschnittbox der Seite erhält: Document document = new Document("sample.pdf"); Rectangle bleedBox = document.getPages().get(1).getBleedBox(); </pre>

### getColorType {#getColorType--}
```
public ColorType getColorType()
```

Liefert den Farbtyp der Seiten basierend auf Informationen, die von den Operatoren SetColor, Bildern und Formularen erhalten werden.

**Returns:**
ColorType-Element @see ColorType

### getContents {#getContents--}
```
public OperatorCollection getContents()
```

<p> Liefert die Sammlung von Operatoren im Inhaltsstrom der Seite. {@code OperatorCollection} </p>

**Returns:**
OperatorCollection-Objekt <hr> <pre> Beispiel zeigt, wie man den Operatoren-Stream einer Seite scannt. Document document = new Document("sample.pdf"); Operators contents = document.getPages().get_Item(1).getContents(); for(Operator op : {@code (Iterable<Operator>)}contents) { System.out.println(op); } </pre>

### getContentsAppender {#getContentsAppender--}
```
public ContentsAppender getContentsAppender()
```

Liefert den aktuellen Inhalts‑Appender. {@code ContentsAppender}

**Returns:**
ContentsAppender-Wert

### getCropBox {#getCropBox--}
```
public Rectangle getCropBox()
```

<p> Liefert die Beschnittbox der Seite. </p>

**Returns:**
Rechteck-Wert <hr> <pre> Beispiel zeigt, wie man die Crop-Box der Seite erhält: Document document = new Document("sample.pdf"); Rectangle cropBox = document.getPages().get_Item(1).getCropBox(); </pre>

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

Dokument abrufen

**Returns:**
IDocument‑Objekt

### getDuration {#getDuration--}
```
public double getDuration()
```

<p> Liefert die Anzeigedauer der Seite. Dies ist die Zeit in Sekunden, die die Seite während einer Präsentation angezeigt werden soll. Gibt -1 zurück, wenn die Dauer nicht definiert ist. </p> <hr> Beispiel zeigt, wie man die Seitendauer abruft <p> Document document = new Document("sample.pdf"); Page page = document.getPages().get(1); int pageRect = page.getDuration(); </p>

**Returns:**
double-Wert

### getEnginePage {#getEnginePage--}
```
public com.aspose.pdf.engine.commondata.IPage getEnginePage()
```

Nur für den internen Gebrauch

**Returns:**
interne Instanz

### getFieldsInTabOrder {#getFieldsInTabOrder--}
```
public List < Field > getFieldsInTabOrder()
```

Liefert die Liste von Field‑Objekten in Tab‑Reihenfolge auf dieser Seite.

**Returns:**
Liste von Feldobjekten

### getFooter {#getFooter--}
```
public HeaderFooter getFooter()
```

Liefert die Seitenfußzeile.

**Returns:**
Die Seitenfußzeile.

### getGroup {#getGroup--}
```
public Group getGroup()
```

Liefert eine Gruppen‑Attribut‑Klasse, die die Attribute der Seitengruppe für die Verwendung im transparenten Bildgebungsmodell spezifiziert.

**Returns:**
Gruppenwert

### getHeader {#getHeader--}
```
public HeaderFooter getHeader()
```

Liefert die Seitenkopfzeile.

**Returns:**
Die Seitenkopfzeile.

### getLayers {#getLayers--}
```
public List < Layer > getLayers()
```

Ruft die Ebenensammlung ab.

**Returns:**
Wert: Die Sammlung der Ebenen.

### getMediaBox {#getMediaBox--}
```
public Rectangle getMediaBox()
```

<p> Ruft die MediaBox der Seite ab. </p>

**Returns:**
Rechteck-Wert <hr> <pre> Beispiel zeigt, wie man die Media-Box der Seite erhält: Document document = new Document("sample.pdf"); Rectangle mediaBox = document.getPages().get(1).getMediaBox(); </pre>

### getNoteLineStyle {#getNoteLineStyle--}
```
public GraphInfo getNoteLineStyle()
```

Ruft den Linienstil für Notizen ab. (nur für Generator, beim Lesen des Dokuments nicht ausgefüllt)

**Returns:**
GraphInfo-Wert

### getNotifications {#getNotifications--}
```
public String getNotifications()
```

Gibt Benachrichtigungen über interne Vorgänge mit Seiteninhalt zurück. (Derzeit werden nur Benachrichtigungen über Absatzereignisse in Text‑Hinzufügungs‑Szenarien unterstützt.)

**Returns:**
Zeichenkette, die Benachrichtigungen über interne Vorgänge mit Seiteninhalt darstellt.

### getNumber {#getNumber--}
```
public final int getNumber()
```

Ruft die Seitennummer ab.

**Returns:**
int-Wert

### getOnBeforePageGenerate {#getOnBeforePageGenerate--}
```
public PdfEvent < Page.BeforePageGenerate > getOnBeforePageGenerate()
```

Ereignis zum Anpassen von Kopf‑ und Fußzeile.

**Returns:**
{@code PdfEvent<BeforePageGenerate> Instanz}

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

Ruft die Seiteninformationen ab. (nur für Generator, beim Lesen des Dokuments nicht ausgefüllt).

**Returns:**
Die Seiteninfo.

### getPageRect {#getPageRect-boolean-}
```
public Rectangle getPageRect(boolean considerRotation)
```

Gibt das Rechteck der Seite gemäß ihrer CropBox zurück (oder MediaBox, falls CropBox null ist).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| considerRotation |  | Wenn true, dann wird die Drehung der Seite bei der Rechteckberechnung berücksichtigt. |

**Returns:**
Rechteck der Seite.

### getParagraphs {#getParagraphs--}
```
public Paragraphs getParagraphs()
```

Ruft die Absätze ab.

**Returns:**
Die Absätze.

### getRect_Rename_Namesake {#getRect_Rename_Namesake--}
```
public Rectangle getRect_Rename_Namesake()
```

<p> Gibt das Rechteck der Seite gemäß ihrer CropBox und MediaBox zurück; </p> Internal

**Returns:**
Rechteckwert <hr> <pre> Beispiel zeigt, wie man das Seitenrechteck erhält: Document document = new Document(\"sample.pdf\"); Page page = document.getPages().get(1); Rectangle pageRect = page.getRect(); </pre>

### getRect {#getRect--}
```
public Rectangle getRect()
```

<p> Gibt das Rechteck der Seite gemäß ihrer CropBox und MediaBox zurück; Beim Abrufen: Wird die CropBox der Seite zurückgegeben, wenn angegeben, sonst wird die MediaBox der Seite zurückgegeben. Beim Setzen: Wird die MediaBox der Seite immer gesetzt. </p>

**Returns:**
Rechteckwert <hr> <pre> Beispiel zeigt, wie man das Seitenrechteck erhält: Document document = new Document(\"sample.pdf\"); Page page = document.getPages().get(1); Rectangle pageRect = page.getRect(); </pre>

### getResources {#getResources--}
```
public final Resources getResources()
```

Ruft die mit der Seite verbundenen Ressourcen ab.

**Returns:**
Ein {@code Resources}({@link #getResources()}) Objekt, das die Ressourcen der Seite darstellt.

### getResourcesField {#getResourcesField--}
```
public Resources getResourcesField()
```

<p> Ruft Seitenressourcen ab. Das Ressourcen‑Objekt enthält Sammlungen von Bildern, Formularen und Schriften. {@code Resources} </p>

**Returns:**
Ressourcenwert <hr> <pre> Beispiel zeigt das Durchsuchen von Seitenbildern: Document document = new Document(\"sample.pdf\"); DocumentActions actions = document.getActions(); Resources resources = document.getPages().get(1).getResources(); for(XImage image : {@code (Iterable<XImage>)resources}.getImages()) { System.out.println(image.getWidth() + \":\" + image.getHeight()); } </pre>

### getRotate {#getRotate--}
```
public Rotation getRotate()
```

<p> Ruft die Drehung der Seite ab. </p>

**Returns:**
Drehungselement <hr> <pre> Beispiel zeigt, wie man die Seitendrehung bestimmt. Document document = new Document(\"sample.pdf\"); System.out.println(document.getPages().get(1).getRotate()); </pre> @see Rotation

### getRotationMatrix {#getRotationMatrix--}
```
public Matrix getRotationMatrix()
```

Ruft die Transformationsmatrix für die Seite ab.

**Returns:**
Matrixwert

### getTabOrder {#getTabOrder--}
```
public int getTabOrder()
```

Ruft die Tab‑Reihenfolge der Seite ab. Mögliche Werte: Zeile, Spalte. Standard, Manuell

**Returns:**
TabOrder-Wert @see TabOrder

### getTocInfo {#getTocInfo--}
```
public TocInfo getTocInfo()
```

Ruft die Informationen zum Inhaltsverzeichnis ab.

**Returns:**
Die Inhaltsverzeichnis-Information - standardmäßig null. Wenn sie gesetzt ist, enthält diese Seite ein Inhaltsverzeichnis.

### getTrimBox {#getTrimBox--}
```
public Rectangle getTrimBox()
```

<p> Ruft die TrimBox der Seite ab. </p>

**Returns:**
Rechteckwert <hr> <pre> Beispiel zeigt, wie man die Beschnittbox der Seite erhält: Document document = new Document(\"sample.pdf\"); Rectangle trimBox = document.getPages().get(1).getTrimBox(); </pre>

### getUserUnit {#getUserUnit--}
```
public final double getUserUnit()
```

Liest oder setzt den UserUnit-Wert. Eine positive Zahl, die die Größe der Standard‑User‑Space‑Einheiten in Vielfachen von 1/72 Zoll angibt. Der Standardwert ist 1. Bitte setzen Sie null oder einen negativen Wert, um diesen Eintrag auf der Seite zu löschen.

**Returns:**
double-Wert

### getWatermark {#getWatermark--}
```
public Watermark getWatermark()
```

Ruft das Wasserzeichen der Seite ab.

**Returns:**
Wasserzeichenwert

### hasVectorGraphics {#hasVectorGraphics--}
```
public final boolean hasVectorGraphics()
```

Erkennt das Vorhandensein von Vektorgrafiken, falls sie auf der Seite vorhanden sind.

**Returns:**
True, wenn die Seite Pfadkonstruktionsoperatoren enthält; andernfalls False.

### intToRotation {#intToRotation-int-}
```
public static Rotation intToRotation(int rotation)
```

Übersetzt einen Ganzzahlwert in das entsprechende Rotations‑Enum‑Mitglied.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Drehung |  | Ganzzahlwert zum Konvertieren |

**Returns:**
Rotation-Aufzählungsmitglied @see Rotation

### isAddParagraphsAfterLast {#isAddParagraphsAfterLast--}
```
public final boolean isAddParagraphsAfterLast()
```

Liest oder setzt das Hinzufügen von Absätzen nach dem letzten Absatz der Seite. Wert: Der Wert gibt an, ob Absätze nach dem letzten Absatz der Seite hinzugefügt werden. Absätze werden nach dem letzten Absatz der Seite hinzugefügt, wenn der Wert true ist.

**Returns:**
boolescher Wert

### isBlank {#isBlank-double-}
```
public boolean isBlank(double fillThresholdFactor)
```

Ruft das Flag ab, ob die Seite leer ist oder nicht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fillThresholdFactor |  | Der Füllschwellenwert, der die Empfindlichkeit der Erkennung steuert. Sollte im Bereich [0..1) liegen. Um zu bestimmen, ob eine Seite leer ist oder nicht, wird das Verhältnis des gefüllten Bereichs zur Gesamtfläche der Seite berechnet. Dieses Verhältnis wird mit dem Parameter fillThresholdFactor verglichen und wenn es kleiner ist, wird die Seite als leer betrachtet. |

**Returns:**
boolescher Wert True - wenn die Seite leer ist; andernfalls false.

### isBlank {#isBlank-double-boolean-}
```
public boolean isBlank(double fillThresholdFactor, boolean parseWhiteContent)
```

Ruft das Flag ab, ob die Seite leer ist oder nicht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fillThresholdFactor |  | Der Füllschwellenwert, der die Empfindlichkeit der Erkennung steuert. Sollte gleich oder größer als 0,01 sein. |
| parseWhiteContent |  | True für vollständiges Scannen der Seite mit Analyse von weißem Inhalt, False (standard) - schneller Algorithmus, bei dem weiße Grafiken als nicht leere Seite gezählt werden. |

**Returns:**
boolescher Wert True - wenn die Seite leer ist; andernfalls false.

### makeGrayscale {#makeGrayscale--}
```
public final void makeGrayscale()
```

Konvertiert die Seite in Graustufen.

### mergeLayers {#mergeLayers-java.lang.String-}
Fügt alle Ebenen auf der Seite zu einer einzelnen Ebene mit dem angegebenen neuen Ebenennamen zusammen.

### mergeLayers {#mergeLayers-java.lang.String-java.lang.String-}
Fügt alle Ebenen auf der Seite zu einer einzelnen Ebene mit dem angegebenen neuen Ebenennamen und optionaler Inhaltsgruppen‑Id zusammen.

### removeObjectReferences {#removeObjectReferences-com.aspose.pdf.OperatorCollection-java.lang.String-}
Objektverweise entfernen

### removeObjectReferences {#removeObjectReferences-java.lang.String-}
Entfernt Verweise auf XObject aus dem Seiteninhalt (d. h. alle Do‑Operatoren, die den Namen des Objekts verwenden).

### resize {#resize-com.aspose.pdf.PageSize-}
Ändert die Größe der Seite.

### rotationToInt {#rotationToInt-com.aspose.pdf.Rotation-}
Übersetzt das Rotations‑Enum‑Element in einen Ganzzahlwert.

### sendTo {#sendTo-com.aspose.pdf.devices.PageDevice-java.io.OutputStream-}
Sendet die Seite zur Verarbeitung mit dem angegebenen Seiten‑Gerät.

### sendTo {#sendTo-com.aspose.pdf.devices.PageDevice-java.lang.String-}
Sendet die Seite zur Verarbeitung mit dem angegebenen Seiten‑Gerät.

### setAddParagraphsAfterLast {#setAddParagraphsAfterLast-boolean-}
```
public final void setAddParagraphsAfterLast(boolean value)
```

Liest oder setzt das Hinzufügen von Absätzen nach dem letzten Absatz der Seite. Wert: Der Wert gibt an, ob Absätze nach dem letzten Absatz der Seite hinzugefügt werden. Absätze werden nach dem letzten Absatz der Seite hinzugefügt, wenn der Wert true ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setArtBox {#setArtBox-com.aspose.pdf.Rectangle-}
Setzt die Art‑Box der Seite.

### setBackground {#setBackground-java.awt.Color-}
Setzt die Hintergrundfarbe der Seite.

### setBackground {#setBackground-com.aspose.pdf.Color-}
Setzt die Hintergrundfarbe der Seite.

### setBackgroundImage {#setBackgroundImage-com.aspose.pdf.Image-}
Liest oder setzt das Hintergrundbild für die Seite (nur für den Generator, beim Lesen des Dokuments nicht befüllt).

### setBleedBox {#setBleedBox-com.aspose.pdf.Rectangle-}
Setzt die Beschnitt‑Box der Seite.

### setCropBox {#setCropBox-com.aspose.pdf.Rectangle-}
<p> Setzt die Beschnitt‑Box der Seite. </p> <hr> <pre> Beispiel zeigt, wie man die Beschnitt‑Box der Seite erhält: Document document = new Document("sample.pdf"); document.getPages().get_Item(1).setCropBox(new Rectangle(0d,0d,100d,100d)); </pre>

### setDuration {#setDuration-double-}
```
public void setDuration(double value)
```

Setzt die Anzeigedauer der Seite. Dies ist die Zeit in Sekunden, die die Seite während einer Präsentation angezeigt werden soll. Gibt -1 zurück, wenn die Dauer nicht definiert ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Anzeigedauer der Seite. |

### setEnginePage {#setEnginePage-com.aspose.pdf.engine.commondata.IPage-}
Nur für den internen Gebrauch

### setFooter {#setFooter-com.aspose.pdf.HeaderFooter-}
Setzt die Seitenfußzeile.

### setGroup {#setGroup-com.aspose.pdf.Group-}
Setzt eine Gruppenattribute‑Klasse, die die Attribute der Seiten‑Gruppierung für die Verwendung im transparenten Bildgebungsmodell spezifiziert.

### setHeader {#setHeader-com.aspose.pdf.HeaderFooter-}
Setzt die Seitenkopfzeile.

### setLayers {#setLayers-java.util.ArrayList-}
Setzt die Ebenensammlung.

### setLayersInternal {#setLayersInternal-com.aspose.ms.System.Collections.Generic.List-}
Setzt die Ebenensammlung.

### setMediaBox {#setMediaBox-com.aspose.pdf.Rectangle-}
Setzt die Medien‑Box der Seite.

### setNoteLineStyle {#setNoteLineStyle-com.aspose.pdf.GraphInfo-}
Setzt den Linienstil für Anmerkungen. (nur für Generator, beim Lesen des Dokuments nicht ausgefüllt)

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
Setzt die Seiteninformationen. (nur für Generator, beim Lesen des Dokuments nicht ausgefüllt).

### setPageSize {#setPageSize-double-double-}
```
public void setPageSize(double width, double height)
```

Setzt die Seitengröße für die Seite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite |  | Seitenbreite. |
| Höhe |  | Seitengröße. |

### setParagraphs {#setParagraphs-com.aspose.pdf.Paragraphs-}
Setzt die Absätze.

### setRect {#setRect-com.aspose.pdf.Rectangle-}
Liest oder setzt das Rechteck der Seite. Beim Lesen: page crop box wird zurückgegeben, wenn angegeben, sonst wird page media box zurückgegeben. Beim Schreiben: page media box wird immer gesetzt. Bitte beachten Sie, dass diese Eigenschaft die Seitenrotation nicht berücksichtigt. Um das Seitenrechteck unter Berücksichtigung der Rotation zu erhalten, verwenden Sie bitte ActualRect.

### setRotate {#setRotate-com.aspose.pdf.Rotation-}
Setzt die Rotation der Seite.

### setTabOrder {#setTabOrder-int-}
```
public void setTabOrder(int value)
```

Setzt die Tab‑Reihenfolge der Seite. Mögliche Werte: Row, Column. Standard, Manual

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | TabOrder-Objekt @see TabOrder |

### setTocInfo {#setTocInfo-com.aspose.pdf.TocInfo-}
Setzt die Informationen zum Inhaltsverzeichnis.

### setTransition {#setTransition-com.aspose.pdf.engine.data.IPdfDictionary-}
Übergang festlegen

### setTrimBox {#setTrimBox-com.aspose.pdf.Rectangle-}
Legt die Beschnittbox der Seite fest.

### setUserUnit {#setUserUnit-double-}
```
public final void setUserUnit(double value)
```

Liest oder setzt den UserUnit-Wert. Eine positive Zahl, die die Größe der Standard‑User‑Space‑Einheiten in Vielfachen von 1/72 Zoll angibt. Der Standardwert ist 1. Bitte setzen Sie null oder einen negativen Wert, um diesen Eintrag auf der Seite zu löschen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setWatermark {#setWatermark-com.aspose.pdf.Watermark-}
Legt das Wasserzeichen der Seite fest.

### trySaveVectorGraphics {#trySaveVectorGraphics-java.lang.String-}
Versucht, Vektorgrafiken zu speichern, wenn sie auf der Seite vorhanden sind. Das Speicherformat ist SVG.
