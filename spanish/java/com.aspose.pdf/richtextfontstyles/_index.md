---
title: "RichTextFontStyles"
linktitle: "RichTextFontStyles"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Opciones para dar estilo a fragmentos de texto en RichText."
type: docs
weight: 4300
url: /es/java/com.aspose.pdf/richtextfontstyles/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.RichTextFontStyles, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.RichTextFontStyles, com.aspose.ms.System.Enum, com.aspose.pdf.RichTextFontStyles

```
public final class RichTextFontStyles extends com.aspose.ms.System.Enum
```

Opciones para dar estilo a fragmentos de texto en RichText.

## Campos

| Campo | Descripción |
| --- | --- |
| [Bold](#Bold) | Opción que especifica negrita. |
| [ClearExisting](#ClearExisting) | Si está establecida, elimina todos los estilos existentes antes de aplicar los adicionales. Cuando se combina con otras banderas de estilo (p. ej., {@code RichTextFontStyles#Bold}), primero restablece los estilos y luego aplica los especificados. Sin esta bandera, los nuevos estilos se añaden a los existentes. |
| [Italic](#Italic) | Opción que especifica cursiva. |
| [Underline](#Underline) | Opción que especifica subrayado. |

## Métodos

| Método | Descripción |
| --- | --- |
| [hasFlag](#hasFlag-int-int-) | Comprueba si la bandera especificada está establecida. |

### Bold {#Bold}
```
public static final int Bold
```

Opción que especifica negrita.

### ClearExisting {#ClearExisting}
```
public static final int ClearExisting
```

Si está establecida, elimina todos los estilos existentes antes de aplicar los adicionales. Cuando se combina con otras banderas de estilo (p. ej., {@code RichTextFontStyles#Bold}), primero restablece los estilos y luego aplica los especificados. Sin esta bandera, los nuevos estilos se añaden a los existentes.

### Italic {#Italic}
```
public static final int Italic
```

Opción que especifica cursiva.

### Underline {#Underline}
```
public static final int Underline
```

Opción que especifica subrayado.

### hasFlag {#hasFlag-int-int-}
```
public static boolean hasFlag(int flag, int flagToCheck)
```

Comprueba si la bandera especificada está establecida.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bandera |  | el valor enum que representa la bandera a comprobar |
| flagToCheck |  | el valor enum que representa la bandera a comprobar |

**Returns:**
{@code true} si la bandera está establecida; {@code false} de lo contrario
