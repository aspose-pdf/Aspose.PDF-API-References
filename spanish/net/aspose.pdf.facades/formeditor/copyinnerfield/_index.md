---
title: FormEditor.CopyInnerField
second_title: Aspose.PDF for .NET API Reference
description: Método FormEditor. Copia un campo existente a la misma posición en el número de página especificado. Se producirá un nuevo documento que contiene todo lo que tiene el documento fuente, excepto por el campo copiado recientemente.
type: docs
weight: 150
url: /es/net/aspose.pdf.facades/formeditor/copyinnerfield/
---
## CopyInnerField(string, string, int) {#copyinnerfield}

Copia un campo existente a la misma posición en el número de página especificado. Se producirá un nuevo documento, que contiene todo lo que tiene el documento fuente, excepto por el campo copiado recientemente.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | String | El antiguo nombre de campo completamente calificado. |
| newFieldName | String | El nuevo nombre de campo completamente calificado. Si es nulo, se establecerá como fieldName + "~". |
| pageNum | Int32 | El número de página para contener el nuevo campo. Si es -1, el nuevo campo se copiará a la misma página que el antiguo. |

## Ejemplos

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//Creates copy of text field on psecond page.
formEditor.CopyInnerField("textField", "textFieldCopy", 2);
```

### Ver También

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyInnerField(string, string, int, float, float) {#copyinnerfield_1}

Copia un campo existente a una nueva posición especificada por el número de página y las coordenadas. Se producirá un nuevo documento, que contiene todo lo que tiene el documento fuente, excepto por el campo copiado recientemente.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum, float abscissa, 
    float ordinate)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fieldName | String | El antiguo nombre de campo completamente calificado. |
| newFieldName | String | El nuevo nombre de campo completamente calificado. Si es nulo, se establecerá como fieldName + "~". |
| pageNum | Int32 | El número de página para contener el nuevo campo. Si es -1, el nuevo campo se copiará a la misma página que el antiguo. |
| abscissa | Single | La abscisa del nuevo campo. Si es -1, la abscisa será igual a la original. |
| ordinate | Single | La ordenada del nuevo campo. Si es -1, la ordenada será igual a la original. |

## Ejemplos

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//Creates copy of text field on psecond page.
formEditor.CopyInnerField("textField", "textFieldCopy", 2, 100, 200);
```

### Ver También

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)