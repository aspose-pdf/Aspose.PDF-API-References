---
title: PdfPageEditor.MovePosition
second_title: Aspose.PDF for .NET API Reference
description: Método PdfPageEditor. Move a origem de 0 0 para o ponto designado. A origem é inferior esquerda e a unidade é ponto (1 polegada = 72 pontos)
type: docs
weight: 170
url: /pt/net/aspose.pdf.facades/pdfpageeditor/moveposition/
---
## Método PdfPageEditor.MovePosition

Move a origem de (0, 0) para o ponto designado. A origem é inferior esquerda e a unidade é ponto (1 polegada = 72 pontos).

```csharp
public void MovePosition(float moveX, float moveY)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| moveX | Único | Coordenada X. |
| moveY | Único | Coordenada Y. |

## Exemplos

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("input.pdf");
editor.MovePosition(-100, 60);
editor.Save("moved.pdf");
```

### Veja Também

* classe [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)