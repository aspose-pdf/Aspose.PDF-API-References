---
title: PdfPageEditor.MovePosition
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfPageEditor. Sposta l'origine da 0 0 al punto designato. L'origine è in basso a sinistra e l'unità è punto (1 pollice = 72 punti)
type: docs
weight: 170
url: /it/net/aspose.pdf.facades/pdfpageeditor/moveposition/
---
## Metodo PdfPageEditor.MovePosition

Sposta l'origine da (0, 0) al punto designato. L'origine è in basso a sinistra e l'unità è punto (1 pollice = 72 punti).

```csharp
public void MovePosition(float moveX, float moveY)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| moveX | Singolo | Coordinata X. |
| moveY | Singolo | Coordinata Y. |

## Esempi

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("input.pdf");
editor.MovePosition(-100, 60);
editor.Save("moved.pdf");
```

### Vedi Anche

* classe [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)