---
title: PdfContentEditor.CreatePdfDocumentLink
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfContentEditor. Crea un link a un'altra pagina di documento PDF
type: docs
weight: 220
url: /it/net/aspose.pdf.facades/pdfcontenteditor/createpdfdocumentlink/
---
## CreatePdfDocumentLink(Rectangle, string, int, int, Color, Enum[]) {#createpdfdocumentlink_2}

Crea un link a un'altra pagina di documento PDF.

```csharp
public void CreatePdfDocumentLink(Rectangle rect, string remotePdf, int originalPage, 
    int destinationPage, Color clr, Enum[] actionName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | Rectangle | Il rettangolo per il clic attivo. |
| remotePdf | String | Il documento PDF la cui pagina sarà aperta. |
| originalPage | Int32 | Il numero della pagina originale dove il rettangolo legato al link sarà creato. |
| destinationPage | Int32 | La pagina di destinazione. |
| clr | Color | Il colore del rettangolo per il clic attivo. |
| actionName | Enum[] | L'array di azioni (membri dell'enum PredefinedAction) corrispondenti all'esecuzione degli elementi di menu nel visualizzatore Acrobat. |

## Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePdfDocumentLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "another_example.pdf", 1, 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### Vedi Anche

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreatePdfDocumentLink(Rectangle, string, int, int, Color) {#createpdfdocumentlink_1}

Crea un link a un'altra pagina di documento PDF.

```csharp
public void CreatePdfDocumentLink(Rectangle rect, string remotePdf, int originalPage, 
    int destinationPage, Color clr)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | Rectangle | Il rettangolo per il clic attivo. |
| remotePdf | String | Il documento PDF la cui pagina sarà aperta. |
| originalPage | Int32 | Il numero della pagina originale dove il rettangolo legato al link sarà creato. |
| destinationPage | Int32 | La pagina di destinazione. |
| clr | Color | Il colore del rettangolo per il clic attivo. |

## Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePdfDocumentLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "another_example.pdf", 1, 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### Vedi Anche

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreatePdfDocumentLink(Rectangle, string, int, int) {#createpdfdocumentlink}

Crea un link a un'altra pagina di documento PDF.

```csharp
public void CreatePdfDocumentLink(Rectangle rect, string remotePdf, int originalPage, 
    int destinationPage)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | Rectangle | Il rettangolo per il clic attivo. |
| remotePdf | String | Il documento PDF la cui pagina sarà aperta. |
| originalPage | Int32 | Il numero della pagina originale dove il rettangolo legato al link sarà creato. |
| destinationPage | Int32 | La pagina di destinazione. |

## Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreatePdfDocumentLink(new System.Drawing.Rectangle(0, 0, 100, 100), "another_example.pdf", 1, 1 });
editor.Save("example_out.pdf");
```

### Vedi Anche

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)