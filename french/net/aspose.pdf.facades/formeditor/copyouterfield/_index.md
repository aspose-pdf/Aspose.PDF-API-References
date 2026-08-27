---
title: "FormEditor.CopyOuterField"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode FormEditor. Copie un champ existant d'un document PDF à un autre document avec le numéro de page et les coordonnées d'origine. Remarque : uniquement pour les champs AcroForm, à l'exclusion des radio box"
type: docs
weight: 160
url: /fr/net/aspose.pdf.facades/formeditor/copyouterfield/
---
## CopyOuterField(string, string) {#copyouterfield}

Copie un champ existant d'un document PDF à un autre document avec le numéro de page et les coordonnées d'origine. Remarque : uniquement pour les champs AcroForm (excluant les boutons radio).

```csharp
public void CopyOuterField(string srcFileName, string fieldName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| srcFileName | String | Le nom du document PDF qui contient le champ à copier. |
| fieldName | String | Le nom complet original du champ. |

## Exemples

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
//copie le champ texte de source.pdf vers PdfForm.pdf
formEditor.CopyOuterField("source.pdf", "textField");
formEditor.Save();
```

### Voir aussi

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int) {#copyouterfield_1}

Copie un champ existant d'un document PDF à un autre document avec le numéro de page spécifié et les coordonnées d'origine. Remarque : uniquement pour les champs AcroForm (excluant les boutons radio).

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| srcFileName | String | Le nom du document PDF qui contient le champ à copier. |
| fieldName | String | Le nom complet original du champ. |
| pageNum | Int32 | Le numéro de page qui contiendra le nouveau champ. Si -1, le nouveau champ sera copié sur la même page que l'ancienne. |

## Exemples

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField", 2);
formEditor.Save();
```

### Voir aussi

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int, float, float) {#copyouterfield_2}

Copie un champ existant d'un document PDF à un autre document avec le numéro de page et les coordonnées spécifiés. Remarque : uniquement pour les champs AcroForm (excluant les boutons radio).

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum, float abscissa, 
    float ordinate)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| srcFileName | String | Le nom du document PDF qui contient le champ à copier. |
| fieldName | String | Le nom complet original du champ. |
| pageNum | Int32 | Le numéro de page qui contiendra le nouveau champ. Si -1, le nouveau champ sera copié sur la même page que l'ancienne. |
| abscisse | Single | L'abscisse du nouveau champ. Si -1, l'abscisse sera égale à celle d'origine. |
| ordonnée | Single | L'ordonnée du nouveau champ. Si -1, l'ordonnée sera égale à celle d'origine. |

## Exemples

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField" , 2, 100, 200);
```

### Voir aussi

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


