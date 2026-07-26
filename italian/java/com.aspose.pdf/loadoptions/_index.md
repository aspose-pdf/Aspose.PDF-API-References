---
title: "LoadOptions"
linktitle: "LoadOptions"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Il tipo LoadOptions contiene il livello di astrazione sulle singole opzioni di caricamento."
type: docs
weight: 2790
url: /it/java/com.aspose.pdf/loadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions

```
public abstract class LoadOptions extends Object
```

Il tipo LoadOptions contiene il livello di astrazione sulle singole opzioni di caricamento.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [LoadOptions](#LoadOptions--) |  |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLoadFormat](#getLoadFormat--) | Rappresenta il formato file che {@code LoadOptions} descrive. |
| [getWarningHandler](#getWarningHandler--) | Callback per gestire eventuali avvisi generati. Il WarningHandler restituisce l'elemento enum ReturnAction che specifica Continue o Abort. Continue è l'azione predefinita e l'operazione di Load continua, tuttavia l'utente può anche restituire Abort, nel qual caso l'operazione di Load dovrebbe terminare. |
| [isDisableFontLicenseVerifications](#isDisableFontLicenseVerifications--) | Ottiene o imposta il flag per disabilitare qualsiasi restrizione di licenza per tutti i font durante il caricamento del file. Quando {@code }, consente di eseguire operazioni con un font che sono proibite da una licenza di quel font, ad esempio consente di incorporare un font in un documento PDF anche se le regole di licenza disabilitano l'incorporamento per questo font. Per impostazione predefinita {@code }. Prestare attenzione quando si utilizza questo flag. Quando è impostato significa che la persona che lo imposta si assume tutta la responsabilità di possibili violazioni di licenza o legge. Quindi lo fa a proprio rischio. Si raccomanda vivamente di utilizzare questo flag solo quando si è pienamente certi di non violare la legge sul diritto d'autore. |
| [setDisableFontLicenseVerifications](#setDisableFontLicenseVerifications-boolean-) | Ottiene o imposta il flag per disabilitare qualsiasi restrizione di licenza per tutti i font durante il caricamento del file. Quando {@code }, consente di eseguire operazioni con un font che sono proibite da una licenza di quel font, ad esempio consente di incorporare un font in un documento PDF anche se le regole di licenza disabilitano l'incorporamento per questo font. Per impostazione predefinita {@code }. Prestare attenzione quando si utilizza questo flag. Quando è impostato significa che la persona che lo imposta si assume tutta la responsabilità di possibili violazioni di licenza o legge. Quindi lo fa a proprio rischio. Si raccomanda vivamente di utilizzare questo flag solo quando si è pienamente certi di non violare la legge sul diritto d'autore. |
| [setWarningHandler](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Callback per gestire eventuali avvisi generati. Il WarningHandler restituisce l'elemento enum ReturnAction che specifica Continue o Abort. Continue è l'azione predefinita e l'operazione di Load continua, tuttavia l'utente può anche restituire Abort, nel qual caso l'operazione di Load dovrebbe terminare. |

### LoadOptions {#LoadOptions--}
```
public LoadOptions()
```



### getLoadFormat {#getLoadFormat--}
```
public LoadFormat getLoadFormat()
```

Rappresenta il formato file che {@code LoadOptions} descrive.

**Returns:**
Elemento LoadFormat @see LoadFormat

### getWarningHandler {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```

Callback per gestire eventuali avvisi generati. Il WarningHandler restituisce l'elemento enum ReturnAction che specifica Continue o Abort. Continue è l'azione predefinita e l'operazione di Load continua, tuttavia l'utente può anche restituire Abort, nel qual caso l'operazione di Load dovrebbe terminare.

**Returns:**
Valore IWarningCallback

### isDisableFontLicenseVerifications {#isDisableFontLicenseVerifications--}
```
public final boolean isDisableFontLicenseVerifications()
```

Ottiene o imposta il flag per disabilitare qualsiasi restrizione di licenza per tutti i font durante il caricamento del file. Quando {@code }, consente di eseguire operazioni con un font che sono proibite da una licenza di quel font, ad esempio consente di incorporare un font in un documento PDF anche se le regole di licenza disabilitano l'incorporamento per questo font. Per impostazione predefinita {@code }. Prestare attenzione quando si utilizza questo flag. Quando è impostato significa che la persona che lo imposta si assume tutta la responsabilità di possibili violazioni di licenza o legge. Quindi lo fa a proprio rischio. Si raccomanda vivamente di utilizzare questo flag solo quando si è pienamente certi di non violare la legge sul diritto d'autore.

**Returns:**
valore booleano

### setDisableFontLicenseVerifications {#setDisableFontLicenseVerifications-boolean-}
```
public final void setDisableFontLicenseVerifications(boolean value)
```

Ottiene o imposta il flag per disabilitare qualsiasi restrizione di licenza per tutti i font durante il caricamento del file. Quando {@code }, consente di eseguire operazioni con un font che sono proibite da una licenza di quel font, ad esempio consente di incorporare un font in un documento PDF anche se le regole di licenza disabilitano l'incorporamento per questo font. Per impostazione predefinita {@code }. Prestare attenzione quando si utilizza questo flag. Quando è impostato significa che la persona che lo imposta si assume tutta la responsabilità di possibili violazioni di licenza o legge. Quindi lo fa a proprio rischio. Si raccomanda vivamente di utilizzare questo flag solo quando si è pienamente certi di non violare la legge sul diritto d'autore.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setWarningHandler {#setWarningHandler-com.aspose.pdf.WarningCallback-}
Callback per gestire eventuali avvisi generati. Il WarningHandler restituisce l'elemento enum ReturnAction che specifica Continue o Abort. Continue è l'azione predefinita e l'operazione di Load continua, tuttavia l'utente può anche restituire Abort, nel qual caso l'operazione di Load dovrebbe terminare.
