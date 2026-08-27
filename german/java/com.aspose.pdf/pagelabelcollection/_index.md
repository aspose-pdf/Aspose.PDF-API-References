---
title: "PageLabelCollection"
linktitle: "PageLabelCollection"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Seiten‑Markup dargestellt durch Sammlungen von {@code MarkupSection} und {@code MarkupParagraph}."
type: docs
weight: 3400
url: /de/java/com.aspose.pdf/pagelabelcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PageLabelCollection

```
public class PageLabelCollection extends Object
```

Seiten‑Markup dargestellt durch Sammlungen von {@code MarkupSection} und {@code MarkupParagraph}.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLabel](#getLabel-int-) | Liefert das Seitenlabel nach Seitenindex (Seitenindex beginnt bei 0). |
| [getPages](#getPages--) | Liefert die Seitenindizes in der Sammlung. |
| [removeLabel](#removeLabel-int-) | Entfernt das Label nach Seitenindex (Seitenindex beginnt bei 0). |
| [updateLabel](#updateLabel-int-com.aspose.pdf.PageLabel-) | Aktualisiert das Label für den angegebenen Seitenindex (Seitenindex beginnt bei 0). |

### getLabel {#getLabel-int-}
```
public PageLabel getLabel(int pageIndex)
```

Liefert das Seitenlabel nach Seitenindex (Seitenindex beginnt bei 0).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageIndex |  | Index der Seite. |

**Returns:**
Seitenlabel für den angegebenen Seitenindex oder null, falls das Seitenlabel nicht existiert.

### getPages {#getPages--}
```
public int[] getPages()
```

Liefert die Seitenindizes in der Sammlung.

**Returns:**
Array von Ganzzahlen, das die Indizes der Seiten enthält.

### removeLabel {#removeLabel-int-}
```
public boolean removeLabel(int pageIndex)
```

Entfernt das Label nach Seitenindex (Seitenindex beginnt bei 0).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pageIndex |  | Index der Seite, bei der das Label gelöscht werden muss. |

**Returns:**
true, wenn die Operation erfolgreich ausgeführt wurde.

### updateLabel {#updateLabel-int-com.aspose.pdf.PageLabel-}
Aktualisiert das Label für den angegebenen Seitenindex (Seitenindex beginnt bei 0).
