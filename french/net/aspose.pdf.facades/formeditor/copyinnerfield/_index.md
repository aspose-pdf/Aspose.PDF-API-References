---
title: "FormEditor.CopyInnerField"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode FormEditor. Copie un champ existant à la même position dans le numéro de page spécifié. Un nouveau document sera créé contenant tout ce que le document source possède, sauf le champ nouvellement copié."
type: docs
weight: 150
url: /fr/net/aspose.pdf.facades/formeditor/copyinnerfield/
---
## CopyInnerField(string, string, int) {#copyinnerfield}

Copie un champ existant à la même position dans le numéro de page spécifié. Un nouveau document sera produit, contenant tout ce que le document source possède, à l'exception du champ nouvellement copié.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | L'ancien nom de champ entièrement qualifié. |
| newFieldName | String | Le nouveau nom de champ entièrement qualifié. Si null, il sera défini comme fieldName + "~". |
| pageNum | Int32 | Le numéro de page qui contiendra le nouveau champ. Si -1, le nouveau champ sera copié sur la même page que l'ancienne. |

## Exemples

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//Crée une copie du champ texte sur la deuxième page.
formEditor.CopyInnerField("textField", "textFieldCopy", 2);
```

### Voir aussi

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyInnerField(string, string, int, float, float) {#copyinnerfield_1}

Copie un champ existant à une nouvelle position spécifiée à la fois par le numéro de page et les coordonnées. Un nouveau document sera produit, contenant tout ce que le document source possède, à l'exception du champ nouvellement copié.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum, float abscissa, 
    float ordinate)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | L'ancien nom de champ entièrement qualifié. |
| newFieldName | String | Le nouveau nom de champ entièrement qualifié. Si null, il sera défini comme fieldName + "~". |
| pageNum | Int32 | Le numéro de page qui contiendra le nouveau champ. Si -1, le nouveau champ sera copié sur la même page que l'ancienne. |
| abscisse | Single | L'abscisse du nouveau champ. Si -1, l'abscisse sera égale à celle d'origine. |
| ordonnée | Single | L'ordonnée du nouveau champ. Si -1, l'ordonnée sera égale à celle d'origine. |

## Exemples

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//Crée une copie du champ texte sur la deuxième page.
formEditor.CopyInnerField("textField", "textFieldCopy", 2, 100, 200);
```

### Voir aussi

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


