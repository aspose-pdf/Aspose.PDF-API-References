---
title: "ExportFieldsOptions"
linktitle: "ExportFieldsOptions"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta la classe base delle opzioni per l'esportazione dei campi modulo."
type: docs
weight: 1310
url: /it/java/com.aspose.pdf/exportfieldsoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExportFieldsOptions

```
public abstract class ExportFieldsOptions extends Object
```

Rappresenta la classe base delle opzioni per l'esportazione dei campi modulo.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ExportFieldsOptions](#ExportFieldsOptions--) |  |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getExportPasswordValue](#getExportPasswordValue--) | Ottiene o imposta un valore che indica se il valore della password deve essere esportato. Valore: {@code true} se il valore della password deve essere esportato; altrimenti, {@code false}. |
| [getFieldSelector](#getFieldSelector--) | Ottiene un delegato che determina se un campo particolare deve essere esportato. Se il delegato è {@code null}, tutti i campi sono esportati (comportamento predefinito). |
| [setExportPasswordValue](#setExportPasswordValue-boolean-) | Ottiene o imposta un valore che indica se il valore della password deve essere esportato. Valore: {@code true} se il valore della password deve essere esportato; altrimenti, {@code false}. |
| [setFieldSelector](#setFieldSelector-com.aspose.ms.System.Predicate-) | Imposta un delegato che determina se un campo particolare deve essere esportato. |

### ExportFieldsOptions {#ExportFieldsOptions--}
```
public ExportFieldsOptions()
```



### getExportPasswordValue {#getExportPasswordValue--}
```
public final boolean getExportPasswordValue()
```

Ottiene o imposta un valore che indica se il valore della password deve essere esportato. Valore: {@code true} se il valore della password deve essere esportato; altrimenti, {@code false}.

**Returns:**
valore booleano

### getFieldSelector {#getFieldSelector--}
```
public final com.aspose.ms.System.Predicate< Field > getFieldSelector()
```

Ottiene un delegato che determina se un campo particolare deve essere esportato. Se il delegato è {@code null}, tutti i campi sono esportati (comportamento predefinito).

**Returns:**
un delegato che determina se un campo particolare deve essere esportato.

### setExportPasswordValue {#setExportPasswordValue-boolean-}
```
public final void setExportPasswordValue(boolean value)
```

Ottiene o imposta un valore che indica se il valore della password deve essere esportato. Valore: {@code true} se il valore della password deve essere esportato; altrimenti, {@code false}.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setFieldSelector {#setFieldSelector-com.aspose.ms.System.Predicate-}
Imposta un delegato che determina se un campo particolare deve essere esportato.
