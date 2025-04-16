---
title: FormEditor.CopyOuterField
second_title: Aspose.PDF for .NET API Reference
description: Método FormEditor. Copia un campo existente de un documento PDF a otro documento con el número de página original y las ordenadas. Nota: Solo para campos AcroForm.
type: docs
weight: 160
url: /es/net/aspose.pdf.facades/formeditor/copyouterfield/
---
## CopyOuterField(string, string) {#copyouterfield}

Copia un campo existente de un documento PDF a otro documento con el número de página original y las ordenadas. Nota: Solo para campos AcroForm (excluyendo el cuadro de radio).

```csharp
public void CopyOuterField(string srcFileName, string fieldName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcFileName | String | El nombre del documento PDF que contiene el campo a copiar. |
| fieldName | String | El nombre del campo completamente calificado original. |

## Ejemplos

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
//copies text field from source.pdf to PdfForm.pdf
formEditor.CopyOuterField("source.pdf", "textField");
formEditor.Save();
```

### Véase también

* clase [FormEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int) {#copyouterfield_1}

Copia un campo existente de un documento PDF a otro documento con el número de página especificado y las ordenadas originales. Nota: Solo para campos AcroForm (excluyendo el cuadro de radio).

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcFileName | String | El nombre del documento PDF que contiene el campo a copiar. |
| fieldName | String | El nombre del campo completamente calificado original. |
| pageNum | Int32 | El número de página que contendrá el nuevo campo. Si es -1, el nuevo campo se copiará a la misma página que el antiguo. |

## Ejemplos

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField", 2);
formEditor.Save();
```

### Véase también

* clase [FormEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int, float, float) {#copyouterfield_2}

Copia un campo existente de un documento PDF a otro documento con el número de página especificado y las ordenadas. Nota: Solo para campos AcroForm (excluyendo el cuadro de radio).

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum, float abscissa, 
    float ordinate)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcFileName | String | El nombre del documento PDF que contiene el campo a copiar. |
| fieldName | String | El nombre del campo completamente calificado original. |
| pageNum | Int32 | El número de página que contendrá el nuevo campo. Si es -1, el nuevo campo se copiará a la misma página que el antiguo. |
| abscissa | Single | La abscisa del nuevo campo. Si es -1, la abscisa será igual a la original. |
| ordinate | Single | La ordenada del nuevo campo. Si es -1, la ordenada será igual a la original. |

## Ejemplos

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField" , 2, 100, 200);
```

### Véase también

* clase [FormEditor](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)