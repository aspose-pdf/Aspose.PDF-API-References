---
title: FormEditor.MoveField
second_title: Aspose.PDF for .NET API Reference
description: Método FormEditor. Establecer nueva posición del campo
type: docs
weight: 200
url: /es/net/aspose.pdf.facades/formeditor/movefield/
---
## Método FormEditor.MoveField

Establecer nueva posición del campo.

```csharp
public bool MoveField(string fieldName, float llx, float lly, float urx, float ury)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | String | Nombre del campo que debe ser movido. |
| llx | Single | Abscisa de la esquina inferior izquierda del campo. |
| lly | Single | Ordenada de la esquina inferior izquierda del campo. |
| urx | Single | Abscisa de la esquina superior derecha del campo. |
| ury | Single | Ordenada de la esquina superior derecha del campo. |

### Valor de Retorno

true si la posición del campo se cambió con éxito.

## Ejemplos

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_MoveField.pdf");
formEditor.MoveField("textField", 20.5f, 20.3f, 120.6f, 40.8f);
```

### Ver También

* clase [FormEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)