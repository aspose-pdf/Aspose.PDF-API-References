---
title: "SaveOptions"
linktitle: "SaveOptions"
second_title: "Referência da API Aspose.PDF para Java"
description: "O tipo SaveOptions mantém nível de abstração nas opções individuais de salvamento."
type: docs
weight: 4370
url: /pt/java/com.aspose.pdf/saveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions

```
public abstract class SaveOptions extends Object
```

O tipo SaveOptions mantém nível de abstração nas opções individuais de salvamento.

## Métodos

| Método | Descrição |
| --- | --- |
| [getSaveFormat](#getSaveFormat--) | Formato de salvamento de dados. |
| [getWarningHandler](#getWarningHandler--) | Retorno de chamada para lidar com quaisquer avisos gerados. O WarningHandler devolve o item enum ReturnAction especificando Continue ou Abort. Continue é a ação padrão e a operação de Save continua, porém o usuário também pode devolver Abort, caso em que a operação de Save deve ser interrompida. |
| [isCacheGlyphs](#isCacheGlyphs--) | Obtém ou define o valor booleano que indica se os glifos de fonte serão armazenados em cache ao preparar páginas aps. Melhora o desempenho da conversão de PDF para outros formatos, mas aumenta o consumo de memória. |
| [isCloseResponse](#isCloseResponse--) | Obtém o valor booleano que indica se o objeto Response será fechado após o documento ser salvo na resposta. |
| [setCacheGlyphs](#setCacheGlyphs-boolean-) | Obtém ou define o valor booleano que indica se os glifos de fonte serão armazenados em cache ao preparar páginas aps. Melhora o desempenho da conversão de PDF para outros formatos, mas aumenta o consumo de memória. |
| [setCloseResponse](#setCloseResponse-boolean-) | Define o valor booleano que indica se o objeto Response será fechado após o documento ser salvo na resposta. |
| [setWarningHandler](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Retorno de chamada para lidar com quaisquer avisos gerados. O WarningHandler devolve o item enum ReturnAction especificando Continue ou Abort. Continue é a ação padrão e a operação de Save continua, porém o usuário também pode devolver Abort, caso em que a operação de Save deve ser interrompida. |

### getSaveFormat {#getSaveFormat--}
```
public SaveFormat getSaveFormat()
```

Formato de salvamento de dados.

**Returns:**
Valor SaveFormat @see SaveFormat

### getWarningHandler {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```

Retorno de chamada para lidar com quaisquer avisos gerados. O WarningHandler devolve o item enum ReturnAction especificando Continue ou Abort. Continue é a ação padrão e a operação de Save continua, porém o usuário também pode devolver Abort, caso em que a operação de Save deve ser interrompida.

**Returns:**
Valor IWarningCallback

### isCacheGlyphs {#isCacheGlyphs--}
```
public final boolean isCacheGlyphs()
```

Obtém ou define o valor booleano que indica se os glifos de fonte serão armazenados em cache ao preparar páginas aps. Melhora o desempenho da conversão de PDF para outros formatos, mas aumenta o consumo de memória.

**Returns:**
valor booleano

### isCloseResponse {#isCloseResponse--}
```
public boolean isCloseResponse()
```

Obtém o valor booleano que indica se o objeto Response será fechado após o documento ser salvo na resposta.

**Returns:**
valor booleano

### setCacheGlyphs {#setCacheGlyphs-boolean-}
```
public final void setCacheGlyphs(boolean value)
```

Obtém ou define o valor booleano que indica se os glifos de fonte serão armazenados em cache ao preparar páginas aps. Melhora o desempenho da conversão de PDF para outros formatos, mas aumenta o consumo de memória.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setCloseResponse {#setCloseResponse-boolean-}
```
public void setCloseResponse(boolean value)
```

Define o valor booleano que indica se o objeto Response será fechado após o documento ser salvo na resposta.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setWarningHandler {#setWarningHandler-com.aspose.pdf.WarningCallback-}
Retorno de chamada para lidar com quaisquer avisos gerados. O WarningHandler devolve o item enum ReturnAction especificando Continue ou Abort. Continue é a ação padrão e a operação de Save continua, porém o usuário também pode devolver Abort, caso em que a operação de Save deve ser interrompida.
