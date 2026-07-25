---
title: "TextDefaults.DefaultFontStrategy"
linktitle: "TextDefaults.DefaultFontStrategy"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Spécifie le type des valeurs par défaut du sous-système texte"
type: docs
weight: 4960
url: /fr/java/com.aspose.pdf/textdefaults.defaultfontstrategy/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.TextDefaults.DefaultFontStrategy, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.TextDefaults.DefaultFontStrategy, com.aspose.ms.System.Enum, com.aspose.pdf.TextDefaults.DefaultFontStrategy

```
public static class TextDefaults.DefaultFontStrategy extends com.aspose.ms.System.Enum
```

Spécifie le type des valeurs par défaut du sous-système texte

## Champs

| Champ | Description |
| --- | --- |
| [ListOfFonts](#ListOfFonts) | Utilisez la police par défaut à partir d'une liste prédéfinie d'instances de Font. Peut être définie à l'aide de setDefaultFonts(Liste d'instances de Font). La première police trouvée contenant tous les caractères requis pour le texte sera utilisée. Si aucune police de ce type n'est trouvée, la police système sera utilisée. |
| [PredefinedFont](#PredefinedFont) | Utilisez la police par défaut ainsi. Peut être définie à l'aide de set/get PredefinedFont(Font) ; si PredefinedFont est nul, la SystemFont sera utilisée. |
| [SystemFont](#SystemFont) | Utilisez la police système par défaut Helvetica, ou son analogue substitué. |
| [TheFirstSuitableFoundFont](#TheFirstSuitableFoundFont) | La première police trouvée sera utilisée, contenant tous les caractères nécessaires pour le texte. Toutes les polices trouvées seront prises en compte. Si aucune police de ce type n'est trouvée, la police système sera utilisée. |

### ListOfFonts {#ListOfFonts}
```
public static final int ListOfFonts
```

Utilisez la police par défaut à partir d'une liste prédéfinie d'instances de Font. Peut être définie à l'aide de setDefaultFonts(Liste d'instances de Font). La première police trouvée contenant tous les caractères requis pour le texte sera utilisée. Si aucune police de ce type n'est trouvée, la police système sera utilisée.

### PredefinedFont {#PredefinedFont}
```
public static final int PredefinedFont
```

Utilisez la police par défaut ainsi. Peut être définie à l'aide de set/get PredefinedFont(Font) ; si PredefinedFont est nul, la SystemFont sera utilisée.

### SystemFont {#SystemFont}
```
public static final int SystemFont
```

Utilisez la police système par défaut Helvetica, ou son analogue substitué.

### TheFirstSuitableFoundFont {#TheFirstSuitableFoundFont}
```
public static final int TheFirstSuitableFoundFont
```

La première police trouvée sera utilisée, contenant tous les caractères nécessaires pour le texte. Toutes les polices trouvées seront prises en compte. Si aucune police de ce type n'est trouvée, la police système sera utilisée.
