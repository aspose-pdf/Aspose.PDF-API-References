---
title: FormEditor.CopyInnerField
second_title: Aspose.PDF for .NET API Reference
description: Méthode FormEditor. Copie un champ existant à la même position dans le numéro de page spécifié. Un nouveau document sera produit, qui contient tout ce que le document source a sauf pour le champ nouvellement copié.
type: docs
weight: 150
url: /fr/net/aspose.pdf.facades/formeditor/copyinnerfield/
---
## CopyInnerField(string, string, int) {#copyinnerfield}

Copie un champ existant à la même position dans le numéro de page spécifié. Un nouveau document sera produit, qui contient tout ce que le document source a sauf pour le champ nouvellement copié.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | L'ancien nom de champ entièrement qualifié. |
| newFieldName | String | Le nouveau nom de champ entièrement qualifié. Si null, il sera défini comme fieldName + "~". |
| pageNum | Int32 | Le numéro de page pour contenir le nouveau champ. Si -1, le nouveau champ sera copié sur la même page que l'ancien. |

## Exemples

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//Creates copy of text field on psecond page.
formEditor.CopyInnerField("textField", "textFieldCopy", 2);
```

### Voir aussi

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyInnerField(string, string, int, float, float) {#copyinnerfield_1}

Copie un champ existant à une nouvelle position spécifiée par le numéro de page et les ordonnées. Un nouveau document sera produit, qui contient tout ce que le document source a sauf pour le champ nouvellement copié.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum, float abscissa, 
    float ordinate)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | L'ancien nom de champ entièrement qualifié. |
| newFieldName | String | Le nouveau nom de champ entièrement qualifié. Si null, il sera défini comme fieldName + "~". |
| pageNum | Int32 | Le numéro de page pour contenir le nouveau champ. Si -1, le nouveau champ sera copié sur la même page que l'ancien. |
| abscissa | Single | L'abscisse du nouveau champ. Si -1, l'abscisse sera égale à l'original. |
| ordinate | Single | L'ordonnée du nouveau champ. Si -1, l'ordonnée sera égale à l'original. |

## Exemples

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//Creates copy of text field on psecond page.
formEditor.CopyInnerField("textField", "textFieldCopy", 2, 100, 200);
```

### Voir aussi

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)