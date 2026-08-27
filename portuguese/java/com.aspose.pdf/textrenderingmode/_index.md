---
title: "TextRenderingMode"
linktitle: "TextRenderingMode"
second_title: "Referência da API Aspose.PDF para Java"
description: "O modo de renderização de texto, Tmode, determina se a exibição do texto deve causar contorno de glifos traçado, preenchido, usado como limite de recorte ou alguma combinação dos três."
type: docs
weight: 5240
url: /pt/java/com.aspose.pdf/textrenderingmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < TextRenderingMode > com.aspose.pdf.TextRenderingMode, java.lang.Enum < TextRenderingMode >, com.aspose.pdf.TextRenderingMode

**All Implemented Interfaces:**
Serializable, Comparable < TextRenderingMode >

```
public enum TextRenderingMode extends Enum < TextRenderingMode >
```

O modo de renderização de texto, Tmode, determina se a exibição do texto deve causar contorno de glifos traçado, preenchido, usado como limite de recorte ou alguma combinação dos três.

## Campos

| Campo | Descrição |
| --- | --- |
| [AddPathToClipping](#AddPathToClipping) | Adicionar texto ao caminho para recorte. |
| [FillText](#FillText) | Preencher texto. |
| [FillTextAndAddPathToClipping](#FillTextAndAddPathToClipping) | Preencher texto e adicionar ao caminho para recorte (veja 9.3.6, "Text Rendering Mode,"). |
| [FillThenStrokeText](#FillThenStrokeText) | Preencher, então traçar texto. |
| [FillThenStrokeTextAndAddPathToClipping](#FillThenStrokeTextAndAddPathToClipping) | Preencher, então traçar texto e adicionar ao caminho para recorte. |
| [Invisible](#Invisible) | Nem preencher nem traçar texto (invisível). |
| [StrokeText](#StrokeText) | Traçar texto. |
| [StrokeTextAndAddPathToClipping](#StrokeTextAndAddPathToClipping) | Traçar texto e adicionar ao caminho para recorte. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-int-) |  |
| [valueOf](#valueOf-java.lang.String-) | Retorna a constante enum deste tipo com o nome especificado. |
| [values](#values--) | Retorna um array contendo as constantes deste tipo enum, na ordem em que são declaradas. |

### AddPathToClipping {#AddPathToClipping}
```
public static final TextRenderingMode AddPathToClipping
```

Adicionar texto ao caminho para recorte.

### FillText {#FillText}
```
public static final TextRenderingMode FillText
```

Preencher texto.

### FillTextAndAddPathToClipping {#FillTextAndAddPathToClipping}
```
public static final TextRenderingMode FillTextAndAddPathToClipping
```

Preencher texto e adicionar ao caminho para recorte (veja 9.3.6, "Text Rendering Mode,").

### FillThenStrokeText {#FillThenStrokeText}
```
public static final TextRenderingMode FillThenStrokeText
```

Preencher, então traçar texto.

### FillThenStrokeTextAndAddPathToClipping {#FillThenStrokeTextAndAddPathToClipping}
```
public static final TextRenderingMode FillThenStrokeTextAndAddPathToClipping
```

Preencher, então traçar texto e adicionar ao caminho para recorte.

### Invisible {#Invisible}
```
public static final TextRenderingMode Invisible
```

Nem preencher nem traçar texto (invisível).

### StrokeText {#StrokeText}
```
public static final TextRenderingMode StrokeText
```

Traçar texto.

### StrokeTextAndAddPathToClipping {#StrokeTextAndAddPathToClipping}
```
public static final TextRenderingMode StrokeTextAndAddPathToClipping
```

Traçar texto e adicionar ao caminho para recorte.

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-int-}
```
public static TextRenderingMode valueOf(int value)
```



**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  |  |

### valueOf {#valueOf-java.lang.String-}
Retorna a constante enum deste tipo com o nome especificado.

### values {#values--}
```
public static TextRenderingMode [] values()
```

Retorna um array contendo as constantes deste tipo enum, na ordem em que são declaradas.

**Returns:**
um array contendo as constantes deste tipo enum, na ordem em que são declaradas
