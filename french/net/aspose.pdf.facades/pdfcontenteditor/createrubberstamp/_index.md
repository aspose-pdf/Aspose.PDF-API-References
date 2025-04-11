---
title: PdfContentEditor.CreateRubberStamp
second_title: Aspose.PDF for .NET API Reference
description: Méthode PdfContentEditor. Crée une annotation de tampon en caoutchouc
type: docs
weight: 260
url: /fr/net/aspose.pdf.facades/pdfcontenteditor/createrubberstamp/
---
## CreateRubberStamp(int, Rectangle, string, string, Color) {#createrubberstamp_2}

Crée une annotation de tampon en caoutchouc.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string icon, string annotContents, 
    Color color)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| page | Int32 | Le numéro de la page originale où l'annotation sera créée. |
| annotRect | Rectangle | Le rectangle d'annotation définissant l'emplacement de l'annotation sur la page. |
| icon | String | Une icône à utiliser pour afficher l'annotation. Valeur par défaut : 'Brouillon'. |
| annotContents | String | Le contenu de l'annotation. |
| color | Color | La couleur de l'annotation. |

## Exemples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red);
editor.Save("example_out.pdf");
```

### Voir aussi

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateRubberStamp(int, Rectangle, string, Color, string) {#createrubberstamp_1}

Crée une annotation de tampon en caoutchouc.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string annotContents, Color color, 
    string appearanceFile)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| page | Int32 | Le numéro de la page originale où l'annotation sera créée. |
| annotRect | Rectangle | Le rectangle d'annotation définissant l'emplacement de l'annotation sur la page. |
| annotContents | String | Le contenu de l'annotation. |
| color | Color | La couleur de l'annotation. |
| appearanceFile | String | Le chemin du fichier d'apparence. |

## Exemples

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateRubberStamp(1, System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", System.Drawing.Color.Red, "appearance_file.pdf");
editor.Save("example_out.pdf");
```

### Voir aussi

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateRubberStamp(int, Rectangle, string, Color, Stream) {#createrubberstamp}

Crée une annotation de tampon en caoutchouc.

```csharp
public void CreateRubberStamp(int page, Rectangle annotRect, string annotContents, Color color, 
    Stream appearanceStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| page | Int32 | Le numéro de la page originale où l'annotation sera créée. |
| annotRect | Rectangle | Le rectangle d'annotation définissant l'emplacement de l'annotation sur la page. |
| annotContents | String | Le contenu de l'annotation. |
| color | Color | La couleur de l'annotation. |
| appearanceStream | Stream | Le flux du fichier d'apparence. |

## Exemples

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

### Voir aussi

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)