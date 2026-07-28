---
title: "TextDefaults.DefaultFontStrategy"
linktitle: "TextDefaults.DefaultFontStrategy"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Especifica el tipo de valores predeterminados del subsistema de texto"
type: docs
weight: 4960
url: /es/java/com.aspose.pdf/textdefaults.defaultfontstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.TextDefaults.DefaultFontStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.TextDefaults.DefaultFontStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.TextDefaults.DefaultFontStrategy

```
public static class TextDefaults.DefaultFontStrategy extends com.aspose.ms.System.Enum
```

Especifica el tipo de valores predeterminados del subsistema de texto

## Campos

| Campo | Descripción |
| --- | --- |
| [ListOfFonts](#ListOfFonts) | Utilice la fuente predeterminada de la lista predefinida de instancias de Font. Puede establecerse usando setDefaultFonts(List of Font instances) Se utilizará la primera fuente encontrada que contenga todos los caracteres requeridos para el texto. Si no se encuentra dicha fuente, se usará la fuente del Sistema. |
| [PredefinedFont](#PredefinedFont) | Utilice la fuente predeterminada. Puede establecerse usando set/get PredefinedFont(Font) si PredefinedFont es nulo, se usará SystemFont. |
| [SystemFont](#SystemFont) | Utilice la fuente del sistema predeterminada Helvetica, o su análogo sustituido. |
| [TheFirstSuitableFoundFont](#TheFirstSuitableFoundFont) | Se utilizará la primera fuente encontrada que contenga todos los caracteres necesarios para el texto. Todas las fuentes encontradas estarán involucradas. Si no se encuentra dicha fuente, se usará la fuente del Sistema. |

### ListOfFonts {#ListOfFonts}
```
public static final int ListOfFonts
```

Utilice la fuente predeterminada de la lista predefinida de instancias de Font. Puede establecerse usando setDefaultFonts(List of Font instances) Se utilizará la primera fuente encontrada que contenga todos los caracteres requeridos para el texto. Si no se encuentra dicha fuente, se usará la fuente del Sistema.

### PredefinedFont {#PredefinedFont}
```
public static final int PredefinedFont
```

Utilice la fuente predeterminada. Puede establecerse usando set/get PredefinedFont(Font) si PredefinedFont es nulo, se usará SystemFont.

### SystemFont {#SystemFont}
```
public static final int SystemFont
```

Utilice la fuente del sistema predeterminada Helvetica, o su análogo sustituido.

### TheFirstSuitableFoundFont {#TheFirstSuitableFoundFont}
```
public static final int TheFirstSuitableFoundFont
```

Se utilizará la primera fuente encontrada que contenga todos los caracteres necesarios para el texto. Todas las fuentes encontradas estarán involucradas. Si no se encuentra dicha fuente, se usará la fuente del Sistema.
