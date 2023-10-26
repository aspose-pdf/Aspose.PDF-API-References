---
title: FormEditor.CopyInnerField
second_title: Aspose.PDF for .NET API Reference
description: FormEditor method. Copies an existing field to the same position in specified page number. A new document will be produced which contains everything the source document has except for the newly copied field
type: docs
weight: 190
url: /net/aspose.pdf.facades/formeditor/copyinnerfield/
---
## CopyInnerField(string, string, int) {#copyinnerfield}

Copies an existing field to the same position in specified page number. A new document will be produced, which contains everything the source document has except for the newly copied field.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | The old fully qualified field name. |
| newFieldName | String | The new fully qualified field name. If null, it will be set as fieldName + "~". |
| pageNum | Int32 | The number of page to hold the new field. If -1, new field will be copid to the same page as old one hosted. |

## Examples

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//Creates copy of text field on psecond page.
formEditor.CopyInnerField("textField", "textFieldCopy", 2);
```

### See Also

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyInnerField(string, string, int, float, float) {#copyinnerfield_1}

Copies an existing field to a new position specified by both page number and ordinates. A new document will be produced, which contains everything the source document has except for the newly copied field.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum, float abscissa, 
    float ordinate)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | The old fully qualified field name. |
| newFieldName | String | The new fully qualified field name. If null, it will be set as fieldName + "~". |
| pageNum | Int32 | The number of page to hold the new field. If -1, new field will be copid to the same page as old one hosted. |
| abscissa | Single | The abscissa of the new field. If -1, the abscissa will be equaled to the original one. |
| ordinate | Single | The ordinate of the new field. If -1, the ordinate will be equaled to the original one. |

## Examples

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//Creates copy of text field on psecond page.
formEditor.CopyInnerField("textField", "textFieldCopy", 2, 100, 200);
```

### See Also

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


