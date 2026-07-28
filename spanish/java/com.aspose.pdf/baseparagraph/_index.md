---
title: "BaseParagraph"
linktitle: "BaseParagraph"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa un objeto base abstracto que puede añadirse a la página (doc.Paragraphs.Add())."
type: docs
weight: 280
url: /es/java/com.aspose.pdf/baseparagraph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public abstract class BaseParagraph extends Object implements com.aspose.ms.System.ICloneable
```

Representa un objeto base abstracto que puede añadirse a la página (doc.Paragraphs.Add()).

## Constructores

| Constructor | Descripción |
| --- | --- |
| [BaseParagraph](#BaseParagraph--) |  |

## Métodos

| Método | Descripción |
| --- | --- |
| [deepClone](#deepClone--) | Clona esta instancia. Método virtual. Siempre devuelve null. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Obtiene una alineación horizontal del párrafo |
| [getHyperlink](#getHyperlink--) | / * / * Obtiene o establece si un párrafo es nota al pie. El valor predeterminado es false.(para generación de pdf) / * / * |
| [getMargin](#getMargin--) | Obtiene un margen exterior para el párrafo (para generación de pdf) |
| [getVerticalAlignment](#getVerticalAlignment--) | Obtiene una alineación vertical del párrafo |
| [getZIndex](#getZIndex--) | Obtiene un valor int que indica el orden Z del gráfico. Un gráfico con ZIndex mayor se colocará sobre el gráfico con ZIndex menor. ZIndex puede ser negativo. Un gráfico con ZIndex negativo se colocará detrás del texto en la página. |
| [isFirstParagraphInColumn](#isFirstParagraphInColumn--) | Obtiene o establece un valor bool que indica si este párrafo estará en la siguiente columna. El valor predeterminado es false.(para generación de pdf) |
| [isInLineParagraph](#isInLineParagraph--) | Obtiene si un párrafo es inline. El valor predeterminado es false.(para generación de pdf) |
| [isInNewPage](#isInNewPage--) | Obtiene un valor bool que fuerza que este párrafo se genere en una nueva página. El valor predeterminado es false. (para generación de pdf) |
| [isKeptWithNext](#isKeptWithNext--) | Obtiene un valor booleano que indica si el párrafo actual permanece en la misma página junto con el siguiente párrafo. El valor predeterminado es false. (para generación de pdf) |
| [setFirstParagraphInColumn](#setFirstParagraphInColumn-boolean-) | Obtiene o establece un valor bool que indica si este párrafo estará en la siguiente columna. El valor predeterminado es false.(para generación de pdf) |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Establece una alineación horizontal del párrafo |
| [setHyperlink](#setHyperlink-com.aspose.pdf.Hyperlink-) | Establece un hipervínculo (para generador de pdf). |
| [setInLineParagraph](#setInLineParagraph-boolean-) | Establece que un párrafo es en línea. El valor predeterminado es false. (para generación de pdf) |
| [setInNewPage](#setInNewPage-boolean-) | Establece un valor booleano que fuerza que este párrafo se genere en una nueva página. El valor predeterminado es false. (para generación de pdf) |
| [setKeptWithNext](#setKeptWithNext-boolean-) | Establece un valor booleano que indica si el párrafo actual permanece en la misma página junto con el siguiente párrafo. El valor predeterminado es false. (para generación de pdf) |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Establece un margen exterior para el párrafo (para generación de pdf) |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Establece una alineación vertical del párrafo |
| [setZIndex](#setZIndex-int-) | Establece un valor int que indica el orden Z del gráfico. Un gráfico con ZIndex mayor se colocará sobre el gráfico con ZIndex menor. ZIndex puede ser negativo. Un gráfico con ZIndex negativo se colocará detrás del texto en la página. |

### BaseParagraph {#BaseParagraph--}
```
public BaseParagraph()
```



### deepClone {#deepClone--}
```
public Object deepClone()
```

Clona esta instancia. Método virtual. Siempre devuelve null.

**Returns:**
Nulo

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Obtiene una alineación horizontal del párrafo

**Returns:**
Valor HorizontalAlignment @see HorizontalAlignment

### getHyperlink {#getHyperlink--}
```
public Hyperlink getHyperlink()
```

/ * / * Obtiene o establece si un párrafo es nota al pie. El valor predeterminado es false.(para generación de pdf) / * / *

**Returns:**
valor booleano /

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

Obtiene un margen exterior para el párrafo (para generación de pdf)

**Returns:**
valor MarginInfo

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Obtiene una alineación vertical del párrafo

**Returns:**
Elemento VerticalAlignment @see VerticalAlignment

### getZIndex {#getZIndex--}
```
public int getZIndex()
```

Obtiene un valor int que indica el orden Z del gráfico. Un gráfico con ZIndex mayor se colocará sobre el gráfico con ZIndex menor. ZIndex puede ser negativo. Un gráfico con ZIndex negativo se colocará detrás del texto en la página.

**Returns:**
valor int

### isFirstParagraphInColumn {#isFirstParagraphInColumn--}
```
public boolean isFirstParagraphInColumn()
```

Obtiene o establece un valor bool que indica si este párrafo estará en la siguiente columna. El valor predeterminado es false.(para generación de pdf)

**Returns:**
valor booleano

### isInLineParagraph {#isInLineParagraph--}
```
public boolean isInLineParagraph()
```

Obtiene si un párrafo es inline. El valor predeterminado es false.(para generación de pdf)

**Returns:**
valor booleano

### isInNewPage {#isInNewPage--}
```
public boolean isInNewPage()
```

Obtiene un valor bool que fuerza que este párrafo se genere en una nueva página. El valor predeterminado es false. (para generación de pdf)

**Returns:**
valor booleano

### isKeptWithNext {#isKeptWithNext--}
```
public boolean isKeptWithNext()
```

Obtiene un valor booleano que indica si el párrafo actual permanece en la misma página junto con el siguiente párrafo. El valor predeterminado es false. (para generación de pdf)

**Returns:**
valor booleano

### setFirstParagraphInColumn {#setFirstParagraphInColumn-boolean-}
```
public void setFirstParagraphInColumn(boolean value)
```

Obtiene o establece un valor bool que indica si este párrafo estará en la siguiente columna. El valor predeterminado es false.(para generación de pdf)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Establece una alineación horizontal del párrafo

### setHyperlink {#setHyperlink-com.aspose.pdf.Hyperlink-}
Establece un hipervínculo (para generador de pdf).

### setInLineParagraph {#setInLineParagraph-boolean-}
```
public void setInLineParagraph(boolean value)
```

Establece que un párrafo es en línea. El valor predeterminado es false. (para generación de pdf)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setInNewPage {#setInNewPage-boolean-}
```
public void setInNewPage(boolean value)
```

Establece un valor booleano que fuerza que este párrafo se genere en una nueva página. El valor predeterminado es false. (para generación de pdf)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setKeptWithNext {#setKeptWithNext-boolean-}
```
public final void setKeptWithNext(boolean value)
```

Establece un valor booleano que indica si el párrafo actual permanece en la misma página junto con el siguiente párrafo. El valor predeterminado es false. (para generación de pdf)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Establece un margen exterior para el párrafo (para generación de pdf)

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Establece una alineación vertical del párrafo

### setZIndex {#setZIndex-int-}
```
public void setZIndex(int value)
```

Establece un valor int que indica el orden Z del gráfico. Un gráfico con ZIndex mayor se colocará sobre el gráfico con ZIndex menor. ZIndex puede ser negativo. Un gráfico con ZIndex negativo se colocará detrás del texto en la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor int |
