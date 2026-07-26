---
title: "TextReplaceOptions"
linktitle: "TextReplaceOptions"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta le opzioni di sostituzione del testo"
type: docs
weight: 5250
url: /it/java/com.aspose.pdf/textreplaceoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextReplaceOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextReplaceOptions

```
public final class TextReplaceOptions extends TextOptions
```

Rappresenta le opzioni di sostituzione del testo

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TextReplaceOptions](#TextReplaceOptions--) | Inizializza una nuova istanza dell'oggetto {@code TextReplaceOptions} per l'aggiustamento predefinito e l'ambito: ReplaceAdjustment.None e Scope.REPLACE_FIRST |
| [TextReplaceOptions](#TextReplaceOptions-int-) | Inizializza una nuova istanza dell'oggetto {@code TextReplaceOptions} per l'azione specificata dopo la sostituzione. |
| [TextReplaceOptions](#TextReplaceOptions-int-com.aspose.pdf.TextReplaceOptions.Scope-) | Inizializza una nuova istanza dell'oggetto {@code TextReplaceOptions} per l'aggiustamento predefinito e l'ambito: ReplaceAdjustment.None e Scope.REPLACE_FIRST |
| [TextReplaceOptions](#TextReplaceOptions-com.aspose.pdf.TextReplaceOptions.Scope-) | Inizializza una nuova istanza dell'oggetto {@code TextReplaceOptions} per l'aggiustamento predefinito e l'ambito: ReplaceAdjustment.None e Scope.REPLACE_FIRST |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAdjustmentNewLineSpacing](#getAdjustmentNewLineSpacing--) | Ottiene o imposta il valore dell'interlinea utilizzato se l'aggiustamento della sostituzione è forzato a creare una nuova riga di testo. Il valore previsto è un moltiplicatore della dimensione del carattere del testo sostituito. Il valore predefinito è 1,2. |
| [getFontSizeAdjustmentAction](#getFontSizeAdjustmentAction--) | Ottiene o imposta la politica per regolare la dimensione del carattere in modo da adattarsi ai limiti definiti da {@code TextReplaceOptions.Rectangle}({@link #getRectangle}/{@link #setRectangle(Rectangle)}). |
| [getLeftAdjustment](#getLeftAdjustment--) | Ottiene la regolazione della posizione sinistra per il testo sostituito quando si utilizza TextReplaceOptions: - ReplaceAdjustmentAction = IsFormFillingMode; |
| [getRectangle](#getRectangle--) | Ottiene o imposta il rettangolo per adattare il testo dopo la sostituzione. |
| [getReplaceAdjustmentAction](#getReplaceAdjustmentAction--) | Ottiene un'azione che verrà eseguita dopo la sostituzione del frammento di testo per renderlo più breve. |
| [getReplaceScope](#getReplaceScope--) | Ottiene l'ambito in cui viene applicata l'operazione di sostituzione del testo |
| [getRightAdjustment](#getRightAdjustment--) | Imposta o ottiene la regolazione della posizione destra per il testo sostituito quando si utilizza TextReplaceOptions: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode; |
| [isIgnoreParagraphs](#isIgnoreParagraphs--) | Ottiene o imposta un valore che indica se ignorare paragrafi distinti durante la regolazione del testo nella pagina dopo la sostituzione del testo. |
| [setAdjustmentNewLineSpacing](#setAdjustmentNewLineSpacing-double-) | Ottiene o imposta il valore dell'interlinea utilizzato se l'aggiustamento della sostituzione è forzato a creare una nuova riga di testo. Il valore previsto è un moltiplicatore della dimensione del carattere del testo sostituito. Il valore predefinito è 1,2. |
| [setFontSizeAdjustmentAction](#setFontSizeAdjustmentAction-com.aspose.pdf.TextReplaceOptions.FontSizeAdjustment-) | Ottiene o imposta la politica per regolare la dimensione del carattere in modo da adattarsi ai limiti definiti da TextReplaceOptions.Rectangle ( getRectangle() / setRectangle(Rectangle) ). |
| [setIgnoreParagraphs](#setIgnoreParagraphs-boolean-) | Ottiene o imposta un valore che indica se ignorare paragrafi distinti durante la regolazione del testo nella pagina dopo la sostituzione del testo. |
| [setLeftAdjustment](#setLeftAdjustment-double-) | Imposta o ottiene la regolazione della posizione sinistra per il testo sostituito quando si utilizza TextReplaceOptions: - ReplaceAdjustmentAction = IsFormFillingMode; |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | Ottiene o imposta il rettangolo per adattare il testo dopo la sostituzione. |
| [setReplaceAdjustmentAction](#setReplaceAdjustmentAction-int-) | Imposta un'azione che verrà eseguita dopo la sostituzione del frammento di testo per renderlo più breve. |
| [setReplaceScope](#setReplaceScope-com.aspose.pdf.TextReplaceOptions.Scope-) | Imposta l'ambito in cui viene applicata l'operazione di sostituzione del testo |
| [setRightAdjustment](#setRightAdjustment-double-) | Imposta la regolazione della posizione destra per il testo sostituito quando si utilizza TextReplaceOptions: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode; |

### TextReplaceOptions {#TextReplaceOptions--}
```
public TextReplaceOptions()
```

Inizializza una nuova istanza dell'oggetto {@code TextReplaceOptions} per l'aggiustamento predefinito e l'ambito: ReplaceAdjustment.None e Scope.REPLACE_FIRST

### TextReplaceOptions {#TextReplaceOptions-int-}
```
public TextReplaceOptions(int adjustment)
```

Inizializza una nuova istanza dell'oggetto {@code TextReplaceOptions} per l'azione specificata dopo la sostituzione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| aggiustamento |  | Oggetto ReplaceAdjustment. @see ReplaceAdjustment |

### TextReplaceOptions {#TextReplaceOptions-int-com.aspose.pdf.TextReplaceOptions.Scope-}
Inizializza una nuova istanza dell'oggetto {@code TextReplaceOptions} per l'aggiustamento predefinito e l'ambito: ReplaceAdjustment.None e Scope.REPLACE_FIRST

### TextReplaceOptions {#TextReplaceOptions-com.aspose.pdf.TextReplaceOptions.Scope-}
Inizializza una nuova istanza dell'oggetto {@code TextReplaceOptions} per l'aggiustamento predefinito e l'ambito: ReplaceAdjustment.None e Scope.REPLACE_FIRST

### getAdjustmentNewLineSpacing {#getAdjustmentNewLineSpacing--}
```
public double getAdjustmentNewLineSpacing()
```

Ottiene o imposta il valore dell'interlinea utilizzato se l'aggiustamento della sostituzione è forzato a creare una nuova riga di testo. Il valore previsto è un moltiplicatore della dimensione del carattere del testo sostituito. Il valore predefinito è 1,2.

**Returns:**
valore double

### getFontSizeAdjustmentAction {#getFontSizeAdjustmentAction--}
```
public final TextReplaceOptions.FontSizeAdjustment getFontSizeAdjustmentAction()
```

Ottiene o imposta la politica per regolare la dimensione del carattere in modo da adattarsi ai limiti definiti da {@code TextReplaceOptions.Rectangle}({@link #getRectangle}/{@link #setRectangle(Rectangle)}).

**Returns:**
Elemento FontSizeAdjustment

### getLeftAdjustment {#getLeftAdjustment--}
```
public final double getLeftAdjustment()
```

Ottiene la regolazione della posizione sinistra per il testo sostituito quando si utilizza TextReplaceOptions: - ReplaceAdjustmentAction = IsFormFillingMode;

**Returns:**
valore double

### getRectangle {#getRectangle--}
```
public final Rectangle getRectangle()
```

Ottiene o imposta il rettangolo per adattare il testo dopo la sostituzione.

**Returns:**
Istanza Rectangle

### getReplaceAdjustmentAction {#getReplaceAdjustmentAction--}
```
public int getReplaceAdjustmentAction()
```

Ottiene un'azione che verrà eseguita dopo la sostituzione del frammento di testo per renderlo più breve.

**Returns:**
Elemento ReplaceAdjustment @see ReplaceAdjustment

### getReplaceScope {#getReplaceScope--}
```
public TextReplaceOptions.Scope getReplaceScope()
```

Ottiene l'ambito in cui viene applicata l'operazione di sostituzione del testo

**Returns:**
valore int @see Scope

### getRightAdjustment {#getRightAdjustment--}
```
public final double getRightAdjustment()
```

Imposta o ottiene la regolazione della posizione destra per il testo sostituito quando si utilizza TextReplaceOptions: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode;

**Returns:**
valore double

### isIgnoreParagraphs {#isIgnoreParagraphs--}
```
public final boolean isIgnoreParagraphs()
```

Ottiene o imposta un valore che indica se ignorare paragrafi distinti durante la regolazione del testo nella pagina dopo la sostituzione del testo.

**Returns:**
valore booleano

### setAdjustmentNewLineSpacing {#setAdjustmentNewLineSpacing-double-}
```
public void setAdjustmentNewLineSpacing(double value)
```

Ottiene o imposta il valore dell'interlinea utilizzato se l'aggiustamento della sostituzione è forzato a creare una nuova riga di testo. Il valore previsto è un moltiplicatore della dimensione del carattere del testo sostituito. Il valore predefinito è 1,2.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setFontSizeAdjustmentAction {#setFontSizeAdjustmentAction-com.aspose.pdf.TextReplaceOptions.FontSizeAdjustment-}
Ottiene o imposta la politica per regolare la dimensione del carattere in modo da adattarsi ai limiti definiti da TextReplaceOptions.Rectangle ( getRectangle() / setRectangle(Rectangle) ).

### setIgnoreParagraphs {#setIgnoreParagraphs-boolean-}
```
public final void setIgnoreParagraphs(boolean value)
```

Ottiene o imposta un valore che indica se ignorare paragrafi distinti durante la regolazione del testo nella pagina dopo la sostituzione del testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setLeftAdjustment {#setLeftAdjustment-double-}
```
public final void setLeftAdjustment(double value)
```

Imposta o ottiene la regolazione della posizione sinistra per il testo sostituito quando si utilizza TextReplaceOptions: - ReplaceAdjustmentAction = IsFormFillingMode;

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
Ottiene o imposta il rettangolo per adattare il testo dopo la sostituzione.

### setReplaceAdjustmentAction {#setReplaceAdjustmentAction-int-}
```
public void setReplaceAdjustmentAction(int value)
```

Imposta un'azione che verrà eseguita dopo la sostituzione del frammento di testo per renderlo più breve.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Elemento ReplaceAdjustment @see ReplaceAdjustment |

### setReplaceScope {#setReplaceScope-com.aspose.pdf.TextReplaceOptions.Scope-}
Imposta l'ambito in cui viene applicata l'operazione di sostituzione del testo

### setRightAdjustment {#setRightAdjustment-double-}
```
public final void setRightAdjustment(double value)
```

Imposta la regolazione della posizione destra per il testo sostituito quando si utilizza TextReplaceOptions: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode;

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |
