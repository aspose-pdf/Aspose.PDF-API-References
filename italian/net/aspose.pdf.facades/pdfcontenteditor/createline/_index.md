---
title: CreateLine
second_title: Aspose.PDF per .NET API Reference
description: Crea annotazione riga.
type: docs
weight: 180
url: /it/net/aspose.pdf.facades/pdfcontenteditor/createline/
---
## PdfContentEditor.CreateLine method

Crea annotazione riga.

```csharp
public void CreateLine(Rectangle rect, string contents, float x1, float y1, float x2, float y2, 
    int page, int border, Color clr, string borderStyle, int[] dashArray, string[] LEArray)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | Rectangle | Il rettangolo di annotazione che definisce la posizione dell'annotazione sulla pagina. |
| contents | String | Il contenuto dell'annotazione. |
| x1 | Single | La coordinata orizzontale iniziale della linea. |
| y1 | Single | La coordinata verticale iniziale della linea. |
| x2 | Single | La coordinata orizzontale finale della linea. |
| y2 | Single | La coordinata verticale finale della linea. |
| page | Int32 | Il numero della pagina originale in cui verrà creata l'annotazione. |
| border | Int32 | La larghezza del bordo in punti. Se questo valore è 0 non viene tracciato alcun bordo. Il valore predefinito è 1. |
| clr | Color | Il colore della linea. |
| borderStyle | String | Lo stile del bordo che specifica la larghezza e il modello di trattino da utilizzare per disegnare la linea. Questo valore può essere: "S" (solido), "D" (tratteggiato), "B" (smussato), "I" (riquadro) , "U" (sottolineato). |
| dashArray | Int32[] | Un array di trattini che definisce uno schema di trattini e spazi vuoti da utilizzare per disegnare un bordo tratteggiato. Se viene utilizzato, borderSyle deve essere impostato di conseguenza su "D". |
| LEArray | String[] | Un array di due valori che specificano rispettivamente lo stile iniziale e finale della linea di disegno. I valori possono essere: "Square", "Cerchio", "Diamond", "OpenArrow", "ClosedArrow", "None", "Butt" , "ROpenArrow", "RClosedArrow", "Slash". |

### Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLine(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", 0, 0, 100, 100,
    1, 1, System.Drawing.Color.Red, "D", new int[] {2, 3}, new string[] {"OpenArrow", "ClosedArrow"});
editor.Save("example_out.pdf");
```

### Guarda anche

* class [PdfContentEditor](../../pdfcontenteditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfcontenteditor)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->