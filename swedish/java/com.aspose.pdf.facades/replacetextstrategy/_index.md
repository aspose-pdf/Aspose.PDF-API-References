---
title: "ReplaceTextStrategy"
linktitle: "ReplaceTextStrategy"
second_title: "Aspose.PDF för Java API-referens"
description: "Denna klass innehåller parametrar som definierar PdfContentEditor‑beteende när ReplaceText‑operationen utförs."
type: docs
weight: 650
url: /sv/java/com.aspose.pdf.facades/replacetextstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.ReplaceTextStrategy

```
public final class ReplaceTextStrategy extends Object
```

Denna klass innehåller parametrar som definierar PdfContentEditor‑beteende när ReplaceText‑operationen utförs.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [ReplaceTextStrategy](#ReplaceTextStrategy--) |  |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getNoCharacterBehavior](#getNoCharacterBehavior--) | Åtgärd som utförs när ingen lämplig teckensnitt hittas för ändrad text (Kasta undantag / Ersätt med annat teckensnitt / Ersätt ändå). |
| [getReplaceScope](#getReplaceScope--) | Omfattning av ersättningsoperationen (ersätt första förekomsten eller ersätt alla förekomster). |
| [isRegularExpressionUsed](#isRegularExpressionUsed--) | Om falskt är söksträngen enkel text. Om sant är söksträngen ett reguljärt uttryck. |
| [setNoCharacterBehavior](#setNoCharacterBehavior-com.aspose.pdf.facades.ReplaceTextStrategy.NoCharacterAction-) | Åtgärd som utförs när ingen lämplig teckensnitt hittas för ändrad text (Kasta undantag / Ersätt med annat teckensnitt / Ersätt ändå). |
| [setRegularExpressionUsed](#setRegularExpressionUsed-boolean-) | Om falskt är söksträngen enkel text. Om sant är söksträngen ett reguljärt uttryck. |
| [setReplaceScope](#setReplaceScope-com.aspose.pdf.facades.ReplaceTextStrategy.Scope-) | Omfattning av ersättningsoperationen (ersätt första förekomsten eller ersätt alla förekomster). |

### ReplaceTextStrategy {#ReplaceTextStrategy--}
```
public ReplaceTextStrategy()
```



### getNoCharacterBehavior {#getNoCharacterBehavior--}
```
public ReplaceTextStrategy.NoCharacterAction getNoCharacterBehavior()
```

Åtgärd som utförs när ingen lämplig teckensnitt hittas för ändrad text (Kasta undantag / Ersätt med annat teckensnitt / Ersätt ändå).

**Returns:**
Värde för NoCharacterAction. @see NoCharacterAction

### getReplaceScope {#getReplaceScope--}
```
public ReplaceTextStrategy.Scope getReplaceScope()
```

Omfattning av ersättningsoperationen (ersätt första förekomsten eller ersätt alla förekomster).

**Returns:**
Scope-element @see Scope

### isRegularExpressionUsed {#isRegularExpressionUsed--}
```
public boolean isRegularExpressionUsed()
```

Om falskt är söksträngen enkel text. Om sant är söksträngen ett reguljärt uttryck.

**Returns:**
booleskt värde

### setNoCharacterBehavior {#setNoCharacterBehavior-com.aspose.pdf.facades.ReplaceTextStrategy.NoCharacterAction-}
Åtgärd som utförs när ingen lämplig teckensnitt hittas för ändrad text (Kasta undantag / Ersätt med annat teckensnitt / Ersätt ändå).

### setRegularExpressionUsed {#setRegularExpressionUsed-boolean-}
```
public void setRegularExpressionUsed(boolean value)
```

Om falskt är söksträngen enkel text. Om sant är söksträngen ett reguljärt uttryck.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setReplaceScope {#setReplaceScope-com.aspose.pdf.facades.ReplaceTextStrategy.Scope-}
Omfattning av ersättningsoperationen (ersätt första förekomsten eller ersätt alla förekomster).
