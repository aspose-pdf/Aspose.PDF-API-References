---
title: CreateSquareCircle
second_title: Aspose.PDF per .NET API Reference
description: Crea annotazioni a cerchio quadrato.
type: docs
weight: 280
url: /it/net/aspose.pdf.facades/pdfcontenteditor/createsquarecircle/
---
## PdfContentEditor.CreateSquareCircle method

Crea annotazioni a cerchio quadrato.

```csharp
public void CreateSquareCircle(Rectangle rect, string contents, Color clr, bool square, int page, 
    int borderWidth)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | Rectangle | Il rettangolo di annotazione che definisce la posizione dell'annotazione sulla pagina. |
| contents | String | Il contenuto dell'annotazione. |
| clr | Color | Il colore del quadrato o del cerchio. |
| square | Boolean | Vero (quadrato), falso (sircle). |
| page | Int32 | Il numero della pagina originale in cui verrà creata l'annotazione. |
| borderWidth | Int32 | La larghezza del bordo del quadrato o del cerchio. |

### Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateSquareCircle(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red, false, 1, 5);
editor.Save("example_out.pdf");
```

### Guarda anche

* class [PdfContentEditor](../../pdfcontenteditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfcontenteditor)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
