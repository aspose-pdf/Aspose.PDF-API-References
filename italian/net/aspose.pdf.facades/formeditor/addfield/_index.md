---
title: FormEditor.AddField
second_title: Aspose.PDF for .NET API Reference
description: Metodo FormEditor. Aggiungi campo di tipo specificato al modulo
type: docs
weight: 100
url: /it/net/aspose.pdf.facades/formeditor/addfield/
---
## AddField(FieldType, string, int, float, float, float, float) {#addfield}

Aggiungi campo di tipo specificato al modulo.

```csharp
public bool AddField(FieldType fieldType, string fieldName, int pageNum, float llx, float lly, 
    float urx, float ury)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldType | FieldType | Tipo del campo che deve essere aggiunto. |
| fieldName | String | Nome del campo che deve essere aggiunto. |
| pageNum | Int32 | Numero di pagina dove il nuovo campo deve essere posizionato. |
| llx | Single | Ascissa dell'angolo in basso a sinistra del campo. |
| lly | Single | Ordinata dell'angolo in basso a sinistra del campo. |
| urx | Single | Ascissa dell'angolo in alto a destra del campo. |
| ury | Single | Ordinata dell'angolo in alto a destra del campo. |

### Return Value

true se il campo è stato aggiunto con successo.

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

Aggiungi campo di tipo specificato al modulo.

```csharp
public bool AddField(FieldType fieldType, string fieldName, string initValue, int pageNum, 
    float llx, float lly, float urx, float ury)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldType | FieldType | Tipo del campo che deve essere aggiunto. |
| fieldName | String | Nome del campo che deve essere aggiunto. |
| initValue | String | Valore iniziale del campo. |
| pageNum | Int32 | Numero di pagina dove il nuovo campo deve essere posizionato. |
| llx | Single | Ascissa dell'angolo in basso a sinistra del campo. |
| lly | Single | Ordinata dell'angolo in basso a sinistra del campo. |
| urx | Single | Ascissa dell'angolo in alto a destra del campo. |
| ury | Single | Ordinata dell'angolo in alto a destra del campo. |

### Return Value

true se il campo è stato aggiunto con successo.

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