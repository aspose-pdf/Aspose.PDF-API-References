---
title: CopyInnerField
second_title: Referencia de API de Aspose.PDF para .NET
description: Copia un campo existente en la misma posición en el número de página especificado. Se producirá un nuevo documento que contiene todo lo que tiene el documento de origen excepto el campo recién copiado.
type: docs
weight: 190
url: /es/net/aspose.pdf.facades/formeditor/copyinnerfield/
---
## CopyInnerField(string, string, int) {#copyinnerfield}

Copia un campo existente en la misma posición en el número de página especificado. Se producirá un nuevo documento, que contiene todo lo que tiene el documento de origen excepto el campo recién copiado.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fieldName | String | El antiguo nombre de campo completo. |
| newFieldName | String | El nuevo nombre de campo completo. Si es nulo, se establecerá como fieldName + "~". |
| pageNum | Int32 | El número de página para contener el nuevo campo. Si -1, el nuevo campo se copiará en la misma página que el antiguo alojado. |

### Ejemplos

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//Crea una copia del campo de texto en la segunda página.
formEditor.CopyInnerField("textField", "textFieldCopy", 2);
```

### Ver también

* class [FormEditor](../../formeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../formeditor)
* asamblea [Aspose.PDF](../../../)

---

## CopyInnerField(string, string, int, float, float) {#copyinnerfield_1}

Copia un campo existente en una nueva posición especificada tanto por el número de página como por las ordenadas. Se producirá un nuevo documento, que contiene todo lo que tiene el documento de origen excepto el campo recién copiado.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum, float abscissa, 
    float ordinate)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| fieldName | String | El antiguo nombre de campo completo. |
| newFieldName | String | El nuevo nombre de campo completo. Si es nulo, se establecerá como fieldName + "~". |
| pageNum | Int32 | El número de página para contener el nuevo campo. Si -1, el nuevo campo se copiará en la misma página que el antiguo alojado. |
| abscissa | Single | La abscisa del nuevo campo. Si -1, la abscisa se igualará a la original. |
| ordinate | Single | La ordenada del nuevo campo. Si -1, la ordenada se igualará a la original. |

### Ejemplos

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//Crea una copia del campo de texto en la segunda página.
formEditor.CopyInnerField("textField", "textFieldCopy", 2, 100, 200);
```

### Ver también

* class [FormEditor](../../formeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../formeditor)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->