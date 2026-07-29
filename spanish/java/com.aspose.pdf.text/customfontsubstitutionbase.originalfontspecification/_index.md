---
title: "CustomFontSubstitutionBase.OriginalFontSpecification"
linktitle: "CustomFontSubstitutionBase.OriginalFontSpecification"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "<p> Representa la especificación de la fuente original. </p> <hr> <p> Proporciona información relacionada con la fuente original, como , bandera. También proporciona una bandera que ayuda a verificar si la sustitución lo será. </p>"
type: docs
weight: 20
url: /es/java/com.aspose.pdf.text/customfontsubstitutionbase.originalfontspecification/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.CustomFontSubstitutionBase.OriginalFontSpecification

```
public static final class CustomFontSubstitutionBase.OriginalFontSpecification extends Object
```

<p> Representa la especificación de fuente original. </p> <hr> <p> Proporciona información relacionada con la fuente original, como , flag. También proporciona una bandera que ayuda a comprobar si la sustitución ocurrirá de todos modos con la fuente y el usuario puede sobrescribir la lógica de sustitución predeterminada. </p>

## Constructores

| Constructor | Descripción |
| --- | --- |
| [OriginalFontSpecification](#OriginalFontSpecification-java.lang.String-boolean-boolean-) | Inicializa un nuevo objeto OriginalFontSpecification. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getOriginalFontName](#getOriginalFontName--) | Obtiene el nombre de la fuente original. |
| [isEmbedded](#isEmbedded--) | Obtiene un valor que indica si la fuente está incrustada. |
| [isSubstitutionUnavoidable](#isSubstitutionUnavoidable--) | <p> Obtiene un valor que indica que la sustitución es inevitable. </p> |

### OriginalFontSpecification {#OriginalFontSpecification-java.lang.String-boolean-boolean-}
Inicializa un nuevo objeto OriginalFontSpecification.

### getOriginalFontName {#getOriginalFontName--}
```
public String getOriginalFontName()
```

Obtiene el nombre de la fuente original.

**Returns:**
valor String

### isEmbedded {#isEmbedded--}
```
public boolean isEmbedded()
```

Obtiene un valor que indica si la fuente está incrustada.

**Returns:**
valor booleano

### isSubstitutionUnavoidable {#isSubstitutionUnavoidable--}
```
public boolean isSubstitutionUnavoidable()
```

<p> Obtiene un valor que indica que la sustitución es inevitable. </p>

**Returns:**
boolean value <hr> <p> Devuelve true en caso de que la sustitución se haya solicitado debido a la ausencia de la fuente original o en caso de que la fuente original no pueda usarse en el contexto de alguna tarea. Si el usuario ignora la bandera y no sustituye la fuente, se ejecuta el procedimiento de sustitución de fuentes predeterminado. Pero brinda la oportunidad al usuario de alternar el procedimiento estándar de sustitución de fuentes y establecer una fuente mejor en el sistema. Devuelve false en caso de que la fuente original esté presente, sea válida, pero se permita al usuario sustituirla. </p>
