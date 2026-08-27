---
title: "ColorType"
linktitle: "ColorType"
second_title: "Referência da API Aspose.PDF para Java"
description: "Especifica o tipo de cor dos elementos na página."
type: docs
weight: 710
url: /pt/java/com.aspose.pdf/colortype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < ColorType > com.aspose.pdf.ColorType, java.lang.Enum < ColorType >, com.aspose.pdf.ColorType

**All Implemented Interfaces:**
Serializable, Comparable < ColorType >

```
public enum ColorType extends Enum < ColorType >
```

Especifica o tipo de cor dos elementos na página.

## Campos

| Campo | Descrição |
| --- | --- |
| [BlackAndWhite](#BlackAndWhite) | Tipo de cor preto e branco. |
| [Grayscale](#Grayscale) | Tipo de cor em escala de cinza. |
| [Rgb](#Rgb) | Tipo de cor RGB. |
| [Undefined](#Undefined) | Valor de tipo de cor indefinido. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getName](#getName-int-) | <p> Retorna o nome da String para o valor do enum. </p> <hr> Exemplo: <br> {@code String s = ColorType.getName(ColorType.Grayscale); } |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Retorna a constante enum deste tipo com o nome especificado. |
| [values](#values--) | Retorna um array contendo as constantes deste tipo enum, na ordem em que são declaradas. |

### BlackAndWhite {#BlackAndWhite}
```
public static final ColorType BlackAndWhite
```

Tipo de cor preto e branco.

### Grayscale {#Grayscale}
```
public static final ColorType Grayscale
```

Tipo de cor em escala de cinza.

### Rgb {#Rgb}
```
public static final ColorType Rgb
```

Tipo de cor RGB.

### Undefined {#Undefined}
```
public static final ColorType Undefined
```

Valor de tipo de cor indefinido.

### getByValue {#getByValue-int-}
```
public static ColorType getByValue(int value)
```



**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  |  |

### getName {#getName-int-}
```
public static String getName(int value)
```

<p> Retorna o nome da String para o valor do enum. </p> <hr> Exemplo: <br> {@code String s = ColorType.getName(ColorType.Grayscale); }

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Valor do enum |

**Returns:**
Nome do valor

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Retorna a constante enum deste tipo com o nome especificado.

### values {#values--}
```
public static ColorType [] values()
```

Retorna um array contendo as constantes deste tipo enum, na ordem em que são declaradas.

**Returns:**
um array contendo as constantes deste tipo enum, na ordem em que são declaradas
