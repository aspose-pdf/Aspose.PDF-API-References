---
title: FormEditor.SetFieldCombNumber
second_title: Aspose.PDF for .NET API Reference
description: Método FormEditor. Establece el número de compartimentos para un campo de texto de una sola línea regular; el campo se divide automáticamente en tantas posiciones o compartimentos igualmente espaciados como el valor del parámetro combNumber.
type: docs
weight: 300
url: /es/net/aspose.pdf.facades/formeditor/setfieldcombnumber/
---
## Método FormEditor.SetFieldCombNumber

Establece el número de compartimentos para un campo de texto de una sola línea regular (el campo se divide automáticamente en tantas posiciones, o compartimentos, igualmente espaciados como el valor del parámetro combNumber).

```csharp
public bool SetFieldCombNumber(string fieldName, int combNumber)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | String | El nombre del campo calificado. |
| combNumber | Int32 | El número de compartimentos en los que dividir el campo. |

### Valor de Retorno

Si tiene éxito, devuelve true; de lo contrario, false.

## Ejemplos

```csharp
FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf"));
formEditor.SetFieldCombNumber("textCombField", 5);
```

### Ver También

* clase [FormEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblaje [Aspose.PDF](../../../)