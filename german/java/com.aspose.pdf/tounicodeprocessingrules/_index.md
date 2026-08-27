---
title: "ToUnicodeProcessingRules"
linktitle: "ToUnicodeProcessingRules"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Diese Klasse beschreibt Regeln, die verwendet werden können, um den Adobe Preflight-Fehler \\\"Text cannot be mapped to Unicode\\\" zu lösen."
type: docs
weight: 5380
url: /de/java/com.aspose.pdf/tounicodeprocessingrules/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ToUnicodeProcessingRules

```
public class ToUnicodeProcessingRules extends Object
```

Diese Klasse beschreibt Regeln, die verwendet werden können, um den Adobe‑Preflight‑Fehler \"Text cannot be mapped to Unicode\" zu lösen.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ToUnicodeProcessingRules](#ToUnicodeProcessingRules--) | Initialisiert eine neue Instanz der {@link ToUnicodeProcessingRules}-Klasse. |
| [ToUnicodeProcessingRules](#ToUnicodeProcessingRules-boolean-) | Initialisiert eine neue Instanz der {@link ToUnicodeProcessingRules}-Klasse mit der angegebenen Option, Leerzeichen aus CMap-Namen zu entfernen. |
| [ToUnicodeProcessingRules](#ToUnicodeProcessingRules-boolean-boolean-) | Initialisiert eine neue Instanz der {@link ToUnicodeProcessingRules}-Klasse mit angegebenen Optionen. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getMapNonLinkedSymbolsOnSpace](#getMapNonLinkedSymbolsOnSpace--) | Einige Schriftarten liefern keine Informationen über Unicodes für bestimmte Textsymbole. Dieser Mangel an Informationen löst den Fehler \"Text cannot be mapped to Unicode\" aus. Verwenden Sie dieses Flag, um nicht verknüpfte Symbole auf das Unicode‑\"Leerzeichen\" (Code 32) abzubilden. |
| [getRemoveSpacesFromCMapNames](#getRemoveSpacesFromCMapNames--) | Einige Schriftarten haben ToUnicode‑Zeichencodierungskarten mit Leerzeichen in den Namen. Diese Leerzeichen können Fehler bei der Unicode-Textzuordnung verursachen. Dieses Flag bewirkt das Entfernen von Leerzeichen aus den Namen von ToUnicode‑Zeichencodierungskarten. Standardmäßig false. |
| [setMapNonLinkedSymbolsOnSpace](#setMapNonLinkedSymbolsOnSpace-boolean-) | Einige Schriftarten liefern keine Informationen über Unicodes für bestimmte Textsymbole. Dieser Mangel an Informationen löst den Fehler \"Text cannot be mapped to Unicode\" aus. Verwenden Sie dieses Flag, um nicht verknüpfte Symbole auf das Unicode‑\"Leerzeichen\" (Code 32) abzubilden. |
| [setRemoveSpacesFromCMapNames](#setRemoveSpacesFromCMapNames-boolean-) | Einige Schriftarten haben ToUnicode‑Zeichencodierungskarten mit Leerzeichen in den Namen. Diese Leerzeichen können Fehler bei der Unicode-Textzuordnung verursachen. Dieses Flag bewirkt das Entfernen von Leerzeichen aus den Namen von ToUnicode‑Zeichencodierungskarten. Standardmäßig false. |

### ToUnicodeProcessingRules {#ToUnicodeProcessingRules--}
```
public ToUnicodeProcessingRules()
```

Initialisiert eine neue Instanz der {@link ToUnicodeProcessingRules}-Klasse.

### ToUnicodeProcessingRules {#ToUnicodeProcessingRules-boolean-}
```
public ToUnicodeProcessingRules(boolean removeSpaces)
```

Initialisiert eine neue Instanz der {@link ToUnicodeProcessingRules}-Klasse mit der angegebenen Option, Leerzeichen aus CMap-Namen zu entfernen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| removeSpaces |  | Ein boolescher Wert, der angibt, ob Leerzeichen aus CMap-Namen entfernt werden sollen. |

### ToUnicodeProcessingRules {#ToUnicodeProcessingRules-boolean-boolean-}
```
public ToUnicodeProcessingRules(boolean removeSpaces, boolean mapNonLinkedUnicodesOnSpace)
```

Initialisiert eine neue Instanz der {@link ToUnicodeProcessingRules}-Klasse mit angegebenen Optionen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| removeSpaces |  | Gibt an, ob Leerzeichen aus CMap-Namen entfernt werden sollen. |
| mapNonLinkedUnicodesOnSpace |  | Gibt an, ob nicht verknüpfte Unicode‑Symbole auf Leerzeichen abgebildet werden sollen. |

### getMapNonLinkedSymbolsOnSpace {#getMapNonLinkedSymbolsOnSpace--}
```
public boolean getMapNonLinkedSymbolsOnSpace()
```

Einige Schriftarten liefern keine Informationen über Unicodes für bestimmte Textsymbole. Dieser Mangel an Informationen löst den Fehler \"Text cannot be mapped to Unicode\" aus. Verwenden Sie dieses Flag, um nicht verknüpfte Symbole auf das Unicode‑\"Leerzeichen\" (Code 32) abzubilden.

**Returns:**
boolescher Wert

### getRemoveSpacesFromCMapNames {#getRemoveSpacesFromCMapNames--}
```
public boolean getRemoveSpacesFromCMapNames()
```

Einige Schriftarten haben ToUnicode‑Zeichencodierungskarten mit Leerzeichen in den Namen. Diese Leerzeichen können Fehler bei der Unicode-Textzuordnung verursachen. Dieses Flag bewirkt das Entfernen von Leerzeichen aus den Namen von ToUnicode‑Zeichencodierungskarten. Standardmäßig false.

**Returns:**
boolescher Wert

### setMapNonLinkedSymbolsOnSpace {#setMapNonLinkedSymbolsOnSpace-boolean-}
```
public void setMapNonLinkedSymbolsOnSpace(boolean value)
```

Einige Schriftarten liefern keine Informationen über Unicodes für bestimmte Textsymbole. Dieser Mangel an Informationen löst den Fehler \"Text cannot be mapped to Unicode\" aus. Verwenden Sie dieses Flag, um nicht verknüpfte Symbole auf das Unicode‑\"Leerzeichen\" (Code 32) abzubilden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setRemoveSpacesFromCMapNames {#setRemoveSpacesFromCMapNames-boolean-}
```
public void setRemoveSpacesFromCMapNames(boolean value)
```

Einige Schriftarten haben ToUnicode‑Zeichencodierungskarten mit Leerzeichen in den Namen. Diese Leerzeichen können Fehler bei der Unicode-Textzuordnung verursachen. Dieses Flag bewirkt das Entfernen von Leerzeichen aus den Namen von ToUnicode‑Zeichencodierungskarten. Standardmäßig false.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |
