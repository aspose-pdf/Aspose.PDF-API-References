---
title: PdfContentEditor.DrawCurve
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Cria anotação de curva
type: docs
weight: 360
url: /pt/net/aspose.pdf.facades/pdfcontenteditor/drawcurve/
---
## Método PdfContentEditor.DrawCurve

Cria anotação de curva.

```csharp
public void DrawCurve(LineInfo lineInfo, int page, Rectangle annotRect, string annotContents)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| lineInfo | LineInfo | A instância da classe LineInfo. |
| page | Int32 | O número da página original onde a anotação será criada. |
| annotRect | Rectangle | O retângulo da anotação definindo a localização da anotação na página. |
| annotContents | String | O conteúdo da anotação. |

## Exemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
newApiEditor.BindPdf("example.pdf");
LineInfo lineInfo = new LineInfo();
lineInfo.VerticeCoordinate = new float[] { 0, 0, 100, 100 };  //x1, y1, x2, y2, .. xn, yn
lineInfo.Visibility = true;
editor.DrawCurve(lineInfo, 1, new System.Drawing.Rectangle(0, 0, 0, 0), "Welcome to Aspose");
editor.Save("example_out.pdf");
```

### Veja Também

* classe [LineInfo](../../lineinfo/)
* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)