---
title: "FontEmbeddingOptions"
linktitle: "FontEmbeddingOptions"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Lo standard PDF/A richiede che tutti i caratteri siano incorporati nel documento. Questa classe include flag per i casi in cui non è possibile incorporare alcuni caratteri perché tali caratteri sono assenti."
type: docs
weight: 1680
url: /it/java/com.aspose.pdf/fontembeddingoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontEmbeddingOptions

```
public class FontEmbeddingOptions extends Object
```

Lo standard PDF/A richiede che tutti i font siano incorporati nel documento. Questa classe include flag per i casi in cui non è possibile incorporare alcuni font perché tali font sono assenti sul PC di destinazione.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FontEmbeddingOptions](#FontEmbeddingOptions--) | Inizializza una nuova istanza della classe {@link FontEmbeddingOptions}. Questo costruttore imposta il valore predefinito per la proprietà {@code UseDefaultSubstitution}({@link #getUseDefaultSubstitution}/{@link #setUseDefaultSubstitution(boolean)}) a {@code }. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getUseDefaultSubstitution](#getUseDefaultSubstitution--) | Indica se sostituire i caratteri non incorporati utilizzando la strategia di sostituzione predefinita. Per impostazione predefinita false; |
| [setUseDefaultSubstitution](#setUseDefaultSubstitution-boolean-) | Indica se sostituire i caratteri non incorporati utilizzando la strategia di sostituzione predefinita. Per impostazione predefinita false; |

### FontEmbeddingOptions {#FontEmbeddingOptions--}
```
public FontEmbeddingOptions()
```

Inizializza una nuova istanza della classe {@link FontEmbeddingOptions}. Questo costruttore imposta il valore predefinito per la proprietà {@code UseDefaultSubstitution}({@link #getUseDefaultSubstitution}/{@link #setUseDefaultSubstitution(boolean)}) a {@code }.

### getUseDefaultSubstitution {#getUseDefaultSubstitution--}
```
public boolean getUseDefaultSubstitution()
```

Indica se sostituire i caratteri non incorporati utilizzando la strategia di sostituzione predefinita. Per impostazione predefinita false;

**Returns:**
valore booleano

### setUseDefaultSubstitution {#setUseDefaultSubstitution-boolean-}
```
public void setUseDefaultSubstitution(boolean value)
```

Indica se sostituire i caratteri non incorporati utilizzando la strategia di sostituzione predefinita. Per impostazione predefinita false;

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |
