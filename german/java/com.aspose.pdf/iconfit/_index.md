---
title: "IconFit"
linktitle: "IconFit"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Beschreibt, wie das Symbol der Widget-Annotation innerhalb ihres Annotationsrechtecks angezeigt werden soll."
type: docs
weight: 2210
url: /de/java/com.aspose.pdf/iconfit/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.IconFit

```
public final class IconFit extends Object
```

Beschreibt, wie das Symbol der Widget-Annotation innerhalb ihres Annotationsrechtecks angezeigt werden soll.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getLeftoverBottom](#getLeftoverBottom--) | Ermittelt den Platz, der am unteren Rand des Icons zugewiesen wird. |
| [getLeftoverLeft](#getLeftoverLeft--) | Ermittelt den Platz, der am linken Rand des Icons zugewiesen wird. |
| [getScalingMode](#getScalingMode--) | Der Skalierungstyp, der verwendet werden soll. |
| [getScalingReason](#getScalingReason--) | Ermittelt den Skalierungsgrund. |
| [isSpreadOnBorder](#isSpreadOnBorder--) | Wenn true, gibt an, dass das Erscheinungsbild der Schaltfläche vollständig innerhalb der Grenzen der Anmerkung skaliert werden soll, ohne die Linienbreite des Rahmens zu berücksichtigen. |
| [nameToScalingMode](#nameToScalingMode-java.lang.String-) | Konvertiert den Namen des Skalierungsmodus in ein ScalingMode-Objekt. |
| [nameToScalingReason](#nameToScalingReason-java.lang.String-) | Konvertiert den Namen des Skalierungsgrundes in ein ScalingReason-Objekt. |
| [scalingModeToName](#scalingModeToName-int-) | Konvertiert ein Skalierungsmodus-Objekt in einen Namen. |
| [scalingReasonToName](#scalingReasonToName-int-) | Konvertiert ein Skalierungsgrund-Objekt in einen Namen. |
| [setLeftoverBottom](#setLeftoverBottom-double-) | Legt den Platz fest, der am unteren Rand des Icons zugewiesen wird. |
| [setLeftoverLeft](#setLeftoverLeft-double-) | Legt den Platz fest, der am linken Rand des Icons zugewiesen wird. |
| [setScalingMode](#setScalingMode-int-) | Der Skalierungstyp, der verwendet werden soll. |
| [setScalingReason](#setScalingReason-int-) | Legt den Skalierungsgrund fest. |
| [setSpreadOnBorder](#setSpreadOnBorder-boolean-) | Wenn true, gibt an, dass das Erscheinungsbild der Schaltfläche vollständig innerhalb der Grenzen der Anmerkung skaliert werden soll, ohne die Linienbreite des Rahmens zu berücksichtigen. |

### getLeftoverBottom {#getLeftoverBottom--}
```
public double getLeftoverBottom()
```

Ermittelt den Platz, der am unteren Rand des Icons zugewiesen wird.

**Returns:**
Platz, der am unteren Rand zugewiesen wird

### getLeftoverLeft {#getLeftoverLeft--}
```
public double getLeftoverLeft()
```

Ermittelt den Platz, der am linken Rand des Icons zugewiesen wird.

**Returns:**
Platz, der am linken Rand des Icons zugewiesen wird.

### getScalingMode {#getScalingMode--}
```
public int getScalingMode()
```

Der Skalierungstyp, der verwendet werden soll.

**Returns:**
ScalingMode-Wert @see ScalingMode

### getScalingReason {#getScalingReason--}
```
public int getScalingReason()
```

Ermittelt den Skalierungsgrund.

**Returns:**
ScalingReason-Wert @see ScalingReason

### isSpreadOnBorder {#isSpreadOnBorder--}
```
public boolean isSpreadOnBorder()
```

Wenn true, gibt an, dass das Erscheinungsbild der Schaltfläche vollständig innerhalb der Grenzen der Anmerkung skaliert werden soll, ohne die Linienbreite des Rahmens zu berücksichtigen.

**Returns:**
boolescher Wert

### nameToScalingMode {#nameToScalingMode-java.lang.String-}
Konvertiert den Namen des Skalierungsmodus in ein ScalingMode-Objekt.

### nameToScalingReason {#nameToScalingReason-java.lang.String-}
Konvertiert den Namen des Skalierungsgrundes in ein ScalingReason-Objekt.

### scalingModeToName {#scalingModeToName-int-}
```
public static String scalingModeToName(int mode)
```

Konvertiert ein Skalierungsmodus-Objekt in einen Namen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Modus |  | Scaling-Modus-Objekt. |

**Returns:**
Scaling-Modus-Name.

### scalingReasonToName {#scalingReasonToName-int-}
```
public static String scalingReasonToName(int reason)
```

Konvertiert ein Skalierungsgrund-Objekt in einen Namen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Grund |  | Scaling-Grund-Objekt, das konvertiert werden soll. |

**Returns:**
Name des Scaling-Grundes.

### setLeftoverBottom {#setLeftoverBottom-double-}
```
public void setLeftoverBottom(double value)
```

Legt den Platz fest, der am unteren Rand des Icons zugewiesen wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Platz, der am unteren Rand zugewiesen wird |

### setLeftoverLeft {#setLeftoverLeft-double-}
```
public void setLeftoverLeft(double value)
```

Legt den Platz fest, der am linken Rand des Icons zugewiesen wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Platz, der am linken Rand des Icons zugewiesen wird. |

### setScalingMode {#setScalingMode-int-}
```
public void setScalingMode(int value)
```

Der Skalierungstyp, der verwendet werden soll.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | ScalingMode-Wert @see ScalingMode |

### setScalingReason {#setScalingReason-int-}
```
public void setScalingReason(int value)
```

Legt den Skalierungsgrund fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | ScalingReason-Wert @see ScalingReason |

### setSpreadOnBorder {#setSpreadOnBorder-boolean-}
```
public void setSpreadOnBorder(boolean value)
```

Wenn true, gibt an, dass das Erscheinungsbild der Schaltfläche vollständig innerhalb der Grenzen der Anmerkung skaliert werden soll, ohne die Linienbreite des Rahmens zu berücksichtigen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |
