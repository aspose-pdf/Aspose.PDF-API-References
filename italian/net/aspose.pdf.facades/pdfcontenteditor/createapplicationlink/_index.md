---
title: PdfContentEditor.CreateApplicationLink
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfContentEditor. Crea un link per avviare un'applicazione nel documento PDF
type: docs
weight: 110
url: /it/net/aspose.pdf.facades/pdfcontenteditor/createapplicationlink/
---
## CreateApplicationLink(Rectangle, string, int, Color, Enum[]) {#createapplicationlink_2}

Crea un link per avviare un'applicazione nel documento PDF.

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page, Color clr, 
    Enum[] actionName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | Il rettangolo per il clic attivo. |
| application | String | Il percorso dell'applicazione da avviare. |
| page | Int32 | Il numero della pagina originale in cui verrà creato il rettangolo legato al link. |
| clr | Color | Il colore del rettangolo per il clic attivo. |
| actionName | Enum[] | L'array di azioni (membri dell'enum PredefinedAction) corrispondente all'esecuzione degli elementi di menu nel visualizzatore Acrobat. |

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "explorer", 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateApplicationLink(Rectangle, string, int, Color) {#createapplicationlink_1}

Crea un link per avviare un'applicazione nel documento PDF.

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page, Color clr)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | Il rettangolo per il clic attivo. |
| application | String | Il percorso dell'applicazione da avviare. |
| page | Int32 | Il numero della pagina originale in cui verrà creato il rettangolo legato al link. |
| clr | Color | Il colore del rettangolo per il clic attivo. |

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "explorer", 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateApplicationLink(Rectangle, string, int) {#createapplicationlink}

Crea un link per avviare un'applicazione nel documento PDF.

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page)
```

| Parameter | Type | Description |
| --- | --- | --- |
| rect | Rectangle | Il rettangolo per il clic attivo. |
| application | String | Il percorso dell'applicazione da avviare. |
| page | Int32 | Il numero della pagina originale in cui verrà creato il rettangolo legato al link. |

## Examples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100), "explorer", 1 });
editor.Save("example_out.pdf");
```

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)