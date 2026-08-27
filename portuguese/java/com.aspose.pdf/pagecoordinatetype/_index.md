---
title: "PageCoordinateType"
linktitle: "PageCoordinateType"
second_title: "Referência da API Aspose.PDF para Java"
description: "Descreve o tipo de coordenada da página. MediaBox = 0 CropBox = 1"
type: docs
weight: 3350
url: /pt/java/com.aspose.pdf/pagecoordinatetype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < PageCoordinateType > com.aspose.pdf.PageCoordinateType, java.lang.Enum < PageCoordinateType >, com.aspose.pdf.PageCoordinateType

**All Implemented Interfaces:**
Serializable, Comparable < PageCoordinateType >

```
public enum PageCoordinateType extends Enum < PageCoordinateType >
```

Descreve o tipo de coordenada da página. MediaBox = 0 CropBox = 1

## Campos

| Campo | Descrição |
| --- | --- |
| [CropBox](#CropBox) | O CropBox define a região para a qual o conteúdo da página será recortado. |
| [MediaBox](#MediaBox) | O MediaBox é usado para especificar a largura e a altura da página. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Retorna a constante enum deste tipo com o nome especificado. |
| [values](#values--) | Retorna um array contendo as constantes deste tipo enum, na ordem em que são declaradas. |

### CropBox {#CropBox}
```
public static final PageCoordinateType CropBox
```

O CropBox define a região para a qual o conteúdo da página será recortado.

### MediaBox {#MediaBox}
```
public static final PageCoordinateType MediaBox
```

O MediaBox é usado para especificar a largura e a altura da página.

### getByValue {#getByValue-int-}
```
public static PageCoordinateType getByValue(int value)
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
public static PageCoordinateType [] values()
```

Retorna um array contendo as constantes deste tipo enum, na ordem em que são declaradas.

**Returns:**
um array contendo as constantes deste tipo enum, na ordem em que são declaradas
