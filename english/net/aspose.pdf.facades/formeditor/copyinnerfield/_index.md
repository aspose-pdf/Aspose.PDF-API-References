---
title: "FormEditor.CopyInnerField"
linktitle: "CopyInnerField"
articleTitle: "CopyInnerField"
second_title: "Aspose.PDF for .NET"
description: "Copies an existing field to the same position in specified page number. A new document will be produced, which contains everything the source document has ex..."
type: docs
weight: 210
url: "/net/aspose.pdf.facades/formeditor/copyinnerfield/"
product_version: "26.9.0"
---
## CopyInnerField(string, string, int) {#copyinnerfield}

Copies an existing field to the same position in specified page number.
 A new document will be produced, which contains everything the source document has except for the newly copied field.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | string | The old fully qualified field name. |
| newFieldName | string | The new fully qualified field name. If null, it will be set as fieldName + "~". |
| pageNum | int | The number of page to hold the new field. If -1, new field will be copid to the same page as old one hosted. |

### See Also

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyInnerField(string, string, int, float, float) {#copyinnerfield_1}

Copies an existing field to a new position specified by both page number and ordinates.
 A new document will be produced, which contains everything the source document has except for the newly copied field.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum, float abscissa, float ordinate)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | string | The old fully qualified field name. |
| newFieldName | string | The new fully qualified field name. If null, it will be set as fieldName + "~". |
| pageNum | int | The number of page to hold the new field. If -1, new field will be copid to the same page as old one hosted. |
| abscissa | float | The abscissa of the new field. If -1, the abscissa will be equaled to the original one. |
| ordinate | float | The ordinate of the new field. If -1, the ordinate will be equaled to the original one. |

### See Also

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

