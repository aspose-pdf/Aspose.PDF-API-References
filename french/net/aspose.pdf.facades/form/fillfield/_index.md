---
title: Form.FillField
second_title: Aspose.PDF for .NET API Reference
description: Méthode Form. Remplit le champ avec une valeur valide selon un nom de champ entièrement qualifié. Avant de remplir les champs, tous les noms de champs et leurs valeurs valides correspondantes doivent être connus. Les noms de champs et les valeurs sont sensibles à la casse. Veuillez noter qu'Aspose.Pdf.Facades ne prend en charge que les noms de champs complets et ne fonctionne pas avec des noms de champs partiels, contrairement à Aspose.Pdf.Kit. Par exemple, si le champ a le nom complet Form.Subform.TextField, vous devez spécifier le nom complet et non TextField. Vous pouvez utiliser la propriété FieldNames pour explorer les noms de champs existants et rechercher le champ requis par son nom partiel.
type: docs
weight: 130
url: /fr/net/aspose.pdf.facades/form/fillfield/
---
## FillField(string, string, bool) {#fillfield_3}

Remplit le champ avec la valeur spécifiée.

```csharp
public bool FillField(string fieldName, string value, bool fitFontSize)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Nom du champ |
| value | String | Nouvelle valeur du champ |
| fitFontSize | Boolean | Si vrai, la taille de police dans les zones de texte sera ajustée. |

### Valeur de retour

vrai si le champ a été trouvé et rempli avec succès.

### Voir aussi

* classe [Form](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, string) {#fillfield_2}

Remplit le champ avec une valeur valide selon un nom de champ entièrement qualifié. Avant de remplir les champs, tous les noms de champs et leurs valeurs valides correspondantes doivent être connus. Les noms de champs et les valeurs sont sensibles à la casse. Veuillez noter qu'Aspose.Pdf.Facades ne prend en charge que les noms de champs complets et ne fonctionne pas avec des noms de champs partiels, contrairement à Aspose.Pdf.Kit ; Par exemple, si le champ a le nom complet "Form.Subform.TextField", vous devez spécifier le nom complet et non "TextField". Vous pouvez utiliser la propriété FieldNames pour explorer les noms de champs existants et rechercher le champ requis par son nom partiel.

```csharp
public bool FillField(string fieldName, string fieldValue)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Le nom du champ à remplir. |
| fieldValue | String | La valeur du champ qui doit être une valeur valide pour certains champs. |

### Valeur de retour

vrai si le champ est trouvé et rempli avec succès.

## Exemples

```csharp
Form form = new Form(TestSettings.GetInputFile("PdfForm.pdf"));
form.FillField("FirstName", "John");
form.FillField("LastName",  "Smith");
```

```csharp
//how to search field by its partial name:
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("TextField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### Voir aussi

* classe [Form](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, int) {#fillfield_1}

Remplit le champ de case à cocher avec une valeur d'index valide selon un nom de champ entièrement qualifié. Avant de remplir les champs, seul le nom du champ doit être connu. Alors que la valeur peut être spécifiée par son index. Remarque : S'applique uniquement aux champs de case à cocher, de liste déroulante et de liste. Veuillez noter qu'Aspose.Pdf.Facades ne prend en charge que les noms de champs complets et ne fonctionne pas avec des noms de champs partiels, contrairement à Aspose.Pdf.Kit ; Par exemple, si le champ a le nom complet "Form.Subform.ListBoxField", vous devez spécifier le nom complet et non "ListBoxField". Vous pouvez utiliser la propriété FieldNames pour explorer les noms de champs existants et rechercher le champ requis par son nom partiel.

```csharp
public bool FillField(string fieldName, int index)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Nom du champ à remplir. |
| index | Int32 | Index de l'élément choisi. |

### Valeur de retour

vrai si le champ a été trouvé et rempli avec succès.

## Exemples

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("listboxField", 2);
form.FillField("comboboxField", 2);
form.FillField("radiobuttonField", 2);
```

```csharp
//how to search field by its partial name:
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("ListBoxField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### Voir aussi

* classe [Form](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, bool) {#fillfield}

Remplit le champ de case à cocher avec une valeur booléenne. Remarque : S'applique uniquement aux cases à cocher. Veuillez noter qu'Aspose.Pdf.Facades ne prend en charge que les noms de champs complets et ne fonctionne pas avec des noms de champs partiels, contrairement à Aspose.Pdf.Kit ; Par exemple, si le champ a le nom complet "Form.Subform.CheckBoxField", vous devez spécifier le nom complet et non "CheckBoxField". Vous pouvez utiliser la propriété FieldNames pour explorer les noms de champs existants et rechercher le champ requis par son nom partiel.

```csharp
public bool FillField(string fieldName, bool beChecked)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Le nom du champ à remplir. |
| beChecked | Boolean | Un indicateur booléen : vrai signifie cocher la case, tandis que faux signifie la décocher. |

### Valeur de retour

vrai si le champ a été trouvé et rempli avec succès.

## Exemples

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("checkboxField", true);
```

```csharp
//how to search field by its partial name:
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("CheckBoxField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### Voir aussi

* classe [Form](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, string[]) {#fillfield_4}

Remplit un champ avec plusieurs sélections. Remarque : uniquement pour le champ de liste AcroForm.

```csharp
public void FillField(string fieldName, string[] fieldValues)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Le nom de champ entièrement qualifié. |
| fieldValues | String[] | Un tableau de chaînes contenant plusieurs éléments à sélectionner. |

## Exemples

```csharp
Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf", "Form_Updated.pdf");
form.FillField("ListBox1", new String[] { "Three", "One" });
form.Save();
```

### Voir aussi

* classe [Form](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

--- 

## FillField(string, string, bool) {#fillfield_3}

Remplit le champ avec la valeur spécifiée.

```csharp
public bool FillField(string fieldName, string value, bool fitFontSize)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Nom du champ |
| value | String | Nouvelle valeur du champ |
| fitFontSize | Boolean | Si vrai, la taille de police dans les zones de texte sera ajustée. |

### Valeur de retour

vrai si le champ a été trouvé et rempli avec succès.

### Voir aussi

* classe [Form](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)