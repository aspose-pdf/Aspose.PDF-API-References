---
title: "ExtractImageMode"
linktitle: "ExtractImageMode"
second_title: "Referência da API Aspose.PDF para Java"
description: "Define diferentes modos que podem ser usados ao extrair imagens de documentos."
type: docs
weight: 1360
url: /pt/java/com.aspose.pdf/extractimagemode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < ExtractImageMode > com.aspose.pdf.ExtractImageMode, java.lang.Enum < ExtractImageMode >, com.aspose.pdf.ExtractImageMode

**All Implemented Interfaces:**
Serializable, Comparable < ExtractImageMode >

```
public enum ExtractImageMode extends Enum < ExtractImageMode >
```

Define diferentes modos que podem ser usados ao extrair imagens de documentos.

## Campos

| Campo | Descrição |
| --- | --- |
| [ActuallyUsed](#ActuallyUsed) | Define o modo de extração de imagens no qual apenas as imagens que são realmente exibidas em uma página são extraídas. |
| [DefinedInResources](#DefinedInResources) | Define o modo de extração de imagens no qual todas as imagens definidas nos recursos de uma página específica são extraídas. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Retorna a constante enum deste tipo com o nome especificado. |
| [values](#values--) | Retorna um array contendo as constantes deste tipo enum, na ordem em que são declaradas. |

### ActuallyUsed {#ActuallyUsed}
```
public static final ExtractImageMode ActuallyUsed
```

Define o modo de extração de imagens no qual apenas as imagens que são realmente exibidas em uma página são extraídas.

### DefinedInResources {#DefinedInResources}
```
public static final ExtractImageMode DefinedInResources
```

Define o modo de extração de imagens no qual todas as imagens definidas nos recursos de uma página específica são extraídas.

### getByValue {#getByValue-int-}
```
public static ExtractImageMode getByValue(int value)
```



**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Retorna a constante enum deste tipo com o nome especificado.

### values {#values--}
```
public static ExtractImageMode [] values()
```

Retorna um array contendo as constantes deste tipo enum, na ordem em que são declaradas.

**Returns:**
um array contendo as constantes deste tipo enum, na ordem em que são declaradas
