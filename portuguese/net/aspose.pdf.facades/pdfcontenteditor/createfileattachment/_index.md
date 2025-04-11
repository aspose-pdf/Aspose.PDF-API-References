---
title: PdfContentEditor.CreateFileAttachment
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Cria anotação de anexo de arquivo
type: docs
weight: 150
url: /pt/net/aspose.pdf.facades/pdfcontenteditor/createfileattachment/
---
## CreateFileAttachment(Rectangle, string, string, int, string) {#createfileattachment_2}

Cria anotação de anexo de arquivo.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rect | Rectangle | O retângulo da anotação que define a localização da anotação na página. |
| contents | String | O conteúdo da anotação. |
| filePath | String | O caminho do arquivo que será anexado. |
| page | Int32 | O número da página original onde a anotação será criada. |
| name | String | O nome de um ícone que será usado na exibição da anotação. Este valor pode ser: "Graph", "PushPin", "Paperclip", "Tag". |

## Exemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph");
editor.Save("example_out.pdf");
```

### Veja Também

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, string, int, string, double) {#createfileattachment_3}

Cria anotação de anexo de arquivo.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, string filePath, int page, 
    string name, double opacity)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rect | Rectangle | O retângulo da anotação que define a localização da anotação na página. |
| contents | String | O conteúdo da anotação. |
| filePath | String | O caminho do arquivo que será anexado. |
| page | Int32 | O número da página original onde a anotação será criada. |
| name | String | O nome de um ícone que será usado na exibição da anotação. Este valor pode ser: "Graph", "PushPin", "Paperclip", "Tag". |
| opacity | Double | Opacidade do ícone de 0 a 1: 0 - completamente transparente, 1 - completamente opaco. |

## Exemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
    "Welcome to Aspose", "attachment_file.pdf", 1, "Graph", 0.5);
editor.Save("example_out.pdf");
```

### Veja Também

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string) {#createfileattachment}

Cria anotação de anexo de arquivo.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rect | Rectangle | O retângulo da anotação que define a localização da anotação na página. |
| contents | String | O conteúdo da anotação. |
| attachmentStream | Stream | O fluxo do arquivo de anexo. |
| attachmentName | String | O nome do anexo. |
| page | Int32 | O número da página original onde a anotação será criada. |
| name | String | O nome de um ícone que será usado na exibição da anotação. Este valor pode ser: "Graph", "PushPin", "Paperclip", "Tag". |

## Exemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using(System.IO.FileStream attStream = System.IO.File.OpenRead("attachment_file.pdf"))
{
    editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
        "Welcome to Aspose", attStream, "attachment_file.pdf", 1, "Graph");
    editor.Save("example_out.pdf");
}
```

### Veja Também

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CreateFileAttachment(Rectangle, string, Stream, string, int, string, double) {#createfileattachment_1}

Cria anotação de anexo de arquivo.

```csharp
public void CreateFileAttachment(Rectangle rect, string contents, Stream attachmentStream, 
    string attachmentName, int page, string name, double opacity)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| rect | Rectangle | O retângulo da anotação que define a localização da anotação na página. |
| contents | String | O conteúdo da anotação. |
| attachmentStream | Stream | O fluxo do arquivo de anexo. |
| attachmentName | String | O nome do anexo. |
| page | Int32 | O número da página original onde a anotação será criada. |
| name | String | O nome de um ícone que será usado na exibição da anotação. Este valor pode ser: "Graph", "PushPin", "Paperclip", "Tag". |
| opacity | Double | Opacidade do ícone de 0 a 1: 0 - completamente transparente, 1 - completamente opaco. |

## Exemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using(System.IO.FileStream attStream = System.IO.File.OpenRead("attachment_file.pdf"))
{
    editor.CreateFileAttachment(new System.Drawing.Rectangle(0, 0, 100, 100),
        "Welcome to Aspose", attStream, "attachment_file.pdf", 1, "Graph", 0.5);
    editor.Save("example_out.pdf");
}
```

### Veja Também

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)