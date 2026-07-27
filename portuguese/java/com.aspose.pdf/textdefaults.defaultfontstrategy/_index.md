---
title: "TextDefaults.DefaultFontStrategy"
linktitle: "TextDefaults.DefaultFontStrategy"
second_title: "Referência da API Aspose.PDF para Java"
description: "Especifica o tipo de padrões do subsistema de texto"
type: docs
weight: 4960
url: /pt/java/com.aspose.pdf/textdefaults.defaultfontstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.TextDefaults.DefaultFontStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.TextDefaults.DefaultFontStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.TextDefaults.DefaultFontStrategy

```
public static class TextDefaults.DefaultFontStrategy extends com.aspose.ms.System.Enum
```

Especifica o tipo de padrões do subsistema de texto

## Campos

| Campo | Descrição |
| --- | --- |
| [ListOfFonts](#ListOfFonts) | Use a fonte padrão da lista predefinida de instâncias de Font. Pode ser definida usando setDefaultFonts(List of Font instances) Será usada a primeira fonte encontrada que contém todos os caracteres necessários para o texto. Se tal fonte não for encontrada, será usada a fonte do sistema. |
| [PredefinedFont](#PredefinedFont) | Use a fonte padrão. Pode ser definida usando set/get PredefinedFont(Font) se PredefinedFont for nulo - será usada SystemFont. |
| [SystemFont](#SystemFont) | Use a fonte padrão do sistema Helvetica, ou seu análogo substituto. |
| [TheFirstSuitableFoundFont](#TheFirstSuitableFoundFont) | A primeira fonte encontrada será usada, contendo todos os caracteres necessários para o texto. Todas as fontes encontradas serão consideradas. Se tal fonte não for encontrada, será usada a fonte do sistema. |

### ListOfFonts {#ListOfFonts}
```
public static final int ListOfFonts
```

Use a fonte padrão da lista predefinida de instâncias de Font. Pode ser definida usando setDefaultFonts(List of Font instances) Será usada a primeira fonte encontrada que contém todos os caracteres necessários para o texto. Se tal fonte não for encontrada, será usada a fonte do sistema.

### PredefinedFont {#PredefinedFont}
```
public static final int PredefinedFont
```

Use a fonte padrão. Pode ser definida usando set/get PredefinedFont(Font) se PredefinedFont for nulo - será usada SystemFont.

### SystemFont {#SystemFont}
```
public static final int SystemFont
```

Use a fonte padrão do sistema Helvetica, ou seu análogo substituto.

### TheFirstSuitableFoundFont {#TheFirstSuitableFoundFont}
```
public static final int TheFirstSuitableFoundFont
```

A primeira fonte encontrada será usada, contendo todos os caracteres necessários para o texto. Todas as fontes encontradas serão consideradas. Se tal fonte não for encontrada, será usada a fonte do sistema.
