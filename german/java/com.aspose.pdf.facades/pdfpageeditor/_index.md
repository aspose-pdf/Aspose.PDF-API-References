---
title: "PdfPageEditor"
linktitle: "PdfPageEditor"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Klasse dar, um die Seite der PDF-Datei zu bearbeiten, einschließlich Drehen der Seite, Zoomen der Seite, Verschieben der Position und Ändern der Seitengröße."
type: docs
weight: 570
url: /de/java/com.aspose.pdf.facades/pdfpageeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfPageEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfPageEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfPageEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfPageEditor extends SaveableFacade
```

Stellt eine Klasse dar, um die Seite der PDF-Datei zu bearbeiten, einschließlich Drehen der Seite, Zoomen der Seite, Verschieben der Position und Ändern der Seitengröße.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [BLINDH](#BLINDH) | Vertikale Jalousien |
| [BLINDV](#BLINDV) | Vertikale Jalousien |
| [BTWIPE](#BTWIPE) | Von unten nach oben wischen |
| [DGLITTER](#DGLITTER) | Diagonales Glitzern |
| [DISSOLVE](#DISSOLVE) | Die alte Seite löst sich auf |
| [INBOX](#INBOX) | Einwärts-Box |
| [LRGLITTER](#LRGLITTER) | Links-rechts Glitzern |
| [LRWIPE](#LRWIPE) | Links-rechts Wischen |
| [OUTBOX](#OUTBOX) | Auswärts-Box |
| [RLWIPE](#RLWIPE) | Rechts-links Wischen |
| [SPLITHIN](#SPLITHIN) | IN Horizontaler Aufteilung |
| [SPLITHOUT](#SPLITHOUT) | Horizontaler Split nach außen |
| [SPLITVIN](#SPLITVIN) | Vertikaler Split nach innen |
| [SPLITVOUT](#SPLITVOUT) | Vertikaler Split nach außen |
| [TBGLITTER](#TBGLITTER) | Glitzer von oben nach unten |
| [TBWIPE](#TBWIPE) | Wisch von oben nach unten |

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [PdfPageEditor](#PdfPageEditor--) | Konstruktor für die Klasse PdfPageEditor. |
| [PdfPageEditor](#PdfPageEditor-com.aspose.pdf.Document-) | Konstruktor für die Klasse PdfPageEditor. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [applyChanges](#applyChanges--) | Änderungen, die an den Dokumentseiten vorgenommen wurden, anwenden. |
| [getAlignment](#getAlignment--) | Ermittelt die horizontale Ausrichtung des ursprünglichen PDF-Inhalts auf der Ergebnisseite, Standard ist **AlignmentType.Left**. Verwenden Sie stattdessen **getHorizontalAlignment**. |
| [getDisplayDuration](#getDisplayDuration--) | Ermittelt die Anzeigedauer für Seiten. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Ermittelt die horizontale Ausrichtung des ursprünglichen PDF-Inhalts auf der Ergebnisseite, Standard ist **AlignmentType.Left**. |
| [getPageBoxSize](#getPageBoxSize-int-java.lang.String-) | <p> Gibt die Größe des angegebenen Kastens im Dokument zurück. </p> <hr> <pre> The following example demonstrates how to get media box of the 1st page: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); Rectangle rect = editor.getBoxSize(1, "media"); </pre> |
| [getPageRectangle](#getPageRectangle-com.aspose.pdf.Page-) | Gibt die Seitengröße der Seite zurück. |
| [getPageRotation](#getPageRotation-int-) | <p> Gibt die Drehung der angegebenen Seite zurück. </p> <hr> <pre> The following example demonstrates how to get page rotation: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); int rotation = editor.getPageSize(1); System.out.println("Rotation of 1st page : " + rotation + " degrees"); </pre> |
| [getPageRotations](#getPageRotations--) | <p> Ermittelt die Drehung der Seiten, eine Hashtable enthält die Seitennummer und den Drehwinkel, der Schlüssel steht für die Seitennummer, der Wert des Schlüssels steht für die Drehung in Grad. </p> |
| [getPages](#getPages--) | <p> Gibt die Gesamtzahl der Seiten zurück. </p> <hr> <pre> The following example demonstrates using of GetPages() method: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); System.out.println("Document has: " + editor.GetPages()); </pre> |
| [getPageSize](#getPageSize--) | Ermittelt die Seitengröße der Ausgabedatei. |
| [getPageSize](#getPageSize-int-) | <p> Gibt die Seitengröße der angegebenen Seite zurück. </p> <hr> <pre> The following example demonstrates using of GetPageSize method: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); PageSize size = editor.getPageSize(1); System.out.println("Size of 1st page : " + size.getWidth() + " x " + size.getHeight()); </pre> |
| [getProcessPages](#getProcessPages--) | Ermittelt die zu bearbeitenden Seitennummern. Standardmäßig wird jede Seite bearbeitet. |
| [getRotation](#getRotation--) | Ermittelt die Drehung der Seiten, die Drehung muss 0, 90, 180 oder 270 sein. Standardwert ist 0. |
| [getTransitionDuration](#getTransitionDuration--) | Ermittelt die Dauer des Übergangseffekts. |
| [getTransitionType](#getTransitionType--) | Ermittelt den Übergangsstil, der beim Wechsel zu dieser Seite von einer anderen während einer Präsentation verwendet wird. |
| [getVerticalAlignment](#getVerticalAlignment--) | Ermittelt die vertikale Ausrichtung des ursprünglichen PDF-Inhalts auf der Ergebnisseite, Standard ist **VerticalAlignmentType.Bottom**. Verwenden Sie stattdessen **getVerticalAlignmentType**. |
| [getVerticalAlignmentType](#getVerticalAlignmentType--) | Ermittelt die vertikale Ausrichtung des ursprünglichen PDF-Inhalts auf der Ergebnisseite, Standard ist **VerticalAlignmentType.Bottom**. |
| [getZoom](#getZoom--) | Erhalte den Zoomkoeffizienten. Wert 1.0 entspricht 100%. Standardwert ist 1.0. |
| [isBoxDefined](#isBoxDefined-com.aspose.pdf.Page-java.lang.String-) | Prüfen, ob das Feld auf der Seite definiert ist. |
| [movePosition](#movePosition-float-float-) | <p> Verschiebt den Ursprung von (0, 0) zu dem angegebenen Punkt. Der Ursprung ist links unten und die Einheit ist Punkt(1 Zoll = 72 Punkte). </p> <hr> <pre> PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf(\"input.pdf\"); editor.movePosition(-100, 60); editor.save(\"moved.pdf\"); </pre> |
| [save](#save-java.io.OutputStream-) | <p> Speichert das geänderte Dokument in einen Stream. </p> <hr> <pre> Das folgende Beispiel zeigt, wie man ein geändertes PDF-Dokument in einen Stream speichert. PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf(\"sample.pdf\"); editor.setZoom ( 0.5f); editor.save(\"newdocument.pdf\"); </pre> |
| [save](#save-java.lang.String-) | <p> Speichert das geänderte Dokument in eine Datei. </p> <hr> <pre> Das folgende Beispiel zeigt, wie man ein geändertes PDF-Dokument speichert. PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf(\"sample.pdf\"); editor.setZoom ( 0.5f); editor.save(\"newdocument.pdf\"); </pre> |
| [setAlignment](#setAlignment-com.aspose.pdf.facades.AlignmentType-) | Legt die horizontale Ausrichtung des ursprünglichen PDF-Inhalts auf der Ergebnisseite fest, standardmäßig ist AlignmentType.Left. Verwenden Sie stattdessen setHorizontalAlignment. |
| [setDisplayDuration](#setDisplayDuration-int-) | Legt die Anzeigedauer für Seiten fest. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Legt die horizontale Ausrichtung des ursprünglichen PDF-Inhalts auf der Ergebnisseite fest, standardmäßig ist AlignmentType.Left. |
| [setPageRotations](#setPageRotations-java.util.Map-) | Legt die Drehung der Seiten fest. Eine Hashtable enthält die Seitennummer und den Drehwinkel; der Schlüssel steht für die Seitennummer, der Wert des Schlüssels steht für die Drehung in Grad. |
| [setPageSize](#setPageSize-com.aspose.pdf.PageSize-) | Legt die Seitengröße der Ausgabedatei fest. |
| [setProcessPages](#setProcessPages-int:A-) | Legt die zu bearbeitenden Seitennummern fest. Standardmäßig wird jede Seite bearbeitet. |
| [setRotation](#setRotation-int-) | Legt die Drehung der Seiten fest, die Drehung muss 0, 90, 180 oder 270 sein. Standardwert ist 0. |
| [setTransitionDuration](#setTransitionDuration-int-) | Legt die Dauer des Übergangseffekts fest. |
| [setTransitionType](#setTransitionType-int-) | Legt den Übergangsstil fest, der beim Wechsel zu dieser Seite von einer anderen während einer Präsentation verwendet wird. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.facades.VerticalAlignmentType-) | Legt die vertikale Ausrichtung des ursprünglichen PDF-Inhalts auf der Ergebnisseite fest, standardmäßig ist VerticalAlignmentType.Bottom. Verwenden Sie stattdessen setVerticalAlignmentType. |
| [setVerticalAlignmentType](#setVerticalAlignmentType-com.aspose.pdf.VerticalAlignment-) | Legt die vertikale Ausrichtung des ursprünglichen PDF-Inhalts auf der Ergebnisseite fest, standardmäßig ist VerticalAlignmentType.Bottom. |
| [setZoom](#setZoom-float-) | <p> Legt den Zoomfaktor fest. Der Wert 1.0 entspricht 100%. Standardwert ist 1.0. </p> |

### BLINDH {#BLINDH}
```
public static final int BLINDH
```

Vertikale Jalousien

### BLINDV {#BLINDV}
```
public static final int BLINDV
```

Vertikale Jalousien

### BTWIPE {#BTWIPE}
```
public static final int BTWIPE
```

Von unten nach oben wischen

### DGLITTER {#DGLITTER}
```
public static final int DGLITTER
```

Diagonales Glitzern

### DISSOLVE {#DISSOLVE}
```
public static final int DISSOLVE
```

Die alte Seite löst sich auf

### INBOX {#INBOX}
```
public static final int INBOX
```

Einwärts-Box

### LRGLITTER {#LRGLITTER}
```
public static final int LRGLITTER
```

Links-rechts Glitzern

### LRWIPE {#LRWIPE}
```
public static final int LRWIPE
```

Links-rechts Wischen

### OUTBOX {#OUTBOX}
```
public static final int OUTBOX
```

Auswärts-Box

### RLWIPE {#RLWIPE}
```
public static final int RLWIPE
```

Rechts-links Wischen

### SPLITHIN {#SPLITHIN}
```
public static final int SPLITHIN
```

IN Horizontaler Aufteilung

### SPLITHOUT {#SPLITHOUT}
```
public static final int SPLITHOUT
```

Horizontaler Split nach außen

### SPLITVIN {#SPLITVIN}
```
public static final int SPLITVIN
```

Vertikaler Split nach innen

### SPLITVOUT {#SPLITVOUT}
```
public static final int SPLITVOUT
```

Vertikaler Split nach außen

### TBGLITTER {#TBGLITTER}
```
public static final int TBGLITTER
```

Glitzer von oben nach unten

### TBWIPE {#TBWIPE}
```
public static final int TBWIPE
```

Wisch von oben nach unten

### PdfPageEditor {#PdfPageEditor--}
```
public PdfPageEditor()
```

Konstruktor für die Klasse PdfPageEditor.

### PdfPageEditor {#PdfPageEditor-com.aspose.pdf.Document-}
Konstruktor für die Klasse PdfPageEditor.

### applyChanges {#applyChanges--}
```
public void applyChanges()
```

Änderungen, die an den Dokumentseiten vorgenommen wurden, anwenden.

### getAlignment {#getAlignment--}
```
@Deprecated public AlignmentType getAlignment()
```

Ermittelt die horizontale Ausrichtung des ursprünglichen PDF-Inhalts auf der Ergebnisseite, Standard ist **AlignmentType.Left**. Verwenden Sie stattdessen **getHorizontalAlignment**.

**Returns:**
AlignmentType-Objekt @see HorizontalAlignment

### getDisplayDuration {#getDisplayDuration--}
```
public int getDisplayDuration()
```

Ermittelt die Anzeigedauer für Seiten.

**Returns:**
int-Wert

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Ermittelt die horizontale Ausrichtung des ursprünglichen PDF-Inhalts auf der Ergebnisseite, Standard ist **AlignmentType.Left**.

**Returns:**
HorizontalAlignment‑Element @see HorizontalAlignment

### getPageBoxSize {#getPageBoxSize-int-java.lang.String-}
<p> Gibt die Größe des angegebenen Kastens im Dokument zurück. </p> <hr> <pre> The following example demonstrates how to get media box of the 1st page: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); Rectangle rect = editor.getBoxSize(1, "media"); </pre>

### getPageRectangle {#getPageRectangle-com.aspose.pdf.Page-}
Gibt die Seitengröße der Seite zurück.

### getPageRotation {#getPageRotation-int-}
```
public int getPageRotation(int page)
```

<p> Gibt die Drehung der angegebenen Seite zurück. </p> <hr> <pre> The following example demonstrates how to get page rotation: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); int rotation = editor.getPageSize(1); System.out.println("Rotation of 1st page : " + rotation + " degrees"); </pre>

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Seite |  | Seitenindex. Dokumentseiten werden ab 1 nummeriert. |

**Returns:**
Seitendrehung in Grad.

### getPageRotations {#getPageRotations--}
```
public Map < Integer , Integer > getPageRotations()
```

<p> Ermittelt die Drehung der Seiten, eine Hashtable enthält die Seitennummer und den Drehwinkel, der Schlüssel steht für die Seitennummer, der Wert des Schlüssels steht für die Drehung in Grad. </p>

**Returns:**
{@code Map<Integer, Integer>}-Objekt

### getPages {#getPages--}
```
public int getPages()
```

<p> Gibt die Gesamtzahl der Seiten zurück. </p> <hr> <pre> The following example demonstrates using of GetPages() method: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); System.out.println("Document has: " + editor.GetPages()); </pre>

**Returns:**
Anzahl der Seiten.

### getPageSize {#getPageSize--}
```
public PageSize getPageSize()
```

Ermittelt die Seitengröße der Ausgabedatei.

**Returns:**
PageSize-Objekt

### getPageSize {#getPageSize-int-}
```
public PageSize getPageSize(int page)
```

<p> Gibt die Seitengröße der angegebenen Seite zurück. </p> <hr> <pre> The following example demonstrates using of GetPageSize method: PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); PageSize size = editor.getPageSize(1); System.out.println("Size of 1st page : " + size.getWidth() + " x " + size.getHeight()); </pre>

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Seite |  | Seitenindex. Dokumentseiten werden ab 1 nummeriert. |

**Returns:**
Das Ergebnis ist eine Instanz von PageSize. Verwenden Sie die Eigenschaften Width und Height des zurückgegebenen Objekts, um Seitenbreite und -höhe zu erhalten.

### getProcessPages {#getProcessPages--}
```
public int[] getProcessPages()
```

Ermittelt die zu bearbeitenden Seitennummern. Standardmäßig wird jede Seite bearbeitet.

**Returns:**
Array von int-Werten

### getRotation {#getRotation--}
```
public int getRotation()
```

Ermittelt die Drehung der Seiten, die Drehung muss 0, 90, 180 oder 270 sein. Standardwert ist 0.

**Returns:**
int-Wert

### getTransitionDuration {#getTransitionDuration--}
```
public int getTransitionDuration()
```

Ermittelt die Dauer des Übergangseffekts.

**Returns:**
int-Wert

### getTransitionType {#getTransitionType--}
```
public int getTransitionType()
```

Ermittelt den Übergangsstil, der beim Wechsel zu dieser Seite von einer anderen während einer Präsentation verwendet wird.

**Returns:**
int-Wert

### getVerticalAlignment {#getVerticalAlignment--}
```
@Deprecated public VerticalAlignmentType getVerticalAlignment()
```

Ermittelt die vertikale Ausrichtung des ursprünglichen PDF-Inhalts auf der Ergebnisseite, Standard ist **VerticalAlignmentType.Bottom**. Verwenden Sie stattdessen **getVerticalAlignmentType**.

**Returns:**
VerticalAlignmentType-Objekt

### getVerticalAlignmentType {#getVerticalAlignmentType--}
```
public VerticalAlignment getVerticalAlignmentType()
```

Ermittelt die vertikale Ausrichtung des ursprünglichen PDF-Inhalts auf der Ergebnisseite, Standard ist **VerticalAlignmentType.Bottom**.

**Returns:**
VerticalAlignmentType-Element @see VerticalAlignmentType

### getZoom {#getZoom--}
```
public float getZoom()
```

Erhalte den Zoomkoeffizienten. Wert 1.0 entspricht 100%. Standardwert ist 1.0.

**Returns:**
float-Wert

### isBoxDefined {#isBoxDefined-com.aspose.pdf.Page-java.lang.String-}
Prüfen, ob das Feld auf der Seite definiert ist.

### movePosition {#movePosition-float-float-}
```
public void movePosition(float moveX, float moveY)
```

<p> Verschiebt den Ursprung von (0, 0) zu dem angegebenen Punkt. Der Ursprung ist links unten und die Einheit ist Punkt(1 Zoll = 72 Punkte). </p> <hr> <pre> PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf(\"input.pdf\"); editor.movePosition(-100, 60); editor.save(\"moved.pdf\"); </pre>

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| moveX |  | X-Koordinate. |
| moveY |  | Y-Koordinate. |

### save {#save-java.io.OutputStream-}
<p> Speichert das geänderte Dokument in einen Stream. </p> <hr> <pre> Das folgende Beispiel zeigt, wie man ein geändertes PDF-Dokument in einen Stream speichert. PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf(\"sample.pdf\"); editor.setZoom ( 0.5f); editor.save(\"newdocument.pdf\"); </pre>

### save {#save-java.lang.String-}
<p> Speichert das geänderte Dokument in eine Datei. </p> <hr> <pre> Das folgende Beispiel zeigt, wie man ein geändertes PDF-Dokument speichert. PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf(\"sample.pdf\"); editor.setZoom ( 0.5f); editor.save(\"newdocument.pdf\"); </pre>

### setAlignment {#setAlignment-com.aspose.pdf.facades.AlignmentType-}
Legt die horizontale Ausrichtung des ursprünglichen PDF-Inhalts auf der Ergebnisseite fest, standardmäßig ist AlignmentType.Left. Verwenden Sie stattdessen setHorizontalAlignment.

### setDisplayDuration {#setDisplayDuration-int-}
```
public void setDisplayDuration(int value)
```

Legt die Anzeigedauer für Seiten fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Legt die horizontale Ausrichtung des ursprünglichen PDF-Inhalts auf der Ergebnisseite fest, standardmäßig ist AlignmentType.Left.

### setPageRotations {#setPageRotations-java.util.Map-}
Legt die Drehung der Seiten fest. Eine Hashtable enthält die Seitennummer und den Drehwinkel; der Schlüssel steht für die Seitennummer, der Wert des Schlüssels steht für die Drehung in Grad.

### setPageSize {#setPageSize-com.aspose.pdf.PageSize-}
Legt die Seitengröße der Ausgabedatei fest.

### setProcessPages {#setProcessPages-int:A-}
```
public void setProcessPages(int[] value)
```

Legt die zu bearbeitenden Seitennummern fest. Standardmäßig wird jede Seite bearbeitet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Array von int-Werten |

### setRotation {#setRotation-int-}
```
public void setRotation(int value)
```

Legt die Drehung der Seiten fest, die Drehung muss 0, 90, 180 oder 270 sein. Standardwert ist 0.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setTransitionDuration {#setTransitionDuration-int-}
```
public void setTransitionDuration(int value)
```

Legt die Dauer des Übergangseffekts fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setTransitionType {#setTransitionType-int-}
```
public void setTransitionType(int value)
```

Legt den Übergangsstil fest, der beim Wechsel zu dieser Seite von einer anderen während einer Präsentation verwendet wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.facades.VerticalAlignmentType-}
Legt die vertikale Ausrichtung des ursprünglichen PDF-Inhalts auf der Ergebnisseite fest, standardmäßig ist VerticalAlignmentType.Bottom. Verwenden Sie stattdessen setVerticalAlignmentType.

### setVerticalAlignmentType {#setVerticalAlignmentType-com.aspose.pdf.VerticalAlignment-}
Legt die vertikale Ausrichtung des ursprünglichen PDF-Inhalts auf der Ergebnisseite fest, standardmäßig ist VerticalAlignmentType.Bottom.

### setZoom {#setZoom-float-}
```
public void setZoom(float value)
```

<p> Legt den Zoomfaktor fest. Der Wert 1.0 entspricht 100%. Standardwert ist 1.0. </p>

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | float-Wert <hr> <pre> Das folgende Beispiel zeigt, wie man den Zoom der Dokumentseiten ändert. PdfPageEditor editor = new PdfPageEditor(); editor.bindPdf("sample.pdf"); editor.setZoom ( 0.5f); </pre> |
