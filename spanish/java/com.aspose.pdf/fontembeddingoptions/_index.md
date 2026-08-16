---
title: "FontEmbeddingOptions"
linktitle: "FontEmbeddingOptions"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "El estándar PDF/A requiere que todas las fuentes se incrusten en el documento. Esta clase incluye indicadores para los casos en que no es posible incrustar alguna fuente porque dicha fuente está ausente."
type: docs
weight: 1680
url: /es/java/com.aspose.pdf/fontembeddingoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontEmbeddingOptions

```
public class FontEmbeddingOptions extends Object
```

El estándar PDF/A requiere que todas las fuentes estén incrustadas en el documento. Esta clase incluye indicadores para los casos en que no es posible incrustar alguna fuente porque dicha fuente está ausente en el PC de destino.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [FontEmbeddingOptions](#FontEmbeddingOptions--) | Inicializa una nueva instancia de la clase {@link FontEmbeddingOptions}. Este constructor establece el valor predeterminado para la propiedad {@code UseDefaultSubstitution}({@link #getUseDefaultSubstitution}/{@link #setUseDefaultSubstitution(boolean)}) a {@code }. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getUseDefaultSubstitution](#getUseDefaultSubstitution--) | Indica si se debe sustituir la fuente no incrustada usando la estrategia de sustitución de fuentes predeterminada. Por defecto, false; |
| [setUseDefaultSubstitution](#setUseDefaultSubstitution-boolean-) | Indica si se debe sustituir la fuente no incrustada usando la estrategia de sustitución de fuentes predeterminada. Por defecto, false; |

### FontEmbeddingOptions {#FontEmbeddingOptions--}
```
public FontEmbeddingOptions()
```

Inicializa una nueva instancia de la clase {@link FontEmbeddingOptions}. Este constructor establece el valor predeterminado para la propiedad {@code UseDefaultSubstitution}({@link #getUseDefaultSubstitution}/{@link #setUseDefaultSubstitution(boolean)}) a {@code }.

### getUseDefaultSubstitution {#getUseDefaultSubstitution--}
```
public boolean getUseDefaultSubstitution()
```

Indica si se debe sustituir la fuente no incrustada usando la estrategia de sustitución de fuentes predeterminada. Por defecto, false;

**Returns:**
valor booleano

### setUseDefaultSubstitution {#setUseDefaultSubstitution-boolean-}
```
public void setUseDefaultSubstitution(boolean value)
```

Indica si se debe sustituir la fuente no incrustada usando la estrategia de sustitución de fuentes predeterminada. Por defecto, false;

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |
