---
title: "IPdfFileEditor.ContentsResizeValue"
linktitle: "IPdfFileEditor.ContentsResizeValue"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Wert des Randes oder der Inhaltsgröße, angegeben in Prozent der Standard‑Raumeinheiten. Diese Klasse wird in ContentsResizeParameters verwendet."
type: docs
weight: 310
url: /de/java/com.aspose.pdf.facades/ipdffileeditor.contentsresizevalue/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue

```
public static class IPdfFileEditor.ContentsResizeValue extends Object
```

Wert des Randes oder der Inhaltsgröße, angegeben in Prozent der Standard‑Raumeinheiten. Diese Klasse wird in ContentsResizeParameters verwendet.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [auto](#auto--) | Initialisiert automatisch berechneten Wert. |
| [getValue](#getValue--) | Liefert den angegebenen Wert. Verwenden Sie die Eigenschaft Unit, um die Einheit des Wertes zu erhalten. |
| [isPercent](#isPercent--) | Liefert True, wenn der Wert in Prozent angegeben ist; False, wenn der Wert in Standard­einheiten angegeben ist. |
| [percents](#percents-double-) | Initialisiert den Wert in Prozent. |
| [setPercentValue](#setPercentValue-double-) | Setzt den Wert in Prozent der Seitengröße. |
| [setUnitValue](#setUnitValue-double-) | Setzt den Wert in Standard‑Raumeinheiten. |
| [units](#units-double-) | Initialisiert den Wert in Standard‑Raumeinheiten. |

### auto {#auto--}
```
public static IPdfFileEditor.ContentsResizeValue auto()
```

Initialisiert automatisch berechneten Wert.

**Returns:**
Neue Wertinstanz.

### getValue {#getValue--}
```
public final double getValue()
```

Liefert den angegebenen Wert. Verwenden Sie die Eigenschaft Unit, um die Einheit des Wertes zu erhalten.

**Returns:**
double-Wert

### isPercent {#isPercent--}
```
public final boolean isPercent()
```

Liefert True, wenn der Wert in Prozent angegeben ist; False, wenn der Wert in Standard­einheiten angegeben ist.

**Returns:**
boolescher Wert

### percents {#percents-double-}
```
public static IPdfFileEditor.ContentsResizeValue percents(double value)
```

Initialisiert den Wert in Prozent.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Wert in Prozent. |

**Returns:**
Neue Wertinstanz.

### setPercentValue {#setPercentValue-double-}
```
public final void setPercentValue(double value)
```

Setzt den Wert in Prozent der Seitengröße.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### setUnitValue {#setUnitValue-double-}
```
public final void setUnitValue(double value)
```

Setzt den Wert in Standard‑Raumeinheiten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | double-Wert |

### units {#units-double-}
```
public static IPdfFileEditor.ContentsResizeValue units(double value)
```

Initialisiert den Wert in Standard‑Raumeinheiten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Wert in Einheiten. |

**Returns:**
Neue Wertinstanz.
