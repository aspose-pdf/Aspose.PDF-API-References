---
title: PdfContentEditor.CreateCustomActionLink
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfContentEditor. Crea un link a azioni personalizzate nel documento PDF
type: docs
weight: 140
url: /it/net/aspose.pdf.facades/pdfcontenteditor/createcustomactionlink/
---
## Metodo PdfContentEditor.CreateCustomActionLink

Crea un link a azioni personalizzate nel documento PDF.

```csharp
public void CreateCustomActionLink(Rectangle rect, int originalPage, Color color, Enum[] actionName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | Rectangle | Il rettangolo per il clic attivo. |
| originalPage | Int32 | Il numero della pagina originale dove verrà creato il rettangolo legato al link. |
| color | Color | Il colore del rettangolo per il clic attivo. |
| actionName | Enum[] | L'array di azioni (membri dell'enum PredefinedAction) corrispondenti all'esecuzione degli elementi di menu nel visualizzatore Acrobat. |

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

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)