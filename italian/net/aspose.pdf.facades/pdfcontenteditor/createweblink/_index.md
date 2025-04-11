---
title: PdfContentEditor.CreateWebLink
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfContentEditor. Crea un collegamento web nel documento PDF
type: docs
weight: 300
url: /it/net/aspose.pdf.facades/pdfcontenteditor/createweblink/
---
## CreateWebLink(Rectangle, string, int, Color, Enum[]) {#createweblink_2}

Crea un collegamento web nel documento PDF.

```csharp
public void CreateWebLink(Rectangle rect, string url, int originalPage, Color clr, 
    Enum[] actionName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | Rectangle | Il rettangolo per il clic attivo. |
| url | String | La destinazione del collegamento web. |
| originalPage | Int32 | Il numero della pagina originale su cui verrà creato il rettangolo legato al collegamento web. |
| clr | Color | Il colore del rettangolo per il clic attivo. |
| actionName | Enum[] | L'array di azioni (membri dell'enum PredefinedAction) corrispondente all'esecuzione degli elementi di menu nel visualizzatore Acrobat. |

## Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateWebLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "http://www.aspose.com", 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### Vedi anche

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateWebLink(Rectangle, string, int, Color) {#createweblink_1}

Crea un collegamento web nel documento PDF.

```csharp
public void CreateWebLink(Rectangle rect, string url, int originalPage, Color clr)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | Rectangle | Il rettangolo per il clic attivo. |
| url | String | La destinazione del collegamento web. |
| originalPage | Int32 | Il numero della pagina originale in cui verrà creato il rettangolo legato al collegamento web. |
| clr | Color | Il colore del rettangolo per il clic attivo. |

## Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateWebLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "http://www.aspose.com", 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### Vedi anche

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateWebLink(Rectangle, string, int) {#createweblink}

Crea un collegamento web nel documento PDF.

```csharp
public void CreateWebLink(Rectangle rect, string url, int originalPage)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | Rectangle | Il rettangolo per il clic attivo. |
| url | String | La destinazione del collegamento web. |
| originalPage | Int32 | Il numero della pagina originale in cui verrà creato il rettangolo legato al collegamento web. |

## Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateWebLink(new System.Drawing.Rectangle(0, 0, 100, 100), "http://www.aspose.com", 1 });
editor.Save("example_out.pdf");
```

### Vedi anche

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)