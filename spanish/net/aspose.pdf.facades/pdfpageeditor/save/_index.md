---
title: PdfPageEditor.Save
second_title: Aspose.PDF for .NET API Reference
description: Método PdfPageEditor. Guarda el documento modificado en un archivo
type: docs
weight: 180
url: /es/net/aspose.pdf.facades/pdfpageeditor/save/
---
## Save(string) {#save_1}

Guarda el documento modificado en un archivo.

```csharp
public override void Save(string outputFile)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputFile | String | Ruta al archivo donde se guardará el documento. |

## Ejemplos

El siguiente ejemplo demuestra cómo guardar un documento PDF modificado.

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### Ver También

* clase [PdfPageEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## Save(Stream) {#save}

Guarda el documento modificado en un flujo.

```csharp
public override void Save(Stream outputStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| outputStream | Stream | Flujo donde se guardará el documento PDF modificado. |

## Ejemplos

El siguiente ejemplo demuestra cómo guardar un documento PDF modificado en un flujo.

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### Ver También

* clase [PdfPageEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)