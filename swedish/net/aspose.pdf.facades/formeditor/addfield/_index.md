---
title: "FormEditor.AddField"
second_title: "Aspose.PDF för .NET API‑referens"
description: "FormEditor-metod. Lägg till fält av angiven typ i formuläret"
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
| fieldType | FieldType | Typ av fält som ska läggas till. |
| fieldName | String | Namnet på fältet som ska läggas till. |
| pageNum | Int32 | Sidnummer där det nya fältet ska placeras. |
| llx | Single | Abskissa för fältets nedre vänstra hörn. |
| lly | Single | Koordinat för fältets nedre vänstra hörn. |
| urx | Single | Abskissa för fältets övre högra hörn. |
| ury | Single | Ordinat för fältets övre högra hörn. |

### Returvärde

true om fältet lades till framgångsrikt.

## Exempel

```csharp
FormEditor formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_Text.pdf");
formEditor.AddField(FieldType.Text, "AddedTextField",  1, 10, 30, 110, 46);
formEditor.Save();
```

### Se även

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
| fieldType | FieldType | Typ av fält som ska läggas till. |
| fieldName | String | Namnet på fältet som ska läggas till. |
| initValue | String | Initialvärde för fältet. |
| pageNum | Int32 | Sidnummer där det nya fältet ska placeras. |
| llx | Single | Abskissa för fältets nedre vänstra hörn. |
| lly | Single | Koordinat för fältets nedre vänstra hörn. |
| urx | Single | Abskissa för fältets övre högra hörn. |
| ury | Single | Ordinat för fältets övre högra hörn. |

### Returvärde

true om fältet lades till framgångsrikt.

## Exempel

```csharp
FormEditor formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_Text.pdf");
formEditor.AddField(FieldType.Text, "AddedTextField", "Text Value", 1, 10, 30, 110, 46);
formEditor.Items = new string[] { "Item1", "Item2", Item3" };
formEditor.AddField(FieldType.Radio, "RadioButtonField", 1, 265, 695, 365, 720);
formEditor.Save();
```

### Se även

* enum [FieldType](../../fieldtype/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


