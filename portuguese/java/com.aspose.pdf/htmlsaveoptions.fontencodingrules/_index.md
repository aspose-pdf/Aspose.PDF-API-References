---
title: "HtmlSaveOptions.FontEncodingRules"
linktitle: "HtmlSaveOptions.FontEncodingRules"
second_title: "Referência da API Aspose.PDF para Java"
description: "Esta enumeração define regras que ajustam a lógica de codificação"
type: docs
weight: 2050
url: /pt/java/com.aspose.pdf/htmlsaveoptions.fontencodingrules/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.FontEncodingRules, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.FontEncodingRules, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.FontEncodingRules

```
public static final class HtmlSaveOptions.FontEncodingRules extends com.aspose.ms.System.Enum
```

Esta enumeração define regras que ajustam a lógica de codificação

## Campos

| Campo | Descrição |
| --- | --- |
| [DecreaseToUnicodePriorityLevel](#DecreaseToUnicodePriorityLevel) | ToUnicode é um mecanismo especial que ajuda a decodificar códigos de entrada em símbolos unicode. De acordo com a especificação, ele deve ser usado como o primeiro de todos os mecanismos para obter símbolos unicode para um código de entrada específico. Mas alguns documentos têm fontes não padrão e, para converter esses documentos corretamente, pode ser necessário diminuir a prioridade do ToUnicode e usar outros mecanismos para decodificar os códigos de entrada. |
| [Default](#Default) | Deixe a lógica de codificação \"como está\" - de acordo com a especificação PDF |

### DecreaseToUnicodePriorityLevel {#DecreaseToUnicodePriorityLevel}
```
public static final byte DecreaseToUnicodePriorityLevel
```

ToUnicode é um mecanismo especial que ajuda a decodificar códigos de entrada em símbolos unicode. De acordo com a especificação, ele deve ser usado como o primeiro de todos os mecanismos para obter símbolos unicode para um código de entrada específico. Mas alguns documentos têm fontes não padrão e, para converter esses documentos corretamente, pode ser necessário diminuir a prioridade do ToUnicode e usar outros mecanismos para decodificar os códigos de entrada.

### Default {#Default}
```
public static final byte Default
```

Deixe a lógica de codificação \"como está\" - de acordo com a especificação PDF
