---
title: Form.FillFields
second_title: Aspose.PDF for .NET API Reference
description: Método Form. Rellena los campos de texto con valores de texto y guarda el documento. Relevante para documentos firmados. Nota: Solo se aplica a Text Box. Tanto los nombres de los campos como los valores son sensibles a mayúsculas y minúsculas.
type: docs
weight: 140
url: /es/net/aspose.pdf.facades/form/fillfields/
---
## Método Form.FillFields

Rellena los campos de texto con valores de texto y guarda el documento. Relevante para documentos firmados. Nota: Solo se aplica a Text Box. Tanto los nombres de los campos como los valores son sensibles a mayúsculas y minúsculas.

```csharp
public bool FillFields(string[] fieldNames, string[] fieldValues, out Stream output)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldNames | String[] | Nombres de los campos. |
| fieldValues | String[] | Nuevos valores de los campos. |
| output | Stream& | Flujo donde se guardará el documento. |

### Valor de Retorno

true si se encontraron los campos y se llenaron con éxito.

## Ejemplos

```csharp
var form = new Form(dataDir + "SignedPdfForm.pdf");
Stream stream; 
form.FillFields(new string[] {"Field1"}, new string[] {"+"}, out stream);
```

### Ver También

* clase [Form](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)