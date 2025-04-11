---
title: Enum HtmlSaveOptions.FontEncodingRules
second_title: Aspose.PDF for .NET API Reference
description: Enum Aspose.Pdf.HtmlSaveOptionsFontEncodingRules. Esta enumeração define regras que ajustam a lógica de codificação
type: docs
weight: 5620
url: /pt/net/aspose.pdf/htmlsaveoptions.fontencodingrules/
---
## Enumeração HtmlSaveOptions.FontEncodingRules

Esta enumeração define regras que ajustam a lógica de codificação

```csharp
public enum FontEncodingRules : byte
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| Padrão | `0` | Deixar a lógica de codificação "como está" - de acordo com a especificação PDF |
| DiminuirNívelDePrioridadeParaUnicode | `1` | ToUnicode é um mecanismo especial que ajuda a decodificar códigos de entrada em símbolos unicode. De acordo com a especificação, deve ser usado antes de todos os mecanismos para obter símbolos unicode para um código de entrada específico. Mas alguns documentos têm fontes não padrão e, para converter esses documentos corretamente, pode ser necessário diminuir a prioridade do ToUnicode e usar outros mecanismos para decodificar códigos de entrada. |

### Veja Também

* classe [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)