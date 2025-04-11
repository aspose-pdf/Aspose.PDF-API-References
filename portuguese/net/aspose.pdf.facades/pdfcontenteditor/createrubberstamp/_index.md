---
title: PdfContentEditor.CreateRubberStamp
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Cria uma anotação de carimbo de borracha
type: docs
weight: 260
url: /pt/net/aspose.pdf.facades/pdfcontenteditor/createrubberstamp/
---
## CreateRubberStamp(int, Rectangle, string, string, Color) {#createrubberstamp_2}

Cria uma anotação de carimbo de borracha.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string icon, string annotContents, 
    Color color)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| page | Int32 | O número da página original onde a anotação será criada. |
| annotRect | Rectangle | O retângulo da anotação que define a localização da anotação na página. |
| icon | String | Um ícone a ser usado na exibição da anotação. Valor padrão: 'Draft'. |
| annotContents | String | O conteúdo da anotação. |
| color | Color | A cor da anotação. |

## Exemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### Veja Também

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateRubberStamp(int, Rectangle, string, Color, string) {#createrubberstamp_1}

Cria uma anotação de carimbo de borracha.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string annotContents, Color color, 
    string appearanceFile)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| page | Int32 | O número da página original onde a anotação será criada. |
| annotRect | Rectangle | O retângulo da anotação que define a localização da anotação na página. |
| annotContents | String | O conteúdo da anotação. |
| color | Color | A cor da anotação. |
| appearanceFile | String | O caminho do arquivo de aparência. |

## Exemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red, "appearance_file.pdf");
editor.Save("example_out.pdf");
```

### Veja Também

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateRubberStamp(int, Rectangle, string, Color, Stream) {#createrubberstamp}

Cria uma anotação de carimbo de borracha.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string annotContents, Color color, 
    Stream appearanceStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| page | Int32 | O número da página original onde a anotação será criada. |
| annotRect | Rectangle | O retângulo da anotação que define a localização da anotação na página. |
| annotContents | String | O conteúdo da anotação. |
| color | Color | A cor da anotação. |
| appearanceStream | Stream | O fluxo do arquivo de aparência. |

## Exemplos

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

### Veja Também

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)