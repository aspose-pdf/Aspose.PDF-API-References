---
title: "Group"
linktitle: "Group"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Una clase de atributos de grupo que especifica los atributos del grupo de página para su uso en el modelo de imágenes transparente."
type: docs
weight: 1850
url: /es/java/com.aspose.pdf/group/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Group

```
public final class Group extends Object
```

Una clase de atributos de grupo que especifica los atributos del grupo de página para su uso en el modelo de imágenes transparente.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [Group](#Group-com.aspose.pdf.Page-) | El constructor. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getColorSpace](#getColorSpace--) | Obtiene ColorSpace <p> |
| [isKnockout](#isKnockout--) | Solo para uso interno. Si este indicador es falso, los objetos posteriores dentro del grupo se componen con los anteriores con los que se superponen; si es verdadero, se componen con el fondo inicial del grupo y sobrescriben ("knock out") cualquier objeto superpuesto anterior. |
| [isTransparency](#isTransparency--) | solo para uso interno devuelve la bandera de transparencia del grupo. |
| [setColorSpace](#setColorSpace-com.aspose.pdf.ColorSpace-) | El espacio de color del grupo. |
| [setKnockout](#setKnockout-com.aspose.pdf.ExtendedBoolean-) | Si esta bandera es falsa, los objetos posteriores dentro del grupo se componen con los anteriores con los que se superponen; si es verdadera, se componen con el fondo inicial del grupo y sobrescriben ("knock out") cualquier objeto superpuesto anterior. |

### Group {#Group-com.aspose.pdf.Page-}
El constructor.

### getColorSpace {#getColorSpace--}
```
public ColorSpace getColorSpace()
```

Obtiene ColorSpace <p>

**Returns:**
Valor de ColorSpace. @see ColorSpace

### isKnockout {#isKnockout--}
```
public ExtendedBoolean isKnockout()
```

Solo para uso interno. Si este indicador es falso, los objetos posteriores dentro del grupo se componen con los anteriores con los que se superponen; si es verdadero, se componen con el fondo inicial del grupo y sobrescriben ("knock out") cualquier objeto superpuesto anterior.

**Returns:**
Elemento ExtendedBoolean @see ExtendedBoolean

### isTransparency {#isTransparency--}
```
public boolean isTransparency()
```

solo para uso interno devuelve la bandera de transparencia del grupo.

**Returns:**
valor booleano

### setColorSpace {#setColorSpace-com.aspose.pdf.ColorSpace-}
El espacio de color del grupo.

### setKnockout {#setKnockout-com.aspose.pdf.ExtendedBoolean-}
Si esta bandera es falsa, los objetos posteriores dentro del grupo se componen con los anteriores con los que se superponen; si es verdadera, se componen con el fondo inicial del grupo y sobrescriben ("knock out") cualquier objeto superpuesto anterior.
