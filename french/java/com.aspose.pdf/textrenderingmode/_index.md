---
title: "TextRenderingMode"
linktitle: "TextRenderingMode"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Le mode de rendu du texte, Tmode, détermine si l'affichage du texte doit entraîner le tracé des contours des glyphes, leur remplissage, leur utilisation comme limite de découpe, ou une combinaison de ces trois options."
type: docs
weight: 5240
url: /fr/java/com.aspose.pdf/textrenderingmode/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < TextRenderingMode > com.aspose.pdf.TextRenderingMode, java.lang.Enum < TextRenderingMode >, com.aspose.pdf.TextRenderingMode

**All Implemented Interfaces:**
Serializable, Comparable < TextRenderingMode >

```
public enum TextRenderingMode extends Enum < TextRenderingMode >
```

Le mode de rendu du texte, Tmode, détermine si l'affichage du texte doit entraîner le tracé des contours des glyphes, leur remplissage, leur utilisation comme limite de découpe, ou une combinaison de ces trois options.

## Champs

| Champ | Description |
| --- | --- |
| [AddPathToClipping](#AddPathToClipping) | Ajouter du texte au chemin pour le découpage. |
| [FillText](#FillText) | Remplir le texte. |
| [FillTextAndAddPathToClipping](#FillTextAndAddPathToClipping) | Remplir le texte et ajouter au chemin pour le découpage (voir 9.3.6, "Text Rendering Mode,"). |
| [FillThenStrokeText](#FillThenStrokeText) | Remplir, puis tracer le texte. |
| [FillThenStrokeTextAndAddPathToClipping](#FillThenStrokeTextAndAddPathToClipping) | Remplir, puis tracer le texte et ajouter au chemin pour le découpage. |
| [Invisible](#Invisible) | Ni remplissage ni tracé du texte (invisible). |
| [StrokeText](#StrokeText) | Tracer le texte. |
| [StrokeTextAndAddPathToClipping](#StrokeTextAndAddPathToClipping) | Tracer le texte et ajouter au chemin pour le découpage. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-int-) |  |
| [valueOf](#valueOf-java.lang.String-) | Renvoie la constante d'énumération de ce type avec le nom spécifié. |
| [values](#values--) | Renvoie un tableau contenant les constantes de ce type d'énumération, dans l'ordre où elles sont déclarées. |

### AddPathToClipping {#AddPathToClipping}
```
public static final TextRenderingMode AddPathToClipping
```

Ajouter du texte au chemin pour le découpage.

### FillText {#FillText}
```
public static final TextRenderingMode FillText
```

Remplir le texte.

### FillTextAndAddPathToClipping {#FillTextAndAddPathToClipping}
```
public static final TextRenderingMode FillTextAndAddPathToClipping
```

Remplir le texte et ajouter au chemin pour le découpage (voir 9.3.6, "Text Rendering Mode,").

### FillThenStrokeText {#FillThenStrokeText}
```
public static final TextRenderingMode FillThenStrokeText
```

Remplir, puis tracer le texte.

### FillThenStrokeTextAndAddPathToClipping {#FillThenStrokeTextAndAddPathToClipping}
```
public static final TextRenderingMode FillThenStrokeTextAndAddPathToClipping
```

Remplir, puis tracer le texte et ajouter au chemin pour le découpage.

### Invisible {#Invisible}
```
public static final TextRenderingMode Invisible
```

Ni remplissage ni tracé du texte (invisible).

### StrokeText {#StrokeText}
```
public static final TextRenderingMode StrokeText
```

Tracer le texte.

### StrokeTextAndAddPathToClipping {#StrokeTextAndAddPathToClipping}
```
public static final TextRenderingMode StrokeTextAndAddPathToClipping
```

Tracer le texte et ajouter au chemin pour le découpage.

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-int-}
```
public static TextRenderingMode valueOf(int value)
```



**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  |  |

### valueOf {#valueOf-java.lang.String-}
Renvoie la constante d'énumération de ce type avec le nom spécifié.

### values {#values--}
```
public static TextRenderingMode [] values()
```

Renvoie un tableau contenant les constantes de ce type d'énumération, dans l'ordre où elles sont déclarées.

**Returns:**
un tableau contenant les constantes de ce type d'énumération, dans l'ordre où elles sont déclarées
