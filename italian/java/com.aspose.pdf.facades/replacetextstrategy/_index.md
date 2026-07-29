---
title: "ReplaceTextStrategy"
linktitle: "ReplaceTextStrategy"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Questa classe contiene i parametri che definiscono il comportamento di PdfContentEditor quando viene eseguita l'operazione ReplaceText."
type: docs
weight: 650
url: /it/java/com.aspose.pdf.facades/replacetextstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.ReplaceTextStrategy

```
public final class ReplaceTextStrategy extends Object
```

Questa classe contiene i parametri che definiscono il comportamento di PdfContentEditor quando viene eseguita l'operazione ReplaceText.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ReplaceTextStrategy](#ReplaceTextStrategy--) |  |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getNoCharacterBehavior](#getNoCharacterBehavior--) | Azione eseguita quando non viene trovato alcun font appropriato per il testo modificato (Lancia eccezione / Sostituisci con un altro font / Sostituisci comunque). |
| [getReplaceScope](#getReplaceScope--) | Ambito dell'operazione di sostituzione (sostituisci la prima occorrenza o sostituisci tutte le occorrenze). |
| [isRegularExpressionUsed](#isRegularExpressionUsed--) | Se false, la stringa da trovare è un semplice testo. Se true, la stringa da trovare è un'espressione regolare. |
| [setNoCharacterBehavior](#setNoCharacterBehavior-com.aspose.pdf.facades.ReplaceTextStrategy.NoCharacterAction-) | Azione eseguita quando non viene trovato alcun font appropriato per il testo modificato (Lancia eccezione / Sostituisci con un altro font / Sostituisci comunque). |
| [setRegularExpressionUsed](#setRegularExpressionUsed-boolean-) | Se false, la stringa da trovare è un semplice testo. Se true, la stringa da trovare è un'espressione regolare. |
| [setReplaceScope](#setReplaceScope-com.aspose.pdf.facades.ReplaceTextStrategy.Scope-) | Ambito dell'operazione di sostituzione (sostituisci la prima occorrenza o sostituisci tutte le occorrenze). |

### ReplaceTextStrategy {#ReplaceTextStrategy--}
```
public ReplaceTextStrategy()
```



### getNoCharacterBehavior {#getNoCharacterBehavior--}
```
public ReplaceTextStrategy.NoCharacterAction getNoCharacterBehavior()
```

Azione eseguita quando non viene trovato alcun font appropriato per il testo modificato (Lancia eccezione / Sostituisci con un altro font / Sostituisci comunque).

**Returns:**
Valore NoCharacterAction. @see NoCharacterAction

### getReplaceScope {#getReplaceScope--}
```
public ReplaceTextStrategy.Scope getReplaceScope()
```

Ambito dell'operazione di sostituzione (sostituisci la prima occorrenza o sostituisci tutte le occorrenze).

**Returns:**
Elemento Scope @see Scope

### isRegularExpressionUsed {#isRegularExpressionUsed--}
```
public boolean isRegularExpressionUsed()
```

Se false, la stringa da trovare è un semplice testo. Se true, la stringa da trovare è un'espressione regolare.

**Returns:**
valore booleano

### setNoCharacterBehavior {#setNoCharacterBehavior-com.aspose.pdf.facades.ReplaceTextStrategy.NoCharacterAction-}
Azione eseguita quando non viene trovato alcun font appropriato per il testo modificato (Lancia eccezione / Sostituisci con un altro font / Sostituisci comunque).

### setRegularExpressionUsed {#setRegularExpressionUsed-boolean-}
```
public void setRegularExpressionUsed(boolean value)
```

Se false, la stringa da trovare è un semplice testo. Se true, la stringa da trovare è un'espressione regolare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setReplaceScope {#setReplaceScope-com.aspose.pdf.facades.ReplaceTextStrategy.Scope-}
Ambito dell'operazione di sostituzione (sostituisci la prima occorrenza o sostituisci tutte le occorrenze).
