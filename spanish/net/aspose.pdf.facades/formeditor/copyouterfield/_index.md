---
title: CopyOuterField
second_title: Referencia de API de Aspose.PDF para .NET
description: Copia un campo existente de un documento PDF a otro documento con el número de página original y las ordenadas. Aviso solo para campos de AcroForm excepto cuadro de radio.
type: docs
weight: 200
url: /es/net/aspose.pdf.facades/formeditor/copyouterfield/
---
## CopyOuterField(string, string) {#copyouterfield}

Copia un campo existente de un documento PDF a otro documento con el número de página original y las ordenadas. Aviso: solo para campos de AcroForm (excepto cuadro de radio).

```csharp
public void CopyOuterField(string srcFileName, string fieldName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| srcFileName | String | El nombre del documento PDF que contiene el campo que se va a copiar. |
| fieldName | String | El nombre de campo totalmente calificado original. |

### Ejemplos

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
//copia el campo de texto de source.pdf a PdfForm.pdf
formEditor.CopyOuterField("source.pdf", "textField");
formEditor.Save();
```

### Ver también

* class [FormEditor](../../formeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../formeditor)
* asamblea [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int) {#copyouterfield_1}

Copia un campo existente de un documento PDF a otro documento con el número de página especificado y las ordenadas originales. Aviso: solo para campos de AcroForm (excepto el cuadro de radio).

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| srcFileName | String | El nombre del documento PDF que contiene el campo que se va a copiar. |
| fieldName | String | El nombre de campo totalmente calificado original. |
| pageNum | Int32 | El número de página para contener el nuevo campo. Si -1, el nuevo campo se copiará en la misma página que el antiguo alojado. |

### Ejemplos

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField", 2);
formEditor.Save();
```

### Ver también

* class [FormEditor](../../formeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../formeditor)
* asamblea [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int, float, float) {#copyouterfield_2}

Copia un campo existente de un documento PDF a otro documento con el número de página y las ordenadas especificados. Aviso: solo para campos de AcroForm (excepto cuadro de opción).

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum, float abscissa, 
    float ordinate)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| srcFileName | String | El nombre del documento PDF que contiene el campo que se va a copiar. |
| fieldName | String | El nombre de campo totalmente calificado original. |
| pageNum | Int32 | El número de página para contener el nuevo campo. Si -1, el nuevo campo se copiará en la misma página que el antiguo alojado. |
| abscissa | Single | La abscisa del nuevo campo. Si -1, la abscisa se igualará a la original. |
| ordinate | Single | La ordenada del nuevo campo. Si -1, la ordenada se igualará a la original. |

### Ejemplos

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField" , 2, 100, 200);
```

### Ver también

* class [FormEditor](../../formeditor)
* espacio de nombres [Aspose.Pdf.Facades](../../formeditor)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->