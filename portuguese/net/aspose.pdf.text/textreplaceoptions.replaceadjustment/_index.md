---
title: Enum TextReplaceOptions.ReplaceAdjustment
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextReplaceOptionsReplaceAdjustment enum. Determina a ação que será realizada após a substituição de um fragmento de texto por um mais curto. Nenhum - nenhuma ação, o texto substituído pode sobrepor o restante da linha; AjustarLarguraEspaço - tenta ajustar os espaços entre as palavras para manter o comprimento da linha; HifenizaçãoPalavrasInteiras - tenta distribuir as palavras entre as linhas do parágrafo para manter o campo correto do parágrafo; DeslocarRestoDaLinha - desloca o restante da linha de acordo com a mudança no comprimento do texto, o comprimento da linha pode ser alterado; O valor padrão é DeslocarRestoDaLinha.
type: docs
weight: 11020
url: /pt/net/aspose.pdf.text/textreplaceoptions.replaceadjustment/
---
## Enumeração TextReplaceOptions.ReplaceAdjustment

Determina a ação que será realizada após a substituição de um fragmento de texto por um mais curto. Nenhum - nenhuma ação, o texto substituído pode sobrepor o restante da linha; AjustarLarguraEspaço - tenta ajustar os espaços entre as palavras para manter o comprimento da linha; HifenizaçãoPalavrasInteiras - tenta distribuir as palavras entre as linhas do parágrafo para manter o campo correto do parágrafo; DeslocarRestoDaLinha - desloca o restante da linha de acordo com a mudança no comprimento do texto, o comprimento da linha pode ser alterado; O valor padrão é DeslocarRestoDaLinha.

```csharp
[Flags]
public enum ReplaceAdjustment
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| Nenhum | `0` | Nenhuma ação, o texto substituído pode sobrepor o restante da linha |
| AjustarLarguraEspaço | `1` | Tenta ajustar os espaços entre as palavras para manter o comprimento da linha |
| HifenizaçãoPalavrasInteiras | `2` | Tenta distribuir as palavras entre as linhas do parágrafo para manter o campo correto do parágrafo |
| ModoPreenchimentoFormulario | `4` | Tenta espalhar as palavras no espaço em branco disponível usando a largura do parágrafo. Se o texto transbordar, será ocultado. |
| DeslocarRestoDaLinha | `8` | (Padrão) Desloca o restante da linha de acordo com a mudança no comprimento do texto, o comprimento da linha pode ser alterado |

### Veja Também

* classe [TextReplaceOptions](../textreplaceoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)