---
title: Form.FillImageField
second_title: Aspose.PDF for .NET API Reference
description: Método de formulario. Pega una imagen en el campo de botón existente como su apariencia de acuerdo con su nombre de campo completamente calificado
type: docs
weight: 150
url: /es/net/aspose.pdf.facades/form/fillimagefield/
---
## FillImageField(string, string) {#fillimagefield_1}

Pega una imagen en el campo de botón existente como su apariencia de acuerdo con su nombre de campo completamente calificado.

```csharp
public void FillImageField(string fieldName, string imageFileName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | String | El nombre de campo completamente calificado del campo de botón de imagen. |
| imageFileName | String | La ruta del archivo de imagen, tanto relativa como absoluta son aceptables. |

## Ejemplos

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", "file.jpg");
form.Save();
```

### Ver También

* clase [Form](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## FillImageField(string, Stream) {#fillimagefield}

Sobrecarga de la función FillImageField. La entrada es un flujo de imagen.

```csharp
public void FillImageField(string fieldName, Stream imageStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | String | El nombre de campo completamente calificado. |
| imageStream | Stream | El flujo de la imagen. |

## Ejemplos

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", new FileStream("file.jpg", FileMode.Open, FileAccess.Read));
```

### Ver También

* clase [Form](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)