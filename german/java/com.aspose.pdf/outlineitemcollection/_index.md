---
title: "OutlineItemCollection"
linktitle: "OutlineItemCollection"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt einen Gliederungseintrag in der Gliederungshierarchie eines PDF-Dokuments dar."
type: docs
weight: 3270
url: /de/java/com.aspose.pdf/outlineitemcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Outlines com.aspose.pdf.OutlineItemCollection, com.aspose.pdf.Outlines, com.aspose.pdf.OutlineItemCollection

**All Implemented Interfaces:**
Iterable < OutlineItemCollection >

```
public final class OutlineItemCollection extends Outlines
```

Stellt einen Gliederungseintrag in der Gliederungshierarchie eines PDF-Dokuments dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [OutlineItemCollection](#OutlineItemCollection-com.aspose.pdf.engine.data.IPdfObject-) | Initialisiert eine neue Instanz dieser Klasse mithilfe des internen Engine-Outline-Eintragsobjekts. |
| [OutlineItemCollection](#OutlineItemCollection-com.aspose.pdf.OutlineCollection-) | Initialisiert die outline item-Instanz mithilfe des root hierarchy-Objekts. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [add](#add-com.aspose.pdf.OutlineItemCollection-) | Fügt ein Gliederungselement zur Sammlung hinzu. |
| [clear](#clear--) | Löscht alle Elemente aus der Sammlung. |
| [contains](#contains-com.aspose.pdf.OutlineItemCollection-) | Noch nicht unterstützt. Wirft immer NotImplementedException. |
| [copyTo](#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-) | Kopiert die Outline-Einträge in ein System.Array, beginnend an einem bestimmten System.Array-Index. |
| [delete](#delete--) | Löscht dieses Gliederungselement aus der Dokumenten‑Gliederungshierarchie. |
| [delete](#delete-java.lang.String-) | Löscht dieses Gliederungselement aus der Dokumenten‑Gliederungshierarchie. |
| [get_Item](#get_Item-int-) | Ruft das Gliederungselement aus der Sammlung anhand des Index ab. |
| [getAction](#getAction--) | Ruft die Aktion für dieses Gliederungselement ab. |
| [getBold](#getBold--) | Ruft das Fettdruck‑Flag für den Titeltext dieses Gliederungselements ab |
| [getColor](#getColor--) | Ruft die Farbe für den Titeltext dieses Gliederungselements ab. |
| [getDestination](#getDestination--) | Ruft das Ziel für dieses Gliederungselement ab. |
| [getEngineDict](#getEngineDict--) | Nur intern |
| [getEngineObj](#getEngineObj--) | Nur intern |
| [getFirst](#getFirst--) | Ruft das Gliederungselement ab, das das erste Element der obersten Ebene in der Gliederungshierarchie darstellt. |
| [getItalic](#getItalic--) | Ruft ein Kursiv‑Flag für den Titeltext dieses Gliederungselements ab |
| [getLast](#getLast--) | Ruft das Gliederungselement ab, das das letzte Element der obersten Ebene in der Gliederungshierarchie darstellt. |
| [getLevel](#getLevel--) | Ruft die Hierarchieebene des Gliederungselements ab. |
| [getNext](#getNext--) | Ruft das Gliederungselement ab, das das nächste Element relativ zu diesem Element in der Gliederungshierarchie darstellt. |
| [getOpen](#getOpen--) | Ruft den Öffnungsstatus (true/false) für das Gliederungselement ab. |
| [getParent](#getParent--) | Ruft das übergeordnete Objekt dieses Gliederungselements in der Gliederungshierarchie ab. |
| [getPrev](#getPrev--) | Ruft das Gliederungselement ab, das das vorherige Element relativ zu diesem Element in der Gliederungshierarchie darstellt. |
| [getSyncRoot](#getSyncRoot--) | Ruft das Objekt ab, das verwendet werden kann, um den Zugriff auf diese Sammlung zu synchronisieren. |
| [getTitle](#getTitle--) | Ruft den Titel für dieses Gliederungselement ab. |
| [getVisibleCount](#getVisibleCount--) | Ruft die Gesamtzahl der Gliederungselemente auf allen Ebenen in der Dokumenten‑Gliederungshierarchie ab. |
| [hasNext](#hasNext--) | Überprüft, ob das Gliederungselement das nächste Element relativ zu diesem Element in der Gliederungshierarchie darstellt. |
| [insert](#insert-int-com.aspose.pdf.OutlineItemCollection-) | Fügt das Gliederungselement in die Sammlung an der angegebenen Stelle ein. |
| [isReadOnly](#isReadOnly--) | Ermittelt einen Wert, der angibt, ob die Sammlung schreibgeschützt ist. |
| [isSynchronized](#isSynchronized--) | Ruft den Wert ab, der angibt, ob der Zugriff auf diese Sammlung synchronisiert (thread‑sicher) ist. |
| [iterator](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [next](#next--) |  |
| [remove](#remove-int-) | Entfernt ein Element nach Index. |
| [remove](#remove-com.aspose.pdf.OutlineItemCollection-) | Noch nicht unterstützt. Wirft immer NotImplementedException. |
| [setAction](#setAction-com.aspose.pdf.PdfAction-) | Setzt die Aktion für dieses Gliederungselement. |
| [setBold](#setBold-boolean-) | Setzt das Fettdruck‑Flag für den Titeltext dieses Gliederungselements |
| [setColor](#setColor-java.awt.Color-) | Setzt die Farbe für den Titeltext dieses Gliederungselements. |
| [setDestination](#setDestination-com.aspose.pdf.IAppointment-) | Setzt das Ziel für dieses Gliederungselement. |
| [setItalic](#setItalic-boolean-) | Setzt das Kursiv‑Flag für den Titeltext dieses Gliederungselements |
| [setOpen](#setOpen-boolean-) | Setzt den Öffnungsstatus (true/false) für das Outline-Element. |
| [setTitle](#setTitle-java.lang.String-) | Setzt den Titel für dieses Outline-Element. |
| [size](#size--) | Anzahl der Sammlungsobjekte. Bitte nicht mit VisibleCount verwechseln: VisibleCount gibt die Anzahl der sichtbaren Outline-Elemente auf allen Ebenen zurück. |

### OutlineItemCollection {#OutlineItemCollection-com.aspose.pdf.engine.data.IPdfObject-}
Initialisiert eine neue Instanz dieser Klasse mithilfe des internen Engine-Outline-Eintragsobjekts.

### OutlineItemCollection {#OutlineItemCollection-com.aspose.pdf.OutlineCollection-}
Initialisiert die outline item-Instanz mithilfe des root hierarchy-Objekts.

### add {#add-com.aspose.pdf.OutlineItemCollection-}
Fügt ein Gliederungselement zur Sammlung hinzu.

### clear {#clear--}
```
public void clear()
```

Löscht alle Elemente aus der Sammlung.

### contains {#contains-com.aspose.pdf.OutlineItemCollection-}
Noch nicht unterstützt. Wirft immer NotImplementedException.

### copyTo {#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-}
Kopiert die Outline-Einträge in ein System.Array, beginnend an einem bestimmten System.Array-Index.

### delete {#delete--}
```
public void delete()
```

Löscht dieses Gliederungselement aus der Dokumenten‑Gliederungshierarchie.

### delete {#delete-java.lang.String-}
Löscht dieses Gliederungselement aus der Dokumenten‑Gliederungshierarchie.

### get_Item {#get_Item-int-}
```
public OutlineItemCollection get_Item(int index)
```

Ruft das Gliederungselement aus der Sammlung anhand des Index ab.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index |  | Index innerhalb der Sammlung. |

**Returns:**
OutlineItemCollection-Objekt.

### getAction {#getAction--}
```
public PdfAction getAction()
```

Ruft die Aktion für dieses Gliederungselement ab.

**Returns:**
PdfAction-Wert

### getBold {#getBold--}
```
public boolean getBold()
```

Ruft das Fettdruck‑Flag für den Titeltext dieses Gliederungselements ab

**Returns:**
boolescher Wert

### getColor {#getColor--}
```
public Color getColor()
```

Ruft die Farbe für den Titeltext dieses Gliederungselements ab.

**Returns:**
Farbwert

### getDestination {#getDestination--}
```
public IAppointment getDestination()
```

Ruft das Ziel für dieses Gliederungselement ab.

**Returns:**
IAppointment‑Wert

### getEngineDict {#getEngineDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getEngineDict()
```

Nur intern

**Returns:**
IPdfDictionary-Objekt

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

Nur intern

**Returns:**
IPdfObject-Objekt

### getFirst {#getFirst--}
```
public OutlineItemCollection getFirst()
```

Ruft das Gliederungselement ab, das das erste Element der obersten Ebene in der Gliederungshierarchie darstellt.

**Returns:**
OutlineItemCollection-Wert

### getItalic {#getItalic--}
```
public boolean getItalic()
```

Ruft ein Kursiv‑Flag für den Titeltext dieses Gliederungselements ab

**Returns:**
boolescher Wert

### getLast {#getLast--}
```
public OutlineItemCollection getLast()
```

Ruft das Gliederungselement ab, das das letzte Element der obersten Ebene in der Gliederungshierarchie darstellt.

**Returns:**
OutlineItemCollection-Wert

### getLevel {#getLevel--}
```
public int getLevel()
```

Ruft die Hierarchieebene des Gliederungselements ab.

**Returns:**
int-Wert

### getNext {#getNext--}
```
public OutlineItemCollection getNext()
```

Ruft das Gliederungselement ab, das das nächste Element relativ zu diesem Element in der Gliederungshierarchie darstellt.

**Returns:**
OutlineItemCollection-Wert

### getOpen {#getOpen--}
```
public boolean getOpen()
```

Ruft den Öffnungsstatus (true/false) für das Gliederungselement ab.

**Returns:**
boolescher Wert

### getParent {#getParent--}
```
public Outlines getParent()
```

Ruft das übergeordnete Objekt dieses Gliederungselements in der Gliederungshierarchie ab.

**Returns:**
Objektwert

### getPrev {#getPrev--}
```
public OutlineItemCollection getPrev()
```

Ruft das Gliederungselement ab, das das vorherige Element relativ zu diesem Element in der Gliederungshierarchie darstellt.

**Returns:**
OutlineItemCollection-Wert

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Ruft das Objekt ab, das verwendet werden kann, um den Zugriff auf diese Sammlung zu synchronisieren.

**Returns:**
Objektwert

### getTitle {#getTitle--}
```
public String getTitle()
```

Ruft den Titel für dieses Gliederungselement ab.

**Returns:**
String Wert

### getVisibleCount {#getVisibleCount--}
```
public int getVisibleCount()
```

Ruft die Gesamtzahl der Gliederungselemente auf allen Ebenen in der Dokumenten‑Gliederungshierarchie ab.

**Returns:**
int-Wert

### hasNext {#hasNext--}
```
public final boolean hasNext()
```

Überprüft, ob das Gliederungselement das nächste Element relativ zu diesem Element in der Gliederungshierarchie darstellt.

**Returns:**
boolescher Wert

### insert {#insert-int-com.aspose.pdf.OutlineItemCollection-}
Fügt das Gliederungselement in die Sammlung an der angegebenen Stelle ein.

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Ermittelt einen Wert, der angibt, ob die Sammlung schreibgeschützt ist.

**Returns:**
boolescher Wert

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Ruft den Wert ab, der angibt, ob der Zugriff auf diese Sammlung synchronisiert (thread‑sicher) ist.

**Returns:**
boolescher Wert

### iterator {#iterator--}
```
public Iterator < OutlineItemCollection > iterator()
```

Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Returns:**
Ein System.Collections.IEnumerator-Objekt, das verwendet werden kann, um die Sammlung zu durchlaufen.

### next {#next--}
```
public OutlineItemCollection next()
```



### remove {#remove-int-}
```
public final void remove(int index)
```

Entfernt ein Element nach Index.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index |  | Index des zu löschenden Elements. |

### remove {#remove-com.aspose.pdf.OutlineItemCollection-}
Noch nicht unterstützt. Wirft immer NotImplementedException.

### setAction {#setAction-com.aspose.pdf.PdfAction-}
Setzt die Aktion für dieses Gliederungselement.

### setBold {#setBold-boolean-}
```
public void setBold(boolean value)
```

Setzt das Fettdruck‑Flag für den Titeltext dieses Gliederungselements

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setColor {#setColor-java.awt.Color-}
Setzt die Farbe für den Titeltext dieses Gliederungselements.

### setDestination {#setDestination-com.aspose.pdf.IAppointment-}
Setzt das Ziel für dieses Gliederungselement.

### setItalic {#setItalic-boolean-}
```
public void setItalic(boolean value)
```

Setzt das Kursiv‑Flag für den Titeltext dieses Gliederungselements

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

Setzt den Öffnungsstatus (true/false) für das Outline-Element.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setTitle {#setTitle-java.lang.String-}
Setzt den Titel für dieses Outline-Element.

### size {#size--}
```
public int size()
```

Anzahl der Sammlungsobjekte. Bitte nicht mit VisibleCount verwechseln: VisibleCount gibt die Anzahl der sichtbaren Outline-Elemente auf allen Ebenen zurück.

**Returns:**
int-Wert
