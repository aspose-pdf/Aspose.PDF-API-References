---
title: "TextDefaults.DefaultFontStrategy"
linktitle: "TextDefaults.DefaultFontStrategy"
second_title: "Справочник API Aspose.PDF для Java"
description: "Указывает тип значений по умолчанию подсистемы текста"
type: docs
weight: 4960
url: /ru/java/com.aspose.pdf/textdefaults.defaultfontstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.TextDefaults.DefaultFontStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.TextDefaults.DefaultFontStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.TextDefaults.DefaultFontStrategy

```
public static class TextDefaults.DefaultFontStrategy extends com.aspose.ms.System.Enum
```

Указывает тип значений по умолчанию подсистемы текста

## Поля

| Поле | Описание |
| --- | --- |
| [ListOfFonts](#ListOfFonts) | Используйте шрифт по умолчанию из предопределённого списка экземпляров Font. Можно задать с помощью setDefaultFonts(List of Font instances). Будет использован первый найденный шрифт, содержащий все необходимые символы для текста. Если такой шрифт не найден - будет использован системный шрифт. |
| [PredefinedFont](#PredefinedFont) | Используйте шрифт по умолчанию. Можно задать с помощью set/get PredefinedFont(Font), если PredefinedFont равен null — будет использован SystemFont. |
| [SystemFont](#SystemFont) | Используйте системный шрифт по умолчанию Helvetica или его заменяющий аналог. |
| [TheFirstSuitableFoundFont](#TheFirstSuitableFoundFont) | Будет использован первый найденный шрифт, содержащий все необходимые символы для текста. Все найденные шрифты будут задействованы. Если такой шрифт не найден — будет использован системный шрифт. |

### ListOfFonts {#ListOfFonts}
```
public static final int ListOfFonts
```

Используйте шрифт по умолчанию из предопределённого списка экземпляров Font. Можно задать с помощью setDefaultFonts(List of Font instances). Будет использован первый найденный шрифт, содержащий все необходимые символы для текста. Если такой шрифт не найден - будет использован системный шрифт.

### PredefinedFont {#PredefinedFont}
```
public static final int PredefinedFont
```

Используйте шрифт по умолчанию. Можно задать с помощью set/get PredefinedFont(Font), если PredefinedFont равен null — будет использован SystemFont.

### SystemFont {#SystemFont}
```
public static final int SystemFont
```

Используйте системный шрифт по умолчанию Helvetica или его заменяющий аналог.

### TheFirstSuitableFoundFont {#TheFirstSuitableFoundFont}
```
public static final int TheFirstSuitableFoundFont
```

Будет использован первый найденный шрифт, содержащий все необходимые символы для текста. Все найденные шрифты будут задействованы. Если такой шрифт не найден — будет использован системный шрифт.
