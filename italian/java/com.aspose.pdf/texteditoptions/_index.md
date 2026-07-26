---
title: "TextEditOptions"
linktitle: "TextEditOptions"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Descrive le opzioni delle operazioni di modifica del testo."
type: docs
weight: 4970
url: /it/java/com.aspose.pdf/texteditoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextEditOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextEditOptions

```
public final class TextEditOptions extends TextOptions
```

Descrive le opzioni delle operazioni di modifica del testo.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TextEditOptions](#TextEditOptions--) | Inizializza una nuova istanza dell'oggetto {@code TextEditOptions} con le opzioni predefinite. NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-boolean-) | / * / * Inizializza una nuova istanza dell'oggetto {@code TextEditOptions} per la modalità di riorganizzazione del testo specificata. / * / * |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.FontReplace-) | Inizializza una nuova istanza dell'oggetto {@code TextEditOptions} con le opzioni predefinite. NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.LanguageTransformation-) | Inizializza una nuova istanza dell'oggetto {@code TextEditOptions} con le opzioni predefinite. NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.NoCharacterAction-) | Inizializza una nuova istanza dell'oggetto {@code TextEditOptions} con le opzioni predefinite. NoCharacterAction.UseStandardFont LanguageTransformation.Default |
| [TextEditOptions](#TextEditOptions-com.aspose.pdf.TextEditOptions.TextRearrangement-) | Inizializza una nuova istanza dell'oggetto {@code TextEditOptions} con le opzioni predefinite. NoCharacterAction.UseStandardFont LanguageTransformation.Default |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAllowLanguageTransformation](#getAllowLanguageTransformation--) | Ottiene il valore che consente l'uso della trasformazione linguistica durante l'aggiunta o la modifica del testo. true - la trasformazione linguistica verrà applicata se necessario (valore predefinito). false - la trasformazione linguistica NON verrà applicata. |
| [getClippingPathsProcessing](#getClippingPathsProcessing--) | Ottiene la modalità per l'elaborazione del percorso di ritaglio del testo modificato. |
| [getFontReplaceBehavior](#getFontReplaceBehavior--) | Ottiene la modalità che definisce il comportamento per gli scenari di sostituzione dei font. |
| [getLanguageTransformationBehavior](#getLanguageTransformationBehavior--) | Ottiene la modalità che definisce il comportamento per gli scenari di trasformazione linguistica. |
| [getNoCharacterBehavior](#getNoCharacterBehavior--) | Ottiene la modalità che definisce il comportamento nel caso in cui i font non contengano i caratteri richiesti. |
| [getReplacementFont](#getReplacementFont--) | Ottiene o imposta il font usato per la sostituzione se il font dell'utente non contiene il carattere richiesto |
| [getToAttemptGetUnderlineFromSource](#getToAttemptGetUnderlineFromSource--) | <p> Ottiene o imposta il valore che consente la ricerca di sottolineature del testo nella pagina del documento di origine. <p> (Obsoleto) Si prega di utilizzare TextSearchOptions.SearchForTextRelatedGraphics invece di questo. </p> |
| [setAllowLanguageTransformation](#setAllowLanguageTransformation-boolean-) | Imposta il valore che consente l'uso della trasformazione linguistica durante l'aggiunta o la modifica del testo. true - la trasformazione linguistica verrà applicata se necessario (valore predefinito). false - la trasformazione linguistica NON verrà applicata. |
| [setClippingPathsProcessing](#setClippingPathsProcessing-com.aspose.pdf.TextEditOptions.ClippingPathsProcessingMode-) | Ottiene la modalità per l'elaborazione del percorso di ritaglio del testo modificato. |
| [setFontReplaceBehavior](#setFontReplaceBehavior-com.aspose.pdf.TextEditOptions.FontReplace-) | Imposta la modalità che definisce il comportamento per gli scenari di sostituzione dei font. |
| [setLanguageTransformationBehavior](#setLanguageTransformationBehavior-com.aspose.pdf.TextEditOptions.LanguageTransformation-) | Imposta la modalità che definisce il comportamento per gli scenari di trasformazione linguistica. |
| [setNoCharacterBehavior](#setNoCharacterBehavior-com.aspose.pdf.TextEditOptions.NoCharacterAction-) | Imposta la modalità che definisce il comportamento nel caso in cui i font non contengano i caratteri richiesti. |
| [setReplacementFont](#setReplacementFont-com.aspose.pdf.Font-) | Ottiene o imposta il font usato per la sostituzione se il font dell'utente non contiene il carattere richiesto |
| [setToAttemptGetUnderlineFromSource](#setToAttemptGetUnderlineFromSource-boolean-) | <p> Ottiene o imposta il valore che consente la ricerca di sottolineature del testo nella pagina del documento di origine. <p> (Obsoleto) Si prega di utilizzare TextSearchOptions.SearchForTextRelatedGraphics invece di questo. </p> |

### TextEditOptions {#TextEditOptions--}
```
public TextEditOptions()
```

Inizializza una nuova istanza dell'oggetto {@code TextEditOptions} con le opzioni predefinite. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-boolean-}
```
public TextEditOptions(boolean allowLanguageTransformation)
```

/ * / * Inizializza una nuova istanza dell'oggetto {@code TextEditOptions} per la modalità di riorganizzazione del testo specificata. / * / *

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| allowLanguageTransformation |  |  |

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.FontReplace-}
Inizializza una nuova istanza dell'oggetto {@code TextEditOptions} con le opzioni predefinite. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.LanguageTransformation-}
Inizializza una nuova istanza dell'oggetto {@code TextEditOptions} con le opzioni predefinite. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.NoCharacterAction-}
Inizializza una nuova istanza dell'oggetto {@code TextEditOptions} con le opzioni predefinite. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### TextEditOptions {#TextEditOptions-com.aspose.pdf.TextEditOptions.TextRearrangement-}
Inizializza una nuova istanza dell'oggetto {@code TextEditOptions} con le opzioni predefinite. NoCharacterAction.UseStandardFont LanguageTransformation.Default

### getAllowLanguageTransformation {#getAllowLanguageTransformation--}
```
public boolean getAllowLanguageTransformation()
```

Ottiene il valore che consente l'uso della trasformazione linguistica durante l'aggiunta o la modifica del testo. true - la trasformazione linguistica verrà applicata se necessario (valore predefinito). false - la trasformazione linguistica NON verrà applicata.

**Returns:**
valore booleano

### getClippingPathsProcessing {#getClippingPathsProcessing--}
```
public final TextEditOptions.ClippingPathsProcessingMode getClippingPathsProcessing()
```

Ottiene la modalità per l'elaborazione del percorso di ritaglio del testo modificato.

**Returns:**
Elemento ClippingPathsProcessingMode

### getFontReplaceBehavior {#getFontReplaceBehavior--}
```
public TextEditOptions.FontReplace getFontReplaceBehavior()
```

Ottiene la modalità che definisce il comportamento per gli scenari di sostituzione dei font.

**Returns:**
FontReplace valore @see FontReplace

### getLanguageTransformationBehavior {#getLanguageTransformationBehavior--}
```
public TextEditOptions.LanguageTransformation getLanguageTransformationBehavior()
```

Ottiene la modalità che definisce il comportamento per gli scenari di trasformazione linguistica.

**Returns:**
LanguageTransformation valore @see LanguageTransformation

### getNoCharacterBehavior {#getNoCharacterBehavior--}
```
public TextEditOptions.NoCharacterAction getNoCharacterBehavior()
```

Ottiene la modalità che definisce il comportamento nel caso in cui i font non contengano i caratteri richiesti.

**Returns:**
NoCharacterAction valore @see NoCharacterAction

### getReplacementFont {#getReplacementFont--}
```
public final Font getReplacementFont()
```

Ottiene o imposta il font usato per la sostituzione se il font dell'utente non contiene il carattere richiesto

**Returns:**
Font istanza

### getToAttemptGetUnderlineFromSource {#getToAttemptGetUnderlineFromSource--}
```
public boolean getToAttemptGetUnderlineFromSource()
```

<p> Ottiene o imposta il valore che consente la ricerca di sottolineature del testo nella pagina del documento di origine. <p> (Obsoleto) Si prega di utilizzare TextSearchOptions.SearchForTextRelatedGraphics invece di questo. </p>

**Returns:**
valore booleano

### setAllowLanguageTransformation {#setAllowLanguageTransformation-boolean-}
```
public void setAllowLanguageTransformation(boolean value)
```

Imposta il valore che consente l'uso della trasformazione linguistica durante l'aggiunta o la modifica del testo. true - la trasformazione linguistica verrà applicata se necessario (valore predefinito). false - la trasformazione linguistica NON verrà applicata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setClippingPathsProcessing {#setClippingPathsProcessing-com.aspose.pdf.TextEditOptions.ClippingPathsProcessingMode-}
Ottiene la modalità per l'elaborazione del percorso di ritaglio del testo modificato.

### setFontReplaceBehavior {#setFontReplaceBehavior-com.aspose.pdf.TextEditOptions.FontReplace-}
Imposta la modalità che definisce il comportamento per gli scenari di sostituzione dei font.

### setLanguageTransformationBehavior {#setLanguageTransformationBehavior-com.aspose.pdf.TextEditOptions.LanguageTransformation-}
Imposta la modalità che definisce il comportamento per gli scenari di trasformazione linguistica.

### setNoCharacterBehavior {#setNoCharacterBehavior-com.aspose.pdf.TextEditOptions.NoCharacterAction-}
Imposta la modalità che definisce il comportamento nel caso in cui i font non contengano i caratteri richiesti.

### setReplacementFont {#setReplacementFont-com.aspose.pdf.Font-}
Ottiene o imposta il font usato per la sostituzione se il font dell'utente non contiene il carattere richiesto

### setToAttemptGetUnderlineFromSource {#setToAttemptGetUnderlineFromSource-boolean-}
```
public void setToAttemptGetUnderlineFromSource(boolean value)
```

<p> Ottiene o imposta il valore che consente la ricerca di sottolineature del testo nella pagina del documento di origine. <p> (Obsoleto) Si prega di utilizzare TextSearchOptions.SearchForTextRelatedGraphics invece di questo. </p>

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |
