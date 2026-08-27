---
title: "PdfContentEditor.CreateLine"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo PdfContentEditor. Crea un'annotazione di linea"
type: docs
weight: 180
url: /it/net/aspose.pdf.facades/pdfcontenteditor/createline/
---
## PdfContentEditor.CreateLine method

Crea un'annotazione linea.

```csharp
public void CreateLine(Rectangle rect, string contents, float x1, float y1, float x2, float y2, 
    int page, int border, Color clr, string borderStyle, int[] dashArray, string[] LEArray)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rect | Rectangle | Il rettangolo dell'annotazione che definisce la posizione dell'annotazione sulla pagina. |
| contents | String | Il contenuto dell'annotazione. |
| x1 | Single | La coordinata orizzontale iniziale della linea. |
| y1 | Single | La coordinata verticale iniziale della linea. |
| x2 | Single | La coordinata orizzontale finale della linea. |
| y2 | Single | La coordinata verticale finale della linea. |
| pagina | Int32 | Il numero della pagina originale dove verrà creata l'annotazione. |
| border | Int32 | La larghezza del bordo in punti. Se questo valore è 0 non viene disegnato alcun bordo. Il valore predefinito è 1. |
| clr | Color | Il colore della linea. |
| borderStyle | String | Lo stile del bordo che specifica la larghezza e il modello di tratteggio da utilizzare nel disegno della linea. Questo valore può essere: "S" (Solido), "D" (Tratteggiato), "B" (Smussato), "I" (Incastonato), "U" (Sottolineato). |
| dashArray | Int32[] | Un array di tratteggi che definisce un modello di linee e spazi da utilizzare nel disegno di un bordo tratteggiato. Se viene usato, borderSyle deve essere impostato di conseguenza su "D". |
| LEArray | String[] | Un array di due valori che specificano rispettivamente lo stile di inizio e fine della linea disegnata. I valori possono essere: "Square", "Circle", "Diamond", "OpenArrow", "ClosedArrow", "None", "Butt", "ROpenArrow", "RClosedArrow", "Slash". |

## Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateLine(new System.Drawing.Rectangle(0, 0, 100, 100), "Welcome to Aspose", 0, 0, 100, 100,
    1, 1, System.Drawing.Color.Red, "D", new int[] {2, 3}, new string[] {"OpenArrow", "ClosedArrow"});
editor.Save("example_out.pdf");
```

### Vedi anche

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


