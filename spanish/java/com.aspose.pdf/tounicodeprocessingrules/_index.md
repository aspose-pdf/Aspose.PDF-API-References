---
title: "ToUnicodeProcessingRules"
linktitle: "ToUnicodeProcessingRules"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Esta clase describe reglas que pueden usarse para resolver el error de Adobe Preflight \\\"Text cannot be mapped to Unicode\\\"."
type: docs
weight: 5380
url: /es/java/com.aspose.pdf/tounicodeprocessingrules/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ToUnicodeProcessingRules

```
public class ToUnicodeProcessingRules extends Object
```

Esta clase describe reglas que pueden usarse para resolver el error de Adobe Preflight "Text cannot be mapped to Unicode".

## Constructores

| Constructor | Descripción |
| --- | --- |
| [ToUnicodeProcessingRules](#ToUnicodeProcessingRules--) | Inicializa una nueva instancia de la clase {@link ToUnicodeProcessingRules}. |
| [ToUnicodeProcessingRules](#ToUnicodeProcessingRules-boolean-) | Inicializa una nueva instancia de la clase {@link ToUnicodeProcessingRules} con la opción especificada para eliminar espacios de los nombres CMap. |
| [ToUnicodeProcessingRules](#ToUnicodeProcessingRules-boolean-boolean-) | Inicializa una nueva instancia de la clase {@link ToUnicodeProcessingRules} con opciones especificadas. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getMapNonLinkedSymbolsOnSpace](#getMapNonLinkedSymbolsOnSpace--) | Algunas fuentes no proporcionan información sobre unicodes para algunos símbolos de texto. Esta falta de información genera un error \"Text cannot be mapped to Unicode\". Use esta bandera para mapear símbolos no vinculados al unicode \"space\" (código 32). |
| [getRemoveSpacesFromCMapNames](#getRemoveSpacesFromCMapNames--) | Algunas fuentes tienen mapas de códigos de caracteres ToUnicode con espacios en los nombres. Estos espacios podrían generar errores al mapear texto Unicode. Esta bandera indica eliminar los espacios de los nombres de los mapas de códigos de caracteres ToUnicode. Por defecto, false. |
| [setMapNonLinkedSymbolsOnSpace](#setMapNonLinkedSymbolsOnSpace-boolean-) | Algunas fuentes no proporcionan información sobre unicodes para algunos símbolos de texto. Esta falta de información genera un error \"Text cannot be mapped to Unicode\". Use esta bandera para mapear símbolos no vinculados al unicode \"space\" (código 32). |
| [setRemoveSpacesFromCMapNames](#setRemoveSpacesFromCMapNames-boolean-) | Algunas fuentes tienen mapas de códigos de caracteres ToUnicode con espacios en los nombres. Estos espacios podrían generar errores al mapear texto Unicode. Esta bandera indica eliminar los espacios de los nombres de los mapas de códigos de caracteres ToUnicode. Por defecto, false. |

### ToUnicodeProcessingRules {#ToUnicodeProcessingRules--}
```
public ToUnicodeProcessingRules()
```

Inicializa una nueva instancia de la clase {@link ToUnicodeProcessingRules}.

### ToUnicodeProcessingRules {#ToUnicodeProcessingRules-boolean-}
```
public ToUnicodeProcessingRules(boolean removeSpaces)
```

Inicializa una nueva instancia de la clase {@link ToUnicodeProcessingRules} con la opción especificada para eliminar espacios de los nombres CMap.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| removeSpaces |  | Valor booleano que indica si se deben eliminar los espacios de los nombres CMap. |

### ToUnicodeProcessingRules {#ToUnicodeProcessingRules-boolean-boolean-}
```
public ToUnicodeProcessingRules(boolean removeSpaces, boolean mapNonLinkedUnicodesOnSpace)
```

Inicializa una nueva instancia de la clase {@link ToUnicodeProcessingRules} con opciones especificadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| removeSpaces |  | Indica si los espacios deben eliminarse de los nombres CMap. |
| mapNonLinkedUnicodesOnSpace |  | Indica si los símbolos Unicode no vinculados deben mapearse a espacios. |

### getMapNonLinkedSymbolsOnSpace {#getMapNonLinkedSymbolsOnSpace--}
```
public boolean getMapNonLinkedSymbolsOnSpace()
```

Algunas fuentes no proporcionan información sobre unicodes para algunos símbolos de texto. Esta falta de información genera un error \"Text cannot be mapped to Unicode\". Use esta bandera para mapear símbolos no vinculados al unicode \"space\" (código 32).

**Returns:**
valor booleano

### getRemoveSpacesFromCMapNames {#getRemoveSpacesFromCMapNames--}
```
public boolean getRemoveSpacesFromCMapNames()
```

Algunas fuentes tienen mapas de códigos de caracteres ToUnicode con espacios en los nombres. Estos espacios podrían generar errores al mapear texto Unicode. Esta bandera indica eliminar los espacios de los nombres de los mapas de códigos de caracteres ToUnicode. Por defecto, false.

**Returns:**
valor booleano

### setMapNonLinkedSymbolsOnSpace {#setMapNonLinkedSymbolsOnSpace-boolean-}
```
public void setMapNonLinkedSymbolsOnSpace(boolean value)
```

Algunas fuentes no proporcionan información sobre unicodes para algunos símbolos de texto. Esta falta de información genera un error \"Text cannot be mapped to Unicode\". Use esta bandera para mapear símbolos no vinculados al unicode \"space\" (código 32).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |

### setRemoveSpacesFromCMapNames {#setRemoveSpacesFromCMapNames-boolean-}
```
public void setRemoveSpacesFromCMapNames(boolean value)
```

Algunas fuentes tienen mapas de códigos de caracteres ToUnicode con espacios en los nombres. Estos espacios podrían generar errores al mapear texto Unicode. Esta bandera indica eliminar los espacios de los nombres de los mapas de códigos de caracteres ToUnicode. Por defecto, false.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | valor booleano |
