---
title: "FormEditor.CopyOuterField"
linktitle: "CopyOuterField"
articleTitle: "CopyOuterField"
second_title: "Aspose.PDF for .NET API Reference"
description: "FormEditor method. Copies an existing field from one PDF document to another document with original page number and ordinates. Notice: Only for AcroForm fiel..."
type: docs
weight: 180
url: "/net/aspose.pdf.facades/formeditor/copyouterfield/"
product_version: "26.9.0"
---
## CopyOuterField(string, string) {#copyouterfield}

Copies an existing field from one PDF document to another document with original page number and ordinates.
 Notice: Only for AcroForm fields (excluding radio box).

```csharp
public void CopyOuterField(string srcFileName, string fieldName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | String | The name of PDF document which containes the field to be copied. |
| fieldName | String | The original fully qualified field name. |

### See Also

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int) {#copyouterfield_1}

Copies an existing field from one PDF document to another document with specified page number and original ordinates.
 Notice: Only for AcroForm fields (excluding radio box).

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | String | The name of PDF document which containes the field to be copied. |
| fieldName | String | The original fully qualified field name. |
| pageNum | Int32 | The number of page to hold the new field. If -1, new field will be copid to the same page as old one hosted. |

### See Also

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int, float, float) {#copyouterfield_2}

Copies an existing field from one PDF document to another document with specified page number and ordinates.
 Notice: Only for AcroForm fields (excluding radio box).

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum, float abscissa, 
    float ordinate)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | String | The name of PDF document which containes the field to be copied. |
| fieldName | String | The original fully qualified field name. |
| pageNum | Int32 | The number of page to hold the new field. If -1, new field will be copid to the same page as old one hosted. |
| abscissa | Single | The abscissa of the new field. If -1, the abscissa will be equaled to the original one. |
| ordinate | Single | The ordinate of the new field. If -1, the ordinate will be equaled to the original one. |

### See Also

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

