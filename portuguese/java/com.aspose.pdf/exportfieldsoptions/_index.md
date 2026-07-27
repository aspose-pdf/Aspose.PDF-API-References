---
title: "ExportFieldsOptions"
linktitle: "ExportFieldsOptions"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa a classe base de opções para exportação de campos de formulário."
type: docs
weight: 1310
url: /pt/java/com.aspose.pdf/exportfieldsoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExportFieldsOptions

```
public abstract class ExportFieldsOptions extends Object
```

Representa a classe base de opções para exportação de campos de formulário.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [ExportFieldsOptions](#ExportFieldsOptions--) |  |

## Métodos

| Método | Descrição |
| --- | --- |
| [getExportPasswordValue](#getExportPasswordValue--) | Obtém ou define um valor que indica se o valor da senha deve ser exportado. Valor: {@code true} se o valor da senha deve ser exportado; caso contrário, {@code false}. |
| [getFieldSelector](#getFieldSelector--) | Obtém um delegate que determina se um campo específico deve ser exportado. Se o delegate for {@code null}, todos os campos são exportados (comportamento padrão). |
| [setExportPasswordValue](#setExportPasswordValue-boolean-) | Obtém ou define um valor que indica se o valor da senha deve ser exportado. Valor: {@code true} se o valor da senha deve ser exportado; caso contrário, {@code false}. |
| [setFieldSelector](#setFieldSelector-com.aspose.ms.System.Predicate-) | Define um delegate que determina se um campo específico deve ser exportado. |

### ExportFieldsOptions {#ExportFieldsOptions--}
```
public ExportFieldsOptions()
```



### getExportPasswordValue {#getExportPasswordValue--}
```
public final boolean getExportPasswordValue()
```

Obtém ou define um valor que indica se o valor da senha deve ser exportado. Valor: {@code true} se o valor da senha deve ser exportado; caso contrário, {@code false}.

**Returns:**
valor booleano

### getFieldSelector {#getFieldSelector--}
```
public final com.aspose.ms.System.Predicate< Field > getFieldSelector()
```

Obtém um delegate que determina se um campo específico deve ser exportado. Se o delegate for {@code null}, todos os campos são exportados (comportamento padrão).

**Returns:**
um delegate que determina se um campo específico deve ser exportado.

### setExportPasswordValue {#setExportPasswordValue-boolean-}
```
public final void setExportPasswordValue(boolean value)
```

Obtém ou define um valor que indica se o valor da senha deve ser exportado. Valor: {@code true} se o valor da senha deve ser exportado; caso contrário, {@code false}.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setFieldSelector {#setFieldSelector-com.aspose.ms.System.Predicate-}
Define um delegate que determina se um campo específico deve ser exportado.
