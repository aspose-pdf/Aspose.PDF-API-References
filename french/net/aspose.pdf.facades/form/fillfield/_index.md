---
title: "Form.FillField"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode Form. Remplit le champ avec une valeur valide selon un nom de champ entièrement qualifié. Avant de remplir les champs, chaque nom de champ et sa valeur valide correspondante doivent être connus. Les noms de champs et les valeurs sont sensibles à la casse. Veuillez noter que Aspose.Pdf.Facades ne prend en charge que les noms de champs complets et ne fonctionne pas avec les noms de champs partiels, contrairement à Aspose.Pdf.Kit. Par exemple, si le champ a le nom complet Form.Subform.TextField, vous devez spécifier le nom complet et non TextField. Vous pouvez utiliser la propriété FieldNames pour explorer les noms de champs existants et rechercher le champ requis par son nom partiel"
type: docs
weight: 130
url: /fr/net/aspose.pdf.facades/form/fillfield/
---
## FillField(string, string) {#fillfield_2}

Remplit le champ avec une valeur valide selon un nom de champ entièrement qualifié. Avant de remplir les champs, le nom de chaque champ et ses valeurs valides correspondantes doivent être connus. Les noms et les valeurs des champs sont sensibles à la casse. Veuillez noter que Aspose.Pdf.Facades ne prend en charge que les noms de champs complets et ne fonctionne pas avec des noms de champs partiels, contrairement à Aspose.Pdf.Kit ; par exemple, si le champ a le nom complet "Form.Subform.TextField", vous devez spécifier le nom complet et non "TextField". Vous pouvez utiliser la propriété FieldNames pour explorer les noms de champs existants et rechercher le champ requis par son nom partiel.

```csharp
public bool FillField(string fieldName, string fieldValue)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Le nom du champ à remplir. |
| fieldValue | String | La valeur du champ qui doit être une valeur valide pour certains champs. |

### Valeur de retour

true si le champ est trouvé et rempli avec succès.

## Exemples

```csharp
Form form = new Form(TestSettings.GetInputFile("PdfForm.pdf"));
form.FillField("FirstName", "John");
form.FillField("LastName",  "Smith");
```

```csharp
//comment rechercher un champ par son nom partiel :
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

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, int) {#fillfield_1}

Remplit le champ boîte radio avec une valeur d'index valide selon un nom de champ entièrement qualifié. Avant de remplir les champs, seul le nom du champ doit être connu. La valeur peut être spécifiée par son index. Remarque : applicable uniquement aux champs Boîte radio, Boîte combinée et Boîte de liste. Veuillez noter que Aspose.Pdf.Facades ne prend en charge que les noms de champs complets et ne fonctionne pas avec des noms de champs partiels, contrairement à Aspose.Pdf.Kit ; par exemple, si le champ a le nom complet "Form.Subform.ListBoxField", vous devez spécifier le nom complet et non "ListBoxField". Vous pouvez utiliser la propriété FieldNames pour explorer les noms de champs existants et rechercher le champ requis par son nom partiel.

```csharp
public bool FillField(string fieldName, int index)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Nom du champ à remplir. |
| index | Int32 | Index de l'élément choisi. |

### Valeur de retour

true si le champ a été trouvé et rempli avec succès.

## Exemples

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("listboxField", 2);
form.FillField("comboboxField", 2);
form.FillField("radiobuttonField", 2);
```

```csharp
//comment rechercher un champ par son nom partiel :
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

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, bool) {#fillfield}

Remplit le champ case à cocher avec une valeur booléenne. Remarque : applicable uniquement aux cases à cocher. Veuillez noter que Aspose.Pdf.Facades ne prend en charge que les noms de champs complets et ne fonctionne pas avec des noms de champs partiels, contrairement à Aspose.Pdf.Kit ; par exemple, si le champ a le nom complet "Form.Subform.CheckBoxField", vous devez spécifier le nom complet et non "CheckBoxField". Vous pouvez utiliser la propriété FieldNames pour explorer les noms de champs existants et rechercher le champ requis par son nom partiel.

```csharp
public bool FillField(string fieldName, bool beChecked)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Le nom du champ à remplir. |
| beChecked | Boolean | Un drapeau booléen : true signifie cocher la case, tandis que false la décoche. |

### Valeur de retour

true si le champ a été trouvé et rempli avec succès.

## Exemples

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("checkboxField", true);
```

```csharp
//comment rechercher un champ par son nom partiel :
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

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, string[]) {#fillfield_4}

Remplit un champ avec plusieurs sélections. Remarque : uniquement pour le champ Boîte de liste AcroForm.

```csharp
public void FillField(string fieldName, string[] fieldValues)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Le nom complet du champ. |
| fieldValues | String[] | Un tableau de chaînes contenant plusieurs éléments à sélectionner. |

## Exemples

```csharp
Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf", "Form_Updated.pdf");
form.FillField("ListBox1", new String[] { "Three", "One" });
form.Save();
```

### Voir aussi

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
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
| valeur | String | Nouvelle valeur du champ |
| fitFontSize | Boolean | Si vrai, la taille de police dans les zones de saisie sera adaptée. |

### Valeur de retour

true si le champ a été trouvé et rempli avec succès.

### Voir aussi

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


