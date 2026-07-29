---
title: "PageLabelCollection"
linktitle: "PageLabelCollection"
second_title: "Aspose.PDF för Java API-referens"
description: "Klassen som representerar en samling av Page Label."
type: docs
weight: 3400
url: /sv/java/com.aspose.pdf/pagelabelcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PageLabelCollection

```
public class PageLabelCollection extends Object
```

Klassen som representerar en samling av Page Label.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLabel](#getLabel-int-) | Hämtar sidetikett efter sidindex (sidindex startar från 0). |
| [getPages](#getPages--) | Hämtar sidindex i samlingen. |
| [removeLabel](#removeLabel-int-) | Ta bort etikett efter sidindex (sidindex startar från 0). |
| [updateLabel](#updateLabel-int-com.aspose.pdf.PageLabel-) | Uppdatera etikett för angivet sidindex (sidindex startar från 0). |

### getLabel {#getLabel-int-}
```
public PageLabel getLabel(int pageIndex)
```

Hämtar sidetikett efter sidindex (sidindex startar från 0).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageIndex |  | Index för sidan. |

**Returns:**
Sidetikett för angivet sidindex eller null om sidetiketten inte finns.

### getPages {#getPages--}
```
public int[] getPages()
```

Hämtar sidindex i samlingen.

**Returns:**
Array av heltal som innehåller index för sidorna.

### removeLabel {#removeLabel-int-}
```
public boolean removeLabel(int pageIndex)
```

Ta bort etikett efter sidindex (sidindex startar från 0).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pageIndex |  | Index för sidan där etiketten ska tas bort. |

**Returns:**
sant om operationen utfördes framgångsrikt.

### updateLabel {#updateLabel-int-com.aspose.pdf.PageLabel-}
Uppdatera etikett för angivet sidindex (sidindex startar från 0).
