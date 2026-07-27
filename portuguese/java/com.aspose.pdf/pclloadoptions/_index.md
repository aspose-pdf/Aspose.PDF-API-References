---
title: "PclLoadOptions"
linktitle: "PclLoadOptions"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa opções para carregar (importar) arquivo PCL em um documento PDF."
type: docs
weight: 3530
url: /pt/java/com.aspose.pdf/pclloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.PclLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.PclLoadOptions

**All Implemented Interfaces:**
IPipelineOptions

```
public final class PclLoadOptions extends LoadOptions implements IPipelineOptions
```

Representa opções para carregar (importar) arquivo PCL em um documento PDF.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [PclLoadOptions](#PclLoadOptions--) | Cria o objeto {@code PclLoadOptions}. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getBatchSize](#getBatchSize--) | Define o tamanho do lote se a conversão em lote for aplicável ao par de formatos de origem e destino. |
| [getConversionEngine](#getConversionEngine--) | Define o mecanismo de conversão que será usado para a conversão |
| [getExceptions](#getExceptions--) | Lista de erros de conversão. |
| [isSupressErrors](#isSupressErrors--) | Obtém ou define o valor booleano que indica se os erros de conversão PCL devem ser suprimidos. |
| [setBatchSize](#setBatchSize-int-) | Define o tamanho do lote se a conversão em lote for aplicável ao par de formatos de origem e destino. |
| [setConversionEngine](#setConversionEngine-int-) | Define o mecanismo de conversão que será usado para a conversão |
| [setSupressErrors](#setSupressErrors-boolean-) | Obtém ou define o valor booleano que indica se os erros de conversão PCL devem ser suprimidos. |

### PclLoadOptions {#PclLoadOptions--}
```
public PclLoadOptions()
```

Cria o objeto {@code PclLoadOptions}.

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

Define o tamanho do lote se a conversão em lote for aplicável ao par de formatos de origem e destino.

**Returns:**
valor int

### getConversionEngine {#getConversionEngine--}
```
public int getConversionEngine()
```

Define o mecanismo de conversão que será usado para a conversão

**Returns:**
Elemento ConversionEngines @see ConversionEngines

### getExceptions {#getExceptions--}
```
public List < Exception > getExceptions()
```

Lista de erros de conversão.

**Returns:**
Lista de exceções

### isSupressErrors {#isSupressErrors--}
```
public boolean isSupressErrors()
```

Obtém ou define o valor booleano que indica se os erros de conversão PCL devem ser suprimidos.

**Returns:**
valor booleano

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

Define o tamanho do lote se a conversão em lote for aplicável ao par de formatos de origem e destino.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setConversionEngine {#setConversionEngine-int-}
```
public void setConversionEngine(int conversionEngine)
```

Define o mecanismo de conversão que será usado para a conversão

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| conversionEngine |  | Elemento ConversionEngines @see ConversionEngines |

### setSupressErrors {#setSupressErrors-boolean-}
```
public void setSupressErrors(boolean supressErrors)
```

Obtém ou define o valor booleano que indica se os erros de conversão PCL devem ser suprimidos.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| supressErrors |  | valor booleano |
