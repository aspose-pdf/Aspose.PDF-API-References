---
title: FormEditor.AddField
second_title: Aspose.PDF for .NET API Reference
description: FormEditor-Methode. Fügen Sie ein Feld des angegebenen Typs zum Formular hinzu
type: docs
weight: 100
url: /de/net/aspose.pdf.facades/formeditor/addfield/
---
## AddField(FieldType, string, int, float, float, float, float) {#addfield}

Fügen Sie ein Feld des angegebenen Typs zum Formular hinzu.

```csharp
public bool AddField(FieldType fieldType, string fieldName, int pageNum, float llx, float lly, 
    float urx, float ury)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldType | FieldType | Typ des Feldes, das hinzugefügt werden muss. |
| fieldName | String | Name des Feldes, das hinzugefügt werden muss. |
| pageNum | Int32 | Seitennummer, auf der das neue Feld platziert werden muss. |
| llx | Single | Abszisse der unteren linken Ecke des Feldes. |
| lly | Single | Ordinate der unteren linken Ecke des Feldes. |
| urx | Single | Abszisse der oberen rechten Ecke des Feldes. |
| ury | Single | Ordinate der oberen rechten Ecke des Feldes. |

### Rückgabewert

true, wenn das Feld erfolgreich hinzugefügt wurde.

## Beispiele

```csharp
FormEditor formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_Text.pdf");
formEditor.AddField(FieldType.Text, "AddedTextField",  1, 10, 30, 110, 46);
formEditor.Save();
```

### Siehe auch

* enum [FieldType](../../fieldtype/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddField(FieldType, string, string, int, float, float, float, float) {#addfield_1}

Fügen Sie ein Feld des angegebenen Typs zum Formular hinzu.

```csharp
public bool AddField(FieldType fieldType, string fieldName, string initValue, int pageNum, 
    float llx, float lly, float urx, float ury)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldType | FieldType | Typ des Feldes, das hinzugefügt werden muss. |
| fieldName | String | Name des Feldes, das hinzugefügt werden muss. |
| initValue | String | Anfangswert des Feldes. |
| pageNum | Int32 | Seitennummer, auf der das neue Feld platziert werden muss. |
| llx | Single | Abszisse der unteren linken Ecke des Feldes. |
| lly | Single | Ordinate der unteren linken Ecke des Feldes. |
| urx | Single | Abszisse der oberen rechten Ecke des Feldes. |
| ury | Single | Ordinate der oberen rechten Ecke des Feldes. |

### Rückgabewert

true, wenn das Feld erfolgreich hinzugefügt wurde.

## Beispiele

```csharp
FormEditor formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_Text.pdf");
formEditor.AddField(FieldType.Text, "AddedTextField", "Text Value", 1, 10, 30, 110, 46);
formEditor.Items = new string[] { "Item1", "Item2", Item3" };
formEditor.AddField(FieldType.Radio, "RadioButtonField", 1, 265, 695, 365, 720);
formEditor.Save();
```

### Siehe auch

* enum [FieldType](../../fieldtype/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)