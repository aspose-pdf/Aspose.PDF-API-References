---
title: CreateApplicationLink
second_title: Aspose.PDF per .NET API Reference
description: Crea un collegamento per avviare unapplicazione nel documento PDF.
type: docs
weight: 110
url: /it/net/aspose.pdf.facades/pdfcontenteditor/createapplicationlink/
---
## CreateApplicationLink(Rectangle, string, int, Color, Enum[]) {#createapplicationlink_2}

Crea un collegamento per avviare un'applicazione nel documento PDF.

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page, Color clr, 
    Enum[] actionName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | Rectangle | Il rettangolo per il clic attivo. |
| application | String | Il percorso dell'applicazione da avviare. |
| page | Int32 | Il numero della pagina originale in cui verrà creato il rettangolo rilegato con il collegamento. |
| clr | Color | Il colore del rettangolo per il clic attivo. |
| actionName | Enum[] | La matrice di azioni (membri di PredefinedAction enum) corrispondenti alle voci di menu in esecuzione nel visualizzatore Acrobat. |

### Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "explorer", 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### Guarda anche

* class [PdfContentEditor](../../pdfcontenteditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfcontenteditor)
* assemblea [Aspose.PDF](../../../)

---

## CreateApplicationLink(Rectangle, string, int, Color) {#createapplicationlink_1}

Crea un collegamento per avviare un'applicazione nel documento PDF.

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page, Color clr)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | Rectangle | Il rettangolo per il clic attivo. |
| application | String | Il percorso dell'applicazione da avviare. |
| page | Int32 | Il numero della pagina originale in cui verrà creato il rettangolo rilegato con il collegamento. |
| clr | Color | Il colore del rettangolo per il clic attivo. |

### Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "explorer", 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### Guarda anche

* class [PdfContentEditor](../../pdfcontenteditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfcontenteditor)
* assemblea [Aspose.PDF](../../../)

---

## CreateApplicationLink(Rectangle, string, int) {#createapplicationlink}

Crea un collegamento per avviare un'applicazione nel documento PDF.

```csharp
public void CreateApplicationLink(Rectangle rect, string application, int page)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | Rectangle | Il rettangolo per il clic attivo. |
| application | String | Il percorso dell'applicazione da avviare. |
| page | Int32 | Il numero della pagina originale in cui verrà creato il rettangolo rilegato con il collegamento. |

### Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateApplicationLink(new System.Drawing.Rectangle(0, 0, 100, 100), "explorer", 1 });
editor.Save("example_out.pdf");
```

### Guarda anche

* class [PdfContentEditor](../../pdfcontenteditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfcontenteditor)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->