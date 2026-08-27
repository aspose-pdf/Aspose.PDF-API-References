---
title: "ExcelSaveOptions"
linktitle: "ExcelSaveOptions"
second_title: "Referência da API Aspose.PDF para Java"
description: "Opções de salvamento para exportação para o formato Excel"
type: docs
weight: 1260
url: /pt/java/com.aspose.pdf/excelsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.ExcelSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.ExcelSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.ExcelSaveOptions

```
public class ExcelSaveOptions extends UnifiedSaveOptions
```

Opções de salvamento para exportação para o formato Excel

## Construtores

| Construtor | Descrição |
| --- | --- |
| [ExcelSaveOptions](#ExcelSaveOptions--) | Construtor |

## Métodos

| Método | Descrição |
| --- | --- |
| [getFormat](#getFormat--) | / * / * Obtém ou define o fator que será aplicado ao tamanho da fonte de escala (virtual) durante a conversão para tabela Excel no / * mecanismo legado. Definir um valor menor facilita a busca por colunas e impede a mesclagem delas em alguns / * documentos. Valor padrão é 0.9; Definir o valor como zero permite que o algoritmo escolha a escala automaticamente. / * / * / * |
| [getMinimizeTheNumberOfWorksheets](#getMinimizeTheNumberOfWorksheets--) | Defina como verdadeiro se precisar minimizar o número de planilhas no livro de trabalho resultante. O valor padrão é falso; isso significa salvar cada página PDF como planilha separada. |
| [isInsertBlankColumnAtFirst](#isInsertBlankColumnAtFirst--) | Defina como false se precisar suprimir a inserção de coluna em branco como a primeira coluna da planilha. O valor padrão é true; isso significa que a coluna em branco será inserida. |
| [isUniformWorksheets](#isUniformWorksheets--) | Defina como true para usar divisão uniforme de colunas ao longo do documento. O valor padrão é false; isso significa que a divisão de colunas será independente para cada página. |
| [setFormat](#setFormat-com.aspose.pdf.ExcelSaveOptions.ExcelFormat-) | Formato de saída |
| [setInsertBlankColumnAtFirst](#setInsertBlankColumnAtFirst-boolean-) | Defina como false se precisar suprimir a inserção de coluna em branco como a primeira coluna da planilha. O valor padrão é true; isso significa que a coluna em branco será inserida. |
| [setMinimizeTheNumberOfWorksheets](#setMinimizeTheNumberOfWorksheets-boolean-) | Defina como verdadeiro se precisar minimizar o número de planilhas no livro de trabalho resultante. O valor padrão é falso; isso significa salvar cada página PDF como planilha separada. |
| [setUniformWorksheets](#setUniformWorksheets-boolean-) | Define o mecanismo de conversão que será usado para a conversão |

### ExcelSaveOptions {#ExcelSaveOptions--}
```
public ExcelSaveOptions()
```

Construtor

### getFormat {#getFormat--}
```
public ExcelSaveOptions.ExcelFormat getFormat()
```

/ * / * Obtém ou define o fator que será aplicado ao tamanho da fonte de escala (virtual) durante a conversão para tabela Excel no / * mecanismo legado. Definir um valor menor facilita a busca por colunas e impede a mesclagem delas em alguns / * documentos. Valor padrão é 0.9; Definir o valor como zero permite que o algoritmo escolha a escala automaticamente. / * / * / *

**Returns:**
valor double /

### getMinimizeTheNumberOfWorksheets {#getMinimizeTheNumberOfWorksheets--}
```
public boolean getMinimizeTheNumberOfWorksheets()
```

Defina como verdadeiro se precisar minimizar o número de planilhas no livro de trabalho resultante. O valor padrão é falso; isso significa salvar cada página PDF como planilha separada.

**Returns:**
valor booleano

### isInsertBlankColumnAtFirst {#isInsertBlankColumnAtFirst--}
```
public boolean isInsertBlankColumnAtFirst()
```

Defina como false se precisar suprimir a inserção de coluna em branco como a primeira coluna da planilha. O valor padrão é true; isso significa que a coluna em branco será inserida.

**Returns:**
valor booleano

### isUniformWorksheets {#isUniformWorksheets--}
```
public boolean isUniformWorksheets()
```

Defina como true para usar divisão uniforme de colunas ao longo do documento. O valor padrão é false; isso significa que a divisão de colunas será independente para cada página.

**Returns:**
valor booleano

### setFormat {#setFormat-com.aspose.pdf.ExcelSaveOptions.ExcelFormat-}
Formato de saída

### setInsertBlankColumnAtFirst {#setInsertBlankColumnAtFirst-boolean-}
```
public void setInsertBlankColumnAtFirst(boolean value)
```

Defina como false se precisar suprimir a inserção de coluna em branco como a primeira coluna da planilha. O valor padrão é true; isso significa que a coluna em branco será inserida.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setMinimizeTheNumberOfWorksheets {#setMinimizeTheNumberOfWorksheets-boolean-}
```
public void setMinimizeTheNumberOfWorksheets(boolean value)
```

Defina como verdadeiro se precisar minimizar o número de planilhas no livro de trabalho resultante. O valor padrão é falso; isso significa salvar cada página PDF como planilha separada.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setUniformWorksheets {#setUniformWorksheets-boolean-}
```
public void setUniformWorksheets(boolean value)
```

Define o mecanismo de conversão que será usado para a conversão

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  |  |
