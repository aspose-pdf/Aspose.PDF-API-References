---
title: FillField
second_title: Référence de l'API Aspose.PDF pour .NET
description: Remplit le champ avec la valeur spécifiée.
type: docs
weight: 160
url: /fr/net/aspose.pdf.facades/form/fillfield/
---
## FillField(string, string, bool) {#fillfield_3}

Remplit le champ avec la valeur spécifiée.

```csharp
public bool FillField(string fieldName, string value, bool fitFontSize)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| fieldName | String | Nom du champ |
| value | String | Nouvelle valeur du champ |
| fitFontSize | Boolean | Si vrai, la taille de la police dans les zones d'édition sera ajustée. |

### Return_Value

true si le champ a été trouvé et rempli avec succès.

### Voir également

* class [Form](../../form)
* espace de noms [Aspose.Pdf.Facades](../../form)
* Assemblée [Aspose.PDF](../../../)

---

## FillField(string, string) {#fillfield_2}

Remplit le champ avec une valeur valide selon un nom de champ complet. Avant de remplir les champs, les noms de chaque champ et leurs valeurs valides correspondantes doivent être connus. Le nom et les valeurs des champs sont sensibles à la casse. Veuillez noter que Aspose.Pdf.Facades ne prend en charge que les noms de champ complets et ne fonctionne pas avec les noms de champ partiels contrairement à Aspose.Pdf.Kit; Par exemple, si le champ a le nom complet "Form.Subform.TextField", vous devez spécifier le nom complet et non "Champ de texte". Vous pouvez utiliser la propriété FieldNames pour explorer les noms de champs existants et rechercher le champ requis par son nom partiel.

```csharp
public bool FillField(string fieldName, string fieldValue)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| fieldName | String | Nom du champ à remplir. |
| fieldValue | String | La valeur du champ qui doit être une valeur valide pour certains champs. |

### Return_Value

true si le champ est trouvé et rempli avec succès.

### Exemples

```csharp
Form form = new Form(TestSettings.GetInputFile("PdfForm.pdf"));
form.FillField("FirstName", "John");
form.FillField("LastName",  "Smith");
```

```csharp
//comment rechercher un champ par son nom partiel :
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("TextField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### Voir également

* class [Form](../../form)
* espace de noms [Aspose.Pdf.Facades](../../form)
* Assemblée [Aspose.PDF](../../../)

---

## FillField(string, int) {#fillfield_1}

Remplit le champ de la boîte radio avec une valeur d'index valide selon un nom de champ complet. Avant de remplir les champs, seul le nom du champ doit être connu. Bien que la valeur puisse être spécifiée par son index. Avis : ne s'applique qu'aux champs Radio Box, Combo Box et List Box. Veuillez noter qu'Aspose.Pdf.Facades ne prend en charge que les noms de champs complets et ne fonctionne pas avec les noms de champs partiels contrairement à Aspose.Pdf.Kit; Par exemple, si le champ a le nom complet "Form.Subform.ListBoxField", vous devez spécifier le nom complet et non "ListBoxField". Vous pouvez utiliser la propriété FieldNames pour explorer les noms de champs existants et rechercher le champ requis par son nom partiel.

```csharp
public bool FillField(string fieldName, int index)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| fieldName | String | Nom du champ à remplir. |
| index | Int32 | Index de l'article choisi. |

### Return_Value

true si le champ a été trouvé et rempli avec succès.

### Exemples

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("listboxField", 2);
form.FillField("comboboxField", 2);
form.FillField("radiobuttonField", 2);
```

```csharp
//comment rechercher un champ par son nom partiel :
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("ListBoxField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### Voir également

* class [Form](../../form)
* espace de noms [Aspose.Pdf.Facades](../../form)
* Assemblée [Aspose.PDF](../../../)

---

## FillField(string, bool) {#fillfield}

Remplit le champ de la case à cocher avec une valeur booléenne. Remarque : ne s'applique qu'à la case à cocher. Veuillez noter qu'Aspose.Pdf.Facades ne prend en charge que les noms de champ complets et ne fonctionne pas avec les noms de champ partiels contrairement à Aspose.Pdf .Kit; Par exemple, si le champ a le nom complet "Form.Subform.CheckBoxField", vous devez spécifier le nom complet et non "CheckBoxField". Vous pouvez utiliser la propriété FieldNames pour explorer les noms de champs existants et rechercher le champ requis par son nom partiel.

```csharp
public bool FillField(string fieldName, bool beChecked)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| fieldName | String | Nom du champ à remplir. |
| beChecked | Boolean | Un drapeau booléen : vrai signifie cocher la case, faux signifie la décocher. |

### Return_Value

true si le champ a été trouvé et rempli avec succès.

### Exemples

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("checkboxField", true);
```

```csharp
//comment rechercher un champ par son nom partiel :
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("CheckBoxField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### Voir également

* class [Form](../../form)
* espace de noms [Aspose.Pdf.Facades](../../form)
* Assemblée [Aspose.PDF](../../../)

---

## FillField(string, string[]) {#fillfield_4}

Remplir un champ avec plusieurs sélections.Remarque : uniquement pour le champ de zone de liste AcroForm.

```csharp
public void FillField(string fieldName, string[] fieldValues)
```

| Paramètre | Taper | La description |
| --- | --- | --- |
| fieldName | String | Le nom de champ complet. |
| fieldValues | String[] | Un tableau de chaînes qui contient plusieurs éléments à sélectionner. |

### Exemples

```csharp
Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf", "Form_Updated.pdf");
form.FillField("ListBox1", new String[] { "Three", "One" });
form.Save();
```

### Voir également

* class [Form](../../form)
* espace de noms [Aspose.Pdf.Facades](../../form)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
