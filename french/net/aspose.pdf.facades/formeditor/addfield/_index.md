---
title: FormEditor.AddField
second_title: Aspose.PDF for .NET API Reference
description: Méthode FormEditor. Ajouter un champ de type spécifié au formulaire
type: docs
weight: 100
url: /fr/net/aspose.pdf.facades/formeditor/addfield/
---
## AddField(FieldType, string, int, float, float, float, float) {#addfield}

Ajouter un champ de type spécifié au formulaire.

```csharp
public bool AddField(FieldType fieldType, string fieldName, int pageNum, float llx, float lly, 
    float urx, float ury)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldType | FieldType | Type du champ qui doit être ajouté. |
| fieldName | String | Nom du champ qui doit être ajouté. |
| pageNum | Int32 | Numéro de page où le nouveau champ doit être placé. |
| llx | Single | Abscisse du coin inférieur gauche du champ. |
| lly | Single | Ordonnée du coin inférieur gauche du champ. |
| urx | Single | Abscisse du coin supérieur droit du champ. |
| ury | Single | Ordonnée du coin supérieur droit du champ. |

### Valeur de retour

true si le champ a été ajouté avec succès.

## Exemples

```csharp
FormEditor formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_Text.pdf");
formEditor.AddField(FieldType.Text, "AddedTextField",  1, 10, 30, 110, 46);
formEditor.Save();
```

### Voir aussi

* enum [FieldType](../../fieldtype/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddField(FieldType, string, string, int, float, float, float, float) {#addfield_1}

Ajouter un champ de type spécifié au formulaire.

```csharp
public bool AddField(FieldType fieldType, string fieldName, string initValue, int pageNum, 
    float llx, float lly, float urx, float ury)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldType | FieldType | Type du champ qui doit être ajouté. |
| fieldName | String | Nom du champ qui doit être ajouté. |
| initValue | String | Valeur initiale du champ. |
| pageNum | Int32 | Numéro de page où le nouveau champ doit être placé. |
| llx | Single | Abscisse du coin inférieur gauche du champ. |
| lly | Single | Ordonnée du coin inférieur gauche du champ. |
| urx | Single | Abscisse du coin supérieur droit du champ. |
| ury | Single | Ordonnée du coin supérieur droit du champ. |

### Valeur de retour

true si le champ a été ajouté avec succès.

## Exemples

```csharp
FormEditor formEditor = new Aspose.Pdf.Facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_Text.pdf");
formEditor.AddField(FieldType.Text, "AddedTextField", "Text Value", 1, 10, 30, 110, 46);
formEditor.Items = new string[] { "Item1", "Item2", Item3" };
formEditor.AddField(FieldType.Radio, "RadioButtonField", 1, 265, 695, 365, 720);
formEditor.Save();
```

### Voir aussi

* enum [FieldType](../../fieldtype/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)