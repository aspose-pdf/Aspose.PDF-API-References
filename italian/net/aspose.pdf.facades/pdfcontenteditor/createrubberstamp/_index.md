---
title: CreateRubberStamp
second_title: Aspose.PDF per .NET API Reference
description: Crea unannotazione del timbro di gomma.
type: docs
weight: 260
url: /it/net/aspose.pdf.facades/pdfcontenteditor/createrubberstamp/
---
## CreateRubberStamp(int, Rectangle, string, string, Color) {#createrubberstamp_2}

Crea un'annotazione del timbro di gomma.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string icon, string annotContents, 
    Color color)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page | Int32 | Il numero della pagina originale in cui verrà creata l'annotazione. |
| annotRect | Rectangle | Il rettangolo di annotazione che definisce la posizione dell'annotazione sulla pagina. |
| icon | String | Un'icona deve essere utilizzata per visualizzare l'annotazione. Valore predefinito: 'Bozza'." |
| annotContents | String | Il contenuto dell'annotazione. |
| color | Color | Il colore dell'annotazione. |

### Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### Guarda anche

* class [PdfContentEditor](../../pdfcontenteditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfcontenteditor)
* assemblea [Aspose.PDF](../../../)

---

## CreateRubberStamp(int, Rectangle, string, Color, string) {#createrubberstamp_1}

Crea un'annotazione del timbro di gomma.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string annotContents, Color color, 
    string appearanceFile)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page | Int32 | Il numero della pagina originale in cui verrà creata l'annotazione. |
| annotRect | Rectangle | Il rettangolo di annotazione che definisce la posizione dell'annotazione sulla pagina. |
| annotContents | String | Il contenuto dell'annotazione. |
| color | Color | Il colore dell'annotazione. |
| appearanceFile | String | Il percorso del file di aspetto. |

### Esempi

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red, "appearance_file.pdf");
editor.Save("example_out.pdf");
```

### Guarda anche

* class [PdfContentEditor](../../pdfcontenteditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfcontenteditor)
* assemblea [Aspose.PDF](../../../)

---

## CreateRubberStamp(int, Rectangle, string, Color, Stream) {#createrubberstamp}

Crea un'annotazione del timbro di gomma.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string annotContents, Color color, 
    Stream appearanceStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| page | Int32 | Il numero della pagina originale in cui verrà creata l'annotazione. |
| annotRect | Rectangle | Il rettangolo di annotazione che definisce la posizione dell'annotazione sulla pagina. |
| annotContents | String | Il contenuto dell'annotazione. |
| color | Color | Il colore dell'annotazione. |
| appearanceStream | Stream | Il flusso del file dell'aspetto. |

### Esempi

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

### Guarda anche

* class [PdfContentEditor](../../pdfcontenteditor)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdfcontenteditor)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->