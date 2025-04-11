---
title: FormEditor.AddField
second_title: Aspose.PDF for .NET API Reference
description: FormEditor metod. Lägg till fält av angiven typ till formuläret
type: docs
weight: 100
url: /sv/net/aspose.pdf.facades/formeditor/addfield/
---
## AddField(FieldType, string, int, float, float, float, float) {#addfield}

Lägg till fält av angiven typ till formuläret.

```csharp
public bool AddField(FieldType fieldType, string fieldName, int pageNum, float llx, float lly, 
    float urx, float ury)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldType | FieldType | Typ av fältet som måste läggas till. |
| fieldName | String | Namn på fältet som måste läggas till. |
| pageNum | Int32 | Sidnummer där det nya fältet måste placeras. |
| llx | Single | Abscissa för det nedre vänstra hörnet av fältet. |
| lly | Single | Ordinate för det nedre vänstra hörnet av fältet. |
| urx | Single | Abscissa för det övre högra hörnet av fältet. |
| ury | Single | Ordinate för det övre högra hörnet av fältet. |

### Return Value

true om fältet framgångsrikt lades till.

## Examples

```csharp
FormEditor formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_Text.pdf");
formEditor.AddField(FieldType.Text, "AddedTextField",  1, 10, 30, 110, 46);
formEditor.Save();
```

### See Also

* enum [FieldType](../../fieldtype/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddField(FieldType, string, string, int, float, float, float, float) {#addfield_1}

Lägg till fält av angiven typ till formuläret.

```csharp
public bool AddField(FieldType fieldType, string fieldName, string initValue, int pageNum, 
    float llx, float lly, float urx, float ury)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldType | FieldType | Typ av fältet som måste läggas till. |
| fieldName | String | Namn på fältet som måste läggas till. |
| initValue | String | Initialt värde för fältet. |
| pageNum | Int32 | Sidnummer där det nya fältet måste placeras. |
| llx | Single | Abscissa för det nedre vänstra hörnet av fältet. |
| lly | Single | Ordinate för det nedre vänstra hörnet av fältet. |
| urx | Single | Abscissa för det övre högra hörnet av fältet. |
| ury | Single | Ordinate för det övre högra hörnet av fältet. |

### Return Value

true om fältet framgångsrikt lades till.

## Examples

```csharp
FormEditor formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_Text.pdf");
formEditor.AddField(FieldType.Text, "AddedTextField", "Text Value", 1, 10, 30, 110, 46);
formEditor.Items = new string[] { "Item1", "Item2", Item3" };
formEditor.AddField(FieldType.Radio, "RadioButtonField", 1, 265, 695, 365, 720);
formEditor.Save();
```

### See Also

* enum [FieldType](../../fieldtype/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)