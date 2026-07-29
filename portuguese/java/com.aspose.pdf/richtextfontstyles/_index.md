---
title: "RichTextFontStyles"
linktitle: "RichTextFontStyles"
second_title: "Referência da API Aspose.PDF para Java"
description: "Opções para estilizar fragmentos de texto em RichText."
type: docs
weight: 4300
url: /pt/java/com.aspose.pdf/richtextfontstyles/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.RichTextFontStyles, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.RichTextFontStyles, com.aspose.ms.System.Enum, com.aspose.pdf.RichTextFontStyles

```
public final class RichTextFontStyles extends com.aspose.ms.System.Enum
```

Opções para estilizar fragmentos de texto em RichText.

## Campos

| Campo | Descrição |
| --- | --- |
| [Bold](#Bold) | Opção que especifica negrito. |
| [ClearExisting](#ClearExisting) | Se definido, limpa todos os estilos existentes antes de aplicar os adicionais. Quando combinado com outras bandeiras de estilo (por exemplo, {@code RichTextFontStyles#Bold}), ele primeiro redefine os estilos e, em seguida, aplica os especificados. Sem esta bandeira, novos estilos são adicionados aos existentes. |
| [Italic](#Italic) | Opção que especifica itálico. |
| [Underline](#Underline) | Opção que especifica sublinhado. |

## Métodos

| Método | Descrição |
| --- | --- |
| [hasFlag](#hasFlag-int-int-) | Verifica se a bandeira especificada está definida. |

### Bold {#Bold}
```
public static final int Bold
```

Opção que especifica negrito.

### ClearExisting {#ClearExisting}
```
public static final int ClearExisting
```

Se definido, limpa todos os estilos existentes antes de aplicar os adicionais. Quando combinado com outras bandeiras de estilo (por exemplo, {@code RichTextFontStyles#Bold}), ele primeiro redefine os estilos e, em seguida, aplica os especificados. Sem esta bandeira, novos estilos são adicionados aos existentes.

### Italic {#Italic}
```
public static final int Italic
```

Opção que especifica itálico.

### Underline {#Underline}
```
public static final int Underline
```

Opção que especifica sublinhado.

### hasFlag {#hasFlag-int-int-}
```
public static boolean hasFlag(int flag, int flagToCheck)
```

Verifica se a bandeira especificada está definida.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bandeira |  | o valor enum que representa a bandeira a ser verificada |
| flagToCheck |  | o valor enum que representa a bandeira a ser verificada |

**Returns:**
{@code true} se a bandeira estiver definida; {@code false} caso contrário
