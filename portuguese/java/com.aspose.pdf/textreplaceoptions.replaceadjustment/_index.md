---
title: "TextReplaceOptions.ReplaceAdjustment"
linktitle: "TextReplaceOptions.ReplaceAdjustment"
second_title: "Referência da API Aspose.PDF para Java"
description: "Determina a ação que será realizada após a substituição do fragmento de texto por um mais curto. None - nenhuma ação, o texto substituído pode sobrepor o resto da linha; AdjustSpaceWidth - tenta."
type: docs
weight: 5270
url: /pt/java/com.aspose.pdf/textreplaceoptions.replaceadjustment/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment, com.aspose.ms.System.Enum, com.aspose.pdf.TextReplaceOptions.ReplaceAdjustment

```
public static final class TextReplaceOptions.ReplaceAdjustment extends com.aspose.ms.System.Enum
```

Determina a ação que será realizada após a substituição de um fragmento de texto por um mais curto. None - nenhuma ação, o texto substituído pode sobrepor o restante da linha; AdjustSpaceWidth - tenta ajustar os espaços entre palavras para manter o comprimento da linha; WholeWordsHyphenation - tenta distribuir palavras entre as linhas do parágrafo para manter o campo direito do parágrafo; ShiftRestOfLine - desloca o restante da linha de acordo com a mudança no comprimento do texto, o comprimento da linha pode ser alterado; O valor padrão é ShiftRestOfLine.

## Campos

| Campo | Descrição |
| --- | --- |
| [AdjustSpaceWidth](#AdjustSpaceWidth) | Tenta ajustar os espaços entre as palavras para manter o comprimento da linha |
| [IsFormFillingMode](#IsFormFillingMode) | Tenta distribuir as palavras no espaço em branco disponível usando a largura do parágrafo. Se o texto transbordar, ele será ocultado. |
| [None](#None) | Nenhuma ação, o texto substituído pode sobrepor o resto da linha |
| [ShiftRestOfLine](#ShiftRestOfLine) | (Padrão) Desloca o resto da linha de acordo com a mudança no comprimento do texto, o comprimento da linha pode ser alterado |
| [WholeWordsHyphenation](#WholeWordsHyphenation) | Tenta distribuir as palavras entre as linhas do parágrafo para manter o campo direito do parágrafo |

## Métodos

| Método | Descrição |
| --- | --- |
| [hasFlag](#hasFlag-int-int-) |  |

### AdjustSpaceWidth {#AdjustSpaceWidth}
```
public static final int AdjustSpaceWidth
```

Tenta ajustar os espaços entre as palavras para manter o comprimento da linha

### IsFormFillingMode {#IsFormFillingMode}
```
public static final int IsFormFillingMode
```

Tenta distribuir as palavras no espaço em branco disponível usando a largura do parágrafo. Se o texto transbordar, ele será ocultado.

### None {#None}
```
public static final int None
```

Nenhuma ação, o texto substituído pode sobrepor o resto da linha

### ShiftRestOfLine {#ShiftRestOfLine}
```
public static final int ShiftRestOfLine
```

(Padrão) Desloca o resto da linha de acordo com a mudança no comprimento do texto, o comprimento da linha pode ser alterado

### WholeWordsHyphenation {#WholeWordsHyphenation}
```
public static final int WholeWordsHyphenation
```

Tenta distribuir as palavras entre as linhas do parágrafo para manter o campo direito do parágrafo

### hasFlag {#hasFlag-int-int-}
```
public static boolean hasFlag(int flag, int flagToCheck)
```



**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| bandeira |  |  |
| flagToCheck |  |  |
