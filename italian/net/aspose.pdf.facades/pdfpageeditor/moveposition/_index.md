---
title: "PdfPageEditor.MovePosition"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfPageEditor. Sposta l'origine da 0 0 al punto specificato. L'origine è in basso a sinistra e l'unità è point1 inch  72 punti"
type: docs
weight: 170
url: /it/net/aspose.pdf.facades/pdfpageeditor/moveposition/
---
## PdfPageEditor.MovePosition method

Sposta l'origine da (0, 0) al punto indicato. L'origine è in basso a sinistra e l'unità è il punto (1 pollice = 72 punti).

```csharp
public void MovePosition(float moveX, float moveY)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| moveX | Single | Coordinata X. |
| moveY | Single | Coordinata Y. |

## Esempi

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("input.pdf");
editor.MovePosition(-100, 60);
editor.Save("moved.pdf");
```

### Vedi anche

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


