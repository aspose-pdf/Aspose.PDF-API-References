---
title: "PdfContentEditor.CreateCustomActionLink"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfContentEditor. Crea un collegamento a azioni personalizzate in PDF Document"
type: docs
weight: 140
url: /it/net/aspose.pdf.facades/pdfcontenteditor/createcustomactionlink/
---
## PdfContentEditor.CreateCustomActionLink method

Crea un collegamento a azioni personalizzate nel documento PDF.

```csharp
public void CreateCustomActionLink(Rectangle rect, int originalPage, Color color, Enum[] actionName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | Rectangle | Il rettangolo per il clic attivo. |
| originalPage | Int32 | Il numero della pagina originale dove verrà creato il rettangolo associato al collegamento. |
| color | Color | Il colore del rettangolo per il clic attivo. |
| actionName | Enum[] | L'array di azioni (membri dell'enumerazione PredefinedAction) corrispondente all'esecuzione delle voci di menu nel visualizzatore Acrobat. |

## Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateCustomActionLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### Vedi anche

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


