---
title: "Artefakt"
linktitle: "Artefakt"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse stellt ein PDF-Artifact-Objekt dar."
type: docs
weight: 190
url: /de/java/com.aspose.pdf/artifact/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Artifact

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public class Artifact extends Object implements com.aspose.ms.System.IDisposable, Closeable
```

Klasse stellt ein PDF-Artifact-Objekt dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Artifact](#Artifact-com.aspose.pdf.Artifact.ArtifactType-com.aspose.pdf.Artifact.ArtifactSubtype-) | Konstruktor des Artefakts mit angegebenem Typ und Subtyp |
| [Artifact](#Artifact-com.aspose.pdf.ArtifactCollection-com.aspose.pdf.Artifact.ArtifactContext-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.engine.data.IPdfDictionary-) | Dieser Konstruktor wird verwendet, wenn das Artefakt von der Seite gelesen wird. |
| [Artifact](#Artifact-java.lang.String-java.lang.String-) | Konstruktor des Artefakts mit angegebenem Typ und Subtyp |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [beginUpdates](#beginUpdates--) | Starten Sie gelöschte Updates. Verwenden Sie diese Funktion, wenn Sie mehrere Änderungen am selben Artefakt vornehmen müssen, um die Leistung zu verbessern. Normalerweise werden Artefakt‑Operatoren jedes Mal geändert, wenn eine Artefakt‑Eigenschaft geändert wurde. Dies führt dazu, dass der Seiteninhalt jedes Mal geändert wird, wenn das Artefakt geändert wurde. Um diesen Effekt zu vermeiden, setzen Sie alle Artefakt‑Updates zwischen Aufrufe von StartUpdates/SaveUpdates. Dadurch wird der Seiteninhalt nur einmal geändert. Artifact art = doc.getPages().get_Item(1).getArtifacts().get_Item(1); art.beginUpdates(); art.setOpacity ( 0.3f); art.setPosition ( new Point(10,10)); art.setRotation (30); art.saveUpdates(); |
| [close](#close--) | Schließt alle von diesem Dokument verwendeten Ressourcen. |
| [dispose](#dispose--) | Entfernt das Artefakt. Diese Methode ist veraltet, verwenden Sie stattdessen close(). |
| [getArtifactHorizontalAlignment](#getArtifactHorizontalAlignment--) | Liefert die horizontale Ausrichtung des Artefakts. Wenn die Position explizit angegeben ist (in der Eigenschaft Position), wird dieser Wert ignoriert. |
| [getArtifactVerticalAlignment](#getArtifactVerticalAlignment--) | Liefert die vertikale Ausrichtung des Artefakts. Wenn die Position explizit angegeben ist (in der Eigenschaft Position), wird dieser Wert ignoriert. |
| [getBottomMargin](#getBottomMargin--) | Liefert den unteren Rand des Artefakts. Wenn die Position explizit angegeben ist (in der Eigenschaft Position), wird dieser Wert ignoriert. |
| [getContents](#getContents--) | Liefert die Sammlung interner Operatoren des Artefakts. |
| [getCustomSubtype](#getCustomSubtype--) | Liefert den Namen des Artefakt‑Subtyps. Kann verwendet werden, wenn der Artefakt‑Subtyp kein Standard‑Subtyp ist. |
| [getCustomType](#getCustomType--) | Liefert den Namen des Artefakt‑Typs. Kann verwendet werden, wenn der Artefakt‑Typ nicht standardmäßig ist. |
| [getForm](#getForm--) | Liefert das XForm des Artefakts (falls XForm verwendet wird). |
| [getImage](#getImage--) | Liefert das Bild des Artefakts (falls vorhanden). |
| [getLeftMargin](#getLeftMargin--) | Liefert den linken Rand des Artefakts. Wenn die Position explizit angegeben ist (in der Eigenschaft Position), wird dieser Wert ignoriert. |
| [getLines](#getLines--) | Zeilen des mehrzeiligen Text‑Artefakts. |
| [getOpacity](#getOpacity--) | Liefert die Deckkraft des Artefakts. Mögliche Werte liegen im Bereich 0..1. |
| [getPosition](#getPosition--) | Liefert die Position des Artefakts. Wenn diese Eigenschaft angegeben ist, werden Rand und Ausrichtungen ignoriert. |
| [getRectangle](#getRectangle--) | Liefert das Rechteck des Artefakts. |
| [getRightMargin](#getRightMargin--) | Liefert den rechten Rand des Artefakts. Wenn die Position explizit angegeben ist (in der Eigenschaft Position), wird dieser Wert ignoriert. |
| [getRotation](#getRotation--) | Liest den Rotationswinkel des Artefakts. |
| [getSubtype](#getSubtype--) | Liest den Subtyp des Artefakts. Wenn das Artefakt einen nicht‑standardmäßigen Subtyp hat, kann der Name des Subtyps über CustomSubtype gelesen werden. |
| [getText](#getText--) | Liest den Text des Artefakts. |
| [getTextState](#getTextState--) | Textstatus für den Artefakt‑Text. |
| [getTopMargin](#getTopMargin--) | Liest den oberen Rand des Artefakts. Wenn die Position explizit angegeben ist (in der Eigenschaft Position), wird dieser Wert ignoriert. |
| [getType](#getType--) | Liest den Typ des Artefakts. |
| [getValue](#getValue-java.lang.String-) | Liest den benutzerdefinierten Wert des Artefakts. |
| [isBackground](#isBackground--) | Wenn true, wird das Artefakt hinter dem Seiteninhalt platziert. |
| [removeValue](#removeValue-java.lang.String-) | Entfernt den benutzerdefinierten Wert aus dem Artefakt. |
| [saveUpdates](#saveUpdates--) | Speichert alle Aktualisierungen im Artefakt, die nach dem Aufruf von BeginUpdates() vorgenommen wurden. |
| [setArtifactHorizontalAlignment](#setArtifactHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Liest die horizontale Ausrichtung des Artefakts. |
| [setArtifactVerticalAlignment](#setArtifactVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Setzt die vertikale Ausrichtung des Artefakts. |
| [setBackground](#setBackground-boolean-) | Wenn true, wird das Artefakt hinter dem Seiteninhalt platziert. |
| [setBottomMargin](#setBottomMargin-double-) | Setzt den unteren Rand des Artefakts. |
| [setCustomSubtype](#setCustomSubtype-java.lang.String-) |  |
| [setCustomType](#setCustomType-java.lang.String-) | Setzt den Namen des Artefakt‑Typs. Kann verwendet werden, wenn der Artefakt‑Typ nicht standardmäßig ist. |
| [setImage](#setImage-java.io.InputStream-) | Setzt das Bild des Artefakts. |
| [setImage](#setImage-java.lang.String-) | Setzt das Bild des Artefakts. |
| [setLeftMargin](#setLeftMargin-double-) | Setzt den linken Rand des Artefakts. Wenn die Position explizit angegeben ist (in der Eigenschaft Position), wird dieser Wert ignoriert. |
| [setLinesAndState](#setLinesAndState-java.lang.String:A-com.aspose.pdf.TextState-) | Setzt den Text und die Texteigenschaften des Artefakts. Ermöglicht die Angabe mehrerer Zeilen. |
| [setOpacity](#setOpacity-double-) | Setzt die Deckkraft des Artefakts. Mögliche Werte liegen im Bereich 0..1. |
| [setPageNumberReplacementString](#setPageNumberReplacementString-java.lang.String-) | Legt fest, welche Zeichenkette durch die Seitenzahl ersetzt wird. Der Standardwert ist #. |
| [setPdfPage](#setPdfPage-com.aspose.pdf.Page-) | Setzt die PDF‑Seite, die als Artefakt auf der Dokumentseite platziert wird. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Setzt die Position des Artefakts. |
| [setRightMargin](#setRightMargin-double-) | Setzt den rechten Rand des Artefakts. |
| [setRotation](#setRotation-double-) | Setzt den Rotationswinkel des Artefakts. |
| [setSubtype](#setSubtype-com.aspose.pdf.Artifact.ArtifactSubtype-) | Setzt den Subtyp des Artefakts. |
| [setText](#setText-com.aspose.pdf.facades.FormattedText-) | Setzt den Text des Artefakts. |
| [setText](#setText-java.lang.String-) | Setzt den Text des Artefakts. |
| [setTextAndState](#setTextAndState-java.lang.String-com.aspose.pdf.TextState-) | Text und Texteigenschaften des Artefakts festlegen. |
| [setTextState](#setTextState-com.aspose.pdf.TextState-) | Textstatus für den Artefakt‑Text. |
| [setTopMargin](#setTopMargin-double-) | Setzt den oberen Rand des Artefakts. |
| [setType](#setType-com.aspose.pdf.Artifact.ArtifactType-) | Setzt den Artefakttyp. |
| [setValue](#setValue-java.lang.String-java.lang.String-) | Setzt den benutzerdefinierten Wert des Artefakts. |

### Artifact {#Artifact-com.aspose.pdf.Artifact.ArtifactType-com.aspose.pdf.Artifact.ArtifactSubtype-}
Konstruktor des Artefakts mit angegebenem Typ und Subtyp

### Artifact {#Artifact-com.aspose.pdf.ArtifactCollection-com.aspose.pdf.Artifact.ArtifactContext-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.engine.data.IPdfDictionary-}
Dieser Konstruktor wird verwendet, wenn das Artefakt von der Seite gelesen wird.

### Artifact {#Artifact-java.lang.String-java.lang.String-}
Konstruktor des Artefakts mit angegebenem Typ und Subtyp

### beginUpdates {#beginUpdates--}
```
public void beginUpdates()
```

Starten Sie gelöschte Updates. Verwenden Sie diese Funktion, wenn Sie mehrere Änderungen am selben Artefakt vornehmen müssen, um die Leistung zu verbessern. Normalerweise werden Artefakt‑Operatoren jedes Mal geändert, wenn eine Artefakt‑Eigenschaft geändert wurde. Dies führt dazu, dass der Seiteninhalt jedes Mal geändert wird, wenn das Artefakt geändert wurde. Um diesen Effekt zu vermeiden, setzen Sie alle Artefakt‑Updates zwischen Aufrufe von StartUpdates/SaveUpdates. Dadurch wird der Seiteninhalt nur einmal geändert. Artifact art = doc.getPages().get_Item(1).getArtifacts().get_Item(1); art.beginUpdates(); art.setOpacity ( 0.3f); art.setPosition ( new Point(10,10)); art.setRotation (30); art.saveUpdates();

### close {#close--}
```
public void close()
```

Schließt alle von diesem Dokument verwendeten Ressourcen.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Entfernt das Artefakt. Diese Methode ist veraltet, verwenden Sie stattdessen close().

### getArtifactHorizontalAlignment {#getArtifactHorizontalAlignment--}
```
public HorizontalAlignment getArtifactHorizontalAlignment()
```

Liefert die horizontale Ausrichtung des Artefakts. Wenn die Position explizit angegeben ist (in der Eigenschaft Position), wird dieser Wert ignoriert.

**Returns:**
HorizontalAlignment-Wert @see HorizontalAlignment

### getArtifactVerticalAlignment {#getArtifactVerticalAlignment--}
```
public VerticalAlignment getArtifactVerticalAlignment()
```

Liefert die vertikale Ausrichtung des Artefakts. Wenn die Position explizit angegeben ist (in der Eigenschaft Position), wird dieser Wert ignoriert.

**Returns:**
VerticalAlignment-Wert. @see VerticalAlignment

### getBottomMargin {#getBottomMargin--}
```
public double getBottomMargin()
```

Liefert den unteren Rand des Artefakts. Wenn die Position explizit angegeben ist (in der Eigenschaft Position), wird dieser Wert ignoriert.

**Returns:**
unterer Rand.

### getContents {#getContents--}
```
public List < Operator > getContents()
```

Liefert die Sammlung interner Operatoren des Artefakts.

**Returns:**
listet interne Operatoren des Artefakts auf.

### getCustomSubtype {#getCustomSubtype--}
```
public String getCustomSubtype()
```

Liefert den Namen des Artefakt‑Subtyps. Kann verwendet werden, wenn der Artefakt‑Subtyp kein Standard‑Subtyp ist.

**Returns:**
String Wert

### getCustomType {#getCustomType--}
```
public String getCustomType()
```

Liefert den Namen des Artefakt‑Typs. Kann verwendet werden, wenn der Artefakt‑Typ nicht standardmäßig ist.

**Returns:**
String Artefaktname

### getForm {#getForm--}
```
public XForm getForm()
```

Liefert das XForm des Artefakts (falls XForm verwendet wird).

**Returns:**
XForm-Objekt

### getImage {#getImage--}
```
public XImage getImage()
```

Liefert das Bild des Artefakts (falls vorhanden).

**Returns:**
XImage-Objekt

### getLeftMargin {#getLeftMargin--}
```
public double getLeftMargin()
```

Liefert den linken Rand des Artefakts. Wenn die Position explizit angegeben ist (in der Eigenschaft Position), wird dieser Wert ignoriert.

**Returns:**
linker Rand des Artefakts.

### getLines {#getLines--}
```
public final List < String > getLines()
```

Zeilen des mehrzeiligen Text‑Artefakts.

**Returns:**
Liste von Strings

### getOpacity {#getOpacity--}
```
public double getOpacity()
```

Liefert die Deckkraft des Artefakts. Mögliche Werte liegen im Bereich 0..1.

**Returns:**
Deckkraft des Artefakts.

### getPosition {#getPosition--}
```
public Point getPosition()
```

Liefert die Position des Artefakts. Wenn diese Eigenschaft angegeben ist, werden Rand und Ausrichtungen ignoriert.

**Returns:**
Artefaktposition.

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Liefert das Rechteck des Artefakts.

**Returns:**
Rectangle-Objekt

### getRightMargin {#getRightMargin--}
```
public double getRightMargin()
```

Liefert den rechten Rand des Artefakts. Wenn die Position explizit angegeben ist (in der Eigenschaft Position), wird dieser Wert ignoriert.

**Returns:**
rechter Rand des Artefakts.

### getRotation {#getRotation--}
```
public double getRotation()
```

Liest den Rotationswinkel des Artefakts.

**Returns:**
Artefaktdrehwinkel.

### getSubtype {#getSubtype--}
```
public Artifact.ArtifactSubtype getSubtype()
```

Liest den Subtyp des Artefakts. Wenn das Artefakt einen nicht‑standardmäßigen Subtyp hat, kann der Name des Subtyps über CustomSubtype gelesen werden.

**Returns:**
Artefaktuntertyp. @see ArtifactSubtype

### getText {#getText--}
```
public String getText()
```

Liest den Text des Artefakts.

**Returns:**
String Wert

### getTextState {#getTextState--}
```
public final TextState getTextState()
```

Textstatus für den Artefakt‑Text.

**Returns:**
TextState-Instanz

### getTopMargin {#getTopMargin--}
```
public double getTopMargin()
```

Liest den oberen Rand des Artefakts. Wenn die Position explizit angegeben ist (in der Eigenschaft Position), wird dieser Wert ignoriert.

**Returns:**
oberer Rand des Artefakts.

### getType {#getType--}
```
public Artifact.ArtifactType getType()
```

Liest den Typ des Artefakts.

**Returns:**
Artefakttypwert. @see ArtifactType

### getValue {#getValue-java.lang.String-}
Liest den benutzerdefinierten Wert des Artefakts.

### isBackground {#isBackground--}
```
public boolean isBackground()
```

Wenn true, wird das Artefakt hinter dem Seiteninhalt platziert.

**Returns:**
boolescher Wert

### removeValue {#removeValue-java.lang.String-}
Entfernt den benutzerdefinierten Wert aus dem Artefakt.

### saveUpdates {#saveUpdates--}
```
public void saveUpdates()
```

Speichert alle Aktualisierungen im Artefakt, die nach dem Aufruf von BeginUpdates() vorgenommen wurden.

### setArtifactHorizontalAlignment {#setArtifactHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Liest die horizontale Ausrichtung des Artefakts.

### setArtifactVerticalAlignment {#setArtifactVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Setzt die vertikale Ausrichtung des Artefakts.

### setBackground {#setBackground-boolean-}
```
public void setBackground(boolean value)
```

Wenn true, wird das Artefakt hinter dem Seiteninhalt platziert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setBottomMargin {#setBottomMargin-double-}
```
public void setBottomMargin(double value)
```

Setzt den unteren Rand des Artefakts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | unterer Rand. |

### setCustomSubtype {#setCustomSubtype-java.lang.String-}


### setCustomType {#setCustomType-java.lang.String-}
Setzt den Namen des Artefakt‑Typs. Kann verwendet werden, wenn der Artefakt‑Typ nicht standardmäßig ist.

### setImage {#setImage-java.io.InputStream-}
Setzt das Bild des Artefakts.

### setImage {#setImage-java.lang.String-}
Setzt das Bild des Artefakts.

### setLeftMargin {#setLeftMargin-double-}
```
public void setLeftMargin(double value)
```

Setzt den linken Rand des Artefakts. Wenn die Position explizit angegeben ist (in der Eigenschaft Position), wird dieser Wert ignoriert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | linker Rand des Artefakts. |

### setLinesAndState {#setLinesAndState-java.lang.String:A-com.aspose.pdf.TextState-}
Setzt den Text und die Texteigenschaften des Artefakts. Ermöglicht die Angabe mehrerer Zeilen.

### setOpacity {#setOpacity-double-}
```
public void setOpacity(double value)
```

Setzt die Deckkraft des Artefakts. Mögliche Werte liegen im Bereich 0..1.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Deckkraft des Artefakts. |

### setPageNumberReplacementString {#setPageNumberReplacementString-java.lang.String-}
Legt fest, welche Zeichenkette durch die Seitenzahl ersetzt wird. Der Standardwert ist #.

### setPdfPage {#setPdfPage-com.aspose.pdf.Page-}
Setzt die PDF‑Seite, die als Artefakt auf der Dokumentseite platziert wird.

### setPosition {#setPosition-com.aspose.pdf.Point-}
Setzt die Position des Artefakts.

### setRightMargin {#setRightMargin-double-}
```
public void setRightMargin(double value)
```

Setzt den rechten Rand des Artefakts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | rechter Rand des Artefakts. |

### setRotation {#setRotation-double-}
```
public void setRotation(double value)
```

Setzt den Rotationswinkel des Artefakts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Artefaktdrehwinkel. |

### setSubtype {#setSubtype-com.aspose.pdf.Artifact.ArtifactSubtype-}
Setzt den Subtyp des Artefakts.

### setText {#setText-com.aspose.pdf.facades.FormattedText-}
Setzt den Text des Artefakts.

### setText {#setText-java.lang.String-}
Setzt den Text des Artefakts.

### setTextAndState {#setTextAndState-java.lang.String-com.aspose.pdf.TextState-}
Text und Texteigenschaften des Artefakts festlegen.

### setTextState {#setTextState-com.aspose.pdf.TextState-}
Textstatus für den Artefakt‑Text.

### setTopMargin {#setTopMargin-double-}
```
public void setTopMargin(double value)
```

Setzt den oberen Rand des Artefakts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | oberer Rand des Artefakts. |

### setType {#setType-com.aspose.pdf.Artifact.ArtifactType-}
Setzt den Artefakttyp.

### setValue {#setValue-java.lang.String-java.lang.String-}
Setzt den benutzerdefinierten Wert des Artefakts.
