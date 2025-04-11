---
title: FormEditor.AddListItem
second_title: Aspose.PDF for .NET API Reference
description: Méthode FormEditor. Ajoute un nouvel élément à la boîte de liste
type: docs
weight: 120
url: /fr/net/aspose.pdf.facades/formeditor/addlistitem/
---
## AddListItem(string, string) {#addlistitem}

Ajoute un nouvel élément à la boîte de liste.

```csharp
public void AddListItem(string fieldName, string itemName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Nom du champ auquel le nouvel élément sera ajouté. |
| itemName | String | Nom du nouvel élément. |

## Exemples

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", PdfForm_out.pdf");
formEditor.AddListItem("listBoxField", "Item 4 (New Item)");
```

### Voir aussi

* classe [FormEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddListItem(string, string[]) {#addlistitem_1}

Ajoute un nouvel élément avec une valeur d'exportation au champ de boîte de liste existant, uniquement pour le champ de boîte combinée AcroForm.

```csharp
public void AddListItem(string fieldName, string[] exportName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Nom du champ auquel les éléments seront ajoutés. |
| exportName | String[] | Un tableau de chaînes désignant un nouvel élément de liste avec une valeur d'exportation, c'est-à-dire (Étiquette de l'élément, Valeur d'exportation). |

## Exemples

```csharp
FormEditor fe = new FormEditor("PdfForm.pdf", "FormEditor_AddListItem2.pdf");
fe.AddListItem("listboxField", new string[] { "4", "Item4(Added)" });
```

### Voir aussi

* classe [FormEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)