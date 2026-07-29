---
title: "SystemFontsSubstitution"
linktitle: "SystemFontsSubstitution"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa una clase para una estrategia de sustitución de fuentes que reemplaza fuentes por fuentes del sistema."
type: docs
weight: 110
url: /es/java/com.aspose.pdf.text/systemfontssubstitution/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.FontSubstitution com.aspose.pdf.text.SystemFontsSubstitution, com.aspose.pdf.text.FontSubstitution, com.aspose.pdf.text.SystemFontsSubstitution

```
public final class SystemFontsSubstitution extends FontSubstitution
```

Representa una clase para una estrategia de sustitución de fuentes que reemplaza fuentes por fuentes del sistema.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [SystemFontsSubstitution](#SystemFontsSubstitution-int-) | Inicializa una nueva instancia de la clase {@code SystemFontsSubstitution}. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getDefaultFont](#getDefaultFont--) | Obtiene o establece la fuente de sustitución predeterminada. La fuente se usa cuando no se encontró ninguna otra sustitución válida pero la fuente inicial pertenece a la categoría de sustitución objetivo ({@code FontCategories}). |
| [getFontCategories](#getFontCategories--) | Obtiene o establece las categorías de fuentes de sustitución que deben ser sustituidas por fuentes del sistema. |
| [setDefaultFont](#setDefaultFont-com.aspose.pdf.Font-) | Obtiene o establece la fuente de sustitución predeterminada. La fuente se usa cuando no se encontró ninguna otra sustitución válida pero la fuente inicial pertenece a la categoría de sustitución objetivo ({@code FontCategories}). |
| [setFontCategories](#setFontCategories-int-) | Obtiene o establece las categorías de fuentes de sustitución que deben ser sustituidas por fuentes del sistema. |

### SystemFontsSubstitution {#SystemFontsSubstitution-int-}
```
public SystemFontsSubstitution(int fontCategories)
```

Inicializa una nueva instancia de la clase {@code SystemFontsSubstitution}.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontCategories |  | Categorías de fuentes objetivo para sustituir con fuentes del sistema |

### getDefaultFont {#getDefaultFont--}
```
public Font getDefaultFont()
```

Obtiene o establece la fuente de sustitución predeterminada. La fuente se usa cuando no se encontró ninguna otra sustitución válida pero la fuente inicial pertenece a la categoría de sustitución objetivo ({@code FontCategories}).

**Returns:**
objeto Font

### getFontCategories {#getFontCategories--}
```
public int getFontCategories()
```

Obtiene o establece las categorías de fuentes de sustitución que deben ser sustituidas por fuentes del sistema.

**Returns:**
Elemento SubstitutionFontCategories @see SubstitutionFontCategories

### setDefaultFont {#setDefaultFont-com.aspose.pdf.Font-}
Obtiene o establece la fuente de sustitución predeterminada. La fuente se usa cuando no se encontró ninguna otra sustitución válida pero la fuente inicial pertenece a la categoría de sustitución objetivo ({@code FontCategories}).

### setFontCategories {#setFontCategories-int-}
```
public void setFontCategories(int value)
```

Obtiene o establece las categorías de fuentes de sustitución que deben ser sustituidas por fuentes del sistema.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  | Elemento SubstitutionFontCategories @see SubstitutionFontCategories |
