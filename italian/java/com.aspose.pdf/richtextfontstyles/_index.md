---
title: "RichTextFontStyles"
linktitle: "RichTextFontStyles"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Opzioni per lo stile dei frammenti di testo in RichText."
type: docs
weight: 4300
url: /it/java/com.aspose.pdf/richtextfontstyles/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.RichTextFontStyles, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.RichTextFontStyles, com.aspose.ms.System.Enum, com.aspose.pdf.RichTextFontStyles

```
public final class RichTextFontStyles extends com.aspose.ms.System.Enum
```

Opzioni per lo stile dei frammenti di testo in RichText.

## Campi

| Campo | Descrizione |
| --- | --- |
| [Bold](#Bold) | Opzione che specifica il grassetto. |
| [ClearExisting](#ClearExisting) | Se impostata, cancella tutti gli stili esistenti prima di applicare quelli aggiuntivi. Quando combinata con altri flag di stile (ad es., {@code RichTextFontStyles#Bold}), resetta prima gli stili, poi applica quelli specificati. Senza questo flag, i nuovi stili vengono aggiunti a quelli esistenti. |
| [Italic](#Italic) | Opzione che specifica il corsivo. |
| [Underline](#Underline) | Opzione che specifica la sottolineatura. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [hasFlag](#hasFlag-int-int-) | Verifica se il flag specificato è impostato. |

### Bold {#Bold}
```
public static final int Bold
```

Opzione che specifica il grassetto.

### ClearExisting {#ClearExisting}
```
public static final int ClearExisting
```

Se impostata, cancella tutti gli stili esistenti prima di applicare quelli aggiuntivi. Quando combinata con altri flag di stile (ad es., {@code RichTextFontStyles#Bold}), resetta prima gli stili, poi applica quelli specificati. Senza questo flag, i nuovi stili vengono aggiunti a quelli esistenti.

### Italic {#Italic}
```
public static final int Italic
```

Opzione che specifica il corsivo.

### Underline {#Underline}
```
public static final int Underline
```

Opzione che specifica la sottolineatura.

### hasFlag {#hasFlag-int-int-}
```
public static boolean hasFlag(int flag, int flagToCheck)
```

Verifica se il flag specificato è impostato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flag |  | il valore enum che rappresenta il flag da verificare |
| flagToCheck |  | il valore enum che rappresenta il flag da verificare |

**Returns:**
{@code true} se il flag è impostato; {@code false} altrimenti
