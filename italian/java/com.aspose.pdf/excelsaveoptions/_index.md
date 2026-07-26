---
title: "ExcelSaveOptions"
linktitle: "ExcelSaveOptions"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Opzioni di salvataggio per l'esportazione in formato Excel"
type: docs
weight: 1260
url: /it/java/com.aspose.pdf/excelsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.ExcelSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.ExcelSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.ExcelSaveOptions

```
public class ExcelSaveOptions extends UnifiedSaveOptions
```

Opzioni di salvataggio per l'esportazione in formato Excel

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ExcelSaveOptions](#ExcelSaveOptions--) | Costruttore |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFormat](#getFormat--) | / * / * Ottiene o imposta il fattore che verrà applicato alla dimensione del carattere di scala (virtuale) durante la conversione in tabella Excel nel / * motore legacy. Impostare un valore più basso facilita la ricerca delle colonne e impedisce la loro unione per alcuni / * documenti. Il valore predefinito è 0.9; impostare il valore a zero consente all'algoritmo di scegliere automaticamente la scala. / * / * / * |
| [getMinimizeTheNumberOfWorksheets](#getMinimizeTheNumberOfWorksheets--) | Imposta true se è necessario ridurre al minimo il numero di fogli di lavoro nella cartella di lavoro risultante. Il valore predefinito è false; significa salvare ogni pagina PDF come foglio di lavoro separato. |
| [isInsertBlankColumnAtFirst](#isInsertBlankColumnAtFirst--) | Imposta false se è necessario sopprimere l'inserimento di una colonna vuota come prima colonna del foglio di lavoro. Il valore predefinito è true; significa che la colonna vuota verrà inserita. |
| [isUniformWorksheets](#isUniformWorksheets--) | Imposta true per utilizzare una divisione uniforme delle colonne nel documento. Il valore predefinito è false; significa che la divisione delle colonne sarà indipendente per ogni pagina. |
| [setFormat](#setFormat-com.aspose.pdf.ExcelSaveOptions.ExcelFormat-) | Formato di output |
| [setInsertBlankColumnAtFirst](#setInsertBlankColumnAtFirst-boolean-) | Imposta false se è necessario sopprimere l'inserimento di una colonna vuota come prima colonna del foglio di lavoro. Il valore predefinito è true; significa che la colonna vuota verrà inserita. |
| [setMinimizeTheNumberOfWorksheets](#setMinimizeTheNumberOfWorksheets-boolean-) | Imposta true se è necessario ridurre al minimo il numero di fogli di lavoro nella cartella di lavoro risultante. Il valore predefinito è false; significa salvare ogni pagina PDF come foglio di lavoro separato. |
| [setUniformWorksheets](#setUniformWorksheets-boolean-) | Definisce il motore di conversione che verrà utilizzato per la conversione |

### ExcelSaveOptions {#ExcelSaveOptions--}
```
public ExcelSaveOptions()
```

Costruttore

### getFormat {#getFormat--}
```
public ExcelSaveOptions.ExcelFormat getFormat()
```

/ * / * Ottiene o imposta il fattore che verrà applicato alla dimensione del carattere di scala (virtuale) durante la conversione in tabella Excel nel / * motore legacy. Impostare un valore più basso facilita la ricerca delle colonne e impedisce la loro unione per alcuni / * documenti. Il valore predefinito è 0.9; impostare il valore a zero consente all'algoritmo di scegliere automaticamente la scala. / * / * / *

**Returns:**
valore double /

### getMinimizeTheNumberOfWorksheets {#getMinimizeTheNumberOfWorksheets--}
```
public boolean getMinimizeTheNumberOfWorksheets()
```

Imposta true se è necessario ridurre al minimo il numero di fogli di lavoro nella cartella di lavoro risultante. Il valore predefinito è false; significa salvare ogni pagina PDF come foglio di lavoro separato.

**Returns:**
valore booleano

### isInsertBlankColumnAtFirst {#isInsertBlankColumnAtFirst--}
```
public boolean isInsertBlankColumnAtFirst()
```

Imposta false se è necessario sopprimere l'inserimento di una colonna vuota come prima colonna del foglio di lavoro. Il valore predefinito è true; significa che la colonna vuota verrà inserita.

**Returns:**
valore booleano

### isUniformWorksheets {#isUniformWorksheets--}
```
public boolean isUniformWorksheets()
```

Imposta true per utilizzare una divisione uniforme delle colonne nel documento. Il valore predefinito è false; significa che la divisione delle colonne sarà indipendente per ogni pagina.

**Returns:**
valore booleano

### setFormat {#setFormat-com.aspose.pdf.ExcelSaveOptions.ExcelFormat-}
Formato di output

### setInsertBlankColumnAtFirst {#setInsertBlankColumnAtFirst-boolean-}
```
public void setInsertBlankColumnAtFirst(boolean value)
```

Imposta false se è necessario sopprimere l'inserimento di una colonna vuota come prima colonna del foglio di lavoro. Il valore predefinito è true; significa che la colonna vuota verrà inserita.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setMinimizeTheNumberOfWorksheets {#setMinimizeTheNumberOfWorksheets-boolean-}
```
public void setMinimizeTheNumberOfWorksheets(boolean value)
```

Imposta true se è necessario ridurre al minimo il numero di fogli di lavoro nella cartella di lavoro risultante. Il valore predefinito è false; significa salvare ogni pagina PDF come foglio di lavoro separato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setUniformWorksheets {#setUniformWorksheets-boolean-}
```
public void setUniformWorksheets(boolean value)
```

Definisce il motore di conversione che verrà utilizzato per la conversione

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  |  |
