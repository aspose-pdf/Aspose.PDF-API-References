---
title: Form.ImportJson
second_title: Aspose.PDF for .NET API Reference
description: Método de formulario. Importa todos los datos de campo de un flujo JSON en los campos del documento que coinciden con los nombres completos de los campos.
type: docs
weight: 290
url: /es/net/aspose.pdf.facades/form/importjson/
---
## Método Form.ImportJson

Importa todos los datos de campo de un flujo JSON en los campos del documento, coincidiendo los campos por sus nombres completos.

```csharp
public void ImportJson(Stream inputJsonStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputJsonStream | Stream | El flujo JSON de entrada que contiene los datos de campo que se importarán en los campos del documento. |

## Ejemplos

```csharp
Form form = new Form("PdfForm.pdf", "Form_ImportJson.pdf");
Stream fs = new FileStream("export_old.json", FileMode.Open, FileAccess.Read);
form.ImportJson(fs);
fs.Close();
form.Save();
```

### Ver También

* clase [Form](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)