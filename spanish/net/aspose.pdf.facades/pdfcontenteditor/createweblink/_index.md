---
title: PdfContentEditor.CreateWebLink
second_title: Aspose.PDF for .NET API Reference
description: Método PdfContentEditor. Crea un enlace web en el documento PDF
type: docs
weight: 300
url: /es/net/aspose.pdf.facades/pdfcontenteditor/createweblink/
---
## CreateWebLink(Rectangle, string, int, Color, Enum[]) {#createweblink_2}

Crea un enlace web en el documento PDF.

```csharp
public void CreateWebLink(Rectangle rect, string url, int originalPage, Color clr, 
    Enum[] actionName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | Rectangle | El rectángulo para el clic activo. |
| url | String | El destino del enlace web. |
| originalPage | Int32 | El número de la página original en la que se creará el rectángulo vinculado con el enlace web. |
| clr | Color | El color del rectángulo para el clic activo. |
| actionName | Enum[] | El arreglo de acciones (miembros del enum PredefinedAction) correspondientes a la ejecución de elementos de menú en el visor de Acrobat. |

## Ejemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateWebLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "http://www.aspose.com", 1, System.Drawing.Color.Red,
    new Enum[] { PredefinedAction.FirstPage, PredefinedAction.PrintDialog });
editor.Save("example_out.pdf");
```

### Ver También

* clase [PdfContentEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## CreateWebLink(Rectangle, string, int, Color) {#createweblink_1}

Crea un enlace web en el documento PDF.

```csharp
public void CreateWebLink(Rectangle rect, string url, int originalPage, Color clr)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | Rectangle | El rectángulo para el clic activo. |
| url | String | El destino del enlace web. |
| originalPage | Int32 | El número de la página original donde se creará el rectángulo vinculado con el enlace web. |
| clr | Color | El color del rectángulo para el clic activo. |

## Ejemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateWebLink(new System.Drawing.Rectangle(0, 0, 100, 100),
    "http://www.aspose.com", 1, System.Drawing.Color.Red });
editor.Save("example_out.pdf");
```

### Ver También

* clase [PdfContentEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## CreateWebLink(Rectangle, string, int) {#createweblink}

Crea un enlace web en el documento PDF.

```csharp
public void CreateWebLink(Rectangle rect, string url, int originalPage)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | Rectangle | El rectángulo para el clic activo. |
| url | String | El destino del enlace web. |
| originalPage | Int32 | El número de la página original donde se creará el rectángulo vinculado con el enlace web. |

## Ejemplos

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.CreateWebLink(new System.Drawing.Rectangle(0, 0, 100, 100), "http://www.aspose.com", 1 });
editor.Save("example_out.pdf");
```

### Ver También

* clase [PdfContentEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)