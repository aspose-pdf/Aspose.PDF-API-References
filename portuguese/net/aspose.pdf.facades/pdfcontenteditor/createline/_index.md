---
title: PdfContentEditor.CreateLine
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Cria anotação de linha
type: docs
weight: 180
url: /pt/net/aspose.pdf.facades/pdfcontenteditor/createline/
---
## Método PdfContentEditor.CreateLine

Cria anotação de linha.

```csharp
public void CreateLine(Rectangle rect, string contents, float x1, float y1, float x2, float y2, 
    int page, int border, Color clr, string borderStyle, int[] dashArray, string[] LEArray)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rect | Rectangle | O retângulo da anotação que define a localização da anotação na página. |
| contents | String | O conteúdo da anotação. |
| x1 | Single | A coordenada horizontal inicial da linha. |
| y1 | Single | A coordenada vertical inicial da linha. |
| x2 | Single | A coordenada horizontal final da linha. |
| y2 | Single | A coordenada vertical final da linha. |
| page | Int32 | O número da página original onde a anotação será criada. |
| border | Int32 | A largura da borda em pontos. Se este valor for 0, nenhuma borda é desenhada. O valor padrão é 1. |
| clr | Color | A cor da linha. |
| borderStyle | String | O estilo da borda que especifica a largura e o padrão de traço a ser usado ao desenhar a linha. Este valor pode ser: "S" (Sólido), "D" (Tracejado), "B" (Chanfrado), "I" (Recuado), "U" (Sublinhado). |
| dashArray | Int32[] | Um array de traços definindo um padrão de traços e espaços a ser usado ao desenhar uma borda tracejada. Se for usado, borderStyle deve ser configurado para "D". |
| LEArray | String[] | Um array de dois valores que especificam respectivamente o estilo inicial e final da linha de desenho. Os valores podem ser: "Quadrado", "Círculo", "Losango", "SetaAberta", "SetaFechada", "Nenhum", "Corte", "RSetaAberta", "RSetaFechada", "Barra". |

## Exemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLine(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", 0, 0, 100, 100,
    1, 1, System.Drawing.Color.Red, "D", new int[] {2, 3}, new string[] {"OpenArrow", "ClosedArrow"});
editor.Save("example_out.pdf");
```

### Veja Também

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)