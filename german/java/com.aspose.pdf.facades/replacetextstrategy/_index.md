---
title: "ReplaceTextStrategy"
linktitle: "ReplaceTextStrategy"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Diese Klasse enthält Parameter, die das Verhalten von PdfContentEditor beim Ausführen einer ReplaceText-Operation definieren."
type: docs
weight: 650
url: /de/java/com.aspose.pdf.facades/replacetextstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.ReplaceTextStrategy

```
public final class ReplaceTextStrategy extends Object
```

Diese Klasse enthält Parameter, die das Verhalten von PdfContentEditor beim Ausführen einer ReplaceText-Operation definieren.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ReplaceTextStrategy](#ReplaceTextStrategy--) |  |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getNoCharacterBehavior](#getNoCharacterBehavior--) | Aktion, die ausgeführt wird, wenn für den geänderten Text keine geeignete Schriftart gefunden wird (Ausnahme werfen / Andere Schriftart substituieren / Trotzdem ersetzen). |
| [getReplaceScope](#getReplaceScope--) | Umfang der Ersetzungsoperation (erste Vorkommen ersetzen oder alle Vorkommen ersetzen). |
| [isRegularExpressionUsed](#isRegularExpressionUsed--) | Falls false, ist die zu findende Zeichenkette ein einfacher Text. Falls true, ist die zu findende Zeichenkette ein regulärer Ausdruck. |
| [setNoCharacterBehavior](#setNoCharacterBehavior-com.aspose.pdf.facades.ReplaceTextStrategy.NoCharacterAction-) | Aktion, die ausgeführt wird, wenn für den geänderten Text keine geeignete Schriftart gefunden wird (Ausnahme werfen / Andere Schriftart substituieren / Trotzdem ersetzen). |
| [setRegularExpressionUsed](#setRegularExpressionUsed-boolean-) | Falls false, ist die zu findende Zeichenkette ein einfacher Text. Falls true, ist die zu findende Zeichenkette ein regulärer Ausdruck. |
| [setReplaceScope](#setReplaceScope-com.aspose.pdf.facades.ReplaceTextStrategy.Scope-) | Umfang der Ersetzungsoperation (erste Vorkommen ersetzen oder alle Vorkommen ersetzen). |

### ReplaceTextStrategy {#ReplaceTextStrategy--}
```
public ReplaceTextStrategy()
```



### getNoCharacterBehavior {#getNoCharacterBehavior--}
```
public ReplaceTextStrategy.NoCharacterAction getNoCharacterBehavior()
```

Aktion, die ausgeführt wird, wenn für den geänderten Text keine geeignete Schriftart gefunden wird (Ausnahme werfen / Andere Schriftart substituieren / Trotzdem ersetzen).

**Returns:**
Wert für NoCharacterAction. @see NoCharacterAction

### getReplaceScope {#getReplaceScope--}
```
public ReplaceTextStrategy.Scope getReplaceScope()
```

Umfang der Ersetzungsoperation (erste Vorkommen ersetzen oder alle Vorkommen ersetzen).

**Returns:**
Scope-Element @see Scope

### isRegularExpressionUsed {#isRegularExpressionUsed--}
```
public boolean isRegularExpressionUsed()
```

Falls false, ist die zu findende Zeichenkette ein einfacher Text. Falls true, ist die zu findende Zeichenkette ein regulärer Ausdruck.

**Returns:**
boolescher Wert

### setNoCharacterBehavior {#setNoCharacterBehavior-com.aspose.pdf.facades.ReplaceTextStrategy.NoCharacterAction-}
Aktion, die ausgeführt wird, wenn für den geänderten Text keine geeignete Schriftart gefunden wird (Ausnahme werfen / Andere Schriftart substituieren / Trotzdem ersetzen).

### setRegularExpressionUsed {#setRegularExpressionUsed-boolean-}
```
public void setRegularExpressionUsed(boolean value)
```

Falls false, ist die zu findende Zeichenkette ein einfacher Text. Falls true, ist die zu findende Zeichenkette ein regulärer Ausdruck.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setReplaceScope {#setReplaceScope-com.aspose.pdf.facades.ReplaceTextStrategy.Scope-}
Umfang der Ersetzungsoperation (erste Vorkommen ersetzen oder alle Vorkommen ersetzen).
