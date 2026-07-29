---
title: "Lesezeichen"
linktitle: "Lesezeichen"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt ein Lesezeichen dar."
type: docs
weight: 60
url: /de/java/com.aspose.pdf.facades/bookmark/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Bookmark

```
public final class Bookmark extends Object
```

Stellt ein Lesezeichen dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Bookmark](#Bookmark--) | Initialisiert eine neue Instanz der {@code Bookmark}-Klasse. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAction](#getAction--) | Liest die mit dem Lesezeichen verknüpfte Aktion. Wenn PageNumber angegeben ist, kann die Aktion nicht spezifiziert werden. Der Aktionstyp umfasst: "GoTo", "GoToR", "Launch", "Named". |
| [getBoldFlag](#getBoldFlag--) | Liest das Fettdruck-Flag des Titels des Lesezeichens. |
| [getChildItem](#getChildItem--) | Liest die Unterelemente des Lesezeichens. Veraltet("Use getChildItems() property instead of this one.") |
| [getChildItems](#getChildItems--) | Liest die Unterelemente des Lesezeichens. |
| [getCustomAcorbatViewerMenuActionName](#getCustomAcorbatViewerMenuActionName--) | Noch nicht unterstützt. Der Aktionsname, der dem Ausführen eines Menüeintrags im Acrobat-Viewer entspricht. |
| [getDestination](#getDestination--) | Liest die Zielseite des Lesezeichens. Erforderlich, wenn die Aktion als "" festgelegt ist. |
| [getItalicFlag](#getItalicFlag--) | Liest das Kursiv-Flag des Titels des Lesezeichens. |
| [getLevel](#getLevel--) | Ermittelt die Hierarchieebene des Lesezeichens. |
| [getPageDisplay_Bottom](#getPageDisplay_Bottom--) | Ermittelt die untere Koordinate der Seitenanzeige. |
| [getPageDisplay_Left](#getPageDisplay_Left--) | Ermittelt die linke Koordinate der Seitenanzeige. |
| [getPageDisplay_Right](#getPageDisplay_Right--) | Ermittelt die rechte Koordinate der Seitenanzeige. |
| [getPageDisplay_Top](#getPageDisplay_Top--) | Ermittelt die obere Koordinate der Seitenanzeige. |
| [getPageDisplay_Zoom](#getPageDisplay_Zoom--) | Ermittelt den Zoomfaktor der Seitenanzeige. |
| [getPageDisplay](#getPageDisplay--) | Ermittelt den Typ der Anzeigeseite des Lesezeichenziels. |
| [getPageNumber](#getPageNumber--) | Ermittelt die Nummer der Lesezeichen‑Zielseite. |
| [getRemoteFile](#getRemoteFile--) | Ermittelt die Datei (Pfad), die für die \"GoToR\"‑Aktion des Lesezeichens erforderlich ist. |
| [getTitle](#getTitle--) | Ermittelt den Titel des Lesezeichens. |
| [getTitleColor](#getTitleColor--) | Ermittelt die Farbe des Lesezeichentitels. |
| [isOpen](#isOpen--) | Ermittelt den Zustand des Lesezeichens (offen, geschlossen). |
| [setAction](#setAction-java.lang.String-) | Legt die mit dem Lesezeichen verbundene Aktion fest. Wenn PageNumber angegeben ist, kann die Aktion nicht spezifiziert werden. Der Aktionstyp umfasst: \"GoTo\", \"GoToR\", \"Launch\", \"Named\". |
| [setBoldFlag](#setBoldFlag-boolean-) | Legt das Fettdruck‑Flag des Lesezeichentitels fest. |
| [setChildItem](#setChildItem-com.aspose.pdf.facades.Bookmarks-) | Legt die Unterelemente des Lesezeichens fest. Obsolete(\"Use setChildItems() property instead of this one.\") |
| [setChildItems](#setChildItems-com.aspose.pdf.facades.Bookmarks-) | Legt die Unterelemente des Lesezeichens fest. |
| [setCustomAcorbatViewerMenuActionName](#setCustomAcorbatViewerMenuActionName-int:A-) | Noch nicht unterstützt. Legt den Aktionsnamen fest, der dem Ausführen eines Menüeintrags im Acrobat‑Viewer entspricht. |
| [setDestination](#setDestination-java.lang.String-) | Legt die Zielseite des Lesezeichens fest. Erforderlich, wenn die Aktion als \"\" festgelegt ist. |
| [setItalicFlag](#setItalicFlag-boolean-) | Legt das Kursiv‑Flag des Lesezeichentitels fest. |
| [setLevel](#setLevel-int-) | Legt die Hierarchieebene des Lesezeichens fest. |
| [setOpen](#setOpen-boolean-) | Legt den Zustand des Lesezeichens fest (offen, geschlossen). |
| [setPageDisplay_Bottom](#setPageDisplay_Bottom-int-) | Legt die untere Koordinate der Seitenanzeige fest. |
| [setPageDisplay_Left](#setPageDisplay_Left-int-) | Legt die linke Koordinate der Seitenanzeige fest. |
| [setPageDisplay_Right](#setPageDisplay_Right-int-) | Legt die rechte Koordinate der Seitenanzeige fest. |
| [setPageDisplay_Top](#setPageDisplay_Top-int-) | Legt die obere Koordinate der Seitenanzeige fest. |
| [setPageDisplay_Zoom](#setPageDisplay_Zoom-int-) | Legt den Zoomfaktor der Seitenanzeige fest. |
| [setPageDisplay](#setPageDisplay-java.lang.String-) | Legt den Anzeigetyp der Zielseite des Lesezeichens fest. |
| [setPageNumber](#setPageNumber-int-) | Legt die Nummer der Zielseite des Lesezeichens fest. |
| [setRemoteFile](#setRemoteFile-java.lang.String-) | Legt die Datei (Pfad) fest, die für die "GoToR"-Aktion des Lesezeichens erforderlich ist. |
| [setTitle](#setTitle-java.lang.String-) | Legt den Titel des Lesezeichens fest. |
| [setTitleColor](#setTitleColor-java.awt.Color-) | Legt die Farbe des Lesezeichentitels fest. |
| [toOutlineItemCollection](#toOutlineItemCollection-com.aspose.pdf.IDocument-) | In OutlineItemCollection konvertieren |

### Bookmark {#Bookmark--}
```
public Bookmark()
```

Initialisiert eine neue Instanz der {@code Bookmark}-Klasse.

### getAction {#getAction--}
```
public String getAction()
```

Liest die mit dem Lesezeichen verknüpfte Aktion. Wenn PageNumber angegeben ist, kann die Aktion nicht spezifiziert werden. Der Aktionstyp umfasst: "GoTo", "GoToR", "Launch", "Named".

**Returns:**
String Wert

### getBoldFlag {#getBoldFlag--}
```
public boolean getBoldFlag()
```

Liest das Fettdruck-Flag des Titels des Lesezeichens.

**Returns:**
boolescher Wert

### getChildItem {#getChildItem--}
```
@Deprecated public Bookmarks getChildItem()
```

Liest die Unterelemente des Lesezeichens. Veraltet("Use getChildItems() property instead of this one.")

**Returns:**
Lesezeichen-Element

### getChildItems {#getChildItems--}
```
public Bookmarks getChildItems()
```

Liest die Unterelemente des Lesezeichens.

**Returns:**
Untergeordnete Elemente des Lesezeichens.

### getCustomAcorbatViewerMenuActionName {#getCustomAcorbatViewerMenuActionName--}
```
public int[] getCustomAcorbatViewerMenuActionName()
```

Noch nicht unterstützt. Der Aktionsname, der dem Ausführen eines Menüeintrags im Acrobat-Viewer entspricht.

**Returns:**
Array von int-Werten

### getDestination {#getDestination--}
```
public String getDestination()
```

Liest die Zielseite des Lesezeichens. Erforderlich, wenn die Aktion als "" festgelegt ist.

**Returns:**
String Wert

### getItalicFlag {#getItalicFlag--}
```
public boolean getItalicFlag()
```

Liest das Kursiv-Flag des Titels des Lesezeichens.

**Returns:**
boolescher Wert

### getLevel {#getLevel--}
```
public int getLevel()
```

Ermittelt die Hierarchieebene des Lesezeichens.

**Returns:**
int-Wert

### getPageDisplay_Bottom {#getPageDisplay_Bottom--}
```
public int getPageDisplay_Bottom()
```

Ermittelt die untere Koordinate der Seitenanzeige.

**Returns:**
int-Wert

### getPageDisplay_Left {#getPageDisplay_Left--}
```
public int getPageDisplay_Left()
```

Ermittelt die linke Koordinate der Seitenanzeige.

**Returns:**
int-Wert

### getPageDisplay_Right {#getPageDisplay_Right--}
```
public int getPageDisplay_Right()
```

Ermittelt die rechte Koordinate der Seitenanzeige.

**Returns:**
int-Wert

### getPageDisplay_Top {#getPageDisplay_Top--}
```
public int getPageDisplay_Top()
```

Ermittelt die obere Koordinate der Seitenanzeige.

**Returns:**
int-Wert

### getPageDisplay_Zoom {#getPageDisplay_Zoom--}
```
public int getPageDisplay_Zoom()
```

Ermittelt den Zoomfaktor der Seitenanzeige.

**Returns:**
int-Wert

### getPageDisplay {#getPageDisplay--}
```
public String getPageDisplay()
```

Ermittelt den Typ der Anzeigeseite des Lesezeichenziels.

**Returns:**
String Wert

### getPageNumber {#getPageNumber--}
```
public int getPageNumber()
```

Ermittelt die Nummer der Lesezeichen‑Zielseite.

**Returns:**
int-Wert

### getRemoteFile {#getRemoteFile--}
```
public String getRemoteFile()
```

Ermittelt die Datei (Pfad), die für die \"GoToR\"‑Aktion des Lesezeichens erforderlich ist.

**Returns:**
String Wert

### getTitle {#getTitle--}
```
public String getTitle()
```

Ermittelt den Titel des Lesezeichens.

**Returns:**
String Wert

### getTitleColor {#getTitleColor--}
```
public Color getTitleColor()
```

Ermittelt die Farbe des Lesezeichentitels.

**Returns:**
Farbe-Element

### isOpen {#isOpen--}
```
public boolean isOpen()
```

Ermittelt den Zustand des Lesezeichens (offen, geschlossen).

**Returns:**
boolescher Wert

### setAction {#setAction-java.lang.String-}
Legt die mit dem Lesezeichen verbundene Aktion fest. Wenn PageNumber angegeben ist, kann die Aktion nicht spezifiziert werden. Der Aktionstyp umfasst: \"GoTo\", \"GoToR\", \"Launch\", \"Named\".

### setBoldFlag {#setBoldFlag-boolean-}
```
public void setBoldFlag(boolean value)
```

Legt das Fettdruck‑Flag des Lesezeichentitels fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setChildItem {#setChildItem-com.aspose.pdf.facades.Bookmarks-}
Legt die Unterelemente des Lesezeichens fest. Obsolete(\"Use setChildItems() property instead of this one.\")

### setChildItems {#setChildItems-com.aspose.pdf.facades.Bookmarks-}
Legt die Unterelemente des Lesezeichens fest.

### setCustomAcorbatViewerMenuActionName {#setCustomAcorbatViewerMenuActionName-int:A-}
```
public void setCustomAcorbatViewerMenuActionName(int[] value)
```

Noch nicht unterstützt. Legt den Aktionsnamen fest, der dem Ausführen eines Menüeintrags im Acrobat‑Viewer entspricht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Array von int-Werten |

### setDestination {#setDestination-java.lang.String-}
Legt die Zielseite des Lesezeichens fest. Erforderlich, wenn die Aktion als \"\" festgelegt ist.

### setItalicFlag {#setItalicFlag-boolean-}
```
public void setItalicFlag(boolean value)
```

Legt das Kursiv‑Flag des Lesezeichentitels fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setLevel {#setLevel-int-}
```
public void setLevel(int value)
```

Legt die Hierarchieebene des Lesezeichens fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

Legt den Zustand des Lesezeichens fest (offen, geschlossen).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setPageDisplay_Bottom {#setPageDisplay_Bottom-int-}
```
public void setPageDisplay_Bottom(int value)
```

Legt die untere Koordinate der Seitenanzeige fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setPageDisplay_Left {#setPageDisplay_Left-int-}
```
public void setPageDisplay_Left(int value)
```

Legt die linke Koordinate der Seitenanzeige fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setPageDisplay_Right {#setPageDisplay_Right-int-}
```
public void setPageDisplay_Right(int value)
```

Legt die rechte Koordinate der Seitenanzeige fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setPageDisplay_Top {#setPageDisplay_Top-int-}
```
public void setPageDisplay_Top(int value)
```

Legt die obere Koordinate der Seitenanzeige fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setPageDisplay_Zoom {#setPageDisplay_Zoom-int-}
```
public void setPageDisplay_Zoom(int value)
```

Legt den Zoomfaktor der Seitenanzeige fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setPageDisplay {#setPageDisplay-java.lang.String-}
Legt den Anzeigetyp der Zielseite des Lesezeichens fest.

### setPageNumber {#setPageNumber-int-}
```
public void setPageNumber(int value)
```

Legt die Nummer der Zielseite des Lesezeichens fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setRemoteFile {#setRemoteFile-java.lang.String-}
Legt die Datei (Pfad) fest, die für die "GoToR"-Aktion des Lesezeichens erforderlich ist.

### setTitle {#setTitle-java.lang.String-}
Legt den Titel des Lesezeichens fest.

### setTitleColor {#setTitleColor-java.awt.Color-}
Legt die Farbe des Lesezeichentitels fest.

### toOutlineItemCollection {#toOutlineItemCollection-com.aspose.pdf.IDocument-}
In OutlineItemCollection konvertieren
