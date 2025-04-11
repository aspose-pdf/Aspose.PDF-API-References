---
title: PdfContentEditor.CreateRubberStamp
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfContentEditor. Crea un'annotazione di timbro in gomma
type: docs
weight: 260
url: /it/net/aspose.pdf.facades/pdfcontenteditor/createrubberstamp/
---
## CreateRubberStamp(int, Rectangle, string, string, Color) {#createrubberstamp_2}

Crea un'annotazione di timbro in gomma.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string icon, string annotContents, 
    Color color)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page | Int32 | Il numero della pagina originale in cui verrà creata l'annotazione. |
| annotRect | Rectangle | Il rettangolo dell'annotazione che definisce la posizione dell'annotazione sulla pagina. |
| icon | String | Un'icona da utilizzare per visualizzare l'annotazione. Valore predefinito: 'Draft'. |
| annotContents | String | I contenuti dell'annotazione. |
| color | Color | Il colore dell'annotazione. |

## Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### Vedi Anche

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateRubberStamp(int, Rectangle, string, Color, string) {#createrubberstamp_1}

Crea un'annotazione di timbro in gomma.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string annotContents, Color color, 
    string appearanceFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page | Int32 | Il numero della pagina originale in cui verrà creata l'annotazione. |
| annotRect | Rectangle | Il rettangolo dell'annotazione che definisce la posizione dell'annotazione sulla pagina. |
| annotContents | String | I contenuti dell'annotazione. |
| color | Color | Il colore dell'annotazione. |
| appearanceFile | String | Il percorso del file di aspetto. |

## Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red, "appearance_file.pdf");
editor.Save("example_out.pdf");
```

### Vedi Anche

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateRubberStamp(int, Rectangle, string, Color, Stream) {#createrubberstamp}

Crea un'annotazione di timbro in gomma.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string annotContents, Color color, 
    Stream appearanceStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page | Int32 | Il numero della pagina originale in cui verrà creata l'annotazione. |
| annotRect | Rectangle | Il rettangolo dell'annotazione che definisce la posizione dell'annotazione sulla pagina. |
| annotContents | String | I contenuti dell'annotazione. |
| color | Color | Il colore dell'annotazione. |
| appearanceStream | Stream | Il flusso del file di aspetto. |

## Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using (System.IO.FileStream appStream = File.OpenRead("appearance_file.pdf"))
{
    editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
        "Welcome to Aspose", System.Drawing.Color.Red, appStream);
    editor.Save("example_out.pdf");
}    
```

### Vedi Anche

* classe [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)