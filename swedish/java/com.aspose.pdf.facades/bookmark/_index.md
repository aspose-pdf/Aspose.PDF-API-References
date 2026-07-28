---
title: "Bookmark"
linktitle: "Bookmark"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar ett bokmärke."
type: docs
weight: 60
url: /sv/java/com.aspose.pdf.facades/bookmark/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Bookmark

```
public final class Bookmark extends Object
```

Representerar ett bokmärke.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [Bookmark](#Bookmark--) | Initierar en ny instans av {@code Bookmark}-klassen. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAction](#getAction--) | Hämtar åtgärden som är bunden till bokmärket. Om PageNumber är angivet kan åtgärden inte specificeras. Åtgärdstypen inkluderar: "GoTo", "GoToR", "Launch", "Named". |
| [getBoldFlag](#getBoldFlag--) | Hämtar fetstil-flaggan för bokmärkets titel. |
| [getChildItem](#getChildItem--) | Hämtar bokmärkets barn. Obsolete("Use getChildItems() property instead of this one.") |
| [getChildItems](#getChildItems--) | Hämtar bokmärkets barn. |
| [getCustomAcorbatViewerMenuActionName](#getCustomAcorbatViewerMenuActionName--) | Stöds ännu inte. Åtgärdsnamnet som motsvarar att köra ett menyalternativ i Acrobat-visaren. |
| [getDestination](#getDestination--) | Hämtar bokmärkets destinationssida. Krävs om åtgärden är satt till "". |
| [getItalicFlag](#getItalicFlag--) | Hämtar kursiv-flaggan för bokmärkets titel. |
| [getLevel](#getLevel--) | Hämtar bokmärkets hierarkinivå. |
| [getPageDisplay_Bottom](#getPageDisplay_Bottom--) | Hämtar den nedre koordinaten för sidvisningen. |
| [getPageDisplay_Left](#getPageDisplay_Left--) | Hämtar den vänstra koordinaten för sidvisningen. |
| [getPageDisplay_Right](#getPageDisplay_Right--) | Hämtar den högra koordinaten för sidvisning. |
| [getPageDisplay_Top](#getPageDisplay_Top--) | Hämtar den övre koordinaten för sidvisning. |
| [getPageDisplay_Zoom](#getPageDisplay_Zoom--) | Hämtar zoomfaktorn för sidvisning. |
| [getPageDisplay](#getPageDisplay--) | Hämtar typen av visningsbokmärkets destinationssida. |
| [getPageNumber](#getPageNumber--) | Hämtar antalet för bokmärkets destinationssida. |
| [getRemoteFile](#getRemoteFile--) | Hämtar filen (sökvägen) som krävs för "GoToR"‑åtgärden för bokmärket. |
| [getTitle](#getTitle--) | Hämtar bokmärkets titel. |
| [getTitleColor](#getTitleColor--) | Hämtar färgen på bokmärkets titel. |
| [isOpen](#isOpen--) | Hämtar bokmärkets tillstånd (öppen, stängd). |
| [setAction](#setAction-java.lang.String-) | Ställer in åtgärden som är bunden till bokmärket. Om PageNumber är angivet kan inte åtgärden specificeras. Åtgärdstypen inkluderar: "GoTo", "GoToR", "Launch", "Named". |
| [setBoldFlag](#setBoldFlag-boolean-) | Ställer in fetstil‑flaggan för bokmärkets titel. |
| [setChildItem](#setChildItem-com.aspose.pdf.facades.Bookmarks-) | Ställer in bokmärkets barn. Obsolete("Använd setChildItems() egenskap istället för den här.") |
| [setChildItems](#setChildItems-com.aspose.pdf.facades.Bookmarks-) | Ställer in bokmärkets barn. |
| [setCustomAcorbatViewerMenuActionName](#setCustomAcorbatViewerMenuActionName-int:A-) | Stöds ännu inte. Ställer in åtgärdsnamnet som motsvarar att köra ett menyalternativ i Acrobat‑visaren. |
| [setDestination](#setDestination-java.lang.String-) | Ställer in bokmärkets destinationssida. Krävs om åtgärden är inställd som "". |
| [setItalicFlag](#setItalicFlag-boolean-) | Ställer in kursiv‑flaggan för bokmärkets titel. |
| [setLevel](#setLevel-int-) | Ställer in bokmärkets hierarkinivå. |
| [setOpen](#setOpen-boolean-) | Ställer in bokmärkets tillstånd (öppen, stängd). |
| [setPageDisplay_Bottom](#setPageDisplay_Bottom-int-) | Ställer in den nedre koordinaten för sidvisning. |
| [setPageDisplay_Left](#setPageDisplay_Left-int-) | Ställer in den vänstra koordinaten för sidvisning. |
| [setPageDisplay_Right](#setPageDisplay_Right-int-) | Ställer in den högra koordinaten för sidvisning. |
| [setPageDisplay_Top](#setPageDisplay_Top-int-) | Ställer in den övre koordinaten för sidvisning. |
| [setPageDisplay_Zoom](#setPageDisplay_Zoom-int-) | Ställer in zoomfaktorn för sidvisning. |
| [setPageDisplay](#setPageDisplay-java.lang.String-) | Ställer in typen av visningsbokmärkets destinationssida. |
| [setPageNumber](#setPageNumber-int-) | Ställer in antalet för bokmärkets destinationssida. |
| [setRemoteFile](#setRemoteFile-java.lang.String-) | Ställer in filen (sökvägen) som krävs för "GoToR"-åtgärden för bokmärke. |
| [setTitle](#setTitle-java.lang.String-) | Ställer in bokmärkets titel. |
| [setTitleColor](#setTitleColor-java.awt.Color-) | Ställer in färgen på bokmärkets titel. |
| [toOutlineItemCollection](#toOutlineItemCollection-com.aspose.pdf.IDocument-) | konvertera till OutlineItemCollection |

### Bookmark {#Bookmark--}
```
public Bookmark()
```

Initierar en ny instans av {@code Bookmark}-klassen.

### getAction {#getAction--}
```
public String getAction()
```

Hämtar åtgärden som är bunden till bokmärket. Om PageNumber är angivet kan åtgärden inte specificeras. Åtgärdstypen inkluderar: "GoTo", "GoToR", "Launch", "Named".

**Returns:**
String värde

### getBoldFlag {#getBoldFlag--}
```
public boolean getBoldFlag()
```

Hämtar fetstil-flaggan för bokmärkets titel.

**Returns:**
booleskt värde

### getChildItem {#getChildItem--}
```
@Deprecated public Bookmarks getChildItem()
```

Hämtar bokmärkets barn. Obsolete("Use getChildItems() property instead of this one.")

**Returns:**
Bokmärken element

### getChildItems {#getChildItems--}
```
public Bookmarks getChildItems()
```

Hämtar bokmärkets barn.

**Returns:**
bokmärkets underordnade objekt.

### getCustomAcorbatViewerMenuActionName {#getCustomAcorbatViewerMenuActionName--}
```
public int[] getCustomAcorbatViewerMenuActionName()
```

Stöds ännu inte. Åtgärdsnamnet som motsvarar att köra ett menyalternativ i Acrobat-visaren.

**Returns:**
array av int‑värde

### getDestination {#getDestination--}
```
public String getDestination()
```

Hämtar bokmärkets destinationssida. Krävs om åtgärden är satt till "".

**Returns:**
String värde

### getItalicFlag {#getItalicFlag--}
```
public boolean getItalicFlag()
```

Hämtar kursiv-flaggan för bokmärkets titel.

**Returns:**
booleskt värde

### getLevel {#getLevel--}
```
public int getLevel()
```

Hämtar bokmärkets hierarkinivå.

**Returns:**
int‑värde

### getPageDisplay_Bottom {#getPageDisplay_Bottom--}
```
public int getPageDisplay_Bottom()
```

Hämtar den nedre koordinaten för sidvisningen.

**Returns:**
int‑värde

### getPageDisplay_Left {#getPageDisplay_Left--}
```
public int getPageDisplay_Left()
```

Hämtar den vänstra koordinaten för sidvisningen.

**Returns:**
int‑värde

### getPageDisplay_Right {#getPageDisplay_Right--}
```
public int getPageDisplay_Right()
```

Hämtar den högra koordinaten för sidvisning.

**Returns:**
int‑värde

### getPageDisplay_Top {#getPageDisplay_Top--}
```
public int getPageDisplay_Top()
```

Hämtar den övre koordinaten för sidvisning.

**Returns:**
int‑värde

### getPageDisplay_Zoom {#getPageDisplay_Zoom--}
```
public int getPageDisplay_Zoom()
```

Hämtar zoomfaktorn för sidvisning.

**Returns:**
int‑värde

### getPageDisplay {#getPageDisplay--}
```
public String getPageDisplay()
```

Hämtar typen av visningsbokmärkets destinationssida.

**Returns:**
String värde

### getPageNumber {#getPageNumber--}
```
public int getPageNumber()
```

Hämtar antalet för bokmärkets destinationssida.

**Returns:**
int‑värde

### getRemoteFile {#getRemoteFile--}
```
public String getRemoteFile()
```

Hämtar filen (sökvägen) som krävs för "GoToR"‑åtgärden för bokmärket.

**Returns:**
String värde

### getTitle {#getTitle--}
```
public String getTitle()
```

Hämtar bokmärkets titel.

**Returns:**
String värde

### getTitleColor {#getTitleColor--}
```
public Color getTitleColor()
```

Hämtar färgen på bokmärkets titel.

**Returns:**
Färgelement

### isOpen {#isOpen--}
```
public boolean isOpen()
```

Hämtar bokmärkets tillstånd (öppen, stängd).

**Returns:**
booleskt värde

### setAction {#setAction-java.lang.String-}
Ställer in åtgärden som är bunden till bokmärket. Om PageNumber är angivet kan inte åtgärden specificeras. Åtgärdstypen inkluderar: "GoTo", "GoToR", "Launch", "Named".

### setBoldFlag {#setBoldFlag-boolean-}
```
public void setBoldFlag(boolean value)
```

Ställer in fetstil‑flaggan för bokmärkets titel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setChildItem {#setChildItem-com.aspose.pdf.facades.Bookmarks-}
Ställer in bokmärkets barn. Obsolete("Använd setChildItems() egenskap istället för den här.")

### setChildItems {#setChildItems-com.aspose.pdf.facades.Bookmarks-}
Ställer in bokmärkets barn.

### setCustomAcorbatViewerMenuActionName {#setCustomAcorbatViewerMenuActionName-int:A-}
```
public void setCustomAcorbatViewerMenuActionName(int[] value)
```

Stöds ännu inte. Ställer in åtgärdsnamnet som motsvarar att köra ett menyalternativ i Acrobat‑visaren.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | array av int‑värde |

### setDestination {#setDestination-java.lang.String-}
Ställer in bokmärkets destinationssida. Krävs om åtgärden är inställd som "".

### setItalicFlag {#setItalicFlag-boolean-}
```
public void setItalicFlag(boolean value)
```

Ställer in kursiv‑flaggan för bokmärkets titel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setLevel {#setLevel-int-}
```
public void setLevel(int value)
```

Ställer in bokmärkets hierarkinivå.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

Ställer in bokmärkets tillstånd (öppen, stängd).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setPageDisplay_Bottom {#setPageDisplay_Bottom-int-}
```
public void setPageDisplay_Bottom(int value)
```

Ställer in den nedre koordinaten för sidvisning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setPageDisplay_Left {#setPageDisplay_Left-int-}
```
public void setPageDisplay_Left(int value)
```

Ställer in den vänstra koordinaten för sidvisning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setPageDisplay_Right {#setPageDisplay_Right-int-}
```
public void setPageDisplay_Right(int value)
```

Ställer in den högra koordinaten för sidvisning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setPageDisplay_Top {#setPageDisplay_Top-int-}
```
public void setPageDisplay_Top(int value)
```

Ställer in den övre koordinaten för sidvisning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setPageDisplay_Zoom {#setPageDisplay_Zoom-int-}
```
public void setPageDisplay_Zoom(int value)
```

Ställer in zoomfaktorn för sidvisning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setPageDisplay {#setPageDisplay-java.lang.String-}
Ställer in typen av visningsbokmärkets destinationssida.

### setPageNumber {#setPageNumber-int-}
```
public void setPageNumber(int value)
```

Ställer in antalet för bokmärkets destinationssida.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setRemoteFile {#setRemoteFile-java.lang.String-}
Ställer in filen (sökvägen) som krävs för "GoToR"-åtgärden för bokmärke.

### setTitle {#setTitle-java.lang.String-}
Ställer in bokmärkets titel.

### setTitleColor {#setTitleColor-java.awt.Color-}
Ställer in färgen på bokmärkets titel.

### toOutlineItemCollection {#toOutlineItemCollection-com.aspose.pdf.IDocument-}
konvertera till OutlineItemCollection
